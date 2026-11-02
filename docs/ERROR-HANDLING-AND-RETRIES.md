Act as an expert Automation Architect and Reliability Engineer. I need you to generate a comprehensive, production-ready `ERROR-HANDLING-AND-RETRIES.md` file in Markdown format for my workflow automation project (e.g., n8n, Make.com, or custom event-driven pipelines).

Here are the project details:
- Project Name: [Insert Project Name, e.g., Automated CRM Lead Sync Pipeline]
- Automation Tool / Framework: [e.g., n8n, Apache Airflow, Python Celery]
- Critical Failure Points: [e.g., Third-party API timeouts, database deadlocks, rate limiting]

Please structure the document with the following professional sections:
1. Error Handling Philosophy & Strategy (Overview of resilience, graceful degradation, and fail-safes)
2. Retry Policies & Backoff Strategies (Configuring retry counts, interval delays, and exponential backoff for transient errors)
3. Error Trigger & Catch Nodes Implementation (How the platform catches node failures or uncaught exceptions)
4. Alerting & Incident Notification Sub-System (Routing alerts via Slack, Telegram, or Email when a critical workflow crashes)
5. Dead Letter Queue (DLQ) & Manual Recovery Procedures (How failed payloads are stored for manual inspection or replay)

Ensure the tone is technical, highly structured, and ready to be committed directly into the project repository.
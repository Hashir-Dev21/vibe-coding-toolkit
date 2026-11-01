Act as an expert Database Architect and Senior Backend Engineer. I need you to generate a comprehensive, production-ready Database Schema and Data Models Document (`DATABASE-SCHEMA.md`) in Markdown format for my project.

Here are the core project details:
- Project Name: [Insert Project Name, e.g., Football Academy Management System]
- Database Engine: [e.g., PostgreSQL / Supabase / MySQL]
- Core Entities / Modules: [e.g., Users, Teams, Players, Matches, Attendance, Payments]

Please structure the document with the following professional sections:
1. Database Overview & Design Principles (e.g., UUID primary keys, normalization standards, timestamps)
2. Entity Relationship Diagram (ERD) using a clean Mermaid.js `erDiagram` showing tables, fields, and foreign-key relations
3. Detailed Table Specifications:
   - For each table (e.g., `users`, `teams`, `matches`), provide a markdown table detailing: Column Name, Data Type, Constraints (PK, FK, Unique, NOT NULL), and Description.
4. Indexing & Query Optimization Strategy (List out specific indexes like `CREATE INDEX` for high-frequency search/filter columns)
5. Database Security & Policies (Brief mention of Row Level Security or access constraints if applicable)

Ensure the tone is highly technical, precise, structured, and ready to be placed directly into a professional GitHub repository.
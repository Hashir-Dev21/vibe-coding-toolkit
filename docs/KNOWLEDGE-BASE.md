Act as an expert RAG (Retrieval-Augmented Generation) Architect and Data Engineer. I need you to generate a comprehensive, production-ready `KNOWLEDGE-BASE.md` file in Markdown format for my AI Agent project's data pipeline.

Here are the project details:
- Agent Name: [Insert Agent Name]
- Data Sources: [e.g., Markdown files, PDF manuals, Database records, API docs]
- Vector Database / Search Engine: [e.g., Supabase pgvector, Pinecone, Chroma]

Please structure the document with the following professional sections:
1. Knowledge Pipeline Overview (Ingestion -> Chunking -> Embedding -> Storage -> Retrieval)
2. Ingestion & Document Processing Strategy (File parsers, cleaning, metadata tagging)
3. Chunking & Embedding Configuration (Chunk size, overlap, embedding model details)
4. Retrieval & Hybrid Search Strategy (Vector similarity search + Keyword BM25 search, re-ranking mechanisms)
5. Data Sync & Update Routines (How documents are refreshed when source data changes)

Ensure the tone is highly technical, detailed, and structured for backend data implementation.
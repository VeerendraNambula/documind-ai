# DocuMind AI

AI-powered document intelligence platform using retrieval-augmented generation (RAG), vector search, and grounded question answering.

## Project status

🚧 Under active development.

## Planned capabilities

- Upload and manage multiple PDF documents
- Extract and index document content
- Ask questions across uploaded documents
- Get evidence-grounded answers with page-level citations
- Open cited pages to verify answers
- Preserve conversation history
- Abstain when the documents do not contain sufficient evidence

## Planned architecture

| Component | Technology |
|---|---|
| Frontend | Next.js, TypeScript, Tailwind CSS |
| Backend API | Python, FastAPI |
| Database | PostgreSQL |
| Vector search | pgvector |
| PDF extraction | PyMuPDF |
| LLM integration | Provider-agnostic adapter (Gemini initially) |
| Testing | Pytest, Playwright |
| Deployment | Docker |

## Repository layout

```text
documind-ai/
├── frontend/   # Next.js application
├── backend/    # FastAPI application
├── docs/       # Architecture, requirements, and API documentation
├── tests/      # Integration and end-to-end tests
├── .gitignore
└── README.md
```

## Development

Setup instructions will be added as the application components are scaffolded.

## Quality goals

The project will include an evaluation dataset and measurable checks for retrieval quality, answer faithfulness, citation accuracy, relevance, latency, and cost. Evaluation results will be reported only after they are measured.

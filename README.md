# gcp-data-dude-tool
gcp-data-dude-tool

## 📁 Projektstruktur

```text
.
├─ backend
│  ├─ app
│  │  ├─ __init__.py          # optional, falls du Packages nutzen willst
│  │  ├─ main.py              # FastAPI-Entry-Point
│  │  ├─ deps.py              # Auth-, BQ-, Gemini-Utilities
│  │  └─ models.py            # Pydantic-Schemas
│  ├─ requirements.txt
│  ├─ Dockerfile              # Production Image (distroless)
│  └─ dev.Dockerfile          # Hot-Reload Image für Codespaces
│
├─ frontend
│  ├─ src
│  │  ├─ App.tsx
│  │  ├─ index.css
│  │  └─ components
│  │     ├─ Chat.tsx
│  │     ├─ DataTable.tsx
│  │     └─ Chart.tsx
│  ├─ index.html
│  ├─ vite.config.ts
│  └─ package.json
│
├─ .devcontainer
│  └─ devcontainer.json       # Codespaces-Config (Python + Node)
│
├─ .github
│  └─ workflows
│     └─ build.yml            # CI/CD → Cloud Run
│
├─ .gitignore
└─ README.md                  # Dieses Dokument


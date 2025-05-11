# gcp-data-dude-tool
gcp-data-dude-tool

.
├─ backend/
│  ├─ app/
│  │  ├─ main.py          # FastAPI-Entry-Point
│  │  ├─ deps.py          # Auth-, BQ- & Gemini-Utils (Platzhalter)
│  │  └─ models.py        # Pydantic-Schemas
│  ├─ requirements.txt
│  ├─ Dockerfile
│  └─ dev.Dockerfile      # schlanker Image für Codespaces
├─ frontend/
│  ├─ src/
│  │  ├─ App.tsx
│  │  ├─ components/
│  │  │  ├─ Chat.tsx
│  │  │  ├─ DataTable.tsx
│  │  │  └─ Chart.tsx
│  ├─ index.html
│  ├─ vite.config.ts
│  └─ package.json
├─ .github/
│  └─ workflows/
│     ├─ build.yml        # CI (Docker build + Cloud Run deploy)
└─ README.md

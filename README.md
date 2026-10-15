<div align="center">

# 🏙️ URBANMIND
### *AI-Powered Urban Spatial Intelligence Platform & Planning Studio*

<p align="center">
  <img src="https://img.shields.io/badge/REACT-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/EXPRESS-4.x-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/VITE-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/MAPLIBRE-3.x-396B9E?style=for-the-badge&logo=maplibre&logoColor=white" />
  <img src="https://img.shields.io/badge/LITELLM_RAG-AI_POWERED-8A2BE2?style=for-the-badge" />
</p>

<p align="center">
  <b>A comprehensive, enterprise-grade urban analytics superapp integrating real-time geospatial mapping, deep academic research agents, automated spatial planning synthesis, and interactive diagram generators.</b>
</p>

---

</div>

## 🌟 Core Modules & Architecture

```
+-----------------------------------------------------------------------------------------+
|                                  URBANMIND SUPERAPP                                     |
+-----------------------------------------------------------------------------------------+
| FRONTEND WORKSPACES                                                                     |
| • Dashboard: Regional KPIs, land-use distribution & urban morphology metrics            |
| • Maps Studio: Multi-layer GeoJSON inspector, spatial buffers & thematic styling        |
| • Planning Studio: Automated policy briefs, zoning regulations & statutory templates   |
| • Research Studio: Deep literature synthesis, citation tracker & academic RAG           |
| • Document Studio: Real-time visual document editor with Mermaid & Kroki diagrams       |
+-----------------------------------------------------------------------------------------+
                                           ▲
                                           │ Unified REST API
                                           ▼
+-----------------------------------------------------------------------------------------+
| BACKEND ENGINE & AI INFRASTRUCTURE                                                      |
| • Unified AI Service: Multi-model routing via LiteLLM & OpenRouter                     |
| • Deep Research Engine: Autonomous search, synthesis & citation extraction              |
| • Geospatial Document Parser: Multi-format ingestion (PDF, DOCX, GeoJSON, Shapefiles)  |
+-----------------------------------------------------------------------------------------+
```

---

## 🚀 Key Features

### 1. 🗺️ Advanced Spatial Mapping Studio
- **Multi-Layer Geoparsing**: Seamlessly drag & drop GeoJSON, Shapefile, and CSV datasets.
- **Dynamic Layer Styling**: Categorized choropleths, graduated buffers, and live attribute inspection.
- **Spatial Measurement**: On-the-fly area (Hectares/m²) and perimeter distance calculations.

### 2. 🧠 Deep Research & Literature Agent
- Autonomous agent scouring academic papers, regional masterplans (RTRW/RDTR), and regulatory frameworks.
- Grounded citations with zero epistemic hallucination.
- Evidence-backed synthesis for urban resilience and climate vulnerability.

### 3. 📊 Visual Builder & Diagram Engine
- Live rendering of **Mermaid.js** and **Kroki** architectural graphs, zoning decision trees, and workflow pipelines.
- Instant export to SVG, PNG, and formatted policy briefs.

### 4. 📄 Regulatory Planning Document Studio
- Instant generation of formatted policy documents adhering to national planning standards (Permen ATR/BPN & Permen PU).
- Structured Markdown, DOCX, and PDF publishing pipelines.

---

## 🛠️ Installation & Getting Started

### Prerequisites
- **Node.js** >= 18.0.0 or **Bun** >= 1.1
- **npm** or **pnpm**
- Active AI API Key (OpenAI, Anthropic, or OpenRouter)

### 1. Clone & Configure
```bash
git clone https://github.com/hilmithehacker/URBANMIND.git
cd URBANMIND

# Copy environment variables
cp .env.example .env
```

### 2. Launch Backend Service
```bash
cd backend
npm install
npm run dev
```
Backend API will listen on `http://localhost:5000` (or configured port).

### 3. Launch Frontend Application
```bash
cd ../frontend
npm install
npm run dev
```
Visit `http://localhost:5173` to access the full URBANMIND workspace.

---

## 📂 Repository Layout

```
URBANMIND/
├── frontend/                  # React 18 + TypeScript + Vite Workspace
│   ├── src/
│   │   ├── components/        # UI primitives, MermaidBlock, KrokiBlock, Layout
│   │   ├── pages/             # Dashboard, Maps, Planning, Research, DocumentStudio
│   │   ├── services/          # API gateways & spatial utility pipelines
│   │   └── store/             # Global state management
│   └── vite.config.ts         # Bundler configuration
│
├── backend/                   # Node.js + Express + TypeScript Core
│   └── src/
│       ├── ai/                # Unified AI provider & LiteLLM integrations
│       ├── rag/               # Vector embeddings & document retrieval
│       ├── routes/            # REST endpoints (data, files, research, planning)
│       └── services/          # Deep research & document parser microservices
│
├── .env.example               # Template environment configuration
└── README.md                  # System overview & developer guide
```

---

<div align="center">
  <b>Developed by <a href="https://github.com/hilmithehacker">@hilmithehacker</a></b><br/>
  <i>Empowering Next-Generation Autonomous Urban Planning.</i>
</div>

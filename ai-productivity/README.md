# AI Productivity Tools

LLM-powered automation tools that accelerate knowledge work and business processes.

---

## MasterLister
**Repo:** [bewayo2/masterlister](https://github.com/bewayo2/masterlister) · `JavaScript` · `Private`

Multi-user collaborative inventory counter using AI vision. Users photograph items from multiple angles; GPT-5.1 Vision extracts names, quantities, and details automatically.

### What it does
- Multi-angle camera capture for better AI recognition accuracy
- **GPT-5.1 Vision** (Responses API) extracts item details from photos
- Real-time multi-user collaboration via Firebase live sync
- Location-based organisation within counts
- Shared account-level item master list for consistent naming
- CSV export at any point

### Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React 18 · Vite |
| Backend/DB | Firebase (Auth + Firestore) |
| AI | OpenAI GPT-5.1 Vision (Responses API) |
| Camera | react-webcam |
| Export | papaparse (CSV) |

---

## Strategic Blueprint GPTs
**Repo:** [bewayo2/StrategicBlueprintGPTs](https://github.com/bewayo2/StrategicBlueprintGPTs) · `Python` · `Private`

Multi-client pipeline that processes business documents (DOCX/PDF) into structured JSON knowledge bases ready to power chatbots.

### What it does
- Supports multiple isolated clients, each with their own data, configs, prompts, and outputs
- Extracts and structures content from DOCX/PDF into sections and summaries
- Produces `knowledge_base.json` per client for direct chatbot integration
- Configurable per-client prompts (summarisation, Q&A, tagging, etc.)

### Tech Stack
| Layer | Technology |
|-------|-----------|
| Language | Python |
| AI | OpenAI GPT (LLM pipeline) |
| Input formats | DOCX · PDF |
| Output | Structured JSON knowledge base |

---

## AI Hiring Tool
**Repo:** [bewayo2/AIhiringtool](https://github.com/bewayo2/AIhiringtool) · `Python` · `Public`

AI-assisted candidate screening that matches resumes against role requirements and generates structured assessments, reducing manual review time in early hiring stages.

**Stack:** Python · AI/LLM

---

## Audio Transcription App
**Repo:** [bewayo2/audiotransriptionapp](https://github.com/bewayo2/audiotransriptionapp) · `Python` · `Public`

Lightweight utility to convert audio files to text using OpenAI Whisper. Focused, minimal, runs locally.

**Stack:** Python · OpenAI Whisper

---

## Ref Extractor
**Repo:** [bewayo2/RefExtractor](https://github.com/bewayo2/RefExtractor) · `HTML` · `Public`

Browser-based tool for researchers to extract structured citation data from academic paper DOIs and URLs — no server, runs entirely in the browser.

**Stack:** HTML · JavaScript

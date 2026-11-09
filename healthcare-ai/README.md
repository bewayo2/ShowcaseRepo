# Healthcare AI Projects

Source-checked clinical AI prototypes and supporting applications.

## WoundCareAI
**Repository:** [bewayo2/WoundCareAI](https://github.com/bewayo2/WoundCareAI) · **Status:** Research prototype; private

Built for the Google Gemma 3n Impact Challenge. The Streamlit interface accepts wound photos and notes, produces structured AI-generated assessments, and exports text reports. Local/offline operation is described by the source README but has not been independently tested. Medical decisions still require a qualified clinician.

**Technology:** Python, Streamlit, Gemma 3n, PyTorch

---

## ScanAuditor
**Repository:** [bewayo2/scanauditor](https://github.com/bewayo2/scanauditor) · **Status:** Active desktop QA tool; public

Audits scanned medical-record PDFs page by page. Current defaults use local Ollama Qwen3 vision and text models. JavaScript rules check patient identifiers, dates, quality and complete page-processing coverage. Resumable folder audits, SQLite review workspace, and optional authorized OpenAI vision are documented. The tool cannot independently establish completeness against original paper records.

**Technology:** Electron/JavaScript, Python, Ollama Qwen3, SQLite

---

## BHS Virtual Health Assistant
**Repository:** [bewayo2/BHSVirtualHealthAssistant](https://github.com/bewayo2/BHSVirtualHealthAssistant) · **Status:** Prototype; public

FastAPI and web frontend proof of concept. The backend README calls the concept JAMCare and uses GPT-4o-mini for Jamaica-focused general health information and escalation guidance. It is not an independently approved medical advice service.

**Technology:** Python, FastAPI, OpenAI API, web frontend

---

## BHS Discharge Summary Generator
**Repository:** [bewayo2/BHSDischargeSummaryGenerator](https://github.com/bewayo2/BHSDischargeSummaryGenerator) · **Status:** Prototype; public

An HTML interface and Express backend generate a draft summary from supplied clinical notes using an OpenAI chat endpoint. The source references an older GPT-4 preview model; compatibility and clinical quality need testing. A clinician must review outputs.

**Technology:** HTML, JavaScript, Node.js/Express, OpenAI API

---

## Sepsis Predictor
**Repository:** [bewayo2/Sepsispredictor](https://github.com/bewayo2/Sepsispredictor) · **Status:** Research/educational demo; public

A Streamlit dashboard and saved machine-learning model examine sepsis-related risk factors including lactate, temperature and mean arterial pressure. No prospective clinical validation or clinical deployment is established by the repository.

**Technology:** Python, scikit-learn, Streamlit

---

## MediScripts
**Repository:** [bewayo2/MediScripts](https://github.com/bewayo2/MediScripts) · **Status:** Name-only placeholder; private

Contains a minimal README with the repository name and no verifiable implementation. No product claims are made.



---

*Source-checked 9 November 2026. Descriptions do not assert clinical validation, institutional adoption or production readiness unless separately evidenced.*

# Data & Research Tools

Visualisation and analysis tools for clinical and research data.

---

## AUROC Demo
**Repo:** [bewayo2/AUROCdemo](https://github.com/bewayo2/AUROCdemo) · `JavaScript` · `Public`

Interactive educational web tool demonstrating the effects of sensitivity on AUROC curves and temperature scaling on calibration curves — useful for understanding ML model evaluation in clinical contexts.

### What it shows
**AUROC Panel:**
- Three curves: Perfect (AUC 1.0), Good (AUC 0.75), Random (AUC 0.5)
- Sensitivity slider (0.1–0.9) moves operating point markers along each curve in real time
- Diamond markers show current operating point per curve

**Calibration Panel:**
- Temperature scaling slider (0.1–3.0) adjusts model confidence calibration
- Compares original vs. temperature-scaled predictions
- Perfect calibration diagonal line for reference

**Stack:** JavaScript · Interactive Visualisation (browser-based)

---

## BHS Flow Map Generator
**Repo:** [bewayo2/BHSFlowMapGen](https://github.com/bewayo2/BHSFlowMapGen) · `HTML` · `Public`

Web app that converts free-text process descriptions into rendered Graphviz diagrams using GPT-4. Built for BHS clinical and operations teams.

### What it does
- Sends text to **GPT-4**, which returns a structured process table
- Renders the table as a **Graphviz** diagram (DOT language)
- Supports two diagram types:
  - Process Flow: Start → Process → Decision → Subprocess → End notation
  - Swimlane: Organised by function and phase
- Export as SVG or DOT file
- Single-file frontend (all HTML/CSS/JS in one file) — easy to deploy anywhere

### Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | HTML · CSS · JavaScript (single file) |
| Backend | Python |
| AI | OpenAI GPT-4 |
| Rendering | Graphviz |

---

## Ref Extractor
**Repo:** [bewayo2/RefExtractor](https://github.com/bewayo2/RefExtractor) · `HTML` · `Public`

Browser-based tool for researchers to extract and format structured citation data from academic paper DOIs and URLs. Runs entirely client-side — no server required.

**Stack:** HTML · JavaScript

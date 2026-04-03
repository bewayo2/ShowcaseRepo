# Healthcare AI Projects

AI-powered tools applied directly to clinical workflows, diagnostics, and patient care.

---

## WoundCareAI
**Repo:** [bewayo2/WoundCareAI](https://github.com/bewayo2/WoundCareAI) · `Python` · `Private`

Built for the **Google Gemma 3n Impact Challenge**. A mobile-first web application that uses Google's Gemma 3n multimodal AI to provide comprehensive wound assessment without internet access — designed for healthcare professionals in remote areas.

### What it does
- Captures wound photos via device camera
- Records voice notes alongside images
- Analyses wounds across 15 medical parameters: location, size, shape, wound bed tissue, edges, depth, exudate, surrounding skin, infection signs, pain severity, and more
- Stores up to 10 previous reports for progress tracking
- Exports analysis reports as text files

### Tech Stack
| Layer | Technology |
|-------|-----------|
| AI Model | Google Gemma 3n (multimodal) |
| Language | Python |
| Design | Mobile-first, works offline |

---

## ScanAuditor
**Repo:** [bewayo2/scanauditor](https://github.com/bewayo2/scanauditor) · `JavaScript` · `Public`

AI audit tool for scanned handwritten medical records. Identifies data integrity issues, multi-patient file mixups, and date mismatches across entire document sets.

### What it does
- Runs **PaddleOCR** on all pages of scanned documents to extract handwritten text
- Uses **Gemma 3n 4b** to analyse text for patient names, hospital numbers (5–6 digit), date inconsistencies
- Flags multi-patient documents and data integrity violations
- Processes entire document batches, not page-by-page

### Tech Stack
| Layer | Technology |
|-------|-----------|
| OCR | PaddleOCR |
| AI Analysis | Google Gemma 3n 4b |
| Language | JavaScript |

---

## BHS Virtual Health Assistant
**Repo:** [bewayo2/BHSVirtualHealthAssistant](https://github.com/bewayo2/BHSVirtualHealthAssistant) · `Python` · `Public`

Conversational AI chatbot demo for Bright Health Solutions, enabling patient-facing interactions for common health queries.

**Stack:** Python

---

## BHS Discharge Summary Generator
**Repo:** [bewayo2/BHSDischargeSummaryGenerator](https://github.com/bewayo2/BHSDischargeSummaryGenerator) · `HTML/JS` · `Public`

Web-based tool that generates structured clinical discharge summaries for BHS clinical staff.

**Stack:** HTML · JavaScript

---

## Sepsis Predictor
**Repo:** [bewayo2/Sepsispredictor](https://github.com/bewayo2/Sepsispredictor) · `Python` · `Public`

Machine learning model for early sepsis risk detection from clinical data, enabling earlier clinical intervention.

**Stack:** Python · Machine Learning

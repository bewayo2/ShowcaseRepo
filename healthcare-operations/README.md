# Healthcare Operations Projects

Systems for managing clinical workflows, inventory, equipment, and process documentation.

---

## RoomManager (Procedure Manager)
**Repo:** [bewayo2/RoomManager](https://github.com/bewayo2/RoomManager) · `TypeScript` · `Private`

Full-stack inventory and procedure management system for healthcare clinics. Tracks medical supplies from purchase to procedure usage with full audit trails.

### What it does
- **Item Master**: Centralised product definitions with reorder points, safety stock, and vendor preferences
- **FEFO Stock Rotation**: First-Expiry-First-Out logic to minimise waste and ensure compliance
- **Purchase Orders**: Create, receive, and track POs end-to-end
- **Procedure Tracking**: Logs item consumption per procedure with full audit trail
- **Reporting**: Low stock alerts, usage reports, expiry tracking, variance analysis
- **AI Features** *(coming)*: Label scanning for batch/expiry extraction, invoice matching

### Tech Stack
| Layer | Technology |
|-------|-----------|
| Backend | Node.js · TypeScript · Express |
| Frontend | React · TypeScript · Vite · React Router |
| Database | Firebase Firestore |
| Validation | Zod |

---

## Scan Progress Tracker
**Repo:** [bewayo2/ScanProgressTracker](https://github.com/bewayo2/ScanProgressTracker) · `Python` · `Private`

Flask app for monitoring digitisation progress of paper medical records. Analyses entire PDF folder trees and reports on scanning throughput.

### What it does
- Recursively scans all PDFs in a folder and subfolders
- Extracts creation dates and page counts from metadata
- Generates 7 chart visualisations: cumulative output, weekly comparisons, shift splits (morning/afternoon), peak rates, efficiency metrics, and weekend-adjusted completion forecasts
- Exports complete reports to PDF

### Tech Stack
| Layer | Technology |
|-------|-----------|
| Backend | Python · Flask |
| Charts | Chart.js |
| Export | PDF generation |

---

## SJH Equipment Commissioning
**Repo:** [bewayo2/SJHEquipmentCommissioning](https://github.com/bewayo2/SJHEquipmentCommissioning) · `JavaScript` · `Private`

React application for tracking equipment commissioning status at St John of God Hospital. Built with React + Vite.

**Stack:** React · Vite · JavaScript

---

## SJH Swimlane Generator
**Repo:** [bewayo2/SJHSwimlaneGenerator](https://github.com/bewayo2/SJHSwimlaneGenerator) · `HTML` · `Public`

AI-powered tool for generating swimlane and process flow diagrams from text descriptions. Built for SJH clinical and operations teams to document workflows.

**Stack:** HTML · JavaScript · AI

---

## AI OCR Sorter
**Repo:** [bewayo2/AIOCRSorter](https://github.com/bewayo2/AIOCRSorter) · `Python` · `Public`

Automatically classifies and sorts large batches of scanned documents using OCR and AI, eliminating manual document routing.

**Stack:** Python · OCR · AI Classification

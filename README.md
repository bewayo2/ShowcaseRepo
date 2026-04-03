# bewayo2 — Project Showcase

A portfolio of software projects built by [@bewayo2](https://github.com/bewayo2), spanning AI-powered healthcare tools, clinical operations systems, productivity automation, and EMR platforms.

---

## Categories

| # | Category | Projects |
|---|----------|----------|
| 1 | [Healthcare AI](#-healthcare-ai) | WoundCareAI, ScanAuditor, BHS Virtual Health Assistant, Sepsis Predictor, BHS Discharge Summary Generator |
| 2 | [Healthcare Operations](#-healthcare-operations) | RoomManager, Scan Progress Tracker, SJH Equipment Commissioning, SJH Swimlane Generator, AI OCR Sorter |
| 3 | [AI Productivity Tools](#-ai-productivity-tools) | MasterLister, Strategic Blueprint GPTs, AI Hiring Tool, Audio Transcription App, Ref Extractor |
| 4 | [Marketing & Content](#-marketing--content) | Caption Generator, Keyword Generator, Blog Outline & SEO Generator, Training Mindmaps |
| 5 | [EMR & Practice Management](#-emr--practice-management) | Paradyme (OpenEMR Fork), Paradyme Aide, EMR Select |
| 6 | [Goal & Project Management](#-goal--project-management) | PG Annie, Settle App |
| 7 | [Data & Research](#-data--research) | AUROC Demo, BHS Flow Map Generator, Ref Extractor |

---

## Healthcare AI

Tools that apply AI/ML directly to clinical workflows, diagnostics, and patient care.

### [WoundCareAI](https://github.com/bewayo2/WoundCareAI) `Python` `Private`
> AI-powered wound analysis for healthcare professionals and remote areas.

Built for the **Google Gemma 3n Impact Challenge**. A mobile-first web app that uses Google's Gemma 3n multimodal AI to capture wound photos and voice notes, then produces a structured assessment across 15 medical parameters (size, depth, infection signs, exudate, etc.).

**Stack:** Python · Google Gemma 3n · Mobile-first Web

---

### [ScanAuditor](https://github.com/bewayo2/scanauditor) `JavaScript` `Public`
> Comprehensive AI analysis of scanned handwritten medical records.

Uses **PaddleOCR** for handwriting extraction and **Gemma 3n 4b** for text analysis. Detects multi-patient files, date mismatches, and data integrity issues across entire documents. Designed for auditing legacy paper-based clinical records.

**Stack:** JavaScript · PaddleOCR · Google Gemma 3n

---

### [BHS Virtual Health Assistant](https://github.com/bewayo2/BHSVirtualHealthAssistant) `Python` `Public`
> Conversational AI chatbot demo for Bright Health Solutions.

A virtual health assistant chatbot for patient-facing interactions, built as a demonstration for BHS.

**Stack:** Python

---

### [BHS Discharge Summary Generator](https://github.com/bewayo2/BHSDischargeSummaryGenerator) `HTML` `Public`
> Automated clinical discharge summary generation tool.

Web-based tool for generating structured discharge summaries for BHS clinical staff.

**Stack:** HTML · JavaScript

---

### [Sepsis Predictor](https://github.com/bewayo2/Sepsispredictor) `Python` `Public`
> Machine learning model for early sepsis risk prediction.

Predictive model using clinical data to identify patients at risk of sepsis, enabling earlier intervention.

**Stack:** Python · Machine Learning

---

## Healthcare Operations

Systems for managing clinical workflows, inventory, equipment, and process documentation.

### [RoomManager](https://github.com/bewayo2/RoomManager) `TypeScript` `Private`
> Full-stack healthcare clinic inventory and procedure tracking system.

Manages medical supplies with **FEFO (First-Expiry-First-Out)** stock rotation, purchase orders, procedure usage logging, and AI-assisted label scanning for batch/expiry extraction. Includes low stock alerts, variance analysis, and full audit trails.

**Stack:** Node.js · TypeScript · Express · React · Firebase Firestore · Zod

---

### [Scan Progress Tracker](https://github.com/bewayo2/ScanProgressTracker) `Python` `Private`
> Analyses PDF scan batches to report digitisation progress.

Flask app that recursively analyses PDFs in a folder tree, extracts metadata, and produces reports with 7 interactive Chart.js visualisations — weekly output, shift splits, peak rates, efficiency metrics, and completion forecasts (excluding weekends).

**Stack:** Python · Flask · Chart.js

---

### [SJH Equipment Commissioning](https://github.com/bewayo2/SJHEquipmentCommissioning) `JavaScript` `Private`
> Equipment commissioning tracking app for St John of God Hospital.

React + Vite application for managing and tracking the commissioning status of hospital equipment.

**Stack:** React · Vite · JavaScript

---

### [SJH Swimlane Generator](https://github.com/bewayo2/SJHSwimlaneGenerator) `HTML` `Public`
> AI-powered swimlane and process flow diagram generator.

Web tool that converts text descriptions into swimlane or process flow diagrams, built for SJH clinical and operations teams.

**Stack:** HTML · JavaScript

---

### [AI OCR Sorter](https://github.com/bewayo2/AIOCRSorter) `Python` `Public`
> Automatically sorts and classifies scanned documents using AI and OCR.

Uses OCR and AI classification to sort large batches of scanned files into categories without manual review.

**Stack:** Python · OCR · AI Classification

---

## AI Productivity Tools

Automation tools that leverage LLMs to accelerate knowledge work.

### [MasterLister](https://github.com/bewayo2/masterlister) `JavaScript` `Private`
> Multi-user collaborative inventory counter with AI image recognition.

Users capture multi-angle photos of items; **GPT-5.1 vision** extracts item details automatically. Supports real-time multi-user collaboration, location-based organisation, a shared item master list, and CSV export. Built on Firebase for live sync.

**Stack:** React 18 · Vite · Firebase · OpenAI GPT-5.1 Vision

---

### [Strategic Blueprint GPTs](https://github.com/bewayo2/StrategicBlueprintGPTs) `Python` `Private`
> Multi-client business document pipeline for chatbot knowledge bases.

Processes DOCX/PDF business documents into structured JSON knowledge bases per client. Each client gets isolated data, configs, prompts, and outputs — ready to power custom chatbots.

**Stack:** Python · OpenAI GPT · LLM Pipeline

---

### [AI Hiring Tool](https://github.com/bewayo2/AIhiringtool) `Python` `Public`
> AI-assisted candidate screening and hiring workflow tool.

Automates early-stage candidate evaluation using AI to match resumes against role requirements and generate structured assessments.

**Stack:** Python · AI/LLM

---

### [Audio Transcription App](https://github.com/bewayo2/audiotransriptionapp) `Python` `Public`
> Lightweight utility to convert audio files to text.

Simple, focused tool for transcribing audio recordings using OpenAI Whisper. Designed for quick local use with minimal setup.

**Stack:** Python · OpenAI Whisper

---

### [Ref Extractor](https://github.com/bewayo2/RefExtractor) `HTML` `Public`
> Extract and format references from academic papers via DOIs and URLs.

Browser-based tool for researchers to pull structured citation data from paper links and DOIs.

**Stack:** HTML · JavaScript

---

## Marketing & Content

AI tools for generating, optimising, and repurposing content at scale.

### [Caption Generator](https://github.com/bewayo2/CaptionGenerator) `Python` `Private`
> Automated social media and long-form content from video/audio files.

Transcribes videos using **OpenAI Whisper**, then uses **GPT-4.1** to generate platform-specific content based on duration:
- < 2 min → Shorts captions
- 2–8 min → LinkedIn, YouTube, Facebook posts
- 8–45 min → Posts + email content
- 45+ min (podcasts) → All of the above + full show notes

Outputs to Word documents.

**Stack:** Python · OpenAI GPT-4.1 · Whisper

---

### [Keyword Generator](https://github.com/bewayo2/KeyWordGenerator) `Python` `Public`
> SEO keyword research tool powered by Google Ads API and GPT.

Streamlit app that pulls keyword ideas from **Google Ads Keyword Planner**, then uses **GPT-5.2** to categorise them and generate a Focus Keyphrase, SEO Title, and SEO Excerpt for blog optimisation. CSV export included.

**Stack:** Python · Streamlit · Google Ads API · OpenAI GPT-5.2

---

### [Blog Outline & SEO Generator](https://github.com/bewayo2/BlogOutlineandSEOGenerator) `Python` `Private`
> Generates blog outlines with full SEO metadata using keyword data.

Companion to the Keyword Generator — takes keyword research and produces structured blog outlines with SEO-optimised metadata.

**Stack:** Python · Streamlit · OpenAI GPT

---

### [Training Mindmaps](https://github.com/bewayo2/Trainingmindmaps) `Python` `Public`
> Generate interactive Cytoscape.js mind maps from DOCX training documents.

Converts Word documents into standalone HTML mind map files using an LLM to extract structure. No server required — the output is a single portable HTML file.

**Stack:** Python · OpenAI LLM · Cytoscape.js

---

## EMR & Practice Management

Electronic Medical Record systems and tooling.

### [Paradyme](https://github.com/bewayo2/Paradyme) `PHP` `Public`
> Fork of OpenEMR — open source electronic health records platform.

A customised fork of [OpenEMR](https://open-emr.org), the leading open-source EHR and practice management system. Features integrated health records, scheduling, electronic billing, and internationalization.

**Stack:** PHP · MySQL · OpenEMR

---

### [Paradyme Aide](https://github.com/bewayo2/Paradyme-aide) `TypeScript` `Public`
> Fork of Aide — AI-native code editor based on VS Code.

A customised fork of [Aide](https://github.com/codestoryai/aide), an open-source AI code editor that combines VS Code with agentic AI capabilities including chat+edit flow, proactive linting agents, and inline editing.

**Stack:** TypeScript · VS Code Fork · AI

---

### [EMR Select](https://github.com/bewayo2/EMRSelect) `JavaScript` `Public`
> Decision tool to help clinics evaluate and select an EMR system.

Interactive tool guiding healthcare practices through structured criteria to identify the most suitable EMR platform for their needs.

**Stack:** JavaScript

---

## Goal & Project Management

Personal and business planning tools.

### [PG Annie](https://github.com/bewayo2/PGAnnie) `TypeScript` `Private`
> Full-stack personal goal planning app with OKR-style quarterly tracking.

Users set long-horizon goals (10/5/3/1 years) across life buckets, then cascade them into quarterly OKRs, monthly goals, and weekly activities. Includes a dashboard for at-risk items, weekly check-ins, and workload calculations.

**Stack:** React · TypeScript · Tailwind CSS · Python FastAPI · Firebase Auth · Firestore

---

### [Settle App](https://github.com/bewayo2/SettleApp) `Python` `Private`
> App to manage and track settlement tasks.

Python application for managing structured task lists and progress tracking around settlements or project completion workflows.

**Stack:** Python

---

## Data & Research

Visualisation and analysis tools for clinical and research data.

### [AUROC Demo](https://github.com/bewayo2/AUROCdemo) `JavaScript` `Public`
> Interactive demo of AUROC curves and calibration with temperature scaling.

Educational web tool with three AUROC curves (perfect, good, random) and a sensitivity slider showing operating point movement. A second panel demonstrates temperature scaling effects on calibration curves in real time.

**Stack:** JavaScript · Interactive Visualisation

---

### [BHS Flow Map Generator](https://github.com/bewayo2/BHSFlowMapGen) `HTML` `Public`
> Convert text descriptions into process flow and swimlane diagrams using GPT-4.

Web app that sends text to **GPT-4**, receives structured process tables, and renders them as Graphviz diagrams. Supports both process flow (Start/Process/Decision/End) and swimlane formats. SVG and DOT export.

**Stack:** HTML · Python · GPT-4 · Graphviz

---

## Stats

| Metric | Count |
|--------|-------|
| Total repositories | 43 |
| Public | 18 |
| Private | 25 |
| Primary languages | Python (19), TypeScript (6), JavaScript (8), HTML (6), C# (1), PHP (1) |
| Healthcare-focused | ~28 |

---

*Last updated: April 2026*

# bewayo2 — Project Showcase

A portfolio of software projects built by [@bewayo2](https://github.com/bewayo2), spanning AI-powered healthcare tools, clinical operations systems, productivity automation, and EMR platforms.

---

## Categories

| # | Category | Projects |
|---|----------|----------|
| 1 | [Healthcare AI](#-healthcare-ai) | WoundCareAI, ScanAuditor, BHS Virtual Health Assistant, Sepsis Predictor, BHS Discharge Summary Generator |
| 2 | [Healthcare Operations](#-healthcare-operations) | RoomManager, Scan Progress Tracker, SJH Equipment Commissioning, SJH Swimlane Generator, AI OCR Sorter, SentinelQG, SJH Org Chart, Inventory Matching |
| 3 | [AI Productivity Tools](#-ai-productivity-tools) | MasterLister, Strategic Blueprint GPTs, AI Hiring Tool, arvohire, Audio Transcription App, Ref Extractor, BrainKick, Utility Projects |
| 4 | [Marketing & Content](#-marketing--content) | Caption Generator, Shorts Generator, Keyword Generator, Blog Outline & SEO Generator, Training Mindmaps, Articles & Blogs |
| 5 | [EMR & Practice Management](#-emr--practice-management) | Paradyme, Paradyme Aide, EMR Select, Local Paradyme |
| 6 | [Revenue Cycle Management](#-revenue-cycle-management) | Settle |
| 7 | [Goal & Project Management](#-goal--project-management) | PG Annie |
| 8 | [Data & Research](#-data--research) | AUROC Demo, BHS Flow Map Generator, Ref Extractor, SciWrap, Data Analysis |
| 9 | [Security & Compliance](#-security--compliance) | 27Readiness |

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

### [SentinelQG](https://github.com/bewayo2/SentinelQG) `C#` `Private`
> Enterprise quality management solution for healthcare organisations.

A comprehensive quality governance platform built for healthcare. Manages clinical quality indicators, incident tracking, audit workflows, corrective actions, and compliance reporting — giving quality teams a unified system across departments and sites.

**Stack:** C# · .NET

---

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

### [SJH Org Chart](https://github.com/bewayo2/SJHOrgchart) `HTML` `Private`
> Interactive organisational chart for St John of God Hospital.

Web-based org chart tool for visualising department and reporting structures within SJH. Built for internal use by HR and operations teams.

**Stack:** HTML · JavaScript

---

### [AI OCR Sorter](https://github.com/bewayo2/AIOCRSorter) `Python` `Public`
> Automatically sorts and classifies scanned documents using AI and OCR.

Uses OCR and AI classification to sort large batches of scanned files into categories without manual review.

**Stack:** Python · OCR · AI Classification

---

### [Inventory Matching](https://github.com/bewayo2/Inventorymatching) `Public`
> Matches and reconciles inventory items across systems or locations.

Tool for cross-referencing inventory records to identify duplicates, discrepancies, and unmatched items — supporting stock audits and data migration workflows.

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

### [arvohire](https://github.com/bewayo2/arvohire) `Python` `Private`
> Culture-based recruitment platform.

A hiring platform that goes beyond skills matching to evaluate candidate-culture fit. Structures the recruitment process around organisational values, team dynamics, and behavioural indicators — helping teams hire for long-term retention as much as capability.

**Stack:** Python

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

### [BrainKick](https://github.com/bewayo2/Brainkick) `Private`
> Chat-to-document and chat-to-PDF platform.

Conversational interface that lets users generate, edit, and export structured documents and PDFs through natural language chat. Built as a multi-service architecture across five repositories covering the core app, frontend, backend API, registration service, and live collaboration layer.

**Repositories:** [Core](https://github.com/bewayo2/Brainkick) · [Frontend](https://github.com/bewayo2/BrainkickFE) · [Backend](https://github.com/bewayo2/Brainkick-BE) · [Registration](https://github.com/bewayo2/BrainKick-Reg) · [Live](https://github.com/bewayo2/BrainKick-Live)

---

### [Utility Projects](https://github.com/bewayo2/Utilityprojects) `Python` `Private`
> Collection of reusable Python utility scripts and automation tools.

A workspace for smaller scripts and utilities that support other projects — data processing helpers, file manipulation tools, and automation snippets.

**Stack:** Python

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

### [Shorts Generator](https://github.com/bewayo2/Shortsgenerator) `Private`
> Generates viral short-form clips from long-form video content.

Analyses long-form video to identify the highest-engagement moments and automatically extracts them as short-form clips optimised for platforms like YouTube Shorts, TikTok, and Instagram Reels. Separate pipeline from Caption Generator — focused on clip extraction rather than text output.

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

### [Articles & Blogs](https://github.com/bewayo2/ArticlesandBlogs) `Python` `Private`
> Automated article and blog content generation pipeline.

Python pipeline for drafting, structuring, and publishing long-form written content. Supports multi-topic batch generation with configurable tone, length, and SEO settings.

**Stack:** Python · OpenAI GPT

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

### [Local Paradyme](https://github.com/bewayo2/Localparadyme) `TypeScript` `Private`
> Self-hosted local deployment build of Paradyme EMR.

A locally deployable configuration of the Paradyme EMR system, optimised for clinics running on-premises infrastructure rather than cloud-hosted environments.

**Stack:** TypeScript

---

## Revenue Cycle Management

AI-powered tools for medical billing, claim recovery, and practice financial operations.

### [Settle](https://github.com/bewayo2/SettleApp) `Python` `Private`
> AI-powered revenue cycle management for independent medical practices.

Medical practices typically see 5–15% of claims denied on first submission, and physicians lose an average of 13 hours/week to payer administrative work. Settle automates EOB analysis, claim appeals, patient billing, and revenue tracking so practices can focus on care.

**Key stats Settle addresses:**
- Up to 15% initial claim denial rate (private payers)
- 70% of denied claims overturned on appeal — but only after costly rework
- 1–3% of net revenue lost annually to commercial underpayments
- Target: A/R under 30–40 days (AAFP benchmark)

**Features:**
- **AI EOB Analysis** — Reads every Explanation of Benefits in seconds, flags underpayments, denials, and discrepancies across all major payer formats
- **Automated Claim Follow-Up** — Auto-generates appeals with supporting documentation; tracks every claim from submission to payment; prioritises by recovery value
- **Real-Time Revenue Dashboard** — Live cash-flow forecasting, payer performance scorecards, aging bucket analysis
- **Smart Patient Billing** — Calculates patient responsibility post-insurance, sends clear statements, supports payment plans — fully HIPAA compliant

**How it works:**
1. Connect your practice — import billing records in minutes, no IT overhaul
2. AI analyses every claim — cross-references contracted rates, identifies every underpayment and denial
3. Recover what you're owed — Settle generates appeals, sends statements, tracks every dollar to resolution

**Stack:** Python · AI/LLM · HIPAA Compliant  
**Contact:** bewaji@bewajihealth.com

---

## Goal & Project Management

Personal and business planning tools.

### [PG Annie](https://github.com/bewayo2/PGAnnie) `TypeScript` `Private`
> Full-stack personal goal planning app with OKR-style quarterly tracking.

Users set long-horizon goals (10/5/3/1 years) across life buckets, then cascade them into quarterly OKRs, monthly goals, and weekly activities. Includes a dashboard for at-risk items, weekly check-ins, and workload calculations.

**Stack:** React · TypeScript · Tailwind CSS · Python FastAPI · Firebase Auth · Firestore

---

### [PG Annie (Early Prototype)](https://github.com/bewayo2/PG-Annie) `HTML` `Private`
> Original HTML prototype of the PG Annie goal planning tool.

The initial proof-of-concept for the PG Annie goal planner, built in plain HTML/JS before the full TypeScript rewrite. Established the core goal-cascading model and UX flow.

**Stack:** HTML · JavaScript

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

### [SciWrap](https://github.com/bewayo2/SciWrap) `Python` `Private`
> Delivers personalised journal article summaries based on user-defined keywords.

Users submit keywords or topic areas and SciWrap retrieves relevant journal articles, summarises them using an LLM, and delivers digestible research briefings. Designed to keep clinicians and researchers current without the burden of manual literature review.

**Stack:** Python · LLM · Academic APIs

---

### [Data Analysis](https://github.com/bewayo2/Data-Analysis) `Public`
> Collection of data analysis notebooks and scripts.

A repository of analytical work including exploratory data analysis, visualisations, and research scripts spanning clinical and operational datasets.

---

## Security & Compliance

Tools for organisational security assessment and compliance readiness.

### [27Readiness](https://github.com/bewayo2/27Readiness) `JavaScript` `Public`
> Cybersecurity readiness assessment tool for organisations.

Guides organisations through a structured self-assessment of their cybersecurity posture based on ISO 27001 / NIST-aligned controls. Produces a readiness score, gap analysis, and prioritised remediation roadmap — helping teams understand where they stand before a formal audit or certification.

**Stack:** JavaScript

---

## Stats

| Metric | Count |
|--------|-------|
| Total repositories | 44 |
| Public | 20 |
| Private | 24 |
| Primary languages | Python (19), TypeScript (7), JavaScript (9), HTML (7), C# (1), PHP (1) |
| Healthcare-focused | ~28 |

---

*Last updated: April 2026*

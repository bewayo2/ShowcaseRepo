# bewayo2 — Project Showcase

A source-checked portfolio of software work maintained by [@bewayo2](https://github.com/bewayo2), spanning healthcare AI, clinical operations, digital systems, research, and business applications. Entries describe repositories and their documented implementation. Inclusion does not imply clinical validation, production deployment, regulatory certification, or exclusive authorship of upstream open-source code.

**Inventory verified:** 9 November 2026. Project labels distinguish applications, prototypes, adaptations, and placeholders. Private repository links require authorized GitHub access.

---

## Categories

| # | Category | Projects |
|---|----------|----------|
| 1 | [Healthcare AI](#-healthcare-ai) | WoundCareAI, ScanAuditor, BHS Virtual Health Assistant, Sepsis Predictor, BHS Discharge Summary Generator, MediScripts (placeholder) |
| 2 | [Healthcare Operations](#-healthcare-operations) | RoomManager, Scan Progress Tracker, SJH Equipment Commissioning, SJH Swimlane Generator, AI OCR Sorter, SentinelQG, SJH Org Chart (two repositories), Inventory Matching (empty) |
| 3 | [AI Productivity Tools](#-ai-productivity-tools) | MasterLister, Strategic Blueprint GPTs, AI Hiring Tool, arvohire, ContactBuilder, Audio Transcription, Ref Extractor, BrainKick, Utility Projects, BHS Knowledge Base Sync, Paradyme Aide |
| 4 | [Marketing & Content](#-marketing--content) | Media Content Generator, Video Editing, SJH Mockup Builder, Shorts Generator, Keyword Generator, WordPress Manager, Training Mindmaps, Articles & Blogs, BHS Writer, SJH Content & Brand Creator |
| 5 | [EMR & Practice Management](#-emr--practice-management) | Paradyme (OpenEMR fork), EMR Select, Local Paradyme (AgentCare MCP experiment) |
| 6 | [Finance & Revenue Operations](#-finance--revenue-operations) | Settle, KinCFO (licensing server and demo) |
| 7 | [Goal & Project Management](#-goal--project-management) | PG Annie, Personal Planner |
| 8 | [Data & Research](#-data--research) | AUROC Demo, BHS Flow Map Generator, Ref Extractor, SciWrap, Academic Writing, Data Analysis |
| 9 | [Security & Compliance](#-security--compliance) | 27Readiness |

---

## Healthcare AI

Tools that apply AI/ML directly to clinical workflows, diagnostics, and patient care.

### [WoundCareAI](https://github.com/bewayo2/WoundCareAI) `Python` `Private`
> Multimodal wound-assessment research prototype for the Google Gemma 3n Impact Challenge.

Mobile-oriented Streamlit application for recording wound photographs and notes, generating a structured multi-parameter AI assessment, and exporting reports. The README describes local/offline operation after setup; actual mobile performance and clinical accuracy were not independently verified. Its medical disclaimer requires professional judgment and warns against using the application as a replacement for clinical assessment.

**Stack:** Python · Streamlit · Google Gemma 3n · Transformers/PyTorch

---

### [ScanAuditor](https://github.com/bewayo2/scanauditor) `JavaScript` `Public`
> Desktop quality-assurance workspace for scanned medical-record PDFs.

The current pipeline converts PDF pages to images and, by default, uses local Ollama models **qwen3-vl:8b-instruct** for OCR/visual checks and **qwen3:14b** for identifier and date extraction. Deterministic checks flag unreadable pages, possible duplicate pages, patient-identity conflicts, missing coverage and inconsistent dates. Supports resumable folder audits, a local SQLite review queue, audit evidence, and optional hospital-authorized cloud inference. It **does not** establish source-paper completeness or authorize disposal of paper records.

**Stack:** Electron/JavaScript · Python PDF conversion · Ollama/Qwen3 · SQLite · Optional OpenAI

---

### [BHS Virtual Health Assistant](https://github.com/bewayo2/BHSVirtualHealthAssistant) `Python` `Public`
> Jamaica-focused health information chatbot prototype.

Contains a FastAPI backend and web frontend for a virtual health-information assistant. The backend documents the **JAMCare** concept, uses OpenAI GPT-4o-mini, and includes guidance on health information and escalation. It is an experimental demonstration, not a clinically validated or regulator-approved patient-care service.

**Stack:** Python · FastAPI · OpenAI API · JavaScript frontend

---

### [BHS Discharge Summary Generator](https://github.com/bewayo2/BHSDischargeSummaryGenerator) `JavaScript` `Public`
> Prototype for drafting structured discharge summaries from supplied clinical notes.

Browser UI backed by an Express server that calls an OpenAI model to produce summarised text. Human clinical review remains necessary before use in a patient record. The source uses a legacy GPT-4 preview model identifier, so operational compatibility needs verification.

**Stack:** HTML · JavaScript · Node.js/Express · OpenAI API

---

### [Sepsis Predictor](https://github.com/bewayo2/Sepsispredictor) `Python` `Public`
> Educational sepsis risk modelling and sensitivity dashboard.

Contains a clinical dataset, a saved machine-learning model, and a Streamlit dashboard examining lactate, temperature, and mean arterial pressure. No prospective clinical validation or approval for diagnosis/treatment was verified. Present as a research or teaching demonstration.

**Stack:** Python · Streamlit · scikit-learn · joblib

---

### [MediScripts](https://github.com/bewayo2/MediScripts) `Private`
> **Placeholder repository.** Only a minimal README containing the project name was found. No features or implementation are claimed.

---
## Healthcare Operations

Systems for managing clinical workflows, inventory, equipment, and process documentation.

### [SentinelQG](https://github.com/bewayo2/SentinelQG) `C#` `Private`
> Enterprise quality management solution for healthcare organisations.

A comprehensive quality governance platform built for healthcare. Manages clinical quality indicators, incident tracking, audit workflows, corrective actions, and compliance reporting — giving quality teams a unified system across departments and sites.

**Stack:** C# · .NET

---

### [RoomManager](https://github.com/bewayo2/RoomManager) `TypeScript` `Private`
> Healthcare procedure and inventory-management application under development.

Includes item master data, FEFO inventory rotation, purchasing and receiving, procedure consumption logging, stock adjustments, and reporting workflows. **AI-assisted label scanning and invoice matching are listed as planned features**, rather than confirmed completed capabilities.

**Stack:** Node.js · TypeScript · Express · React · Firestore · Zod

---

### [Scan Progress Tracker](https://github.com/bewayo2/ScanProgressTracker) `Python` `Private`
> Analyses PDF scan batches to report digitisation progress.

Flask app that recursively analyses PDFs in a folder tree, extracts metadata, and produces reports with 7 interactive Chart.js visualisations — weekly output, shift splits, peak rates, efficiency metrics, and completion forecasts (excluding weekends).

**Stack:** Python · Flask · Chart.js

---

### [SJH Equipment Commissioning](https://github.com/bewayo2/SJHEquipmentCommissioning) `JavaScript` `Private`
> Equipment and room-commissioning workflow application for St Jude Hospital.

React/Vite application with room checklists, biomedical equipment views and reporting, supplier register, item search, and bill-of-quantities/reference views. Repository code documents these modules; institutional adoption or deployment was not verified.

**Stack:** React · Vite · JavaScript · Firebase

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
> Local batch-processing script for scanned PDF medical records.

The code extracts hospital numbers from PDFs using document/image processing and AI components, then supports page bookmarking, splitting, and regrouping by identifier. It should not be described as an independently validated general-purpose classification platform.

**Stack:** Python · PyMuPDF · PDF/image tools · Qwen2-VL components

---

### [Inventory Matching](https://github.com/bewayo2/Inventorymatching) `Public`
> **Empty repository / placeholder.**

The repository currently has no files on its default branch. Matching, reconciliation, or migration functions cannot be verified from code. It is listed for inventory completeness and **not counted as a working application**.

---

### [SJH Organisation Chart (full-stack)](https://github.com/bewayo2/sjh-org-chart) `TypeScript` `Private`
> Separate, full-stack hospital organisational-chart project.

Includes a client, a server with Prisma database tooling, and organisation-chart image generation scripts. This is distinct from the earlier single-file [SJHOrgchart](https://github.com/bewayo2/SJHOrgchart).

**Stack:** TypeScript · Node.js · Prisma · Web client

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

### [ContactBuilder](https://github.com/bewayo2/ContactBuilder) `Python` `Private`
> Lead research and outreach automation for healthcare opportunities.

Pipeline for discovering healthcare organisations and decision-makers from project triggers, job postings, and public-sector buying signals. Supports Exa discovery, Hunter enrichment, GPT contact playbooks, CRM-ready exports, LinkedIn URL exports, and outreach document generation.

**Stack:** Python · Exa · OpenAI GPT · Hunter · python-docx

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
> Multi-repository document workflow project with uneven implementation status.

[Brainkick-BE](https://github.com/bewayo2/Brainkick-BE) contains Python application/backend code; [BrainKick-Live](https://github.com/bewayo2/BrainKick-Live) contains a larger web application codebase. The [core](https://github.com/bewayo2/Brainkick), [frontend](https://github.com/bewayo2/BrainkickFE), and [registration](https://github.com/bewayo2/BrainKick-Reg) repositories are **currently empty**. The original portfolio's end-to-end chat-to-document/PDF product claim is a project aim, not a verified integrated capability.

**Repositories:** [Backend](https://github.com/bewayo2/Brainkick-BE) · [Live](https://github.com/bewayo2/BrainKick-Live) · [Core placeholder](https://github.com/bewayo2/Brainkick) · [Frontend placeholder](https://github.com/bewayo2/BrainkickFE) · [Registration placeholder](https://github.com/bewayo2/BrainKick-Reg)

---

### [Utility Projects](https://github.com/bewayo2/Utilityprojects) `Python` `Private`
> Collection of reusable Python utility scripts and automation tools.

A workspace for smaller scripts and utilities that support other projects — data processing helpers, file manipulation tools, and automation snippets.

**Stack:** Python

---

### [BHS Knowledge Base Sync](https://github.com/bewayo2/BHSKnowledgebasesync) `Python` `Private`
> Knowledge-management automation connecting a curated Google Drive library with an OpenAI vector store.

Uses configured folder inclusion/exclusion rules, exports eligible source files, maintains a sync register, updates changed vector-store entries, and supports GitHub Actions runs. Designed to avoid raw intake, archived and human-review material.

**Stack:** Python · Google Drive API · OpenAI Files/vector stores · GitHub Actions

---

### [Paradyme Aide](https://github.com/bewayo2/Paradyme-aide) `TypeScript` `Public`
> Fork of the AI-enabled Aide/VS Code editor, classified here as development tooling rather than clinical records software.

Code and features from the upstream Aide project are acknowledged. No independently verified original editor feature claims are made.

**Stack:** TypeScript · VS Code/Aide fork

---
## Marketing & Content

AI tools for generating, optimising, and repurposing content at scale.

### [Media Content Generator](https://github.com/bewayo2/MediaContentGenerator) `Python` `Private`
> Automated social media and long-form content from video/audio files.

Transcribes videos using **OpenAI Whisper**, then uses **GPT-4.1** to generate platform-specific content based on duration:
- < 2 min → Shorts captions
- 2–8 min → LinkedIn, YouTube, Facebook posts
- 8–45 min → Posts + email content
- 45+ min (podcasts) → All of the above + full show notes

Outputs to Word documents.

**Stack:** Python · OpenAI GPT-4.1 · Whisper

---

### [Video Editing](https://github.com/bewayo2/VideoEditing) `Python` `Private`
> Adaptation of the open-source `video-use` agentic video-editing toolkit for BHS content production.

The upstream repository's code and MIT license are attributed to Browser Use. This working copy includes BHS-specific caption, brand, podcast-audiogram, and editorial overlay guidance, as well as FFmpeg, Manim, and Remotion-based workflows. Describe this as **customization and integration**, not sole authorship of the original tool.

**Stack:** Python · FFmpeg · Remotion · Manim · Claude Code workflows

---

### [SJH Mockup Builder](https://github.com/bewayo2/SJHMockupBuilder) `JavaScript` `Private`
> Browser-based mockup builder for SJH website concepts.

Interactive page mockup canvas with editable sections, layers, properties, drag-and-drop controls, JSON project import/export, and PNG export for individual pages.

**Stack:** HTML · CSS · JavaScript · Node.js

---

### [Shorts Generator](https://github.com/bewayo2/Shortsgenerator) `Private`
> Generates viral short-form clips from long-form video content.

Analyses long-form video to identify the highest-engagement moments and automatically extracts them as short-form clips optimised for platforms like YouTube Shorts, TikTok, and Instagram Reels. Separate pipeline from Media Content Generator — focused on clip extraction rather than text output.

---

### [Keyword Generator](https://github.com/bewayo2/KeyWordGenerator) `Python` `Public`
> SEO keyword research tool powered by Google Ads API and GPT.

Streamlit app that pulls keyword ideas from **Google Ads Keyword Planner**, then uses **GPT-5.2** to categorise them and generate a Focus Keyphrase, SEO Title, and SEO Excerpt for blog optimisation. CSV export included.

**Stack:** Python · Streamlit · Google Ads API · OpenAI GPT-5.2

---

### [WordPress Manager](https://github.com/bewayo2/wordpressmanager) `Python` `Private`
> Blog content, SEO and WordPress publishing workflow tools.

The repository includes a command-line keyword-and-outline generator using Google Ads data and GPT, a legacy Streamlit app, and an ArticlesandBlogs subdirectory. It is the accessible replacement for the showcase's broken `BlogOutlineandSEOGenerator` repository link.

**Stack:** Python · Google Ads API · OpenAI API · WordPress tooling

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

### [BHS Writer](https://github.com/bewayo2/BHSWriter) `Python` `Private`
> BHS long-form and search-oriented article drafting pipeline.

Converts supplied outlines into two article drafts using an Anthropic Claude model, BHS writing guidance, and SEO checks. The repository overlaps in file structure with ArticlesandBlogs; they are counted as separate repositories, not independent proof of unrelated products.

**Stack:** Python · Anthropic API · Word/Markdown tooling

---

### [SJH Content & Brand Creator](https://github.com/bewayo2/SJH-Content-Brand-Creator) `Public`
> Deployable AI skill package for St Jude Hospital communication and brand-governance workflows.

Includes instructions, playbooks, reference files, templates and optional linting scripts. Its rules require current approved brand sources and human institutional approvals, which the skill does not grant.

**Stack:** Markdown skill files · Python/utilities

---
## EMR & Practice Management

Electronic Medical Record systems and tooling.

### [Paradyme](https://github.com/bewayo2/Paradyme) `PHP` `Public`
> Fork of the open-source OpenEMR electronic records and practice-management platform.

The repository contains an OpenEMR-derived codebase, including records, scheduling and billing functionality inherited from the upstream project. The available README largely reproduces upstream OpenEMR documentation. Specific original modifications, completed implementations and deployments require separate evidence.

**Stack:** PHP · MySQL · OpenEMR (upstream project)

---


### [EMR Select](https://github.com/bewayo2/EMRSelect) `JavaScript` `Public`
> Decision tool to help clinics evaluate and select an EMR system.

Interactive tool guiding healthcare practices through structured criteria to identify the most suitable EMR platform for their needs.

**Stack:** JavaScript

---

### [Local Paradyme / AgentCare MCP](https://github.com/bewayo2/Localparadyme) `TypeScript` `Private`
> Experimental local healthcare integration and MCP server code.

The package identifies itself as `agentcare-mcp` and includes an MCP SDK, Express dependencies, connector modules and a starter React/Vite interface. The code inspected does not substantiate the previous claim of a complete locally deployable Paradyme EMR.

**Stack:** TypeScript · Model Context Protocol SDK · Express · React/Vite

---

## Finance & Revenue Operations

Software for medical revenue workflows and personal finance tooling.

### [Settle](https://github.com/bewayo2/SettleApp) `Python` `Private`
> Revenue-cycle operations application in development for independent medical practices.

The codebase includes claims, insurance receivables, payment and short-pay workflows, imports, documents, dashboards, reminders, and background jobs. It contains engineering standards addressing access controls and clinic-level data separation. The portfolio does **not** claim completed HIPAA compliance, live integrations with every payer, or independently verified recovery outcomes. The README includes local setup and test instructions, but production readiness has not been established by this review.

**Stack:** Python/FastAPI · PostgreSQL · Redis/Celery · Next.js · OpenAI integrations

---

### [KinCFO Licensing & Demo](https://github.com/bewayo2/KinCFO) `TypeScript` `Private`
> Licensing services and a controlled public demonstration for a personal-finance assistant.

The accessible repository contains a Firebase-based license server and deterministic demo tools using fictional household data. It does not contain evidence of an entire standalone finance application or live bank integration. KinCFO is **personal finance tooling**, separate from Settle's medical revenue workflows.

**Stack:** TypeScript · Firebase Cloud Functions/Firestore

---
## Goal & Project Management

Personal and business planning tools.

### [PG Annie](https://github.com/bewayo2/PGAnnie) `TypeScript` `Private`
> Full-stack personal goal planning app with OKR-style quarterly tracking.

Users set long-horizon goals (10/5/3/1 years) across life buckets, then cascade them into quarterly OKRs, monthly goals, and weekly activities. Includes a dashboard for at-risk items, weekly check-ins, and workload calculations.

**Stack:** React · TypeScript · Tailwind CSS · Python FastAPI · Firebase Auth · Firestore

---

### [PG Annie (Earlier Flask Version)](https://github.com/bewayo2/PG-Annie) `Python` `Private`
> Earlier web application for goal planning, not a static HTML-only prototype.

Includes Flask, Firebase authentication/data integration, planning logic and AI-related modules. Separate from the newer React/TypeScript and FastAPI implementation in [PGAnnie](https://github.com/bewayo2/PGAnnie).

**Stack:** Python · Flask · Firebase · HTML templates

---

### [Personal Planner](https://github.com/bewayo2/PersonalPlanner) `Python` `Private`
> Personal planning automation across ClickUp, Google Drive, and Google Calendar.

Python toolkit for weekly planning, ClickUp task reporting and updates, Google Drive search/linking, and Google Calendar planning windows. Organised as sibling modules for ClickUp, Drive, and Calendar helpers.

**Stack:** Python · ClickUp API · Google Drive API · Google Calendar API

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

### [Academic Writing](https://github.com/bewayo2/AcademicWriting) `Python` `Private`
> Literature review automation tools for Caribbean healthcare and AI research.

Multi-step research pipeline for extracting source links, downloading and preflighting PDFs, converting papers to text, running OpenAI-assisted multi-pass paper extraction, and building master synthesis tables for academic writing.

**Stack:** Python · OpenAI GPT · Exa · pypdf · python-docx

---

### [Data Analysis](https://github.com/bewayo2/Data-Analysis) `Public`
> Collection of data analysis notebooks and scripts.

A repository of analytical work including exploratory data analysis, visualisations, and research scripts spanning clinical and operational datasets.

---

## Security & Compliance

Tools for organisational security assessment and compliance readiness.

### [27Readiness](https://github.com/bewayo2/27Readiness) `JavaScript` `Public`
> ISO 27001-aligned information security readiness self-assessment.

React/MUI questionnaire covering information-security management topics, with assessment interaction and Excel export. Code specifically references ISO 27001; NIST coverage, audit accreditation and certification readiness have not been independently verified.

**Stack:** React · Material UI · Excel export · Express

---

## Stats

| Metric | Count |
|--------|-------|
| Accessible GitHub repositories (including this showcase repository) | 55 |
| Public repositories | 21 |
| Private repositories | 34 |
| Non-showcase repositories | 54 |
| Known empty repositories | 4 (Brainkick, BrainkickFE, BrainKick-Reg, Inventorymatching) |
| Other minimal placeholder | MediScripts (name-only README) |

*These are repository counts, not counts of completed products. Several repositories share code, represent forks or prototypes, or belong to a single multi-repository project.*

---

*Repository descriptions checked: 9 November 2026. Source inspection does not constitute runtime testing or a compliance assessment.*

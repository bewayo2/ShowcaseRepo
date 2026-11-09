# Marketing & Content Tools

AI-assisted writing, video, SEO and institutional communication tooling.

## Media Content Generator
**Repository:** [bewayo2/MediaContentGenerator](https://github.com/bewayo2/MediaContentGenerator) · **Status:** Pipeline code; private

Converts source media into transcripts and platform-specific drafts. The project now includes bundle creation, editorial QA, an approval interface and optional scheduling workflows. Integration with the ShortsGenerator package is documented. Publication depends on configuration and approval.

**Technology:** Python, Whisper, OpenAI and Anthropic APIs, FFmpeg

---

## Video Editing
**Repository:** [bewayo2/VideoEditing](https://github.com/bewayo2/VideoEditing) · **Status:** Open-source adaptation; private

Based on the MIT-licensed Browser Use `video-use` project, with BHS-specific caption, brand, editorial and podcast-audiogram guidance. Its upstream authors deserve attribution. Workflows include transcript-led editing and FFmpeg/Remotion/Manim effects.

**Technology:** Python, FFmpeg, Claude Code, Remotion, Manim

---

## SJH Mockup Builder
**Repository:** [bewayo2/SJHMockupBuilder](https://github.com/bewayo2/SJHMockupBuilder) · **Status:** Browser app; private

Editable page mockups, sections, layers, drag-and-drop, JSON project import/export and PNG output for St Jude Hospital concepts.

**Technology:** HTML, CSS, JavaScript

---

## Shorts Generator
**Repository:** [bewayo2/Shortsgenerator](https://github.com/bewayo2/Shortsgenerator) · **Status:** Video processing code; private

Separate short-form video extraction pipeline and transcription guidance. Its code is also represented in MediaContentGenerator; not counted as evidence of an independent end-to-end platform.

**Technology:** Python, FFmpeg

---

## Keyword Generator
**Repository:** [bewayo2/KeyWordGenerator](https://github.com/bewayo2/KeyWordGenerator) · **Status:** Streamlit app; public

Retrieves Google Ads keyword ideas and uses GPT-5.2 to categorize keywords and suggest SEO metadata. CSV export is documented.

**Technology:** Python, Streamlit, Google Ads API, OpenAI

---

## WordPress Manager
**Repository:** [bewayo2/wordpressmanager](https://github.com/bewayo2/wordpressmanager) · **Status:** CLI and web tooling; private

Contains blog keyword/outline-generation scripts, legacy Streamlit functionality and an ArticlesandBlogs subfolder. This is the available repository associated with the former broken BlogOutlineandSEOGenerator entry.

**Technology:** Python, Google Ads API, WordPress

---

## Training Mindmaps
**Repository:** [bewayo2/Trainingmindmaps](https://github.com/bewayo2/Trainingmindmaps) · **Status:** Document conversion tool; public

Builds Cytoscape-based interactive HTML mind maps from DOCX using an LLM.

**Technology:** Python, OpenAI, Cytoscape.js

---

## Articles & Blogs
**Repository:** [bewayo2/ArticlesandBlogs](https://github.com/bewayo2/ArticlesandBlogs) · **Status:** Writing pipeline; private

Drafts and structures long-form content, with SEO assets and WordPress-related utilities. Overlaps in file structure with BHSWriter.

**Technology:** Python

---

## BHS Writer
**Repository:** [bewayo2/BHSWriter](https://github.com/bewayo2/BHSWriter) · **Status:** Writing pipeline; private

Uses Claude and BHS writing guidance to produce a long-form article and an SEO-oriented short version from supplied outlines.

**Technology:** Python, Anthropic

---

## SJH Content & Brand Creator
**Repository:** [bewayo2/SJH-Content-Brand-Creator](https://github.com/bewayo2/SJH-Content-Brand-Creator) · **Status:** Reusable AI skill; public

Instructions, reference documents, playbooks and templates supporting St Jude Hospital brand-consistent communication. The skill requires approved source materials and human review; it does not itself grant hospital approval.

**Technology:** AI skill files, utilities


---

*Source-checked 9 November 2026. Source review does not constitute production, compliance or outcome validation.*

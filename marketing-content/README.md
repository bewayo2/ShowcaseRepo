# Marketing & Content Tools

AI tools for generating, optimising, and repurposing content at scale.

---

## Caption Generator
**Repo:** [bewayo2/CaptionGenerator](https://github.com/bewayo2/CaptionGenerator) · `Python` · `Private`

Automated content generator for BHS marketing. Transcribes video/audio files, then generates platform-specific content based on duration — from short captions to full podcast show notes.

### Content by Duration
| Duration | Output |
|----------|--------|
| < 2 min | Shorts captions |
| 2–8 min | LinkedIn, YouTube, Facebook posts |
| 8–45 min | Posts + email content |
| 45+ min | All above + comprehensive show notes |

### What it does
- Transcribes audio/video using **OpenAI Whisper** (with chunking for large files)
- Detects content type for long videos (podcast, webinar, tutorial, etc.)
- Generates all content with **GPT-4.1** with contextual awareness of content type
- Outputs everything to a Word document
- Supports MP4, MP3, and other common media formats

### Tech Stack
| Layer | Technology |
|-------|-----------|
| Transcription | OpenAI Whisper |
| Content Generation | OpenAI GPT-4.1 |
| Output | Word document (python-docx) |
| Language | Python |

---

## Keyword Generator
**Repo:** [bewayo2/KeyWordGenerator](https://github.com/bewayo2/KeyWordGenerator) · `Python` · `Public`

Streamlit app that pulls keyword ideas from Google Ads Keyword Planner and uses GPT to categorise them and generate complete SEO metadata for blog posts.

### What it does
- Connects to **Google Ads API** to fetch keyword volume and competition data
- Uses **GPT-5.2** to categorise keywords with SEO-focused analysis
- Generates Focus Keyphrase, SEO Title, and SEO Excerpt per blog post
- Exports full keyword report as CSV

### Tech Stack
| Layer | Technology |
|-------|-----------|
| UI | Python · Streamlit |
| Keyword Data | Google Ads API (Keyword Planner) |
| AI Analysis | OpenAI GPT-5.2 |

---

## Blog Outline & SEO Generator
**Repo:** [bewayo2/BlogOutlineandSEOGenerator](https://github.com/bewayo2/BlogOutlineandSEOGenerator) · `Python` · `Private`

Companion to the Keyword Generator. Takes keyword research input and produces structured blog outlines with full SEO-optimised metadata.

**Stack:** Python · Streamlit · OpenAI GPT

---

## Training Mindmaps
**Repo:** [bewayo2/Trainingmindmaps](https://github.com/bewayo2/Trainingmindmaps) · `Python` · `Public`

Converts Word training documents into standalone interactive Cytoscape.js mind map HTML files using an LLM to extract and structure the content. Output is a single portable HTML file — no server needed.

**Stack:** Python · OpenAI LLM · Cytoscape.js

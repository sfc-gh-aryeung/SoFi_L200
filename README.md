# SoFi Finance AI Champions — Level 200 Attendee Guide

A facilitator-provisioned Snowflake Hands-On Lab. Your Snowflake environment —
role, warehouse, real documents/audio, and extraction tables — is already set
up for you before the session. This guide walks you through what to do with it.

## What You'll Build

Across 9 Cortex AI Functions, you'll turn unstructured documents and audio
into structured, queryable Snowflake tables:

- **AI_EXTRACT** — pull structured fields (and full line-item tables) out of invoices
- **AI_CLASSIFY** — auto-label documents by type
- **AI_PARSE_DOCUMENT** — convert PDFs into clean text
- **AI_FILTER** / **AI_REDACT** — flag and mask sensitive contract content
- **AI_TRANSCRIBE** / **AI_SENTIMENT** / **AI_SUMMARIZE_AGG** — turn earnings call audio into transcript, sentiment, and narrative summary
- **AI_COMPLETE** (capstone) — reason directly over the same audio file, multimodal, in one call

## Prerequisites

- A Snowflake trial account (credentials from your facilitator, environment pre-loaded)
- Chrome or Edge browser
- No prior SQL or coding experience required — Level 100 recommended but not required

## Getting Started

**[View the guide online](https://sfc-gh-aryeung.github.io/SoFi_L200/L200_Participant_Guide.html)** (no download needed) — it walks you through all 9 functions, the SQL for each, and what to try hands-on. Includes a slide reference gallery matching the deck your facilitator presents.

There's no setup script to run yourself for Level 200 — your facilitator has already provisioned your account. Just open the guide and follow along.

## Assets

- `assets/logos/` — SoFi + Snowflake logos (reused from Level 100)
- `assets/slide_images/` — thumbnails of all 18 slides from the Level 200 deck, used in the guide's Slide Reference gallery
- `assets/screenshots/` — currently empty (just a `.gitkeep`); Snowsight walkthrough screenshots will be added here later, following Level 100's naming convention (`00_...`, `01_...`, etc.)
- `assets/practice_files/L200_Practice_Upload_Sample.pdf` — a renamed copy of one of the pre-loaded invoices, used by Step 1's "Upload Your Own Document" exercise so attendees can practice the Snowsight file-upload flow themselves; not part of the facilitator-provisioned stage content
- `assets/documents/` — the 6 real source documents used by the AI functions (2 invoices, 1 SEC-filed contract, 2 earnings-call PDFs, 1 earnings-call audio clip), linked inline in the guide so attendees can view/listen to the source before running each function against it


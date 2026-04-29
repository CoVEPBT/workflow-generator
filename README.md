# RMIT Process Writing Assistant

A single-page HTML tool that reviews process documentation against three published standards used at RMIT:

- **CoVE Process Writing Golden Rules** — the College of Vocational Education's 11 rules for clear, consistent process maps.
- **RMIT Tips for Process Editors & Champions** — including activity title length, owner/expert separation, audience terminology and verb usage.
- **Nintex Process Writing Techniques** — the eight Nintex techniques covering 80/20 normal vs exception, sub-process triggers, decisions vs notes, and verb-first naming.

## Usage

Open `rmit-process-writing-assistant-v2.html` in a modern browser, or embed it in a SharePoint page. No build step or server is required.

The review runs entirely in the browser using rule-based logic — no data leaves the user's device.

## Features

- Accepts process input as pasted text, `.docx`, or `.pdf`
- Rule-based review against CoVE, RMIT and Nintex standards
- Visual workflow rendering via Mermaid and BPMN
- Export results as `.docx` or `.pdf`

## Dependencies

External libraries are loaded from public CDNs at runtime (no install needed):

- pdf.js — PDF parsing
- mammoth.js — `.docx` parsing
- mermaid — flowchart rendering
- bpmn-js — BPMN diagram rendering
- docx — `.docx` export
- html2pdf.js — `.pdf` export

## Maintainer

CoVE Projects and Business Transformation, RMIT.

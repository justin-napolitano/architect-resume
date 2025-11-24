---
slug: github-architect-resume-note-technical-overview
id: github-architect-resume-note-technical-overview
title: architect-resume
repo: justin-napolitano/architect-resume
githubUrl: https://github.com/justin-napolitano/architect-resume
generatedAt: '2025-11-24T18:30:53.118Z'
source: github-auto
summary: >-
  This repository holds a LaTeX resume template designed for architects and
  other professionals. It’s customizable, clean, and built using XeLaTeX for
  advanced font and Unicode support.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repository holds a LaTeX resume template designed for architects and other professionals. It’s customizable, clean, and built using XeLaTeX for advanced font and Unicode support.

### Key Features
- Multiple page styles, headers, and highlight bars
- Options for single and double-sided layouts
- Fully customizable colors, fonts, and sections
- Example PDFs included for layout reference

### Getting Started
1. Ensure you have XeLaTeX and Python 3 installed.
2. Clone the repo:
   ```bash
   git clone https://github.com/justin-napolitano/architect-resume.git
   cd architect-resume
   ```
3. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Build your resume using:
   ```bash
   make clean
   make html
   ```
   Or automate it:
   ```bash
   python python-build.py
   ```

### Gotchas
You’ll need `make` installed for the traditional build method. Check your LaTeX distribution for XeLaTeX support.

---
slug: "github-architect-resume"
title: "architect-resume"
repo: "justin-napolitano/architect-resume"
githubUrl: "https://github.com/justin-napolitano/architect-resume"
generatedAt: "2025-11-23T08:14:17.931883Z"
source: "github-auto"
---


# Building My Architect Resume Template: A Personal Journey

When I first started looking for a resume template that truly reflected my professional identity as an architect, I found myself frustrated. Most templates were either too generic or too rigid, lacking the flexibility I needed to highlight my unique skills and projects. That's when I decided to create my own LaTeX-based resume template — architect-resume.

## Motivation

The motivation behind architect-resume was simple: I wanted a clean, professional, and customizable resume that could be easily maintained and updated using LaTeX. I was inspired by popular templates like AltaCV and AwesomeCV, but I needed something tailored to my style and workflow. I also wanted to leverage XeLaTeX for its superior font and Unicode support, which is essential for the diverse typographic needs in architecture.

## What Problem Does It Solve?

Many architects and creative professionals struggle to find resume templates that balance aesthetics with functionality. Architect-resume solves this by providing a flexible LaTeX class that supports multiple page styles, highlight bars, and customizable sections. It allows users to create resumes that stand out while remaining easy to update and maintain.

## How It's Built

The core of the project is the `my-resume.cls` LaTeX class, which defines the layout, colors, fonts, and structural elements of the resume. The main document `resume.tex` imports this class and assembles the content, which is modularized into sections stored in the `sections` directory.

I also included a Python build script, `python-build.py`, which automates dependency installation and the build process using `make`. This script runs commands like `make clean` and `make html` to generate the PDF resume efficiently. The build system ensures that the resume can be rebuilt quickly and reliably, which is crucial when iterating on design and content.

## Interesting Implementation Details

- **XeLaTeX Compatibility:** Using XeLaTeX allows me to use system fonts and handle Unicode characters seamlessly, which is a big plus for internationalization and typographic finesse.
- **Highlight Bars and Page Styles:** The template supports different page styles, including headers and highlight bars that can alternate sides for double-sided printing or stay fixed for single-sided layouts.
- **Automated Build Pipeline:** The Python script integrates subprocess calls to `make` and pip, streamlining the build and dependency management process.

## Why this project matters for my career

Creating architect-resume has been more than just a personal project; it’s a reflection of my commitment to precision, design, and professionalism—qualities that are essential in architecture. By building and maintaining this template, I sharpen my LaTeX skills, automate workflows, and produce a polished resume that truly represents my brand. It also showcases my ability to blend technical skills with creative design, which is invaluable in my career development.

---

If you're an architect or creative professional looking for a customizable and elegant resume solution, I hope architect-resume inspires you to take control of your own professional narrative through thoughtful design and automation.
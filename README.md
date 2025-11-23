# architect-resume

A LaTeX-based resume template designed for architects and professionals who want a clean, customizable CV built with XeLaTeX. This project provides a flexible resume layout with multiple page styles and options to highlight your professional profile effectively.

---

## Features

- Clean, professional LaTeX resume template
- Multiple page styles including headers and highlight bars
- Support for single-sided and double-sided layouts
- Easily customizable colors, fonts, and sections
- XeLaTeX compatible for advanced font and Unicode support
- Includes example PDFs demonstrating layout possibilities

## Tech Stack

- Primary Language: TeX (LaTeX)
- Build Tools: Makefile (assumed from `make` commands in build script)
- Python: helper build script (`python-build.py`) automates dependency installation and building process

## Getting Started

### Prerequisites

- XeLaTeX installed (part of TeX Live or MikTeX distributions)
- Python 3 (for running the build script)
- `make` utility

### Installation

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/architect-resume.git
cd architect-resume
```

Install Python dependencies:

```bash
pip install -r requirements.txt
```

### Build the Resume

You can build the resume PDF by running:

```bash
make clean
make html
```

Or use the Python build script which automates this:

```bash
python python-build.py
```

## Project Structure

```
architect-resume/
├── deployz/                 # Possibly deployment scripts or assets
├── sections/                # Resume sections as separate LaTeX files
├── my-resume.cls           # Custom LaTeX class defining the resume style
├── resume.tex              # Main LaTeX source file
├── resume.pdf              # Generated PDF resume
├── python-build.py         # Python script automating build and deployment
├── README.md               # This documentation file
├── LICENSE                 # License file
├── *.png, *.jpeg           # Example images and screenshots
└── *.log, *.aux, *.out     # LaTeX auxiliary build files
```

## Future Work / Roadmap

- Add detailed documentation for customizing the template
- Support additional output formats (e.g., HTML or DOCX)
- Integrate CI/CD pipeline for automated build and deployment
- Expand example resumes showcasing different professions
- Improve build script with error handling and logging
- Add support for more languages/locales

---

*Note: This README is based on the current repository contents and inferred details.*
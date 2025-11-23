# architect-resume

A LaTeX-based resume template tailored for architects and professionals seeking a clean, customizable CV built with XeLaTeX. This project offers a flexible layout with multiple page styles to effectively showcase your professional profile.

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
- Build Tools: Makefile (inferred from `make` commands)
- Python: helper build script (`python-build.py`) automates dependency installation and building

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

Build the PDF resume using Makefile commands:

```bash
make clean
make html
```

Alternatively, run the Python build script to automate the process:

```bash
python python-build.py
```

## Project Structure

```
architect-resume/
├── deployz/                 # Deployment scripts or related assets
├── sections/                # Resume sections as separate LaTeX files
├── my-resume.cls            # Custom LaTeX class defining the resume style
├── resume.tex               # Main LaTeX source file
├── resume.pdf               # Generated PDF resume
├── python-build.py          # Python script automating build and deployment
├── README.md                # This documentation file
├── LICENSE                  # License file
├── *.png, *.jpeg            # Example images and headshots
```

## Future Work / Roadmap

- Add more customizable templates and layout options
- Integrate continuous integration for automated PDF builds
- Expand documentation with usage examples and customization guides
- Support additional output formats such as HTML or Word exports
- Improve build script with error handling and logging

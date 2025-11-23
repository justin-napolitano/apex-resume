# apex-resume

A LaTeX-based resume/CV project using a custom document class and automated build scripts. This repository contains the source files, custom class, and automation tools to generate a professional resume PDF.

## Features

- Custom LaTeX class (`my-resume.cls`) tailored for resume formatting
- Automated build process using Python scripts and Makefile
- Support for single- or double-sided document layouts
- Integration of graphics and icons via TikZ, FontAwesome, and Academicons
- Sample resume source and output files included

## Tech Stack

- LaTeX (TeX Live compatible)
- Python 3 (for build automation)
- Make
- TikZ, tcolorbox, fontawesome, academicons LaTeX packages

## Getting Started

### Prerequisites

- LaTeX distribution installed (e.g., TeX Live, MiKTeX)
- Python 3
- Make

### Installation

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/apex-resume.git
cd apex-resume
```

Install Python dependencies if any (assumed from `requirements.txt`):

```bash
pip install -r requirements.txt
```

### Build Resume

Use the provided Python build script or Makefile to compile the resume:

```bash
# Clean previous builds
make clean

# Build PDF resume
make pdf
```

Alternatively, run the Python build script:

```bash
python3 python-build.py
```

## Project Structure

```
/apex-resume
├── deployz/               # Possibly deployment-related scripts or assets
├── sections/              # Resume content sections (assumed)
├── my-resume.cls          # Custom LaTeX resume class
├── python-build.py        # Python script automating build and deployment
├── resume.tex             # Main LaTeX resume source
├── README.md              # This file
├── LICENSE                # License file
├── resume.pdf             # Generated resume PDF
├── resume-*.png           # Sample resume images
├── *.log, *.aux, *.out    # LaTeX build auxiliary files
└── head_shot.jpeg, picture.jpg  # Images for resume
```

## Future Work / Roadmap

- Add detailed documentation and usage examples
- Enhance build automation with error handling and logging
- Support for multiple resume templates
- Integration with CI/CD pipelines for automatic deployment
- Improve README with screenshots and usage instructions

---

*Note: Some assumptions were made regarding the purpose of folders and build commands due to limited documentation.*
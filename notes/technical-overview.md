---
slug: github-apex-resume-note-technical-overview
id: github-apex-resume-note-technical-overview
title: apex-resume
repo: justin-napolitano/apex-resume
githubUrl: https://github.com/justin-napolitano/apex-resume
generatedAt: '2025-11-24T18:30:48.479Z'
source: github-auto
summary: >-
  The **apex-resume** repo is a LaTeX-based project for generating professional
  resumes. It includes a custom LaTeX class, build scripts, and sample files.
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

The **apex-resume** repo is a LaTeX-based project for generating professional resumes. It includes a custom LaTeX class, build scripts, and sample files.

### Key Features
- Custom LaTeX class (`my-resume.cls`) for tailored formatting.
- Automated build with Python scripts and Makefile.
- Supports single or double-sided layouts.
- Integrates graphics using TikZ and FontAwesome.

### Getting Started

**Prerequisites:**
- LaTeX (TeX Live or MiKTeX)
- Python 3
- Make

**Installation:**
Clone the repo and install any Python dependencies:

```bash
git clone https://github.com/justin-napolitano/apex-resume.git
cd apex-resume
pip install -r requirements.txt
```

**Build the Resume:**

```bash
make clean   # Clean old builds
make pdf     # Generate PDF
```

Or use the Python script:

```bash
python3 python-build.py
```

### Gotchas
Ensure all required LaTeX packages are installed. Check the build logs for issues.

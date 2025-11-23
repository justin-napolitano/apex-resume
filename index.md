---
slug: "github-apex-resume"
title: "apex-resume"
repo: "justin-napolitano/apex-resume"
githubUrl: "https://github.com/justin-napolitano/apex-resume"
generatedAt: "2025-11-23T08:13:51.621086Z"
source: "github-auto"
---


# Building my own LaTeX Resume Template: my-resume

Hey there! I wanted to share a little project I've been working on called **my-resume** — a custom LaTeX template for creating resumes and CVs. If you've ever struggled with making your resume look just right or wanted a template that fits *your* style perfectly, this might resonate with you.

## Why I Built my-resume

When it comes to resumes, I’ve always found the existing templates either too rigid or overly complex. I love the clean, professional look of templates like AltaCV and AwesomeCV, but I wanted something that did exactly what *I* needed without extra bells and whistles. Plus, I wanted full control over the styling and layout without wrestling with tons of packages or code I didn’t understand.

That’s where **my-resume** came in. It’s a LaTeX class I wrote from scratch that gives me flexibility with page styles, highlight bars, headers, and more — all running on XeLaTeX to leverage modern font and graphics capabilities.

## How It's Built

At the core is the `my-resume.cls` file, a custom LaTeX class that defines options like single-sided or double-sided layouts. It uses TikZ and tcolorbox for drawing highlight bars and styling elements, and it supports fontawesome and academicons for including icons easily.

The main resume content lives in `resume.tex`, which loads this class and fills in the sections. I also included a `python-build.py` script that automates building the resume by running `make clean` and `make html` commands, handling dependencies, and even committing and pushing changes if needed.

I’ve included example PDFs and images to showcase different page styles — from full headers with highlight bars to empty pages — so you can see the flexibility in action.

## Interesting Details

- The class supports an option to toggle between single-sided documents (highlight bar always on the left) and double-sided documents (highlight bar alternates sides). This subtle feature adds polish for printed resumes.
- The build script is a neat little Python automation that runs shell commands and manages dependencies, making it easy to update and rebuild the resume with a single command.
- I borrowed some ideas and code snippets from popular templates but rewrote everything to fit my personal workflow and preferences.

## Why this project matters for my career

Creating **my-resume** was more than just making a document — it was about mastering LaTeX and automation to present myself professionally. It pushed me to deepen my understanding of document preparation systems, scripting, and build pipelines. Plus, having a polished, customizable resume template means I can quickly tailor my CV for different job applications without starting from scratch each time.

This project reflects my commitment to quality and attention to detail, qualities I bring to all my software development work. It’s a tangible example of my ability to combine creativity with technical skills — something that definitely matters in my career journey.

---

Thanks for reading! If you’re interested, check out the repo and feel free to reach out with questions or suggestions.
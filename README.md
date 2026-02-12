# UCPM Collection Points Library

This repository is a shared library of **UCPM Collection Point demos**, implemented as standalone HTML files.

Each Collection Point represents a self-contained consent or preference experience that can be easily reviewed, shared, and reused by internal teams or during customer demos.

---

## Table of Contents

- [What is this repository?](#what-is-this-repository)
- [How this repository works](#how-this-repository-works)
- [How to upload your Collection Point](#how-to-upload-your-collection-point)
  - [1. Create your Collection Site](#1-create-your-collection-site)
  - [2. Commit the file](#2-commit-the-file)
  - [3. Access the Collection Points library](#3-access-the-collection-points-library)
- [How to create a Collection Point](#how-to-create-a-collection-point)
- [Why GitHub and GitHub Pages?](#why-github-and-github-pages)
- [Contribution guidelines](#contribution-guidelines)

---

## What is this repository?

This repository contains a collection of **UCPM Collection Point demos**, each stored as a **single HTML file**.

The purpose of this repository is to:

- Maintain a **centralized library** of Collection Point demos
- Make it easy to **add, discover, and preview** Collection Sites
- Provide **live URLs** that can be shared with customers or internal teams
- Keep demos **versioned, traceable, and easy to update**

---

## How this repository works

This repository uses **GitHub Pages** to host static HTML files.

At a high level:

- Each Collection Point is a **single `.html` file**
- Files are stored in the repository and committed to `main`
- GitHub Pages automatically:
  - Rebuilds the site
  - Regenerates the index of Collection Points
  - Hosts each file as a live URL

No servers, deployments, or build pipelines are required.

---

## How to upload your Collection Point

This section explains **how to add a new Collection Point demo** so it appears in the shared library.

### 1. Create your Collection Site

- Your Collection Point **must be a single HTML file**
- The file should be fully self-contained:
  - HTML
  - CSS
  - JavaScript
- Place the file inside the **`demo/` folder**

Example structure:

```text
demo/
└── ucpm-basic-banner.html

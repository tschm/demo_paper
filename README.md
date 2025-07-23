# 📄 [Demo](https://github.com/tschm/ppp1/blob/draft/document.pdf)

[![LaTeX](https://github.com/tschm/ppp1/actions/workflows/latex.yml/badge.svg)](https://github.com/tschm/ppp1/actions/workflows/latex.yml)
[![Created with qCradle](https://img.shields.io/badge/Created%20with-qCradle-blue?style=flat-square)](https://github.com/tschm/paper)

<!-- Add your arXiv badge here when available -->
<!-- [![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX) -->

## 📝 Abstract

This project provides a comprehensive LaTeX template for academic 
papers with automated build and release processes. 
It features customizable headers, environment variable integration, 
GitHub Actions workflows for continuous integration, and a streamlined
development workflow using Tectonic for reliable LaTeX compilation.

## 🔗 Link to a companion Python package

<!-- Update this link to your actual companion package if available -->
Companion [Python package](https://github.com/tschm)

## 🚀 Getting started

### **📋 Customize the README.md file**

Update this README with your project-specific information:

- Add your project's abstract
- Update links to your companion packages or resources
- Add any additional sections relevant to your project

### **✏️ Edit the LaTeX document**

The main LaTeX file is `paper/document.tex`. 
Edit this file to add your content.
We use [tectonic](https://github.com/tectonic-typesetting/tectonic)
to compile LaTeX files. The resulting PDF documents are automatically released
to the [draft branch](https://github.com/tschm/ppp1/tree/draft)
of the repository.

### **🏷️ Repository Tags**

The document can display metadata in the header.

Both in latex.yml and release.yml we create a file `header.txt` 
where we extract the sha or the current tag. This allows you to add custom text
to the header without modifying the LaTeX code.

### **🔍 Viewing Your Document**

The title at the top of this README (marked with 📄) links to your compiled document in the draft branch. This provides an easy way to access the latest version of your document without having to download the PDF file.

### **⚙️ Installation and Setup**

To set up the development environment:

1. **Install Tectonic**:

  ```bash
   make install
   ```

2. **Compile the document**:

  ```bash
   make compile
   ```

3. **Clean up generated files**:

  ```bash
   make clean
   ```

For more details on available commands, run:

```bash
make help
```

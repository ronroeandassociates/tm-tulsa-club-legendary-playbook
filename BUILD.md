# BUILD.md

Build and export instructions for the **Tulsa Club Legendary Playbook** repository.

This document defines how Markdown source files in the repository are converted into member-facing and leadership-facing artifacts such as **PDF** and **DOCX**.

---

# Build Philosophy

The repository stores the **source of truth**.

Source files are authored in Markdown and organized by project governance structure.  
Exports are generated from those Markdown files for:

- member consumption
- officer use
- review drafts
- website publishing
- archival packaging

Core rule:

> Git stores source.  
> Build commands generate artifacts.  
> Published outputs are derived, not primary.

---

# Recommended Environment

## Required Tools

- **Pandoc**
- **PowerShell**
- Optional:
  - LaTeX engine for PDF generation
  - Microsoft Word for DOCX review/editing
  - VS Code or Cursor for Markdown editing

## Verify Pandoc

Run:

```powershell
pandoc --version
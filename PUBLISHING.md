
---

# `PUBLISHING.md`

```markdown
# PUBLISHING.md

Publishing guide for the **Tulsa Club Legendary Playbook**.

This document defines how repository source materials are exposed to club members and officers through the **FreeToastHost** website and other controlled delivery channels.

---

# Publishing Philosophy

The repository is the **authoritative source layer**.

The website is the **access and navigation layer**.

Published outputs should be:

- member-friendly
- stable
- easy to access on mobile
- separated from raw working documentation

Core rule:

> Do not publish raw working structure when a member-facing artifact is more appropriate.

---

# Delivery Architecture

```text
GitHub Repository
    ↓
Markdown Source Files
    ↓
Pandoc Export
    ↓
PDF / DOCX / Web Copy
    ↓
FreeToastHost Club Website
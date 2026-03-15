# Tulsa Club Legendary Playbook

Operational playbook for **Tulsa Toastmasters Club #148**.

This repository contains the structured documentation, facilitator scripts, meeting systems, and operational standards used to run a **high-performance Toastmasters club**.

The playbook is designed to provide:

* consistent meeting quality
* rapid onboarding of new members
* institutional memory
* replicable club systems

This repository stores the **source documentation and system architecture** for the playbook.

Member-facing materials are published separately through the club website.

---

# Repository Purpose

The Legendary Playbook defines the **operating system of the club**.

It includes:

* meeting architecture
* role scripts
* officer operating procedures
* event systems
* templates and tools
* institutional reference material

The goal is to move the club from **ad-hoc operation** to **structured execution**.

---

# Repository Structure

This project follows the **PARA project governance model**.

```
P_TM_TulsaClub_Legendary_Playbook_v1
│
├─ 00_Project_Charter
│
├─ 01_Deliverables
│   ├─ Playbook_Core
│   ├─ Facilitator_Scripts
│   ├─ Officer_SOPs
│   ├─ Meeting_SOPs
│   ├─ Event_SOPs
│   └─ Templates
│
├─ 02_Reference
│
└─ 03_Completion
```

### Folder Roles

| Folder                 | Purpose                                    |
| ---------------------- | ------------------------------------------ |
| **00_Project_Charter** | Project charter and scope definition       |
| **01_Deliverables**    | Operational playbook components            |
| **02_Reference**       | Research and reference materials           |
| **03_Completion**      | Lessons learned and closeout documentation |

---

# Deliverable Categories

## Playbook Core

Defines the philosophy and operating framework of the club.

Examples:

* club mission and culture
* meeting structure
* member development philosophy
* legendary meeting model

---

## Facilitator Scripts

Role scripts that enable members to confidently perform meeting roles.

Examples:

* Presiding Officer
* Table Topics Master
* Speech Evaluator
* General Evaluator
* Timer
* Ah-Counter
* Grammarian
* Closing

These scripts help maintain **consistent meeting execution**.

---

## Officer SOPs

Operating procedures for club officers.

Examples:

* President
* Vice President Education
* Vice President Membership
* Vice President Public Relations
* Secretary
* Treasurer
* Sergeant at Arms

These documents define the **institutional memory of club leadership**.

---

## Event Systems

Frameworks used to run special club events.

Examples:

* Open House events
* Speech contests
* guest conversion events
* networking formats such as **Speak & Connect**

---

## Templates

Reusable operational tools.

Examples:

* speech introduction template
* evaluation template
* meeting agenda template
* event planning templates

---

# Publishing Model

This repository contains **source documentation**.

Member-accessible materials are distributed through the club website.

Architecture:

```
GitHub Repository
      │
      │ Source Documentation
      ▼
Pandoc / Export
      │
      ▼
PDF / Member-Friendly Documents
      │
      ▼
FreeToastHost Website
```

The website acts as the **access layer** while GitHub remains the **source of truth**.

---

# Build Workflow

Documentation is authored in **Markdown**.

Example export using Pandoc:

```
pandoc Script_Timer_v1.0.md -o Script_Timer_v1.0.pdf
```

Full playbook builds may combine multiple documents into a single export.

---

# Governance

This repository follows the author's **PARA Governance Doctrine**:

Key principles include:

* strict project folder structure
* clear separation between deliverables and reference material
* versioned artifacts
* documentation of lessons learned and verification

---

# Contribution Model

This repository is primarily maintained by the club leadership team.

Suggested workflow:

```
Edit Markdown
Commit changes
Generate PDF outputs
Publish updates to club website
```

All structural changes should maintain the **PARA folder structure**.

---

# Intended Outcome

The Legendary Playbook enables the club to operate as a **repeatable system rather than an improvised meeting**.

Benefits include:

* higher meeting quality
* faster member development
* easier officer transitions
* scalable club growth

---

# License

Internal club operational documentation.

Usage is intended for **Tulsa Toastmasters Club operations and leadership development**.

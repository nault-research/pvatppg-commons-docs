# [pvatppg-commons-docs](https://nault-research.github.io/pvatppg-commons-docs/)

_More details to come_

# Gen3 Naming Standards: Program, Project, and Study

This document describes the naming conventions and organizational logic for the three levels of the Gen3 Data Commons hierarchy. Following these standards keeps the Gen3 commons consistent and navigable for both internal teams and external data consumers.

---

## The Gen3 Hierarchy

```
Program
└── Project  ←  unit of public release
    └── Study
```

| Level | Entity | Role |
|-------|--------|------|
| 1 | **Program** | Administrative grouping representing a lab, center, or initiative (e.g., `NAULTLAB`, `MSUSRC`, `PVATPPG`). Admin-assigned. |
| 2 | **Project** | A self-contained body of work. The unit of public data release (e.g., `PVATPPG_0012`, `MSUSRC_0004`). Admin-assigned. |
| 3 | **Study** | A subdivision within a Project. Default set to one per Project (e.g., `Main`, `Replication Cohort`). Admin-assigned.|

---

## Program

Programs are administrative. They represent a lab, center, or initiative and serve as the organizational owner of all Projects beneath them. Program codes are defined by the Data Commons administrator.

**Format:** Short uppercase acronym, no separators.

| Example | Represents |
|---------|------------|
| `NAULTLAB` | Nault Lab |
| `MSUSRC` | MSU Superfund Research Center |
| `PVATPPG` | PVAT Program Project Grant |

- Maximum 15 characters

---

## Project

A Project is the core organizational unit in Gen3. It represents a self-contained body of work and is the level at which data becomes public. All datasets associated with a body of work — weights, RNAseq, metabolomics, etc. — live together under one Project.

**Format:**

```
[PROGRAM]_[NNNN]
```

- Program code prefix, underscore, zero-padded four-digit sequential number
- Assigned by the Data Commons administrator
- Maximum 20 characters

**Examples:**

```
NAULTLAB_0001
MSUSRC_0004
PVATPPG_0012
```

### Key rules

- **Admin-assigned.** Contact your Data Commons administrator to request a new Project. This prevents numbering collisions and maintains a central registry.
- **Subjects belong to one Project.** Cross-project subject linking is not supported in Gen3. Define Project boundaries around data that naturally belongs together.
- **Public release is all-or-nothing at the Project level.** When a Project is made public, all Studies beneath it become public simultaneously. Plan your Project boundaries with this in mind.
- **Names are permanent.** Renaming a Project after data submission begins is technically complex and may break data references and external links.

---

## Study

A Study is a subdivision within a Project. In most cases there will be only one Study per Project. The distinction only matters when a Project contains a clearly separable sub-dataset (e.g., a replication study) that will definitively always be released alongside the main data.

**Default: Only one Study per Project.**

Multiple Studies are only created when:

- There is a replication or validation dataset that is part of the same Project
- The sub-dataset has a meaningfully different provenance or design but belongs to the same release unit
- You are certain it will always be released together with the other Studies in the Project

### Naming expectations

Studies names are assigned by the administrator, but may be requested by the submitter. Since Studies are the most granular level, this is where human-readable context lives. If you choose to request a Study name:

- Use plain descriptive language — no codes or IDs needed
- Title Case
- Include what distinguishes this Study from others in the same Project, if applicable
- Avoid restating the Project name or number
- Max 60 characters

| ✔ | ✘ |
|---|---|
| `Main` | `NAULT-0001-Study` |
| `Replication Cohort` | `study_final_v2` |
| `High Dose Validation Set` | `Study1` |

---

## Quick Reference

| Entity | Format | Assigned By | Max Length | Public? |
|--------|--------|-------------|------------|---------|
| Program | `ACRONYM` | Administrator | 15 chars | Indirect |
| **Project** | `[PROGRAM]_[NNNN]` | **Administrator** | 20 chars | **Yes ⚠️** |
| Study | Descriptive phrase | Administrator | 60 chars | With Project |

---

## Requesting a New Project

Reach out to your Data Commons administrator with:

1. The **Program** it belongs to (e.g., `MSUSRC`, `PVATPPG`)
2. A brief description of the body of work (used for the internal registry — not the Project name)
3. Any known Studies you plan to create beneath it

The administrator will assign the next available Project number, register it, and confirm you can proceed.
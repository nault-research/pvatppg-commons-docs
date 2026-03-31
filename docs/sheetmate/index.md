
# What is SheetMATE?

SheetMATE (Google Sheets–based <b>M</b>etadata <b>A</b>lignment and <b>T</b>emplatization <b>E</b>ngine) is a Google Sheets add-on that streamlines the creation, validation, and submission of structured metadata for PVAT PPG datasets. It is developed to make simplify robust structured metadata collection, entry, and submission to the [PVAT PPG Data Commons](http://data.pvatppgmsu.com).

---

## Features

- **Google Sheets-based**: Familiar spreadsheet interface with drop-downs and validation.
- **Template-driven**: Schema-defined templates ensure consistent metadata entry across studies, assays, and labs.
- **Validation**: Built-in rules check for required fields, controlled vocabularies, and formatting before submission.
- **Export & Submission**: Convert sheets into structured files that can be uploaded to repositories like ToxDataCommons (Gen3).
- **Versioning & Reuse**: Templates can be version-controlled, extended, and customized for specific projects.

---

## Why SheetMATE?

Metadata entry is often a major bottleneck for data reuse. Public repositories may accept datasets but lack the detailed experimental metadata required for reproducibility, integration, and AI-readiness. SheetMATE addresses this gap by:

1. Lowering the barrier for researchers to record rich metadata in a familiar interface.
2. Enforcing standards through schema-based templates and validation.
3. Generating machine-readable metadata that can plug directly into modern data commons platforms.

---


## Getting started

To begin using SheetMATE:

1. Open your Google Sheet  
2. Navigate to: **Extensions → App Script**  
3. Run the SheetMATE script  
4. A new menu named **ToxDataCommons** will appear  

From there, you can:

- populate metadata templates  
- create a data file manifest  
- begin structuring your submission  

[Go to setup instructions](setup.md)

---

## Important notes

!!! warning
    SheetMATE is under active development. You may encounter incomplete features or unexpected behavior.

!!! note
    If you prefer not to run the App Script, contact the team for template-based alternatives.

---

## How it fits into the workflow

SheetMATE is used at multiple stages of submission:

1. **Initialize study metadata**  
2. **Create file manifest**  
3. **Populate metadata templates**  
4. **Link data to metadata**

[See full walkthrough](../getting-started/walkthrough.md)
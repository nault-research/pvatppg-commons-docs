# File Formats

## Open Formats

Whenever possible, use **open, non-proprietary file formats** for data submission.

Open formats ensure that your data can be:

- accessed without specialized or licensed software  
- reused by others across different platforms  
- integrated into downstream analyses and workflows  
- preserved over time without dependency on vendor-specific tools  

Proprietary formats are accepted when necessary, but may limit interoperability, reproducibility, and long-term usability.

---

### Examples of Open Formats

Common open formats include:

- Tabular data → TSV, CSV  
- Imaging data → OME-TIFF  
- Sequencing data → FASTQ, BAM  
- Mass spectrometry → mzML  

Common Closed Formats that are sometimes acceptable:

- Excel → XLSX; Most have access but it is preferable to convert to open format
- Prism → PZF; It is recommended to only provide the tabular data in a structured format instead. 

---

## PVAT PPG Commons Supported Data

<b>weight_measurements</b>
??? info "Weight Measurements"

    | Data Type | Description | Supported Formats |
    |----------|------------|------------------|
    | Body weight | weight measurement | TSV, CSV |
    | Sample weight | weight measurement | TSV, CSV |
    | Food weight | weight measurement | TSV, CSV |

<b>cardiovascular_measurements</b>
??? info "Cardiovascular Measurements"

    | Data Type | Description | Supported Formats |
    |----------|------------|------------------|
    | MAP (Mean Arterial Pressure) | Blood pressure measurement | TSV, CSV |
    | SBP (Systolic Blood Pressure) | Blood pressure measurement | TSV, CSV |
    | DBP (Diastolic Blood Pressure) | Blood pressure measurement | TSV, CSV |
    | Heart Rate (HR) | Cardiac rhythm measurement | TSV, CSV |
    | Pulse Pressure (PP) | Derived blood pressure metric | TSV, CSV |
    | Heart Rate Variability (HRV) | Autonomic function metric | TSV, CSV |
    | Cardiac Output (CO) | Cardiac function measurement | TSV, CSV |
    | Stroke Volume (SV) | Cardiac function measurement | TSV, CSV |
    | Systemic Vascular Resistance (SVR) | Hemodynamic parameter | TSV, CSV |
    | Left Ventricular Ejection Fraction (LVEF) | Cardiac function measurement | TSV, CSV |
    | Cardiac Index (CI) | Normalized cardiac output | TSV, CSV |
    | End-Systolic Volume (ESV) | Ventricular volume measurement | TSV, CSV |
    | End-Diastolic Volume (EDV) | Ventricular volume measurement | TSV, CSV |
    | Left Ventricular End-Diastolic Pressure (LVEDP) | Cardiac pressure measurement | TSV, CSV |
    | Aortic Pulse Wave Velocity (PWV) | Arterial stiffness metric | TSV, CSV |
    | Central Augmentation Index (AIx) | Arterial stiffness metric | TSV, CSV |
    | Ankle-Brachial Index (ABI) | Peripheral vascular assessment | TSV, CSV |
    | Carotid Intima-Media Thickness (CIMT) | Structural vascular measurement | TSV, CSV |
    | Myocardial Perfusion (MP) | Cardiac perfusion measurement | TSV, CSV |
    | Coronary Flow Reserve (CFR) | Coronary circulation metric | TSV, CSV |
    | QT Interval (QTc) | Cardiac electrical measurement | TSV, CSV |
    | Left Atrial Volume Index (LAVI) | Cardiac structure measurement | TSV, CSV |
    | Mitral Annular Plane Systolic Excursion (MAPSE) | Cardiac function measurement | TSV, CSV |
    | Global Longitudinal Strain (GLS) | Myocardial deformation metric | TSV, CSV |
    | Troponin (hs-Troponin) | Cardiac injury biomarker | TSV, CSV |
    | BNP / NT-proBNP | Cardiac stress biomarker | TSV, CSV |
    | C-Reactive Protein (CRP) | Inflammation marker | TSV, CSV |
    | Endothelial Function (e.g., FMD) | Vascular function assessment | TSV, CSV |

<b>clinical_chemistry_measurements</b>
??? info "Clinical Chemistry"

    | Data Type | Description | Supported Formats |
    |----------|------------|------------------|
    | Clinical chemistry measurements | Quantitative measurements derived from assays, regardless of platform (e.g., automated analyzers, plate-based assays, cuvette-based systems) | TSV, CSV |

<b>slide_imaging_data</b>
??? info "Slide imaging data"
    | Data Type | Description | Formats |
    |----------|------------|--------|
    | Field of view image | A selected representative portion o fa tissue taken by a microscope | TIFF |
    | Whole slide scan | A digitized slide through a scanner or equivalent | OME-TIFF, SVS, VSI (zip) |

---

## Additional Resources

The following resources provide guidance on recommended and supported formats:

- [National Archives – Transfer Guidance Tables](https://www.archives.gov/records-mgmt/policy/transfer-guidance-tables.html)  
- [Bio-Formats Supported Imaging Formats](https://bio-formats.readthedocs.io/en/stable/supported-formats.html)  
- [PRIDE File Formats](https://www.ebi.ac.uk/pride/markdownpage/pridefileformats)  
- [Metabolomics Workbench Data Submission](https://www.metabolomicsworkbench.org/data/DRCCDataDeposit.php)  
- [MASSive Repository](https://massive.ucsd.edu/ProteoSAFe/static/massive.jsp?redirect=auth)  
- [ISAC Data Standards (Flow Cytometry)](https://isac-net.org/page/Data-Standards)  
- [GEO Submission Guidelines](https://www.ncbi.nlm.nih.gov/geo/info/submission.html)  

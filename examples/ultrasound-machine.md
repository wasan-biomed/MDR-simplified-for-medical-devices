# Ultrasound Machine – MDR Example

This document explains how to apply the European Medical Device Regulation (MDR 2017/745) to an **ultrasound machine**. Intended for biomedical engineers and regulatory learners.

---

##  1. Device Description

An **ultrasound machine** uses high-frequency sound waves to generate real-time images of internal organs, tissues, and blood flow.

Types:
- General imaging (abdomen, pelvis)
- Cardiac (echocardiography)
- Obstetric & fetal
- Doppler (blood flow measurement)

---

##  2. MDR Classification

According to **MDR Annex VIII, Rule 10** and **Rule 9**:

> **“Devices intended to monitor vital physiological parameters, or provide diagnostic imaging, are at least Class IIa.”**

- **Standard diagnostic ultrasound** = **Class IIa**  
- **Echocardiography or obstetric use (critical diagnosis)** = **Class IIb**

---

##  3. Technical Documentation (Annex II)

Must include:

- Block diagram of system architecture
- Probe specs: frequency, materials, max output power
- Imaging modes: B-mode, M-mode, Doppler, Color Flow
- Safety of acoustic output (TI, MI indices)
- Display hardware and image processing details
- Software logic (IEC 62304)
- Biocompatibility of probe materials (ISO 10993)
- Electrical and EMC test results (IEC 60601-1, -1-2)
- Cooling systems (if needed)

---

##  4. Clinical Evaluation (Annex XIV)

Must demonstrate:

- Image quality and diagnostic reliability
- Comparison with gold-standard devices
- Performance for each intended use (abdomen, OB/GYN, cardiac…)
- Accuracy of Doppler measurement (if applicable)

---

##  5. Labeling & IFU (Annex I)

Include:

- CE marking and UDI
- Probe cleaning and disinfection procedure
- Safe use duration (exposure limits)
- Contraindications (e.g. thermal risks)
- Electrical safety warnings
- Explanation of display icons and functions

---

##  6. CE Marking

- Requires **Notified Body** involvement for both IIa and IIb
- Typical path: **Annex IX** (Full QMS audit)
- Need ISO 13485 QMS certification
- Declaration of Conformity to MDR Annex IV

---

##  7. Post-Market Surveillance

- Monitor image quality issues or software failures
- Collect clinician feedback and usage reports
- Analyze temperature-related tissue effects (thermal index)
- Implement PMS plan + vigilance reporting

---

##  8. Economic Operators

Define clearly:

- Manufacturer
- Authorized Representative (if outside EU)
- Importer / Distributor
- Field service provider (if relevant)

Each has MDR-defined responsibilities.

---

## ⚠ 9. Relevant Standards

- **IEC 60601-1** – Electrical safety
- **IEC 60601-1-2** – EMC
- **IEC 60601-2-37** – Particular safety for ultrasound
- **IEC 62304** – Medical software lifecycle
- **IEC 62366** – Usability engineering
- **ISO 10993** – Biocompatibility
- **ISO 14971** – Risk management

---

##  Summary

| Step                         | Action                                      |
|------------------------------|---------------------------------------------|
| Classification               | Class IIa or IIb                            |
| Technical File               | Design, acoustic safety, software, EMC      |
| Clinical Evaluation          | Imaging quality, accuracy, comparisons      |
| Label & IFU                  | CE, cleaning, warnings, usage icons         |
| Conformity Assessment        | Notified Body + Annex IX                    |
| Post-Market Surveillance     | PMS, reports, acoustic monitoring           |
| Economic Operators           | All roles defined under MDR                 |

---

**Note:** This is an educational summary and not a substitute for official MDR compliance consulting.

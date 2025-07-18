# ECG Machine – MDR Example

This document explains how to apply the European Medical Device Regulation (MDR 2017/745) to an **ECG (Electrocardiograph)** machine. It serves as a real-world example for biomedical engineers and students.

---

##  1. Device Description

An **ECG machine** records the electrical activity of the heart through electrodes placed on the patient’s skin. It helps in diagnosing arrhythmias, ischemia, and other cardiac conditions.

Variants:
- Portable (single-lead or 3-lead)
- Hospital-grade (12-lead with printing & storage)
- Integrated with patient monitors

---

##  2. MDR Classification

According to MDR Annex VIII, Rule 10:

> **"Devices intended for monitoring physiological parameters where the nature of variations is such that it could result in immediate danger are Class IIb."**

Depending on the model:

- **Basic ECGs** (for routine diagnostic use):  
  ➤ **Class IIa**

- **Critical-care ECGs** (used in ICU or emergency):  
  ➤ **Class IIb**

---

##  3. Technical Documentation (Annex II)

The technical file must include:

- Device description (leads, cables, display, power)
- Block diagrams and circuit descriptions
- List of electronic components
- Software architecture and logic flow (if applicable)
- Risk analysis and mitigation (IEC 60601 + ISO 14971)
- Electromagnetic compatibility (EMC) test reports
- Data storage, transmission & security (if digital)
- Calibration and signal accuracy validation
- Cleaning and maintenance instructions

---

##  4. Clinical Evaluation (Annex XIV)

You must provide:

- Clinical performance studies or literature data
- Equivalence data with predicate devices
- Accuracy of signal detection and waveform integrity
- Studies validating diagnostic value

---

##  5. Labeling & IFU (Annex I)

Must include:

- CE marking
- UDI code
- Manufacturer info
- Electrical safety warnings
- Proper electrode placement diagram
- Maintenance and calibration schedule
- Instructions for safe data transfer (if applicable)

---

##  6. CE Marking

- Requires Notified Body involvement (for Class IIa or IIb)
- Perform conformity assessment (Annex IX or XI)
- Maintain a certified QMS (e.g., ISO 13485)
- Issue a Declaration of Conformity

---

##  7. Post-Market Surveillance

- Implement a PMS plan (track malfunctions, waveform errors)
- Collect real-world performance feedback
- Report serious incidents (MDR Article 87)
- Submit Periodic Safety Update Reports (PSUR)

---

##  8. Economic Operators

Define and document:

- Manufacturer
- Authorized Representative (if outside EU)
- Importer
- Distributor

Ensure each actor fulfills MDR responsibilities (Articles 11–16).

---

## ⚠ 9. Standards to Apply

- **ISO 14971** – Risk Management
- **IEC 60601-1** – Electrical Safety
- **IEC 60601-2-25** – ECG-specific Safety
- **IEC 62304** – Software lifecycle (if applicable)
- **IEC 62366** – Usability Engineering
- **ISO 14155** – Clinical Investigations (if needed)

---

##  Summary

| Step                         | Action                                      |
|------------------------------|---------------------------------------------|
| Classification               | Class IIa or IIb                            |
| Technical File               | Design, software, safety, EMC               |
| Clinical Evaluation          | ECG accuracy and equivalence                |
| Label & IFU                  | CE, warnings, lead placement, maintenance   |
| Conformity Assessment        | Notified Body (Annex IX or XI)              |
| Post-Market Surveillance     | PSURs, incident reports, software issues    |
| Economic Operators           | Roles for manufacturer, importer, etc.      |

---

This example is simplified for educational purposes. Always consult regulatory experts and Notified Bodies when preparing a device for EU market entry.

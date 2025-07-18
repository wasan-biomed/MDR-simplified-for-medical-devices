# Thermometer – MDR Example

This document explains how to apply the European Medical Device Regulation (MDR 2017/745) to a **medical thermometer**. It is intended for biomedical engineers and regulatory beginners.

---

##  1. Device Description

A **medical thermometer** is a device used to measure human body temperature. It can be:

- **Digital contact** (oral, rectal, underarm)
- **Infrared (non-contact)** – used on forehead or ear
- **Mercury-based** (mostly obsolete in EU)

---

##  2. MDR Classification

Under MDR **Annex VIII, Rule 1** and **Rule 10**:

| Type                       | Classification |
|----------------------------|----------------|
| Digital contact thermometer | **Class IIa**  |
| Infrared (forehead/ear)     | **Class IIa**  |
| Simple mercury thermometer  | **Class I** (non-sterile, no electronics)  |

> If the thermometer is **electronic**, it is usually **Class IIa**  
> If it's a simple **glass mercury device**, it's **Class I**

---

##  3. Technical Documentation (Annex II)

Must include:

- Device type, design drawings, photos
- Materials in contact with skin or mucosa
- Sensor and measurement technology
- Battery safety (if digital)
- Calibration data and accuracy validation
- Software logic (for infrared/digital types)
- Risk analysis (ISO 14971)
- Biocompatibility test results (ISO 10993)
- EMC and electrical safety (for Class IIa)

---

##  4. Clinical Evaluation (Annex XIV)

- Demonstrate accuracy across temperature ranges
- Compare with reference thermometers
- Prove consistency and repeatability
- Address skin type, distance, ambient conditions (for infrared types)

---

##  5. Labeling & IFU (Annex I)

Include:

- CE mark
- UDI code
- Measurement site instructions (ear, forehead, etc.)
- Cleaning and disinfection procedure
- Warning for battery usage (if applicable)
- Accuracy tolerance (e.g. ±0.2 °C)

---

##  6. CE Marking

- For **Class I**:  
  ➤ **Self-certification** is allowed, *no Notified Body needed*

- For **Class IIa**:  
  ➤ Must involve a **Notified Body**, with technical documentation review and QMS audit

In both cases, the **CE mark** must be affixed **before placing on the market**

---

##  7. Post-Market Surveillance

- Monitor accuracy and failures over time
- Address feedback about false readings
- Have a **PMS plan** in place
- Report serious incidents (MDR Article 87)

---

##  8. Economic Operators

Define:

- Manufacturer (even for simple Class I)
- Authorized Representative (if outside EU)
- Importer & distributor roles

---

## ⚠ 9. Relevant Standards

- **ISO 80601-2-56** – Clinical thermometers
- **ISO 14971** – Risk management
- **ISO 10993** – Biocompatibility
- **IEC 60601-1** – Electrical safety (if applicable)
- **IEC 60601-1-2** – EMC (for digital thermometers)

---

##  Summary

| Step                         | Action                                      |
|------------------------------|---------------------------------------------|
| Classification               | Class I or Class IIa                        |
| Technical File               | Design, accuracy, battery, safety           |
| Clinical Evaluation          | Accuracy, comparison with reference         |
| Label & IFU                  | CE mark, UDI, usage site, disinfection      |
| Conformity Assessment        | Class I = self-declared / Class IIa = NB    |
| Post-Market Surveillance     | Accuracy tracking, incident response        |
| Economic Operators           | Clearly defined roles                       |

---

This example is for educational use only and does not substitute formal regulatory guidance.

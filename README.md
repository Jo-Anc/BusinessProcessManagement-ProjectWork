# BPM Analysis & Logistics Optimization: Poste Italiane

##  Project Overview
This repository presents an in-depth **Business Process Management (BPM)** analysis of the parcel delivery lifecycle at Poste Italiane. The project aims to map the "As-Is" state, quantify operational gaps using a 7-parameter scoring model, and propose a "To-Be" digital transformation to reduce failed delivery rates and optimize the "First-Time Hit" success.

---

##  Methodology: The 7-Parameter Model
To ensure a data-driven approach, every process node was evaluated through **7 technical parameters** derived from the project framework:

1.  **Periodicity:** Activity frequency (from occasional to daily).
2.  **Technology Adoption:** Scored from 1 (Full Automation/AI) to 5 (Manual/Paper-based).
3.  **Organizational Relationships:** Complexity of coordination between different departments.
4.  **Inter-functional Tasks:** Number of hand-offs between distinct business functions.
5.  **Process Linearity:** Assessment of decision loops or structural bottlenecks.
6.  **Strategic Goal Importance:** Impact of the phase on final Customer Satisfaction.
7.  **Activity Volume:** Task density (ranging from 1-4 to 13-15 for the delivery phase).

---

## Quantitative Analysis (As-Is)
By applying these parameters, we calculated the **Weighted Value** for each macro-stage, revealing the true operational burden across the supply chain:

| Macro-Process | Weighted Value | Impact Percentage | Technology Status |
| :--- | :---: | :---: | :--- |
| **1. Acceptance & Registration** | 22 | **9.87%** | Normally Used |
| **2. Sorting & Transport** | 57 | **25.56%** | Highly Used (OCR) |
| **3. Planning & Delivery** | 144 | **64.57%** | **Poorly Used (Critical)** |

> **Key Insight:** The final delivery phase accounts for **64.57%** of the total process friction. This is due to maximum **Activity Volume (Score 5/5)** combined with fragmented technological support in the Last-Mile segment.

---

##  Proposed Solutions (To-Be)
To mitigate the weight of the delivery phase, the redesign focuses on 4 technological pillars:

* **Self-Service Check-in:** Full digitalization of the acceptance phase via QR Code integration to eliminate manual data entry.
* **Computer Vision (AI):** Evolution of OCR systems to drastically reduce scanning errors and manual sorting in Hubs.
* **AI Dynamic Routing:** Algorithmic path optimization for carriers based on real-time traffic and delivery priority.
* **Geofencing & Time Slots:** Automatic push notifications triggered when the carrier is within 1km, ensuring the recipient's presence.

---

## Repository Structure
* `POSTE ITALIANE.pdf`: Full technical report including parametrization tables.
* `Poste-AsIS-Flowchart`: Visual process mapping (Miro export).
* `github_bpm_preview.png`: Data dashboard summarizing project metrics.

---



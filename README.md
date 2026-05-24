# ITU-surveying-equipment-calibration
# Geodetic Instrument Calibration & Structural Axis Error Analysis

An advanced, data-driven geomatics engineering repository containing comprehensive instrument verification, structural axis calibration reports, and empirical field computations executed within the **Geomatics Equipment Laboratory at Istanbul Technical University (ITU)**. 

This project systematically models, detects, and isolates instrumental systematic errors through rigorous field workflows, data cleansing matrices, and structural adjustments conforming to geodetic tolerance standards.

---

## Repository Overview

The core repository is structured into two primary geodetic homework (HW) projects:
1. **PART I (HW1): Total Station Axis Conditions and Verification**
   * Comprehensive analysis of orthogonal axial relationships (Vertical, Horizontal, Sighting, and Bubble axes).
   * Dual-face (Face I / Face Left & Face II / Face Right) observation series over multiple sets.
   * Analytical determination and technical solutions for the Vertical Index Error ($\varepsilon$) and Horizontal Collimation Error ($c$).
2. **PART II (HW2): Optical-Mechanical Level Axis Conditions and Two-Peg Test**
   * Geometrical modeling of tilting/optical levels and principal leveling boundary constraints.
   * Empirical isolation of systematic collimation tilt errors ($e$) via asymmetrical baseline setups.
   * Formulation of precise hardware adjustment protocols using reticle diaphragm screw manipulation.

---

## 🛠️ Project Details & Technical Specifications

### PART I: Total Station Axis Verification
* **Objective:** Assess the perpendicularity conditions of the instrument's structural axes and eliminate systematic eccentricities.
* **Methodology:** Conducted 2 full sets (tam seri) of directional tracking towards low-elevation reference Point B ($\approx$ 78 grad) and high-elevation reference Point C ($\approx$ 77 grad). The second set utilized a $100^g$ horizontal circle re-indexing strategy to mitigate glass graduation imperfections.
* **Core Computational Findings:**
  * **Mean Vertical Index Error ($\varepsilon_{avg}$):** $+121.1^{cc}$ 
  * **Mean Horizontal Collimation Error ($c_{avg}$):** $+33.0^{cc}$ (with high-elevation variations indicating a compounding trunnion axis misalignment).
* **Legal Evaluation:** The residual values exceed the strict engineering tolerance thresholds ($\pm 20^{cc}$ to $\pm 30^{cc}$) defined by national large-scale surveying frameworks (**BÖHHBÜY**). Digital calibration routines and mechanical crosshair reticle shifting adjustments are documented as technical corrections.

### PART II: Optical Level Axis & Two-Peg Test
* **Objective:** Verify the principal axis condition mandating absolute parallelism between the line of sight (collimation axis) and the tubular spirit level axis.
* **Methodology:** Implemented a variable-baseline differential leveling geometry over a 60-meter path. 
  * *Station 1 (Midpoint Setup):* Symmetric 30-meter sight paths to eliminate error accumulation and capture the absolute True Elevation Difference.
  * *Station 2 (Outside Setup):* Asymmetric configuration (3m near sight, 63m distant sight) to isolate uncompensated angular tilt.
* **Core Computational Findings:**
  * **True Elevation Difference ($\Delta H_{true}$):** $1.085 \text{ m}$
  * **Apparent Elevation Difference ($\Delta H_{apparent}$):** $1.079 \text{ m}$
  * **Systematic Collimation Error ($e$):** $+6 \text{ mm}$ over the extended line path.
* **Adjustment Protocol:** Documented the mechanical intervention where the tubular bubble is manually centered via tilting screws and the crosshair reticle diaphragm plate is physically shifted via capstan adjustment pins from $2.691 \text{ m}$ to the mathematically true reference mark of $2.697 \text{ m}$.

---

## Consolidated Field Books (Cleaned Empirical Data)

### Total Station Horizontal Angles (Grad/Gon System)
| Set No | Target Point | Face I Reading (gon) | Face II Reading (gon) | Difference (Face II - Face I) |
|:------:|:------------:|:--------------------:|:---------------------:|:----------------------------:|
|   1    |      B       |        0.0000        |       200.0074        |           200.0074           |
|   1    |      C       |       345.2734       |       145.2896        |          -199.9838           |
|   2    |      B       |       100.0000       |       300.0024        |           200.0024           |
|   2    |      C       |       45.2728        |       245.2732        |           200.0004           |

### Optical Level Two-Peg Staff Readings (Three-Wire System)
* **Station 1 (Midpoint Setup):**
  * Staff A1 (30m) Center Reading: 2.216 | Computed Mean: **2.215**
  * Staff B1 (30m) Center Reading: 1.130 | Computed Mean: **1.130**
* **Station 2 (Outside Setup):**
  * Staff A2 (63m) Center Reading: 2.690 | Corrected Mean: **2.691**
  * Staff B2 (3m)  Center Reading: 1.612  | Computed Mean: **1.612**

---

## Core Geomatics Competencies Demonstrated
* Rigorous understanding of instrument dependencies and mathematical error propagation models.
* Execution of high-precision observation workflows (elimination of optical parallax, circle re-indexing, manual bubble alignment).
* Empirical data cleaning, processing, and validation techniques.
* Structural alignment, firmware calibration mapping, and mechanical adjustment execution.

---

## Contributors & Field Team
* **Harun Dayıoğlu** - *Geomatics Engineering Undergraduate, ITU*
* Project Partners & Course Colleagues 

## 🏛️ Academic Context
* **Institution:** Istanbul Technical University (İTÜ)  
* **Faculty:** Faculty of Civil Engineering  
* **Department:** Department of Geomatics Engineering  
* **Course:** Terrain Surveying Equipment and Softwares (GEO114E)  
* **Instructors:** Assoc. Prof. Dr. Turan Erden, Res. Asst. Muhammed Yahya Bıyık  

---


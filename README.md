# Molecular-Docking-Lithospermum
Molecular docking analysis of plant-derived compounds using AutoDock Vina

# Screening and Evaluation of Phytoconstituents of Lithospermum officinale for Thyroid Drug Targets
## 🚀 Key Result 
Lithospermic acid showed stronger binding affinity (-8.6 kcal/mol) compared to standard anti-thyroid drugs (~ -4 kcal/mol), indicating potential as a lead compound.

## 🔬 Project Highlights
- Molecular docking analysis of plant-derived compound Lithospermic acid
- Targeted thyroid-related proteins (TSH receptor, Thyroid peroxidase, Thyroglobulin)
- Comparative study with FDA-approved anti-thyroid drugs
- Identified strong binding affinity suggesting potential therapeutic application

## 🧬 Overview
This project focuses on evaluating phytoconstituents of *Lithospermum officinale* for their potential anti-thyroid activity using molecular docking.

The ligand Lithospermic acid was docked against multiple thyroid-related protein targets to analyze binding affinity and interaction patterns.

## 🧪 Tools Used
- AutoDock Vina
- AutoDock Tools
- PyMOL
- RCSB PDB
- PubChem

## ⚙️ Methodology

### 1. Protein Selection
- Retrieved thyroid-related protein structures from RCSB PDB:
  - 7UUY (Thyroid Peroxidase)
  - 7XW5 (TSH receptor)
  - 6SCJ (Thyroglobulin)

### 2. Ligand Preparation
- Selected Lithospermic acid from PubChem
- Downloaded 3D structure in SDF format

### 3. Docking Procedure
- Converted structures to .pdbqt format
- Defined grid box parameters
- Performed docking using AutoDock Vina
- Selected best binding pose based on lowest binding energy

### 4. Visualization
- Visualized protein–ligand interactions using PyMOL

## 📊 Results

### 🔹 Binding Energy (Plant Compound)
- 7UUY → **-8.6 kcal/mol**
- 7XW5 → -8.2 kcal/mol
- 6SCJ → -6.9 kcal/mol

### 🔹 Binding Energy (Standard Drugs)
- Methimazole → ~ -4.5 kcal/mol
- Propylthiouracil → ~ -3.9 kcal/mol
- Carbimazole → ~ -3.2 kcal/mol

## 📊 Comparison of Binding Energies

| Ligand | Target Protein | Binding Energy (kcal/mol) |
|--------|--------------|--------------------------|
| Lithospermic acid | 7UUY | -8.6 |
| Lithospermic acid | 7XW5 | -8.2 |
| Lithospermic acid | 6SCJ | -6.9 |
| Methimazole | 7UUY | -4.5 |
| Propylthiouracil | 7UUY | -3.9 |
| Carbimazole | 7UUY | -3.2 |

## 🔬 Docking Visualization

### 7UUY – Lithospermic Acid
![7UUY](dock_7UUY.png)
*Binding interaction of Lithospermic acid with 7UUY (Thyroid peroxidase) showing stable ligand positioning within active site.*

### 7XW5 – Lithospermic Acid
![7XW5](dock_7XW5.png)
*Binding interaction of Lithospermic acid with 7XW5 (Thyroid stimulating hormone receptor) showing stable ligand positioning within active site.*

### 6SCJ – Lithospermic Acid
![6SCJ](dock_6SCJ.png)
*Binding interaction of Lithospermic acid with 6SCJ (Thyroglobulin) showing stable ligand positioning within active site.*


## 🧪 Key Findings
- Lithospermic acid showed stronger binding affinity compared to standard drugs
- Best interaction observed with Thyroid Peroxidase (7UUY)
- Negative binding energies indicate stable protein–ligand interactions
- Suggests potential use as a lead compound for anti-thyroid drug development

## 🧠 Skills Demonstrated
- Molecular Docking
- Structural Bioinformatics
- Drug Discovery Concepts
- Protein-Ligand Interaction Analysis

## 📌 Conclusion
The study demonstrates that phytoconstituents of *Lithospermum officinale*, particularly Lithospermic acid, exhibit promising anti-thyroid activity and may serve as potential candidates for future drug development.
## Author
Harini R

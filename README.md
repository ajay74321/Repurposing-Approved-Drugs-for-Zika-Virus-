# 🧬 Repurposing Approved Drugs for Zika Virus

![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Project-blue)
![Drug Repurposing](https://img.shields.io/badge/Drug%20Repurposing-Computational-green)
![Molecular Docking](https://img.shields.io/badge/Molecular%20Docking-LibDock-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Description

Computational drug repurposing project targeting the **Zika virus NS2B-NS3 serine protease** using structure-based virtual screening, binding site prediction, molecular docking, and protein–ligand interaction analysis.

The project aims to identify potential antiviral compounds against Zika virus using computational bioinformatics and molecular docking approaches.

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Background](#-background)
- [Project Objective](#-project-objective)
- [Target Protein](#-target-protein)
- [Methodology](#️-methodology)
- [Binding Site Analysis](#-binding-site-analysis)
- [Top Docked Compounds](#-top-docked-compounds)
- [Protein–Ligand Interaction Analysis](#-proteinligand-interaction-analysis)
- [Tools and Databases Used](#️-tools-and-databases-used)
- [Results](#-results)
- [Conclusion](#-conclusion)
- [Future Scope](#-future-scope)
- [References](#-references)
- [Author](#-author)

---

# 🔍 Overview

This project focuses on the computational repurposing of approved and bioactive compounds against the Zika virus using a structure-based drug discovery approach.

The study targets the **NS2B-NS3 serine protease**, a crucial viral enzyme responsible for:

- Polyprotein cleavage
- Viral maturation
- Viral replication

The workflow integrates:

- Binding site prediction
- Druggability assessment
- Molecular docking
- Protein–ligand interaction analysis

to identify potential antiviral candidates.

---

# 🌍 Background

## About Zika Virus

Zika virus is a mosquito-borne flavivirus first identified in Uganda in 1947 and later discovered in humans in 1952.

### Key Facts

- Positive single-stranded RNA virus
- Transmitted primarily by *Aedes* mosquitoes
- Causes fever, rash, conjunctivitis, and joint pain
- Infection during pregnancy may lead to microcephaly and congenital disorders
- WHO declared Zika-related microcephaly a Public Health Emergency in 2016
- No fully effective antiviral treatment currently available

---

# 🎯 Project Objective

> To identify potential repurposed drug candidates against the Zika virus NS2B-NS3 serine protease using computational molecular docking and interaction analysis.

---

# 🧪 Target Protein

## NS2B-NS3 Serine Protease

The NS2B-NS3 serine protease is an essential non-structural viral protein involved in cleavage of the viral polyprotein.

## Why this target?

- Essential for viral survival
- Plays a critical role in viral replication
- No close human homolog
- Druggable binding pocket
- Crystal structure available

| Feature | Details |
|---|---|
| Target Protein | NS2B-NS3 Serine Protease |
| Virus | Zika Virus |
| PDB ID | 5LC0 |
| Protein Type | Non-structural Protein |

---

# ⚙️ Methodology

## Workflow

```text
Target Selection
       ↓
Protein Structure Retrieval (PDB ID: 5LC0)
       ↓
Binding Site Prediction
       ↓
Druggability Assessment
       ↓
Compound Selection
       ↓
Molecular Docking using LibDock
       ↓
Protein–Ligand Interaction Analysis
       ↓
Identification of Potential Inhibitors
```

---

# 🧬 Binding Site Analysis

The selected binding pocket showed:

- Largest surface area
- Largest pocket volume
- Presence of active site residues
- High druggability probability

## Druggability Score

| Tool | Score |
|---|---|
| PockDrug | 0.69 |

---

# 💊 Top Docked Compounds

## 1️⃣ Dofequidar

| Property | Value |
|---|---|
| PubChem CID | 213040 |
| LibDock Score | 177.642 |

### Description

- Synthetic quinoline derivative
- Known P-glycoprotein inhibitor
- Highest docking affinity among screened compounds

### Potential Role

May improve intracellular retention of antiviral compounds and influence viral transport pathways.

---

## 2️⃣ Peptidomimetic Inhibitor

### Compound

```text
1-[2-(3-Biphenyl)-4-methylvaleryl)]amino-3-(2-pyridylsulfonyl)amino-2-propanone
```

| Property | Value |
|---|---|
| PubChem CID | 5288593 |
| LibDock Score | 176.212 |

### Potential Role

Associated with Cathepsin K inhibition which may interfere with viral entry mechanisms.

---

## 3️⃣ 10-Propargyl-5,8-dideazafolic acid

| Property | Value |
|---|---|
| PubChem CID | 135438608 |
| LibDock Score | 173.777 |

### Potential Role

May indirectly support host DNA repair pathways affected during infection.

---

## 4️⃣ Carbamic Acid Derivative

| Property | Value |
|---|---|
| PubChem CID | 5289091 |
| LibDock Score | 173.718 |

### Potential Role

Related to cysteine protease pathways associated with viral infection mechanisms.

---

## 5️⃣ Ximelagatran

| Property | Value |
|---|---|
| PubChem CID | 9574101 |
| LibDock Score | 171.468 |

### Observation

Although docking affinity was strong, therapeutic suitability is limited due to bleeding risks and unrelated biological mechanisms.

---

# 🔗 Protein–Ligand Interaction Analysis

Interaction analysis was performed to evaluate:

- Hydrogen bonding
- Hydrophobic interactions
- Active-site residue interactions
- Binding stability
- Protein–ligand affinity

These analyses helped validate docking results and identify compounds with stronger interaction potential.

---

# 🛠️ Tools and Databases Used

## 📚 Databases

- PubChem
- DrugBank
- Protein Data Bank (PDB)

## ⚙️ Computational Tools

- LibDock
- PockDrug
- CASTp
- Discovery Studio

---

# 📊 Results

## Key Findings

- Dofequidar achieved the highest LibDock score
- Multiple compounds formed stable active-site interactions
- The target pocket demonstrated strong druggability characteristics
- Structure-based repurposing showed potential for antiviral screening

---

# ✅ Conclusion

This project demonstrates the effectiveness of computational drug repurposing approaches for identifying potential antiviral candidates against Zika virus.

The NS2B-NS3 serine protease proved to be a promising therapeutic target due to:

- Essential role in viral replication
- Favorable druggability profile
- Availability of crystal structure

The identified compounds require experimental validation for further development.

---

# 🚀 Future Scope

- Molecular dynamics simulations
- ADMET profiling
- QSAR modeling
- AI/ML-based drug screening
- In vitro antiviral validation

---

# 📚 References

1. PubChem — https://pubchem.ncbi.nlm.nih.gov/
2. DrugBank — https://go.drugbank.com/
3. PockDrug — https://pockdrug.rpbs.univ-paris-diderot.fr/
4. CASTp — http://sts.bioe.uic.edu/castp/
5. Protein Data Bank — https://www.rcsb.org/

---

# 👨‍💻 Author

## Chandra Prakash Ajay

**MTech Computational Biology**  
Bioinformatics | Computational Drug Discovery | AI/ML in Biology

---

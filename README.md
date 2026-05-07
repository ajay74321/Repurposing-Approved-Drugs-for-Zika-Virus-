# Repurposing-Approved-Drugs-for-Zika-Virus-
Computational drug repurposing project targeting the Zika virus NS2B-NS3 serine protease using structure-based virtual screening, binding site analysis, and molecular docking. Identified potential antiviral candidates through LibDock scoring and protein–ligand interaction analysis using bioinformatics tools and public databases.

🔍 Overview

This project focuses on the computational repurposing of approved and bioactive compounds against the Zika virus using a structure-based drug discovery approach. The study targets the NS2B-NS3 serine protease, a crucial viral enzyme required for polyprotein processing and viral replication.

By integrating binding site prediction, druggability assessment, molecular docking, and protein–ligand interaction analysis, the project identifies potential compounds that may act as inhibitors against the Zika virus protease.

🌍 Background
About Zika Virus

Zika virus is a mosquito-borne flavivirus first identified in monkeys in Uganda in 1947 and later discovered in humans in 1952. It is a positive single-stranded RNA virus primarily transmitted by Aedes mosquitoes.

Key Facts
Causes fever, rash, conjunctivitis, muscle pain, and joint pain
Infection during pregnancy may lead to microcephaly and congenital disorders
Declared a Public Health Emergency of International Concern (PHEIC) by WHO in 2016
No specific antiviral treatment currently available
No fully effective vaccine available for prevention
🎯 Project Objective

The main objective of this project is:

To identify potential repurposed drug candidates against the Zika virus NS2B-NS3 serine protease using computational molecular docking and interaction analysis.

This approach helps accelerate antiviral drug discovery by utilizing existing compounds with known biological activity.

🧪 Target Protein
NS2B-NS3 Serine Protease

The NS2B-NS3 serine protease plays a critical role in the viral life cycle.

Why this target?
Essential for viral replication
Performs polyprotein cleavage
Druggable binding pocket
No close human homolog
Crystal structure available
Protein Information
Feature	Details
Target Protein	NS2B-NS3 Serine Protease
Virus	Zika Virus
PDB ID	5LC0
Protein Type	Non-structural Protein
⚙️ Methodology
Workflow
Selection of Zika virus target protein
Retrieval of crystal structure (PDB ID: 5LC0)
Binding site prediction and pocket analysis
Druggability assessment using PockDrug
Compound selection from public databases
Molecular docking using LibDock
Ranking based on docking score
Protein–ligand interaction analysis
Identification of top potential inhibitors
🧬 Binding Site Analysis

The selected binding pocket showed:

Largest surface area
Largest pocket volume
Presence of active site residues
High druggability probability
Druggability Score
Tool	Score
PockDrug	0.69
💊 Top Docked Compounds
1. Dofequidar
Details
Property	Value
PubChem CID	213040
LibDock Score	177.642
Compound Type	Quinoline Derivative
Description

Dofequidar is an orally available synthetic quinoline derivative known for multidrug resistance modulation and P-glycoprotein inhibition.

Potential Role Against Zika Virus

Although Dofequidar does not directly target viral replication, inhibition of P-glycoprotein may increase intracellular retention of antiviral compounds and potentially influence viral component transport.

2. 1-[2-(3-Biphenyl)-4-methylvaleryl)]amino-3-(2-pyridylsulfonyl)amino-2-propanone
Details
Property	Value
PubChem CID	5288593
LibDock Score	176.212
Compound Type	Covalent Peptidomimetic Inhibitor
Mechanism

Associated with Cathepsin K inhibition.

Potential Role Against Zika Virus

Studies suggest cathepsins may assist viral entry into host cells. Inhibition of Cathepsin K could interfere with this process and reduce viral spread.

3. 10-Propargyl-5,8-dideazafolic acid
Details
Property	Value
PubChem CID	135438608
LibDock Score	173.777
Functional Association	Thymidylate Synthase
Potential Role Against Zika Virus

This compound may indirectly assist host cell recovery by supporting DNA repair pathways affected during viral infection.

4. [1-(3-Hydroxy-2-oxo-1-phenethyl-propylcarbamoyl)-2-phenyl-ethyl]-carbamic acid pyridin-4-ylmethyl ester
Details
Property	Value
PubChem CID	5289091
LibDock Score	173.718
Mechanism	Cysteine Protease Related
Potential Role Against Zika Virus

May indirectly affect viral entry by targeting protease pathways associated with host cell infection mechanisms.

5. Ximelagatran
Details
Property	Value
PubChem CID	9574101
LibDock Score	171.468
Mechanism	Thrombin Inhibitor
Observations

Although it showed strong docking scores, Ximelagatran is unlikely to directly inhibit Zika viral replication because its primary target is associated with blood clotting pathways.

Safety concerns related to bleeding risks also reduce its therapeutic suitability.

🔗 Protein–Ligand Interaction Analysis

Protein–ligand interaction studies were performed for all top-ranked compounds to analyze:

Hydrogen bonding interactions
Hydrophobic interactions
Pi interactions
Active site residue contacts
Binding stability within the pocket

These interactions helped validate docking results and identify compounds with stronger binding affinity.

🛠️ Tools and Databases Used
Databases
PubChem
DrugBank
Protein Data Bank (PDB)
Computational Tools
LibDock
PockDrug
CASTp
Discovery Studio
📊 Results

The study successfully identified several compounds with high docking affinity against the NS2B-NS3 serine protease.

Key Findings
Dofequidar achieved the highest LibDock score
Multiple compounds formed stable interactions with active site residues
The target pocket demonstrated good druggability characteristics
Structure-based repurposing showed promise for rapid antiviral screening
✅ Conclusion

This project demonstrates the potential of computational drug repurposing approaches for identifying antiviral candidates against the Zika virus.

The NS2B-NS3 serine protease proved to be a promising therapeutic target due to its essential role in viral replication and favorable druggability profile.

While the identified compounds require experimental validation, the study highlights the effectiveness of molecular docking and interaction analysis in accelerating early-stage drug discovery.

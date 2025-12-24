# In Silico Design of a Multi-Epitope Vaccine Against Human Metapneumovirus (hMPV)

## 📅 Project Context
**Undergraduate Dissertation (B.Sc. Biotechnology)**
**Institution:** B.K. Birla College, Kalyan
**Duration:** 2024 – 2025

## 📌 Project Overview
Human Metapneumovirus (hMPV) is a significant respiratory pathogen with no licensed vaccine. This project utilized a **Reverse Vaccinology** approach to design a multi-epitope subunit vaccine targeting conserved antigenic regions of the virus. The final construct was validated for antigenicity, safety, and structural stability.

## 🎯 Objectives
* To retrieve and analyze whole genome sequences of hMPV (Assembly ID: ASM281537v1 and others).
* To predict immunodominant **B-cell and T-cell epitopes** (MHC I & II).
* To design a chimeric vaccine construct using **GGGGS** and **AAY** linkers with a **PADRE adjuvant**.
* To validate the vaccine through **Molecular Docking** with TLR4 receptors.

## 🛠️ Methodology & Tools Used
The study followed a strict computational pipeline:

1.  **Proteome Retrieval:** NCBI GenBank (5 complete genomes analyzed).
2.  **Antigenicity Screening:** VaxiJen v2.0 (Threshold > 0.8).
3.  **Epitope Mapping:** IEDB (NetMHCpan, BepiPred 2.0).
4.  **Safety Profiling:** AllerTOP v2.0 (Allergenicity) & ToxinPred (Toxicity).
5.  **3D Modeling:** SwissModel / PyMOL.
6.  **Molecular Docking:** ClusPro Server.

## 📊 Key Results
* **Epitope Selection:** Identified **5 B-cell**, **5 MHC Class I**, and **4 MHC Class II** epitopes with high conservation.
* **Vaccine Construct:** A 264 amino acid polypeptide with a **PADRE adjuvant** at the N-terminus and a **6x His-tag** at the C-terminus.
* **Expression Quality:** Codon Optimization (CAI) score of **0.9558**, indicating high expression potential in *Homo sapiens*.
* **Docking Analysis:** The vaccine showed strong binding affinity to the **TLR4 receptor** with a lowest energy score of **-605.4 kcal/mol**.

## 🖼️ Visuals
* **Figure 1:** Final vaccine linear sequence.
* <img width="940" height="470" alt="image" src="https://github.com/user-attachments/assets/2864f822-33dc-4df3-b970-4592bd58dffc" />

* **Figure 2:** 3D modelled structure of the vaccine (PyMOL).
* <img width="883" height="595" alt="image" src="https://github.com/user-attachments/assets/f4ac67a9-1f09-45f4-acb6-db9a77b5d7cf" />


---
*Research conducted by Aafreen Sayed and team under the guidance of Dr. Sneha Dokhale.*

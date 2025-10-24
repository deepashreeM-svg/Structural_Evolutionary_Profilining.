# Structural and Evolutionary Profiling of Select Human Protein–Protein Interactions Across Diverse Folds

**Author:** Ms. Deepashree M  
**Institution:** JSS Academy of Higher Education & Research, Mysuru  
**Degree:** Master of Science in Bioinformatics  
**Guide:** Dr. Sowmya T. N  
**Co-Guide:** Prof. R. Sowdhamini (NCBS, Bengaluru)  
**Date:** June 2025  

---

## 🧬 Project Overview
This project investigates the **structural and evolutionary conservation** of selected human **protein–protein interactions (PPIs)** across diverse folds. The study focuses on two representative pairs:  
- **Profilin-1 (PFN1)** with **Beta-actin (ACTB)**  
- **Transthyretin (TTR)** with **Retinol Binding Protein 4 (RBP4)**  

The analysis integrates **sequence-based**, **structure-based**, and **phylogenetic** bioinformatics approaches to uncover conserved residues, interaction interfaces, and evolutionary patterns.

---

## 🎯 Objectives
- Classify proteins using **SCOPe** and identify interacting partners via **STRING**.  
- Retrieve and annotate 3D structures from **PDB**, **PDBe**, and **PDBsum**.  
- Identify key residues using **PyMOL** visualization.  
- Retrieve homologous sequences using **BLAST** and reduce redundancy using **CD-HIT**.  
- Perform **multiple sequence alignments (MSA)** with Kalign, MAFFT, MUSCLE, Clustal Omega, and T-Coffee.  
- Conduct **structural alignments** with DALI, TM-align, and PROMALS3D.  
- Build **phylogenetic trees** using MEGA and annotate them in **iTOL**.  
- Analyze **mutations** and **disease-associated residues** from **UniProt**.  

---

## 🧰 Tools and Databases Used
| Category | Tool/Database | Function |
|-----------|----------------|----------|
| Structural Classification | SCOPe | Protein fold and class identification |
| PPI Analysis | STRING, PDBe, PDBsum | Interaction mapping |
| Structure Visualization | PyMOL | 3D structural analysis |
| Sequence Retrieval | BLAST (NR, PDB, UniProt) | Homology search |
| Redundancy Reduction | CD-HIT | Sequence clustering |
| Multiple Sequence Alignment | MAFFT, MUSCLE, Kalign, Clustal Omega, T-Coffee, MEGA | Sequence conservation analysis |
| Alignment Evaluation | AliStat | Completeness and quality scoring |
| Structure Alignment | TM-align, DALI, PROMALS3D | Structural conservation analysis |
| Phylogenetic Analysis | MEGA, iTOL | Evolutionary tree construction |
| Visualization | Jalview | Alignment visualization and annotation |
| Variant Analysis | UniProt | Mutation and disease association |

---

## 🧫 Methodology
1. **Protein Retrieval and Interaction Mapping:**  
   - Selected PFN1–ACTB and TTR–RBP4 pairs using SCOPe and STRING databases.  
   - Retrieved 3D structures and analyzed interaction sites in PDBe and PDBsum.  

2. **Homology and Clustering:**  
   - Retrieved homologs via BLAST.  
   - Clustered sequences with CD-HIT at 70% identity threshold.

3. **Sequence Alignment and Evaluation:**  
   - Performed MSA using various tools.  
   - Evaluated alignment quality with AliStat — Clustal (MEGA) showed the best completeness scores.

4. **Structure Alignment:**  
   - Conducted pairwise and multiple structure alignments with DALI, TM-align, and PROMALS3D.  

5. **Phylogenetic Analysis:**  
   - Built trees using MEGA (Neighbor-Joining method).  
   - Visualized and annotated with iTOL using custom Python scripts.

6. **Residue and Variant Analysis:**  
   - Mapped functional and disease-related residues via Jalview and UniProt data.

---

scripts/
│ ├── cd_hit_cluster.sh
│ ├── alistat_summary.py
│ ├── tm_align_batch.sh
│ ├── phylogeny_tree_builder.sh
│ ├── itol_label_generator.py
│ ├── color_annotation_generator.py
│ ├── cluster_extraction.py
│ └── jalview_visualization_script.py

---

## 🧠 Key Findings
- Profilin-1 interacts with Beta-actin through conserved residues crucial for cytoskeletal organization.  
- Transthyretin binds Retinol Binding Protein 4 for vitamin A transport, highlighting ligand-binding conservation.  
- Multiple sequence and structure alignments reveal fold-level conservation across species.  
- Disease-linked mutations (e.g., in TTR) align with conserved structural regions, indicating functional relevance.

---

## 🧾 Citation
If you use this repository or any part of this analysis, please cite:

> Deepashree M. (2025). *Structural and Evolutionary Profiling of Select Human Protein–Protein Interactions Across Diverse Folds.*  
> MSc Dissertation, JSS Academy of Higher Education & Research, Mysuru.

---

## 👩‍💻 Author
**Deepashree M**  
MSc Bioinformatics | JSS Academy of Higher Education & Research  
📧 [deepashreemanjunath07@gmail.com]  





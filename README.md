# 📌 1. Title

## 🧬 Drug-Likeness-Analysis-of-Natural-Compounds-Using-RDKit

# 📖 2. Introduction

## RDKit is an open-source toolkit for cheminformatics. It's a collection of cheminformatics and machine-learning software, widely used in fields involving chemical data.
Natural products have played a crucial role in the history of drug discovery. 
This project uses RDKit to calculate molecular descriptors for 10 traditional 
natural compounds and evaluates their drug-likeness based on Lipinski's Rule of 5.We also visualize key descriptors to gain insights into the bioavailability 
and physicochemical profiles of these compounds.

# 📂 3. Project Workflow

### Workflow

1. Define 10 natural compounds (with SMILES)
2. Calculate molecular descriptors using RDKit
3. Add traditional medicinal uses
4. Apply Lipinski's Rule of Five to evaluate drug-likeness
5. Visualize key descriptor relationships (e.g., TPSA vs LogP)
6. Export final results

# 🧪 4. Molecular Descriptors Calculated

- Molecular Weight (MolWt)
- LogP (MolLogP)
- Number of H-bond Donors
- Number of H-bond Acceptors
- Topological Polar Surface Area (TPSA)

# 📊 5. Visualization Sample

A scatter plot of TPSA vs LogP helps visualize how compounds align with 
drug-likeness properties.
Compounds with lower TPSA and moderate LogP generally show better oral bioavailability.
![tpsa_vs_logp](https://github.com/user-attachments/assets/321b48ab-aeed-4481-8c1b-77ce4d493bf9)


# ✅ 6. Lipinski Rule Summary

Each compound is evaluated against Lipinski’s Rule of 5:

- MolWt ≤ 500
- LogP ≤ 5
- H-bond Donors ≤ 5
- H-bond Acceptors ≤ 10

This helps assess the oral drug-likeness of each compound.

📎 7. Results Table 

[natural_compound_descriptors.csv](https://github.com/user-attachments/files/21120345/natural_compound_descriptors.csv)

# 📁 8. Files & Usage

-Drug_Likeness_via_RDKit .ipynb: Main Jupyter notebook
- natural_compound_descriptors.csv: Output CSV of calculated properties
- README.md: Project description

# 🧠 9. Conclusion

This mini-project demonstrates how RDKit can be used to evaluate 
the drug-likeness of natural compounds. It provides a solid starting 
point for natural product screening and cheminformatics-driven lead optimization.


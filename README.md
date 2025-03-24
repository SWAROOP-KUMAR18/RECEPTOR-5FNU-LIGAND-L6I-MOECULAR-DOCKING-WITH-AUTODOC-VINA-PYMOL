# RECEPTOR-5FNU-LIGAND-L6I-MOECULAR-DOCKING-WITH-AUTODOC-VINA-PYMOL
Molecular Docking of 5FNU Receptor and L6I Ligand
Project Overview
This project involves molecular docking of the 5FNU receptor and L6I ligand to analyze their binding interactions, stability, and potential for drug discovery. The study was conducted using AutoDock Vina, PyRx, and related bioinformatics tools.

Data Sources
Receptor (5FNU): https://www.rcsb.org/structure/5FNU

Ligand (L6I): https://www.rcsb.org/ligand/L6I
Methodology
1. Preparation of Receptor and Ligand
Retrieved 5FNU protein structure from RCSB PDB.

Removed water molecules and added hydrogen atoms using MGLTools.

Retrieved L6I ligand structure from RCSB PDB.

Converted the ligand file format using OpenBabel if necessary.

2. Molecular Docking using AutoDock Vina
Defined the docking grid box parameters based on the receptor's active site.

Performed molecular docking using AutoDock Vina.

Generated binding scores and analyzed binding affinity.

3. Analysis of Results
Identified the best docking pose with the lowest binding energy.

Visualized interactions using PyMOL 

Results
mode |   affinity | dist from best mode
     | (kcal/mol) | rmsd l.b.| rmsd u.b.
-----+------------+----------+----------
   1        -10.6      0.000      0.000
   2         -9.6     17.303     20.975
   3         -9.3     17.323     21.346
   4         -9.1      3.796      7.432
   5         -9.1     16.987     20.766
   6         -9.1     17.185     21.105
   7         -9.0     17.835     21.524
   8         -9.0      3.678      7.627

Binding Energy (kcal/mol): -10.4 

Tools Used : 
AutoDock Vina
MGLTools
OpenBabel
PyMOL

References
AutoDock Vina Documentation

PyMOL User Guide

Acknowledgment
We acknowledge the RCSB Protein Data Bank (PDB) for providing structural data:

5FNU Receptor (PDB Entry)

L6I Ligand (PDB Entry)

Author
Swaroop Kumar Ponnaganti

License
This project is open-source under the MIT License.

## How to Reproduce  

### Clone the Repository  

```bash
git clone https://github.com/SWAROOP-KUMAR18/5FNU-L6I-Molecular-Docking.git
cd 5FNU-L6I-Molecular-Docking










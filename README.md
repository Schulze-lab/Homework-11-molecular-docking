# Assignments Week 11
# Introduction
The goal of this assignment is to familiarize yourself with the concept of molecular docking and to compare the results from different docking tools. There is a wide range of tools that you can choose from, but some of the recommended ones are:
- SwissDock: https://www.swissdock.ch/ 
- DiffDock: https://huggingface.co/spaces/reginabarzilaygroup/DiffDock-Web 
- DockThor: https://dockthor.lncc.br/v2/# 
- AutoDock Vina: https://vina.scripps.edu/ 

# Input data
You can use any PDB entry that contains a receptor (protein) and ligand (small molecule). The ligand should be a small organic molecule, not a metal ion or similar. Make sure that an experimentally resolved structure of the receptor with the bound ligand exists, so that you have a basis for comparison.
# Tasks and output files
1)	Generate separate inputs for the receptor and ligand. Depending on the tool, those might be in .pdb, .mol2, or SMILES format
2)	Perform a molecular docking experiment using two different tools and compare the results against each other, and against the experimentally resolved structure. This comparison should shown an overlay of the docked ligands and can be done in ChimeraX or another suitable tool.
3)	Take a snapshot (or multiple) of the comparison(s) in from 2 and briefly (<5 sentences) evaluate the quality of the docking results.
4)	Combine your screenshot(s) and description in a document and upload it, together with the result file(s) from the docking experiment.
# Additional MS student tasks (bonus task for BS students)
5)	Search for an alternative potential ligand, either using a virtual screening tool, or looking for molecules that are similar to the known ligand (e.g. with SwissSimilarity).
6)	Select at least one new ligand, and perform molecular docking (steps 1-4, but only with one tool) for this new ligand, comparing the docking of the new ligand against the original ligand.
# Submission
You must submit the assignment through GitHub (or MyCourses) by 8 am ET Apr 10 to get full credit.


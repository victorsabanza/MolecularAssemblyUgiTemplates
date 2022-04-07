# MolecularAssemblyUgiTemplates
Code used to process and analyze data in Molecular Assembly - Ugi reaction project by Víctor Sabanza Gil (MSc intern Sep21-Jan22, Cronin Lab, University of Glasgow).

Example files and results for the second batch are included. The repository contains three folders:

a) ProductGenerator. It contains the notebook used to generate the theoretical products and their properties for the reaction (ProductGenerator.ipynb). Input file (test_smiles.txt) and results (products_MA.csv and products.png) are also included in the folder as an example. 

b) MS analyzer. It contains the notebook used to process and assign the LC-MS data (LCMSanalyzer.ipynb). The script takes as an input the previous file products_MA.csv, the .ms1 files for the different conditions (extracted from the MS data and included in a "ms1" folder) and the corresponding chromatograms (included in a "chromatograms" folder). Results are included in a "Results" folder

c) Graph Plotter. It contains the notebook used to generate the plots (GraphPlotterv1.ipynb). Input files are products_MA.csv, ProtonIntegration (excel file containing the integrated areas for each ppm region extracted using Mestrenova) and the results from LCMSanalyzer.ipynb (included in "extracted").

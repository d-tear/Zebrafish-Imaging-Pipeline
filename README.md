# Zebrafish-Imaging-Pipeline
ImageJ macros and Python Scripts used to analyze particle results from confocal images of zebrafish embryos

This pieline uses ImageJ to measure particles and nearest neighbor densities for single channel confocal images. Python is 
then used to combine the data from multiple csv files.

1) Use zebrafish_analysis.ijm to analyze the particles within your images and to 
measure the Nearest Neighbor Densities of your particles. The Nearest neighbor Densities (NNDs) and 
analyze particle results will create two sepearate csv files for each image.

2) Use Column_Add.py to add the corresponding NND data from the NND csv file to the analyze particles csv file for each image.

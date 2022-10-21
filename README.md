# Outlier_and_Novelty_Detection

Data Files in Lec15_101_20_2022_data_manip.ipynb on NeurIPS 2022 Ariel Data Challenge:

1. **Features 1:** AuxiliaryTable: Star and Planet Parameters (91392,10)
2. **Features 2:** spec_matrix2 and spec_matrix3: Wavelength bin, Transit depth, noise in the transit, error in wavelength bin for 52 wavelength bins (vertically stacked with 10k points each) (20000,52,4)

The entire 91392 values for the spectra data for the challenge were given, however, the file was too large to be uploaded here. Only the first 20000 instances were added, the first 10000 in spec_matrix2 and the next 10000 in spec_matrix3. These are already vstacked (vertically appended) in the notebook for you.

3. **Targets:** FM_Parameter_Table: Consists of Planet Temperature, and log traces concentrations for H2O, CH4, CO2, CO, NH3 (91392,6)

Note: The .ipynb files were originally loaded as a collection of google colab notebooks.

The Lec15_10_20_2022_Novelty_and_Outlier_Detection.ipynb file is a lecture from Professor Konstantin Matchev's Fall 2022 Machine learning course provided by the Univeristy of FLorida's graduate program.

The Lec15_10_20_2022_data_manip.ipynb file is my manipulation of the data and results using various novelty and outlier detection models, including robust covariance, one-class SVM, SGD one-class SVM, isolation forest, local outlier factor, gaussian mixture models, and DBSCAN.

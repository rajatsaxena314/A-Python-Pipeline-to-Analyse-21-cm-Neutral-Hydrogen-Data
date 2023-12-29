# A-Python-Pipeline-to-Analyse-21-cm-Neutral-Hydrogen-Data
The code takes calibration data and source data as a CSV file and performs all the necessary analysis to give the most redshifted velocity. The input files should have just the spectral power readings and information regarding the parameters (like frequency range, step size, observation date and time). The code skips this initial information in input files and starts processing the Power values. The user has to give three input files: ground and sky calibration data and source data. The user also has to input the number of Gaussians required to fit the curve. 

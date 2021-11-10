This dataset was originated from experimental data involving process parameters of seed-mediated growth synthesis of gold nanorods/spheres (GNRs/GNSs) solutions and their performance indicators captured from UV-vis-NIR absorption spectrometer. 

The experimental processes consisting of 19 features  and absorption spectra data of GNRs/GNSs solutions were preprocessed and randomly divided into training set (70%) and independent test set (30%) for machine learning (ML). Firstly, 11 ML classifiers were adopted to train the data and make prediction. All the parameters were initialized and adjusted with a 5-fold grid-search cross validation method to find the optimal hyperparameters. The prediction results with 11 classifiers were obtained by comparing such evaluation metrics as accuracy, precision, recall, and receiver operating characteristic (ROC) curves. In addition, coefficient of determination (R2) was adopted as the primary performance indicator for XGBoost regressor, which measures the proportion of variance of the outcome that is predictable from the features. 

The column names in the file **'Gold_nanorods_data.csv'** are explained as follows：  
f0：the amount of silver nitrate (AgNO3) in the growth solution  
f1：the amount of ascorbic acid (AA) in the growth solution  
f2：the amount of prepared seeds in the growth solution  
f3：the age of the reduced growth solution  
f4：the temperature of the reduced growth solution  
f5：the time of stirring mixture solutions in the second step  
f6：the rate of stirring mixture solutions in the second step  
f7：the total volume of the growth solution  
f8：the amount of cetyltrimethylammonium bromide (CTAB) in the growth solution  
f9：the total volume of the seed solution  
f10：The amount of CTAB in the seed solution  
f11：the time of stirring mixture solutions in the first step  
f12：the rate of stirring mixture solutions in the first step  
f13：the age of the seed formation solution  
f14：the temperature of the seed formation solution  
f15：the amount of hydrochloric acid (HCl) in the seed solution  
f16：the amount of sodium borohydride (NaBH4) in the seed solution  
f17：the amount of HCl in the growth solution  
f18：the amount of sodium hydroxide (NaOH) in the growth solution  

WTSPR：transverse surface plasmon resonance extinction peak wavelength  
WLSPR：longitudinal surface plasmon resonance extinction peak wavelength  
ALSPR/ATSPR：the ratio between the maximum absorbance of the longitudinal and transverse LSPR bands  
FTSPR：The full width at half maximum of TSPR band  
FLSPR：The full width at half maximum of LSPR band  

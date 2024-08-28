# MasterThesis

Folder Preprocessing:
 - Shows the steps of how the preprocessing of the real data is done 
	- the 10 downlaoded datasets of CSE-CIC-IDS2018 are loaded, then combined 
	- unnecessary columns are dropped
	- preprocessing steps are carried out
		- droping nan, inf and -inf, negative values
		- changing time to UNIX format
	- aggregating and saving the classes back into different datasets
		- "BruteForce": ["FTP-BruteForce", "SSH-Bruteforce", "Brute Force -Web", "Brute Force -XSS"],
		- "DoS": ["DoS attacks-GoldenEye", "DoS attacks-Slowloris", "DoS attacks-Hulk", "DoS attacks-SlowHTTPTest", "DDoS attacks-LOIC-HTTP", "DDOS attack-HOIC", "DDOS attack-LOIC-UDP"],
		- "Infiltration": ["Infilteration"],
		- "Bot": ["Bot"],
		- "Benign": ["Benign"]
 
 
 
 Folder Models
 - contains 4 notebooks
	- SDV (GitHub repo name) notebook has CTGAN, CopulaGAN, and TVAE models more info at: https://docs.sdv.dev/sdv/single-table-data/modeling/synthesizers
	- Synthcity (GitHub repo name) notebook contains RTAVE and ADSGAN models more info at: https://github.com/vanderschaarlab/synthcity
	- TabFairGAN notebook has TabFairGAN models more info at: https://github.com/amirarsalan90/TabFairGAN
	- Combining_everthing contains the code of how synthetically generated datasets are combined into 1 dataset
 
 
 Folder Classifiers
 - contains the code for both Random Forest and XGBoost classifiers and the proprocessing steps
 
 
- Each cell in the notebook is explained separately. 
- sdmetric (used for evaluation) can be found at: https://docs.sdv.dev/sdmetrics/
- table-evaluator (used for the evaluation) can be found at: both are found at: https://github.com/Baukebrenninkmeijer/table-evaluator
 
 

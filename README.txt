This folder contains all the needed data to reproduce the work done in this project:

	1-. "1_Excel Files" folder conatins all excel, and csv data that are needed for this work, and those include:
		1-.a. "1_Full Dataset (only mp-ids, phonon band center).xlsx" that contains only the data referring to the Materials Project ids (MP-ids) and the phonon band center which was calculated.
		1-.b. "2_Full Dataset (Features).csv" contains the inital dataset with the features that have been generated for those materials.
		1-.c. "3_17K Band center prediction & stability.xlsx" contains all the predictions that have been done on the 17k materials that dont have a phonon DOS related calculations obtained from MP alongside their stability as obtained from the same databse.
		1-.d. "4_17K Band center prediction (only stable).xlsx" contains the stable predictions (Eh<0.05 eV) that are obtained from the menitoned 17k materials.
		1-.e. "5_17K Less Than 40meV band center prediction.xlsx" contains the stable and promising materials (total phonon band center < 40 meV) from the 17k materials.
		1-.f. "6_O, S, Se compounds with band center less than 40meV.xlsx" contains only the O-, S-, and Se- Li systems that are in those 17k materials which are stable and promising.
		1-.g. "7_Prediction of all prototypes.xlsx" contains all the prototypes predictions opf the phonon band center that have been predicted by our model, this include NASICON-strucutred, Garnet-type (LLZO), Perovskite, Argyrodites, LGPS, LiPS with the necessary information for identification.
	
	2-. "2_POSCAR Files" folder contains all the necassry POSCAR files for this work, this includes:
		2-.a. "1_POSCAR Initial Dataset.rar" a .rar file that includes the POSCAR crystal structure files for the intial dataset used in this work obtained from MP.
		2-.b. "2_POSCAR 17K compounds.rar" a .rar file that includes the POSCAR files for the 17k materials from MP with no related phonon DOS calculations before.
		2-.c. "3_POSCAR Prototypes.rar" this file includes all the generated prototype structures (around ~200k) for the aformentioned prototypes.
	
	3-. "3_Codes" folder that includes:
		3-.a. "Jupyter_notebook" which includes "1_Final phonon band center model.ipynb" file that contains the convenient Jupyter Notebook needed for the ML model.
		3-.b. "Pickle" folder includes "1_final_phonon_band_center_model.pkl" which is a pickle file that stores the model as built on the original machine, and is ready to be used immediately for prediction. More info about loading pickle models can be found here: https://docs.python.org/3/library/pickle.html
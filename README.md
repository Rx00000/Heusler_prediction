# Quaternary Heusler prediction
This work presents a theoretical workflow to accelerate the discovery of new quaternary Heusler compounds for thermoelectric applications. The process consists of several steps: (i) construction of a consistent home-made DFT learning database with a limited set of compounds consisting mainly of unary, binary and ternary configurations; (ii) machine learning regression to estimate the heat of formation of all possible arrangements of atoms in the 4 crystallographic sites of Heusler phase; (iii) classification learning to predict the semiconductor (SC) feature ; (iv) verification of stable SC compounds by a convex hull analysis of the ground state for each quaternary system; and (v) phonon calculation to check the mechanical stabilities of the final candidates.

## Data set
The final database file used to predict all properties is DATA_TOT_UBTQ.xlsx, with 76,729 unary binary and ternary configurations, and 24,000 quaternary configurations. 
The properties of the 24 selected atoms used are added to atm_info.py using the Mendeleev database https://mendeleev.readthedocs.io. 
Jupyter notebook : 
- ML_Enthalpie_de_formation.ipynb gives an analyze and result of prediction on enthalpy of formation prediction. 
- ML_parametre_de_maille.ipynb  gives an analyze and result of prediction on lattice parameter. 
- ML_du_DOSS.ipynb gives an analyze and result of prediction on the characteristic of density of states (metal or semiconductor) 



# QSAR Biodegradation


## Authors

- [@Theo Underwood](https://github.com/UnderwoodTheo)

- [@Benjamin Toubiana](https://github.com/Btoubiana)


## Project

**Classification problem:** Determine if a chemical is ready biodegradable

**Aim:** Use the best classification model to predict chemical classes


## Features

41 attributes (molecular descriptors)

1) SpMax_L: Leading eigenvalue from Laplace matrix
2) J_Dz(e): Balaban-like index from Barysz matrix weighted by Sanderson electronegativity
3) nHM: Number of heavy atoms
4) F01[N-N]: Frequency of N-N at topological distance 1
5) F04[C-N]: Frequency of C-N at topological distance 4
6) NssssC: Number of atoms of type ssssC
7) nCb-: Number of substituted benzene C(sp2)
8) C%: Percentage of C atoms
9) nCp: Number of terminal primary C(sp3)
10) nO: Number of oxygen atoms
11) F03[C-N]: Frequency of C-N at topological distance 3
12) SdssC: Sum of dssC E-states
13) HyWi_B(m): Hyper-Wiener-like index (log function) from Burden matrix weighted by mass
14) LOC: Lopping centric index
15) SM6_L: Spectral moment of order 6 from Laplace matrix
16) F03[C-O]: Frequency of C - O at topological distance 3
17) Me: Mean atomic Sanderson electronegativity (scaled on Carbon atom)
18) Mi: Mean first ionization potential (scaled on Carbon atom)
19) nN-N: Number of N hydrazines
20) nArNO2: Number of nitro groups (aromatic)
21) nCRX3: Number of CRX3
22) SpPosA_B(p): Normalized spectral positive sum from Burden matrix weighted by polarizability
23) nCIR: Number of circuits
24) B01[C-Br]: Presence/absence of C - Br at topological distance 1
25) B03[C-Cl]: Presence/absence of C - Cl at topological distance 3
26) N-073: Ar2NH / Ar3N / Ar2N-Al / R..N..R
27) SpMax_A: Leading eigenvalue from adjacency matrix (Lovasz-Pelikan index)
28) Psi_i_1d: Intrinsic state pseudoconnectivity index - type 1d
29) B04[C-Br]: Presence/absence of C - Br at topological distance 4
30) SdO: Sum of dO E-states
31) TI2_L: Second Mohar index from Laplace matrix
32) nCrt: Number of ring tertiary C(sp3)
33) C-026: R--CX--R
34) F02[C-N]: Frequency of C - N at topological distance 2
35) nHDon: Number of donor atoms for H-bonds (N and O)
36) SpMax_B(m): Leading eigenvalue from Burden matrix weighted by mass
37) Psi_i_A: Intrinsic state pseudoconnectivity index - type S average
38) nN: Number of Nitrogen atoms
39) SM6_B(m): Spectral moment of order 6 from Burden matrix weighted by mass
40) nArCOOR: Number of esters (aromatic)
41) nX: Number of halogen atoms


## Targets: 
- Ready biodegradable (RB) 
- Not ready biodegradable (NRB)


## Requirements

- graphviz            0.19.1
- matplotlib          3.3.2
- numpy               1.20.3
- pandas              1.1.3
- plotly              4.14.3
- seaborn             0.11.0
- sklearn             0.23.2
## Conclusion

We tested 6 different models:

- Logistic Regression
- Support Vector Classification
- Naive Bayes
- K-Nearest Neighbors
- Decision Tree
- Random Forest

Ater tuning them the best one is Support Vector 
Classification (SVC) with a 90% accuracy. 
## Visualization 

Entiere notebook with all the plots: https://nbviewer.org/github/UnderwoodTheo/ESILV/blob/main/PythonForDataAnalysis/python_project.ipynb

Accuracy before and after tuning

![accuracy](https://user-images.githubusercontent.com/96694641/147854382-e438eb5a-bd86-4487-9336-6309a85194f1.png)

SVC Accuracy

![svc_acc](https://user-images.githubusercontent.com/96694641/147854407-91db64f2-aaf2-4cf0-a2b3-cc66304a2d9a.png)


# QSAR Biodegradation

## Project

**Classification problem:** Determine if a chemical is ready biodegradable

**Features:** 41 attributes (molecular descriptors)

**Targets:** Ready biodegradable (RB) and Not ready biodegradable (NRB)

**Aim:** Use the best classification model to predict chemical classes



## Authors

- [@Theo Underwood](https://github.com/UnderwoodTheo)

- [@Benjamin Toubiana](https://github.com/Btoubiana)


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

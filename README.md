# Pile-driveability-prediction-using-SVM-and-XGBoost
The repository is based on ISFOG 2020 Pile driving prediction competition from kaggle.com. 
In the context of the ISFOG2020 conference in Austin, TX, a prediction event is launched which invites geotechnical engineers 
to share knowledge and gain hands-on experience with machine learning models.

This repository presents a solution to the pile driving prediction using different Machine learning algorithms
(Linear regression, Support Vector Machine with radial basis function (SVM with RBF) and XGBoost). The performance
of each algorithm is explored.

# Dataset
The full data set consists of piezocone penetration test data (PCPT), recorded hammer energies and pile characteristics at 114 pile foundation locations. 
The data is provided vs depth and is resampled to a regular grid with a vertical spacing of 0.5m. The Dataset is provided in the Data folder of this
repository and it can also be downloaded from kaggle.com (https://www.kaggle.com/competitions/isfog2020-pile-driving-predictions/data)

# References
Brownlee Jason XGBoost with Python, Machine Learning Mastery, 2018

Brownlee Jason machinelearningmastery.com/xgboost-for-regression, March 2021

Byrne T., Gaven K., Prendergast L.J., Cachim P, Doherty P., Chenicheri Pulukul. “Performance of CPT-based methods to assess monopile driveability in North Sea Sands”, 
Ocean Engineering, 166 (2018) pp 76-91

github.com/snakesonabrain/isfog-workshop, based on ISFOG 2020 keynote paper “Data Science in offshore geotechnics” (Styuts, 2020)

kaggle.com/c/isfog2020-pile-driving-predictions ISFOG 2020 Data Science prediction event

scikit-learn.org/stable/auto_examples/svm/plot_rbf_parameters.html  Sckikit-learn: RBF SVM Parameters

scikit-learn.org/stable/auto_examples/svm/plot_svm_regression.html?highlight=svr#

van Wijk J., Alvarez M., Moyo T. “Risk reduction in foundation installation project: how data and A.I. make life predictable and easy” 
Proceedings of Geotechniekdag, 2021 (researchgate.net/publication 356128889)


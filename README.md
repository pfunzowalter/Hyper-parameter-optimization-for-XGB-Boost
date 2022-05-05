# Hyper-parameter-optimization-for-XGB-Boost
This project continues on the regression repository. Its main focus is on optimizing the hyper-parameters of the XGBoost regressor to best estimate the photometric redshifts of Quasars and Star forming galaxies under study. We used 80% of the dataset for training the algorithm and 20% for testing. We used sk-learn Randomised Search CV with r2_score, Median absolute deviation and both of them in different trial to find the best parameters for our testing data. The Median absolute deviation provides the best RMS and NMAD for this project. The full python script "XGB_optimization_reviewed.ipynb"



![picture](https://github.com/pfunzowalter/Hyper-parameter-optimization-for-XGB-Boost/blob/main/sample_data.png)

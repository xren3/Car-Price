This project explores a dataset containing information on used cars.
The data was first cleaned and fit with a transformer. Multiple regression models were used, including linear, ridge, and lasso.
The ridge regression coefficients, SFS/RFE features, and permutation importance showed that the linear regression model was more influenced by outliers.
The outliers included luxury car manufacturers such as Astin Martin, Ferrari, and Land Rover, as well as car parts which were persumably much lower in price.
The ridge regression model was better at modeling average cars, and the most influential features was found to be the number of cylinders.
To improve the model, the next step is to cluster the data based on similar features and build models for each cluster.
The link to the Jupyter Notebook is here: https://github.com/xren3/What-Drives-The-Price-Of-A-Car/blob/main/prompt_II.ipynb

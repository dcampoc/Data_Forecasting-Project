The dataset has data about contraceptive consumption, and the goal is to predict consumption (stock_distributed from "train.csv")
for 11 contraceptives across 156 health service delivery sites in the public sector health system in Côte D’Ivore.
The predictions should be made monthly for three months (July, August, September from 2019).

There are 3 different jupyter notebooks containing the steps
to solve the proposed exercise. Namely:

data_analysis.ipynb : Contains an analysis of the data and organize it in a way
be fed to an ML algorithm (neural network in this case).

ml_train.ipynb : Defines the proposed neural network and trains it

ml_estimations.ipynb : Uses the neural network to estimates the future
3 months of all available cases and fills the proposed csv file with the predictions

Additionally, relevant data and models produced by the different notebooks are
already saved in the folder but they can be reproduced by running the notebooks.

The following modules were employed:

numpy 1.18.5
tensorflow 2.0.0
sklearn 0.23.2
pandas 1.1.1
matplotlib 3.3.0
pickle
Random
itertools
datetime

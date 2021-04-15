# Engineering-thesis
This is code for my part of engineering thesis "The use of preference learning methods in multiple criteria store choice modeling". 
My job was to create accurate model from existing ready-to-use classifiers. Thesis is based on confidential dataset, which cannot be shared entirely. For this reason I also don't describe in detail features of the data.

### Preprocessing
This notebook contains code for preprocessing the dataset. The purpose of that was to change three dimensional dataset into two dimensions which can be used with classifiers from sklearn library.
For scientific reasons we wanted to keep original problem and compare shops in pairs.

### Preselection of methods
Simple test based on train split validation.

### ________ -  tuning
Tuning of selected models. Beacuse of the long time of traning (I had to train models on full dataset) in some classifier only minor tuning of some parameter was performed (use of full grid search was not possible)

### ________ - intepretation
Intepretation of models containing permutation importance and partial dependence plots.

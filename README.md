# bankcruptcy_data
Data is retrived from http://norma.ncirl.ie/4312/7/shantanudeshpandeconfigurationmanual.pdf, https://github.com/shantanudeshpande94/bankruptcy-prediction, https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data#.

I have used column mean and row mean to fill in the missing value. The files are saved in test_std.csv, and train_std.csv.

I also delete the missing values and save files as training_filted.csv, and testing_filted.csv.

The accuracy is KNN (k=3, 88%), Softmax (54%), NN (88%) with manual coding. And the accuracy under sklearn is Softmax Regression (88%), Logistic Regression (91%) for filted data, and Softmax Regression (67%), Logistic Regression (73%) for filled-in data.

# UAS-Round---2
1) Use MNIST dataset provided by tensorflow, because dataset provided by official website of MNIST(in GZ format) will give unfamiliar type of output.
2) Next step is to standardize(or fit_transform) the obtained data to make numeric columns to a dataset of a common scale, without changing value differences between the value(in it 0 is taken to be at minimun ad 1 to be at maximum).
3) Next we made a sequential model, added 3 layers of 256 units, with Rectified Linear Unit as activation function, last layer has 10 units because of 0-9 numbers and it is the case of mutually exclusive multiclass classification so the activation function was 'softmax'
4) Next we compiled our model and trained it with our training data, epoch value = 10, i.e. we want to pass or iterate our model 10 timesm verbose is used just to show the progres of each and every epoch, loss and accuracy.
5) Predictions are made on test data.

# UAS-Round---2
1) Use MNIST dataset provided by tensorflow, because dataset provided by official website of MNIST(in GZ format) will give unfamiliar type of output.
2) Next step is to standardize(or fit_transform) the obtained data to make numeric columns to a dataset of a common scale, without changing value differences between the value(in it 0 is taken to be at minimun ad 1 to be at maximum), since our data i present in 3D array, we can not apply fit_tranform algorithms to it so, it is preferable to devide our array with the maximum value available(pixel and 0-9 number).

# UAS-Round---2
This is a classifier which is trained on MNIST hand written dataset, it will classify hand written digits from 0 to 9, is a basic subset of OCR(Optical Character Recognisation).
Click_images file consist of software system which will inable your webcam to click any image and also write it in your disk, array of image is also obtained from it.

Hence, this complete project will help any unmanned machine to click image of any sheet(boord) and recognize the shown digit on its own and classify other further tasks.

In Sequential model, used 3 Dense layers of 256 units and Rectified Linear Unit, because it is the case of Mutually exclusive multi-class classification so here we used "softmax"
as our activation function. While compiling optimiser used is = "adam", loss = "sparse_categorical_crosentropy". Model is trained at 10 epoch values, verbose as 2, also included validation data on(x_test, y_test).

Data Visualization of the obtaioned predicted and y_test data can easily be done through barplots and heatmaps.

Accuracy of predicted test data is calculated through classification report  and errors can be visualized by confusion metrics.

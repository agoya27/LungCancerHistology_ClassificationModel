GOAL: CREATE A DEEP LEARNING MODEL FOR CLASSIFYING HISTOPATHOLOGICAL IMAGES OF LUNG AND COLON CANCER.

This project will help Oncologist in cancer diagnosis by providing a well-trained model to detect cancer using pictures of 2D histological microscopy tissue slices, stained with different stains, and landmarks denoting key points in each slice. 
DataSource: Kaggle
DataSet URL: https://www.kaggle.com/datasets/jirkaborovec/histology-cima-dataset

This project consists of 3 files.
1) Data Precossing -> Preprocess the image data for making it compatible to use with Model.
2) Baseline Model  -> Acts as a starting point to building CNN model and provides idea of how a basic model would perform on this dataset
3) CNN Model -> Final CNN model, which is trained and tested for classification task, achieving a high accuracy of 89.5%.
4) HyperParameter-> Result of HyperParameter Tuning and finding ideal parameter for model.

Best Accuracy Achieved: 90.1% (Learning Rate -> 0.0005, Batch Size -> 32, Number of Epochs -> 6, Activation Function -> Sigmoid, Optimizer -> Adam, Loss -> CrossEntropy, Number of Conv2D Layers -> 6, Train_loss -> 0.223, Test_loss -> 0.208)

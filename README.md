GOAL: CREATE A DEEP LEARNING MODEL FOR CLASSIFYING HISTOPATHOLOGICAL IMAGES OF LUNG AND COLON CANCER.

This project will help Oncologist in cancer diagnosis by providing a well-trained model to detect cancer using pictures of 2D histological microscopy tissue slices, stained with different stains, and landmarks denoting key points in each slice. 
DataSource: Kaggle
DataSet URL: https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images

This project consists of 3 files.
1) Data Precossing -> Preprocess the image data for making it compatible to use with Model.
2) Baseline Model  -> Acts as a starting point to building CNN model and provides idea of how a basic model would perform on this dataset
3) CNN Model -> Final CNN model, which is trained and tested for classification task, achieving a high accuracy of 89.5%.
4) HyperParameter-> Result of HyperParameter Tuning and finding ideal parameter for model.

Best Test Accuracy Achieved: 90.1% (Learning Rate -> 0.0005, Batch Size -> 32, Number of Epochs -> 6, Activation Function -> Sigmoid, Optimizer -> Adam, Loss -> CrossEntropy, Number of Conv2D Layers -> 6, Train_loss -> 0.223, Test_loss -> 0.208)

Best Test Loss: 0.0976 (Learning Rate -> 0.001, Batch Size -> 32, Number Of Epochs -> 6, Activation Function -> ReLU, Optimizer -> Adam, Loss -> CrossEntropy, Number of Conv2D Layers -> 6, Train_loss -> 0.0838, Test_Accuracy -> 89.53%)


Intructions to Run the Project:
1) Download the Dataset as a Zip file from the given Kaggle URL and save it in your Google Drive
2) Open the Preprocessing File from this repository in your local colab/Jupyter notebook environment
3) Link your Google docs to your notebook enrionment so that data file can be accessed.
4) Import the required libraries and Unzip the file using the commands given in the preprocessing notebook
5) Run the cells given in Preprocessing notebook in order and this will lead to embedded tensor of input images being stored in your google drive
6) Run the class given in CNN Notebook in order to create a model, train it and finally test the results.
7) Download the file given in the Hyperparameter section and update model parameters to verify the result achieved for train_loss, test_loss, and test_accuracy.
8) You can also run the BaseLine model file if you wish to see the performance of Baseline model in solving the classification problem.
   (You can also try HyperParameter Tuning in the Baseline Model to see if that leads to performce enhancement)

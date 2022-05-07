# Neural_Network_Charity_Analysis

 In this challenge we use the features  given in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup,using machine learning and neural networks.
The header of the dataset is described below 
          
•	EIN and NAME—Identification columns 

•	APPLICATION_TYPE—Alphabet Soup application type

•	AFFILIATION—Affiliated sector of industry

•	CLASSIFICATION—Government organization classification

•	USE_CASE—Use case for funding

•	ORGANIZATION—Organization type

•	STATUS—Active status

•	INCOME_AMT—Income classification

•	SPECIAL_CONSIDERATIONS—Special consideration for application

•	ASK_AMT—Funding amount requested

•	IS_SUCCESSFUL—Was the money used effectively

## Analysis

First we preprocess the dataset using Pandas and the Scikit-Learn’s StandardScaler()  We use one-hot encoding to encode
categorical variables.

<img width="1034" alt="Screen Shot 2022-05-07 at 11 44 26 AM" src="https://user-images.githubusercontent.com/72629108/167267713-87e17be1-e051-4212-8dce-a80a7234e78f.png">



 Next, we create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset using TensorFlow, design a neural network, or deep learning model. We need to determine the number of inputs before determining the number of neurons and layers in the model. Then we compile, train, and evaluate your binary classification model to calculate the model’s loss and accuracy.
Loss: 0.7635893821716309, Accuracy: 0.47358599305152893

<img width="1065" alt="Screen Shot 2022-05-07 at 11 58 02 AM" src="https://user-images.githubusercontent.com/72629108/167268179-dad337e1-6d8e-46b0-8313-c091269204a0.png">

<img width="1057" alt="Screen Shot 2022-05-07 at 11 57 21 AM" src="https://user-images.githubusercontent.com/72629108/167268189-994f1cc9-e93d-4d06-99e1-6b1790d57d93.png">



Using TensorFlow, optimize the model to achieve a target predictive accuracy higher than 75%. For that dropping STATUS,SPECIAL_CONSIDERATIONS column from the dataframe.

Three attempts to increase model performance

<img width="1069" alt="Screen Shot 2022-05-07 at 12 10 03 PM" src="https://user-images.githubusercontent.com/72629108/167268559-9545fcbd-aaa9-487f-a420-3a1d84941531.png">
<img width="1001" alt="Screen Shot 2022-05-07 at 12 10 24 PM" src="https://user-images.githubusercontent.com/72629108/167268568-081dcf66-6e98-4efd-a74f-3fbb84957896.png">

<img width="1126" alt="Screen Shot 2022-05-07 at 11 35 21 AM" src="https://user-images.githubusercontent.com/72629108/167267757-92cc1df7-1f8f-4518-9d5b-f6a4c2b8adee.png">
<img width="1096" alt="Screen Shot 2022-05-07 at 11 25 55 AM" src="https://user-images.githubusercontent.com/72629108/167268484-5ebd6b81-49dc-49ec-ac07-eae564a17edd.png">

<img width="1065" alt="Screen Shot 2022-05-07 at 11 37 47 AM" src="https://user-images.githubusercontent.com/72629108/167267778-88dc81c2-4f43-47c8-9731-8e189c94d3b7.png">
<img width="1059" alt="Screen Shot 2022-05-07 at 11 37 28 AM" src="https://user-images.githubusercontent.com/72629108/167267790-2111f120-f2e8-412b-a51b-bae7be86d86e.png">


## Results
 Changes in hidden layers,numbers of neurons and activation function has increased the accuracy. The second attempt has the maximum accuracy which is 56.25%.









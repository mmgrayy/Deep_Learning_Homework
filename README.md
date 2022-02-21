# Deep_Learning_Homework
# Background
The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. With our knowledge of machine learning and neural networks, we’ll use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, we have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively
Instructions
# Step 1: Preprocess the data
Using our knowledge of Pandas and the Scikit-Learn’s StandardScaler(), we’ll need to preprocess the dataset in order to compile, train, and evaluate the neural network model later in step 2.

3 Step 2: Compile, Train, and Evaluate the Model
Using our knowledge of TensorFlow, we’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. we’ll need to think about how many inputs there are before determining the number of neurons and layers in your model. Once we’ve completed that step, we’ll compile, train, and evaluate our binary classification model to calculate the model’s loss and accuracy.

# Step 4: Write a Report on the Neural Network Model
For this part of the Challenge, you’ll write a report on the performance of the deep learning model you created for AlphabetSoup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions.

Processing the Data
To begin, we processed the data in order to compile, train, and evaluate the neural network later on. I dropped the unnecessary columns and made the remaining ones be the features of the model. I then split the data into training and testing sets. I identified the target variable as “is_successful” and verified it (1 for yes 0 for no.) I then used the classification values for binning. Also, all the categorical variables were encoded by the “get_dummies” function. 

Target Variable: IS_SUCCESSFUL
Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
Removed Varaibles: EIN, NAME

Compiling, Training, and Evaluation the Model
When evaluating the model using the test data the accuracy result was around 72% (desired accuracy: 75%) 

Summary
Having multiple layers in a deep learning model, allows the computer to learn how to filter inputs through the different layers to classify and predict. That is why I went from 7 layers to 14 which increased the accuracy from 72% to 75%. 



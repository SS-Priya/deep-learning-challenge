# deep-learning-challenge

This project uses deep learning -neural network model.

Overview of the Analysis
------------------------
The purpose of this analysis is to create a binary classification model using deep learning techniques to predict if an organization funded by Alphabet Soup will be successful in their venture. The  dataset has  over 34,000 organizations that have received funding from Alphabet Soup. The CSV file has metadata about each organization.

Results
--------
Data Preprocessing
------------------
Target variable(s) for the model: The target variable is IS_SUCCESSFUL.

Feature variable(s) for the model: The feature variables are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, NAME and ASK_AMT.

Variable(s) removed from the input data: The EIN and NAME columns were removed from the input data. But brought back in the final model.

Compiling, Training, and Evaluating the Model
---------------------------------------------
The model consists of three hidden layers with 80, 30, and 1 neurons, respectively, and ReLU activation functions.
The output layer uses a sigmoid activation function for binary classification. 
This model did not achive desired accuracy of 75%.

[268/268 - 1s - loss: 0.5569 - accuracy: 0.7257 - 691ms/epoch - 3ms/step
Loss: 0.5568886399269104, Accuracy: 0.7257142663002014]

In this project, 4 models has been generated. 
In few models  the EIN and NAME columns has been removed and with applying difirrent neurons and layers and binning just achived accuracy of 72%.

Model "4-AlphabetSoupCharity_Optimisation" has the best accuracy of 78.68%. 

[268/268 - 1s - loss: 0.4549 - accuracy: 0.7868 - 573ms/epoch - 2ms/step
Loss: 0.4548674523830414, Accuracy: 0.7868221402168274]

Achieving target model performance:
-----------------------------------

The model achieves the target performance of 78.68% accuracy.
After multiple attempts were made to optimize the model, including adjusting input data, modifying the structure of the neural network, and modifying the training regimen.

Steps taken in attempts to increase model performance: 
------------------------------------------------------

Dropping additional irrelevant columns from the input data.
Creating more bins for rare occurrences in columns and adjusting the number of values for each bin.
Adding more neurons to a hidden layer.
Adding or removing hidden layers.
Using different activation functions for the hidden layers.
Increasing or decreasing the number of epochs in the training regimen.

Summary
-------
The deep learning model achieved the desired performance of 78.84% accuracy in predicting the success of Alphabet Soup-funded organizations. Several attempts were made to optimize the model. 




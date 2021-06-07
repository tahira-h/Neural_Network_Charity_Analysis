## Neural_Network_Charity_Analysis

OVERVIEW

Purpose of Analysis

The purpose of this analysis is to help the foundation, Alphbet Soup, predict where to make investments. This is done by creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Machine learning and neural networks is used in this analysis.

RESULTS

What variable(s) are considered to be the features for your model?

* As shown in the image below, the variable considered as a target for the model is the IS_SUCCESSFUL Column.

Open the file containing IS_SUCCESSFUl.
![IS_SUCCESSFUL](/Neural_Network_Charity_Analysis/Resources/IS_SUCCESSFUL.png)
Close the file.

Variable(s) Considered to be the Features for the Model?

* The image above also shows that variables considered to be the features for the model is every model except for the IS_SUCCESSFUL Column, which is the target.

What variable(s) are neither targets nor features, and should be removed from the input data?

* Two variables that were neither targets nor features, and should have been removed from the input data were EIN and NAME. These columns were dropped in regards to the limited impact it had on the outcome or results of this dataset. The two columns dropped are shown in the image below.

Open the file containing Drop_the_columns.
![Drop_the_columns](/Neural_Network_Charity_Analysis/Resources/Drop_the_columns.png)
Close the file.
	
 How many neurons, layers, and activation functions did you select for your neural network model, and why?
 
* As shown in the image below, for this analysis, the neural network model has 3 layers: "hidden layer 1", "hidden layer 2", and "output layer". Hidden layer 1 has 80 neurons and uses activation function "relu". Hidden layer 2 has 30 neurons and uses activation function "relu". The  output does not have any neurons, and uses the activation function "sigmoid". The neurons, layers, and activation functions were selected to define the neural network model.

Open the file containing Number_of neurons_layers_and_activation.
![Number_of_neurons_layers_and_activation](/Neural_Network_Charity_Analysis/Resources/Number_of neurons_layers_and_activation.png)
Close the file.

Were you able to achieve the target model performance?

*In this analysis, I was not able to achieve the target model performance of 75%. As shown in the image below, the model accuracy was 63%(0.6365014314651489).

Open the file containing UFO_1.
![UFO_1](/UFOs/static/images/UFO_1.png)
Close the file.

What steps did you take to try and increase model performance?

There were 2 steps taken to try and increase the model's performance. Columns were dropped, hidden layers were added, and one of the activation's were updated.

* Step 1: The non-beneficial 'EIN', 'NAME', and 'USE_CASE' columns were removed. 

* Step 2: Additional hidden layers were added to the dataset, including neurons. The output layer did not have any neurons, and used activation function "sigmoid". This step is what decreased the model's accuracy to 63%(0.6365014314651489).

SUMMARY

Results

The machine learning mode. and neural network used in this analysis had an accuracy score of 63%(0.6365014314651489). Steps taken in this analysis were to improve the accuracy score, however, the steps taken decreased the accuracy score each time a change was made. Leading to the model's accuracy score to not reach the expected amount of accuracy. A reason for this inaccuracy is due to the model being overfitted. Meaning, we could have added more data to the dataset for the model to not be overfitted with too
much data. 

Recommendation

A recommendation on using a different model to solve the classification and justification problem is by using a classifier that is not overfitted. In this analysis, a Random forest classifiers could have been used. According to module 19.5.4: Random Forest vs. Deep Learning Model, "Random forest classifiers are a type of ensemble learning model that combines multiple smaller models into a more robust and accurate model. It has been a staple in machine learning algorithms fore many years due to their robustness and scalability." Using random forest classifiers would be a better model to use to help Alphabet Soup predict where to make investments. 

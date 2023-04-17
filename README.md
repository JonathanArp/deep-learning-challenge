# deep-learning-challenge. 
Module 21 Challenge. 

Overview of the analysis: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.  

Data Preprocessing.   
-What variable(s) are the target(s) for your model? The target of the model is the column, "IS_SUCCESSFULL".  
-What variable(s) are the features for your model?  The features include application type, income amount, ask amount, and if there were special considerations.  
-What variable(s) should be removed from the input data because they are neither targets nor features? Two columns that were dropped were "EIN" & "NAME".  

Compiling, Training, and Evaluating the Model.  
-How many neurons, layers, and activation functions did you select for your neural network model, and why? I selected 3 layers and used relu twice and and sigmoid for the 3rd one. Additionally, I had 80 and 30 neurons for the first two layers.
-Were you able to achieve the target model performance?  No, I was only able to get around 72% of the targeted 75% accuracy.
-What steps did you take in your attempts to increase model performance?  I dropped the 'use_case' column, chnaged the cutoff value for application types to 600, and increased epochs to 200 in my model.

Summary: We were able to get very close, but not eclipse the 75% target accuracy. I would recommend giving trying a random forrest model or a balanced random forest model to see if we could improve the accuracy of the model.

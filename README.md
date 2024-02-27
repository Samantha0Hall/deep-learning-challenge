# deep-learning-challenge
Module 21

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.
 ---------------
•	Data Preprocessing

o	What variable(s) are the target(s) for your model?

IS_SUCCESSFUL column – was the money used effectively?

o	What variable(s) are the features for your model?

Remaining columns: NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

o	What variable(s) should be removed from the input data because they are neither targets nor features?

EIN column, it has no impact on outcome of the model

•	Compiling, Training, and Evaluating the Model

o	How many neurons, layers, and activation functions did you select for your neural network model, and why?

On my first attempt I used 2 hidden layers. When optimizing, I used 3 hidden layers.
![image](https://github.com/Samantha0Hall/deep-learning-challenge/assets/140672220/af8b09fa-1a29-44fe-816c-e0a6c74cf51d)
![image](https://github.com/Samantha0Hall/deep-learning-challenge/assets/140672220/ddce6891-ef68-4429-87d0-2b44a9abb42a)


o	Were you able to achieve the target model performance?

I was not able to achieve target model performance, I was not able to achieve accuracy above 73%. I was able to slightly increase accuracy by adding another hidden layer, and increase neurons, but I was not able to reach the goal of 75%.
![image](https://github.com/Samantha0Hall/deep-learning-challenge/assets/140672220/ad447ede-b8de-47aa-9c1e-903817a18736)

![image](https://github.com/Samantha0Hall/deep-learning-challenge/assets/140672220/77a586f6-29d6-4581-b6ee-df7d9d4e6ae2)



o	What steps did you take in your attempts to increase model performance?

Added a third hidden layer, and increased neurons. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
   
Despite increasing hidden layers, and neurons, I was not able to use the model to obtain an accuracy of about 73% after several attempts. I would consider using another classification model.

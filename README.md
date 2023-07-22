# deep-learning-challenge
Neural Networks and Deep Learning

With knowledge of machine learning and neural networks, I used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Non-Profit, Alphabet Soup.

Data Preprocessing

1. What variable(s) are the target(s) for your model?
   IS_SUCCESSFUL

2. What variable(s) are the features for your model?
   APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS,	ASK_AMT

3. What variable(s) should be removed from the input data because they are neither targets nor features?
   EIN, NAME
   
Compiling, Training, and Evaluating the Model

4. How many neurons, layers, and activation functions did you select for your neural network model, and why?
   200 NUERONS, 3 HIDDEN LAYERS + OUTPUT LAYER, USED LEAKYRELU, TANH, AND SIGMOID.
   
6. Were you able to achieve the target model performance?
   YES, HOWEVER I WAS UNABLE TO GET THE ACCURACY ABOVE 74%. AFTER SWITCHING MANY HYPERPARAMENTERS AND SEEING RESULTS STAY THE SAME, I DETERMINED WE COULD USE MORE DATA.
   
8. What steps did you take in your attempts to increase model performance?
   ADDED EXTRA HIDDEN LAYER, ADDED DROP OUT LAYERS, DECREASED THE CUT OFF FOR THE BINNING OF COLUMN 'CLASSIFICATION', INCREASED NEURONS, CHANGED TEST/TRAIN SPLIT.
   
9. Overall evaluation of the model? 
   Loss: 0.5585682392120361 Accuracy: 0.7271585464477539

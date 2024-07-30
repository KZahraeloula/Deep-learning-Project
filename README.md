# deep-learning-challenge
Overview
the non-proofit foundation "Alphabet Soup" is looking to create an algorithm to predict whether applicants applying for funding will be successful or not. we are using neural machine learning modele to create a classifier able to predict the outcome of applicants applying for funding.

results
Data processing: 
    -Columns 'EIN' and 'NAME' were dropped as they don't addd value to the data
    - Target  was the column 'IS_SUCCESSFUL'
    - Features were created by get_dummies function

Compiling, Training and evaluating the model:
    - Trial 1 : 
    * Activation function all layers is relu (except last one, awlays Sigmoid) 
    * 2 hidden layers
    *15 nodes in each layer
    *Epoch =100

    the results : Accuracy= 0.7273   loss= 0.5595

    - Trial 2 : 
    * Activation function all layers is relu (except last one, awlays Sigmoid) 
    * 2 hidden layers
    *20 nodes in layer 1 and 10 nodes in layer 2 
    *Epoch =100

    the results : Accuracy= 0.7286   loss= 0.5603

 - Trial 3 : 
    * Activation function first layer is tanh (except last one, awlays Sigmoid) 
    * 2 hidden layers
    *15 nodes in each layer
    *Epoch =100

    the results : Accuracy=    loss= 

    - Trial 4 : 
    * Activation function all layers is relu (except last one, awlays Sigmoid) 
    * 3 hidden layers
    *15 nodes in layer 1 and 15 nodes in layer 2  and 5 nodes in layer 3
    *Epoch =100

    the results : Accuracy= 0,7291  loss= 0.5679

Summary
the best Accuracy number is 72%, I wasn't able to reach the 75% event with trying to add more layers and more nodes and a different activation function.

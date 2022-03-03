# Neural_Network_Charity_Analysis

## Overview of the Analysis
Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Deliverables:
- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaulate the Model
- Deliverable 3: Optimize the Model
- Deliverable 4: Written Report

## Results:
- Data Processing:
  - What variable(s) are considered the target(s)?

![image](https://user-images.githubusercontent.com/90146132/156652292-d8446f39-06dc-4c6a-a3eb-316520c740d8.png)

  - What variable(s) are considered to be the features for you model?

![image](https://user-images.githubusercontent.com/90146132/156652160-1f33fbf9-2154-44c6-8b49-5ef0eae0d952.png)

  - What variable(s) are neither targets nor features, and should be removed from the input data?

![image](https://user-images.githubusercontent.com/90146132/156652414-01a39bf2-1d87-491b-a699-9ffa83440d0f.png)

- Compiling, Training, and Evaluating the Model
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?

![image](https://user-images.githubusercontent.com/90146132/156653932-49fa125f-3cd2-4c73-8a2c-d55ee00c09e6.png)

As a rule of thumb it is good to have two or three times the amount of input of neurons in the first hidden layer as the number of inputs. Less neurons were in the second hidden layer to prevent overfitting. Sigmoid and Linear functions are great for the output layer but can make the model more susceptible to problems during training in the hidden layers.

  - Were you able to achieve the target model performance?

Original Accuracy: 0.7251312136650085 = 73.5% --> Attempted Optimzed Accuracy: Accuracy: 0.7265306115150452 = 73.7%

  - What steps did you take to try and increase model performance?
    - Additional noisy variable was removed
    - Added an addition hidden layer with 10 neurons
    - Compared the different activation functions for the hidden layer, relu was the best fit from all the attempts of using other activation functions and the output activation function was selected as sigmoid because it yielded a high accuracy than when liner activation function was used.

## Summary
The analysis of the deep learning model included a recommendation for how the use of a different model may have yielded a better accuracy results for the classification problem. Making additional tweaks to the deep learning model can only help so much before the accuracy does not increase. Using other models such a randomforest or logistic regression may have better outcomes, it all depends on the type and amount of data is being evaluated.

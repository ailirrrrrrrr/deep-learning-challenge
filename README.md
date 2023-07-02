# deep-learning-challenge
Overview of the analysis: by analyzing the dataset of past perfomrance of over 34000 orginizations that were funded by Alphabet Soup over the years, we want to best predict whether the applicants will be successful if funded by Alphabet Soup.

Results: 

•	What variable(s) are the target(s) for your model?
      o	IS_SUCCESSFUL

•	What variable(s) are the features for your model?
      o	All columns but the target variables

•	What variable(s) should be removed from the input data because they are neither targets nor features?
      o	Drop the EIN and NAME columns


•	How many neurons, layers, and activation functions did you select for your neural network model, and why?
      o	First layer = 9, 405 parameters
      o	Second layer =18, 180 parameters
      o	Total trainable parameters = 604, 

•	Were you able to achieve the target model performance?
      o	Loss: 0.5503014922142029, Accuracy: 0.7276967763900757
      o	The 72% accuracy suggests that the model is fairly good to determine whether an organization would be successful or not.
  




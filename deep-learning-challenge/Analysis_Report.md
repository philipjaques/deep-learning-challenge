### Overview ###
The nonprofit foundation Alphabet Soup wanted a tool to help them select applicants for
funding. They need a binary classifier to predict whether applicants will be successful if funded
by Alphabet Soup.

### Data Preprocessing ###

Unnecessary metrics such as EIN and Name were removed from the dataset and all remaining
metrics were considered in the model. Both Classification and Application Type were features
for the model.

- What variable(s) are the target(s) for your model?
- What variable(s) are the features for your model?
- What variable(s) should be removed from the input data because they are neither targets nor features?

### Compiling, Training, and Evaluating the Model ###

Neural Network was used on each model and originally set with 2. For the final model, 3 layers
were added that helped achieve an accuracy of over 75%.

In order to achieve the model performance, I kept Name in the model and applied Name as a
feature and binned the values. I kept classification as a feature in the model as well. In
addition to the changes previously mentioned, I also added a third layer and changed the
epochs to 200 instead of 100.

### Summary ###

Several layers should be considered, so that it can continue to predict and classify information
based on the model.
# Digit-Recognizer: The `print('hello world')` of machine learning

The indea in this notebook is to improve the "Hello world" of machine learning using Keras tuner. 
To save precious time and to speed up and simplify the process of choosing the right hyperparameters of the model, 
it is possible to use a tuner. Kera's relatively new library is well suited for this. 
It allows to automatically play through different parameters and at the end - very conveniently - spits out the desired number of best models. 
These can then be processed in the further course.

## Content:
1. **Introduction**
2. **Preprocess the data**
    * 2.1. Load data
    * 2.2. Prepare data
    * 2.3. Format y_train
    * 2.4. Normalize, reshape and split data
    * 2.5 . Draw some digits
3. **Data augmentation**
4. **Hyperparameter tuning**
    * 4.1. Build hypermodel
    * 4.2. Hyperband tuner
    * 4.3. Tuner search
    * 4.4. Best models
5. **Fit the model**
    * 5.1. Summaries of best models
    * 5.2. Select the model
    * 5.3. Callbacks
    * 5.4. Fit the model
6. **Plot and evaluate the results**
7. **Predict**
8. **Tensorboard**
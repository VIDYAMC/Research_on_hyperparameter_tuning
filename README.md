# Research_on_hyperparameter_tuning
hyperparameter is a parameter from a prior distribution;. it captures the prior belief before data is observed.


# model parameters verusu hyperparameters

Model parameters are the properties of training data that will learn on its own during training by the classifier or other ML model. For example,
 [[Weights and Biases , Split points in Decision Tree etc]]
 
# Model Hyperparameters are the properties that govern the entire training process. The below are the variables usually configure before training a model.
Learning Rate
Number of Epochs
Hidden Layers
Hidden Units
Activations Functions

PARAMETERS in ML model are the parameters whoes values are updated during training using optimization procedure.

Hyperparameters IN ML model are the parameters whose values are decided before training of the model begins. Hyperparameters are not affected(do not change) by training, these affect the quality and speed of the training. So in a sense, these parameters are over, beyond or above(hyper) and hence called hyperparameters.

Hyperparameters can be related to model selection, e.g., model type, model architecture or learning algorithm, e.g., learning rate, batch size, number of epochs.

there are no sufficient algorithms to select optimal(best) values of hyperparameters. so, optimal values of hypermaters are determined using a trial and error process by adjusting or adapting their values for a particular machine learning task. This processs of determing values of hyperparameters is called Hyperparameter Tuning. For example, select the hyperparameters that give the best results on a validation set

we need huge dataset for hyperparameter tuning
because in small dataset we can't find much diffference.


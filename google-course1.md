# Google Machine Learning Crash Course

Framing - identifying the question that will be answered as well as the features/labels and model that will be used to make predictions 
- **Example** is a particular instance of data, x
- **Labeled example** has {features, label}: (x, y)
	> Used to train the model
- **Unlabeled example** has {features, ?}: (x, ?)
	> Used for making predictions on new data
- **Model** maps examples to predicted labels: y'
	> Defined by internal parameters, which are learned
- **Feature** - the provided values to make predictions
- **Labels** - the expected output values to be predicted by the model or used to train the model
- **Training** - the step in which labeled examples are input into the model to teach relationships between features and labels

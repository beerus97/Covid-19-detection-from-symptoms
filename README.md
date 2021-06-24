# Covid-19-detection-from-symptoms
A Machine Learning and ANN model that predicts Covid-19 based on symptoms. A comparative analysis between various models has been done.

Best Models:

K-Nearest Neighbor: K-NN algorithm stores all the available data and classifies a new data point based on the similarity. 
The KNN algorithm assumes that similar things exist in close proximity. K is classified by a plurality poll of its neighbors. 
A class label assigned to the majority of K Nearest Neighbors from the training dataset is considered as a predicted class for the new data point.

ANN(Sequential Model): A Sequential model is appropriate for a  plain stack of layers where each layer has exactly one input tensor and one output tensor.
The Sequential model allows us to build deep neural networks by stacking layers one on top of another. 
Since we’re now building a simple logistic regression model, we will have the input nodes directly connected to output node, without any hidden layers. 

Conclusion:
The trained model of KNN and ANN, both can predict the presence and absence of the Corona Virus Disease with 91% accuracy, based on symptoms.

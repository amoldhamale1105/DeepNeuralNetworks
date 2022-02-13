# DeepNeuralNetworks
Multi-layered neural network classifying datasets implemented using the Keras library of python  
Deep neural networks usually are used to classify datasets with maximum accuracy when a simple linear perceptron based solution is not possible  
For instance the ```deepNeuralNetwork.py``` code is used generate a non-linear decision boundary for this dataset since a straight line would not be able to classify it clearly without errors  
![complexDataset](https://user-images.githubusercontent.com/78597991/153757465-e62c86a0-a45a-4210-ac74-e24e0a106760.png)  
The orange data points are labelled 1 and blue as 0 for the supervised learning model

## Training info
```deepNeuralNetwork.py``` is trained in 25 iterations of 20 batches thus resulting in one epoch covering 500 data points in the given dataset  
The model is trained over 100 epochs although you may notice that it reaches maximum accuracy much sooner but needs large number of epochs to sufficiently minimize the loss. Execute the code to look the `accuracy` and `loss` plots  
This model is built with 2 input nodes, 1 hidden layer comprising of 4 perceptrons and one output node  
The model uses sigmoid activation function at each decision node or activation point during the feed forward process

## Build instructions
Its best to execute the code on Google colab workspace to get faster results  
Run all cells or entire code to observe the decision boundaries and prediction of the 2 sample points  
The prediction output is the probablity(0-1) of the sample data point being labelled 1

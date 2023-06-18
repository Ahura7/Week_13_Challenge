# Week_13_Challenge
USYD FinTech Week 13 Homework
*Written using Python script in Jupyter notebook*

# Results:
With the help 3 iterations of deep neural network models we set out to create a model that predicts whether applicants will be successful if funded by Alphabet Soup:

## Base Model

- Input Layer | 2 Hidden Layers | Output Layer
- Hidden Layer 1: 8 Neurons, Hidden Layer 2: 4 Neuorns
- Epochs: 50
- Loss: 4.791581630706787, Accuracy: 0.6513119339942932

## Alternate Model 1: Added an Additional Layer

- Input Layer | 3 Hidden Layers | Output Layer
- Hidden Layer 1: 8 Neurons, Hidden Layer 2: 4 Neuorns, Hidden Layer 3: 4 Neuorns
- Epochs: 50
- Loss: 3.421417713165283, Accuracy: 0.5991836786270142

## Alternate Model 2: Added More Neurons in Layers 1 to 3 and Double the Epochs

- Input Layer | 3 Hidden Layers | Output Layer
- Hidden Layer 1: 10 Neurons, Hidden Layer 2: 8 Neuorns, Hidden Layer 3: 6 Neuorns
- Epochs: 100
- Loss: 8.408007621765137, Accuracy: 0.4529446065425873

# Outcome

**Wtih an increased number of layers, neurons and epochs, the accuracy of the model decreased in predicting successful applicants funded by Alphabet. Further model enhancement can include removing features that might be contributing to outliers in the data.**


# Resources
- https://stats.stackexchange.com/questions/181/how-to-choose-the-number-of-hidden-layers-and-nodes-in-a-feedforward-neural-netw
- https://stackoverflow.com/questions/70067588/valueerror-input-0-of-layer-sequential-is-incompatible-with-the-layer-expect
- https://discuss.tensorflow.org/t/valueerror-input-0-of-layer-sequential-1-is-incompatible-with-the-layer-expected-shape-none-6-216-1-found-shape-none-216-1/14905/13

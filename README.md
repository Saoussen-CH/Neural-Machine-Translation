# Neural-Machine-Translation
Sequence to Sequence Neural Machine translation with Attention implemented in PyTorch 

Framework and Libraries : PyTorch, Numpy
Platform : Google Colaboratory GPU

# Phases : 

## - Data Exploration and preparation :

- An English to French translation dataset of : 137861 english sentences and a corresponding 137861 french sentences 

+ Techniques : 
** Preprocessing:
+++ Removing Outliers
+++ Tokenization and Removing Punctuation
+++ Padding
*** Splitting the dataset into Training (80%), Validation (10%) , Testing (10%)

## - Modeling and Validation Phase : 

+ Techniques : 
++ Implementing the Encoder in PyTorch, includes an Embedding layer and GRU cells
++ Implementing the Decoder with Attention mechanism in PyTorch, includes an Embedding layer, GRU cells and Dropout 
++ Implementing the sequence to sequence architecture in PyTorch with Batch processing.
++ Implementation of a training and validation methods
++ Hyperparameters Tuning
++ Used Cross-validation technique
++ Best validation accuracy : 92.01 % after 25 epochs

## - Testing Phase:
++ Testing the trained model on the unseen test dataset resulted on an accuracy : 90.13 % 
++ Implementation of a prediction function that predicts the best translation of an input English sentence to French using the trained model.

For this project I used:
-pandas for loading the dataset and dataset manipulation
-numpy for mathematical operations
-PyTorch for implementing Neural Network Architecture
-sklearn for model classification

Project Steps:
1. Imported Libraries
2. Loaded the dataset and then split it into a Train and Test subsection.
3. Used DataLoader and Dataset from torch to improve model parameters.
4. Defined Model architecture with
   - Conv1D layer
   - BatchNormalization Layer
   - ReLU Layer
   - MaxPooling Layer
Then defined a forward pass method
5. Trained the neural network on the dataset while attempting to utilize GPU acceleration
6. Turned on evaluation mode
   - Turned off model droput of neurons
   - printed out a classification report and shows class weights
     N = Normal
     S = Supraventricular
     V = Ventricular
     F = Fusion
     Q = Unknown
   Model is accurate 97 percent of the time

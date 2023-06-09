# ERA1_Session6
 Session 6 assignment is to modify a given neural net model to classify MNIST hand written digits that achives validation accuracy of >= 99.4 using model parameters less than 20000 and training it for less than 20 epochs.

The strategy was to utilize small channel sizes (8, 16, 32) to keep the total parametes under 20000. Use Maxpool2D layer to achive higher RF with less depth, utilize batch norm and dropouts at all layers (except the last) to achieve generalization.

The model with 18014 parameters achieved greater than 99.4 accuracy with 11 epochs of training.

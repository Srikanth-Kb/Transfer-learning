# Transfer-learning
A base-example for using Transfer learning to obtain better results in training for systems with less labelled data to train and have pretrained networks existing.
The feature extraction part of the networks are freezed(static) with their gradients not updated in each backpropagation.
The classifier part of the networks are updated to recognize which features are important for our use. 
In data augmentation, random rotations is removed and jitters is set to 1(which was initially 0.2), because it has produced better performance. 

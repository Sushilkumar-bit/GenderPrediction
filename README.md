# Going deeper
For those not satisfied with the demo and have more understanding how the model is built and trained. This section is for you.
The datasets came from IMDB-WIKI – 500k+ face images with age and gender labels. Each image before feeding into the model we did the same preprocessing step shown above, detect the face and add margin.
The feature extraction part of the neural network uses the WideResNet architecture, short for Wide Residual Networks. It leverages the power of Convolutional Neural Networks (or ConvNets for short) to learn the features of the face. From less abstract features like edges and corners to more abstract features like eyes and mouth.
What unique of the WideResNet architecture is that the author decreased the depth and increased the width of original residual networks so it trained several times faster. Link to the paper here.

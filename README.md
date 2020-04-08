# CNN_kernel_visualization
Neural Network Visualization


## This code is to understand kernel/Channel Visualization. 

The idea here to get an understanding of the Interpretability in a CNN

### Approach

- Load pre-trained VGG with weights initializied for IMAGENET
- Change the final activation layer to Linear
- Pick a few images
- Show activations last few layers of the Network
- A heatmap is generated that is overlayed on the original image
- This gives a good viewpoint on what the network has learned to make the prediction

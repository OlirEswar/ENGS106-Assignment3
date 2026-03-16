## Model
The model implements the formulas described in the assignment notebook to create a diffusion model capable of generating MNIST digits. The parameters of 1000 timesteps, 64 hidden dimensions in the U-Net and convolution architecture were defined in the assignment's configuration. 

## Evaluation
The model trained on a large amount of MNIST digit data for 10 epochs. While the model is able to generate some reasonable numbers, many of the numbers the model generates do not match actual numbers. However, the patterns which these generated numbers are made of do resemble patterns in actual numbers. The curves of 3's and 5's appear in the generated images. This indicates that some features are being learned.

## Reflection
I found it fascinating to see the model learn some of the features of various numbers. Seeing how the model doesn't get everything quite right but still has correct features clearly showed that it was learning something
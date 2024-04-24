## Convolutional Networks

### Required Study Materials
1. **[A friendly introduction to Convolutional Neural Networks and Image Recognition](https://www.youtube.com/watch?v=2-Ol7ZB0MmU)** (video:32min) by Luis Serano 
2. **[Transfer Learning, Explainability in CNN, Adversarial attacks](https://www.youtube.com/watch?v=PCIGOK7WqEg)** (video:25min) by DeepFindr
3. **[AI for Self-driving cars](https://www.youtube.com/watch?v=hx7BXih7zx8)** (video:30min) by Andrej Karpathy from Tesla

### On Session Materials

1. Jupyter Notebook: [Convolution for pixel image](/on-session/06-Convolutional_network/Convolution_for_pixel_image.ipynb)
2. Jupyter Notebook: [ConvNext with Tom and Jerry](/on-session/06-Convolutional_network/ConvNext_Tom_and_Jerry.ipynb)

### Activities
#### 1. Convolution on pixel image
- each team gets a paper with grid (9x9) and draws a pixel image with black, gray and white colors
- write on board different kernels (3x3 matrices filled with values, use eg. smoothing, edge detection or horizontal line detection)
- [teacher] check that students know how the convolution works
- take the pixel image, black ~ -1, gray ~ 0, white ~ 1, do the convolution (no padding, stride 1) for all kernels, go back to 1/0/-1 values (we can call this function pooling) and their colors -> we will get new images, each corresponding to one kernel
- to make the computations easier, we can use [this notebook](/on-session/06-Convolutional_network/Convolution_for_pixel_image.ipynb)
- additional activity: let them think about why are CNNs better than classical fully connected networks 
- after the activity explain the terms usually used while building the convolution layer in context of our images, e.g. kernel size, stride length, padding, filters, pooling; also ask about what they think each kernel was for

#### 2. Finetuning ConvNext to classify Tom and Jerry pictures

- real code, run through Google Colab
- we will use already trained ConvNext - CNN for image classification
- finetune it for our custom dataset of Tom and Jerry images downloaded from [Kaggle](https://www.kaggle.com/datasets/balabaskar/tom-and-jerry-image-classification)
- check the [notebook](/on-session/06-Convolutional_network/ConvNext_Tom_and_Jerry.ipynb)

  
### Reasoning
- try the convolution, know how it's computed and understand what the parameters we are inputting to the convolution layer means
- understand the idea of finetuning and why it can be useful
- get to some real coding, try Google Colab

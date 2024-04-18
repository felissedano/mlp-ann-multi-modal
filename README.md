# mlp-ann-multi-modal
A Multi-layer perception ANN written in with CUDA CuPy GPU acceleration support. Can be trained on image and text data to do classification tasks. Can dynamically change network size by tune hyper parameters. The code demontrates how the network is trained on image data and text data and also plot the training loss and accuracy scores. User can choose which training algorithm to use (Perturbation, Gradient Descent and Feedback Alignment).

## Dataset
For the image data, I used the classic MNIST dataset which can be found [here](https://www.kaggle.com/datasets/pablotab/mnistpklgz)
FOr the text data, I used the AG news corpus which can be found [here](https://github.com/mhjabreel/CharCnn_Keras/tree/master/data/ag_news_csv)

# MHacksX PyTorch Tutorial

PyTorch is a powerful deep learning research platform that provides maximum flexibility and speed, and it allows you to replace numpy to use the power of GPUs. It is similar in some ways to Tensorflow but utilizes dynamic graphs. 

To whet your appetite and to get you going in PyTorch, you will learn how to build a simple Convolutional Neural Network on the [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist) in this tutorial. 

## Preliminaries
This tutorial assumes that you: 
1. Installed [Anaconda](https://www.continuum.io/downloads) with Python 3.5+
2. Updated conda with: `conda update conda`
3. Have a basic understanding of Convolutional Neural Networks ([watch this video](https://www.youtube.com/watch?v=FmpDIaiMIeA)) 

## PyTorch Setup
1. Create conda environment: `conda create --name pytorch numpy`
2. Activate conda environment: `source activate pytorch`
3. Install PyTorch: `conda install pytorch torchvision -c soumith`
4. Install Jupyter notebook kernel and matplotlib: `conda install nb_conda matplotlib`

## Download Data
1. Either clone this repo or go [here](https://github.com/zalandoresearch/fashion-mnist) and find the section entitled **Get the Data** located towards the middle.
2. (Optional) If you chose to download from the website, download the training and test set images and labels. (note where you saved these files)

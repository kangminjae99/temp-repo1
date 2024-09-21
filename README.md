# My Project Plan
*Note: This document is written merely as an illustrative example, and does not provide any working guide to an actual project.*

### Proposal
I am planning to make a **computer vision software** that detects objects in images.

In order to build it, I will use [`opencv`](https://opencv.org/), deep learning libraries, such as [`TensorFlow`](https://www.tensorflow.org/?hl=ko) or [`PyTorch`](https://pytorch.org/), and other open source software.

For example, the objects in the following images were detected using [`mmdetection`](https://github.com/open-mmlab/mmdetection):  

![Object detection example](https://user-images.githubusercontent.com/12907710/187674113-2074d658-f2fb-42d1-ac15-9c4a695e64d7.png)

### Dependencies
The following are the required dependencies:

- **python**
- **opencv-python**
- **tensorflow**
- **openmmlab**
- **package manager**

### Installation
In a bash terminal, run the following commands *(Do NOT actually run these commands in your computer)*:

```bash
$ sudo apt update 
$ conda create -n cv_detection 
$ conda activate cv_detection 
$ python --version 
$ python example.py

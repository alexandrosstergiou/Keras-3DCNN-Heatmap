# Saliency Tubes: Visual Explanations for Spatio-Temporal Convolutions

![supported versions](https://img.shields.io/badge/python-2.7%2C%203.5-green.svg)
[![Bugzilla bug status](https://img.shields.io/github/issues/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions.svg)](https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions/issues)
[![license](https://img.shields.io/github/license/alexandrosstergiou/Keras-3DCNN-Heatmap.svg)](https://github.com/alexandrosstergiou/Keras-3DCNN-Heatmap/blob/master/LICENSE)
[![GitHub language count](https://img.shields.io/badge/library-pytorch%2Ckeras-blue.svg)](https://keras.io/)

## Abstract
Deep learning approaches have been established as the main methodology for video classification and recognition. Recently, 3-dimensional convolutions have been used to achieve state-of-the-art performance in many challenging video datasets. Because of the high level of complexity of these methods, as the convolution operations are also extended to additional dimension in order to extract features from them as well, providing a visualization for the signals that the network interpret as informative, is a challenging task. An effective notion of understanding the network's inner-workings would be to isolate the spatio-temporal regions on the video that the network finds most informative. We propose a method called Saliency Tubes which demonstrate the foremost points and regions in both frame level and over time that are found to be the main focus points of the network. We demonstrate our findings on widely used datasets for third-person and egocentric action classification and enhance the set of methods and visualizations that improve 3D Convolutional Neural Networks (CNNs) intelligibility.

We have recently made available the full paper on arxiv: [https://arxiv.org/pdf/1902.01078.pdf](https://arxiv.org/pdf/1902.01078.pdf)

More visualisations can be found in our youtube video: [https://youtu.be/JANUqoMc3es](https://youtu.be/JANUqoMc3es)

For videos, these frames can be turned to video/GIFs with tools such as [`ImageMagic`](https://github.com/ImageMagick/ImageMagick) or [`imageio`](http://imageio.github.io/).

<p float="left">
<img src="https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions/blob/master/examples/cliff_diving.gif" width="120" height="120" /> 
<img src="https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions/blob/master/examples/rafting.gif" width="120" height="120" />
  <img src="https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions/blob/master/examples/bowling.gif" width="120" height="120" /> 
<img src="https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions/blob/master/examples/opening_door.gif" width="120" height="120" /> 
<img src="https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions/blob/master/examples/washing.gif" width="120" height="120" />
  <img src="https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions/blob/master/examples/opening_drawer.gif" width="120" height="120" /> 
</p>



## Installation
Please make sure, Git is installed in your machine:
```sh
$ sudo apt-get update
$ sudo apt-get install git
$ git clone https://github.com/alexandrosstergiou/Saliency-Tubes-Visual-Explanations-for-Spatio-Temporal-Convolutions.git
```

## Dependencies
Currently the repository supports either Keras or Pytorch models.  `OpenCV` was used for processes in the frame level. For resizing the  to the original video dimensions we used `scipy.ndimage`.
```sh
$ pip install opencv-python
$ pip install scipy
```

## License
MIT


## Contact
Alexandros Stergiou

a.g.stergiou at uu.nl

Any queries or suggestions are much appreciated!

# Face_Detection

### When using OpenCV’s deep neural network module with Caffe models, you’ll need two sets of files:
1. The .prototxt file(s) which define the model architecture (i.e., the layers themselves)
2. The .caffemodel file which contains the weights for the actual layers
#### Both files are required to when using models trained using Caffe for deep learning.

## requirements
1. OpenCV 3.3
2. Python3
3. numpy

## running
### Face detection in images with OpenCV and deep learning
1. $ python detect_faces.py --image rooster.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

### Face detection in video and webcam with OpenCV and deep learning
1. $ python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

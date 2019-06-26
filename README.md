# darknet2caffe

# Steps:

  0. environment is python3. install caffe, pycaffe, pytorch.

  1. you should install upsample_layer into caffe,please check this link https://github.com/BVLC/caffe/pull/6384/commits/4d2400e7ae692b25f034f02ff8e8cd3621725f5c.

  2. run yolov3_darknet2caffe.py in this file.

	$ python3 yolov3_darknet2caffe.py yolov3.cfg yolov3.weights yolov3.prototxt yolov3.caffemodel

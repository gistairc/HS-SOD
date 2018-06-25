# HyperSpectral Salient Object Detection Dataset (HS-SOD)

### Hyperspectral Image Dataset for Benchmarking on Salient Object Detection (QoMEX 2018) 

#### Abstract
Many works have been done on salient object detection using supervised or unsupervised approaches on colour images. Recently, a few studies demonstrated that efficient salient object detection can also be implemented by using spectral features in visible spectrum of hyperspectral images from natural scenes. However, these models on hyperspectral salient object detection were tested with a very few number of data selected from various online public dataset, which are not specifically created for object detection purposes. Therefore, here, we aim to contribute to the field by releasing a hyperspectral salient object detection dataset with a collection of 60 hyperspectral images with their respective ground-truth binary images and representative rendered colour images (sRGB). We took several aspects in consideration during the data collection such as variation in object size, number of objects, foreground-background contrast, object position on the image, and etc. Then, we prepared ground truth binary images for each hyperspectral data, where salient objects are labelled on the images. Finally, we did performance evaluation using Area Under Curve (AUC) metric on some existing hyperspectral saliency detection models in literature.

#### Dataset Details
Details of the dataset (e.g. hyperspectral camera, data format, data collection, and etc.) can be seen in this **[paper](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxpbWFtb2dsdW5ldnJlenxneDo0ZDVkYjE1YjVmN2QzMjYx).**  

**Cite as**: Nevrez Imamoglu, Yu Oishi, Xiaoqiang Zhang, Guanqun Ding, Yuming Fang, Toru Kouyama, Ryosuke Nakamura, "Hyperspectral Image Dataset for Benchmarking on Salient Object Detection", 10th International Conference on Quality of Multimedia Experience (QoMEX), Sardinia, Italy, May 29 - June 1, 2018.

### Download
The dataset can be downloaded from [here](dataset_link) (5.6GB). 
Or type the following in the terminal.
```
$ wget dataset_link
$ unzip HS-SOD.zip
```
**HS-SOD.zip** file contains three folders: i) **hyperspectral**: containing 60 hyperspectral images with #spatial rows:768 #spatial columns:1024 #spectral channels:81 (data only within visible spectrum: 380 nm -720 nm) , ii) **color**: 60 color images of hyperspectral dataset rendered in sRGB for visualization, iii) **ground-truth**: 60 ground-truth binary images for salient objects

![fig:QoMEX2018_poster](https://github.com/gistairc/HS-SOD/blob/master/images/poster-QoMEX2018.png "poster")  

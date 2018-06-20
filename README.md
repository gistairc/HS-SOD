# HyperSpectral Salient Object Detection Dataset (HS-SOD)

### Hyperspectral Image Dataset for Benchmarking on Salient Object Detection (QoMEX 2018 short-paper) 

**Cite as**: Nevrez Imamoglu, Yu Oishi, Xiaoqiang Zhang, Guanqun Ding, Yuming Fang, Toru Kouyama, Ryosuke Nakamura, "Hyperspectral Image Dataset for Benchmarking on Salient Object Detection", 10th International Conference on Quality of Multimedia Experience (QoMEX), Sardinia, Italy, May 29 - June 1, 2018.


#### Abstract
Many works have been done on salient object detection using supervised or unsupervised approaches on colour images. Recently, a few studies demonstrated that efficient salient object detection can also be implemented by using spectral features in visible spectrum of hyperspectral images from natural scenes. However, these models on hyperspectral salient object detection were tested with a very few number of data selected from various online public dataset, which are not specifically created for object detection purposes. Therefore, here, we aim to contribute to the field by releasing a hyperspectral salient object detection dataset with a collection of 60 hyperspectral images with their respective ground-truth binary images and representative rendered colour images (sRGB). We took several aspects in consideration during the data collection such as variation in object size, number of objects, foreground-background contrast, object position on the image, and etc. Then, we prepared ground truth binary images for each hyperspectral data, where salient objects are labelled on the images. Finally, we did performance evaluation using Area Under Curve (AUC) metric on some existing hyperspectral saliency detection models in literature.

### Download
The dataset can be downloaded from [here](http://data.airc.aist.go.jp/HS-SOD/HS-SOD.zip) (5.6GB). 
Or type the following in the terminal.

```
$ wget http://data.airc.aist.go.jp/HS-SOD/HS-SOD.zip
$ unzip HS-SOD.zip
```

**HS-SOD.zip** file contains three fodlers: i)**hyperspectral**: containign 60 hyperspectral images with rows: 768 column: 1024x81 , ii)**color**:   , iii)**ground-truth**:

### Dataset Details

For data collection, NH-AIK model hyperspectral camera is used, which is based on NH-series (NH-5) \cite{18} (see Fig.1) and produced by Eba-Japan Co. Ltd \cite{18}. In Table \ref{table:table1}, specifications of the camera are given. 




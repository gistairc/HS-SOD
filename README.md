# HyperSpectral Salient Object Detection Dataset (HS-SOD)

### Hyperspectral Image Dataset for Benchmarking on Salient Object Detection (QoMEX 2018)

> [!IMPORTANT]
> The original AIST dataset server hosting HS-SOD has been retired.
>
> The dataset is now hosted by the Geoinformation Service Research Group (AIST) on Hugging Face:
>
> **Dataset Repository:**  
> https://huggingface.co/datasets/gsvrg/HS-SOD

#### Abstract

Many works have been done on salient object detection using supervised or unsupervised approaches on colour images. Recently, a few studies demonstrated that efficient salient object detection can also be implemented by using spectral features in visible spectrum of hyperspectral images from natural scenes. However, these models on hyperspectral salient object detection were tested with a very few number of data selected from various online public dataset, which are not specifically created for object detection purposes. Therefore, here, we aim to contribute to the field by releasing a hyperspectral salient object detection dataset with a collection of 60 hyperspectral images with their respective ground-truth binary images and representative rendered colour images (sRGB). We took several aspects in consideration during the data collection such as variation in object size, number of objects, foreground-background contrast, object position on the image, and etc. Then, we prepared ground truth binary images for each hyperspectral data, where salient objects are labelled on the images. Finally, we did performance evaluation using Area Under Curve (AUC) metric on some existing hyperspectral saliency detection models in literature.

#### Dataset Details

Details of the dataset (e.g. hyperspectral camera, data format, data collection, and etc.) can be seen in this [paper](https://arxiv.org/abs/1806.11314).

**Cite as:**

> Nevrez Imamoglu, Yu Oishi, Xiaoqiang Zhang, Guanqun Ding, Yuming Fang, Toru Kouyama, Ryosuke Nakamura,
> "Hyperspectral Image Dataset for Benchmarking on Salient Object Detection",
> 10th International Conference on Quality of Multimedia Experience (QoMEX),
> Sardinia, Italy, May 29 - June 1, 2018.

## Download

The HS-SOD dataset is available on Hugging Face:

**Dataset Page**

https://huggingface.co/datasets/gsvrg/HS-SOD

**Direct Download**

https://huggingface.co/datasets/gsvrg/HS-SOD/resolve/main/HS-SOD.zip

Download from the command line:

```bash
wget https://huggingface.co/datasets/gsvrg/HS-SOD/resolve/main/HS-SOD.zip
unzip HS-SOD.zip
```

**HS-SOD.zip** contains three folders:

1. **hyperspectral**
   - 60 hyperspectral images
   - Spatial resolution: 768 × 1024
   - Spectral channels: 81
   - Visible spectrum range: 380–780 nm

2. **color**
   - 60 sRGB renderings of the hyperspectral images for visualization

3. **ground-truth**
   - 60 binary ground-truth masks for salient object detection

images/poster-QoMEX2018.png
![fig:QoMEX 2018 Poster](images/poster-QoMEX2018.png  "poster")

## Citation

If you use this dataset in your research, please cite:

```bibtex
@inproceedings{imamoglu2018hyperspectral,
  author    = {Nevrez Imamoglu and
               Yu Oishi and
               Xiaoqiang Zhang and
               Guanqun Ding and
               Yuming Fang and
               Toru Kouyama and
               Ryosuke Nakamura},
  title     = {Hyperspectral Image Dataset for Benchmarking on Salient Object Detection},
  booktitle = {Proceedings of the 10th International Conference on Quality of Multimedia Experience (QoMEX)},
  address   = {Sardinia, Italy},
  year      = {2018}
}
```

Paper:
https://arxiv.org/abs/1806.11314

## License

This dataset is distributed under the original HS-SOD Dataset Terms of Use.

See [LICENSE.md](LICENSE.md) for details.

## Acknowledgement

This dataset and source code are based on results obtained from a project commissioned by the New Energy and Industrial Technology Development Organization (NEDO).

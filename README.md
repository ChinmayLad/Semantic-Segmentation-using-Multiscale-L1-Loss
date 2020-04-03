# Semantic-Segmentation-using-Multiscale-L1-Loss

An Semantic Segmentation Network for segmenting medical WSI images using DeepLabv3 as Segmentor and Multiscale L1 Loss as Critic.

Papers:
* [An integrated iterative annotation technique for easing neural network training in medical image analysis](https://www.nature.com/articles/s42256-019-0018-3)
* [Rethinking Atrous Convolution for Semantic Image Segmentation](https://arxiv.org/abs/1706.05587)
* [SegAN: Adversarial Network with Multi-scale L1 Loss for Medical Image Segmentation](https://arxiv.org/abs/1706.01805)


|Label    |Type     |F1 Score   |IoUs    |
|---------|---------|----------|---------|
|0 |Background |0.955| 0.916|
|1| Glomureli| 0.741| 0.687|
|2| Podocyte| 0.150| 0.094|
|3| Non Podocyte| 0.517| 0.408|

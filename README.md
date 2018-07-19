# CSRNet (Try our [Pytorch Version](https://github.com/leeyeehoo/CSRNet-pytorch/tree/master)!)
This is the repo for [CSRNet: Dilated Convolutional Neural Networks for Understanding the Highly Congested Scenes](https://arxiv.org/abs/1802.10062) in CVPR 2018, which delivered a state-of-the-art, straightforward and end-to-end architecture for crowd counting tasks.
## Datasets
ShanghaiTech Dataset: [Google Drive](https://drive.google.com/open?id=16dhJn7k4FWVwByRsQAEpl9lwjuV03jVI)

## Models (Only for tests)

This is the model for test. The results should be similar to the results shown in the paper(slightly better or worse).

1) ShanghaiTech_Part_A: [Google Drive](https://drive.google.com/open?id=1odZ3B_ZDSepPcVFO_TfGUIrpF2DF7SwY)

2) ShanghaiTech_Part_B: [Google Drive](https://drive.google.com/open?id=1NOpn0ztlye85vrHR2TMwOI2Qu_S8zANj)

## Prerequisites

1) A good CAFFE

We understand that it's tedious and difficult to config a custom input layer (even installing CAFFE on your own PC), thus we make a pytorch version for the csrnet: [CSRNet Pytorch Version](https://github.com/leeyeehoo/CSRNet-pytorch/tree/master)

## References

If you find the CSRNet useful, please cite our paper. Thank you!

```
@inproceedings{li2018csrnet,
  title={CSRNet: Dilated convolutional neural networks for understanding the highly congested scenes},
  author={Li, Yuhong and Zhang, Xiaofan and Chen, Deming},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={1091--1100},
  year={2018}
}
```
Please cite the Shanghai datasets and other works if you use them.

```
@inproceedings{zhang2016single,
  title={Single-image crowd counting via multi-column convolutional neural network},
  author={Zhang, Yingying and Zhou, Desen and Chen, Siqin and Gao, Shenghua and Ma, Yi},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={589--597},
  year={2016}
}
```

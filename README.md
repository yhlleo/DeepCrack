## DeepCrack: A Deep Hierarchical Feature Learning Architecture for Crack Segmentation

 - **Paper**: [paper](./paper/DeepCrack-Neurocomputing-2019.pdf) is available at [sNeurocomputing](https://www.sciencedirect.com/science/article/pii/S0925231219300566)(IF: 4.072).
 - **Code**: Pytorch implementation: [[yhlleo/DeepSegmentor]](https://github.com/yhlleo/DeepSegmentor)
 - **Architecture**: based on Holistically-Nested Edge Detection, ICCV 2015, [[Paper]](https://arxiv.org/abs/1504.06375)[[code]](https://github.com/s9xie/hed).

![](./figures/architecture.jpg)

 - **Dataset**:

We established a public benchmark dataset with cracks in multiple scales and scenes to evaluate the crack detection systems. All of the crack images in our dataset are manually annotated.

**Please note that we own the copyrights to part of original crack images and all annotated maps. Their use is RESTRICTED to non-commercial research and educational purposes.**

You can find the dataset in `./dataset`, and here are the details:

|Folder|Description|
|:----|:-----|
|`train_img`|RGB images for training|
|`train_lab`|binary annotation for training images|
|`test_img`|RGB images for testing|
|`test_lab`|binary annotation for testing images|

A brief overview on our crack detection dataset:

![](./figures/dataset-overview.jpg)


 - **Reference:**

If you use this dataset for your research, please cite our paper:


```
@article{liu2019deepcrack,
  title={DeepCrack: A Deep Hierarchical Feature Learning Architecture for Crack Segmentation},
  author={Liu, Yahui and Yao, Jian and Lu, Xiaohu and Xie, Renping and Li, Li},
  journal={Neurocomputing},
  volume={338},
  pages={139--153},
  year={2019},
  doi={10.1016/j.neucom.2019.01.036}
}
```

If you have any questions, please contact me: yahui.liu AT unitn.it without hesitation.

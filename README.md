## DeepCrack: A Deep Hierarchical Feature Learning Architecture for Crack Segmentation

 - **Paper**: [[available on Neurocomputing]](https://www.sciencedirect.com/science/article/pii/S0925231219300566), submitted 14 Dec., 2017, accepted 15 Jan. 2019.
 - **Architecture**: based on Holistically-Nested Edge Detection, ICCV 2015, [[Paper]](https://arxiv.org/abs/1504.06375)[[code]](https://github.com/s9xie/hed).

![](./figures/architecture.jpg)

 - **Dataset**:

We established a public benchmark dataset with cracks in multiple scales and scenes to evaluate the crack detection systems. All of the crack images in our dataset are manually annotated.

You can find the dataset in `./dataset`, and here are the details:

|Folder|Description|
|:----|:-----|
|`train_img`|RGB images for training|
|`train_lab`|binary annotation for training images|
|`test_img`|RGB images for testing|
|`test_lab`|binary annotation for testing images|

A brief overview on our crack detection dataset:

![](./figures/dataset-overview.jpg)

 - **Citation:**

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

You are also welcomed to contact me: yahui.cvrs@gmail.com .

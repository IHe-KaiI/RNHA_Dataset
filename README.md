# 3D Human Dataset
The dataset of the paper "Relightable Neural Human Assets from Multi-view Gradient Illuminations".

## Relightable Neural Human Assets from Multi-view Gradient Illuminations

Taotao Zhou\*, Kai He\*, Di Wu\*, Teng Xu, Qixuan Zhang, Kuixiang Shao, Wenzheng Chen, Lan Xu, Jingyi Yu. 

(*equal contribution) CVPR 2023

[[Project Page]](https://miaoing.github.io/RNHA/) [[Paper Link]](https://arxiv.org/pdf/2212.07648.pdf) [[Dataset Link]](https://shanghaitecheducn-my.sharepoint.com/:f:/g/personal/hekai_shanghaitech_edu_cn/EkwUhF_qoW1CpipgeXwLZxcBMa8clsdGhdR4ub-1f5cfIw?e=5ej5FE)

![dataset_description](./imgs/dataset_description.png)

### Description

We have currently uploaded 100 sample cases of data with different people and different motions. We will be uploading all the data (2K+) soon. The file structure is as follows:

- 8fuu431r1yviisw4.zip (Random filename)
  - full_on (Full on light)
    - 00000.jpg ([Camera index].jpg)
    - ...
    - 00031.jpg 
  - pos (Positive gradient light)
    - 00000.jpg
    - ...
    - 00031.jpg
  - neg (Negative gradient light)
    - 00000.jpg
    - ...
    - 00031.jpg
  - mask (Mask)
    - 00000.jpg
    - ...
    - 00031.jpg
  - normal_alpha (Estimated normal with alpha mask channel)
    - 00000.jpg
    - ...
    - 00031.jpg
  - transforms.json
- 8fuu431r2rlnjhv6.zip
- ...



### Download our dataset

The dataset is available on [OneDrive](https://shanghaitecheducn-my.sharepoint.com/:f:/g/personal/hekai_shanghaitech_edu_cn/EkwUhF_qoW1CpipgeXwLZxcBMa8clsdGhdR4ub-1f5cfIw?e=5ej5FE) and requires permission to access. Please carefully read, fill in the [license form](./license.pdf), and send it to Lan Xu (xulan1@shanghaitech.edu.cn) and cc MARS Lab (shanghaitechmars@foxmail.com) to request the access.

By requesting the access to the content, you acknowledge that you have read this agreement, understand it, and agree to be bound by its terms and conditions. This agreement constitutes a legal and binding agreement between you and the provider of the protected system or content. The Multidisciplinary Artificial Reality Studio (MARS) of ShanghaiTech University is the only owner of all intellectual property rights, including copyright, of 3D HUMAN DATASET, and MARS reserves the right to terminate your access to the dataset at any time.

Notes:

(1) Students are **NOT** eligible to be a recipient.  If you are a student, please ask your supervisor to make a request.

(2) Once the license agreement is signed, we will give access to the data.

### Citation

If you use this dataset for your research, please cite our paper:

```
 @article{zhou2022relightable,
      title={Relightable Neural Human Assets from Multi-view Gradient Illuminations},
      author={Zhou, Taotao and He, Kai and Wu, Di and Xu, Teng and Zhang, Qixuan and Shao, Kuixiang and Chen, Wenzheng and Xu, Lan and Yi, Jingyi},
      journal={arXiv preprint arXiv:2212.07648},
      year={2022}
    }
```




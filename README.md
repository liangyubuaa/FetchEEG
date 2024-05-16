# FetchEEG
This is an implementation of the FetchEEG model, described in the following paper: 

**FetchEEG: a hybrid approach combining feature extraction and temporal-channel joint attention for EEG-based emotion classification**

_Liang et al 2024 J. Neural Eng. https://doi.org/10.1088/1741-2552/ad4743_

## abstract 

_Objective._ Electroencephalogram (EEG) analysis has always been an important tool in neural engineering, and the recognition and classification of human emotions are one of the important tasks in neural engineering. EEG data, obtained from electrodes placed on the scalp, represent a valuable resource of information for brain activity analysis and emotion recognition. Feature extraction methods have shown promising results, but recent trends have shifted toward end-to-end methods based on deep learning. However, these approaches often overlook channel representations, and their complex structures pose certain challenges to model fitting. _Approach._ To address these challenges, this paper proposes a hybrid approach named FetchEEG that combines feature extraction and temporal-channel joint attention. Leveraging the advantages of both traditional feature extraction and deep learning, the FetchEEG adopts a multi-head self-attention mechanism to extract representations between different time moments and channels simultaneously. The joint representations are then concatenated and classified using fully-connected layers for emotion recognition. The performance of the FetchEEG is verified by comparison experiments on a self-developed dataset and two public datasets. _Main results._ In both subject-dependent and subject-independent experiments, the FetchEEG demonstrates better performance and stronger generalization ability than the state-of-the-art methods on all datasets. Moreover, the performance of the FetchEEG is analyzed for different sliding window sizes and overlap rates in the feature extraction module. The sensitivity of emotion recognition is investigated for three- and five-frequency-band scenarios. _Significance._ FetchEEG is a novel hybrid method based on EEG for emotion classification, which combines EEG feature extraction with Transformer neural networks. It has achieved state-of-the-art performance on both self-developed datasets and multiple public datasets, with significantly higher training efficiency compared to end-to-end methods, demonstrating its effectiveness and feasibility.

## Requirements

- Python 3.8
- Pytorch 1.11

## Dataset access
To gain access to the dataset, please send an email to yuliang@bjut.edu.cn with the subject of “Dataset request”. 

## Reference

```
@article{Liang_2024,
  doi = {10.1088/1741-2552/ad4743},
  url = {https://dx.doi.org/10.1088/1741-2552/ad4743},
  year = {2024},
  month = {may},
  publisher = {IOP Publishing},
  volume = {21},
  number = {3},
  pages = {036011},
  author = {Yu Liang and Chenlong Zhang and Shan An and Zaitian Wang and Kaize Shi and Tianhao Peng and Yuqing Ma and Xiaoyang Xie and Jian He and Kun Zheng},
  title = {FetchEEG: a hybrid approach combining feature extraction and temporal-channel joint attention for EEG-based emotion classification},
  journal = {Journal of Neural Engineering},
}
```

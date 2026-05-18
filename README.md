# AIWSEN
AIWSEN: Adaptive Information Weighting and Synchronized Enhancement Network for Hyperspectral Change Detection

Welcome to the repository for our paper: "AIWSEN: Adaptive Information Weighting and Synchronized Enhancement Network for Hyperspectral Change Detection."

### Requirements
torch 1.7.1 + cu101

python 3.7

torchvision 0.8.2 + cu101

### USA dataset

[https://pan.baidu.com/s/1mbt9URipxV5UC6YoUd47Uw?pwd=r9ru](https://pan.baidu.com/s/1mbt9URipxV5UC6YoUd47Uw?pwd=r9ru)

### Usage

The main function for training is AWISEN/train_HSI.py. 

The specific hyperparameter settings can be found in AWISEN/configs/configs.py.

If you need to replace the dataset, please update the dataset files in the AWISEN/datasets/ directory and modify the corresponding settings in AWISEN/data/get_dataset.py.

### Citation
If you find this work helpful, please cite our paper:

> L. Wu, J. Peng, B. Yang, W. Sun and Z. Ye, "AIWSEN: Adaptive Information Weighting and Synchronized Enhancement Network for Hyperspectral Change Detection," in IEEE Transactions on Geoscience and Remote Sensing, doi: 10.1109/TGRS.2025.3531478.


```bibtex
@ARTICLE{10845805,
  author={Wu, Lanxin and Peng, Jiangtao and Yang, Bing and Sun, Weiwei and Ye, Zhijing},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={AIWSEN: Adaptive Information Weighting and Synchronized Enhancement Network for Hyperspectral Change Detection}, 
  year={2025},
  volume={},
  number={},
  pages={1-12},
  keywords={Feature extraction;Transformers;Entropy;Data mining;Convolutional neural networks;Sun;Fuses;Synchronization;Hyperspectral imaging;Attention mechanisms;Hyperspectral image;change detection;adaptive information weighting;synchronic enhancing},
  doi={10.1109/TGRS.2025.3531478}



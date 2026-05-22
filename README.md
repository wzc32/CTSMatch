# Semi-Supervised AI for Architectural Heritage Classification and Style Lineage Discovery in Chinese Traditional Settlements

This repository contains the official code implementation for the paper published in ISPRS International Journal of Geo-Information.

## Paper

- **Title**: Semi-Supervised AI for Architectural Heritage Classification and Style Lineage Discovery in Chinese Traditional Settlements
- **Journal**: ISPRS International Journal of Geo-Information (IJGI)
- **Author**: Qing Han, Zicheng Wang, Chao Yin
- **DOI**: [10.3390/ijgi15050221](https://doi.org/10.3390/ijgi15050221)
- **Link**: https://www.mdpi.com/2220-9964/15/5/221

## Supported Models

We provide pre-trained weights and training configurations for the following semi-supervised learning models:

- **FreeMatch**
- **FixMatch**
- **CTSMatch (Ours)**

The implementation is built on [**TorchSSL**](https://github.com/TorchSSL/TorchSSL), a comprehensive semi-supervised learning framework that provides unified interfaces for various SSL algorithms.

## Dataset

SemiCTS is a dataset extends [**labeled CTS dataset**](https://github.com/PointCloudYC/CTS) with 4360 unlabeled images.

The released dataset is divided into three independent subsets:
- **Train Set**: Labeled samples for supervised training
- **Test Set**: Standard data for model performance evaluation
- **Unlabeled Set**: Unannotated samples for semi-supervised learning

Data partition ratio and usage rules strictly follow the scheme described in the original paper.

## Citation

If you use this code or models in your research, please cite our paper:

```bibtex
@article{Han2026,
  author = {Han, Qing and Wang, Zicheng and Yin, Chao and Hou, Zhiwei and Yao, Tianci},
  title = {Semi-Supervised AI for Architectural Heritage Classification and Style Lineage Discovery in Chinese Traditional Settlements},
  journal = {ISPRS International Journal of Geo-Information},
  volume = {15},
  number = {5},
  article = {221},
  year = {2026},
  doi = {10.3390/ijgi15050221},
  url = {https://www.mdpi.com/2220-9964/15/5/221}
}
```

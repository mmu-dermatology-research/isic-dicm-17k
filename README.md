# Skin Lesion Classification Using Dermoscopic Images and Clinical Metadata: Insights from Multimodal Models

**ISIC-DICM-17K** (**ISIC** **D**ermoscopic **I**mages and **C**linical **M**etadata **17K**) is a curated and balanced dataset designed to support research in skin lesion classification using both dermoscopic images and clinical metadata. The dataset is derived from the [International Skin Imaging Collaboration (ISIC) Archive Gallery](https://gallery.isic-archive.com/#!/topWithHeader/onlyHeaderTop/gallery) for multimodal skin lesion analysis research.

## Dataset Overview
- **Total Samples:** 17,060
- **Classes:**
    - **Melanoma:** 8,530 images
    - **Non-Melanoma:** 8,530 images
- **Modalities:** dermoscopic images and clinical metadata _(e.g., age, sex, anatomical site)_

This dataset has been used in [our study](https://www.openaccess.thecvf.com/content/CVPR2025W/MULA2025/papers/Ahammed_Skin_Lesion_Classification_Using_Dermoscopic_Images_and_Clinical_Metadata_Insights_CVPRW_2025_paper.pdf) to explore the effectiveness of multimodal learning for skin lesion classification.

## Download

You can access and download the dataset here: [ISIC-DICM-17K Download Link](https://api.isic-archive.com/collections/469/)

## Citation

If you use the ISIC-DICM-17K dataset or any part of this work in a research project, please consider citing [our paper](https://www.openaccess.thecvf.com/content/CVPR2025W/MULA2025/html/Ahammed_Skin_Lesion_Classification_Using_Dermoscopic_Images_and_Clinical_Metadata_Insights_CVPRW_2025_paper.html):

> **Skin Lesion Classification Using Dermoscopic Images and Clinical Metadata: Insights from Multimodal Models**  
> DOI: [10.1109/CVPRW67362.2025.00027](https://doi.org/10.1109/CVPRW67362.2025.00027)

```BibTex
@InProceedings{Ahammed_2025_CVPR,
    author    = {Ahammed, Sakib and Cui, Xia and Lu, Wenqi and Yap, Moi Hoon},
    title     = {Skin Lesion Classification Using Dermoscopic Images and Clinical Metadata: Insights from Multimodal Models},
    booktitle = {Proceedings of the Computer Vision and Pattern Recognition Conference (CVPR) Workshops},
    month     = {June},
    year      = {2025},
    pages     = {222-230}
}
```

The ISIC-DICM-17K dataset is partly based on the [curated balanced ISIC dataset](https://github.com/mmu-dermatology-research/isic_duplicate_removal_strategy) proposed by Cassidy et at. 2021, which should be cited as follows:

```BibTex
@article{cassidy2021isic,
 title   = {Analysis of the ISIC Image Datasets: Usage, Benchmarks and Recommendations},
 author  = {Bill Cassidy and Connah Kendrick and Andrzej Brodzicki and Joanna Jaworek-Korjakowska and Moi Hoon Yap},
 journal = {Medical Image Analysis},
 year    = {2021},
 issn    = {1361-8415},
 doi     = {https://doi.org/10.1016/j.media.2021.102305},
 url     = {https://www.sciencedirect.com/science/article/pii/S1361841521003509}
} 
```

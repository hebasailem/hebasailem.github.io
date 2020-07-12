---
abstract: Accurate segmentation of cellular structures is critical for automating the analysis of microscopy data. Advances in deep learning have facilitated extensive improvements in semantic image segmentation. In particular, U-Net, a model specifically developed for biomedical image data, performs multi-instance segmentation through pixel-based classifi- cation. However, approaches based on U-Net tend to merge touching cells in dense cell cultures, resulting in under-segmentation. To address this issue, we propose DeepSplit; a multi-task convolutional neural network architecture where one encoding path splits into two decoding branches. DeepSplit first learns segmentation masks, then explicitly learns the more challenging cell-cell contact regions. We test our approach on a challeng- ing dataset of cells that are highly variable in terms of shape and in- tensity. DeepSplit achieves 90% cell detection coefficient and 90% Dice Similarity Coefficient (DSC) which is a significant improvement on the state-of-the-art U-Net that scored 70% and 84% respectively.
authors:
- Andrew Torr
- Doga Basaran
- Julia Sero
- Jens Rittscher
- Heba Sailem
date: "2020-07-14T00:00:00Z"
doi: "10.1109/ICCVW.2017.13"
featured: false
publication: In *Medical Image Understanding and Analysis*
publication_short: In *MIUA*
tags:
- Artificial Intelligence
- Segmentaiton

publication_types:
- "1"
publishDate: "2020-07-14T00:00:00Z"
summary: "A two-branch U-Net to tackle the problem of undersegmentation (cell merging)."
title: "DeepSplit: Segmentation of Microscopy Images Using Multi-Task Convolutional Networks"
url_pdf: "publication/Torr_MIUA_2020_paper.pdf"
---

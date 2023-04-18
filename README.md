# A Comparison of Image Denoising Methods
Zhaoming Kong (kong.zm@mail.scut.edu.cn), Fangxi Deng, Haomin Zhuang, Xiaowei Yang, Jun Yu, Lifang He

## Overview
In this project, we intend to collect and compare various denoising methods to investigate their effectiveness, efficiency, applicability
and generalization ability with both synthetic and real-world experiments. Datasets, code and results are made publicly available
and will be continuously updated. To gain access to the dataset and the code, please send me an email (kong.zm@mail.scut.edu.cn) with information including name, position and usage. 

## Compared methods
The interest in the realm of denoising grows consistently with a large quantity of approaches, which may be roughly divided into two categories, namely traditional denoisers and DNN methods, depending on whether neural network architectures are utilized.

### Traditional denoisers
For traditional denoisers, learning and denoising are usually accomplished only with the noisy image by leveraging the NLSS property. To achieve this goal, the most popular and successful framework is attributed to BM3D, which mainly follows three consecutive stages: grouping, collaborative filtering and aggregation. The flowchart of this effective three-stage paradigm is illustrated in the following Figure.

<img src="Figs/Traditional_Flowchart.png" width="588px" height="218px"/>

Since the birth of BM3D, there is no shortage of extensions originating from different disciplines. Some representative traditional denoisers are summarized in the following Table.

<details>
<summary> Representative traditional denoisers (click here)</summary>
<p align="center">
  <img width="1180", height="808" src="Figs/Table1.png">
</p>
</details>


### Deep neural network (DNN) methods
The most recent development of image processing stems largely from the applications of deep learning techniques, which demonstrate outstanding performance in a wide variety of tasks. Image denoising is not an exception. From the early plain networks to recently proposed generative and diffusion models, numerous net- work architectures and frameworks have been developed with different training strategies, including supervised, self-supervised and unsupervised learning. The following figure illustrates a simple DNN denoising framework with three convolutional layers.

<img src="Figs/Fig3_PlainDNN.png" width="588px" height="218px"/>

Since the birth of BM3D, there is no shortage of extensions originating from different disciplines. Some representative traditional denoisers are summarized in the following Table.

<details>
<summary> Related DNN methods (click here)</summary>
<p align="center">
  <img width="1280", height="808" src="Figs/Table2.png">
</p>
</details>

## Experiments

* Image denoising (sRGB space).
<img src="Figs/DND_SIDD_comparison.png" width="1180px" height="206px"/>

* Video denoising (sRGB space).
<img src="Figs/Set8_CRVD.png" width="1180px" height="206px"/>

* MSI/HSI denoising.
<img src="Figs/MSI.png" width="1180px" height="286px"/>

* 3D MRI denoising.
<img src="Figs/MRI.png" width="1180px" height="136px"/>

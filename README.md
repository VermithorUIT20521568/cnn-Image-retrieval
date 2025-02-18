## CNN Image Retrieval in PyTorch: Training and evaluating CNNs for Image Retrieval in PyTorch

<img src="http://cmp.felk.cvut.cz/cnnimageretrieval/img/cnnimageretrieval_network_medium.png" width=\textwidth/>

<div align='left'>
  
|Full name|Student-ID|Role|
|:--:|:--:|:--:|
| [Dang Thi Tuong Vy](https://github.com/TuongVy20522176) |20522176| Leader |
| [Nguyen Hoang Long](https://github.com/LongHoangNguyenH) |20521568| Member |
| [Nguyen Tu Luan](https://github.com/luannguyen57) |20521583| Member |
| [Le Hoang Long](https://github.com/long0901) |20521563| Member |
  
</div>

Our video demo [click here](https://drive.google.com/drive/u/0/folders/1-4xaYQKf6gfTvbteylkhim65eozFyKYc)
---
### Table of contents
1. [Introduction](#1-introduction)
2. [Demo](#3-demo)
3. [Results](#4-results)
4. [References](#5-references)
---
### 1. Introduction
we choose the approach as the unsupervised CNNs fine-tuning for image retrieval.
Firstly, we harness SfM information and enforce for both hard unmatched and matched examples for CNNs training.
Secondly, we let our architectures learn the whitening through the same training data to avoid the short representations 
Finally, We choose to use a trainable pooling layer which generalizes existing popular pooling schemes for CNNs and thus both enhances the performance and preserving the same descriptor dimensionality as well.
### 2. Demo
Our video demo is storaged in [here](https://drive.google.com/drive/u/0/folders/1-4xaYQKf6gfTvbteylkhim65eozFyKYc)
### 3. Results

<div align='center'>
  <img width="1440" alt="demo1" src = "https://user-images.githubusercontent.com/79389744/227866259-3f6b0860-e1d0-40d3-aeb7-983831e34218.png">
  <img width ="1440" alt="demo2" src = "https://user-images.githubusercontent.com/79389744/227866730-97500559-777b-4bfc-a522-5f124f1d1d60.png">
  <img width ="1440" alt = "demo3" src ="https://user-images.githubusercontent.com/79389744/227867531-c3177066-dac5-47e0-9c99-5e6b303978f6.png">
  <img width ="1440"! alt = "demo4" src ="https://user-images.githubusercontent.com/79389744/227866880-d0b46b2d-f7dc-44b8-b008-0936ceb1118d.png">
</div>

### 4. References
Our work is inspired from:
[CNN Image Retrieval in PyTorch: Training and evaluating CNNs for Image Retrieval in PyTorch
](https://github.com/vokhanhan25/ImageRetrievalSystem)

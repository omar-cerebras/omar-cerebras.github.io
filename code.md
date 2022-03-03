---
layout: page
permalink: /code/
title: Some Code I've Written
tags: [code]
modified: 3-10-2014
comments: false
---

Here you can find some of the programs I've written.

### Research

* [**Improving ResNet-9 Generalization Trained on Small Datasets**](https://github.com/Omar-Awad/HAET2021_Huawei)<br>
My winning model at the "Hardware Aware Efficient Training" competition at ICLR 2021.
The challenge is to achieve the highest accuracy in
an image classification task given a limited training
time (10 min.). The public dataset for experimentation
is a mini-CIFAR10 with 10 classes,
each has 500 training samples and 100 test samples
of 32×32 pixels RGB images. The evaluation
is performed on mini-ImageNet dataset (hidden
at development time) of size similar to the development
dataset.

<img id="HAET2021_poster" src="../images/HAET2021_Huawei_poster.png" style="width:480;height:513.6;">

* [**Compressed-memory Sparse DNN Inference Acceleration on GPU**](https://github.com/Omar-Awad/SCNN_GPU2)<br>
Compressed-memory sparse DNN inference accelerator on NVIDIA GeForce GTX980, achieving a speedup up to 115x and 170x
on image classification and computational imaging models, respectively compared to an efficient openMP multi-threaded CPU
implementation.
<a href="https://drive.google.com/file/d/1J5PKEQtmodJqRb29zICN3q1NmbEm6MY1/view?usp=sharing" style="color:#FF0000;" target="_blank">[PDF]</a>
<style>
.responsive-wrap iframe{ max-width: 100%;}
</style>
<div class="responsive-wrap">
<!-- this is the embed code provided by Google -->
  <iframe src="https://docs.google.com/presentation/d/1Bk1nIddP9aGF8J6DNsUbOxd2XJx_IjmJ/embed?start=false&loop=false&delayms=3000&slide=id.p1" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
<!-- Google embed ends -->
</div>

* [**5-stage Pipelined MIPS Processor with Encrypted Memory**](https://github.com/Omar-Awad/encrypted-MIPS)<br>
5-stages pipelined MIPS processor with 10-instructions and encrypted memory using Xilinx ISE.

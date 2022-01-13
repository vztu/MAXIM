[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/deblurring-on-hide-trained-on-gopro)](https://paperswithcode.com/sota/deblurring-on-hide-trained-on-gopro?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/deblurring-on-realblur-j-1)](https://paperswithcode.com/sota/deblurring-on-realblur-j-1?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/low-light-image-enhancement-on-lol)](https://paperswithcode.com/sota/low-light-image-enhancement-on-lol?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/single-image-deraining-on-rain100h)](https://paperswithcode.com/sota/single-image-deraining-on-rain100h?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/single-image-deraining-on-rain100l)](https://paperswithcode.com/sota/single-image-deraining-on-rain100l?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/deblurring-on-realblur-r)](https://paperswithcode.com/sota/deblurring-on-realblur-r?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/single-image-deraining-on-test100)](https://paperswithcode.com/sota/single-image-deraining-on-test100?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/image-denoising-on-sidd)](https://paperswithcode.com/sota/image-denoising-on-sidd?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/single-image-deraining-on-test2800)](https://paperswithcode.com/sota/single-image-deraining-on-test2800?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/deblurring-on-realblur-j-trained-on-gopro)](https://paperswithcode.com/sota/deblurring-on-realblur-j-trained-on-gopro?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/image-denoising-on-dnd)](https://paperswithcode.com/sota/image-denoising-on-dnd?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/deblurring-on-realblur-r-trained-on-gopro)](https://paperswithcode.com/sota/deblurring-on-realblur-r-trained-on-gopro?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/single-image-deraining-on-test1200)](https://paperswithcode.com/sota/single-image-deraining-on-test1200?p=maxim-multi-axis-mlp-for-image-processing)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/maxim-multi-axis-mlp-for-image-processing/deblurring-on-gopro)](https://paperswithcode.com/sota/deblurring-on-gopro?p=maxim-multi-axis-mlp-for-image-processing)

# MAXIM: Multi-Axis MLP for Image Processing

[Zhengzhong Tu](https://www.linkedin.com/in/vztu/), [Hossein Talebi](https://scholar.google.com/citations?hl=en&user=UOX9BigAAAAJ), [Han Zhang](https://sites.google.com/view/hanzhang), [Feng Yang](https://sites.google.com/view/feng-yang), [Peyman Milanfar](https://sites.google.com/view/milanfarhome/), [Alan Bovik](https://www.ece.utexas.edu/people/faculty/alan-bovik), and [Yinxiao Li](https://scholar.google.com/citations?user=kZsIU74AAAAJ&hl=en)

**Pre-print**: https://arxiv.org/abs/2201.02973

**Code**: coming soon

**results**: all the experimental results will be released soon

<hr />

> **Abstract:** *Recent progress on Transformers and multi-layer perceptron (MLP) models provide new network architectural designs for computer vision tasks. Although these models proved to be effective in many vision tasks such as image recognition, there remain challenges in adapting them for low-level vision. The inflexibility to support high-resolution images and limitations of local attention are perhaps the main bottlenecks for using Transformers and MLPs in image restoration. In this work we present a multi-axis MLP based architecture, called MAXIM, that can serve as an efficient and flexible general-purpose vision backbone for image processing tasks. MAXIM uses a UNet-shaped hierarchical structure and supports long-range interactions enabled by spatially-gated MLPs. Specifically, MAXIM contains two MLP-based building blocks: a multi-axis gated MLP that allows for efficient and scalable spatial mixing of local and global visual cues, and a cross-gating block, an alternative to cross-attention, which accounts for cross-feature mutual conditioning. Both these modules are exclusively based on MLPs, but also benefit from being both global and `fully-convolutional', two properties that are desirable for image processing. Our extensive experimental results show that the proposed MAXIM model achieves state-of-the-art performance on more than ten benchmarks across a range of image processing tasks, including denoising, deblurring, deraining, dehazing, and enhancement while requiring fewer or comparable numbers of parameters and FLOPs than competitive models.* 
<hr />

## Architecture

![image](https://user-images.githubusercontent.com/43280278/149260149-5376b022-98db-45fd-9148-f865a43c8342.png)
![image](https://user-images.githubusercontent.com/43280278/149260185-e7441080-3c04-4338-bf24-4263b1a9193f.png)

## Results

<strong>Image Denoising</strong>

<img src = "https://user-images.githubusercontent.com/43280278/149262178-b0ebc94f-292b-4897-b371-0dc61d5ffd4c.png" width="400">



<strong>Image Deblurring</strong>

<table>
  <tr>
    <td> <img src = "https://user-images.githubusercontent.com/43280278/149261823-b77e9513-b3b5-4caf-a0eb-67bf18c2f681.png" width="500"> </td>
    <td> <img src = "https://user-images.githubusercontent.com/43280278/149261858-24664c33-dc8a-47c3-b84d-ba64b1c05937.png" width="500"> </td>
  </tr>
  <tr>
    <td><p align="center"><b>Synthetic blur</b></p></td>
    <td><p align="center"><b>Realistic blur</b></p></td>
  </tr>
</table>


<strong>Image Deraining</strong>

<table>
  <tr>
    <td> <img src = "https://user-images.githubusercontent.com/43280278/149261908-8bce72cf-b343-4bf8-8462-8be363616cfa.png" width="700"> </td>
    <td> <p align="top"> <img src = "https://user-images.githubusercontent.com/43280278/149262066-7b93538a-2ccc-4ea0-9187-ef1b54734392.png" width="300"> </td>
  </tr>
  <tr>
    <td><p align="center"><b>Rain streak</b></p></td>
    <td><p align="center"><b>Rain drop</b></p></td>
  </tr>
</table>


<strong>Image Dehazing</strong>

<img src = "https://user-images.githubusercontent.com/43280278/149261947-22954827-ce62-44e8-974a-0aa8d94a4bd9.png"  width="300">


<strong>Image Enhancement</strong>

<img src = "https://user-images.githubusercontent.com/43280278/149261416-67b7bab3-d1e6-4f45-84fe-dd08d19c78df.png" width="400">

## Citation

TBD

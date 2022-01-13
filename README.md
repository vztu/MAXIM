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

<img src = "https://user-images.githubusercontent.com/43280278/149260445-02e4b434-d7f9-465c-80f9-f94cec557efb.png">

<strong>Image Deblurring</strong>

<table>
  <tr>
    <td> <img src = "https://user-images.githubusercontent.com/43280278/149260722-ad05726b-4700-4d52-b768-b16306592c9a.png" width="400"> </td>
    <td> <img src = "https://user-images.githubusercontent.com/43280278/149260760-8483ba1d-62a3-432a-abc9-99588777cf6f.png" width="400"> </td>
  </tr>
</table>

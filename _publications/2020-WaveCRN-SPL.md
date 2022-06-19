---
title: "WaveCRN: An Efficient Convolutional Recurrent Neural Network for End-to-end Speech Enhancement"
collection: publications
permalink: /publication/2020-WaveCRN-SPL
excerpt: 'Due to the simple design pipeline, end-to-end (E2E) neural models for speech enhancement (SE) have attracted great interest. In order to improve the performance of the E2E model, the local and sequential properties of speech should be efficiently taken into account when modelling. However, in most current E2E models for SE, these properties are either not fully considered or are too complex to be realized. In this letter, we propose an efficient E2E SE model, termedWaveCRN. Compared with models based on convolutional neural networks (CNN) or long short-term memory (LSTM), WaveCRN uses a CNN module to capture the speech locality features and a stacked simple recurrent units (SRU) module to model the sequential property of the locality features. Different from conventional recurrent neural networks and LSTM, SRU can be efficiently parallelized in calculation, with even fewer model parameters. In order to more effectively suppress noise components in the noisy speech, we derive a novel restricted feature masking approach, which performs enhancement on the feature maps in the hidden layers; this is different from the approaches that apply the estimated ratio mask to the noisy spectral features, which is commonly used in speech separation methods. Experimental results on speech denoising and compressed speech restoration tasks confirm that with the SRU and the restricted feature map, WaveCRN performs comparably to other state-of-the-art approaches with notably reduced model complexity and inference time'
date: 2020-11-27
venue: 'Signal Processing Letters'
paperurl: 'https://ieeexplore.ieee.org/iel7/97/8966529/09272838.pdf'
---
Citation:
```
@article{hsieh2020wavecrn,
  title={Wavecrn: An efficient convolutional recurrent neural network for end-to-end speech enhancement},
  author={Hsieh, Tsun-An and Wang, Hsin-Min and Lu, Xugang and Tsao, Yu},
  journal={IEEE Signal Processing Letters},
  volume={27},
  pages={2149--2153},
  year={2020},
  publisher={IEEE}
}
```

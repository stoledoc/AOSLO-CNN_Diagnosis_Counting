# Deep Convolutional Neural Networks for Diagnosis and Cone Density Estimation from Adaptive Optics Scanning Light Ophthalmoscope Images

![aoslo](https://github.com/stoledoc/Resources/blob/master/aoslo/xor_model.png)

Implementation of the XOR model for AOSLO image analysis:

* Santiago Toledo-Cortés, Adam M. Dubis, Fabio A. González, and Henning Müller

## Abstract

Although many machine learning models have been successfully developed to diagnose eye-related diseases at a macro level, by the time that any diagnosis is known many irreversible alterations have already happened at a microscopic level. Adaptive Optics Scanning Light Ophthalmoscope (AOSLO) images allow microscopic examination of the retina in living patients and have the potential to become an early diagnostic tool for diseases affecting the photoreceptor cell pattern. This paper presents the development and application of machine learning models based on convolutional neural networks for the automatic analysis of split detector AOSLO images. On one side, we present XUR, a deep learning model for cone density estimation that allows end-to-end training, without the need for further image preprocessing and post-processing stages. On the other side, using the information from the density estimator and deep convolutional neural networks, we prove the feasibility of the Stargardt disease and retinitis pigmentosa diagnosis based on the single AOSLO image analysis.  The results reported on different sets of split detector AOSLO images are competitive with the state of the art and show the robustness and practicality of our proposal.

## Requirements

Python requirements:

- Tensorflow >= 2.3

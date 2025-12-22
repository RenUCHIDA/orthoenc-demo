# Speech Enhancement Demo Page

This repository contains audio samples and spectrograms for the paper:
**"Encoder-Masking-Decoder Framework Using Cayley Convolution as Invertible Linear Encoder"**

## 🎧 Demo Website
Click the link below to listen to the audio samples:
**[View the Demo Page](https://RenUCHIDA.github.io/icassp2026-demo/)**

## 📄 Abstract
While the ordinary audio signal processing scheme has relied on predefined time-frequency analysis, recent end-to-end frameworks have adopted trainable 1-D convolutional layers as the encoder for feature extraction of input signals. An input signal is encoded into some learned representation, processed by a deep neural network (DNN), and reconstructed into the time domain by another convolutional layer (i.e., the decoder). However, even when no processing is applied to the encoded signal, a pair of trained encoder and decoder cannot reconstruct the input signal in general; in other words, the encoder-decoder pair does not achieve perfect reconstruction. In this paper, to circumvent the information loss caused by such a non-invertible encoder, we propose to apply an orthogonal convolutional layer to end-to-end DNNs, Conv-TasNet and RE-SepFormer, together with a reshaping technique to make it practical for audio applications. The proposed DNNs were evaluated through a speech enhancement task, and the experimental results showed their invertibility as well as effectiveness in alleviating the difficulty of training when the kernel size of the encoder and decoder is large.

Comparisons between Conv-TasNet and RE-SepFormer using the proposed method.

## 📚 Reference
...

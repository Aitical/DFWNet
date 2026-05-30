# FCRNet

> **Paper**: Dual Frequency Fusion Network for Low-Light Face Super-Resolution
> 
> **Author**: Jican Fu, Gang Wu, Kui jiang, Junjun Jiang, Xianming Liu


## Overview
Low-light face super-resolution aligns illumination in dark inputs and recovers facial details weakened by downsampling. Existing cascaded solutions combine low-light image enhancement and face super-resolution in separate stages, but either order can accumulate errors because the two tasks optimize different spatial properties. This paper presents \method, a compact network that performs complementary Fourier and wavelet analysis for low-light low-resolution face restoration. The Fourier path decouples amplitude and phase to model illumination-related spectral energy and structure-related responses. In parallel, the Haar wavelet path preserves localized low-frequency and high-frequency context for facial detail recovery. Their outputs are fused inside a U-shaped encoder-decoder, and a lightweight frequency convolution further enhances the feed-forward layer. Experiments on CelebAMask-HQ demonstrate competitive fidelity and perceptual performance, with detailed analysis of the key frequency modules.



# Literature Collections of Diffusion

## Training-free Sampling
1. (2024 Apr) [Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models](https://arxiv.org/pdf/2404.02747)
   - Cross-attention outputs converge to a fixed point in the first few steps: Denoising can be devided into 1) semantics-planning stage and 2) fidelity improving stage
   - Cross-Attention is redundant in the fidelity improving stage: fixing cross-attention maps after certain step
2. (2023 Dec) [DeepCache: Accelerating Diffusion Models for Free](https://arxiv.org/pdf/2312.00858)
   - Adjacent steps in the denoising process exhibit significant temporal similarity in high-level features (the feature obtained from upsample block)
   - Cache main feature and update after several steps (originally update at each step)
4. (2023 Dec) [Adaptive Guidance: Training-free Acceleration of Conditional Diffusion Models](https://arxiv.org/pdf/2312.12487)
   - Classifier-free guidance is important in the first several steps
   - Use no classifier-free guidance after a certain step


## Distillization-based Acceleration
1. (2022 Jun) [Progressive Distillation for Fast Sampling of Diffusion Models](https://arxiv.org/pdf/2202.00512)

## 3D Task

## Video Task

## Understand the SNR in Diffusion
1. (2022 Oct) [f-DM: A MULTI-STAGE DIFFUSION MODEL VIA PROGRESSIVE SIGNAL TRANSFORMATION](https://arxiv.org/pdf/2210.04955)
2. (2023 Dec) [simple diffusion: End-to-end diffusion for high resolution images](https://arxiv.org/pdf/2301.11093)
3. (2023 Jan) [On the Importance of Noise Scheduling for Diffusion Models](https://arxiv.org/pdf/2301.10972)
4. (2024 Feb) [Rethinking the Noise Schedule of Diffusion-Based Generative Models](https://openreview.net/pdf?id=ylHLVq0psd)

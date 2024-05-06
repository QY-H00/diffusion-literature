# diffusion-literature
Literature Collections about diffusion

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

## New task settings

## Others

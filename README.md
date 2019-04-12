# GAN_Metrics-Tensorflow
Simple Tensorflow implementation of metrics for GAN evaluation (Inception score, Frechet-Inception score, Kernel-Inception score)

<div align="center">
  <img src="./assets/description.png">
</div>


## Summary
*Name* | *Description* | *Performance score* 
:---: | :---: | :---: |
**Inception score** | KL-Divergence between conditional and marginal label distributions over generated data. | Higher is better.
**Frechet-Inception score** | Wasserstein-2 distance between multi-variate Gaussians fitted to data embedded into a feature space. | Lower is better.
**Kernel-Inception score** | Measures the dissimilarity between two probability distributions `Pr` and `Pg` using samples drawn independently from each distribution. | Lower is better.

## Reference
* [Pros and Cons of GAN Evaluation Measures](https://arxiv.org/pdf/1802.03446.pdf)
* [Inception score](https://github.com/tsc2017/Inception-Score)
* [Frechet-Inception score](https://github.com/tsc2017/Frechet-Inception-Distance)

## Author
Junho Kim

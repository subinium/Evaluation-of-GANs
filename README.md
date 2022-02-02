# Evaluation of GANs

**Based On [Pros and Cons of GAN Evaluation Measures: New Developments](https://arxiv.org/abs/2103.09396) (Ali Borji)**

![assets](/assets/summary.png)

## Quantitative Evaluation Measures

### FID & IS

|Method|Venue|code|
|-|-|-|
|[Inception Score (IS)](https://arxiv.org/abs/1606.03498)|NeurIPS 2016||
|[Fréchet Inception Distance (FID)](https://arxiv.org/abs/1706.08500)|NeurIPS 2017||

### FID & IS Variants

|Method|Venue|code|
|-|-|-|
|[Spatial FID (sFID)](https://arxiv.org/abs/2103.03841)|ICML 2021||
|[Class-aware FID (CAFD)](https://arxiv.org/abs/1803.07474)|arXiv 2018|[code](https://github.com/B1ueber2y/CAFD)|
|[Conditional FID](https://arxiv.org/abs/2103.11521)|arXiv 2021||
|[Fast FID](https://arxiv.org/abs/2009.14075)|arXiv 2021||
|[Memorization-informed FID (MiFID)](https://arxiv.org/abs/2106.03062)|KDD 2021||
|[Unbiased FID and IS](https://arxiv.org/abs/1911.07023)|CVPR 2020||
|[Clean FID](https://arxiv.org/abs/2104.11222)|arXiv 2021|[code](https://github.com/GaParmar/clean-fid)|
|[Frechet Video Distance (FVD)](https://arxiv.org/abs/1812.01717)|arXiv 2018|[code](https://github.com/google-research/google-research/tree/master/frechet_video_distance)|

### Method based on Analysing Data Manifold

|Method|Venue|code|
|-|-|-|
|[Local Intrinsic Dimensionality (LID)](https://arxiv.org/abs/1905.00643)|arXiv 2019||
|[Intrinsic Multi-scale Distance (IMD)](https://arxiv.org/abs/1905.11141)|ICLR 2020||
|[Perceptual Path Length (PPL)](https://arxiv.org/abs/1812.04948)|CVPR 2019|[code](https://github.com/richzhang/PerceptualSimilarity)|
|[Linear Separability in Latent Space](https://arxiv.org/abs/1812.04948)|CVPR 2019|[code](https://github.com/richzhang/PerceptualSimilarity)|

### New Ideas based on Precision and Recall (P&R)

|Method|Venue|code|
|-|-|-|
|[Precision and Recall (P&R)](https://arxiv.org/abs/1806.00035)|NeurIPS 2018||
|[Improved P&R](https://arxiv.org/abs/1904.06991)|NeurIPS 2019|[code](https://github.com/kynkaat/improved-precision-and-recall-metric)|
|[Density and Coverage (D&C)](https://arxiv.org/abs/2002.09797)|ICML 2020|[code](https://github.com/clovaai/generative-evaluation-prdc)|
|[Alpha Precision & Recall](https://arxiv.org/abs/2102.08921)|arXiv 2021||

### Text-Image

|Method|Venue|code|
|-|-|-|
|[Caption Score (CapS)](https://arxiv.org/abs/2105.13290)|NeurIPS 2021|[code](https://github.com/THUDM/CogView)|

### ETC


|Method|Venue|code|
|-|-|-|
|[Classification Accuracy Score (CAS)](https://arxiv.org/abs/1905.10887)|NeurIPS 2019||
|[Duality GAP Metric](https://arxiv.org/abs/1811.05512)|NeurIPS 2019||




## Qualititative Evaluation Measures

|Method|Venue|code|
|-|-|-|
|[Human Eye Perceptual Evaluation (HYPE)](https://arxiv.org/abs/1904.01121)|NeurIPS 2019||
|[Neuroscore](https://arxiv.org/abs/1811.04172)|Cognitive Computation 2020||
|[GAN Steerability & Dissection](https://arxiv.org/abs/1907.07171)|ICLR 2020|[code](https://github.com/ali-design/gan_steerability)|
|[A Universal Fake vs. Real Detector](https://arxiv.org/abs/1912.11035)|CVPR 2020||
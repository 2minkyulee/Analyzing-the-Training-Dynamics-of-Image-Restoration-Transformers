## Rethinking LayerNorm in Image Restoration Transformers
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg)]([https://arxiv.org/abs/1234.56789](https://arxiv.org/pdf/2504.06629))

MinKyu Lee, Sangeek Hyun, Woojin Jun, Hyunjun Kim, Jiwoo Chung, Jae-Pil Heo* \
Sungkyunkwan University \
\*: Corresponding Author


This is the official Repository of: Rethinking LayerNorm in Image Restoration Transformers \
⭐ If you find our work helpful, please consider giving this repository a star. Thanks! 🤗

---

### Abstract
> This work investigates abnormal feature behaviors observed in image restoration (IR) Transformers. Specifically, we identify two critical issues: feature entropy becoming excessively small and feature magnitudes diverging up to a million-fold scale. We pinpoint the root cause to the per-token normalization aspect of conventional LayerNorm, which disrupts essential spatial correlations and internal feature statistics. To address this, we propose a simple normalization strategy tailored for IR Transformers. Our approach applies normalization across the entire spatio-channel dimension, effectively preserving spatial correlations. Additionally, we introduce an input-adaptive rescaling method that aligns feature statistics to the unique statistical requirements of each input. Experimental results verify that this combined strategy effectively resolves feature divergence, significantly enhancing both the stability and performance of IR Transformers across various IR tasks.


## Acknowledgement
This project is built based on [BasicSR](https://github.com/XPixelGroup/BasicSR) and also
[SwinIR](https://github.com/cszn/KAIR/tree/master)
[HAT](https://github.com/XPixelGroup/HAT)
[DRCT](https://github.com/ming053l/drct),


## Contact
Please contact me via 2minkyulee@gmail.com for any inquiries.

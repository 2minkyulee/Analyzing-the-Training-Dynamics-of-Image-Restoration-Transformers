## Analyzing the Training Dynamics of Image Restoration Transformers: <br> A Revisit to Layer Normalization
[![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg)]([https://arxiv.org/abs/1234.56789](https://arxiv.org/pdf/2504.06629))

MinKyu Lee, Sangeek Hyun, Woojin Jun, Hyunjun Kim, Jiwoo Chung, Jae-Pil Heo* \
Sungkyunkwan University \
\*: Corresponding Author


This is the official Repository of: \
Analyzing the Training Dynamics of Image Restoration Transformers: A Revisit to Layer Normalization \
⭐ If you find our work helpful, please consider giving this repository a star. Thanks! 🤗

---

### Abstract
> This work investigates the internal training dynamics of image restoration (IR) Transformers and uncovers a critical yet overlooked issue: conventional LayerNorm leads feature magnitude divergence, up to a million scale, and collapses channel-wise entropy. We analyze this phenomenon from the perspective of networks attempting to bypass constraints imposed by conventional LayerNorm due to conflicts against requirements in IR tasks. Accordingly, we address two misalignments between LayerNorm and IR tasks, and later show that addressing these mismatches leads to both stabilized training dynamics and improved IR performance. Specifically, conventional LayerNorm works in a per-token manner, disrupting spatial correlations between tokens, essential in IR tasks. Also, it employs an input-independent normalization that restricts the flexibility of feature scales, required to preserve input-specific statistics. Together, these mismatches significantly hinder IR Transformer’s ability to accurately preserve low-level features throughout the network. To this end, we introduce Image Restoration Transformer Tailored Layer Normalization (i-LN), a surprisingly simple drop-in replacement for conventional LayerNorm. We propose to normalize features in a holistic manner across the entire spatio-channel dimension, preserving spatial relationships among individual tokens. Additionally, we introduce an input-adaptive rescaling strategy that maintains the feature range flexibility required by individual inputs. Together, these modifications effectively contribute to preserving low-level feature statistics of inputs throughout IR Transformers. Experimental results verify that this combined strategy enhances both the stability and performance of IR Transformers across various IR tasks.


## Acknowledgement
This project is built based on [BasicSR](https://github.com/XPixelGroup/BasicSR) and also
[SwinIR](https://github.com/cszn/KAIR/tree/master)
[HAT](https://github.com/XPixelGroup/HAT)
[DRCT](https://github.com/ming053l/drct),


## Contact
Please contact me via 2minkyulee@gmail.com for any inquiries.

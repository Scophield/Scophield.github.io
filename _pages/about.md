---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am at the **Graduate School of Information, Production and Systems, Waseda University**.
My research focuses on emerging-memory-based neural network accelerators,
hardware-conscious training, and energy-efficient neuromorphic computing.

My published work spans hardware-conscious training for analog DNN inference
accelerators, STT-MTJ device modeling, and the structural evolution of spiking neural networks.

I am particularly interested in:
- Analog / mixed-signal computing-in-memory (CIM)
- Hardware-software co-design for AI accelerators
- High energy-efficiency architectures for edge intelligence

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div class="publication-figure"><div class="badge">JJAP 2024</div><a href="images/publications/jjap2024-related-architecture.png" target="_blank" rel="noopener" aria-label="View full-size JJAP 2024 representative figure"><img src='images/publications/jjap2024-related-architecture.png' alt="Double-crossbar DNN synapse array and neuron circuits from SSDM 2023 Figure 1" width="100%" loading="lazy"></a><p class="figure-credit">Related architecture: Gao &amp; Ohsawa, <a href="https://arxiv.org/abs/2609.04259">SSDM 2023, Fig. 1</a> (author manuscript).</p></div></div>
<div class='paper-box-text' markdown="1">

[A training method for deep neural network
inference accelerators with high tolerance for their
hardware imperfection](https://doi.org/10.35848/1347-4065/ad1895)

**Shuchao Gao**, Takashi Ohsawa

[**Paper**](https://doi.org/10.35848/1347-4065/ad1895) · [**Project**](https://github.com/Scophield/HCST)
- We have proposed an algorithm (software) method to address the offset voltage issue of operational amplifier in DNN inference accelerators in advanced process.  This method is verified in a larger dataset.
- **Fully Analog ReRAM Inference Accelerator:** An open-source framework for exploring fully analog ReRAM inference accelerators that avoid repeated inter-layer ADC/DAC conversions. It models ReRAM synapse arrays and analog neuron circuits for current-to-voltage conversion, subtraction, activation, and inter-layer driving. Finite-gain and offset models, together with hardware-conscious training tools, support studies of how circuit nonidealities affect inference accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="publication-figure"><div class="badge">SSDM 2023</div><a href="images/publications/ssdm2023-hcst-training.png" target="_blank" rel="noopener" aria-label="View full-size SSDM 2023 representative figure"><img src='images/publications/ssdm2023-hcst-training.png' alt="Hardware-conscious software training with hardware emulator, backpropagation and hardware inference" width="100%" loading="lazy"></a><p class="figure-credit">Gao &amp; Ohsawa, <a href="https://arxiv.org/abs/2609.04259">SSDM 2023, Fig. 5</a> (author manuscript).</p></div></div>
<div class='paper-box-text' markdown="1">

[Hardware-conscious Software Training for Deep Neural Network Inference Accelerator Chips to Recover Accuracy Degradation due to Hardware Variabilities](https://doi.org/10.7567/SSDM.2023.J-5-03)

**Shuchao Gao**, Takashi Ohsawa

[**Paper**](https://doi.org/10.7567/SSDM.2023.J-5-03) · [**Open manuscript**](https://arxiv.org/abs/2609.04259)

*Presented at SSDM 2023; the manuscript was deposited on arXiv in September 2026.*
- We have proposed an algorithm (software) method to address the offset voltage issue of operational amplifier in DNN inference accelerators in advanced process. This method is verified in IRIS dataset.
</div>
</div>

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

Hardware-conscious Training for Deep Neural Network Inference Accelerators to Restore Accuracy Degradation due to Hardware Imperfection

*ISIPS 2023*

**Shuchao Gao**, Takashi Ohsawa

- We have designed a hardware training algorithm that can significantly improve the accuracy of DNN inference accelerators, even under the effect of the hardware imperfection introduced during the fabrication process. We compared offline training, in-situ training and on-chip training, and proved that hardware-conscious training is the best choice, which makes the non-volatile memory devices free from the endurance constraint, the nonlinearity and the asymmetry issues in updating the resistances.
</div>
</div>

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

Single Crossbar Array Architecture for High Density and Low Power Artificial Neural Network

*ISIPS 2019*

**Shuchao Gao**, Takashi Ohsawa

- We compared three different crossbar array structures to realize negative weight and introduced their training method. We used the Iris dataset to test and train the CBA. We also mathematically derive a single CBA training algorithm. It’s proved that single CBA can be more easily implemented in ReRAM CBA with lower error rate and more stability.
</div>
</div>

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

Training ReRAM Crossbar Array in Deep Neural Network

*IEICE 2019*

**Shuchao Gao**, Takashi Ohsawa

- We proposed a DNN training method to train ReRAM Crossbar Array (CBA). We designed and evaluated the Double Crossbar Array and Single Crossbar Array used to achieve negative weights, which also can perform complex matric multiplication at once only by the basic Ohm's law and Kirchhoff’s Law.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="publication-figure"><div class="badge">MEJ 2026</div><a href="images/publications/mej2026-preprint-transmitter.png" target="_blank" rel="noopener" aria-label="View full-size MEJ 2026 representative figure"><img src='images/publications/mej2026-preprint-transmitter.png' alt="PAM-3 transmitter architecture with feedforward equalization, transition booster and crosstalk cancellation" width="100%" loading="lazy"></a><p class="figure-credit">Zhang &amp; Liu, <a href="https://www.preprints.org/manuscript/202604.0364">associated preprint, Fig. 2</a>, <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>. Original preprint figure.</p></div></div>
<div class='paper-box-text' markdown="1">

[A 72-Gb/s/pin PAM-3 transmitter with asymmetric reconfigurable feedforward equalizer and edge-shaping crosstalk cancellation](https://doi.org/10.1016/j.mejo.2026.107361)

Wenxuan Zhang, Yiming Liu, **Shuchao Gao**

*Microelectronics Journal*, 176, 107361 (October 2026)

[**Paper**](https://doi.org/10.1016/j.mejo.2026.107361)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="publication-figure"><div class="badge">NPL 2026</div><a href="images/publications/npl2026-four-stages.png" target="_blank" rel="noopener" aria-label="View full-size NPL 2026 representative figure"><img src='images/publications/npl2026-four-stages.png' alt="Four-stage evolution from baseline ANN through binarization, temporal expansion and accumulation to reset and sparsity control" width="100%" loading="lazy"></a><p class="figure-credit">He &amp; Gao, <a href="https://link.springer.com/article/10.1007/s11063-025-11832-z/figures/2">NPL 2026, Fig. 2</a>, <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a>. Unmodified original.</p></div></div>
<div class='paper-box-text' markdown="1">

[A Four-Stage Structural Evolution Framework for Spiking Neural Networks: A Review and Perspective from Binary ANN to Event-Driven Models](https://link.springer.com/article/10.1007/s11063-025-11832-z)

Huaxu He, **Shuchao Gao**

*Neural Processing Letters*, 58, 14 (2026)

[**Paper**](https://doi.org/10.1007/s11063-025-11832-z) · [**Code**](https://github.com/Scophield/snn-structural-evolution)
- A four-stage framework connects binary ANNs to event-driven SNNs through temporal expansion, accumulation, reset, and sparsity control.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="publication-figure"><div class="badge">TED 2025</div><a href="images/publications/ted2025-mtj-applications.png" target="_blank" rel="noopener" aria-label="View full-size TED 2025 representative figure"><img src='images/publications/ted2025-mtj-applications.png' alt="Magnetic tunnel junction states and applications in DNN, computing in memory, MRAM, SNN, random number generation and stochastic computing" width="100%" loading="lazy"></a></div></div>
<div class='paper-box-text' markdown="1">

[A High-Accuracy STT-MTJ SPICE Model Based on Variable Parameters](https://doi.org/10.1109/TED.2025.3566043)

Haoyan Liu, **Shuchao Gao**, Chunshuang Chu, Kangkai Tian, Fuping Huang, Yonghui Zhang, and Zi-Hui Zhang

*IEEE Transactions on Electron Devices*, 72(7), 3543–3549 (2025)

- A variable-parameter SPICE model for accurate STT-MTJ device simulation.
</div>
</div>

# 🎖 Honors and Awards
- **2018.10 – 2019.03** MEXT Monbukagakusho Honors Scholarship (Japan)
- **2020.09 – 2021.03** MEXT Monbukagakusho Honors Scholarship (Japan)
- **2021.01** Young Researcher Scholarship (Waseda University)
- **2021.09 – 2023.09** China Scholarship Council (CSC) Ph.D. Scholarship

# 📖 Educations
- **M.Eng.**, Emerging Memory Systems Laboratory, Waseda University
- **B.Eng.**, University of Electronic Science and Technology of China

# 💻 Internships
- *DATATOM*, Distributed Cloud Storage System Development

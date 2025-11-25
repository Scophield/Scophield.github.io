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

I am a Ph.D. candidate at Waseda University, focusing on **fully analog emerging memory based DNN inference accelerators**, 
hardware-aware training, and low-power edge AI systems.

My recent work includes:
- A fully analog ReRAM-based DNN inference accelerator with self-compensation for hardware imperfections.
- Switched-capacitor based offset cancellation for analog MAC arrays.
- Binaried llm and BNN accelerators based on mature 6T-SRAM.
- Yield enhancement techniques for MRAM arrays using clamped bitline sense amplifiers (CBLSA).
- Fully analog implemention for spiking transformer.

I am particularly interested in:
- Analog / mixed-signal computing-in-memory (CIM)
- Hardware-software co-design for AI accelerators
- High energy-efficiency architectures for edge intelligence
<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->
<!--
Multi-bit MRAM-based AI accelerators.
Winner-Takes-All (WTA) circuits, level shifters, and high-speed comparators for analog AI front-ends.
-->

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JJAP 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A training method for deep neural network
inference accelerators with high tolerance for their
hardware imperfection](https://iopscience.iop.org/article/10.35848/1347-4065/ad1895/pdf)

**Shuchao Gao**, Takashi Ohsawa

[**Project**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We have proposed an algorithm (software) method to address the offset voltage issue of operational amplifier in DNN inference accelerators in advanced process.  This method is verified in a larger dataset.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SSDM 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hardware-conscious Software Training for Deep Neural Network Inference Accelerator Chips to Recover Accuracy Degradation due to Hardware Variabilities](https://confit.atlas.jp/guide/event-img/ssdm2023/J-5-03/public/pdf_archive?type=in)

**Shuchao Gao**, Takashi Ohsawa

[**Project**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We have proposed an algorithm (software) method to address the offset voltage issue of operational amplifier in DNN inference accelerators in advanced process. This method is verified in IRIS dataset. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISIPS 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Hardware-conscious Training for Deep Neural Network Inference Accelerators to Restore Accuracy Degradation due to Hardware Imperfection

**Shuchao Gao**, Takashi Ohsawa

- We have designed a hardware training algorithm that can significantly improve the accuracy of DNN inference accelerators, even under the effect of the hardware imperfection introduced during the fabrication process. We compared offline training, in-situ training and on-chip training, and proved that hardware-conscious training is the best choice, which makes the non-volatile memory devices free from the endurance constraint, the nonlinearity and the asymmetry issues in updating the resistances.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISIPS 2019</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Single Crossbar Array Architecture for High Density and Low Power Artificial Neural Network

**Shuchao Gao**, Takashi Ohsawa

- We compared three different crossbar array structures to realize negative weight and introduced their training method. We used the Iris dataset to test and train the CBA. We also mathematically derive a single CBA training algorithm. It’s proved that single CBA can be more easily implemented in ReRAM CBA with lower error rate and more stability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEICE 2019</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Training ReRAM Crossbar Array in Deep Neural Network

**Shuchao Gao**, Takashi Ohsawa

- We proposed a DNN training method to train ReRAM Crossbar Array (CBA). We designed and evaluated the Double Crossbar Array and Single Crossbar Array used to achieve negative weights, which also can perform complex matric multiplication at once only by the basic Ohm's law and Kirchhoff’s Law. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TED 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A High-Accuracy STT-MTJ SPICE Model Based on Variable Parameters](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11003814)

Haoyan Liu, **Shuchao Gao**, Chunshuang Chu, Kangkai Tian, Fuping Huang, Yonghui Zhang, and Zi-Hui Zhang

- We have proposed a universal, accurate and simulation-efficient STTMTJ model. 
</div>
</div>

# 🎖 Honors and Awards
- **2018.10 – 2019.03** MEXT Monbukagakusho Honors Scholarship (Japan)
- **2020.09 – 2021.03** MEXT Monbukagakusho Honors Scholarship (Japan)
- **2021.01** Young Researcher Scholarship (Waseda University)
- **2021.09 – 2023.09** China Scholarship Council (CSC) Ph.D. Scholarship


# 📖 Educations
- **Ph.D. Candidate**, Emerging Memory Systems Laboratory, Waseda University
- **M.Eng.**, Emerging Memory Systems Laboratory, Waseda University
- **B.Eng.**, University of Electronic Science and Technology of China

// # 💬 Invited Talks
// - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
// - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *DATATOM*, Distributed Cloud Storage System Development

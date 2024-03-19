---
permalink: /
title: ""
# excerpt: ""
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

I'm a Ph.D candidate for Electrical Science and Technology at the Department of Micro/Nano Electronics (微纳电子学系), Shanghai Jiao Tong University, Shanghai, China, and under the supervision of Professor [Guanghui He](https://dmne.sjtu.edu.cn/dmne/faculty/heguanghui/). 

My current research interests focus on **Efficient ASIC Architecture Design for Emerging Applications**. 
- **Efficient Hardware Accelerators for AI Computing**
- - Multi-sensor Perception Acceleration for Autonomous Driving Systems
- - - Preprocessing: *feature learning network* (DAC'23, TVLSI'24)
- - - Backbone: *3D sparse convolution* (ICCAD'23)
- - - Multi-modality Fusion: *BEV perception* (DAC'24 and new one to be submitted to TCAS-I)
- - - Postprocessing: *Non-maximum Suppression* (ISCAS'23)
- - Data Compression Techniques for High-bandwidth Requirement from Future Neural Networks (TCAS-II'24)
- **Emerging Stochastic Computing Techniques for AI Computing**
- - Efficient Sequence Generator and MAC Implementation (NANOARCH'22, TNANO'24)
- **Efficient Massive MIMO Detectors for 5G/6G Communication**
- - 8x8 High-thoughput Soft-output MIMO detector (TVLSI'21)


The current focus is efficient ASIC design for AI applications like BEV perception, point cloud processing and massive MIMO wireless detector, and emerging computing paradigm design like stochastic computing (<a href='https://scholar.google.com/citations?user=K1JGQBIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.03*: &nbsp;🎉🎉 The preprint version of our DAC'24 paper *DEFA: Deformable Attention Accelerator* is available on [ArXiv](https://arxiv.org/pdf/2403.10913.pdf). Welcome to discuss with us !!
- *2024.02*: &nbsp;🎉🎉 Our TNANO'24 paper can be early accessed on the [IEEE Xplorer](https://ieeexplore.ieee.org/document/10443589).
- *2024.02*: &nbsp;🎉🎉 One co-authored paper about *Deformable Attention Acceleration* is accepted by DAC'24 !!! Congratulations to Yansong !!! See you in San Francisco !!!
- *2024.02*: &nbsp;🎉🎉 Our TCAS-II'24 paper can be early accessed on the [IEEE Xplorer](https://ieeexplore.ieee.org/document/10433078).
- *2024.02*: &nbsp;🎉🎉 One co-authored paper about *NN data compression engine* is accepted by IEEE TCAS-II. Congratulations to Yuzhou !!!
- *2024.01*: &nbsp;🎉🎉 Our TVLSI'24 paper can be early accessed on the [IEEE Xplorer](https://ieeexplore.ieee.org/document/10416684). 
- *2024.01*: &nbsp;🎉🎉 The extended paper of our DAC'23 is accepted by IEEE TVLSI !!!. 
- *2023.11*: &nbsp;🎉🎉 One co-authored paper about *SC-based MAC Design* is accepted by IEEE TNANO. Congratulations to Aokun !!!
- *2023.07*: &nbsp;🎉🎉 One paper about *3D Sparse Convolution Accelerator* is accepted by ICCAD 2023. See you in San Francisco, US! 
- *2023.02*: &nbsp;🎉🎉 One paper about *Feature Learning Network Acceleration of Point Clouds* is accepted by DAC 2023. See you in San Francisco, US!

# 📝 Publications 

$^{\star}$: me as the project manager; $^{\dagger}$: equal contribution.

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVLSI 2024</div><img src='images/TVLSI24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling]()

**Dongxu Lyu**$^{\dagger}$, Zhenyu Li$^{\dagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He

- The **first** grid-based feature learning network accelerator with algorithm-architecture co-optimization for large-scale point clouds. 
- It demonstrates substantial performance boost over the state-of-the-art point cloud accelerators while providing superior support of large-scale point clouds ($>10^6$ points in $\sim$2ms).
- **An extension of our DAC'24 paper**.
- *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DAC 2023</div><img src='images/DAC23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674)

**Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Ningyi Xu and Guanghui He 
- The first grid-based feature learning network accelerator with algorithm-architecture co-optimization. 
- It achieves 13.4−43.3× speedup over RTX 2080Ti GPU on representative FLN benchmarks.
- *2023 60th ACM/IEEE Design Automation Conference (DAC)*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2023</div><img src='images/ICCAD23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728)

**Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Jinming Zhang, Ningyi Xu and Guanghui He 
- A novel 3D sparse convolution accelerator that enables high-speed and energy-efficient point cloud processing. 
- SpOctA rivals the state-of-the-art SpConv accelerators by 1.1-6.9x speedup with 1.5-3.1x energy efficiency improvement on their benchmarks.
- *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*
</div>
</div>

## Full Pub List


### Efficient Hardware Accelerators for AI Computing (Jan. 2022 -- Present)
- ``DAC 2024`` [DEFA: Efficient Deformable Attention Acceleration via Pruning-Assisted Grid-Sampling and Multi-Scale Parallel Processing](https://arxiv.org/pdf/2403.10913.pdf), Yansong Xu, **Dongxu Lyu**$^{\star}$, Zhenyu Li, Yuzhou Chen, Zilong Wang, Gang Wang, Zhican Wang, Haomin Li and Guanghui He, *2024 61th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2024.
- ``TCAS-II 2024`` [A Broad-Spectrum and High-Throughput Compression Engine for Neural Network Processors](https://ieeexplore.ieee.org/document/10433078), Yuzhou Chen, Jinming Zhang, **Dongxu Lyu**$^{\star}$, Zhenyu Li and Guanghui He, in *IEEE Transactions on Circuits and Systems II: Express Briefs*.
- ``TVLSI 2024`` [FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling](https://ieeexplore.ieee.org/document/10416684), **Dongxu Lyu**$^{\dagger}$, Zhenyu Li$^{\dagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*.
- ``ICCAD 2023`` [SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728), **Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Jinming Zhang, Ningyi Xu and Guanghui He, *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*, San Francisco, CA, USA, 2023, pp. 1-9.
- ``DAC 2023`` [FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674), **Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Ningyi Xu and Guanghui He, *2023 60th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2023, pp. 1-6.
- ``ISCAS 2023`` [O$^3$NMS: An Out-Of-Order-Based Low-Latency Accelerator for Non-Maximum Suppression](https://ieeexplore.ieee.org/abstract/document/10181731), Yuzhou Chen, Jinming Zhang, **Dongxu Lyu**$^{\star}$, Xi Yu and Guanghui He, *2023 IEEE International Symposium on Circuits and Systems (ISCAS)*, Monterey, CA, USA, 2023, pp. 1-5.

### Emerging Stochastic Computing Techniques for AI Computing (Sep. 2021 -- Present)
- ``TNANO 2024`` [Efficient Parallel Stochastic Computing Multiply-Accumulate (MAC) Technique Using Pseudo-Sobol Bit-Streams](https://ieeexplore.ieee.org/document/10443589), Aokun Hu, Wenjie Li, **Dongxu Lyu** and Guanghui He, in *IEEE Transactions on Nanotechnology*.
- ``NANOARCH 2022`` [An Efficient Stochastic Convolution Accelerator based on Pseudo-Sobol Sequences](https://dl.acm.org/doi/abs/10.1145/3565478.3572543), Aokun Hu, Wenjie Li, **Dongxu Lyu** and Guanghui He, *the 17th ACM International Symposium on Nanoscale Architectures (NANOARCH)*, pp. 1-6. 2022.

### Efficient Massive MIMO Detectors for 5G/6G Communication (Sep. 2019 -- Sep. 2021)
- ``TVLSI 2021`` [A 3.85-Gb/s 8 × 8 Soft-Output MIMO Detector With Lattice-Reduction-Aided Channel Preprocessing](https://ieeexplore.ieee.org/abstract/document/9266114), Zhuojun Liang, **Dongxu Lyu**, Chao Cui, Hai-Bao Chen, Weifeng He, Weiguang Sheng, Naifeng Jing, Zhigang Mao and Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*, vol. 29, no. 2, pp. 307-320, Feb. 2021.


# 🎖 Honors and Awards
- *2021.11* **1st Prize on China Postgraduate IC Innovation Competition (中国研究生创芯大赛)** from Association of Chinese Graduate Education. 
- *2020.06* **Shanghai Outstanding Graduate** from Shanghai City.
- *2020.06* **Departmental Excellent Undergraduate Thesis (Department of Micro/Nano Electronics)** from Shanghai Jiao Tong University.
- *2019.09* **Guanghua Scholarship** from Shanghai Jiao Tong University.

# 📖 Educations
- *2020.09 - 2025.06 (expected)*, Ph.D. student in Electronic Science and Technology  (*Department of Micro/Nano Electronics*), Shanghai Jiao Tong University, Shanghai, China.
- *2016.09 - 2020.06*, B.E. in Microelectronics Science and Engineering (*Department of Micro/Nano Electronics*), Shanghai Jiao Tong University, Shanghai, China. 

# 💬 Invited Talks
- *2023.07*, **"FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling"** in DAC'23, Moscone Center West, San Francisco, CA, USA. 
- *2023.07*, **"SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing"** in ICCAD'23, Hyatt Soma Downtown, San Francisco, CA, USA.

# 💻 Internships
- *2022.03 - now*, **Hardware & Toolchain Intern** in [Huixi Technology (辉羲智能)](https://www.rhino.auto/), Shanghai, China.
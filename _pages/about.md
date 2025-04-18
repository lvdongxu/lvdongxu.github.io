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

My current research interests focus on **Efficient ASIC Architecture Design for Emerging Applications**  (<a href='https://scholar.google.com/citations?user=K1JGQBIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). 
- **Efficient Hardware Accelerators for AI Computing**
  - Multi-sensor Perception Acceleration for Autonomous Driving Systems
    - Preprocessing: *feature learning network* [DAC'23, TVLSI'24]
    - Backbone: *3D sparse convolution* [ICCAD'23]
    - Multi-modality Fusion: *vision-centric 3D perception* [DAC'24 and TCAS-I'25]
    - Postprocessing: *Non-maximum Suppression* [ISCAS'23]
  - Data Compression Techniques for High-bandwidth Requirement from Future Neural Networks [TCAS-II'24]
  - Hardware/Software Co-Design for Vision/Language Transformer Model [TCAS-I'24, SCIS'24, TCAS-I'25, DAC'25 x2, JETCAS'25 x2]
  - Neural Rendering Acceleration [TCAD'24]
  - Near Memory Processing for Various Applications [HPCA'24, TCAD'25, DAC'25]
- **Emerging Stochastic Computing Techniques for AI Computing**
  - Efficient Sequence Generator and MAC Implementation [NANOARCH'22, TNANO'24]
- **Efficient Massive MIMO Detectors for 5G/6G Communication**
  - 8x8 High-thoughput Soft-output MIMO detector [TVLSI'21]


<!-- The current focus is efficient ASIC design for AI applications like BEV perception, point cloud processing and massive MIMO wireless detector, and emerging computing paradigm design like stochastic computing (<a href='https://scholar.google.com/citations?user=K1JGQBIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.04*: &nbsp;🎉🎉 One co-authored paper about *LLM Quantization* is accepted by JETCAS. Congratulations to Siqi!!!
- *2025.03*: &nbsp;🎉🎉 One first-authored paper about *Acceleration for Vision-Centric 3D Perception* is accepted by TCAS-I !!!
- *2025.03*: &nbsp;🎉🎉 One co-authored paper about *Hyper-Dimentional Computing* is accepted by ISCA. Congratulations to Haomin Li!!!
- *2025.03*: &nbsp;🎉🎉 One co-authored paper about *Non-linear Function Acceleration in LLM* is accepted by JETCAS. Congratulations to Wenjie Li!!!
- *2025.03*: &nbsp;🎉🎉 One co-authored paper about *LLM Quantization* is accepted by TCAS-I. Congratulations to Gang Wang!!!
- *2025.02*: &nbsp;🎉🎉 Two co-first-authored paper about *DSA's Efficiency Optimization on KV Cache in LLMs* and *Near Memory Processing for Generative LLM inference* are accepted by DAC. One co-authored paper about *Bit-serial Neural Network Acceleration* is also accepted by DAC. Congratulations to Zhenyu Li, Liyan Chen and Gang Wang!!!
- *2025.01*: &nbsp;🎉🎉 One co-authored paper about *Near Memory Processing* is accepted by TCAD. Congratulations to Liyan Chen!!!


# 📝 Publications 

$^{\star}$: project manager; $^{\dagger}$: equal contribution.

<!-- ## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVLSI 2024</div><img src='images/TVLSI24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling]()

**Dongxu Lyu**$^{\dagger}$, Zhenyu Li$^{\dagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He

- The **first** grid-based feature learning network accelerator with algorithm-architecture co-optimization for large-scale point clouds. 
- It demonstrates substantial performance boost over the state-of-the-art point cloud accelerators while providing superior support of large-scale point clouds ($>10^6$ points in $\sim$2ms).
- **An extension of our DAC'23 paper**.
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
</div> -->

## Full Pub List


### Efficient Hardware Accelerators for AI Computing (Jan. 2022 -- Present)
- ``JETCAS 2025`` [Adaptive Two-Range Quantization and Hardware Co-Design for Large Language Model Acceleration](), Siqi Cai, Gang Wang, Wenjie Li, **Dongxu Lyu** and Guanghui He, in *IEEE Journal on Emerging and Selected Topics in Circuits and Systems, Special Issue: "Generative AI Compute: Algorithms, Architectures, and Applications to CAS"*.
- ``TCAS-I 2025`` [An Efficient Multi-View Cross-Attention Accelerator for Vision-Centric 3D Perception in Autonomous Driving](), **Dongxu Lyu**$^{\star}$, Zhenyu Li, Yansong Xu, Gang Wang, Wenjie Li, Yuzhou Chen, Liyan Chen, Weifeng He and Guanghui He, in *IEEE Transactions on Circuits and Systems I: Regular Papers*.
- ``JETCAS 2025`` [Efficient Hardware Architecture Design for Rotary Position Embedding of Large Language Models](), Wenjie Li, Gang Wang, **Dongxu Lyu**, Ningyi Xu and Guanghui He, in *IEEE Journal on Emerging and Selected Topics in Circuits and Systems, Special Issue: "Generative AI Compute: Algorithms, Architectures, and Applications to CAS"*.
- ``TCAS-I 2025`` [OFQ-LLM: Outlier-Flexing Quantization for Efficient Low-Bit Large Language Model Acceleration](https://ieeexplore.ieee.org/document/10924797), Gang Wang, Siqi Cai, Wenjie Li, **Dongxu Lyu** and Guanghui He, in *IEEE Transactions on Circuits and Systems I: Regular Papers*.
- ``DAC 2025`` [KVO-LLM: Boosting Long-Context Generation Throughput for Batched LLM Inference](), Zhenyu Li$^{\dagger}$, **Dongxu Lyu**$^{\star \dagger}$, Gang Wang, Yuzhou Chen, Liyan Chen, Wenjie Li, Jianfei Jiang, Yanan Sun and Guanghui He
, *2025 62th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2025.
- ``DAC 2025`` [BitPattern: Enabling Efficient Bit-Serial Acceleration of Deep Neural Networks through Bit-Pattern Pruning](), Gang Wang, Siqi Cai, Zhenyu Li, Wenjie Li, Dongxu Lyu, Yanan Sun, Jianfei Jiang and Guanghui He, *2025 62th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2025.
- ``TCAD 2024`` [Neural Rendering Acceleration with Deferred Neural Decoding and Voxel-Centric Data Flow](https://ieeexplore.ieee.org/abstract/document/10819500), Yuzhou Chen, Zhenyu Li, **Dongxu Lyu**$^{\star}$, Yansong Xu and Guanghui He, in *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*.
- ``TVLSI 2024`` [M2M: A Fine-Grained Mapping Framework to Accelerate Multiple DNNs on a Multi-Chiplet Architecture](https://ieeexplore.ieee.org/abstract/document/10634307) Jinming Zhang, Xuyan Wang, Yaoyao Ye, **Dongxu Lyu**, Guojie Xiong, Ningyi Xu, Yong Lian and Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*.
- ``SCIS 2024`` [Hardware-Oriented Algorithms for Softmax and Layer Normalization of Large Language Models](http://scis.scichina.com/en/2024/200404.pdf) Wenjie Li, **Dongxu Lyu**, Gang Wang, Aokun Hu, Ningyi Xu and Guanghui He, in *Science China Information Sciences*.
- ``TCAS-I 2024`` [BSViT: A Bit-Serial Vision Transformer Accelerator Exploiting Dynamic Patch and Weight Bit-Group Quantization](https://ieeexplore.ieee.org/abstract/document/10601322), Gang Wang, Siqi Cai, Wenjie Li, **Dongxu Lyu** and Guanghui He, in *IEEE Transactions on Circuits and Systems I: Regular Papers*.
- ``DAC 2024`` [DEFA: Efficient Deformable Attention Acceleration via Pruning-Assisted Grid-Sampling and Multi-Scale Parallel Processing](https://arxiv.org/pdf/2403.10913.pdf), Yansong Xu, **Dongxu Lyu**$^{\star}$, Zhenyu Li, Yuzhou Chen, Zilong Wang, Gang Wang, Zhican Wang, Haomin Li and Guanghui He, *2024 61th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2024.
- ``TCAS-II 2024`` [A Broad-Spectrum and High-Throughput Compression Engine for Neural Network Processors](https://ieeexplore.ieee.org/document/10433078), Yuzhou Chen, Jinming Zhang, **Dongxu Lyu**$^{\star}$, Zhenyu Li and Guanghui He, in *IEEE Transactions on Circuits and Systems II: Express Briefs*.
- ``TVLSI 2024`` [FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling](https://ieeexplore.ieee.org/document/10416684), **Dongxu Lyu**$^{\dagger}$, Zhenyu Li$^{\dagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*.
- ``ICCAD 2023`` [SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728), **Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Jinming Zhang, Ningyi Xu and Guanghui He, *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*, San Francisco, CA, USA, 2023, pp. 1-9.
- ``DAC 2023`` [FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674), **Dongxu Lyu**, Zhenyu Li, Yuzhou Chen, Ningyi Xu and Guanghui He, *2023 60th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2023, pp. 1-6.
- ``ISCAS 2023`` [O$^3$NMS: An Out-Of-Order-Based Low-Latency Accelerator for Non-Maximum Suppression](https://ieeexplore.ieee.org/abstract/document/10181731), Yuzhou Chen, Jinming Zhang, **Dongxu Lyu**$^{\star}$, Xi Yu and Guanghui He, *2023 IEEE International Symposium on Circuits and Systems (ISCAS)*, Monterey, CA, USA, 2023, pp. 1-5.

### Efficient System-level Design (Apr. 2024 -- Present)
- ``DAC 2025`` [AttenPIM: Accelerating LLM Attention with Dual-mode GEMV in Processing-in-Memory](), Liyan Chen$^{\dagger}$, **Dongxu Lyu**$^{\dagger}$, Zhenyu Li, Jianfei Jiang, Qin Wang, Zhigang Mao and Naifeng Jing, *2025 62th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2025.
- ``HPCA 2025`` [AsyncDIMM: Achieving Asynchronous Execution in DIMM-Based Near-Memory Processing](), Liyan Chen$^{\star}$, **Dongxu Lyu**$^{\star}$, Jianfei Jiang, Qin Wang, Zhigang Mao, Naifeng Jing, in *2025 International Symposium on Computer Architecture (HPCA)*.
- ``TCAD 2025`` [Bridge-NDP: Efficient Communication-Computation Overlap in Near Data Processing System](), Liyan Chen, Pengyu Liu, **Dongxu Lyu**, Jianfei Jiang, Qin Wang, Zhigang Mao, Naifeng Jing, in *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*

### Efficient AI Computing
- ``ISCA 2025`` [FATE: Boosting the Performance of Hyper-Dimensional Computing Intelligence with Flexible Numerical DAta TypE](), Haomin Li, Fangxin Liu, Yichi Chen, Zongwu Wang, Shiyuan Huang, Ning Yang, **Dongxu Lyu** and Li Jiang, in *52nd Annual International Symposiumon Computer Architecture 2025 (ISCA'25)*.
- ``DATE 2025`` [TAIL: Exploiting Temporal Asynchronous Execution for Efficient Spiking Neural Networks with Inter-Layer Parallelism](), Haomin Li, Fangxin Liu, Zongwu Wang, **Dongxu Lyu**, Shiyuan Huang, Ning Yang, Qi Sun, Zhuoran Song and Li Jiang, in *Design, Automation & Test in Europe Conference 2025*.
- ``DATE 2025`` [HyperDyn: Dynamic Dimensional Masking forEffcient Hyper-Dimensional Computing](), Fangxin Liu, Haomin Li, Zongwu Wang, **Dongxu Lyu** and Li Jiang, in *Design, Automation & Test in Europe Conference 2025*.

### Emerging Stochastic Computing Techniques for AI Computing (Sep. 2021 -- Present)
- ``TNANO 2024`` [Efficient Parallel Stochastic Computing Multiply-Accumulate (MAC) Technique Using Pseudo-Sobol Bit-Streams](https://ieeexplore.ieee.org/document/10443589), Aokun Hu, Wenjie Li, **Dongxu Lyu** and Guanghui He, in *IEEE Transactions on Nanotechnology*.
- ``NANOARCH 2022`` [An Efficient Stochastic Convolution Accelerator based on Pseudo-Sobol Sequences](https://dl.acm.org/doi/abs/10.1145/3565478.3572543), Aokun Hu, Wenjie Li, **Dongxu Lyu** and Guanghui He, *the 17th ACM International Symposium on Nanoscale Architectures (NANOARCH)*, pp. 1-6. 2022.

### Efficient Massive MIMO Detectors for 5G/6G Communication (Sep. 2019 -- Sep. 2021)
- ``TVLSI 2021`` [A 3.85-Gb/s 8 × 8 Soft-Output MIMO Detector With Lattice-Reduction-Aided Channel Preprocessing](https://ieeexplore.ieee.org/abstract/document/9266114), Zhuojun Liang, **Dongxu Lyu**, Chao Cui, Hai-Bao Chen, Weifeng He, Weiguang Sheng, Naifeng Jing, Zhigang Mao and Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*, vol. 29, no. 2, pp. 307-320, Feb. 2021.


# 🎖 Honors and Awards
- *2024.09* **National Scholarship for Doctoral Students** (Top 0.1%) in SEIEE, Shanghai Jiao Tong University.
- *2021.11* **1st Prize on China Postgraduate IC Innovation Competition (中国研究生创芯大赛)** from Association of Chinese Graduate Education. 
- *2020.06* **Shanghai Outstanding Graduate** (Top 1%) from Shanghai City.
- *2020.06* **Departmental Excellent Undergraduate Thesis (Department of Micro/Nano Electronics)** (Top 5%) from Shanghai Jiao Tong University.
- *2019.09* **Guanghua Scholarship** from Shanghai Jiao Tong University.

# 📖 Educations
- *2020.09 - 2025.06 (expected)*, Ph.D. student in Electronic Science and Technology  (*Department of Micro/Nano Electronics*), Shanghai Jiao Tong University, Shanghai, China.
- *2016.09 - 2020.06*, B.E. in Microelectronics Science and Engineering (*Department of Micro/Nano Electronics*), Shanghai Jiao Tong University, Shanghai, China. 

# 💬 Invited Talks
- *2023.07*, **"FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling"** in DAC'23, Moscone Center West, San Francisco, CA, USA. 
- *2023.07*, **"SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing"** in ICCAD'23, Hyatt Soma Downtown, San Francisco, CA, USA.

# 💻 Internships
- *2022.03 - now*, **Hardware & Toolchain Intern** in [Huixi Technology (辉羲智能)](https://www.rhino.auto/), Shanghai, China.

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/7.js?i=5omhdkjpo3a&amp;m=0&amp;c=ff0000&amp;cr1=ffffff&amp;sx=0" async="async"></script>

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/0.js?i=55sol1o649h&amp;d=3&amp;p=0&amp;b=0&amp;w=293&amp;g=2&amp;f=arial&amp;fs=12&amp;r=0&amp;c0=362b05&amp;c1=375363&amp;c2=000000&amp;ic0=0&amp;ic1=0" async="async"></script>
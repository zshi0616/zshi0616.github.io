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

Zhengyuan Shi (石正源, Stone) is a Ph.D. Candidate in Dept. of Computer Science and Engineering, The Chinese University of Hong Kong (CUHK), supervised by [Prof. Qiang Xu](https://cure-lab.github.io/). 
Prior to my journey in CUHK, I obtained the B.Eng. degree with honors in Shandong University in 2021 and was supervised by [Prof. Gangqiang Yang](https://faculty.sdu.edu.cn/g37yang/en/index.htm). 
I gained valuable experience as an intern at Huawei, Hisilicon and Xilinx, and also worked as a visiting student at CityU and UBC. 

**I'm looking for job opportunities in research positions, will graduate in Aug. 2025.**


My research focuses on the following areas: 
- **AI for EDA**: Large Circuit Model, Logic Synthesis and Formal Verification. 
- **AI for Optimization Problem**: SAT/SMT, MaxSAT, ILP. 

I have published more than 20 papers at the top EDA conferences and journals, including DAC, ICCAD, DATE and ASPDAC. I also served as reviewer for DAC, ICCAD, TVLSI, Sci China Inf Sci and etc. 

<!-- **<font color=Red>I'm looking for job opportunity (Faculty and Post-doc) in academia, expected to graduate in Nov. 2025</font>** -->

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Our paper *DeepGate3: Towards Scalable Circuit Representation Learning* was accepted by International Conference on Computer-Aided Design. [Link](https://arxiv.org/abs/2407.11095)
- *2023.11*: &nbsp;👉👉 The pip package of *DeepGate2* was released. You can call the circuit representation model only with **7 lines**. [Link](https://github.com/Ironprop-Stone/python-deepgate) 
- *2023.08*: &nbsp;🎉🎉 Our two papers *DeepGate2: Functionality-Aware Circuit Learning* and *SATformer: Transformers for UNSAT Solving* were accepted by International Conference on Computer-Aided Design. 
- *2022.04*: &nbsp;🎉🎉 Our paper *DeepGate: Learning Neural Representations of Logic Gates* was nominated as Best Paper in Design Automation Conference.  
- *2021.04*: &nbsp; I was selected as the *Outstanding Student of Shandong Province* and my undergraduate thesis was awarded by *Outstanding Undergraduate Thesis Award* in SDU. 
- *2020.12*: &nbsp; I received *Presidential Scholarship* (校长奖学金, only 20 students) and *Baosteel Scholarship* (宝钢奖学金，only 4 students), which is reported by news [齐鲁晚报](https://baijiahao.baidu.com/s?id=1686698491896705379&wfr=spider&for=pc). 

# 📝 Publications 
**Conference Publication**
- [C13] [DeepGate3: Towards Scalable Circuit Representation Learning](https://arxiv.org/pdf/2407.11095), **Zhengyuan Shi**, Ziyang Zheng, Jianyuan Zhong, et. al. International Conference on Computer-Aided Design (ICCAD), 2024
- [C12] [EDA-Driven Preprocessing for SAT Solving](https://arxiv.org/abs/2403.19446), **Zhengyuan Shi**, Tiebing Tang, et. al. Preprint, 2024
- [C11] [DeepSeq2: Temporal Correlations Aware Sequential Circuit Learning](), Sadaf Khan, **Zhengyuan Shi**, Min Li and Qiang Xu, Preprint, 2024
- [C10] [DeepGate2: Functionality-Aware Circuit Learning](https://ieeexplore.ieee.org/document/10323798/), **Zhengyuan Shi**, Hongyang Pan, et. al, International Conference on Computer-Aided Design (ICCAD), 2023
- [C9] [SATformer: Transformers for UNSAT Solving](https://ieeexplore.ieee.org/document/10323731), **Zhengyuan Shi**, Min Li, et. al, International Conference on Computer-Aided Design (ICCAD), 2023
- [C8] [On EDA-Driven Learning for SAT Solving](https://ieeexplore.ieee.org/document/10248001/), Min Li, **Zhengyuan Shi**, et. al, Design Automation Conference (DAC), 2023
- [C7] [Addressing Variable Dependency in GNN-based SAT Solving](https://arxiv.org/pdf/2304.08738), Zhiyuan Yan, Min Li, **Zhengyuan Shi**, et. al. Computer Aided Verification (CAV), 2023
- [C6] [DeepSeq: Deep Sequential Circuit Learning](https://arxiv.org/abs/2302.13608), Sadaf Khan, **Zhengyuan Shi**, et. al. . Design, Automation & Test in Europe (DATE), 2023
- [C5] [Design Space Exploration of Galois and Fibonacci Configuration based on Espresso Stream Cipher](https://dl.acm.org/doi/10.1145/3567428), **Zhengyuan Shi**, Cheng Chen, Gangqiang Yang, et. al. International Conference on Field Programmable Technology (FPT), 2022
- [C4] [DeepTPI: Test Point Insertion with Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/9983950), **Zhengyuan Shi**, Min Li, et. al. International Test Conference, 2022
- [C3] [DeepGate: Learning Neural Representations of Logic Gates](https://dl.acm.org/doi/10.1145/3489517.3530497), Min Li, Sadaf Khan, **Zhengyuan Shi**, et. al. Design Automation Conference (DAC), 2022
- [C2] [Towards a Smaller than Grain Stream Cipher: Optimized FPGA Implementations of Fruit-80](https://ieeexplore.ieee.org/document/9933149), **Zhengyuan Shi**, Gangqiang Yang, et. al. International Conference on Compilers, Architectures, and Synthesis for Embedded Systems (CASES), 2022
- [C1] [Testability-Aware Low Power Controller Design with Evolutionary Learning](https://ieeexplore.ieee.org/document/9611355/), Min Li, **Zhengyuan Shi**, et. al. International Test Conference, 2021

**Journal Publication**
- [J4] [The Dawn of AI-Native EDA: Promises and Challenges of Large Circuit Models](https://arxiv.org/abs/2403.07257), Qiang Xu, Guojie Luo, Mingxuan Yuan, **Zhengyuan Shi**, et. al. Preprint, 2024
- [J3] [Customized FPGA Implementation of Authenticated Lightweight Cipher Fountain for IoT Systems](https://dl.acm.org/doi/10.1145/3643039), **Zhengyuan Shi**, Cheng Chen, Gangqiang Yang et. al. ACM Transactions on Embedded Computing Systems (TECS), 2024
- [J2] [Hardware Optimizations of Fruit-80 Stream Cipher: Smaller than Grain](https://dl.acm.org/doi/10.1145/3569455), **Zhengyuan Shi**, Gangqiang Yang, et. al. ACM Transactions on Reconfigurable Technology and Systems (TRETS), 2023
- [J1] [Design Space Exploration of Galois and Fibonacci Configuration based on Espresso Stream Cipher](https://dl.acm.org/doi/10.1145/3567428), **Zhengyuan Shi**, Cheng Chen, Gangqiang Yang, et. al. ACM Transactions on Reconfigurable Technology and Systems (TRETS), 2023

# 🎖 Honors and Awards
**Acadamic Awards**
- *2023.09* International Conference on Computer-Aided Design (ICCAD) Student Scholar
- *2023.05* Design Automation Conference (DAC) Young Fellowship
- *2022.06* Best Paper Awared Nominee, Design Automation Conference(DAC)
- *2021.04* Outstanding Undergraduate Thesis Award, Shandong University 

**Others**
- *2020.12* Presidential Scholarship, Shandong University 
- *2020.11* Outstanding Maker of Shandong Province (山东省优秀创客), Education Council of Shandong Province (省团委、省教育厅、省科技厅等)
- *2020.09* Second Prize, National Undergraduate Electronics Design Contest (全国大学生电子设计竞赛)
- *2018.05* Outstanding Individual in Innovation and Intrepreneurship, Human Resources and Social Security Bureau, Qingdao City (青岛市团委、市人社局等)
- *2016.11* First Prize, National Olympiad in Informatics in Provinces (NOIP)

# 📖 Educations
- *2021.08 - Now (2025.11)*, Ph.D. Candidate, Department of Computer Science and Engineering, The Chinese University of Hong Kong. 
- *2017.09 - 2021.06*, B.Eng. in Information Engineering, School of Information Science and Engineering, Shandong University. 
- *2018.07 - 2018.08*, Visiting Student, Department of Electrical and Computer Engineering, University of British Columbia. 

# 💻 Internships
- *2024.05 - Now*, National Technology and Innovation Center of EDA 国家集成电路设计自动化技术创新中心, Nanjing, China
- *2022.05 - 2024.05*, Noah's Lab, Huawei, Hong Kong S.A.R. 
- *2021.03 - 2021.06*, Hisilicon, China. 
- *2020.07 - 2020.11*, Central Hardware Engineering Department, Huawei, China. 
- *2019.12 - 2021.04*, Architecture Lab for Arithmetic and Security, CityU, supervised by [Prof. Ray C.C. Cheung](https://scholars.cityu.edu.hk/en/persons/chak-chung-ray-cheung(9874f0c3-ce32-4806-95b1-bb5ff42fe85d).html). 
- *2019.06 - 2019.09*, Xilinx, China.

# 💪 Services
- Chair, IEEE CUHK Student Branch
- Teaching Assistant, Embedded System Development and Applications (CENG4480) / Embedded System Design (CENG2400), CUHK
- Teaching Assistant, Applied Blockchain and Cryptocurrencies (FTEC5520), CUHK

# 😘😘😘 
My love 💗: Yiran Liu, Ph.D. student in the Faculty of Business Administration, University of Macau. 

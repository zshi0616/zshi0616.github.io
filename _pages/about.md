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

Zhengyuan Shi (石正源, Stone) will join the [Microelectronics Thrust](https://mics.hkust-gz.edu.cn/) of Hong Kong University of Science and Technology, Guangzhou (HKUST-GZ) as Assistant Professor in Jan. 2027. I'm now a Postdoctoral Fellow at The Chinese University of Hong Kong (CUHK), supervised by [Prof. Qiang Xu](https://cure-lab.github.io/). Before that, I was Visiting Researcher at University of Bremen, work with [Prof. Rolf Drechsler](https://rolfdrechsler.de/). I obtained Ph.D. degree from CUHK in 2026 and B.Eng. degree with presidential scholarship from Shandong University in 2021. I have published more than 40 papers at top-tier conferences and journals, with 1 Best Paper Award (DAC26), 1 Best Poster Award (ASPDAC26) and 2 Best Paper Nomination awards. I have also served as TPC member for several conferences and reviewer for journals. 

My research focuses on **AI/LLM** for **Electronic Design Automation (EDA)** and **Constraint Programming (CP)**. 

<font color=Red>
I'm recruiting 2-3 PhD students at HKUST-GZ. PhD admission is available for 2027 Spring and 2027 Fall. Red Bird MPhil (RBM) students, undergraudate students, visiting students are also welcome. 
Contact: zyshi21[AT]cse.cuhk.edu.hk / zshi0616[AT]gmail.com
</font>


# 🔥 News
- *2026.09*: &nbsp; Two papers were accepted by ASPDAC 2027! 
- *2026.07*: &nbsp; Our paper *Miter-Aware LUT Mapping: Aligning Structure for Efficient Logic Equivalence Checking* was selected as **Best Paper** in DAC! As co-corresponding author, this is also my first time guiding a junior PhD student. Congratulations to Jiaying! 🎉🎉
- *2026.07*: &nbsp; Two papers were accepted by ICCAD 2026! 
- *2026.02*: &nbsp; Two papers were accepted by DAC 2026. But I may not attend the conference this year 😭. 
- *2026.01*: &nbsp; I was honored to receive the Best Poster Award at SRF of ASPDAC 2026. 

<details markdown="1">
<summary style="cursor: pointer; text-align: center; list-style: none;">--- Show More ---</summary>

- *2025.09*: &nbsp; Two papers were accepted by ASPDAC 2026 (I can't wait to the magical visit to HK Disneyland~). 
- *2025.08*: &nbsp; Our SAT solver Kissat-CURE wins the 3rd prize in SAT Competition Main Track. 
- *2025.06*: &nbsp; Two papers *DeepCell* and *MMCircuitEval* were accepted by International Conference on Computer-Aided Design (ICCAD). 
- *2025.06*: &nbsp; I was selected to attend CP/SAT Doctoral Program and present our work **Circuit Learning for Boolean Satisfiability Problems**. Association for Constraint Programming (ACP) will cover all the travel cost, thanks for the support! 
- *2025.05*: &nbsp; Our paper *DynamicSAT: Dynamic Configuration Tuning for SAT Solving* was accepted by International Conference on Principles and Practice of Constraint Programming (CP). 
- *2025.04* &nbsp; My poster of my PhD topic **Large Circuit Model: Towards AI-Native EDA Methodology** was accpeted by Design Automation Conference (DAC) PhD Forum with 1,000$ travel grant support. 
- *2025.02*: &nbsp; Our paper *Logic Optimization Meets SAT: A Novel Framework for Circuit-SAT Solving* was accepted by Design Automation Conference (DAC).
- *2025.01*: &nbsp; Our paper *DeepSeq2: Enhanced Sequential Circuit Learning with Disentangled Representations* [Link](https://arxiv.org/abs/2411.00530) was **nominated as Best Paper** in ASPDAC. 🎉🎉
- *2024.11*: &nbsp; Our paper about **Large Circuit Model**, an AI-native foundation model for EDA, was published in Science China Information Science [微信公众号](https://mp.weixin.qq.com/s/q-HwkFwaq44yzAZLwDQNCA)

</details>

# 🧐 Research
**Circuit Representation Learning**: 

- Netlist Encoder and Its Applications: [DeepGate Family @ ICCAD23](https://github.com/zshi0616/python-deepgate) for combinational circuit, [DeepSeq Family @ DAC26](https://arxiv.org/abs/2608.28188) for sequential circuit. 
- Multimodal / Multiview Learning: [DeepCell @ ICCAD25](https://ieeexplore.ieee.org/abstract/document/11240883), [MixGate @ ICCAD26](https://arxiv.org/abs/2509.20968)

**From Boolean Satisfiability to Logic Verification**: 

- Problem Reformulation (Preprocessing): [LOMeetSAT @ DAC25](https://arxiv.org/abs/2403.19446), [Map4LEC @ DAC26](https://arxiv.org/abs/2607.07164)
- AI-driven Heuristics (Inprocessing): [DynamicSAT @ CP25](https://drops.dagstuhl.de/storage/00lipics/lipics-vol340-cp2025/LIPIcs.CP.2025.34/LIPIcs.CP.2025.34.pdf), [CASCAD](https://arxiv.org/abs/2508.04235)

**Cross-stage Design and Optimization**:
- Physical-Aware Design: [LevelSyn @ ICCAD26]()
- LLM-driven Design: [MMCircuitEval @ ICCAD25](https://arxiv.org/abs/2507.19525)


# 📝 Publications 
**Publication Summary**: DAC+ICCAD x12, DATE+ASPDAC x8

**Best Paper Award** x1: DAC26

**Best Poster Award** x1: ASPDAC26

**Best Paper Nomination** x2: ASPDAC25, DAC22


Full publication list is available on [Google Scholar]({{ site.author.googlescholar }}).

<!-- # 🎖 Honors and Awards
- *2026.06* Best Paper Award, Design Automation Conference (DAC)
- *2026.01* Best Poster Award, Asia and South Pacific Design Automation Conference (ASPDAC)
- *2025.07* 3rd Award, SAT Competition Main Track. 
- *2025.01* Best Paper Award Nominee, Asia and South Pacific Design Automation Conference (ASPDAC)
- *2022.06* Best Paper Award Nominee, Design Automation Conference (DAC) -->

# 💼 Works
- *2027.01 - Now*, Assistant Professor, Hong Kong University of Science and Technology, Guangzhou. 
- *2026.03 - 2026.12*, PostDoc, The Chinese University of Hong Kong. 
- *2026.05 - 2026.08*, Visiting Scholar, University of Bremen. 

# 📖 Educations
- *2021.08 - 2026.03*, Ph.D., Department of Computer Science and Engineering, The Chinese University of Hong Kong. 
- *2017.09 - 2021.06*, B.Eng., School of Information Science and Engineering, Shandong University. 

# 🎙️ Invited Talks
- *2026.01*, [Learning Circuit Intuition for Smart Design Automation](https://r10.ieee.org/guangzhou-ceda/seminar-talk-026/), IEEE CEDA Guangzhou Chapter. 
- *2025.11*, [Beyond LLMs: Making Foundation Model Understand Circuit](https://sites.google.com/view/iccad-workshop-2025/home), Foundation Models and EDA Workshop, ICCAD 2025. 
- *2025.09*, [大电路模型：进展与展望](https://www.ccf.org.cn/Activities/Training/ADL/ADL/2025-08-19/847782.shtml), CCF ADL164《AI自动芯片设计》. 

<!--
# 💻 Teaching
- Teaching Assistant, Embedded System Development and Applications (CENG4480) / Embedded System Design (CENG2400), CUHK
- Teaching Assistant, Applied Blockchain and Cryptocurrencies (FTEC5520), CUHK -->

# 😘😘😘 
My love 💗: Yiran Liu, Ph.D. candidate in the Faculty of Business Administration, University of Macau. 
<img src="./images/01.jpg" alt="photo" title="photo" width="50%" />

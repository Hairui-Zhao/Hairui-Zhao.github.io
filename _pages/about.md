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


<br>

<div style="font-size: 24pt; font-weight: bold; line-height: 1.2;">Hairui Zhao (赵海睿)</div>

<div style="font-size: 16pt; font-weight: bold; margin-top: 10px;">Assistant Professor / Postdoc </div>

<div style="font-size: 14pt; color: #2c5aa0; margin-top: 5px;">
  <a href="http://www.ict.cas.cn/" style="text-decoration: none; color: #2c5aa0;">Institute of Computing Technology, Chinese Academy of Sciences</a>
</div>

<div style="font-size: 14pt; font-weight: bold; margin-top: 5px;">
  zhaohairui[at]ict[dot]ac[dot]cn
</div>

---
<br><br>



Hairui Zhao (Harry) is currently an **Assistant Professor/Postdoc (特别研究助理) at the [Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS)](https://www.ict.ac.cn/).**
I received my Ph.D. from the College of Computer Science and Technology at [**Jilin University (JLU)**](https://www.jlu.edu.cn/), supervised by [**Associate Prof. Hongliang Li**](https://ccst.jlu.edu.cn/info/1028/20013.htm). From September 2024, I was a **Joint Ph.D. Student** at the [**University of California, Riverside (UCR)**](https://www.ucr.edu/), supported by the **China Scholarship Council (CSC)** and supervised by [**Prof. Zizhong Chen**](https://www.cs.ucr.edu/~chen/). I also hold a Master's degree from Jilin University, where I was supervised by [**Prof. Huaxiao Liu**](https://teachers.jlu.edu.cn/LHX17/zh_CN/index/641487/list/index.htm).
My research interests include: **Distributed Systems, Fault-Tolerant, High-Performance Computing (HPC), and Scheduling.**
  


<span class='anchor' id='-xl'></span>

# 🎓 Experience
- *2026.04 - Present*, <a href="http://www.ict.cas.cn/"><img class="jpg" src="/images/ICT.jpg" width="20pt"></a>  ICT, CAS, Beijing, China, Assistant Professor (Postdoc)
- *2025.11 - 2026.04*, <a href="http://www.ict.cas.cn/"><img class="jpg" src="/images/ICT.jpg" width="20pt"></a>  ICT, CAS, Beijing, China, Intern
- *2024.09 - 2025.10*, <a href="https://www.ucr.edu/"><img class="png" src="/images/ucr.png" width="20pt"></a> UCR, California, USA, Joint Ph.D.
- *2021.09 - 2026.03*, <a href="https://www.jlu.edu.cn/"><img class="png" src="/images/jlu.png" width="20pt"></a> JLU, Changchun, China, Ph.D.
- *2019.12 - 2020.02*, <a href="http://www.ict.cas.cn/"><img class="jpg" src="/images/ICT.jpg" width="20pt"></a> ICT, CAS, Beijing, China, Intern
- *2019.09 - 2021.06*, <a href="https://www.jlu.edu.cn/"><img class="png" src="/images/jlu.png" width="20pt"></a> JLU, Changchun, China, M.S.
- *2015.09 - 2019.06*, <a href="https://www.jlu.edu.cn/"><img class="png" src="/images/jlu.png" width="20pt"></a> JLU, Changchun, China, B.S.

<span class='anchor' id='-xshy'></span>

# 📰 News
- 🎉**Apr 2026**: Two papers accepted by **HPDC 2026** (**CCF-A**):
    * "TACO: Efficient Communication Compression of Intermediate Tensors for Scalable Tensor-Parallel LLM Training."
    * "cuNNQS-SCI: A Fully GPU-Accelerated Framework for High-Performance Configuration Interaction Selection with Neural Network Quantum States."
- 🎉**Nov 2025**: Three papers published in **PPoPP 2025** (**CCF-A**):
    * "COCCL: A Collective Communication Library Supporting Easy Integration and Configuration of Customized Compression for Scalable LLM Training."
    * "CCL-D: A High-Precision Diagnostic System for Slow and Hang Anomalies in Large-Scale Model Training."
    * "PRISM: An Efficient GPU-Based Lossy Compression Framework for Progressive Data Retrieval with Multi-Level Interpolation."
- 🎉**Apr 2025**: Our paper "FlexPipe: Maximizing the Training Efficiency for Transformer-based models with Variable-Length Inputs" was accepted by **USENIX ATC 2025** (**CCF-A**).
- 🎉**Feb 2025**: Our paper "Alleviating Straggler Impacts for Data Parallel Deep Learning with Hybrid Parameter Update" was accepted by **Future Generation Computing Systems** (**FGCS, CAS Tier 1 TOP**). Congratulations to my collaborator, **Qi Tian (2023 Master student)**!
- 🎉**Dec 2024**: Our paper "ArrayPipe: Introducing Job-Array Pipeline Parallelism for High Throughput Model Exploration" was accepted by **IEEE INFOCOM 2025** (**CCF-A**).
- 🎉**Nov 2024**: Interviewed by the School of Engineering, Westlake University, regarding our NLPCC 2024 Best Paper Award. [[Link]](https://www.westlake.edu.cn/news_events/westlakenews/UniversityNews/202411/t20241108_44358.shtml)
- 🎉**Nov 2024**: Our paper "Visage: Visual-Aware Generation of Adversarial Examples in Black-Box for Text Classification" won the **Best Paper Award (1/160)** at **NLPCC 2024** (**CCF-C**).

 
<span class='anchor' id='-lwzl'></span>

# 📝 Selected Publications

---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ATC 2025</div><img src='images/ATC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Hairui Zhao*`, Qi Tian*, Hongliang Li, Zizhong Chen. " FlexPipe: Maximizing the Training Efficiency for Transformer-based models with Variable-Length Inputs. " Accepted by 2025 USENIX Annual Technical Conference (**CCF-A Conference**)
[[网页]]() 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INFOCOM 2025</div><img src='images/INFOCOM.JPG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Hairui Zhao`, Hongliang Li, Qi Tian, Jie Wu, Meng Zhang, Zhewen Xu, Xiang Li, and Haixiao Xu. " ArrayPipe: Introducing Job-Array Pipeline Parallelism for High Throughput Model Exploration. " Accepted by 2025 IEEE International Conference on Computer Communications (**CCF A Conference**) 
[[网页]](https://cis.temple.edu/~jiewu/research/publications/Publication_files/m48122-zhao%20final.pdf#:~:text=This%20paper%20introduces%20Job-Array%20Pipeline%20Parallelism%20%28JAP%29%20that,sibling%20DL%20training%20jobs%20into%20a%20concurrent%20job-array.) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NLPCC 2024</div><img src='images/NLPCC.JPG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Hairui Zhao*`, Xinyu Li*, Hongliang Li. " Visage: Visual-Aware Generation of Adversarial Examples in Black-Box for Text Classification. " Published on 2024 CCF International Conference on Natural Language Processing and Chinese Computing (**Best Paper Award, 1/160, CCF C Conference**) 
[[网页]](https://link.springer.com/chapter/10.1007/978-981-97-9440-9_34)

</div>
</div>

<div style="display:none">

-	Hongliang Li, `Hairui Zhao`, Zhewen Xu, Xiang Li, and Haixiao Xu. " ExplSched: Maximizing Deep Learning Cluster Efficiency for Exploratory Jobs. " Published on 2023 IEEE Conference on CLUSTER Computing (**CCF B Conference**) 
[[网页]](https://ieeexplore.ieee.org/document/10319954)

- Hongliang Li, `Hairui Zhao`, Ting Sun, Xiang Li, Haixiao Xu and Keqin Li. " Interference-aware Opportunistic Job Placement for Shared Distributed Deep Learning Clusters. " Published on 2024 Elsevier Journal of Parallel and Distributed Computing  (**CCF B Journal**)
[[网页]](https://www.sciencedirect.com/science/article/abs/pii/S0743731523001466)

- Hongliang Li, Qi Tian, Dong Xu, `Hairui Zhao` and Zhewen Xu. "Alleviating straggler impacts for data parallel deep learning with hybrid parameter update." Published on Future Generation Computing System ( **中科院一区 TOP**) [[网页]](https://www.sciencedirect.com/science/article/abs/pii/S0167739X25000706?fr=RR-7&ref=pdf_download&rr=9363e13e6cd293e4)

</div>

<span class='anchor' id='-ryjx'></span>

# 🏅 Honors and Awards

🏆 **Featured Award**
- **Best Paper Award (1/160)**, (**NLPCC 2024**)

🏆 **National & International**
- **CSC Scholarship (China Scholarship Council)**: (2024–2026)
- **National Encouragement Scholarship** (2017–2018)

🏆 **University & Specialized**
- **Zhengyuan Scholarship**, Jilin University (2023–2024)
- **Wang Xianghao Scholarship** Jilin University (2022–2023)
- **Outstanding Graduate Student Scholarship (Second Prize)** (2022–2023)
- **Doctoral Academic Fellowship/Scholarship**, Jilin University (2021–2024)
- **Master's Academic Fellowship/Scholarship**, Jilin University (2020–2021)

🏆 **Leadership & Service**
- **Outstanding Graduate Student Leader** (2022–2023)
- **Outstanding Youth League Leader**, (2021)
- **Outstanding Graduate Student Leader** (2020)
- **Outstanding Class Officer** (2018–2019)

<div style="display:none">
- 2017-2018学年国家励志奖学金
- 2018-2019优秀班级干部
- 2018年吉林大学夏令营优秀营员
- 2021年软件与理论硕士研究生优秀团干部
- 2020-2021学年研究生学业奖学金获奖
- 2020年优秀研究生干部
- 2021-2024学年博士研究生学业奖学金获奖
- 2022-2023 年研究生优秀奖学金 （二等）
- 2022-2023 年优秀研究生干部
- 2022-2023 年王湘浩奖学金
- 2023-2024年吉林大学正元奖学金
- 2024-2026年2年中国国家留学基金委访问学者项目
</div>

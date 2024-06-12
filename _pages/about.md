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

# 🙋🏻‍♀️ About Me
I am a master's student at Northwestern Polytechnical University, supervised by [Prof. Yong Xia](https://scholar.google.com/citations?user=Usw1jeMAAAAJ) and [Assoc. Prof. Hengfei Cui](https://scholar.google.com/citations?user=SQbO8oQAAAAJ). My recent research focuses on active learning and federated learning in medical image analysis.


# 🔥 News
- *2024.05*: &nbsp;🎉🎉 One conference paper was early accepted by MICCAI 2024, about Adaptive Weight Aggregation for Federated Learning. 
- *2024.02*: &nbsp;🎉🎉 One conference paper was accepted by CVPR 2024, about [Federated Active Learning](https://arxiv.org/abs/2312.02567).

# 📝 Publications 
<sup>*</sup> denotes equal contribution and <sup>†</sup> indicates corresponding authorship.

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/FEAL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Think Twice Before Selection: Federated Evidential Active Learning for Medical Image Analysis with Domain Shifts**

<i> IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024 </i>

**Jiayi Chen**<sup>*</sup>, Benteng Ma<sup>*</sup>, Hengfei Cui, Yong Xia<sup>†</sup>

[[PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Think_Twice_Before_Selection_Federated_Evidential_Active_Learning_for_Medical_CVPR_2024_paper.pdf)] [[Supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Chen_Think_Twice_Before_CVPR_2024_supplemental.pdf)] [[ArXiv](https://arxiv.org/abs/2312.02567)] [[Code](https://github.com/JiayiChen815/FEAL)] [[BibTex](_pages/bibtex/FEAL.txt)]

<div style="text-align: justify">
In real-world medical scenarios, domain shifts across clients are commonly observed, posing challenges of <b>overconfidence</b> and <b>limited uncertainty representation</b> for federated active learning. To address these challenges, we propose a novel method termed <i>Federated Evidential Active Learning (FEAL)</i>, which incorporates a sampling strategy <i> Calibrated Evidential Sampling</i> and a local training scheme <i> Evidential Model Learning</i>.
</div>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/FedEvi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FedEvi: Improving Federated Medical Image Segmentation via Evidential Weight Aggregation**

<i> Medical Image Computing and Computer Assisted Intervention (MICCAI), 2024 </i> <font color="red">(Early Accept)</font>

**Jiayi Chen**<sup>*</sup>, Benteng Ma<sup>*</sup>, Hengfei Cui, Yong Xia<sup>†</sup>
<div style="text-align: justify">
Existing methods often adjust aggregation weights dynamically to improve the global model's generalization, but they rely heavily on the performance or reliability of the local models, excluding an explicit measure of the generalization gap that arises from deploying the global model across varied local datasets. To address this issue, we propose FedEvi, a method that adjusts the aggregation weights based on the generalization gap between the global model and each local dataset as well as the reliability of the local models.
</div>
</div>
</div>

# 🎖 Honors and Awards
- *2024.05*: NPU Master's Thesis Innovation Scholarship (Key Program)
- *2023.09, 2021.09, 2019.09*: NPU Second-Class Academic Award
- *2022.09, 2020.09*: NPU First-Class Academic Award
- *2022.05*: Outstanding Completion of National Undergraduate Innovation and Entrepreneurship Training Program

# 📖 Educations
- *2022.06 - Present*: Master's student in Computer Science and Technology, Northwestern Polytechnical University, China
- *2018.09 - 2022.06*: B.E. in Computer Science and Technology, Northwestern Polytechnical University, China

# 👩🏻‍💻 Academic Activities
- *2024.06.17-21*: CVPR 2024, Seattle WA, USA (Poster)
- *2024.05.05-07*: VALSE 2024, Chongqing, China
- *2023.07.14-17*: MICS 2023, Taiyuan, China

<div>
  <center>
    &copy; Jiayi Chen | Last updated: 
    <script> 
    document.write(document.lastModified); 
    </script>
  </center>
</div>
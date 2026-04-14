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
I am currently a PhD student at Monash University, supervised by [Prof. Jianfei Cai](https://scholar.google.co.uk/citations?user=N6czCoUAAAAJ) and [Dr. Yasmeen George](https://scholar.google.com/citations?hl=en&user=URHQRGwAAAAJ). Prior to joining Monash, I received my Master's and Bachelor's degrees from Northwestern Polytechnical University, where I was advised by [Prof. Yong Xia](https://scholar.google.com/citations?user=Usw1jeMAAAAJ) and [Assoc. Prof. Hengfei Cui](https://scholar.google.com/citations?user=SQbO8oQAAAAJ). My recent research focuses on trustworthy medical image analysis.


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One conference paper was early accepted by MICCAI 2025, about [Personalized Federated Parameter-Efficient Fine-Tuning](https://papers.miccai.org/miccai-2025/paper/0548_paper.pdf).
- *2025.03*: &nbsp;🎉🎉 One journal paper was accepted by IEEE-JBHI, about [Influence-Based Active Learning](https://pubmed.ncbi.nlm.nih.gov/40126962/). 
- *2024.05*: &nbsp;🎉🎉 One conference paper was early accepted by MICCAI 2024, about [Adaptive Weight Aggregation for Federated Learning](https://papers.miccai.org/miccai-2024/paper/2717_paper.pdf). 
- *2024.02*: &nbsp;🎉🎉 One conference paper was accepted by CVPR 2024, about [Federated Active Learning](https://arxiv.org/abs/2312.02567).

# 📝 Publications 
<sup>*</sup> denotes equal contribution and <sup>†</sup> indicates corresponding authorship.

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/FedNCARE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FedNCARE: Neural Collapse-Aligned Representation Learning for Federated Vision-Language Models under Partially Class-Disjoint Medical Data**

<i> Under review, 2026 </i> 

Yanyang Guo<sup>*</sup>, Benteng Ma<sup>*</sup>, **Jiayi Chen**, Hengfei Cui, Yong Xia<sup>†</sup>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/VIHD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VIHD: Visual Intervention-based Hallucination Detection for Medical Visual Question Answering**

<i> Under review, 2026 </i> 

**Jiayi Chen**<sup>†</sup>, Benteng Ma, Zehui Liao, Winston Chong, Yasmeen George, Jianfei Cai

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/LongDiff-IR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LongDiff-IR: Longitudinal Difference Attention with Instance-Aware Regularization for New MS Lesion Segmentation**

<i> Under review, 2026 </i> 

**Jiayi Chen**, Jin Ye<sup>†</sup>, Jianghao Wu, Jarrel Seah, Anthony Kam, Winston Chong, Yasmeen George, Jianfei Cai

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/EviATTA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**EviATTA: Evidential Active Test-Time Adaptation for Medical Segment Anything Models**

<i> Under review, 2026 </i> 

**Jiayi Chen**<sup>†</sup>, Yasmeen George, Winston Chong, Jianfei Cai

[[PDF](https://arxiv.org/pdf/2603.14666)]

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025</div><img src='images/pFedST.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Personalized Federated Side-Tuning for Medical Image Classification**

<i> Medical Image Computing and Computer Assisted Intervention (MICCAI), 2025 </i> <font color="red">(Early Acceptance)</font>

**Jiayi Chen**<sup>*</sup>, Benteng Ma<sup>*</sup>, Yongsheng Pan, Bin Pu, Hengfei Cui, Yong Xia<sup>†</sup>

[[PDF](https://papers.miccai.org/miccai-2025/paper/0548_paper.pdf)] [[Code](https://github.com/JiayiChen815/pFedST)]

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE-JBHI</div><img src='images/TDGF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Active Learning Based on Temporal Difference of Gradient Flow in Thoracic Disease Diagnosis**

<i> IEEE Journal of Biomedical and Health Informatics (JBHI) </i> 

**Jiayi Chen**<sup>*</sup>, Benteng Ma<sup>*</sup>, Hengfei Cui, Jingfeng Zhang, Yong Xia<sup>†</sup>

[[PDF](https://pubmed.ncbi.nlm.nih.gov/40126962/)] [[Code](https://github.com/JiayiChen815/TDGF)]

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/FedEvi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FedEvi: Improving Federated Medical Image Segmentation via Evidential Weight Aggregation**

<i> Medical Image Computing and Computer Assisted Intervention (MICCAI), 2024 </i> <font color="red">(Early Acceptance)</font>

**Jiayi Chen**<sup>*</sup>, Benteng Ma<sup>*</sup>, Hengfei Cui, Yong Xia<sup>†</sup>

[[PDF](https://papers.miccai.org/miccai-2024/paper/2717_paper.pdf)] [[Code](https://github.com/JiayiChen815/FedEvi)]

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/FEAL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Think Twice Before Selection: Federated Evidential Active Learning for Medical Image Analysis with Domain Shifts**

<i> IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024 </i>

**Jiayi Chen**<sup>*</sup>, Benteng Ma<sup>*</sup>, Hengfei Cui, Yong Xia<sup>†</sup>

[[PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Think_Twice_Before_Selection_Federated_Evidential_Active_Learning_for_Medical_CVPR_2024_paper.pdf)] [[Supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Chen_Think_Twice_Before_CVPR_2024_supplemental.pdf)] [[ArXiv](https://arxiv.org/abs/2312.02567)] [[Code](https://github.com/JiayiChen815/FEAL)] [[Poster](_pages/poster/FEAL_poster.pdf)] [[Video](https://www.youtube.com/watch?v=koDt8nN0gxg)] [[BibTex](_pages/bibtex/FEAL.txt)]

</div>
</div>


# 🎖 Honors and Awards
- *2025.08*: Outstanding Master's Thesis Award
- *2024.12*: National Scholarship 
- *2024.05*: NPU Master's Thesis Innovation Scholarship (Key Program)
- *2023.09, 2021.09, 2019.09*: NPU Second-Class Academic Award
- *2022.09, 2020.09*: NPU First-Class Academic Award
- *2022.05*: Outstanding Completion of National Undergraduate Innovation and Entrepreneurship Training Program

# 📖 Educations
- *2025.05 - Present*: PhD student in Faculty of Information Technology, Monash University, Australia
- *2022.06 - 2025.03*: Master in Computer Science and Technology, Northwestern Polytechnical University, China
- *2018.09 - 2022.06*: B.E. in Computer Science and Technology, Northwestern Polytechnical University, China

# 👩🏻‍💻 Reviews
- Conference: MICCAI, CVPR, ECCV, NeurIPS
- Journal: IJCV


<div>
  <center>
    &copy; Jiayi Chen | Last updated: 
    <script> 
    document.write(document.lastModified); 
    </script>
  </center>
</div>
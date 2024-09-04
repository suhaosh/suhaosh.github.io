---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
body {
  counter-reset: custom-counter; /* 第一个计数器，从 1 开始 */
}

/* 定义第一个编号，从1开始 */
.custom-counter::before {
  counter-increment: custom-counter;
  content: "[" counter(custom-counter) "] ";
  margin-right: 5px; /* 可选：增加编号与文本之间的间距 */
}

</style>



{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hao Su received the Ph.D. degree from the State Key Laboratory of Virtual Reality Technology and Systems, Beihang University, China, in 2024. He is currently an associate research fellow at the School of Computer and Artificial Intelligence, Zhengzhou University, Zhengzhou, China. His research interests are 2D/3D digital human generation, AIGC, and reinforcement learning.

<a href='https://scholar.google.com/citations?user=yf4XwjEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# Publications  

## 🥇 First Author + Corresponding Author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images/CVPR2021_artcoder.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="custom-counter"></span>	`Hao Su`, Jianwei Niu\*, Xuefeng Liu, Qingfeng Li, Ji Wan, Mingliang Xu.  ***<font color=darkblue>ArtCoder: An End-to-End Method for Generating Scanning-Robust Stylized QR Codes</font>***. IEEE
Conference on Computer Vision and Pattern Recognition (CVPR), 2021. (CCF-A)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI</div><img src='images/AAAI2021_mangaGAN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span class="custom-counter"></span>	`Hao Su`, Jianwei Niu\*, Xuefeng Liu, Qingfeng Li, Jiahe Cui, Ji Wan. ***<font color=darkblue>MangaGAN: Unpaired Photo-to-Manga Translation Based on The Methodology of Manga Drawing</font>***. AAAI Conference on Artificial Intelligence (AAAI), 2021. (CCF-A)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI</div><img src='images/BeyondVision.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span>	Nana Wang, Jianwei Niu, Xuefeng Liu, Dongqin Yu, Guogang Zhu, Xinghao Wu, Mingliang Xu, `Hao Su*`.  ***<font color=darkblue>BeyondVision: An EMG-driven Micro Hand Gesture Recognition Based on Dynamic Segmentation</font>***. International Joint Conferences on Artificial Intelligence (IJCAI), 2024. (CCF-A)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM</div><img src='images/ACMMM_Qart.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span>	`Hao Su`, Jianwei Niu, Xuefeng Liu\*, Qingfeng Li, Ji Wan, Mingliang Xu.  ***<font color=darkblue>Q-Art Code: Generating Scanning-robust Artstyle QR Codes by Deformable Convolution</font>***. ACM International Conference on Multimedia (ACM MM), 2021. (CCF-A)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT</div><img src='images/TCSVT_mang2vec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> `Hao Su`, Xuefeng Liu, Jianwei Niu\*, Ji Wan, Xinghao Wu, Nana Wang.  ***<font color=darkblue>MARVEL: Raster Manga Vectorization via Primitive-wise Deep Reinforcement Learning</font>***. IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2023. (CCF-B, CAS SCI District 1, JCR Q1)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/3Deformer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> `Hao Su`, Jianwei Niu, Xuefeng Liu\*, Ji Wan, Nana Wang. ***<font color=darkblue>3Deformer: A Common Framework for Image-Guided Face Editing</font>***. Arxiv, 2023.
</div>
</div>

<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> `Hao Su`, Jianwei Niu\*, Xuefeng Liu, Mohammed Atiquzzaman. ***<font color=darkblue>SafeCoder: A machine-learning-based encoding system to embed safety identification information into QR codes</font>***. Journal of Network and Computer Applications (JNCA), 2024. (CCF-C, CAS SCI District 2, JCR Q1)
</div>

<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Haozhe Guo, Mengjie Chen, Kaijiang Li, `Hao Su*`, Pei Lv. ***<font color=darkblue>GLAD: A Global-Attention-based Diffusion Model for Infrared and Visible Image Fusion</font>***. International Conference on Intelligent Computing (ICIC), 2024. (CCF-C)
</div>



## 🥉 Others
<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Guogang Zhu, Xuefeng Liu, Xinghao Wu, Shaojie Tang, Chao Tang, Jianwei Niu, `Hao Su`. ***<font color=darkblue>Estimating before Debiasing: A Bayesian Approach to Detaching Prior Bias in Federated Semi-Supervised Learning</font>***. International Joint Conferences on Artificial Intelligence (IJCAI), 2024. (CCF-A)
</div>
 
<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Xinghao Wu, Xuefeng Liu, Jianwei Niu, Haolin Wang, Shaojie Tang, Guogang Zhu, `Hao Su`. ***<font color=darkblue>Decoupling General and Personalized Knowledge in Federated Learning via Additive and Low-rank Decomposition</font>***. ACM International Conference on Multimedia (ACM MM), 2024. (CCF-A)
</div>


<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Mingliang Xu, `Hao Su`, Yafei Li\*, Xi Li, Jing Liao, Jianwei Niu, Pei Lv, Bing Zhou. ***<font color=darkblue>Stylized aesthetic QR code</font>***. IEEE Transactions on Multimedia (TMM), 2018. (CCF-B, CAS SCI District 1, JCR Q1)
</div>

<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Mingliang Xu, Qingfeng Li, Jianwei Niu\*, `Hao Su`, Xiting Liu, Weiwei Xu, Pei Lv, Bing Zhou, Yi Yang. ***<font color=darkblue>ART-UP: A novel method for generating scanning-robust aesthetic QR codes</font>***. ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM), 2021. (CCF-B, JCR Q1)
</div>

<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Ji Wan, Kai Hu\*, Jie Li, `Hao Su`. ***<font color=darkblue>AnonymousFox: An efficient and scalable blockchain consensus algorithm </font>*** IEEE Internet of Things Journal (IOT), 2022. (CCF-C, CAS SCI District 1, JCR Q1)
</div>

<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Ji Wan, Kai Hu\*, Jie Li, `Hao Su`, Qingshun Wu, Mingyuan Li, Libo Feng, Yan Pan. ***<font color=darkblue>Smart Contract Service Optimization in Blockchain-Cloud Collaborative Computing</font>***. IEEE International Conference on Mobile Data Management (MDM), 2023. (CCF-C)
</div>

<div class='paper-box-text' markdown="1"> 
<span class="custom-counter"></span> Ji Wan, Kai Hu\*, Jie Li, Yichen Guo, `Hao Su`, Shenzhang Li, Yafei Ye. ***<font color=darkblue>Zebra: A cluster-aware blockchain consensus algorithm</font>***. Journal of Network and Computer Applications (JNCA), 2024. (CCF-C)
</div>



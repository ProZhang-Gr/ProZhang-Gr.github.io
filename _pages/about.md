---
permalink: /
title: "Zihan Zhang's Personal Profile"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- Custom styles to increase font size -->
<style>
  body {
    font-size: 17px; /* Adjust the font size as needed */
    line-height: 1.6; /* Optional: adjust line height for better readability */
  }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='-about-me'></span>

# 📖 Personal Profile

<!-- **Yeqiang Wang (王业强)** is currently pursuing his B.S. degree in Software Engineering (Class of 2026) at [Northwest A&F University](https://www.nwafu.edu.cn/). He is a recommended graduate student for the Class of 2026. -->

I am **Zihan Zhang (张子涵)**, a third-year undergraduate student at the School of Computer Science, [Northwest A&F University (NWAFU)](https://www.nwsuaf.edu.cn/). My research interests span **Artificial Intelligence**, **Machine Learning**, **Large Language Models (LLMs)**, **Graph Neural Networks (GNNs)**, and **AI for Science (AI4SCI)**. I am passionate about exploring the intersection of these fields and welcome academic discussions.



<!-- You are welcome to contact him via email or WeChat: **Muchenxixi_**.  
**Email**: wangyeqiang@nwafu.edu.cn | wangyeqianger@126.com  
[GitHub](https://github.com/WangYeQianger) | [Gitee](https://gitee.com/Muchenxixi) -->



You are welcome to contact him via email or WeChat.
- **Email**: stuzzh@163.com
- **WeChat**: Z2844875842


Other platform links:
 [归山](https://www.zhihu.com/people/4-32-48-46) | [Bilibili (就叫张某人)](https://space.bilibili.com/481176872?spm_id_from=333.1007.0.0) | [GitHub](__https://github.com/ProZhang-Gr__)

<!-- [CV](/assets/PDF/CV/250409_个人简历_王业强.pdf) -->
<!-- [CSDN](https://blog.csdn.net/Muchenxi_?spm=1000.2115.3001.5343) -->

<span class='anchor' id='-News'></span>
# 🔥 News


- <span style="color: red; font-weight: bold;">[2026/02]</span> As the first author, Zihan has one paper accepted by <b>JCIM (JCR Q1, SCI Zone 2 TOP, IF=5.3, 2026).</b>

- <span style="color: red; font-weight: bold;">[2025/12]</span> As the first author, Zihan has one paper accepted by <b>JBHI (CCF-C, JCR Q1, SCI Zone 2 TOP, IF=6.8, 2025).</b>


<span class='anchor' id='-Publications'></span>

# 📝 Publications
<!-- JCIM 2026 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">JCIM 2026</div>
      <img src='images/achievements/2026_JCIM.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>NCRDLLM: Predicting ncRNA-Drug Response Associations via Multimodal Feature Fusion and Large Language Models</li>
      <li><strong>Zihan Zhang</strong>, Yuchen Zhang*.</li>
      <li><i>JCIM</i> 2026. (JCR:Q1, IF:5.3)</li>
      <!-- <li><a href="https://arxiv.org/abs/2402.05725">Link</a> |  -->
      <li><a href="https://pubs.acs.org/doi/full/10.1021/acs.jcim.5c03011">Link</a>
      <a href="https://github.com/ProZhang-Gr/NCRDLLM">Code</a></li>
    </ul>
  </div>
</div>

<!-- JBHI 2025 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">JBHI 2025</div>
      <img src='images/achievements/2025_JBHI.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <ul>
      <li>Prediction of circRNA-Drug Associations Based on Bipartite Graph Transformer</li>
      <li><strong>Zihan Zhang</strong>, Yuchen Zhang*, Xiujuan Lei.</li>
      <li><i>JBHI</i> 2025. (JCR:Q1, IF:6.8)</li>
      <!-- <li><a href="https://arxiv.org/abs/2402.05725">Link</a> |  -->
      <li><a href="https://ieeexplore.ieee.org/document/11319154">Link</a>
      <a href="https://github.com/ProZhang-Gr/CDBGT">Code</a></li>
    </ul>
  </div>
</div>





<span class='anchor' id='-Honors-and-Awards'></span>
# 🥇 Honors and Awards
- **National Scholarship**, Ministry of Education of the People's Republic of China (December 2025)
- **First Prize (Shaanxi Province)**, National Undergraduate Mathematical Contest in Modeling (December 2024)
- **Second Prize (Non-Math A)**, 16th National Undergraduate Mathematics Competition (December 2024)
- **Meritorious Winner (H Prize)**, Mathematical Contest in Modeling (MCM/ICM), COMAP (May 2025)

<!-- # 💻 Internships
-Tencent Technology (Shenzhen) Co., Ltd. 
Robotics X Lab (High-Density Electronic Skin Development)  
*October 2023 – March 2024*

-Xingji Guangnian  (Shenzhen)  Co., Ltd. 
Design of Tendon-Driven Dexterous Hand 
*August  2024 – October 2024* -->

<span class='anchor' id='-Pics'></span>

# 📸 Pics

<style>
  /* Contain the entire image gallery in a container */
  .image-carousel {
    display: flex;
    overflow: hidden; /* Hide the extra images outside the container */
    width: 100%; /* Make it responsive */
    justify-content: space-around; /* Ensure images are spaced evenly */
  }

  /* Create the scroll effect with animation */
  .image-carousel .carousel-items {
    display: flex;
    animation: scroll-images 15s linear infinite; /* Animation name, duration, timing function, and repeat */
  }

  /* Define the scrolling animation */
  @keyframes scroll-images {
    0% {
      transform: translateX(0);
    }
    100% {
      transform: translateX(-100%); /* Move the container to the left, fully scrolling the images */
    }
  }

  /* Style the images */
  .image-carousel img {
    width: 500px;
    height: 300px; /* Set consistent height for all images */
    object-fit: cover;
    margin-right: 20px; /* Add space between images */
  }
</style>

<!-- Image carousel wrapper -->
<div class="image-carousel">
  <div class="carousel-items">
    <!-- Add images inside this wrapper -->
    <img src="images/Personal_Imgs/1.jpg" >
    <img src="images/Personal_Imgs/2.jpg" >
    <img src="images/Personal_Imgs/3.jpg" >
    <img src="images/Personal_Imgs/4.jpg" >
    <img src="images/Personal_Imgs/5.jpg" >
    <img src="images/Personal_Imgs/6.jpg" >
    <img src="images/Personal_Imgs/1.jpg">
    <img src="images/Personal_Imgs/2.jpg">
    <img src="images/Personal_Imgs/3.jpg">
    <img src="images/Personal_Imgs/4.jpg">
    <img src="images/Personal_Imgs/5.jpg">
    <img src="images/Personal_Imgs/6.jpg">
  </div>
</div>


<span class='anchor' id='-about-more'></span>
# 🙋 如果你想了解我

我正处于推免阶段，欢迎您了解我的个人细节，希望这对您了解我能有所帮助。

我的科研生活起始于2025年年初，我追随我院老师进行生信研究，期间独立完成所有工作，我所发表的论文均为独立一作。感谢我的老师[张宇辰](https://cie.nwsuaf.edu.cn/szdw/jiangshi/2022110148/index.htm)先生给予我莫大的支持。

我的座右铭是"学的时候认真学，玩的时候好好玩"。我想我具备一定的抗压能力和理性思考能力。我个人性格开朗，喜欢沉浸在自己所提出的问题中，享受自言自语似的推理与一步步自圆其说，从中获得正反馈——这种方法我常常用在科研工作中，在这种状态下，我走了很远的路。

我接受直博与硕博连读，因为我相信自己的能力。另一方面，在研究AI4SCI的过程中，我诞生了对AI机理研究的渴望，想要从事一些深层次的研究，解决我长久以来关于大模型、Transformer机理上的困惑。AI发展正如日中天，未来十年也不会落幕，我期待这场蛰伏，等待夏夜的到来。

我喜欢摄影，我是一个浪漫的人，我相信自己的审美（你可以看到我两篇论文图摘要的配色，想必还算ok）。

我期待前往北京的高校，若能力尚有不足，也会尝试北京中关村联培项目。

我期待我的导师严肃科研、生活活泼，能给予我科研上的解惑，也能因我的成就真切感到高兴。

<!-- <span class='anchor' id='-VisitMap'></span> -->

<!-- # 🗺️ Visit Map

<a href="https://clustrmaps.com/site/1byil"><img src="https://clustrmaps.com/map_v2.png?cl=ffffff&w=800&t=m&d=X3J61-hp75joVFvuLSJlgpbB6riHUwJsEuuJ_A-gLmM&co=2d78ad&ct=ffffff" /></a> -->


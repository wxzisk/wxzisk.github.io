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

Here is Xizheng Wang's homepage. I'm a Ph.D student in Department of Computer Science and Technology, Tsinghua University, supervised by Prof. <a href='https://nasp.cs.tsinghua.edu.cn/lidan.html'>Dan Li</a>. Before I started my PhD, I received my undergraduate degree and master's degree from Hunan University under the supervision of Professor <a href='http://grzy.hnu.edu.cn/site/index/chenguo'>Guo Chen</a>.

My research interest includes data center network, high-performance NIC. And recently, I have embarked on exploring AI for network.


# 🔥 News
- *2023.06*: &nbsp;🎉🎉 Our paper has been accepted by <a href='https://conferences.sigcomm.org/sigcomm/2023/'>SIGCOMM'23</a>. 
- *2023.06*: &nbsp;🎉🎉 Our paper has been accepted by <a href='https://conferences.sigcomm.org/events/apnet2023/index.html'>APNet'23</a>. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICNP 2021</div><img src='images/StaR_fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[StaR: Breaking the Scalability Limit for RDMA](https://ieeexplore.ieee.org/document/9651935)

**Xizheng Wang**, Guo Chen*, Xijin Yin, Huichen Dai, Bojie Li, Binzhang Fu, Kun Tan

- We propose StaR (Stateless RDMA), which solves the scalability problem of RDMA by transferring states to the other communication end. Leveraging the asymmetric communication pattern in data center applications, StaR lets the communication end with low concurrency save states for the other end with high concurrency, thus making the RNIC on the bottleneck side to be stateless. We have implemented StaR on an FPGA board with 10Gbps network port and evaluated its performance on a testbed
with 9 machines all equipped with StaR NICs. The experimental results show that in high concurrency scenarios, the throughput of StaR can reach up to 4.13x and 1.35x of the original RNIC and the latest software-based solution, respectively.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

</div>
</div>

- [Here is the open-source project of this paper which is a copy of the Verilog/VHDL code deployed on Hardware](https://github.com/wxzisk/stateless_board)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">APNet 2023</div><img src='images/sRDMA_fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

sRDMA: A General and Low-Overhead RDMA Scheduler for RDMA(pre to publish)

**Xizheng Wang**, Shuai Wang*, Dan Li

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

- We propose sRDMA, a general and lowoverhead scheduler working in user-space RDMA driver. sRDMA allows the application to express the expected transfer order to RDMA hardware via work requests (WRs). With priority information in WRs, sRDMA slices and schedules WRs to achieve desired order of message transfer and reduce
blocking impact of large messages in the same RDMA connection. Our experiments show that sRDMA can improve the performance of applications, e.g., TensorFlow, by up to 54%, and sRDMA has negligible overhead in terms of CPU and flow throughput.

</div>
</div>

# 🎖 Honors and Awards
- *2019.06* Outstanding gradute, Hunan University. 

# 📖 Educations
- *2022.09 - now*, Ph.D candidate, Tsinghua University. 
- *2019.09 - 2022.06*, Master degree, Hunan University.
- *2015.09 - 2019.06*, Bachelor degree, Hunan University. 

# 💬 Tech Blog
- [Some blogs posted on Chinese technology forums](https://blog.csdn.net/hb_wxz?type=blog)
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
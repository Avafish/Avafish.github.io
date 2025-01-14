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

Welcome to Zewen Long's Personal Homepage!

I am a master student at [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/) (expected to graduate in June 2025). Additionally, I am a member at [Center for Research on Intelligent Perception and Computing (CRIPAC)](http://cripac.ia.ac.cn/en/EN/volumn/home.shtml), National Laboratory of Pattern Recognition (NLPR). I am fortunate to be advised by Professor [Shu Wu](https://people.ucas.ac.cn/~shuwu?language=en).

My research interests lie in the field of Recommender Systems, with a focus on sequential recommendation. Currently, I am highly intrigued by exploring the intersection of Large Language Models (LLMs) and AI safety.

# 🔥 News
- *2024.10*: &nbsp;📢 Our paper "Playing Language Game with LLMs Leads to Jailbreaking" has been submitted to ICLR 2025!
- *2024.08*: &nbsp;📢 Our paper "GOT4Rec: Graph of Thoughts for Sequential Recommendation" has been submitted to AAAI 2025!
- *2023.08*: &nbsp;🎉 Our paper "Personalized Interest Sustainability Modeling for Sequential POI Recommendation" has been accepted by CIKM 2023!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 Submission</div><img src='images/iclr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Playing Language Game with LLMs Leads to Jailbreaking

Yu Peng<sup>\*</sup>, **Zewen Long<sup>\*</sup>**, Fangming Dong, Congyi Li, Shu Wu, Kai Chen

**Submission to The Thirteenth International Conference on Learning Representations (ICLR 2025).**

We discover a novel jailbreak attack method to exploit large language models (LLMs) by playing custom-designed language games. This method circumvents LLM safety alignments, showcasing the vulnerability of current safety protocols.

[[PDF]](pdfs/Jailbreak.pdf) [[Code]](https://anonymous.4open.science/r/encode_jailbreaking_anonymous-B4C4)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025 Submission</div><img src='images/aaai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

GOT4Rec: Graph of Thoughts for Sequential Recommendation

**Zewen Long**, Liang Wang, Shu Wu, Qiang Liu, Liang Wang

**Submission to The 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025).**

We propose the GOT4Rec model, which first utilizes the graph of thoughts (GoT) prompting strategy in the sequential recommendation domain to capture three key types of information contained within user history sequences: short-term interests, long-term interests and collaborative information from other users.

[[PDF]](pdfs/GOT4Rec.pdf) [[Code]](https://anonymous.4open.science/r/GOT4Rec-ED99)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2023</div><img src='images/cikm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Personalized Interest Sustainability Modeling for Sequential POI Recommendation](https://dl.acm.org/doi/abs/10.1145/3583780.3615278)

**Zewen Long<sup>\*</sup>**, Liang Wang<sup>\*</sup>, Qiang Liu, Shu Wu

**Accepted by The 32nd ACM International Conference on Information and Knowledge Management (CIKM 2023).**

We propose a personalized interest sustainability model for sequential POI recommendation (INSPIRE) to capture whether each user's interest in specific POIs will sustain beyond the training time, aiding in more accurate and sustainable recommendations.

[[PDF]](https://dl.acm.org/doi/pdf/10.1145/3583780.3615278)

</div>
</div>



# 📖 Educations
- *2022.09 - now*, M.S. in Computer Application Technology, Institute of Automation, Chinese Academy of Sciences. Advisor: Prof. Shu Wu.

- *2018.09 - 2022.06*, B.E. in School of Cyber Security, University of Chinese Academy of Sciences. 

# 📅 Academic Services
- The Thirteenth International Conference on Learning Representations (ICLR 2025), Reviewer

# 📋 CV
[[PDF]](pdfs/Resume.pdf)
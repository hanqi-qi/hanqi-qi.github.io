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

✨ Hi everyone! I'm a PostDoc at [King's college London](https://kcl.ac.uk/), NLP Group,led by [Prof. Yulan He](https://sites.google.com/view/yulanhe), . I passed my PhD viva with no corrections after a great time in University of Warwick (2020.10-2024.04), advised by Prof. Yulan He and Dr. Lin Gui. I finished my M.S. at Peking University and my B.E. at Beihang University.
                
During Ph.D., I started my Causality Journey in visiting Prof. Kun Zhang affiliated with Causal Learning and Reasoning Group@CMU. Before Ph.D., I started my NLP journey in visiting professor Wenjie Li affiliated Natural Language Processing Group @PolyU Hong Kong.

# 🔥 News
<div style="border: 1px solid #ccc; padding: 10px; width: 100%; height: 150px; overflow: auto;">
09.2024: Three papers (1 first-author) are accepted by <strong>EMNLP24</strong> Main Conference.<br>
08.2024: I go to <strong>Bangkok</strong>, Thiland for ACL24. <br>
05.2024: Two papers (1 first-author) are accepted by <strong>ACL24</strong>, one in main conference, one in findings. <br>
04.2024: I pass the <strong>PhD viva with no correction</strong>. <br>
01.2024: I become a <strong>PostDoc at King's College London</strong>, NLP Group. <br>
01.2024: I finish my <strong>PhD thesis (draft)</strong> on the same of my birthday.<br>
01.2024: My first-author paper is finally accepted by TKDE. <br>
07.2023: I go to Hawaii, US to present our <strong>Neurips</strong> paper. <br>
07.2023: My first-author paper is accepted by Neurips (my neurips paper). <br>
02.2023: I go back to the UK from <strong>Abu Dhabi, UAE</strong>, finish my Machine Learning Learning trip in MBZUAI. <br>
02.2023: I attend the <strong>EMNLP23</strong> held in Abu Dhabi, to present our <strong>Computation Linguistics</strong> paper. <br>
01.2023: One paper is accepted by <strong>EACL23-findings</strong> (first time as a mentor for a master student). <br>
12.2022: Lionel Messi leads Argentina to win the World Cup championship. <br>
10.2022: I start to be a funded visit student in Machine Learning, Department at <strong>MBZUAI</strong>, Abu Dhabi, UAE, advised by Prof. <a href="https://www.andrew.cmu.edu/user/kunz1/"> Kun Zhang </a>.  <br>
08.2022: I go to <strong>Eindhoven</strong>, NetherLand to present our UAI paper. <br>
05.2022: My first-author paper is accepted by <strong>UAI23</strong> (my first ML paper)  <br>
05.2022: My first-author paper is accepted by <strong>UAI23</strong> (my first ML paper) <br>
05.2021: The first time! My first-author paper is accepted by <strong>ACL21 Oral</strong> A super encouragement in my early PhD career.<br>
10.2020: I start my PhD journey at University of Warwick. <br>
</div>

🚀 I am always open to new collaborations and engaging discussions. Feel free to reach out if you are interested in working together or just want to chat!

🔔 Last Update on Oct. 2024

<a href='[https://scholar.google.com/citations?user=YmWi1lgAAAAJ](https://scholar.google.com/citations?user=YmWi1lgAAAAJ)'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<div id="educations" markdown="1"> 
# 📖 Educations
</div>
- *2020.10 - 2024.04*, Ph.D., Th University of Warwick.
- *2017.09 - 2020.07*, Master, Peking University.
- *2013.09 - 2017.06*, Bachelor, Beihang University.

<div id="publications" markdown="1"> 
# 📝 Selected Publications
</div>

(* indicates equal contribution)

<!-- Filter Buttons -->
<div id="filter-container">
  <button class="filter-btn" onclick="filterPubs('all')">All</button>
  <button class="filter-btn" onclick="filterPubs('interpretability')">Interpretability</button>
  <button class="filter-btn" onclick="filterPubs('representation')">Representation</button>
  <button class="filter-btn" onclick="filterPubs('application')">Application</button>
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;">Encourage or Inhibit Monosemanticity? Revisit Monosemanticity from a Feature Decorrelation Perspective
</b>
\\
**H. Yan**, Y. Xiang, G Chen, Y. Wang, L. Gui, Y. He\\
**EMNLP24, main** |  [Paper](https://arxiv.org/abs/2406.17969)
<br>
<span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
<br>
  
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;"> Weak Reward Model Transforms Generative Models into Robust Causal Event Extraction Systems
</b>
\\
I. Silva, **H. Yan**, L. Gui, Y. He
**EMNLP24, main** |  [Paper](https://arxiv.org/abs/2312.09390) 
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;"> The Mystery and Fascination of LLMs: A Comprehensive Survey on the Interpretation and Analysis of Emergent Abilities
</b>
\\
Y. Zhou, J. Li, Y.Xiang, **H.Yan**, L. Gui, Y. He
**EMNLP24, main** |  [Paper](https://arxiv.org/abs/2311.00237) <br>
<span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  
<br>
</div>

<div class='paper-box-text' markdown="1">
<b style="color:#783F04;"> Counterfactual Generation with Identifiability Guarantee
</b>
\\
<strong>H. Yan</strong>, L. Kong, L. Gui, Y. Chi, Eric. Xing, Y. He, K. Zhang.
**Neurips23, main** |  [Paper](https://neurips.cc/virtual/2023/poster/71063) 
</div>








<!-- JavaScript for Filtering -->
<script>
function filterPubs(category) {
  var papers = document.getElementsByClassName('paper-box-text');
  if (category == 'all') category = '';
  
  // Loop through all publications
  for (var i = 0; i < papers.length; i++) {
    if (papers[i].className.indexOf(category) > -1) {
      papers[i].style.display = "block"; // Show if matches category
    } else {
      papers[i].style.display = "none";  // Hide if not
    }
  }
}
</script>



<div id="honors" markdown="1"> 
# 🎖 Honors and Awards
</div>

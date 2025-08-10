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

🚀 **Updates**: As an incoming assistant professor at King's College London (fall 2025), I am <span style="color:red"> **actively recruiting passionate PhDs and Master's students** </span> interested in interpretable and robust reasoning with language models. I will also be attending ICML 2025 and ACL 2025 in person. If you'd like to work with me, feel free to reach out. 

📷 **My Pictures:** [View gallery here]({{ "/my-pictures/" | relative_url }})

Hi everyone! I'm a PostDoc (01.2024-) at [King's College London](https://kcl.ac.uk/), NLP Group, School of Informatics. I passed my PhD viva with no corrections after a great time at the University of Warwick (10.2020-01.2024), advised by [Prof. Yulan He](https://sites.google.com/view/yulanhe) and [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me). I finished my M.S. at Peking University(09.2017-07.2020) and my B.E. at Beihang University(09.2013-06.2017).
                
During Ph.D., I started my Causality Journey(10.2022-02.2023) in visiting Prof. [Kun Zhang](https://www.andrew.cmu.edu/user/kunz1/) affiliated with the Causal Learning and Reasoning Group@CMU. Before Ph.D., I started my NLP journey(07.2019-10.2019) in visiting Prof. [Wenjie Li](https://www4.comp.polyu.edu.hk/~cswjli/) affiliated NLP Group @PolyU Hong Kong.


I’ve been incredibly lucky to have a number of amazing collaborators and mentors across KCL and a range of other institutions, including  [Carnegie Mellon University](https://www.cmu.edu/dietrich/philosophy/people/faculty/zhang.html), [MIT](https://yifeiwang77.com/), [Peking University](https://jingjingxu.com/), [MBZUAI](https://chengy12.github.io/), [Hong Kong Polytechnic University](https://scholar.google.com/citations?user=Rx5swD4AAAAJ&hl=en), [University College London](https://yanglinyi.github.io/),[University of Warwick](https://warwick.ac.uk/fac/sci/dcs/people/u1898418/). None of the research so far—would be possible without their kind help and support.



# 🔍 Research Summary

My research interests lie in the intersection of Machine Learning and Natural Language Processing, i.e., incorporating fundamental representation learning to enhance the **interpretability** and **reliability** of different NLP models, with 10 (co-)first-authored papers published at top-tier venues: 
- Mechanistic interpretability (neuron-level) in language models and multi-modal models [[**EMNLP24**](https://arxiv.org/pdf/2406.17969),[**NeurIPS24-RBMF**](https://asu-apg.github.io/rbfm/)]; self-explainable models with a conceptualised layer linking the input and decision layer [[**Computational Linguistics 22**](https://aclanthology.org/2022.cl-4.17/),[**TKDE24**](https://arxiv.org/abs/2305.05331)]. 
- Empirical and principled methods to enhance model robustness over various test inputs, e.g., position bias [[ACL24-findings](https://aclanthology.org/2024.findings-acl.386/),[**ACL21-oral**](https://aclanthology.org/2021.acl-long.261.pdf)],  distribution shifts [[**NeurIPS23**](https://proceedings.neurips.cc/paper_files/paper/2023/file/afda6bf3fb086eabbaf161ba1cec5a9a-Paper-Conference.pdf)] and 
representation inefficiency in transformer-based models [[**EMNLP24**](https://arxiv.org/pdf/2406.17969),[**EACL23-findings**](https://aclanthology.org/2023.findings-eacl.102/),[**UAI22-spotlight**](https://proceedings.mlr.press/v180/yan22b.html)]. 
- Understanding and enhancing LM's reasoning capabilities via injecting external knowledge[[**ACL21-oral**](https://arxiv.org/abs/2106.03518)][[**ACL25**](https://openreview.net/pdf?id=bOFGdbXdKV)], weak supervision [[EMNLP24](https://arxiv.org/abs/2406.18245)], applying a self-refinement mechanism for factual knowledge reasoning [[**ACL24**](https://aclanthology.org/2024.acl-long.382/)]. More recently focus in the two directions:
  - Science literature understanding, such as code generation for scientific paper replication on our own [SciReplicate-Bench](https://arxiv.org/abs/2504.00255) and novelty assessment.
  - Reasoning in latent space, such as a position paper at [**ICML25**](https://openreview.net/pdf?id=RrvhbxO2hd) about meta-reasoning, [CODI](https://arxiv.org/abs/2502.21074) in implicit CoT, in retrieved-based QA [[ACL25](https://arxiv.org/abs/2503.01606)], navigating search in latent space [[ICML25spotlight](https://openreview.net/pdf?id=Pp90xRxITT)] and sparse feature for preference optimization [[ICML25](https://arxiv.org/abs/2411.07618)].


# 🔥 News


<div style="width: 100%; height: 300px; overflow-y: scroll; border: 1px solid #ccc; padding: 10px;">
07.2025: I go to Vienna, Austria🇦🇹 to present our faithful rationale generation and RAG papers accepted at <strong>ACL 2025</strong>. 🏞️ Excited to escape city life and explore Gosau & Hallstatt! <br>
07.2025: I go to Vancouver, Canada🇨🇦 to present our LLM reasoning papers accepted at <strong>ICML 2025</strong>. 🍜 Can’t wait to revisit my favorite Chinese restaurant there! <br>
07.2025: 🔥 1*paper, SciReplicate-Bench, accepted by COLM25, a benchmark for paper replication via code generation. <br>
05.2025" 🔥 2*papers accepted by ACL25 main conference, including a co-first author paper in faithful rationale generation during LLM inference. <br>
05.2025: 🔥 3*papers accepted by ICML25, including a first-author paper about meta-reasoning in the Position paper track. <br>
11.2024: I go to Miami☀️🌊🍹🏝, US for EMNLP24 to present our accepted papers and connect with like-minded researchers👩‍💻👨‍💻.<br>
10.2024: 1*first-author paper about <strong>monosemantic neuron in multi-modal model</strong> is accepted by Neurips-RBMF workshop.<br>
09.2024: 3*papers (<strong>monomsemantic neurons</strong>, <strong>oral survey in ICL</strong>, <strong>weak2strong event extraction</strong>) are accepted by EMNLP24 Main Conference. 🎉<br> 
08.2024: I go to Bangkok, Thailand🇹🇭 for ACL24. ✈️ <br> 
06.2024: 2* paper accepted by ACL24, including 1 1st author in main and 1 in findings.  <br>
04.2024: I pass the PhD viva with no corrections 🎓. <br> 
01.2024: I become a PostDoc👩‍🏫 at King's College London, NLP Group. <br> 
01.2024: I finish my PhD thesis (draft) on the same day of my birthday.<br> 
01.2024: 1*first-author paper is finally accepted by TKDE.<br> 
12.2023: I go to New Orleans🎷, US to present our Neurips paper. <br>
07.2023: I go to Hawaii🌴, US to present our ICML-workshop paper. <br> 
07.2023: 1*first-author paper is accepted by Neurips (my Neurips paper).<br> 
02.2023: I go back to the UK from Abu Dhabi, UAE🇦🇪, finish my Machine Learning trip in MBZUAI. <br> 
02.2023: I attend the EMNLP23 held in Abu Dhabi, to present our Computational Linguistics paper. <br> 
01.2023: 1*paper is accepted by EACL23🇭🇷-findings (first time as a mentor for a master's student). <br> 
12.2022: Lionel Messi leads Argentina to win the ⚽️World Cup championship. <br> 
10.2022: I start to be a funded visiting student in Machine Learning, Department at MBZUAI🏫, Abu Dhabi, UAE, advised by Prof. Kun Zhang. <br>
08.2022: I go to Eindhoven, Netherlands🇳🇱 to present our UAI paper. <br> 
05.2022: 1*first-author paper is accepted by UAI23-spotlight (🥳my first ML paper) <br> 
05.2021: The first time to get paper accepted! 1*first-author paper is accepted by ACL21 🌟Oral. A super encouragement in my early PhD career. <br> 
10.2020: I start my PhD📚 journey at University of Warwick, UK🇬🇧. <br>
</div>


# 👩‍🏫 Professional Service

  - Co-Chair of the Asian Chapter of the Association for Computational Linguistics (Student Research Workshop) 2022
  - Organiser of Event - [PreTrain 2025: Spotlight on ACL/ICML/ICLR]((https://pretrain2025.github.io/index.html) at King's College London
  - Area Chair: ACL25, EMNLP25 
  - Reviewers:
    - NLP: AACL, NAACL, EACL, EMNLP, ACL, COLM25
    - AI/ML: UAI, AISTATS, NEURIPS, ICLR, ICML, AAAI26
    - Journal: NeuroComputing, TOIS, TMLR, Transactions on Big Data, Transactions on Artificial Intelligence.

# 💬 Invited Talks

- <strong> University of Southampton, Computer Science </strong>, 04/2025. LLM Reasoning with internal and controllable signals 
- <strong> University of Surrey, Computer Science </strong>, 04/2025. Controllable generation framework for LLM reasoning
- <strong> University of Bath, Computer Science </strong>, 04/2025. Disentanglement for interpretability and controllability
- <strong> University of Birmingham, Computer Science </strong>, 12/2024. Understanding and improving LLM reasoning via representation learning
- <strong> University of Sheffied, NLP Group</strong>, 12/2024. Robust and Interpretable NLP via representation learning and Path Ahead
- <strong> Huawei, LLM research team (Singapore)</strong>. Controllable generation and Causality in LLMs.
- <strong> Amazon, Artificial Generative Intelligence team (London& Cambridge)</strong>. Robust and Interpretable NLP via Representation Learning and Applications in LLMs.
- <strong> Fudan University, NLP Group</strong>, 07/2024. Representation Learning and Mechanistic Interpretability
- <strong> UC San Diego, NLP Group</strong>, 02/2024. Robust and Interpretable NLP via representation learning and Path Ahead
- <strong> Yale University, NLP Group</strong> 01/2024. Robust and Interpretable NLP via representation learning and Path Ahead
- <strong> Turing AI Fellowship Event</strong>, London, 03/2023, Distinguishability Calibration to In-Context Learning 
- <strong> UKRI Fellows Workshop</strong>, University of Edinburgh, 04/2022. Interpreting Long Documents and Recommendation Systems via Latent Variable Models


<div id="mentee" markdown="1">
# 💬 Mentee
- <strong> PhD students </strong>.\\
  - 2*scientific literature understanding (accepted by [COLM25](https://arxiv.org/abs/2504.00255) and in submission).
  - 2* explainable AI (language and multimodal model). (accepted by [ACL25](https://openreview.net/pdf?id=bOFGdbXdKV) and in submission)
  - 3* robust LLM reasoning (accepted by [ACL24-findings](https://arxiv.org/pdf/2402.15637v2)/[ACL25](https://arxiv.org/abs/2503.01606) and in [submission](https://arxiv.org/abs/2502.21074)).
  - 1* event extraction (accepted by [EMNLP24](https://arxiv.org/abs/2406.18245))
- <strong> Master students </strong>. \\
  - 1*rank efficiency in transformer representation (accepted by [EACL23-findings](https://aclanthology.org/2023.findings-eacl.102/)).
  - 5*explainable AI (cognition perspective).
</div>

<!--
<a href='[https://scholar.google.com/citations?user=YmWi1lgAAAAJ](https://scholar.google.com/citations?user=YmWi1lgAAAAJ)'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
-->

<!--
<div id="educations" markdown="1"> 
# 📖 Educations
</div>
- *2020.10 - 2024.04*, Ph.D., University of Warwick.
- *2017.09 - 2020.07*, Master, Peking University.
- *2013.09 - 2017.06*, Bachelor, Beihang University.
-->


# 📝 Publications 

(* indicates equal contribution)

<!-- Filter Buttons -->
<div id="filter-container">
  <button class="filter-btn" onclick="filterPubs('all')">All</button>
  <button class="filter-btn" onclick="filterPubs('interpretability')">Interpretability</button>
  <button class="filter-btn" onclick="filterPubs('representation')">Representation</button>
  <button class="filter-btn" onclick="filterPubs('causality')">Causality</button>
  <button class="filter-btn" onclick="filterPubs('application')">Application</button>
</div>

<div class="publication-list">
    <div class="paper-box-text application" markdown="1">
  <b style="color:#783F04;">Position: LLMs Need a Bayesian Meta-Reasoning Framework for More Robust and Generalizable Reasoning
  </b>
  \\
  **H. Yan**, L. Zhang, J. Li, Z. S, Y. He\\
  **ICML25, Position Track** | [Paper](https://kclpure.kcl.ac.uk/portal/en/publications/position-llms-need-a-bayesian-meta-reasoning-framework-for-more-r)
  <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Application</span> 
  <br>
  </div>

      <div class="paper-box-text application" markdown="1">
  <b style="color:#783F04;">Drift: Enhancing LLM Faithfulness in Rationale Generation via Dual-Reward Probabilistic Inference
  </b>
  \\
  J. Li, **H. Yan**, Y. He\\
  **ACL25, Main** | [Paper](https://openreview.net/pdf?id=bOFGdbXdKV)
  <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Application</span> <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>
  
  <br>
  </div>
  

  <div class="paper-box-text representation" markdown="1">
  <b style="color:#783F04;">Navigating Solution Spaces in Large Language Models through Controlled Embedding Exploration
  </b>
  \\
  Q. Zhu, R. Zhao. **H. Yan**, Y. He, Y. Chen, L. Gui\\
  **ICML25, Spotlight** | [Paper](https://openreview.net/pdf?id=Pp90xRxITT)
  <br>
<span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  <br>
  </div>

    <div class="paper-box-text representation" markdown="1">
  <b style="color:#783F04;">Direct preference optimization using sparse feature-level constraints
  </b>
  \\
  Q. Yin, C. Leong, H. Zhang, M. Zhu, **H. Yan**, Q. Zhang, Y. He, W. Li, J. Wang, Y. Zhang, L. Yang\\
  **ICML25** | [Paper](https://arxiv.org/abs/2411.07618)
  <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  <br>
  </div>
  

  
  <div class="paper-box-text interpretability representation application" markdown="1">
  <b style="color:#783F04;">Encourage or Inhibit Monosemanticity? Revisit Monosemanticity from a Feature Decorrelation Perspective
  </b>
  \\
  **H. Yan**, Y. Xiang, G Chen, Y. Wang, L. Gui, Y. He\\
  **EMNLP24, main** |  [Paper](https://arxiv.org/abs/2406.17969)
  <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  <br>
  </div>

  <div class="paper-box-text causality application" markdown="1">
  <b style="color:#783F04;"> Weak Reward Model Transforms Generative Models into Robust Causal Event Extraction Systems
  </b>
  \\
  I. Silva, **H. Yan**, L. Gui, Y. He\\
  **EMNLP24, main** |  [Paper](https://arxiv.org/abs/2312.09390) 
  <br>
  <span style="background-color: #f0f4d4; color: #000; padding: 2px 6px; border-radius: 4px;">Causality</span> <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class="paper-box-text interpretability" markdown="1">
  <b style="color:#783F04;"> The Mystery and Fascination of LLMs: A Comprehensive Survey on the Interpretation and Analysis of Emergent Abilities
  </b>
  \\
  Y. Zhou, J. Li, Y.Xiang, **H.Yan**, L. Gui, Y. He\\
  **EMNLP24, main** |  [Paper](https://arxiv.org/abs/2311.00237) <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  
  <br>
  </div>

  <div class="paper-box-text application" markdown="1">
  <b style="color:#783F04;"> Mirror: A Multiple-perspective Self-Reflection Method for Knowledge-rich Reasoning
  </b>
  \\
   <strong>H. Yan</strong>, Q. Zhu, X. Wang, L. Gui, Y. He\\
  **ACL24, main** |  [Paper](https://arxiv.org/abs/2311.00237) <br>
  <span style="background-color: #d4d4f0; color: #000; paddinsg: 2px 6px; border-radius: 4px;">application</span>  
  <br>
  </div>

  <div class="paper-box-text representation" markdown="1">
  <b style="color:#783F04;">Addressing Order Sensitivity of In-Context Demonstration Examples in Causal Language Models. 
  </b>
  \\
  Y. Xiang, **H. Yan**, L. Gui, Y. He\\
  **ACL24, findings** |  [Paper](https://arxiv.org/pdf/2402.15637) <br>
  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span> 
  <br>
  </div>
  

  <div class='paper-box-text representation causality application' markdown="1">
  <b style="color:#783F04;"> Counterfactual Generation with Identifiability Guarantee
  </b>
  \\
  <strong>H. Yan</strong>, L. Kong, L. Gui, Y. Chi, Eric. Xing, Y. He, K. Zhang\\
  **Neurips23, main** |  [Paper](https://neurips.cc/virtual/2023/poster/71063)<br>
  <span style="background-color: #f0f4d4; color: #000; padding: 2px 6px; border-radius: 4px;">Causality</span> <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class='paper-box-text interpretability application' markdown="1">
  <b style="color:#783F04;"> Explainable Recommender with Geometric Information Bottleneck
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui, M. Wang, K. Zhang and Y. He\\
  **TKDE** |  [Paper](https://arxiv.org/abs/2305.05331) <br>
    <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>  <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class='paper-box-text interpretability application' markdown="1">
  <b style="color:#783F04;"> Hierarchical Interpretation of Neural Text Classification
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui and Y. He \\
  **Computational Linguistics, Present at EMNLP23** |  [Paper](https://direct.mit.edu/coli/article/doi/10.1162/coli_a_00459/112768/Hierarchical-Interpretation-of-Neural-Text) <br>
  <span style="background-color: #d4f0f0; color: #000; padding: 2px 6px; border-radius: 4px;">Interpretability</span>   <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>

  <div class='paper-box-text representation' markdown="1">
  <b style="color:#783F04;"> Addressing Token Uniformity in Transformers via Singular Value Transformation
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui, W. Li and Y. He \\
  **UAI22, spotlight** |  [Paper](https://proceedings.mlr.press/v180/yan22b.html)<br>
  <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  </div>

  <div class='paper-box-text representation' markdown="1">
  <b style="color:#783F04;"> Distinguishability Calibration to In-Context Learning
  </b>
  \\
  H. Li, <strong>H. Yan</strong>, L. Gui, W. Li and Y. He \\
  **EACL23, findings** |  [Paper](https://arxiv.org/abs/2302.06198)<br>
   <span style="background-color: #f0d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">Representation</span>  
  </div>
  
  <div class='paper-box-text causality application' markdown="1">
  <b style="color:#783F04;"> A Knowledge-Aware Graph Model for Emotion Cause Extraction
  </b>
  \\
  <strong>H. Yan</strong>, L. Gui and Y. He \\
  **ACL21, Oral** |  [Paper](https://aclanthology.org/2021.acl-long.261.pdf)<br>
  <span style="background-color: #f0f4d4; color: #000; padding: 2px 6px; border-radius: 4px;">Causality</span> <span style="background-color: #d4d4f0; color: #000; padding: 2px 6px; border-radius: 4px;">application</span> 
  </div>
</div>


# 📝 Notes
<a href="https://docs.google.com/document/d/1P7ngYVELCz-wxz7u34KCVw67fGQlsUlx6fo2RfWAJmQ/edit?usp=sharing"> o1-technical report (notes for [video](https://www.bilibili.com/video/BV15Rx5eXEnW)) </a> <br>
<a href="https://docs.google.com/presentation/d/1choVI6HIOLpdAywFpWGFR8KMyex7-AhEhEzP_vTsF0Y/edit?usp=sharing"> Machine Unlearning via CausalLens and in NLP tasks</a> <br>
<a href="https://github.com/hanqi-qi/Large_language_modeling/blob/main/Reading_Material.md">Reading List For Large Language Model</a><br>
<a href="https://zhuanlan.zhihu.com/p/665841340">Identifiability101 in Causality (3rd PhD) </a> <br>
<a href="https://zhuanlan.zhihu.com/p/652269984">Induction Head_ contribute to In-context Learning (3rd PhD) </a><br>
<a href="https://github.com/hanqi-qi/NLPReadingGroup/blob/main/CausalInference/CausalInference_RS_hanqi.pdf">Recommendation with Causality (2nd PhD) </a><br>
<a href="https://drive.google.com/file/d/1WbJzgHoN0WOF9Ul4cA5BrG9jDtT0DG1B/view">Causality101 (Feb 2022, 2nd PhD) </a> <br>
<a href="https://drive.google.com/file/d/1uTS3FcM2ouBbusyKwmpi0YMKm2qOOmqi/view"> Explaining Neural Networks (Oct 2020 1st PhD) </a><br>


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

<!-- Basic Styling for Buttons and Papers -->
<style>
  .filter-btn {
    background-color: #ddd;
    border: none;
    padding: 8px 16px;
    margin-right: 5px;
    cursor: pointer;
    border-radius: 5px;
  }

  .filter-btn:hover {
    background-color: #ccc;
  }

  .publication-list {
    margin-top: 20px;
  }

  .paper-box-text {
    margin-bottom: 5px;
    padding: 5px;
    border: 0px solid #ccc;
    border-radius: 0px;
    display: block;
}

</style>

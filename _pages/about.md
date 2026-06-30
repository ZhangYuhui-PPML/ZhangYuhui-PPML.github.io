---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I an an Associate Professor at [the State Key Laboratory of Cyberspace Security Defense](https://sklois.cn/), [Institute of Information Engineering, Chinese Academy of Sciences (CAS)](https://www.iie.ac.cn/). 


I recently received my Ph.D. from Institute of Information Engineering, Chinese Academy of Sciences (CAS). I was advised by [Rui Hou](http://hourui-arch.net/). 

Research Interests
======
- Privacy-preserving Inference for Large Language Models (LLMs)
- Federated Learning
- Confidential Computing
- Ransomware attack detection

Selected Publications
======
{% assign featured_publications = "swiftfl,cryptpeft,erw-radar,specfl,comet-llm-private-inference,tpds-speculative-federated-tree" | split: "," %}

<div class="publications publications--featured">
  <ul class="pub-list">
    {% for slug in featured_publications %}
      {% assign post = site.publications | where: "slug", slug | first %}
      {% if post %}
        {% include publication-item.html post=post %}
      {% endif %}
    {% endfor %}
  </ul>
  <div class="pub-more"><a href="/publications/">Browse the full list →</a></div>
</div>

Projects
======
- **Principal Investigator (PI)** for two NSFC programs: the Youth Program and the Special Program for Macro-control.
- **Core contributor** for two major national research initiatives: the National Key R&D Program of China and the CAS Strategic Priority Research Program. 


Activity and Services
------
PACT Artifact Evaluation Committee, PACT 2023.    
TPC Member for ICA3PP 2025.    
TPC Member for ICPADS 2025.

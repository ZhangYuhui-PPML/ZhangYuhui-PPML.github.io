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
{% assign featured_slugs = "swiftfl,cryptpeft,erw-radar,specfl,comet-llm-private-inference,tpds-speculative-federated-tree" | split: "," %}
{% assign featured_posts = '' | split: '' %}

{% for slug in featured_slugs %}
  {% assign post = site.publications | where: "slug", slug | first %}
  {% if post %}
    {% assign featured_posts = featured_posts | push: post %}
  {% endif %}
{% endfor %}

{% assign featured_posts = featured_posts | sort: "date" | reverse %}

<div class="publications publications--featured">
  <ul class="pub-list">
    {% for post in featured_posts %}
      {% include publication-item.html post=post %}
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

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!-- {% assign total_items = site.publications.size %}
{% for post in site.publications reversed %}
    {% assign index = total_items | minus: forloop.index0 %} 
  <p>{{ index }}.     {% assign citation_parts = post.citation | split: ', ' %}
  {% for part in citation_parts %}
    {% if part contains "Chengpeng Hu" %}
      {% if part contains "and Chengpeng Hu" %}
        {% assign authors = part | split: ' and ' %}
        {% for author in authors %}
          {% if author == "Chengpeng Hu" %}
            <strong>{{ author }}</strong>{% unless forloop.last %}, {% endunless %}
          {% else %}
            {{ author }}{% unless forloop.last %}, {% endunless %}
          {% endif %}
        {% endfor %}
      {% else %}
        <strong>{{ part }}</strong>{% unless forloop.last %}, {% endunless %}
      {% endif %}
    {% else %}
      {{ part }}{% unless forloop.last %}, {% endunless %}
    {% endif %}
  {% endfor %} 
  {% if post.paperurl %}
  <a  href="{{ post.paperurl }}"><u>[pdf]</u></a>
        {% else %}
      {% endif %}
  
  </p>
{% endfor %} -->
<p><sup>*</sup> equal contribution.</p>
<!-- <p>9. <b>Chengpeng Hu</b>, Ziming Wang, Jialin Liu and Xin Yao. “Dynamic material handling through adaptive constrained
evolutionary learning”, 2023 (on-going). </p> -->


<p>10. <b>Chengpeng Hu</b><sup>*</sup>, Yunlong Zhao<sup>*</sup>, Jialin Liu. “Game generation via large language models”, in IEEE Conference on Games, 2024, pp. 1-4.
</p>

<p>9. Shiying Hu<sup>*</sup>, Zengrong Huang<sup>*</sup>, <b>Chengpeng Hu</b>, Jialin Liu. “3D building generation in Minecraft via large language models”, in IEEE Conference on Games, 2024, pp. 1-4.
</p>

<p>8. <b>Chengpeng Hu</b>, Yunlong Zhao, Ziqi Wang, Haocheng Du, Jialin Liu. "Games for artificial intelligence research: A
review and perspectives", IEEE Transactions on Artificial Intelligence, 2024 (accepted).
<a href='https://arxiv.org/pdf/2304.13269.pdf'>[pdf]</a>
</p>

<p>7. Ziqi Wang, <b>Chengpeng Hu</b>, Jialin Liu, Xin Yao. . "Negatively correlated ensemble reinforcement learning for online
diverse game level generatio", in International Conference on Learning Representations, 2024.
<a href='https://arxiv.org/pdf/2304.13269.pdf'>[pdf]</a>
</p>

<p>6. Yunlong Zhao<sup>*</sup>, <b>Chengpeng Hu<sup>*</sup></b>, Jialin Liu. "Playing with Monte-carlo tree search", IEEE Computational Intelligence Magazine, vol. 10, no. 1 pp. 85-86, 2024. 
<!-- <a href=>[pdf]</a> -->
</p>

<p>5. Shuo Huang, <b>Chengpeng Hu</b>, Julian Togelius, Jialin Liu. "Generating redstone style cities in Minecraft", IEEE
Conference on Games, 2023, pp. 1-4.  
<a href='https://arxiv.org/pdf/2307.09777.pdf'>[pdf]</a>
</p>



<p>4. <b>Chengpeng Hu</b>, Ziming Wang, Jialin Liu, Junyi Wen, Bifei Mao, Xin Yao. "Constrained reinforcement learning for
dynamic material handling", in 2023 International Joint Conference on Neural Networks (IJCNN), 2023, pp. 1-9, doi: 10.1109/IJCNN54540.2023.10191999.
<a href='https://arxiv.org/pdf/2305.13824.pdf'>[pdf]</a>
</p>

<p>3. <b>Chengpeng Hu</b>, Jiyuan Pei, Jialin Liu, Xin Yao. "Evolving constrained reinforcement learning policy", in 2023
International Joint Conference on Neural Networks (IJCNN), 2023, pp. 1-8, doi: 10.1109/IJCNN54540.2023.10191982.
<a href='https://arxiv.org/pdf/2304.09869.pdf'>[pdf]</a>
 </p>
 
<p>2. <b>Chengpeng Hu</b>, Ziqi Wang, Tianye Shu, Hao Tong, Julian Togelius, Xin Yao, Jialin Liu. "Reinforcement learning
with dual-Observation for general video game playing". IEEE Transactions on Games, vol. 15, no. 2, pp. 202-216, 2023. 
<a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9748033'>[pdf]</a>
</p>
<!-- <p>2.  Hao Tong, Qingquan Zhang, <b>Chengpeng Hu</b>, Xudong Feng, Feng Wu and Jialin Liu. “Simpler is sometimes better:
A dynamic aero-engine calibration study”, in 2022 International Conference on Sensing and Imaging (ICSI).
Springer, Cham, pp. 343-352, 2022.</p> -->
<p>1. Jiyuan Pei, <b>Chengpeng Hu</b>, Jialin Liu, Yi Mei and Xin Yao. "Bi-objective splitting delivery VRP with loading
constraints and restricted access", in 2021 IEEE Symposium Series on Computational Intelligence (SSCI), 2021, pp. 1-9.   
<a href='https://aingames.cn/publication/pdffiles/SSCI2021_3L_SDVRP.pdf'>[pdf]</a>
 </p>
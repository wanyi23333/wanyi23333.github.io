---
layout: archive
title: " "
permalink: /research/
author_profile: true
---

<div style="text-align: center"> <h1>Research</h1> </div>

Primates represent classic dietary generalists in the class Mammalia, consuming a wide range of plant materials including high-quality foods like fruits and low-quality foods like mature leaves. In contrast to high-quality foods that are easily digestible and of high calorie, low-quality foods typically contain much fiber and thus require extra processing effort. Providing insights into the dietary flexibility of the primates, much attention has been devoted to understanding how primates meet nutritional demand with low-quality foods.</p>

The <strong>gut microbiome</strong> likely plays an active role in facilitating dietary plasticity of mammals including primates. Through fermentation, the gut microbiome transforms fibrous foods into the absorbable nutrient and energy. Aiming to reveal the unique trait that make primates dietary generalists, I have been studying the evolutionary and ecological force shaping the primate gut microbiome by using Japanese macaques as a model. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

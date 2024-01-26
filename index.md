---
title: Home
---

# Artificial neural networks for psychology, neuroscience, and climate change

The Lindsay Lab at New York University has two separate goals: 1.) advance the study of the brain by using artificial neural networks as models of biological information processing and 2.) advance the fight against climate change by applying machine learning and computer vision to real-world problems. 
  
<!-- {%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center} -->

{% include section.html full=true %}

{% include banner.html image="images/bannerNYU2.svg" %}

{% include section.html %}

# Research Directions

{% capture text %}
Attention is widely studied across psychology, neuroscience, and machine learning. To what extent do these different forms of attention relate to each other? Can we use models of attention in artificial neural networks to understand how attention enhances behavior in people? What can the connection between attention and learning in biology tell us about how to make machines learn better?

[Read "Attention in Psychology, Neuroscience, and Machine Learning"](https://www.frontiersin.org/articles/10.3389/fncom.2020.00029/full)
<!--[See what we've published &nbsp;→](research)-->
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo_attn.jpg"
  headline="Understanding Attention"
  text=text
%}

{% capture text %}
Neuroscientists use a variety of analysis methods to try to identify the features of neural activity that drive behavior. Are these tools capable of providing such insights? Artificial neural networks offer an ideal testing ground for the tools of neuroscience as they allow for full access to the neural activity responsible for behavior.   

[Read "Testing the Tools of Systems Neuroscience on Artificial Neural Networks"](https://arxiv.org/abs/2202.07035)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo_tools.jpg"
  headline="Investigating the Tools of Neuroscience"
  text=text
%}

{% capture text %}
Mitigating and adapting to climate change is the biggest challenge of our generation. Progress in many areas can be expedited through the use of artificial intelligence. The Lindsay Lab is particularly focused on analysis of remote sensing data.

[Learn more about why the lab works on climate change](https://lindsay-lab.github.io/2022/10/18/explaining-myself.html)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo_climate.jpg"
  headline="Machine Learning for Climate Change"
  text=text
%}

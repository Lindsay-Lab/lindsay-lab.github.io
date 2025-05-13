---
title: Team
nav:
  order: 1
  tooltip: About the lab
---

# <i class="fas fa-users"></i>Team

{%
  include feature.html
  image="favicons/share-thumbnail.jpg"
  link="team"
  title=""
  text="The Lindsay Lab started in Fall of 2022. See current and past lab members below. If you are interested in joining as a PhD student, please apply to either the [Center for Data Science PhD program](https://cds.nyu.edu/phd-admissions-req/) or the [Cognition and Perception PhD program in Psychology](https://as.nyu.edu/psychology/graduate/phd-cognition-perception.html). Potential postdocs or NYU Masters students interested in doing work in the lab can reach out to Grace directly. The lab is not accepting undergraduates or research assistants at this time." 
%}

{%
  include figure.html
  image="images/neurolab_edit.jpg"
  caption="Neuroscience side of the lab, 2025"
  width="400px"
%}

{%
  include figure.html
  image="images/climatelab_edit.jpg"
  caption="Climate Change side of the lab, 2025"
  width="400px"
%}

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters"
%}

# Lab Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni"
%}
{:.center}


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
  text="The Lindsay Lab started in Fall of 2022. See current and past lab members below. The lab can take PhD students through either the [Center for Data Science PhD program](https://cds.nyu.edu/phd-admissions-req/) or the [Cognition and Perception PhD program in Psychology](https://as.nyu.edu/psychology/graduate/phd-cognition-perception.html). **NOTE**: for the 2025/2026 application cycle we will only be looking for students through the CDS program. Potential postdocs or NYU Masters/undergraduate students interested in doing work in the lab can reach out to Grace directly (applicants should demonstrate relevant quantitative and coding skills). The lab is not hiring research assistants or taking high school students at this time." 
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

{%
  include figure.html
  image="images/neurolab_edit.jpg"
  caption="Neuroscience half of the lab, 2025"
  width="400px"
%} {%
  include figure.html
  image="images/climatelab_edit.jpg"
  caption="Climate Change half of the lab, 2025"
  width="400px"
%}


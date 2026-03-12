---
---
<h1 style="color: #003876; font-size: 2.2em; line-height: 1.3;">
  Decoding the Genome.<br>Transforming Patient Care.
</h1>

<p>
  <span style="color: #003876; font-weight: 700;">Laboratory for Precision Genome Medicine (PGM)</span>
  — we bridge fundamental discoveries in human genetics with clinical applications
  that improve diagnosis, treatment, and outcomes for individuals with disease.
</p>

<p>
  We integrate experimental (wet-lab) and computational (dry-lab)
  approaches to uncover the genetic mechanisms underlying human disease.
</p>

{% include section.html %}

## Recent News

{% for post in site.posts limit:3 %}
<div style="border-left: 4px solid #c8102e; padding-left: 1.2em; margin-bottom: 1.2em;">
  <strong style="color: #003876;">{{ post.date | date: "%Y-%m" }}</strong><br>
  {{ post.excerpt | strip_html | truncatewords: 30 }}
  <a href="{{ post.url }}">Read more →</a>
</div>
{% endfor %}

{%
  include button.html
  link="blog"
  text="See all news & updates"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Highlights
{% capture text %}
Integrating experimental and computational methods to uncover the genetic mechanisms of human disease.
{%
  include button.html
  link="research"
  text="See our research area"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/research.jpg"
  link="research"
  title="Our Research Approach"
  alt="Genomics and precision medicine research at PGM Lab"
  text=text
%}
{% capture text %}
Discover our latest publications and preprints in genetics, genomics, and bioinformatics. 
{%
  include button.html
  link="publication"
  text="Explore our publication lists"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/project.jpg"
  link="publication"
  title="Publications"
  alt="Scientific publications in genetics and bioinformatics from PGM Lab"
  flip=true
  style="bare"
  text=text
%}
{% capture text %}
Meet the researchers behind our work — and explore opportunities to join the lab.
{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}
{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Team Members"
  alt="Research team members of PGM Lab"
  text=text
%}

---

<div align="center" style="margin-top:2em;">
  <strong style="font-size:1.0em;">
    정밀 유전체 의학 연구실<br>
    Laboratory for Precision Genome Medicine (PGM Lab)
  </strong>
  <br>
  <br>
  <div style="font-size:0.95em;">
    PI | Principal Investigator<br>
    윤 지 훈<br>
    Jihoon G. Yoon, M.D., Ph.D.
  </div>
  <br>
  <div style="font-size:0.95em;">
    연세대학교 의과대학 진단검사의학과<br>
    Department of Laboratory Medicine, Yonsei University College of Medicine<br>
  </div>
  <br>
  <img src="/images/yonsei_logo.svg" alt="Yonsei University Logo" width="300" style="margin-top:1em;">
</div>



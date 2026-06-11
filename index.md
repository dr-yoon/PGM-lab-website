---
---
<h1 style="color: var(--primary); font-size: 2.2em; line-height: 1.3;">
  Decoding the Genome.<br>Transforming Patient Care.
</h1>

<p>
  <span style="color: var(--primary); font-weight: 700;">Laboratory for Precision Genome Medicine (PGM)</span>
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
<div style="border-left: 4px solid var(--accent); padding-left: 1.2em; margin-bottom: 1.2em;">
  <strong style="color: var(--primary);">{{ post.date | date: "%Y-%m" }}</strong><br>
  <a href="{{ post.url }}">{{ post.title }}</a>
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

<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap" rel="stylesheet">

<div align="center" style="margin-top:3em; padding:1em 1em 0;">
  <div style="width:46px; height:3px; border-radius:2px; margin:0 auto 22px; background:linear-gradient(90deg, var(--primary) 0 60%, var(--accent) 60% 100%);"></div>

  <div style="font-family:'Noto Sans KR', sans-serif; font-weight:700; color:var(--primary); font-size:1.35rem; letter-spacing:1px;">정밀 유전체 의학 연구실</div>
  <div style="font-family:var(--heading); font-weight:600; color:var(--text); margin-top:6px; letter-spacing:.3px;">Laboratory for Precision Genome Medicine (PGM&nbsp;Lab)</div>

  <div style="width:60px; height:1px; background:var(--light-gray); margin:24px auto;"></div>

  <div style="text-transform:uppercase; letter-spacing:2px; font-size:.7rem; font-weight:700; color:var(--accent); margin-bottom:6px;">Principal Investigator</div>
  <div style="font-family:'Noto Sans KR', sans-serif; font-weight:500; color:var(--text); font-size:1.05rem; letter-spacing:3px;">윤 지 훈</div>
  <div style="color:var(--primary); font-weight:600; margin-top:2px;">Jihoon G. Yoon, M.D., Ph.D.</div>

  <div style="color:var(--gray); font-size:.9rem; margin-top:18px; line-height:1.7;">
    <span style="font-family:'Noto Sans KR', sans-serif;">연세대학교 의과대학 진단검사의학과</span><br>
    Department of Laboratory Medicine, Yonsei University College of Medicine
  </div>

  <div><img src="/images/yonsei_logo.svg" alt="Yonsei University Logo" style="height:54px; width:auto; margin-top:26px; opacity:.92;"></div>
</div>



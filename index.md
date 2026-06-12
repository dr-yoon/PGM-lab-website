---
---
<div style="position:relative; overflow:hidden; border-radius:14px; padding:72px 32px; margin:6px 0 10px; text-align:center; background:linear-gradient(135deg, var(--background) 0%, var(--background-alt) 55%, color-mix(in srgb, var(--primary) 12%, var(--background)) 100%); border:1px solid var(--light-gray); box-shadow:0 6px 30px rgba(0,40,80,.07);">

  <div style="text-transform:uppercase; letter-spacing:3px; font-size:.72rem; font-weight:700; color:var(--gray); margin-bottom:12px;">Precision Genome Medicine</div>

  <h1 style="color: var(--primary); font-size: 2.2em; line-height: 1.3; margin:0 0 .4em;">
    Decoding the Genome.<br>Transforming Patient Care.
  </h1>

  <p style="max-width:680px; margin:0 auto;">
    We bridge fundamental discoveries in human genetics with clinical applications.
  </p>
</div>

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




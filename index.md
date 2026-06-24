---
---
<div style="position:relative; overflow:hidden; border-radius:14px; padding:72px 32px; margin:6px 0 10px; text-align:center; background:radial-gradient(40% 60% at 18% 22%, color-mix(in srgb, var(--primary) 22%, transparent) 0%, transparent 60%), radial-gradient(45% 55% at 85% 8%, color-mix(in srgb, var(--accent) 16%, transparent) 0%, transparent 55%), radial-gradient(55% 65% at 80% 95%, color-mix(in srgb, var(--secondary) 30%, transparent) 0%, transparent 55%), var(--background-alt); border:1px solid var(--light-gray); box-shadow:0 6px 30px rgba(0,40,80,.07);">

  <div style="text-transform:uppercase; letter-spacing:3px; font-size:.72rem; font-weight:700; color:var(--gray); margin-bottom:12px;">Precision Genome Medicine</div>

  <h1 style="color: var(--primary); font-size: 2.2em; line-height: 1.3; margin:0 0 .4em;">
    Decoding the Genome.<br>Transforming Patient Care.
  </h1>

  <p style="max-width:680px; margin:0 auto;">
    We bridge fundamental discoveries in human genetics with clinical applications.
  </p>
</div>

<div style="margin:14px 0 6px; border-radius:14px; overflow:hidden; border:1px solid var(--light-gray); box-shadow:0 6px 30px rgba(0,40,80,.07);">
  <img src="{{ "images/pgmlab.jpg" | relative_url }}" alt="PGM Lab Main"
       loading="lazy" style="display:block; width:100%; height:auto;">
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

<div class="hl-cards">
  <a class="hl-card" href="{{ "research" | relative_url }}">
    <div class="hl-imgw"><img src="{{ "images/research.jpg" | relative_url }}" alt="Our Research Approach" loading="lazy"></div>
    <div class="hl-body">
      <h3>Our Research Approach</h3>
      <p>Integrating experimental and computational methods to uncover the genetic mechanisms of human disease.</p>
      <span class="hl-arrow">See our research {% include icon.html icon="fa-solid fa-arrow-right" %}</span>
    </div>
  </a>
  <a class="hl-card" href="{{ "publication" | relative_url }}">
    <div class="hl-imgw"><img src="{{ "images/project.jpg" | relative_url }}" alt="Publications" loading="lazy"></div>
    <div class="hl-body">
      <h3>Publications</h3>
      <p>Discover our latest publications and preprints in genetics, genomics, and bioinformatics.</p>
      <span class="hl-arrow">Explore publications {% include icon.html icon="fa-solid fa-arrow-right" %}</span>
    </div>
  </a>
  <a class="hl-card" href="{{ "team" | relative_url }}">
    <div class="hl-imgw"><img src="{{ "images/team.jpg" | relative_url }}" alt="Team Members" loading="lazy"></div>
    <div class="hl-body">
      <h3>Team Members</h3>
      <p>Meet the researchers behind our work — and explore opportunities to join the lab.</p>
      <span class="hl-arrow">Meet our team {% include icon.html icon="fa-solid fa-arrow-right" %}</span>
    </div>
  </a>
</div>




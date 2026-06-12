---
title: Team
nav:
  order: 3
  tooltip: About our lab members
---

# {% include icon.html icon="fa-solid fa-users" %} Our members

Welcome to our newly established lab
We are building a collaborative research environment from the ground up, and we’re excited to grow our team.

{% include section.html %}

## Current Members

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and role != 'postdoc' and role != 'intern'" %}

{% include section.html %}

## Internship Members

{% include list.html data="members" component="portrait" filter="role == 'intern'" %}

{% include section.html %}

## Open Positions

<div class="positions">
  <div class="pos">
    <div class="ic">{% include icon.html icon="fa-solid fa-glasses" %}</div>
    <span class="pill">Full-time · Rolling</span>
    <h3>Postdoctoral Researcher</h3>
    <p>Lead projects at the intersection of human genetics and precision medicine, using wet-lab and/or computational approaches.</p>
    <ul>
      <li>PhD in molecular biology, genetics, or bioinformatics</li>
      <li>Expertise in molecular biology <em>or</em> bioinformatics</li>
      <li>First-author publication record</li>
    </ul>
    <a class="apply" href="mailto:YOONJH@yuhs.ac">{% include icon.html icon="fa-solid fa-paper-plane" %} Apply</a>
  </div>

  <div class="pos">
    <div class="ic">{% include icon.html icon="fa-solid fa-microscope" %}</div>
    <span class="pill">Full-time</span>
    <h3>Research Assistant / Associate</h3>
    <p>Support wet-lab and computational projects, from sample preparation and sequencing to data analysis.</p>
    <ul>
      <li>BSc / MSc in life sciences or related field</li>
      <li>Hands-on lab or coding experience</li>
      <li>Detail-oriented and collaborative</li>
    </ul>
    <a class="apply" href="mailto:YOONJH@yuhs.ac">{% include icon.html icon="fa-solid fa-paper-plane" %} Apply</a>
  </div>

  <div class="pos">
    <div class="ic">{% include icon.html icon="fa-solid fa-binoculars" %}</div>
    <span class="pill">Part-time / Full-time</span>
    <h3>Student Internship</h3>
    <p>A hands-on rotation for undergraduate and graduate students curious about genomics and precision medicine.</p>
    <ul>
      <li>Currently enrolled student</li>
      <li>Interest in genetics / genomics</li>
      <li>Flexible commitment</li>
    </ul>
    <a class="apply" href="mailto:YOONJH@yuhs.ac">{% include icon.html icon="fa-solid fa-paper-plane" %} Apply</a>
  </div>
</div>

<div class="applynote">
  Interested? Send your <strong>CV</strong> and a brief statement of interest to <a href="mailto:YOONJH@yuhs.ac">YOONJH[at]yuhs[dot]ac</a>.
</div>

{% include section.html %}

<div align="center" style="padding:1em 1em 0;">
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

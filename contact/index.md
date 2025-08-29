---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you have any question, please contact through

{%
  include button.html
  type="email"
  text="YOONJH@yuhs.ac"
  link="YOONJH@yuhs.ac"
%}
{%
  include button.html
  type="phone"
  text="(02)2019-3781"
  link="+82-2-2019-3781"
%}
{%
  include button.html
  type="address"
  tooltip="강남세브란스병원 비자검진센터 6"
  link="https://www.google.com/maps/place/%EA%B0%95%EB%82%A8%EC%84%B8%EB%B8%8C%EB%9E%80%EC%8A%A4%EB%B3%91%EC%9B%90+%EB%B9%84%EC%9E%90%EA%B2%80%EC%A7%84%EC%84%BC%ED%84%B0/data=!3m1!4b1!4m6!3m5!1s0x357ca7a87da3729d:0x7b761fbe68a493aa!8m2!3d37.4937778!4d127.0442841!16s%2Fg%2F11fl9dsld3?entry=ttu&g_ep=EgoyMDI1MDgyNS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/map.png"
  caption="Lab location"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

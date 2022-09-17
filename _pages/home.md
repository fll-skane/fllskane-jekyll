---
title: Välkommen till FIRST LEGO League Skåne!
layout: splash
permalink: "/"
excerpt: En förening med syfte att befästa barn och ungdomars nyfikenhet kring problemlösning,
  programmering, teknik och laganda.
header:
  overlay_image: "/uploads/laktaren.jpg"
  xactions:
  - label: Bli medlem
    url: "/bli-medlem"
feature_row:
- title: Stötta som domare
  excerpt: Vill du skapa en minnesvärd dag för barn och unga som brinner för innovation
    och teknik?
  image_path: "/uploads/fll19-7.jpg"
  alt: Sötta som domare
  url: "/bli-jurymedlem/"
  btn_class: btn--primary
  btn_label: Läs om att vara domare
- title: Stötta som funktionär
  excerpt: Känner du någon som kan hjälpa oss med genomförandet av årets regionfinal?
  image_path: "/uploads/fll19-73-2.jpg"
  alt: Stötta som funktionär
  url: "/bli-funktionar/"
  btn_class: btn--primary
  btn_label: Anmäl ditt intresse
- title: Stötta som partner
  excerpt: Vill du också vara med och stötta framtidens ingenjörer?
  image_path: "/uploads/fll19-85.jpg"
  alt: Stötta som partner
  url: "/bli-partner/"
  btn_class: btn--primary
  btn_label: Läs om att bli partner

---
{% include countdown.html %}

[Teaser]

{% include feature_row %}

## Nyheter

<div class="posts">
{% for post in site.posts limit:4 %} 
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>

## Våra samarbetspartners

![](/uploads/sponsorer.png)
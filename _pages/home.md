---
layout: splash
permalink: "/"
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: https://image.freepik.com/free-vector/abstract-colorful-fun-background_1115-2340.jpg
  actions:
  - label: Bli medlem
    url: "/bli-medlem"
excerpt: En förening med syfte att befästa barn och ungdomars nyfikenhet kring problemlösning,
  programmering, teknik och laganda.
feature_row:
- image_path: "/uploads/fll19-73-2.jpg"
  alt: lag
  title: För lag/lagledare
  excerpt: Hjälp till dig som lagledare
  url: "/for-lag-lagledare"
  btn_class: btn--primary
  btn_label: Läs mer
- image_path: "/uploads/fll19-85.jpg"
  alt: partners
  title: För partners / partnerskap
  excerpt: ''
  url: "/#/"
  btn_class: btn--primary
  btn_label: Läs mer
- image_path: "/uploads/fll19-7.jpg"
  alt: jury-voluntär
  title: För jury/voluntär
  excerpt: ''
  url: "/#/"
  btn_class: btn--primary
  btn_label: Läs mer

---
**Välkommen till FIRST LEGO League Skåne!**

Välkommen till vår hemsida! Just nu är det inte mycket information här, men i takt med att snön smälter och träden blomstrar, så kommer även det att växa fram något här också.

***

{% include feature_row %}

**Nyheter**

{% for post in site.posts limit:3 %} {% include archive-single.html type="grid" %} {% endfor %}
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
  excerpt: Är du lagledare som vill veta mer? Här hittar du länkar, tips och viktiga
    datum.
  url: "/_pages/for-lag-lagledare"
  btn_class: btn--primary
  btn_label: Läs mer
- image_path: "/uploads/fll19-85.jpg"
  alt: partners
  title: För partners/partnerskap
  excerpt: Vill du också vara med och stötta framtidens ingenjörer?
  url: "/bli-partner/"
  btn_class: btn--primary
  btn_label: Läs mer
- image_path: "/uploads/fll19-7.jpg"
  alt: jury-volontar
  title: För jury/volontär
  excerpt: ''
  url: "/#/"
  btn_class: btn--primary
  btn_label: Läs mer

---
**Välkommen till FIRST LEGO League Skåne!**

***

{% include feature_row %}

**Nyheter**

{% for post in site.posts limit:3 %} {% include archive-single.html type="grid" %} {% endfor %}

***

### **Partners**

* ARM
* Axis Communications
* Tetra Pak
* ustwo
* Malmö stad
* Region Skåne
* Skolverket
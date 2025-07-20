---
layout: page
title: Publications
permalink: /publications/
toc:
  sidebar: left
nav: true
nav_order: 2
---

### Journal Papers
<div class="publications">
{% bibliography --query @article %}
</div>

### Conference Papers
<div class="publications">
{% bibliography --query @inproceedings || @conference %}
</div>

<!-- ### Books -->
<!-- <div class="publications"> -->
<!-- {% bibliography --query @book %} -->
<!-- </div> -->
<!---->
<!-- ### Book Chapters -->
<!-- <div class="publications"> -->
<!-- {% bibliography --query @incollection || @inbook %} -->
<!-- </div> -->
<!---->
<!-- ### Preprints -->
<!-- <div class="publications"> -->
<!-- {% bibliography --query @unpublished || @misc %} -->
<!-- </div> -->
<!---->
<!-- ### Technical Reports -->
<!-- <div class="publications"> -->
<!-- {% bibliography --query @techreport %} -->
<!-- </div> -->
<!---->
### Theses
<div class="publications">
{% bibliography --query @phdthesis || @mastersthesis %}
</div>

<!-- ### Workshop Papers -->
<!-- <div class="publications"> -->
<!-- {% bibliography --query @workshop %} -->
<!-- </div> -->
<!---->
<!-- ### Patents -->
<!-- <div class="publications"> -->
<!-- {% bibliography --query @patent %} -->
<!-- </div> -->
<!---->
<!-- ### Software -->
<!-- <div class="publications"> -->
<!-- {% bibliography --query @software || @misc[software=true] %} -->
<!-- </div> -->

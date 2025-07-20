---
layout: page
title: Publications
permalink: /publications/
toc:
  sidebar: left
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

### Journal Papers
<div class="publications">
{% bibliography --query @article %}
</div>

### Conference Papers
<div class="publications">
{% bibliography --query @inproceedings %}
</div>

### Books
<div class="publications">
{% bibliography --query @book %}
</div>

### Book Chapters
<div class="publications">
{% bibliography --query @incollection %}
</div>

### Theses
<div class="publications">
{% bibliography --query @phdthesis || @mastersthesis %}
</div>

### Preprints
<div class="publications">
{% bibliography --query @unpublished || @misc %}
</div>

---
layout: default
blocks:
  - title: bob
    para: bob
    pic: bob
    pic-des: bob
  - title: bob
    para: bob
    pic: bob
    pic-des: bob
---


<header>
  <h1 class="editable">scooter</h1>
</header>

<section class="grid">
  {% for block in page.blocks %}
  <div class="col-6 text-sec">
    <h2>{{block.title}}</h2>
    <p>{{block.para}}.</p>
  </div>
  <div class="col-6 grad-1">
    <img src="{{block.pic}}" alt="{{block.pic-des}}">
  </div>
  {% endfor %}
</section>


<footer>
  <h2>
    <p>copyright stuff</p>
  </h2>
</footer>
s

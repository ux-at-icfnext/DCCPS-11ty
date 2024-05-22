---
layout: layouts/base
---
{% include 'patterns/breadcrumb/breadcrumb.md' %}

<div class="grid-row grid-gap">
  <div class="tablet:grid-col-3">{% include 'patterns/sidenav/sidenav.html' %}</div>
  <div class="tablet:grid-col-fill usa-prose">
    <h1> {{ title  | capitalize }}</h1>
    {{ content }}
  </div>
</div>
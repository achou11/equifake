---
layout: base
title: "Getting Started"
permalink: /
---

{% for prop in site.props %}
  <div id="interest-{{ prop.index }}" class="interest">
    {{ prop.interest }} - {{ prop.question}}
  </div>
  <div id="prop-{{ prop.index }}" class="prop">
    <p>Congratulations. You were likely exposed to Russian propaganda on Facebook! {{ prop.interest }} was viewed {{ prop.views }} from 2015 until August of this year.</p>
    <p>Russia uses propaganda to divide Americans on contentious social issues. They capitalize on outrage and hot button issues to push Americans further to the extremes, further poisoning our discourse.</p>
    <p>What’s the best defense against propaganda? Exposure. Let your friends and family know that you’ve been exposed. Share {{ site.title }} on Twitter and Facebook.</p>
  </div>
{% endfor %}
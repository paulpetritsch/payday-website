---
layout: default
title: "Datenschutzerklärung | PayDay"
permalink: /privacy/
---

<div class="px-4 pt-32 pb-32">
  <div class="max-w-3xl mx-auto break-words">
    <h1 class="text-3xl font-semibold font-display mb-4">
      {{site.data.textblocks.pages.privacy.headline}}
    </h1>
    {% for section in site.data.textblocks.pages.privacy.sections %}
    <h2 class="text-2xl font-semibold mt-6 mb-2">{{ section.number }} {{ section.title }}</h2>
    {% if section.text %}
      <p class="mb-4">{{ section.text }}</p>
    {% endif %}
    {% if section.subsections %}
      {% for sub in section.subsections %}
        <h3 class="text-xl font-semibold mt-4 mb-1">{{ sub.number }} {{ sub.title }}</h3>
        {% if sub.text %}
          <p class="mb-4">{{ sub.text }}</p>
        {% endif %}
        {% if sub.subsections %}
          {% for subsub in sub.subsections %}
            <h4 class="text-lg font-semibold mt-2 mb-1">{{ subsub.number }} {{ subsub.title }}</h4>
            <p class="mb-4">{{ subsub.text }}</p>
          {% endfor %}
        {% endif %}
      {% endfor %}
    {% endif %}
  {% endfor %}
  </div>
</div>
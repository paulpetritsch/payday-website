---
layout: default
title: Payday Home
permalink: /
key: home
---

<div class="px-4 h-screen">
  <div class="flex flex-col md:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
        <!-- Text Content -->
        <div class="w-full md:w-1/2 flex flex-col items-start justify-center">
            <div class="flex mb-2 items-center">
              {% for subimage in site.data.textblocks.pages.home.hero_subimages %}
              <div class="w-8 h-8 rounded-full overflow-hidden bg-{{ subimage.color }} -mr-2 -z-[{{forloop.index}}] opacity-0 {% if forloop.index == 1 %} animate-fadein-100
              {% elsif forloop.index == 2 %} animate-fadein-200
              {% elsif forloop.index == 3 %} animate-fadein-300
              {% endif %}">
                <img src="{{ subimage.image }}" alt="{{ site.data.textblocks.pages.home.hero_preheadline | escape }}" class="w-auto h-full object-cover mx-auto">
              </div>
              {% endfor %}
              <span class="ml-4 opacity-0 animate-fadein-400">{{site.data.textblocks.pages.home.hero_preheadline}}</span>
            </div>
            <h2 class="text-7xl font-bold font-display mb-4 opacity-0 animate-fadein-500">{{ site.data.textblocks.pages.home.hero_headline }}</h2>
            <div class="text-2xl font-display mb-4 opacity-0 animate-fadein-600">
                {{ site.data.textblocks.pages.home.hero_subheadline }}
            </div>
            <a href="{{site.data.textblocks.pages.home.hero_button_link}}" class="bg-black hover:bg-pink-100 transition-colors duration-200 text-white px-4 py-3 rounded-xl opacity-0 animate-fadein-700">{{ site.data.textblocks.pages.home.hero_button_text }}</a>
        </div>
        <!-- Image -->
        <div class="w-full md:w-1/2 flex justify-center relative items-center">
          <div class="relative">
            <img src="{{ site.data.textblocks.pages.home.hero_image1 }}" alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
                class="max-h-128 object-contain w-full opacity-0 animate-fadein-400">
            <span
                    class="flex items-center px-4 py-2 rounded-full text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.home.hero_tag1.color }} absolute -bottom-8 -right-1 opacity-0 animate-fadedown-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.home.hero_tag1.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.home.hero_tag1.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.home.hero_tag1.text }}</span>
                </span>
          </div>
          <div class="relative">
            <img src="{{ site.data.textblocks.pages.home.hero_image2 }}" alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
              class="max-h-128 object-contain w-full  opacity-0 animate-fadein-500">
            <img src="{{ site.data.textblocks.pages.home.hero_image3 }}" alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
              class="max-h-128 object-contain w-full opacity-0 animate-fadein-600">
              <span
                    class="flex items-center px-4 py-2 rounded-full text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.home.hero_tag2.color }} absolute -bottom-8 -left-1 opacity-0 animate-fadein-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.home.hero_tag2.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.home.hero_tag2.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.home.hero_tag2.text }}</span>
                </span>
          </div>
        </div>
    </div>
  </div>

  {% assign home1 = site.data.textblocks.sections.image_quote.home1 %}
  {% include image-quote-text.html
    image=home1.image
    headline=home1.headline
    subheadline=home1.subheadline
    text=home1.text
    button_text=home1.button_text
    button_link=home1.button_link
    left=home1.left
    tags=home1.tags
  %}
  {% include steps.html %}
  {% assign home2 = site.data.textblocks.sections.image_quote.home2 %}
  {% include image-quote-text.html
    image=home2.image
    headline=home2.headline
    subheadline=home2.subheadline
    text=home2.text
    button_text=home2.button_text
    button_link=home2.button_link
    left=home2.left
    tags=home2.tags
  %}
  {% include faqs.html %}
  {% assign home3 = site.data.textblocks.sections.image_quote.home3 %}
  {% include image-quote-text.html
    image=home3.image
    headline=home3.headline
    subheadline=home3.subheadline
    button_text=home3.button_text
    button_link=home3.button_link
    left=home3.left
    tags=home3.tags
  %}
  {% include blog-overview.html %}
  {% include newsletter.html %}
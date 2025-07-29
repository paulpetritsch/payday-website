---
layout: default
title: Ablauf & Vorteile
permalink: /process-benefits/
---


<div class="px-4 min-h-screen pt-32">
  <div class="flex flex-col md:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
        <!-- Text Content -->
        {% include sections/hero-text.html 
          headline=site.data.textblocks.pages.process_benefits.hero_headline
          subheadline=site.data.textblocks.pages.process_benefits.hero_subheadline
          preheadline=site.data.textblocks.pages.process_benefits.hero_preheadline
          button_text=site.data.textblocks.pages.process_benefits.hero_button_text
          button_link=site.data.textblocks.pages.process_benefits.hero_button_link
          images=site.data.textblocks.pages.process_benefits.hero_subimages
          text=site.data.textblocks.pages.process_benefits.hero_text
          %}
        <!-- Image -->
        <div class="w-full md:w-1/2 flex justify-center relative items-center">
          <div class="relative">
            <img src="{{ site.data.textblocks.pages.home.hero_image1 | relative_url }}" alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
                class="max-h-128 object-contain w-full opacity-0 animate-fadein-400">
            <span
                    class="flex items-center px-4 py-2 rounded-full text-sm md:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.home.hero_tag1.color }} absolute -bottom-8 -right-1 opacity-0 animate-fadedown-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.home.hero_tag1.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.home.hero_tag1.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.home.hero_tag1.text }}</span>
                </span>
          </div>
          <div class="relative">
            <img src="{{ site.data.textblocks.pages.home.hero_image2 | relative_url }}" alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
              class="max-h-128 object-contain w-full  opacity-0 animate-fadein-500">
            <img src="{{ site.data.textblocks.pages.home.hero_image3 | relative_url }}" alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
              class="max-h-128 object-contain w-full opacity-0 animate-fadein-600 pl-5">
              <span
                    class="flex items-center px-4 py-2 rounded-full text-sm md:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.home.hero_tag2.color }} absolute -bottom-8 left-4 opacity-0 animate-fadein-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.home.hero_tag2.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.home.hero_tag2.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.home.hero_tag2.text }}</span>
                </span>
          </div>
        </div>
    </div>
  </div>

  {% include sections/steps.html %}
  {% assign processbenefits1 = site.data.textblocks.sections.image_quote.home2 %}
  {% include sections/image-quote-text.html
    image=processbenefits1.image
    headline=processbenefits1.headline
    subheadline=processbenefits1.subheadline
    text=processbenefits1.text
    button_text=processbenefits1.button_text
    button_link=processbenefits1.button_link
    left=processbenefits1.left
    tags=processbenefits1.tags
    bg=processbenefits1.bg
    centered=processbenefits1.centered
  %}
  {% assign processbenefits2 = site.data.textblocks.sections.image_quote.processbenefits2 %}
  {% include sections/image-quote-text.html
    image=processbenefits2.image
    headline=processbenefits2.headline
    subheadline=processbenefits2.subheadline
    text=processbenefits2.text
    button_text=processbenefits2.button_text
    button_link=processbenefits2.button_link
    left=processbenefits2.left
    tags=processbenefits2.tags
  %}
  {% assign processbenefits3 = site.data.textblocks.sections.image_quote.processbenefits3 %}
  {% include sections/image-quote-text.html
    image=processbenefits3.image
    headline=processbenefits3.headline
    subheadline=processbenefits3.subheadline
    text=processbenefits3.text
    button_text=processbenefits3.button_text
    button_link=processbenefits3.button_link
    left=processbenefits3.left
    tags=processbenefits3.tags
  %}
  {% assign processbenefits4 = site.data.textblocks.sections.image_quote.processbenefits4 %}
  {% include sections/image-quote-text.html
    image=processbenefits4.image
    headline=processbenefits4.headline
    subheadline=processbenefits4.subheadline
    text=processbenefits4.text
    button_text=processbenefits4.button_text
    button_link=processbenefits4.button_link
    left=processbenefits4.left
    tags=processbenefits4.tags
  %}
  {% include sections/faqs.html %}
  {% assign processbenefits5 = site.data.textblocks.sections.image_quote.processbenefits5 %}
  {% include sections/image-quote-text.html
    image=processbenefits5.image
    headline=processbenefits5.headline
    subheadline=processbenefits5.subheadline
    button_text=processbenefits5.button_text
    button_link=processbenefits5.button_link
    left=processbenefits5.left
    tags=processbenefits5.tags
    centered=processbenefits5.centered
  %}
  {% include sections/blog-overview.html %}
  {% include sections/newsletter.html %}
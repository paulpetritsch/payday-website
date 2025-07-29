---
layout: default
title: "KYC Erklärung Anti-Geldwäsche | PayDay"
permalink: /anti-moneylaundering/
---
<div class="px-4 min-h-screen h-full flex items-center pt-32">
  <div class="flex flex-col lg:flex-row items-center gap-8 max-w-7xl mx-auto h-full w-full">
        <!-- Text Content -->
        {% include sections/hero-text.html 
          headline=site.data.textblocks.pages.anti_money_laundering.hero_headline
          subheadline=site.data.textblocks.pages.anti_money_laundering.hero_subheadline
          preheadline=site.data.textblocks.pages.anti_money_laundering.hero_preheadline
          text=site.data.textblocks.pages.anti_money_laundering.hero_text
          button_text=site.data.textblocks.pages.anti_money_laundering.hero_button_text
          button_link=site.data.textblocks.pages.anti_money_laundering.hero_button_link
          images=site.data.textblocks.pages.anti_money_laundering.hero_subimages
          %}
        <!-- Image -->
        <div class="w-full max-w-md lg:w-1/2 flex justify-center relative mt-8 lg:mt-0">
            <img src="{{ site.data.textblocks.pages.anti_money_laundering.hero_image | relative_url }}" alt="{{ include.headline | escape }}"
                class="max-h-128 object-contain w-full max-w-md reveal">
            <!-- Tags -->
            {% if site.data.textblocks.pages.anti_money_laundering.hero_tags %}
              {% include elements/imagetags.html tags=site.data.textblocks.pages.anti_money_laundering.hero_tags layout=site.data.textblocks.pages.anti_money_laundering.hero_tags_layout %}
            {% endif %}
        </div>
    </div>
  </div>

  {% assign section1 = site.data.textblocks.sections.image_quote.antimoneylaundering %}
  {% include sections/image-quote-text.html
    image=section1.image
    headline=section1.headline
    subheadline=section1.subheadline
    text=section1.text
    button_text=section1.button_text
    button_link=section1.button_link
    left=section1.left
    tags=section1.tags
    bg=section1.bg
    centered=section1.centered
    tags_layout=section1.tags_layout
  %}
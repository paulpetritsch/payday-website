---
layout: default
title: About
permalink: /about/
key: about
---

<div class="px-4 min-h-screen pt-32">
  <div class="flex flex-col md:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
        <!-- Text Content -->
        {% include sections/hero-text.html 
          headline=site.data.textblocks.pages.about.hero_headline
          subheadline=site.data.textblocks.pages.about.hero_subheadline
          preheadline=site.data.textblocks.pages.about.hero_preheadline
          text=site.data.textblocks.pages.about.hero_text
          button_text=site.data.textblocks.pages.about.hero_button_text
          button_link=site.data.textblocks.pages.about.hero_button_link
          images=site.data.textblocks.pages.about.hero_subimages
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

  {% assign about1 = site.data.textblocks.sections.image_quote.about1 %}
  {% include sections/image-quote-text.html
    image=about1.image
    headline=about1.headline
    subheadline=about1.subheadline
    text=about1.text
    button_text=about1.button_text
    button_link=about1.button_link
    left=about1.left
    tags=about1.tags
    bg=about1.bg
    centered=about1.centered
  %}

  {% assign about2 = site.data.textblocks.sections.image_quote.about2 %}
  {% include sections/image-quote-text.html
    image=about2.image
    headline=about2.headline
    subheadline=about2.subheadline
    text=about2.text
    button_text=about2.button_text
    button_link=about2.button_link
    left=about2.left
    tags=about2.tags
    bg=about2.bg
    centered=about2.centered
  %}

  {% assign about3 = site.data.textblocks.sections.image_quote.about3 %}
  {% include sections/image-quote-text.html
    image=about3.image
    headline=about3.headline
    subheadline=about3.subheadline
    text=about3.text
    button_text=about3.button_text
    button_link=about3.button_link
    left=about3.left
    tags=about3.tags
    bg=about3.bg
    centered=about3.centered
  %}
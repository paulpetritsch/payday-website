---
layout: default
title: Payday | Sorgenfrei Rechnung bezahlen
permalink: /
key: home
---

<div class="px-4 pt-32 2xl:pt-44 mb-12 md:mb-0">
  <div class="flex flex-col lg:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
        <!-- Text Content -->
        {% include sections/hero-text.html 
          headline=site.data.textblocks.pages.home.hero_headline
          subheadline=site.data.textblocks.pages.home.hero_subheadline
          preheadline=site.data.textblocks.pages.home.hero_preheadline
          button_text=site.data.textblocks.pages.home.hero_button_text
          button_link=site.data.textblocks.pages.home.hero_button_link
          button_icon=site.data.textblocks.pages.home.hero_button_icon
          images=site.data.textblocks.pages.home.hero_subimages
          text=site.data.textblocks.pages.home.hero_text
          text_paragraphs=site.data.textblocks.pages.home.hero_text_paragraphs
          %}
        <!-- Image -->
        <div class="w-full lg:w-1/2 flex justify-end relative items-center">
          <div class="relative flex-1">
            <img
              srcset="{{ site.data.textblocks.pages.home.hero_image1 | relative_url }}-400w.webp 400w, {{ site.data.textblocks.pages.home.hero_image1 | relative_url }}-600w.webp 600w, {{ site.data.textblocks.pages.home.hero_image1 | relative_url }}-800w.webp 800w"
              sizes="(max-width: 400px) 400px, (max-width: 600px) 600px, (min-width: 601px) 800px"
              src="{{ site.data.textblocks.pages.home.hero_image1 | relative_url }}.webp"
              alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"    
              width="1000"
              height="1000"
              class="max-h-128 object-contain w-full opacity-0 animate-fadein-400"
            />
            <span
                    class="flex items-center px-4 py-2 rounded-full text-sm lg:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.home.hero_tag1.color }} absolute -bottom-8 -right-1 opacity-0 animate-fadedown-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.home.hero_tag1.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.home.hero_tag1.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.home.hero_tag1.text }}</span>
                </span>
          </div>
          <div class="relative flex-1">
            <img
              srcset="{{ site.data.textblocks.pages.home.hero_image2 | relative_url }}-400w.webp 400w, {{ site.data.textblocks.pages.home.hero_image2 | relative_url }}-600w.webp 600w, {{ site.data.textblocks.pages.home.hero_image2 | relative_url }}-800w.webp 800w"
              sizes="(max-width: 400px) 400px, (max-width: 600px) 600px, (min-width: 601px) 800px"
              src="{{ site.data.textblocks.pages.home.hero_image2 | relative_url }}.webp"
              alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
              width="1000"
              height="1000"
              class="max-h-128 object-contain w-full  opacity-0 animate-fadein-500"
            />
            <img
              srcset="{{ site.data.textblocks.pages.home.hero_image3 | relative_url }}-400w.webp 400w, {{ site.data.textblocks.pages.home.hero_image3 | relative_url }}-600w.webp 600w, {{ site.data.textblocks.pages.home.hero_image3 | relative_url }}-800w.webp 800w"
              sizes="(max-width: 400px) 400px, (max-width: 600px) 600px, (min-width: 601px) 800px"
              src="{{ site.data.textblocks.pages.home.hero_image3 | relative_url }}.webp"
              alt="{{ site.data.textblocks.pages.home.hero_headline | escape }}"
              width="1000"
              height="1000"
              class="max-h-128 object-contain w-full opacity-0 animate-fadein-800 pl-5"
            />
              <span
                    class="flex items-center px-4 py-2 rounded-full text-sm lg:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.home.hero_tag2.color }} absolute -bottom-8 -left-4 opacity-0 animate-fadein-800">
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
  {% include sections/image-quote-text.html
    image=home1.image
    headline=home1.headline
    subheadline=home1.subheadline
    text=home1.text
    text_paragraphs=home1.text_paragraphs
    button_text=home1.button_text
    button_link=home1.button_link
    button_icon=home1.button_icon
    left=home1.left
    tags=home1.tags
    bg=home1.bg
    squareimage=home1.squareimage
    tags_layout=home1.tags_layout
    centered=home1.centered
  %}
   {% assign home2 = site.data.textblocks.sections.image_quote.home2 %}
  {% include sections/image-quote-text.html
    image=home2.image
    headline=home2.headline
    subheadline=home2.subheadline
    text=home2.text
    text_paragraphs=home2.text_paragraphs
    button_text=home2.button_text
    button_link=home2.button_link
    button_icon=home2.button_icon
    tags_layout=home2.tags_layout
    left=home2.left
    tags=home2.tags
  %}
  {% include sections/steps.html %}
  {% include sections/slider.html %}
  {% include sections/faqs.html %}
  {% assign home3 = site.data.textblocks.sections.image_quote.home3 %}
  {% include sections/image-quote-text.html
    image=home3.image
    headline=home3.headline
    subheadline=home3.subheadline
    text_paragraphs=home3.text_paragraphs
    button_text=home3.button_text
    button_link=home3.button_link
    button_icon=home3.button_icon
    tags_layout=home3.tags_layout
    left=home3.left
    tags=home3.tags
    squareimage=true
    centered=home3.centered
  %}
  {% include sections/blog-overview.html %}
  {% include sections/newsletter.html %}
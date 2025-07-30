---
layout: default
title: Ablauf & Vorteile
permalink: /process-benefits/
---


<div class="px-4 min-h-screen h-full flex items-center pt-32 lg:pt-8 mb-24 md:mb-0">
  <div class="flex flex-col lg:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
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
            <img src="{{ site.data.textblocks.pages.process_benefits.hero_image1 | relative_url }}" alt="{{ site.data.textblocks.pages.process_benefits.hero_headline | escape }}"
                class="max-h-128 object-contain w-full opacity-0 animate-fadein-400">
            <span
                    class="flex items-center px-4 py-2 rounded-full text-sm md:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.process_benefits.hero_tag1.color }} absolute -bottom-8 -right-1 opacity-0 animate-fadedown-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.process_benefits.hero_tag1.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.process_benefits.hero_tag1.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.process_benefits.hero_tag1.text }}</span>
                </span>
          </div>
          <div class="relative">
            <img src="{{ site.data.textblocks.pages.process_benefits.hero_image2 | relative_url }}" alt="{{ site.data.textblocks.pages.process_benefits.hero_headline | escape }}"
              class="max-h-128 object-contain w-full  opacity-0 animate-fadein-500 pl-4 pb-5">
            <img src="{{ site.data.textblocks.pages.process_benefits.hero_image3 | relative_url }}" alt="{{ site.data.textblocks.pages.process_benefits.hero_headline | escape }}"
              class="max-h-128 object-contain w-full opacity-0 animate-fadein-600 pl-4">
              <span
                    class="flex items-center px-4 py-2 rounded-full text-sm md:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.process_benefits.hero_tag2.color }} absolute -bottom-8 -left-4 opacity-0 animate-fadein-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.process_benefits.hero_tag2.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.process_benefits.hero_tag2.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.process_benefits.hero_tag2.text }}</span>
                </span>
          </div>
        </div>
    </div>
  </div>

  {% include sections/steps.html %}
  {% assign processbenefits1 = site.data.textblocks.sections.image_quote.processbenefits1 %}
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
    tags_layout=processbenefits1.tags_layout
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
    tags_layout=processbenefits2.tags_layout
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
    tags_layout=processbenefits3.tags_layout
  %}
  <div class="px-4 min-h-screen h-full flex items-center pt-32 lg:pt-8 mb-24 lg:mb-0">
  <div class="flex flex-col lg:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
        <!-- Image -->
        <div class="w-full lg:w-1/2 flex justify-center relative items-center mb-12 lg:mb-0">
          <div class="relative">
            <img src="{{ site.data.textblocks.pages.process_benefits.customsection_image1 | relative_url }}" alt="{{ site.data.textblocks.pages.process_benefits.customsection_subheadline | escape }}"
                class="max-h-128 object-contain w-full">
                <div class="flex items-center text-sm md:text-xl w-fit absolute -bottom-8 left-1/2 -translate-x-1/2">
                      <span class="px-4 py-2 rounded-full border-12 border-white whitespace-nowrap {{ site.data.textblocks.pages.process_benefits.customsection_tag1.color }}
                          is-animated">
                          <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.process_benefits.customsection_tag1.svg_color }}">
                              {{ site.data.svgs[site.data.textblocks.pages.process_benefits.customsection_tag1.svg] }}
                          </span>
                      <span>{{ site.data.textblocks.pages.process_benefits.customsection_tag1.text }}</span>
                  </span>
                </div>
          </div>
          <div class="relative">
            <img src="{{ site.data.textblocks.pages.process_benefits.customsection_image2 | relative_url }}" alt="{{ site.data.textblocks.pages.process_benefits.customsection_headline | escape }}"
              class="max-h-128 object-contain w-full pl-4">
              <span
                    class="flex items-center px-4 py-2 rounded-full text-sm md:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.process_benefits.customsection_tag2.color }} absolute top-12 -left-16 is-animated">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.process_benefits.customsection_tag2.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.process_benefits.customsection_tag2.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.process_benefits.customsection_tag2.text }}</span>
                </span>
            <img src="{{ site.data.textblocks.pages.process_benefits.customsection_image3 | relative_url }}" alt="{{ site.data.textblocks.pages.process_benefits.customsection_headline | escape }}"
              class="max-h-128 object-contain w-full pl-4 pr-6">
              <span
                    class="flex items-center px-4 py-2 rounded-full text-sm md:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.process_benefits.customsection_tag3.color }} absolute -bottom-8 -right-4 is-animated">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.process_benefits.customsection_tag3.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.process_benefits.customsection_tag3.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.process_benefits.customsection_tag3.text }}</span>
                </span>
          </div>
        </div>
        <div class="w-full lg:w-1/2 flex flex-col items-start justify-center lg:pl-12">
            {% include elements/section-headline.html text=site.data.textblocks.pages.process_benefits.customsection_subheadline centered=true %}
            <div class="mb-4 is-animated text-lg md:text-base max-w-md {% if include.centered %}mx-auto md:mx-0{% endif %}">
             {{ site.data.textblocks.pages.process_benefits.customsection_text | markdownify }}
            </div>
            {% if site.data.textblocks.pages.process_benefits.customsection_button_text and site.data.textblocks.pages.process_benefits.customsection_button_link %}
                {% include elements/button.html text=site.data.textblocks.pages.process_benefits.customsection_button_text link=site.data.textblocks.pages.process_benefits.customsection_button_link %}
            {% endif %}
        </div>
    </div>
  </div>
  {% include sections/faqs.html %}
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
    tags_layout=processbenefits4.tags_layout
  %}
  {% include sections/blog-overview.html %}
  {% include sections/newsletter.html %}
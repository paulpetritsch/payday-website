---
layout: default
title: "Für Unternehmen | PayDay"
permalink: /companies/
---
<div class="px-4 pt-32 lg:pt-44 pb-24">
  <div class="flex flex-col 2xl:flex-row items-center gap-8 max-w-7xl mx-auto h-full w-full">
        <!-- Text Content -->
        {% include sections/hero-text.html 
          headline=site.data.textblocks.pages.companies.hero_headline
          subheadline=site.data.textblocks.pages.companies.hero_subheadline
          preheadline=site.data.textblocks.pages.companies.hero_preheadline
          text=site.data.textblocks.pages.companies.hero_text
          button_text=site.data.textblocks.pages.companies.hero_button_text
          button_link=site.data.textblocks.pages.companies.hero_button_link
          images=site.data.textblocks.pages.companies.hero_subimages
          %}
        <!-- Image -->
        <div class="w-full max-w-md lg:w-1/2 flex justify-end relative mt-8 lg:mt-0 ml-auto">
            <img
              srcset="{{ site.data.textblocks.pages.companies.hero_image | relative_url }}-400w.webp 400w, {{ site.data.textblocks.pages.companies.hero_image | relative_url }}-600w.webp 600w, {{ site.data.textblocks.pages.companies.hero_image | relative_url }}-800w.webp 800w"
              sizes="(max-width: 400px) 400px, (max-width: 600px) 600px, (min-width: 601px) 800px"
              src="{{ site.data.textblocks.pages.companies.hero_image | relative_url }}.webp"
              alt="{{ site.data.textblocks.pages.companies.hero_headline | escape }}"    
              width="1000"
              height="1000"
              class="max-h-128 object-contain w-full max-w-md reveal"
            />
            <!-- Tags -->
            {% if site.data.textblocks.pages.companies.hero_tags %}
              {% include elements/imagetags.html tags=site.data.textblocks.pages.companies.hero_tags layout=site.data.textblocks.pages.companies.hero_tags_layout %}
            {% endif %}
        </div>
    </div>
  </div>

  {% include sections/steps-quote.html %}
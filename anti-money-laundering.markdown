---
layout: default
title: Anti Geldwäsche
permalink: /anti-money-laundering/
---

 anti_money_laundering:
      image: "/assets/images/home-hero1.png"
      headline: "Wozu dieser Onboarding-Prozess?"
      text: "Als Finanzintermediär in der Schweiz sind wir verpflichtet, alle Kund:innen gemäss den Vorschriften der FINMA (Eidgenössische Finanzmarktaufsicht) zu identifizieren. payday nimmt diese KYC-Vorschriften (Know Your Customer) ernst, um unsere Kund:innen zu schützen und eine sichere Plattform aufrechtzuerhalten.
        <br><br>
        Keine Sorge, der Vorgang ist schnell und einfach, und alle deine Informationen werden vertraulich und sicher behandelt.
      button_text: "Jetzt registrieren"
      button_link: "/register"
      left: true
      centered: true
      tags:
        - color: "bg-pink-50"
          text: "sicher"
          svg: "fast"
          svg_color: "text-pink-100"
        - color: "bg-green-50"
          text: "schnell & einfach"
          svg: "smiley"
          svg_color: "text-green-100"

<div class="px-4 min-h-screen pt-32">
  <div class="flex flex-col md:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
        <!-- Text Content -->
        <div class="w-full md:w-1/2 flex flex-col items-start justify-center">
            <h1 class="text-7xl font-bold font-display mb-4 opacity-0 animate-fadein-500 text-center md:text-left">
              {{ site.data.textblocks.pages.anti_money_laundering.hero_headline }}
            </h1>
            <p class="text-base font-display mb-4 opacity-0 animate-fadein-600 text-center md:text-left">
                {{ site.data.textblocks.pages.anti_money_laundering.hero_text }}
            </div>
            <a href="{{ site.baseurl }}{{site.data.textblocks.pages.anti_money_laundering.hero_button_link}}" class="text-xl md:text-base bg-black hover:bg-pink-100 transition-colors duration-200 text-white px-4 py-3 md:py-3 rounded-xl opacity-0 animate-fadein-700 w-full md:w-fit text-center max-w-xs mx-auto md:mx-0">
              {{ site.data.textblocks.pages.anti_money_laundering.hero_button_text }}
            </a>
        </div>
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
              class="max-h-128 object-contain w-full opacity-0 animate-fadein-600">
              <span
                    class="flex items-center px-4 py-2 rounded-full text-sm md:text-xl w-fit border-12 border-white {{ site.data.textblocks.pages.home.hero_tag2.color }} absolute -bottom-8 -left-1 opacity-0 animate-fadein-800">
                        <span class="w-5 h-5 mr-2 inline-block align-middle {{ site.data.textblocks.pages.home.hero_tag2.svg_color }}">
                            {{ site.data.svgs[site.data.textblocks.pages.home.hero_tag2.svg] }}
                        </span>
                    <span>{{ site.data.textblocks.pages.home.hero_tag2.text }}</span>
                </span>
          </div>
        </div>
    </div>
  </div>
  {% assign section = site.data.textblocks.sections.image_quote.anti_money_laundering %}
  {% include sections/image-quote-text.html
    image=section.image
    headline=section.headline
    subheadline=section.subheadline
    text=section.text
    button_text=section.button_text
    button_link=section.button_link
    left=section.left
    tags=section.tags
    bg=section.bg
    centered=section.centered
  %}
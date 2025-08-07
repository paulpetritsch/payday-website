---
layout: default
title: About | PayDay
permalink: /about/
key: about
---

<div class="px-4 pt-32 2xl:pt-44">
  <div class="flex flex-col lg:flex-row items-center gap-8 max-w-7xl mx-auto h-full">
        <!-- Text Content -->
        {% include sections/hero-text.html 
          headline=site.data.textblocks.pages.about.hero_headline
          subheadline=site.data.textblocks.pages.about.hero_subheadline
          preheadline=site.data.textblocks.pages.about.hero_preheadline
          text=site.data.textblocks.pages.about.hero_text
          text_paragraphs=site.data.textblocks.pages.about.hero_text_paragraphs
          button_text=site.data.textblocks.pages.about.hero_button_text
          button_link=site.data.textblocks.pages.about.hero_button_link
          button_icon=site.data.textblocks.pages.about.hero_button_icon
          images=site.data.textblocks.pages.about.hero_subimages
          %}
        <!-- Image -->
        <div class="w-full h-full md:w-1/2 flex justify-end relative items-center">
          <div class="relative w-full flex-1 flex items-center justify-center">
            <!-- SVG with animated circles -->
            <div class="w-full max-w-md md:max-w-lg lg:max-w-xl">
            <svg class="w-full h-auto" width="522" height="513" viewBox="0 0 522 513" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
              <defs>
                <!-- Define clip paths for each circle -->
                <clipPath id="clip-outer1">
                  <ellipse cx="260.485" cy="65.4585" rx="64.9429" ry="65.4585"/>
                </clipPath>
                <clipPath id="clip-outer2">
                  <path d="M325.428 446.871C325.428 483.022 296.352 512.329 260.485 512.329C224.618 512.329 195.542 483.022 195.542 446.871C195.542 410.719 224.618 381.412 260.485 381.412C296.352 381.412 325.428 410.719 325.428 446.871Z"/>
                </clipPath>
                <clipPath id="clip-outer3">
                  <ellipse cx="399.133" cy="392.236" rx="65.4584" ry="65.4585"/>
                </clipPath>
                <clipPath id="clip-outer4">
                  <ellipse cx="121.836" cy="121.124" rx="65.4584" ry="65.4585"/>
                </clipPath>
                <clipPath id="clip-outer5">
                  <ellipse cx="399.133" cy="121.124" rx="65.4584" ry="65.4585"/>
                </clipPath>
                <clipPath id="clip-inner1">
                  <ellipse cx="260.485" cy="176.274" rx="36.0794" ry="36.0795"/>
                </clipPath>
                <clipPath id="clip-inner2">
                  <ellipse cx="222.344" cy="345.333" rx="36.0794" ry="36.0795"/>
                </clipPath>
                <clipPath id="clip-inner3">
                  <ellipse cx="172.863" cy="282.451" rx="36.0794" ry="36.0795"/>
                </clipPath>
                <clipPath id="clip-inner4">
                  <ellipse cx="350.167" cy="282.451" rx="36.0794" ry="36.0795"/>
                </clipPath>
                <clipPath id="clip-inner5">
                  <ellipse cx="301.719" cy="345.333" rx="36.0794" ry="36.0795"/>
                </clipPath>
                <clipPath id="clip-center">
                  <ellipse cx="262.546" cy="264.927" rx="41.2336" ry="41.2337"/>
                </clipPath>
                <clipPath id="clip-inner6">
                  <ellipse cx="333.079" cy="207.2" rx="36.0794" ry="36.0795"/>
                </clipPath>
                <clipPath id="clip-inner7">
                  <ellipse cx="188.079" cy="206.169" rx="36.0794" ry="36.0795"/>
                </clipPath>
                <clipPath id="clip-outer6">
                  <ellipse cx="121.836" cy="392.236" rx="65.4584" ry="65.4585"/>
                </clipPath>
                <clipPath id="clip-outer7">
                  <ellipse cx="455.829" cy="256.165" rx="65.4584" ry="65.4585"/>
                </clipPath>
                <clipPath id="clip-outer8">
                  <ellipse cx="66.1703" cy="256.165" rx="65.4584" ry="65.4585"/>
                </clipPath>
              </defs>
              
              <!-- Outer Circle 1 - Top -->
              <ellipse cx="260.485" cy="65.4585" rx="64.9429" ry="65.4585" fill="#E6F3B7" class="opacity-0 circle-outer animate-fadein-400"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle1.webp' | relative_url }}" x="195.542" y="0" width="130" height="130" clip-path="url(#clip-outer1)" class="opacity-0 circle-outer animate-fadein-400"/>
              
              <!-- Outer Circle 2 - Bottom -->
              <path d="M325.428 446.871C325.428 483.022 296.352 512.329 260.485 512.329C224.618 512.329 195.542 483.022 195.542 446.871C195.542 410.719 224.618 381.412 260.485 381.412C296.352 381.412 325.428 410.719 325.428 446.871Z" fill="#E6F3B7" class="opacity-0 circle-outer animate-fadein-500"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle2.webp' | relative_url }}" x="195.542" y="381.412" width="130" height="130" clip-path="url(#clip-outer2)" class="opacity-0 circle-outer animate-fadein-500"/>
              
              <!-- Outer Circle 3 - Right -->
              <ellipse cx="399.133" cy="392.236" rx="65.4584" ry="65.4585" fill="#FADEF0" class="opacity-0 circle-outer animate-fadein-600"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle3.webp' | relative_url }}" x="333.675" y="326.778" width="130" height="130" clip-path="url(#clip-outer3)" class="opacity-0 circle-outer animate-fadein-600"/>
              
              <!-- Outer Circle 4 - Left -->
              <ellipse cx="121.836" cy="121.124" rx="65.4584" ry="65.4585" fill="#FADEF0" class="opacity-0 circle-outer animate-fadein-700"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle4.webp' | relative_url }}" x="56.378" y="55.666" width="130" height="130" clip-path="url(#clip-outer4)" class="opacity-0 circle-outer animate-fadein-700"/>
              
              <!-- Outer Circle 5 - Top Right -->
              <ellipse cx="399.133" cy="121.124" rx="65.4584" ry="65.4585" fill="#E1CBFC" class="opacity-0 circle-outer animate-fadein-800"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle5.webp' | relative_url }}" x="333.675" y="55.666" width="130" height="130" clip-path="url(#clip-outer5)" class="opacity-0 circle-outer animate-fadein-800"/>
              
              <!-- Inner Circle 1 - Top -->
              <ellipse cx="260.485" cy="176.274" rx="36.0794" ry="36.0795" fill="#E1CBFC" class="opacity-0 circle-inner animate-fadein-200"/>
              <image xlink:href="{{ '/assets/images/about/circles/inner1.webp' | relative_url }}" x="224.406" y="140.195" width="72" height="72" clip-path="url(#clip-inner1)" class="opacity-0 circle-inner animate-fadein-200"/>
              
              <!-- Inner Circle 2 - Bottom Right -->
              <ellipse cx="222.344" cy="345.333" rx="36.0794" ry="36.0795" fill="#E1CBFC" class="opacity-0 circle-inner animate-fadein-300"/>
              <image xlink:href="{{ '/assets/images/about/circles/inner2.webp' | relative_url }}" x="186.265" y="309.254" width="72" height="72" clip-path="url(#clip-inner2)" class="opacity-0 circle-inner animate-fadein-300"/>
              
              <!-- Inner Circle 3 - Bottom Left -->
              <ellipse cx="172.863" cy="282.451" rx="36.0794" ry="36.0795" fill="#FADEF0" class="opacity-0 circle-inner animate-fadein-400"/>
              <image xlink:href="{{ '/assets/images/about/circles/inner3.webp' | relative_url }}" x="136.784" y="246.372" width="72" height="72" clip-path="url(#clip-inner3)" class="opacity-0 circle-inner animate-fadein-400"/>
              
              <!-- Inner Circle 4 - Top Right -->
              <ellipse cx="350.167" cy="282.451" rx="36.0794" ry="36.0795" fill="#FADEF0" class="opacity-0 circle-inner animate-fadein-500"/>
              <image xlink:href="{{ '/assets/images/about/circles/inner4.webp' | relative_url }}" x="314.088" y="246.372" width="72" height="72" clip-path="url(#clip-inner4)" class="opacity-0 circle-inner animate-fadein-500"/>
              
              <!-- Inner Circle 5 - Bottom -->
              <ellipse cx="301.719" cy="345.333" rx="36.0794" ry="36.0795" fill="#E6F3B7" class="opacity-0 circle-inner animate-fadein-600"/>
              <image xlink:href="{{ '/assets/images/about/circles/inner5.webp' | relative_url }}" x="265.64" y="309.254" width="72" height="72" clip-path="url(#clip-inner5)" class="opacity-0 circle-inner animate-fadein-600"/>
              
              <!-- Center Circle -->
              <ellipse cx="262.546" cy="264.927" rx="41.2336" ry="41.2337" fill="#E6F3B7" class="opacity-0 circle-center animate-fadein-100"/>
              <image xlink:href="{{ '/assets/images/about/circles/center.webp' | relative_url }}" x="221.312" y="223.693" width="82" height="82" clip-path="url(#clip-center)" class="opacity-0 circle-center animate-fadein-100"/>
              
              <!-- Inner Circle 6 - Right -->
              <ellipse cx="333.079" cy="207.2" rx="36.0794" ry="36.0795" fill="#E6F3B7" class="opacity-0 circle-inner animate-fadein-700"/>
              <image xlink:href="{{ '/assets/images/about/circles/inner6.webp' | relative_url }}" x="297" y="171.121" width="72" height="72" clip-path="url(#clip-inner6)" class="opacity-0 circle-inner animate-fadein-700"/>
              
              <!-- Inner Circle 7 - Left -->
              <ellipse cx="188.079" cy="206.169" rx="36.0794" ry="36.0795" fill="#E6F3B7" class="opacity-0 circle-inner animate-fadein-800"/>
              <image xlink:href="{{ '/assets/images/about/circles/inner7.webp' | relative_url }}" x="152" y="170.09" width="72" height="72" clip-path="url(#clip-inner7)" class="opacity-0 circle-inner animate-fadein-800"/>
              
              <!-- Outer Circle 6 - Bottom Left -->
              <ellipse cx="121.836" cy="392.236" rx="65.4584" ry="65.4585" fill="#E1CBFC" class="opacity-0 circle-outer animate-fadein-900"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle6.webp' | relative_url }}" x="56.378" y="326.778" width="130" height="130" clip-path="url(#clip-outer6)" class="opacity-0 circle-outer animate-fadein-900"/>
              
              <!-- Outer Circle 7 - Right -->
              <ellipse cx="455.829" cy="256.165" rx="65.4584" ry="65.4585" fill="#E6F3B7" class="opacity-0 circle-outer animate-fadein-1000"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle7.webp' | relative_url }}" x="390.371" y="190.707" width="130" height="130" clip-path="url(#clip-outer7)" class="opacity-0 circle-outer animate-fadein-1000"/>
              
              <!-- Outer Circle 8 - Left -->
              <ellipse cx="66.1703" cy="256.165" rx="65.4584" ry="65.4585" fill="#E6F3B7" class="opacity-0 circle-outer animate-fadein-1100"/>
              <image xlink:href="{{ '/assets/images/about/circles/circle8.webp' | relative_url }}" x="0.712" y="190.707" width="130" height="130" clip-path="url(#clip-outer8)" class="opacity-0 circle-outer animate-fadein-1100"/>
            </svg> 
            </div>
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
    text_paragraphs=about1.text_paragraphs
    button_text=about1.button_text
    button_link=about1.button_link
    button_icon=about1.button_icon
    left=about1.left
    tags=about1.tags
    bg=about1.bg
    centered=about1.centered
    tags_layout=about1.tags_layout
  %}
  {% include sections/quote.html %}
  {% assign about2 = site.data.textblocks.sections.image_quote.about2 %}
  {% include sections/image-quote-text.html
    image=about2.image
    headline=about2.headline
    subheadline=about2.subheadline
    text=about2.text
    text_paragraphs=about2.text_paragraphs
    button_text=about2.button_text
    button_link=about2.button_link
    button_icon=about2.button_icon
    left=about2.left
    tags=about2.tags
    bg=about2.bg
    centered=about2.centered
    tags_layout=about2.tags_layout
  %}
  {% include sections/steps-quote.html %}
  {% assign about3 = site.data.textblocks.sections.image_quote.about3 %}
  {% include sections/image-quote-text.html
    image=about3.image
    headline=about3.headline
    subheadline=about3.subheadline
    text=about3.text
    text_paragraphs=about3.text_paragraphs
    button_text=about3.button_text
    button_link=about3.button_link
    button_icon=about3.button_icon
    left=about3.left
    tags=about3.tags
    bg=about3.bg
    centered=about3.centered
    tags_layout=about3.tags_layout
  %}
  <div class="md:pt-32">
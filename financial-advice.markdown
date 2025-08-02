---
layout: default
title: Finanztipps
permalink: /financial-advice/
---

<div class="px-8 md:px-4 py-24 md:py-32">
    <div class="max-w-7xl mx-auto">
        <div class="text-center mb-12">
          <h1 class="text-5xl md:text-7xl font-bold font-display reveal break-words">PayDay Finanztipps</h1>
        </div>
        <div class="mt-4 flex flex-row gap-8 md:justify-center mb-8 flex-wrap">
            {% assign blog_posts = site.categories.financial-advice %}
            {% for post in blog_posts %}
              <a href="{{ site.baseurl }}{{ post.url }}" class="md:w-[calc(25%-2rem)] group is-animated">
                <div class="mb-4 w-full rounded-3xl aspect-[1/1] relative bg-{{ post.color }}">
                    <div class="absolute top-4 left-4 bg-white text-xs rounded-lg px-2 py-1">
                        {{ site.data.textblocks.texts.reading_time }} {{ post.duration }} {{ site.data.textblocks.texts.min}} 
                    </div>
                    {% if post.image %}
                      <img src="{{ post.image | relative_url }}" alt="{{ post.title }}" class="w-full h-full object-cover" loading="lazy">
                    {% endif %}
                    <div class="absolute rounded-full bg-black group-hover:bg-pink-100 -bottom-2.5 -right-2.5 w-16 h-16 flex items-center justify-center border-white border-12 scale-100 group-hover:scale-110 transition-all duration-300">
                        <svg class=" scale-100 group-hover:scale-90 transition-all duration-300" width="22" height="12" viewBox="0 0 22 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M1 6L21 6" stroke="#FAF6FE" stroke-width="2" stroke-linecap="round"/>
                            <path d="M16 1L21 6" stroke="#FAF6FE" stroke-width="2" stroke-linecap="round"/>
                            <path d="M16 11L21 6" stroke="#FAF6FE" stroke-width="2" stroke-linecap="round"/>
                        </svg>                            
                    </div>
                </div>
                <div class="font-semibold mb-4">
                  {{ post.title }}
                </div>
                <p class="text-gray-600 mb-4">
                  {{ post.intro | default: post.excerpt | strip_html | truncate: 200 }}
                </p>
            </a>
            {% endfor %}
          </div>
    </div>
</div>

  {% include sections/newsletter.html %}
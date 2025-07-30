---
layout: default
title: Kontaktieren Sie uns jetzt | Payday
permalink: /support
key: support
---

<div class="px-4 min-h-screen h-full flex items-center pt-32 pb-12 bg-purple-50">
  <div class="max-w-7xl mx-auto">
    <div class="text-center">
    {% include elements/page-headline.html text=site.data.textblocks.pages.support.headline %}
    </div>
    <form class="max-w-3xl mx-auto mt-8 is-animated">
      <div class="flex flex-col md:flex-row gap-4 mb-6">
        <div class="flex-1">
          <label for="firstname" class="block mb-2">
            {{ site.data.textblocks.pages.support.firstname }}
          </label>
          <input 
            type="text" 
            id="firstname" 
            name="firstname" 
            class="w-full py-3 px-4 rounded-lg focus:outline-purple-200"
            placeholder="{{ site.data.textblocks.pages.support.firstname_placeholder | default: 'Ihr Vorname' }}"
            required
          />
        </div>
        <div class="flex-1">
          <label for="lastname" class="block mb-2">
            {{ site.data.textblocks.pages.support.lastname }}
          </label>
          <input 
            type="text" 
            id="lastname" 
            name="lastname" 
            class="w-full py-3 px-4 rounded-lg focus:outline-purple-200"
            placeholder="{{ site.data.textblocks.pages.support.lastname }}"
            required
          />
        </div>
      </div>
      <div class="mb-6">
        <label for="email" class="block mb-2">
          {{ site.data.textblocks.pages.support.email }}
        </label>
        <input 
          type="email" 
          id="email" 
          name="email" 
          class="w-full py-3 px-4 rounded-lg focus:outline-purple-200"
          placeholder="{{ site.data.textblocks.pages.support.email_placeholder }}"
          required
        />
      </div>
      <div class="mb-8">
        <label for="message" class="block mb-2">
          {{ site.data.textblocks.pages.support.message }}
        </label>
        <textarea 
          id="message" 
          name="message" 
          rows="6"
          class="w-full py-3 px-4 rounded-lg focus:outline-purple-200 resize-vertical"
          placeholder="{{ site.data.textblocks.pages.support.message_placeholder }}"
          required
        ></textarea>
      </div>
      <div class="text-center">
        <button type="submit"
          class="{% if include.animation != false and include.animation != 'false' %}is-animated{% endif %} inline-block bg-black hover:bg-pink-100 transition-colors duration-200 text-white px-4 py-4 md:py-3 rounded-xl text-xl md:text-base w-full md:w-fit text-center max-w-xs mx-auto lg:mx-0">
          {{ site.data.textblocks.pages.support.send }}
        </button>
      </div>
    </form>
  </div>
</div>

  {% include sections/faqs.html bg=false %}
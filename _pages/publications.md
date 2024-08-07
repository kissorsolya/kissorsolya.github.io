---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% for post in site.publications reversed %}
  <div class="publication-item" style="clear: both; margin-bottom: 2em; padding-bottom: 1em; border-bottom: 1px solid #f2f2f2;">
    {% if post.image %}
      <img src="{{ base_path }}{{ post.image }}" alt="{{ post.title }}" style="float: right; margin: 0 0 1.4em 1.4em; max-width: 300px; height: auto;">
    {% endif %}
    <h2>{{ post.title }}</h2>
    <p><strong>Published in:</strong> {{ post.venue }}</p>
    <p><strong>Date:</strong> {{ post.date | date: "%B %d, %Y" }}</p>
    <p><em>{{ post.excerpt }}</em></p>
    {% if post.description %}
      <p>{{ post.description }}</p>
    {% endif %}
    <p>{{ post.citation }}</p>
    <p>
      {% if post.paperurl %}
        <a href="{{ post.paperurl }}" target="_blank">Article</a>
      {% endif %}
      {% if post.poster_link %}
        | <a href="{{ base_path }}{{ post.poster_link }}">Poster</a>
      {% endif %}
    </p>
  </div>
{% endfor %}
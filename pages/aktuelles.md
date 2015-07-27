---
layout: page-notitle
title: "Aktuelles"
show_meta: false
permalink: "/aktuelles/"
header:
   image_fullwidth: "header_scale1.jpg"
show_meta: false
---
<div class="row">
	<div class="medium-8 columns t30">
  {% for post in site.categories.aktuelles %}
    <div class="row">
    <div class="small-12 columns b60">
      <p class="subheadline"><span class="subheader">{% if post.categories %}{{ post.categories | join: ' &middot; ' }}{% endif %}</span> – {% if post.subheadline %}{{ post.subheadline }}{% endif %}</p>
      <h2 class="akt"><a class="akt" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></h2>
      <p>
        {% if post.image.thumb %}<a href="{{ site.url }}{{ post.url }}" title="{{ post.title escape_once }}"><img src="{{ site.urlimg }}{{ post.image.thumb }}" class="alignleft" width="150" height="150" alt="{{ page.title escape_once }}"></a>{% endif %}

        {% if post.meta_description %}{{ post.meta_description | strip_html | escape }}{% elsif post.teaser %}{{ post.teaser | strip_html | escape }}{% endif %}
<br>
        <a href="{{ site.url }}{{ post.url }}" title="{{ site.data.language.read }} {{ post.title escape_once }}"><strong>{{ site.data.language.read_more }}</strong></a>
      </p>
    </div><!-- /.small-12.columns -->
	</div>
  {% endfor %}
	</div><!-- /.medium-7.columns -->
</div><!-- /.row -->
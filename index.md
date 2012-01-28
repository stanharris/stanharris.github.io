---
layout: page
title: In The Beginning...
---
{% include JB/setup %}

TBD: Just getting this site started using Jekyll:

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## This is the ole H2 header line

Start of a paragraph with `code highlighting` and other text:
    
    Put some text here
    
    And even include
      some text
      that is indented.

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.



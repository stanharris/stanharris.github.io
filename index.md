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
    
## One more header here

This is even more text you can put here to get things started.
And of course you can add a line that includes `highlight code or commands` for emphasis.

    $ put your fav command here.

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.



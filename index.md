---
layout: default
---

## Welcome to mud2.net!

Havoc's home for some things <a href="http://www.mudii.co.uk">mud2</a>. Here you can find new and resurrected issues of <a href="/muddledtimes/site/index.html">MuddledTimes</a> as well as Havoc's <a href="/mudiiclient">mudiiclient</a>.

## Havoc's fails

Just for fun, I've started keeping track of the different ways that I died. Enjoy!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

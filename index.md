---
layout: home
---

<div class="header">
 <h1><a href="/"> Everland </a></h1>
 <h2>You can't be anyone else but yourself.</h2>
</div>

 <ul class="artical-list">
        {% for post in site.categories.blog %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    
   <div class="aside">
    <div id="sidebar">
  <a href="/">Blog</a>
  <a href="/contact">Contact</a>
  <a href="/portfolio">Portfolio</a>
</div>
    </div>

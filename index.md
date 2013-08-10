---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">        
            <li class="on"><a href="/"><span>Blog</span></a></li>
            <li><a href="/contact"><span>Contact</span></a></li>
            <li><a href="/portfolio"><span>Portfolio</span></a></li>
        </ul>

        <ul class="artical-list">
        {% for post in site.categories.blog %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>    
                </div>

---
layout: home
---

<div class="index-content blog">
    <div class="section">
    <div class="section2">
    <div class="header">
     <h1><a href="/">Across the universe</a></h1>
     <h2>Look at the stars, look how they shine for you.</h2>
   </div>
        <ul class="artical-cate">        
            <li class="on"><a href="/"><span>Blog</span></a></li>
            <li><a href="/contact"><span>Contact</span></a></li>
            <li><a href="/portfolio"><span>Portfolio</span></a></li>
        </ul>

        <ul class="artical-list">
        {% for post in site.categories.blog %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="category">{{ post.category }}</div>
                <div class="title-desc">{{ post.excerpt }}</div>   
                <p><a href="{{ post.url }}">Read more</a></p>
                      
            </li>
        {% endfor %}
        </ul>
        </div> 
     </div>  
        <div id="credit">
     Designed by Lynette Lu
 </div>    
       
  </div>

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
            <li class="on"><a href="/">Blog</a></li>
            <li><a href="/contact">Contact</a></li>
            <li><a href="/portfolio">Portfolio</a></li>
        </ul>

        <ul class="artical-list">
        {% for post in lynettelu.github.io/blog/Blahblahblah limit:10 %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a> | <a href="{{ category.url }}">{{ post.category }}</a></h2>
                                <div class="title-desc">{{ post.excerpt }}</div>   
                                      
            </li>
        {% endfor %}
        </ul>
        </div> 
     </div>  
        <div id="credit">
     Designed by Lynette Lu
 </div>    
       
  </div>

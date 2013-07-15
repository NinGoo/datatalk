---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
<<<<<<< HEAD
            <li class="on"><a href="/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/opinion"><span>Opinion</span></a></li>
            <li style="text-align:right"><a href="/project"><span>Project</span></a></li>
=======
            <li class="on"><a href="/"><span>文章</span></a></li>
            <li style="text-align:center"><a href="/recommend"><span>推荐</span></a></li>
            <li style="text-align:right"><a href="/about"><span>关于</span></a></li>
>>>>>>> master
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
<<<<<<< HEAD
        {% for post in site.categories.blog %}
=======
        {% for post in site.posts %}
>>>>>>> master
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
<<<<<<< HEAD

=======
>>>>>>> master

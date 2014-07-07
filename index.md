---
layout: page
title: lazysprite 团队官方博客
tagline: lazysprite开发团队
---
{% include JB/setup %}
##团队简介
lazysprite团队是由一批刚刚走出校门，但是又不想淹没在城市中的年轻人组成的团队。虽然他们现在正在起步阶段，只能蜷缩在简陋的工作室里，但是他们每个人的心里都深藏着一颗热情的不甘失败，不甘平庸的种子。  
###主要从事行业及相关工作内容
lazysprite团队，主要是一个软件服务团队，目前主要从事移动端小型游戏的开发。  
##团队最新博客及相关产品
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>





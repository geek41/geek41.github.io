---
layout: blog
title: Happy coding
pg_type: index
---


{% for post in paginator.posts %}
<!--
	<div >
	  <h5 class="post-date" align="right">{{ post.date | date_to_string}}</h5>		</div> -->
<div class="title-block">
  <h3><a href="{{ post.url }}">[{{ post.date | date:"%F" }}] {{ post.title }}</a></h3>
  {% if post.content contains "<!-- more -->" %}
  {{ post.content | split:'<!-- more -->' | first }}
  {% else %}
  {{ post.content | strip_html | truncatewords:50 }}
  {% endif %}
  <div class="commit">
	<a href="#"><span class="glyphicon glyphicon-folder-open" aria-hidden="true"></span> {{post.categories}}</a>
	<a href="#"><span class="glyphicon glyphicon-tags" aria-hidden="true"></span> {{post.tags | array_to_sentence_string }} </a>

	<a href="{{post.url}}"><span class="glyphicon glyphicon-comment" aria-hidden="true"></span> </a>
	<a href="{{post.url}}#disqus_thread">0 comment</a>

	<!-- 
		 <a href="#"><span class="glyphicon glyphicon-comment" aria-hidden="true"></span> Star</a>-->
  </div>
</div>
{% endfor %}


{% if paginator.total_pages > 1 %}
<div class="pagination pull-right">
  <span><a class="btn  btn-sm disabled">Page: {{paginator.page}} of {{paginator.total_pages}}</a></span>
  {% if paginator.previous_page %}
  {% if paginator.previous_page == 1 %}
  <a class="btn  btn-sm" href="/blog">First</a>
  <a class="btn btn-sm" href="/blog">&laquo;</a>
  {% else %}
  <a class="btn btn-sm" href="/blog">First</a>
  <a class="btn btn-sm" href="/blog/page{{paginator.previous_page}}/">&laquo;</a>
  {% endif %}
  {% else %}
  <span><a class="btn  btn-sm disabled" href="/blog">First</a></span>
  <span><a class="btn  btn-sm disabled">&laquo;</a></span>
  {% endif %}
  {% assign dd = paginator.total_pages | minus:2 %}
  {% if paginator.page < 3 %}
	  {% assign start1 = 1  %}
	  {% assign end = 5  %}
  {% elsif paginator.page > dd %}
      {% assign start1 = paginator.total_pages | minus:4  %}
      {% assign end = paginator.total_pages  %}
  {% else %}
   {% assign start1 = paginator.page | minus:2  %}
   {% assign end = paginator.page | plus:2  %}
  {% endif %}
  {% for page in (start1..end) %}
   {% if page == paginator.page %}
   <a class="btn  btn-sm disabled" >{{ page }}</a>
   {% elsif page == 1 %}
   <a href="{{ '/blog/index.html' | prepend: site.baseurl | replace: '//', '/' }}" class="btn  btn-sm">{{ page }}</a>
   {% else %}
 <a href="{{ site.paginate_path | prepend: site.baseurl | replace: '//', '/' | replace: ':num', page }}" class="btn  btn-sm">{{ page }}</a>
   {% endif %}
 {% endfor %}
   {% if paginator.next_page %}
  <a class="btn  btn-sm" href="/blog/page{{paginator.next_page}}/">&raquo;</a>
  <a class="btn btn-sm" href="/blog/page{{paginator.total_pages}}/">Last</a>
  {% else if paginator.page == paginator.total_pages %}
  <span><a class="btn  btn-sm disabled">&raquo;</a></span>
  <span><a class="btn  btn-sm disabled">Last</a></span>
  {% endif %}
</div>
{% endif %}


<!-- Pagination links -->

{% comment %} 
<div class="pull-right">
  {% if paginator.previous_page %}
  {% if paginator.previous_page == 1 %}
  <a class="btn btn-primary btn-sm" href="/">Home</a>
  <a class="btn btn-primary btn-sm" href="/blog">&laquo; Prev</a>
  {% else %}
  <a class="btn btn-primary btn-sm" href="/">Home</a>
  <a class="btn btn-primary btn-sm" href="/blog/page{{paginator.previous_page}}/">&laquo; Prev</a>
  {% endif %}
  {% else %}
  <span><a class="btn btn-primary btn-sm disabled" href="/blog">Home</a></span>
  <span><a class="btn btn-primary btn-sm disabled">&laquo; Prev</a></span>
  {% endif %}
  <span><a class="btn btn-primary btn-sm disabled">Page: {{paginator.page}} of {{paginator.total_pages}}</a></span>
  {% if paginator.next_page %}
  <a class="btn btn-primary btn-sm" href="/blog/page{{paginator.next_page}}/">Next &raquo;</a>
  <a class="btn btn-primary btn-sm" href="/blog/page{{paginator.total_pages}}/">Last</a>
  {% else if paginator.page == paginator.total_pages %}
  <span><a class="btn btn-primary btn-sm disabled">Next &raquo;</a></span>
  <span><a class="btn btn-primary btn-sm disabled">Last</a></span>
  {% endif %}
</div>
and {% endcomment %}
<script type="text/javascript">
  
</script>

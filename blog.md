---
layout: default
title: Blog
---


<ul class="list-unstyled">
  {% for post in paginator.posts %}
  <li class="media">
    <div class="media-body">
      <h5 class="mt-0 mb-1">{{ post.title }}</h5>
      {{ post.excerpt }}[<a href="{{ post.url }}">>></a>]
    </div>
  </li>
    {% endfor %}

<!-- Pagination links -->
<div class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}" class="previous">
      Previous
    </a>
  {% else %}
    <span class="previous">Previous</span>
  {% endif %}
  <span class="page_number ">
    Page: {{ paginator.page }} of {{ paginator.total_pages }}
  </span>
  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}" class="next">Next</a>
  {% else %}
    <span class="next ">Next</span>
  {% endif %}
</div>
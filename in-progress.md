----------------------------------------------------------------------------------------
    
{% for eb in site.ebs %}
  <h2>
    <a href="{{ site.baseurl }}{{ eb.url }}">
      {{ eb.title }}  
    </a>
  </h2>
 
{% endfor %}


 <div class="posts">
  {% for eb in paginator.ebs %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}{{ eb.url | remove_first: '/'}}">
        {{ eb.title }}
      </a>
    </h1>

    <span class="post-date">{{ eb.date | date_to_string }}</span>

    {{ eb.description }}
  </div>
  {% endfor %}
</div>

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
----------------------------------------------------------------------------------------
 {% if paginator.total_pages > 1 %}
<div class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path | relative_url }}">&laquo; Prev</a>
  {% else %}
    <span>&laquo; Prev</span>
  {% endif %}

  {% for page in (1..paginator.total_pages) %}
    {% if page == paginator.page %}
      <em>{{ page }}</em>
    {% elsif page == 1 %}
      <a href="{{ paginator.previous_page_path | relative_url }}">{{ page }}</a>
    {% else %}
      <a href="{{ site.paginate_path | relative_url | replace: ':num', page }}">{{ page }}</a>
    {% endif %}
  {% endfor %}

  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path | relative_url }}">Next &raquo;</a>
  {% else %}
    <span>Next &raquo;</span>
  {% endif %}
</div>
{% endif %}
----------------------------------------------------------------------------------------

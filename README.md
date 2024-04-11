{% include gallery.html folder='/img' %}

OR
```
<div class="flow" markdown="1">
- list
</div>
```

{% if site.github.is_project_page %}
  <p class="view"><a href="{{ site.github.repository_url }}">View the Project on GitHub <small>{{ site.github.repository_nwo }}</small></a></p>
{% endif %}

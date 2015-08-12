---
layout: default
---

{% for page in site.posts %}
  {% include bigscreen.html %}
{% endfor %}

<script>
  setTimeout(function(){ document.location.reload(); }, 1000 * 60 * 5);
</script>

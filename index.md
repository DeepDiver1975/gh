<ul>
{% for version_hash in site.data.verions %}
{% assign version = version_hash[1] %}
  <li>
    <h1>{{ version.name }}</h1>
  </li>
{% endfor %}
</ul>

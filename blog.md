
<ul class="entries">
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">
    <h3>{{ post.date | date: "%d %B %Y" }} | {{ post.title }}</h3> 
    </a>
  </li>
  {% endfor %}
</ul>


<ul class="entries">
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">
    {{ post.date | date: "%d %B %Y" }} | {{ post.title }} 
    </a>
  </li>
  {% endfor %}
</ul>

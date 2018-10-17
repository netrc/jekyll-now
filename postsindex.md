
{% for post in site.posts %}
  <a href="{{ post.url }}"> {{ post.date | date: "%Y-%m-%d" }} - {{ post.title }} </a>
    <br>
{% endfor %}
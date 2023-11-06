# Daeon's Dandy Blog

<p style="color: red">Hello world</p>

![My first time coding](/assets/score counter.png)

## Recent posts
<ul>
{% for post in site.posts%}
<li>
<a href="/Blog{{post.url}}">{{1st post.title}}</a>
</li>
{% endfor %}
</ul>

<ul>
{% for post in site.posts%}
<li>
<a href="/Blog{{2023-10-4-second-post.url}}">{{A python todo.title}}</a>
</li>
{% endfor %}
</ul>
<ul>
{% for post in site.posts%}
<li>
<a href="/Blog{{2023-11-5-third-post.url}}">{{The titanic.title}}</a>
</li>
{% endfor %}
</ul>
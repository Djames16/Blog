# Daeon's Dandy Blog

<p style="color: red">Hello world</p>

![My first time coding](/assets/score counter.png)

## Recent posts
<ul>
{% for post in site.posts%}
<li>
<a href="/Blog{{post.url}}">{{post.title}}</a>
</li>
{% endfor %}
</ul>

<ul>
{% for post in site.posts%}
<li>
<a href="/Blog{{post.url}}">{{}}</a>
</li>
{% endfor %}
</ul>
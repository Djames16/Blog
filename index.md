# Daeon's Dandy Blog
##
###
####
#####
######
Hello *italisized* **bold**
```sql
SELECT * FROM 'users'
WHERE location = "USA"
```

- Thing 

1. Thing
<p style="color: red">Hello world</p>

![My first time coding](/assets/score counter.png)

## Recent posts
<ul>
{% for post in site.posts%}
<li>
<a href="/blog{{post.url}}">{{post.title}}</a>
</li>
{% endfor %}
</ul>
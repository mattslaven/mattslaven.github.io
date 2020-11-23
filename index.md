# My Projects
Here is a list of projects that I am working on:
<ul>
  <li><a href="https://mattslaven.github.io/HelloWorld/">Hello World Project</a></li>
  <li><a href="https://github.io/HelloWorld/">Hello World Project</a></li>
</ul>

# My Interests
I'm interested in technology & nature.

# My Blog
I'm considering creating a blog.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


# Get in Touch
<ul>
<li><a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>
<li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>

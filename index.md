## Moncef Trima's <small>personal webpage</small>

I am mostly interested in concurrency and in applying Computer Science to solve real world problems. I like to take long walks, hiking and going on trips by train...although, thanks to covid, I didn't get the chance to occupy myself with the last two, \*and\* to my disappointment, there are no railway services worthy of that name where I live.

Deep and long conversations are one of my favorite kinds of interactions. I like to talk about anything really (hum...more like what interests me :), but I most certainly enjoy being alone with my thoughts. Currently, I am looking for a job position as a programmer or as a consultant.

You can get in touch with me via email at **moncef [dot] trima [at] gmail [dot] com**

[Twitter](https://twitter.com/monceftrima), [GitHub](https://github.com/trima)

---
### Posts

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }} <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>

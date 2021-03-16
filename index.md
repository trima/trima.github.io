## Moncef Trima's <small>personal webpage</small>

You can get in touch with me via email at **moncef [dot] trima [at] gmail [dot] com**

Links : [Twitter](https://twitter.com/monceftrima), [GitHub](https://github.com/trima)

---

### Publications
- **Graphical notation and tool to design JCSP programs**  by Moncef Trima and Toufik Benouhiba. ISPS  2018. [DOI](https://doi.org/10.1109/ISPS.2018.8379013)

### Teaching experience
As a teaching assistant at UBMA university, I had the pleasure of teaching first year undergrads how to program.
- 2017-2018 - **Introduction to programming**. At the department of Math and CS. I designed the lab materials and examinations for my three groups. [Link](https://github.com/trima/L1MIAS2018){:target="_blank"}
- 2017-2018 - **Programming with C**. At the departement of Science and Technology. [Link](https://github.com/trima/L1ST2018){:target="_blank"}

---
### Posts

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }} <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>

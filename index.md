---
layout: default
title: "Curtis Humpherys"
---

<div style="padding: 2rem 0; text-align: center;">
  <h1 style="font-size: 2.8rem; margin-bottom: 0.5rem;">Curtis Humpherys</h1>
  <p style="font-size: 1.2rem; color: #555;">Welcome to my GitHub page</p>
</div>

---

## About Me
I’m Curtis Humpherys, a first year Computer Science student at Boise State.  
I’m exploring GitHub, Java, and other coding studies.

---

## What I’m Working On
- Course activities and assignments  
- Small web experiments  
- Notes and practice projects  
- Future portfolio content  

---

## Latest Posts
{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*  
{{ post.excerpt }}
{% endfor %}

---

## Links
- [GitHub Profile](https://github.com/curtishumpherys)
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [Boise State University](https://www.boisestate.edu)

---

## Contact
You can reach me through GitHub.

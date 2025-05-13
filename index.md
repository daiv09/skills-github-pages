---
layout: home
title: Welcome to my blog
---

# 👋 Hello and Welcome!

Welcome to my personal blog where I share insights, tutorials, and thoughts on tech, programming, and life. Whether you're a beginner or an experienced developer, there’s something here for everyone.

---

## 📝 Recent Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) <small>({{ post.date | date: "%B %d, %Y" }})</small>
{% endfor %}

[View all posts »](/blog)

---

## 🚀 What You’ll Find Here

- 💡 **Programming tutorials** (Python, C++, JavaScript, etc.)
- 📘 **Project breakdowns** – how I built them and what I learned
- 🛠️ **Tech tools & tips** to boost productivity
- 🎯 **Personal reflections** on learning, growth, and more

---

## 📬 Stay Connected

If you like what you read, feel free to [subscribe via RSS](/feed.xml) or follow me on:

- [GitHub](https://github.com/yourusername)
- [LinkedIn](https://www.linkedin.com/in/yourprofile)
- [Twitter](https://twitter.com/yourhandle)

Thanks for stopping by. Let’s build and learn together!

---

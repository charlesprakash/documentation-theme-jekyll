---
title: Testing the page syntax and others in Jekyll
hide_sidebar: true
permalink: main/test
---

## Reveal info
{{ page.path | relative_url }}

{{ "css/hello.css" | relative_url }}

{{ site.baseurl }}

[Take me there]({{ "/main/test" | relative_url }})

{% include image.html file="jekyll.png" url="/mydoc_alerts" alt="Jekyll" caption="This is a sample caption" %}

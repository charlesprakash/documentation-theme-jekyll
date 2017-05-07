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

| Path | Relative Path | URL | Permalink |
|------|---------------|-----|-----------|
{% for page in site.pages %}| {{ page.path }} | {{ page.relative_path }} | {{ page.url | relative_url }} | {{ page.permalink | relative_url }} |
{% endfor %}

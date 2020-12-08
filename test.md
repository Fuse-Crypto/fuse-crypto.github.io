---
layout: default
title: test
---

# Tests
<pre>
site: {{ site | jsonify }}

site.github.repository_url: {{ site.github.repository_url }}

page: {{ page | jsonify }}

page.url: {{ page.url }}

page.path: {{ page.path}}

page.relative_path: {{ page.relative_path}}
</pre>

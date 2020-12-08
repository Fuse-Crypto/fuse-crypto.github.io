---
layout: default
title: test
---

# Tests
<pre>
site.github.repository_url: {{ site.github.repository_url }}

page.url: {{ page.url }}

page.path: {{ page.path}}

page.relative_path: {{ page.relative_path}}

page: {{ page | jsonify | escape }}

site: {{ site | jsonify | escape }}

</pre>

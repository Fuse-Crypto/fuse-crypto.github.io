---
layout: default
title: test
---

# Tests
<pre>
page.path: {{ page.path}} 
page.name: {{ page.name }} 
page.url: {{ page.url }} 
page: {{ page | jsonify | escape }} 

site.github.repository_url: {{ site.github.repository_url }} 
site.github: {{ site.github | jsonify | escape }} 
site: {{ site | jsonify | escape }} 
</pre>

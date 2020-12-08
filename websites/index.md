---
layout: default
title: Fuse websites
---

# Fuse Websites

<table><tbody><tr><th>Website</th><th>URL</th></tr>
{% for website in site.data.websites %}
    <tr>
      <td>{{ website.name }}</td>
      <td><a href="{{ website.url }}" target="_blank">{{ website.url }}</a></td>
    </tr>
{% endfor %}
</tbody></table>

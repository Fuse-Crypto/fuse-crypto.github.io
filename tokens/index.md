---
layout: default
title: Tokens on the Fuse Network
---

# Tokens on the Fuse Network

Symbol | Name | Contract Address | token transfers | transactions
------ | ---- | ---------------- | --------- | ------------
{% for token in site.data.tokens %}
{{ token.symbol }} | {{ token.name}} | {{ token.address}} | [token transfers](https://explorer.fuse.io/tokens/{{ token.address}}/token_transfers){:target="_blank"} |  [transactions](https://explorer.fuse.io/address/{{ token.address}}/transactions){:target="_blank"}
{% endfor %}

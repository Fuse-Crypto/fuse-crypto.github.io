---
layout: default
title: Tokens on the Fuse Network
---

# Tokens on the Fuse Network

<table>
  <tbody>
    <tr>
      <th>Symbol</th>
      <th>Token Name</th>
      <th>Contract Address</th>
      <th>Token Transfers</th>
      <th>Transactions</th>
    </tr>
{% for token in site.data.tokens %}
    <tr>
      <td>{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td>{{ token.address }}</td>
      <td>[token transfers](https://explorer.fuse.io/tokens/{{ token.address }}/token_transfers){:target="_blank"}</td>
      <td>[transactions](https://explorer.fuse.io/address/{{ token.address }}/transactions){:target="_blank"}</td>
    </tr>
{% endfor %}
  </tbody>
</table>

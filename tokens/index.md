---
layout: default
title: Fuse Tokens
---

# Fuse Network Tokens

<table>
  <tbody>
    <tr>
      <th>Symbol</th>
      <th>Token Name</th>
      <th>Contract Address</th>
      <th>Token Transfers</th>
      <th>Transactions</th>
    </tr>
{% for token in site.data.fuse-tokens %}
    <tr>
      <td>{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td>{{ token.address }}</td>
      <td><a href="https://explorer.fuse.io/tokens/{{ token.address }}/token_transfers" target="_blank">token transfers</a></td>
      <td><a href="https://explorer.fuse.io/address/{{ token.address }}/transactions" target="_blank">transactions</a></td>
    </tr>
{% endfor %}
  </tbody>
</table>

# Ethereum Mainnet Tokens

<table>
  <tbody>
    <tr>
      <th>Symbol</th>
      <th>Token Name</th>
      <th>Contract Address</th>
      <th>Token Transfers</th>
      <th>Transactions</th>
    </tr>
{% for token in site.data.ethereum-tokens %}
    <tr>
      <td>{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td>{{ token.address }}</td>
      <td><a href="https://etherscan.io/token/{{ token.address }}" target="_blank">token transfers</a></td>
      <td><a href="https://etherscan.io/address/{{ token.address }}" target="_blank">transactions</a></td>
    </tr>
{% endfor %}
  </tbody>
</table>

---
layout: default
title: Liquidity Pools on the Fuse Network
---

# Liquidity Pools on the Fuse Network

<table><tbody><tr>
<th>Pool</th>
<th>Token 1</th>
<th>Token 2</th>
<th>Address</th>
<th>Token Holdings</th>
<th>Token Transfers</th>
<th>Transactions</th>
</tr>
{% for pool in site.data.fuse-liquidity-pools %}
    <tr>
      <td>{{ pool.name }}</td>
      <td class="symbol">{{ pool.token1 }}</td>
      <td class="symbol">{{ pool.token2 }}</td> 
      <td class="addr">{{ pool.address }}</td>
      <td><a href="https://explorer.fuse.io/address/{{ pool.address }}/tokens" target="_blank">token holdings</a></td>
      <td><a href="https://explorer.fuse.io/tokens/{{ pool.address }}/token_transfers" target="_blank">token transfers</a></td>
      <td><a href="https://explorer.fuse.io/address/{{ pool.address }}/transactions" target="_blank">transactions</a></td>
    </tr>
{% endfor %}
</tbody></table>

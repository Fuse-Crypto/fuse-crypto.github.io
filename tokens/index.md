---
layout: default
title: Fuse Tokens
---

# Fuse Network

## Tokens on the Fuse Network

<table><tbody><tr><th>Symbol</th><th>Token Name</th><th>Contract Address</th><th>Decimals</th><th>Token Transfers</th><th>Transactions</th></tr>
{% for token in site.data.fuse-tokens %}
    <tr>
      <td class="symbol">{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td class="addr">{{ token.address }}</td>
      <td class="r">{{ token.decimals }}</td>
      <td><a href="https://explorer.fuse.io/tokens/{{ token.address }}/token_transfers" target="_blank">token transfers</a></td>
      <td><a href="https://explorer.fuse.io/address/{{ token.address }}/transactions" target="_blank">transactions</a></td>
    </tr>
{% endfor %}
</tbody></table>

## Stablecoins on the Fuse Network

<table><tbody><tr><th>Symbol</th><th>Token Name</th><th>Contract Address</th><th>Decimals</th><th>Token Transfers</th><th>Transactions</th></tr>
{% for token in site.data.fuse-tokens-stablecoins %}
    <tr>
      <td class="symbol">{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td class="addr">{{ token.address }}</td>
      <td class="r">{{ token.decimals }}</td>
      <td><a href="https://explorer.fuse.io/tokens/{{ token.address }}/token_transfers" target="_blank">token transfers</a></td>
      <td><a href="https://explorer.fuse.io/address/{{ token.address }}/transactions" target="_blank">transactions</a></td>
    </tr>
{% endfor %}
</tbody></table>

## Liquidity Provider Tokens on the Fuse Network

<table><tbody><tr><th>Symbol</th><th>Token Name</th><th>Contract Address</th><th>Decimals</th><th>Token Transfers</th><th>Transactions</th></tr>
{% for token in site.data.fuse-tokens-liquidity-providers %}
    <tr>
      <td class="symbol">{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td class="addr">{{ token.address }}</td>
      <td class="r">{{ token.decimals }}</td>
      <td><a href="https://explorer.fuse.io/tokens/{{ token.address }}/token_transfers" target="_blank">token transfers</a></td>
      <td><a href="https://explorer.fuse.io/address/{{ token.address }}/transactions" target="_blank">transactions</a></td>
    </tr>
{% endfor %}
</tbody></table>

## Other Tokens on the Fuse Network

<table><tbody><tr><th>Symbol</th><th>Token Name</th><th>Contract Address</th><th>Decimals</th><th>Token Transfers</th><th>Transactions</th></tr>
{% for token in site.data.fuse-tokens-others %}
    <tr>
      <td class="symbol">{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td class="addr">{{ token.address }}</td>
      <td class="r">{{ token.decimals }}</td>
      <td><a href="https://explorer.fuse.io/tokens/{{ token.address }}/token_transfers" target="_blank">token transfers</a></td>
      <td><a href="https://explorer.fuse.io/address/{{ token.address }}/transactions" target="_blank">transactions</a></td>
    </tr>
{% endfor %}
</tbody></table>

# Ethereum Mainnet

<table>
  <tbody>
    <tr>
      <th>Symbol</th>
      <th>Token Name</th>
      <th>Contract Address</th>     
      <th>Decimals</th>
      <th>Token Transfers</th>
      <th>Transactions</th>
      <th>DEX Trades</th>
    </tr>
{% for token in site.data.ethereum-tokens %}
    <tr>
      <td class="symbol">{{ token.symbol }}</td>
      <td>{{ token.name }}</td>
      <td class="addr">{{ token.address }}</td>
      <td class="r">{{ token.decimals }}</td>
      <td><a href="https://etherscan.io/token/{{ token.address }}" target="_blank">Token Transfers</a></td>
      <td><a href="https://etherscan.io/address/{{ token.address }}" target="_blank">Transactions</a></td>
      <td><a href="https://etherscan.io/token/{{ token.address }}#tokenTrade" target="_blank">DEX Trades</a></td>
    </tr>
{% endfor %}
  </tbody>
</table>

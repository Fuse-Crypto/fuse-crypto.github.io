---
layout: default
title: Historic Prices - FUSE
---

# Historic Prices - FUSE

<table><tbody>
<tr>
  <th colspan="4">FUSE - USD</th>
</tr>
<tr>
  <th>snapped_at</th>
  <th>price</th>
  <th>market_cap</th>
  <th>total_volume</th>
</tr>
{% for price in site.data.feeds.fuse-usd-max %}
    <tr>
      <td>{{ price.snapped_at }}</td>
      <td>{{ price.price }}</td>
      <td>{{ price.market_cap }}</td>
      <td>{{ price.total_volume }}</td>                  
    </tr>
{% endfor %}
</tbody></table>

Source: CoinGecko

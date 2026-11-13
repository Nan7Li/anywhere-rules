# anywhere-rules

Anywhere（iOS/tvOS 原生代理客戶端）用的自訂分流規則集。

## AmazonJP.arrs

亞馬遜日本分流：`amazon.co.jp` 及其子網域、`amazon.jp`、`amzn.asia`、Kindle 舊域、商品圖 CDN、Prime Video JP、站內廣告。

匯入後要在 Routing 把這組指派到日本節點，`routing = 0`（Default）本身不會指定出口。

```
https://cdn.jsdelivr.net/gh/Nan7Li/anywhere-rules@main/AmazonJP.arrs
```

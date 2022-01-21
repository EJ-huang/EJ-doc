# 尹星資料

> An awesome project.
## 關聯表
```graphviz
digraph hierarchy {
  # 起始與結尾
  start [label="尹星"]

  # 過程
  node[shape=box]
  a [label="尹星官網"]


  # 連線邏輯

  a->藝誠科技 [label="網站開發商"]
  a->智邦生活館 [label="Server託管"]
  智邦生活館->local [label=" SSMS"]
  藝誠科技-> Pan [label="額外需求開發"]
}
```


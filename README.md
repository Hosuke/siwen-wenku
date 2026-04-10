# 斯文文庫

> 「子畏於匡，曰：『文王既沒，文不在茲乎？』」——《論語·子罕》

此乃一文言知識庫也。所納者，必文言之原典；所撰者，必文言之條目。
依四部分類法（經、史、子、集），不雜白話，不參外語。

## 用法

```sh
# 納原典
siwen 納 file path/to/text.md
# 或
siwen ingest file path/to/text.md

# 編原典為條目
siwen 編
# 或
siwen compile

# 立四部
siwen 部
# 或
siwen taxonomy

# 問於文庫
siwen 問 "夫子之道何如？"
# 或
siwen ask "夫子之道何如？"

# 啟web閣
siwen 閣
# 或
siwen web
```

## 諸目錄

- `raw/`——原典所藏
- `wiki/concepts/`——所編之條目
- `wiki/_meta/`——索引、四部、繫辭之屬
- `config.yaml`——文庫之配

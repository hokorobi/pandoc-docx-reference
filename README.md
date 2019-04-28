# reference.docx for Pandoc

現在、Sphinx でドキュメントを作成しているけれど、担当が変わる場合には継続したメンテナンスが期待できないと思っているので docx に変換して去るつもり。

- 見出しにアウトライン追加
- 標準、表題のフォントをメイリオに変更
- Source Code スタイルを追加

## 使い方

```
pandoc something.rst --from=rst --to=docx --reference-doc=reference.docx --output=something.docx
```


---
title: VS Codeで編集中のファイルが自動で保存されるようになった！
summary: なんか突然VS Codeが編集中のファイルを自動で保存するようになってしまいました、、原因は不明ですが、解決策をメモします。
categories:
  - VS Code
---

- 原因：Preferencesに設定が追加されてた
- 対応：User Preferencesから設定を削除

```diff
- "files.autoSave": "afterDelay"
+ "files.autoSave": "off"
```

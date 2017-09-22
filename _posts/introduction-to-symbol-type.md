---
title: 【JavaScript】Symbol型入門　+α
summary: 案件で遭遇したSymbol型を真面目に調べました。
categories:
  - JavaScript
---

# `Symbol`について

## `Symbol`オブジェクトについて

- `Symbol`オブジェクトは、**リファレンス型（参照型）**

- `Object`を継承するが、れんそうはいれつとしては　機能しない

- `typeof Symbol === 'symbol'`

### リファレンス型

値そのものではなく、値が置いてある場所を保持する。配列とかと一緒。

対して、`int`や`boolean`は**基本型**

## `Symbol`オブジェクトの種類

`Symbol`オブジェクトにはローカルなシンボルとグローバルなシンボルのに種類がある

## シンボルプロパティとして活用する

任意のオブジェクトにシンボルプロパティを追加することができる

---

# ローカルなシンボル

# 出典

- [http://hakuhin.jp/js/symbol.html](http://hakuhin.jp/js/symbol.html)

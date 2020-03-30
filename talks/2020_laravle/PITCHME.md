# Laravelソースコードリーディング

---

## アジェンダ
- この勉強会でのゴール
- Laravelについて
- ドキュメントの場所
- ソースコードの場所
  - 
  - laravel/laravelとlaravel/frameworkの違い
- PHPのマジックメソッドについて
  - `__call`, `__callStatic`
---
- PHPStormを使って実際に読んでいく
  - `User::find(1)`
- まとめ
---

## この勉強会でのゴール

1. フレームワークのコードを読む時きっかけを持ってもらう
2. コードを読みたいと思った時の入り口を知ってもらう

---

## Laravelについて

- PHP向けのフルスタックフレームワーク
- MITライセンスによる、オープンソースソフトウェア

---
## Laravelについて

- PHP向けのフルスタックフレームワーク
  - **つまり、ソースコードの規模が大きい**
- MITライセンスによる、オープンソースソフトウェア
  - **つまり、コードが公開されている!**

---
## 参考資料
- [Composerのcreate-projectが何をやっているのか調べてみた - Qiita](https://qiita.com/DQNEO/items/74f4bb8fe447e4582a97)
- [【Laravel】 第1回 Eloquent ソースコードリーディング - モデルの取得](https://qiita.com/mpyw/items/7c7e8dc665584122a275)
- [LaravelのUser::find(1)で知るコードの読み方](https://docs.google.com/presentation/d/1zs20cl5hGcWaXXj47NQ8DeTumo63i7_lpFPeAhM-TZA/edit#slide=id.p)

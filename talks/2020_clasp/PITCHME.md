---
marp: true
---

# GASとclaspで作る簡単Slackボット

---
GASとclaspを使ってゴミボットを作ってみました。
今回はそのGASとclaspについて紹介しようと思います。

---

## GASって何?
- Google Apps Scriptの略
- GmailやGoogleカレンダー、Googleマップなどといった、Googleのツールやサービスをプログラミング言語で操作できる実行環境
- javascriptで記述する

---
## GASの実行環境
- 2020/02からV8エンジン搭載
- つまりES6が使えます
---
- なんとGASは簡易的なサーバーとしても利用できます
- 時間指定での処理の実行
- HTTPリクエストのリッスン
---
## GASのコーディング
- ブラウザ上のエディタを使用してコーディングする
- 使い勝手がイマイチ…
---
## clasp
- Google謹製のCLIツール
- ローカル環境でGASのコーディングが行える
- 以下のことをおこなってくれる
    - GASプロジェクトの作成
    - コードプッシュ
    - コードプル
---
さらに
- デフォルトでTypescriptに対応
- コードプッシュ時にトランスパイルしてプッシュしてくれる
- ローカル環境にあるので、jestも動く
---
## Slackボットを作ってみよう!

---
すみません、時間が足りなかったので書けませんでした

---

![てへぺろ](https://3.bp.blogspot.com/-UIJJgNIW0Kg/Viipfnqvs8I/AAAAAAAAz5w/IP9_-9EASvo/s800/tehepero2_youngman.png)

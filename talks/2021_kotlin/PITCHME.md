# Kotlin入門してみた

---
### 目標

- Kotlinに興味を持ってもらう
- (できれば)Kotlinを書く人が増えてほしい
- (ゆくゆくは)会社でサーバーサイドKotlinを導入する

---
### 話すこと

- Kotoinって何?
- Kotlinは何ができるの?
- Kotlinの何がいいの?

---
### 話さないこと

- Kotlinの構文について
- Androidについて

---
### Kotlinって何?

---

- JetBrains社が主導で開発されているプログラミング言語
- 静的型付けのオブジェクト指向プログラミング
- Androidアプリ開発の公式言語に採用されている

---

- Better Java
- JVM(Java Virtual Machine: Java仮想マシン)上で動作する

---
### Kotlinは何ができるの?

---

- Android
- サーバーサイド(JVM)
- フロントエンド(Kotlin/JS)
- ネイティブアプリ(Kotlin/Native)

---
### Kotlinの何がいいの?

---

- Nullセーフなコードを簡単に書ける

```
// Notnull
val lang: String = "kotlin"

// Error
val lang: String = null

// Nullable
val language: String? = null
```

---

- Javaの資産を活用できる

```
import java.util.*

val javaArray = ArrayList<Int>()

```

- その逆も可能(JavaからKotlinの呼び出し)

---

- コードがシンプル
    - デフォルトのアクセス修飾子がpublic
    - 型推論
    - セミコロン不要
    - データクラス
    - インスタンス生成時のnewキーワードが不要

etc...

---

- JetBrainsが開発しているのでIntelliJで書きやすい

---

終わり

---


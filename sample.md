---
marp: true
theme: nextscape
size: 16:9
paginate: true
footer: "©2025 Organization Name"
title: タイトル
author: Organization Name.
---

<!-- _class: lead -->
<!-- _paginate: false -->

# タイトル

サブタイトル

<div class="title-date">2026/1/1</div>
<div class="title-author">名前</div>

---

## 使い方

<div class="text-sm">

1. 「marp-slide-template」をローカルにコピーします。
2. コピーしたフォルダをVS Code系エディタで開きます。
3. 拡張機能「Marp for VS Code」をインストールします。
4. 任意のフォルダを作成し、「sample.md」をコピーして編集します。
5. エディタ右上のMarpアイコン または、Ctrl + Shift + P で「Marp: Export Slide Deck...」を実行し、PDFやHTMLなどを選択して出力します。

</div>

---

## カスタマイズ

<div class="text-xs">

テーマをカスタマイズするには、[style/style.css] を修正してください。
:root 部にカスタマイズ用の変数を集約しています。

- 基本色（背景、文字、アクセントなど）
- リードスライド用の色（タイトル、文字など）
- グラデーション（背景、強調マーカーなど）
- ロゴ画像

</div>

---

## H2タイトル

- [こちらにMarpの詳しい解説があります。](https://zenn.dev/oyashiro846/articles/0deab8230432a5)

### H3タイトル

本文です。

#### H4タイトル

本文の**一部を強調**できます。

---

### 箇条書き

- リスト1
- リスト2
- リスト3

### 順序付きリスト

1. リスト1
2. リスト2
3. リスト3

---

## テーブル表示

|  | 列タイトル | 列タイトル | 列タイトル |
| --- | --- | --- | --- |
| 行タイトル | 値1 | 値2 | 値3 |
| 行タイトル | 値4 | 値5 | 値6 |
| 行タイトル | 値7 | 値8 | 値9 |

文字サイズを調整することもできます（※次ページ参照）

<div class="text-xs">

|  | 列タイトル | 列タイトル | 列タイトル |
| --- | --- | --- | --- |
| 行タイトル | 値1 | 値2 | 値3 |
| 行タイトル | 値4 | 値5 | 値6 |
| 行タイトル | 値7 | 値8 | 値9 |

</div>

---

## 文字サイズの調整

<div class="text-xxl">

XXLサイズ

</div>

<div class="text-xl">

XLサイズ

</div>

<div class="text-lg">

Lサイズ

</div>

通常サイズ

<div class="text-sm">

Sサイズ

</div>

<div class="text-xs">

XSサイズ

</div>

<div class="text-xxs">

XXSサイズ

</div>

---

<!-- _class: columns-2 -->

## 2カラムレイアウト

### 列タイトル

本文

### 列タイトル

本文

---

<!-- _class: columns-3 -->

## 3カラムレイアウト

### 列タイトル

本文

### 列タイトル

本文

### 列タイトル

本文

---

## 画像を右側に追加
表示比率を指定できます。
contain指定するとマージンが追加されます。

![bg contain right:35%](../images/logo-black.svg)

---

## 画像を左側に追加
表示比率を指定できます。
contain指定しないとマージン無しになります。

![bg left:35%](../images/sample-image.png)

---

## 画像を下側に追加
高さや幅をピクセルで指定できます。

![h:100](../images/logo-black.svg)

---

## 画像を背景全体に
画像の透明度を指定できます。

![bg cover opacity:0.35](../images/sample-image.png)

---
<!-- _color: white -->

## 画像を背景全体に
画像の明るさを指定できます。

![bg cover brightness:0.65](../images/sample-image.png)

---

## リンク
URLを書けばリンクになります。
https://note.com/kiyo_ai_note/n/n47e9657874a9

リンク文字を指定することもできます。
[Marpの解説リンク](https://note.com/kiyo_ai_note/n/n47e9657874a9)

※リスト形式にすると矢印マーカーが付きます

- [Marpの解説リンク](https://note.com/kiyo_ai_note/n/n47e9657874a9)
- [Marpの解説リンク](https://note.com/kiyo_ai_note/n/n47e9657874a9)

---

## コードブロック

```
class Program
{
    static void Main()
    {
        Console.WriteLine("Hello, Marp World!");
    }
}
```

---

## ボックス

任意の位置のボックスを追加します。

<div class="box">ブロック内のコンテンツです。
改行はそのまま反映されます。
</div>

<div class="box" data-icon="&#xf058;">アイコン付きボックス
</div>

<div class="box nowrap">

ボックス内にリストを入れる場合は、nowrapクラスを追加してください。

- リスト
- リスト
- リスト

</div>

---

## 注釈

ページ下端に注釈を記載します。

<div class="note">注釈ブロック1行目
注釈ブロック2行目
</div>

---

## Font Awesome が使用可能
[こちらのページ](https://fontawesome.com/search?o=r)でアイコンを検索し、HTMLをコピーして使用します。
10,000種類以上のアイコンがあります。

<div class="text-xxl"><i class="fa-solid fa-circle-info"></i></div>
<i class="fa-solid fa-circle-question"></i>
<i class="fa-solid fa-circle-check"></i>
<i class="fa-solid fa-comment"></i>
<i class="fa-solid fa-envelope"></i>
<i class="fa-solid fa-file"></i>

本文の中に含めることもできますよ <i class="fa-solid fa-thumbs-up"></i>

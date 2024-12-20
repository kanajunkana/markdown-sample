# Markdown Sample
Sample Document 日本語

これは Markdown のサンプルです。  
文字コードはUTF-8、改行コードはLFです。  


## 基本
### 一般の文章
ソースコード上での改行は反映されず、ひとつの段落にまとめられます。  

## 見出し
ナンバ記号[＃]の数で見出しレベルが指定できます。

(H1, H2 略)
### H3
#### H4
##### H5
###### H6

## コードブロック

```js
const a = 1;
a.toFixed();
```


## リスト
番号梨リストと番号付きリストがあります。  
いずれも記号の後にはスペースを1つ以上入れます。  
タブまたは4スペースでインデントが可能です。  

### 番号なしリスト
アスタリスク、プラス記号、ハイフンのいずれか

* コーヒー
    * ブレンド
    * アメリカン
* パスタ
* チーズ

### 番号付きリスト
数字とピリオドの後にスペース（番号は自動的に挿入されます。）

1. コーヒー
    1. ブレンド
    1. アメリカン
1. パスタ
1. チーズ


## 装飾

### 斜体
アスタリスクまたはアンダースコアで前後を *斜体* のように囲むと *斜体* になります。

### 太字
アスタリスクまたはアンダースコア２つで **太字** のように囲むと**太字** になります。

### 取り消し線
２連チルダで ~~取り消し線~~ のように囲むと ~~取り消し線~~ になります。


## 画像

### Markdown 記法
画像を掲載するには代替文字列を ![ ] で囲んだ後に、ファイルのURLまたは相対パスを( )で囲んで記述します。

![Sample Image](https://img.freepik.com/free-photo/abstract-autumn-beauty-multi-colored-leaf-vein-pattern-generated-by-ai_188544-9871.jpg)

### HTMLタグ
画像をサイズ指定で表示したい場合は、HTMLタグが利用可能です。

<img src="https://img.freepik.com/free-photo/abstract-autumn-beauty-multi-colored-leaf-vein-pattern-generated-by-ai_188544-9871.jpg" width="160">  


## リンク

Markdownには **インライン** と **リファレンス**  という二つのリンクスタイルがあります。

### インライン
インラインスタイルはリンク文字列を[ ]で囲んだ後にURLを( )で囲んで記述します。  

[example.com](https://www.exampel.com/).


### リファレンス
リファレンススタイルは、名前と番号を使って定義したリンクを参照するものです。


* [GOOGLE][1]
* [YAHOO][2]

[1]: https://www.google.co.jp "Google"
[2]: https://www.yahoo.co.jp "Yahoo!"


### 自動リンク

単純に&lt;&gt;でURIを囲むことで自動リンクにすることも出来ます。

<http://www.w3.org>


## 引用ブロック

> これは引用ブロックです。


## 表組
表組は、縦ストローク記号 [ | ] で枠組みを構成します。

| LEFT    | CENTER     | RIGHT  |
| ------- |:----------:| ------:|
| item1   | circle     | red    |
| item2   | triangle   | green  |
| item3   | rect       | blue   |

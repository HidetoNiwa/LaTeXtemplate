# LaTeXtemplate 

## タイトル

## 注意

### 画像ファイルに関して

ImageMagicでjpg,png等の画像ファイルをepsに変換する必要がある.

#### 準備

1. http://www.imagemagick.org/script/index.php にてImage Magickのインストールを行う
2. コマンドプロンプトを起動し、「magick --version」と入力して、PATHが通っているか確認する

#### 使用コマンド

"hoge.jpg"といった名前の画像を"hogehoge.eps"に変換したい場合、下記コマンドを画像フォルダのディレクトリで実行する。
>magick hoge.jpg eps2:hogehoge.eps

※今回はbatファイルを用意してあるのでその上にjpg等を持っていくと画像を作製してくれます。

## 構成

1. 緒言
   1. 研究背景
   2. 先行研究例
   3. 研究目的
   4. 論文構成
2. 実験方法
3. 解析方法
4. 結果・考察
5. 結言
6. 謝辞
7. 参考文献

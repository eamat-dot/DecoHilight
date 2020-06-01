# DecoHilight
秀丸エディタの強調表示ファイルを装飾するマクロ

## Description
秀丸からエクスポートした強調表示などの定義ファイル(*.hilight)に装飾をほどこして視覚的に分かりやすくします。

***DEMO:***

![demo](images/demo.gif)

## Features
- 編集中のファイルの設定を **hilight**ファイル形式で 新規秀丸に書き出します。

  （実行対象が**hilight**ファイルだった場合は直接装飾します。）

- フラグ解説などの説明文をコメントとして付加しします。

- hilightファイル自身をその定義通りの色で描写します。

詳しくは [readme.txt](src/DecoHilight/readme.txt)を読んでください。

## Requirement

- 秀丸エディタ  Ver.8  or later  - [ 秀まるおのホームページ](https://hide.maruo.co.jp/software/hidemaru.html)

- HmJre.dll  Ver. 2.03 or later (秀丸エディタに同梱)


## Installation

- DecoHilight.mac と \DecoHilight 以下のファイルを マクロフォルダ もしくは 任意のフォルダにコピーする。
- DecoHilight.macを 秀丸上でマクロ登録する。カラーリングやコメント挿入を単体で使いたい場合は ColorlingHilight.mac CommentingHilight.mac も登録する。
  
- アンインストール時は秀丸上でマクロ登録を解除の上、全てのファイルを削除して下さい。レジストリへの書込みはしていません。

## Usage

装飾したい hilightファイル、もしくは定義を見たいファイルタイプのファイルを秀丸で開き、DecoHilight.macを実行します。
編集中のファイルが hilightファイル形式のテキストであればそのまま、そうでない場合は、hilightファイル形式で新規秀丸に設定が書き出されてからコメント挿入とカラーリング装飾が行われます。

## Note

動作はかなり遅いです。

## Author

* eamat.
* E-mail : eamat.dot@gmail.com

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

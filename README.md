# MS-VBデータ変換プログラム
### VBのtsvデータをMSの行動系列データに変換する

## プログラム構成
### dividePerson.ipynb（事前準備）
tsvファイルに複数人のPerson indexが含まれる場合、このプログラムを実行し、各個人のtsvファイルに分ける必要がある。
変数「multi_persons_tsv_name」を必要に応じて変更する。

### convert.ipynb
メインの変換プログラム。VBのtsvデータをMSの行動系列データに変換する。
変数「input_tsv_name」等を必要に応じて変更する。
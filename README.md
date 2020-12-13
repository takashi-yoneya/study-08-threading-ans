# マルチスレッド
複数の処理を同時に実行させることで処理を高速化することができます。
スクレイピングなどで処理速度を上げたい場合に有効です。
参考：https://qiita.com/__init__/items/74b36eba31ccbc0364ed

## １　threadingモジュールを使用して、複数の処理を同時に実行してみよう
スレッド１でfor文を大量に回している状態でも、スレッド２は別の処理、print文などが実行できるとを確認してみよう\n
※実施する内容はこれ以外でも構いません。

## ２　全てのスレッドの完了を待ち受けて次の処理にすすめるようにしてみよう
参考URLの情報を基にやってみよう

## ３　課題２のマイナビスクレイピングをマルチスレッド処理により高速化してみよう
スレッド分割の方法は、１スレッドに対して１ページを割り当てて\n
１スレッド目→１ページ、２スレッド目→２ページ・・・というようにしてみよう

## ４　スレッド数を自由に選択できるようにしてみよう。またスレッド数に対するスクレピング速度を時間計測してみよう
スレッド数を増やすことで、スクレイピング速度が向上することを実感してみましょう

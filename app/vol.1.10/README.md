# vol.1.10

- 値の入力は`cin`を利用する
  - 入力方法は`cin>>`を利用する
- 値を入力先の変数が`int`の場合`char*`を入れても`int`のまま上書きされない
  ```
  数値を入力 >> hello
  a = 0
  a*3 = 0
  ```
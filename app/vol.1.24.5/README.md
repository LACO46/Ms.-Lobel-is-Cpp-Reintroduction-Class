# vo.1.24.5

- 文字列の比較には`strcmp()`を利用する
  - 第一引数の`char[]`と第二引数の`char[]`を比較する
  - 一致する場合は`0`を返す
  - 一致しない場合は`0以外`を返す
  - 文字列を直接`==`で比較することはできない
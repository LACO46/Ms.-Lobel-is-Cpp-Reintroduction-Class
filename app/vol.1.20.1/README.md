# vol.1.20.1

- `if(aaa){...} else if(bbb){...} else{...}`で条件分岐を複数定義できる
  - 条件は上から順番に判定される
    - 条件が一致するものがあった場合はif文を抜ける
  - `if()`で分岐を開始し、`else if()`で別の条件を追加し、`else`で条件に一致しなかったものを処理することができる
  - `continue`や`break`と組み合わせることで、ループを抜けたりスキップしたりできる
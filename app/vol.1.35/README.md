# vol.1.35

- 関数に配列を引数として渡す場合
  ```
  void Display(int array[]){ ... }
  ```

  - 引数で渡される`配列は長さがわからない`ので、`配列のポインタ`を引数として受け取る
  - `void Display(int *array[]) { ... }`でも意味は同じ

- 配列のポインタの長さを測る場合
  - ポインタ配列そのものの長さを測ることはできる
  - 引数として渡された配列の値の長さを知ることはできない
    - 余分な情報が付与されている
    ```
    数値 > 0
    番地 > 0x7ffc99f0a960

    数値 > 5
    番地 > 0x7ffc99f0a964

    数値 > 10
    番地 > 0x7ffc99f0a968

    数値 > 15
    番地 > 0x7ffc99f0a96c

    数値 > 20
    番地 > 0x7ffc99f0a970

    数値 > 32764
    番地 > 0x7ffc99f0a974

    数値 > 95603456
    番地 > 0x7ffc99f0a978

    数値 > -378048778
    番地 > 0x7ffc99f0a97c
    ```
  - 配列の長さを渡したい場合
    - 引数として、配列の長さを渡す
    - マクロとして配列の長さを定義する
# vol.1.1

- `cout >> "hello" >> endl;`はどうやら使えなさそう
- `iostream.h`は消えて、`iostream`をインクルードするだけで動く模様
- `printf`は使えそう

- コンパイルは`cc`とかではなく`g++`でできるらしい
- `g++ -o out hello.cpp`で`out`という実行ファイルが生成される
  - `-o`オプションがないと相変わらず`a.out`ファイルが生成される
- 実行ファイルの実行は`./out`で実行できる模様

- VScodeのフォーマット機能はなかなか強力
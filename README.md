# plusコマンド
![test](https://github.com/SomaKobayashi/robosys2022/actions/workflows/test.yml/badge.svg)

このplusコマンドは、任意の数字をすべて足し、その答えを知るために用いることができます。

## 実行環境

* WSL Ubuntu 18.04

## plusコマンドの動かし方

* 必要なソフトウェア
  * Python 3.7～3.10

* 実行方法
  * terminal上に以下の例のようにを打ち込む。
      * 例1 ./plus 1 2 3 4 5
        * 1,2,3,4,5の数字を足した結果が標準出力に表示される。
      * 例2 seq 10 | ./plus
        * 1～10の数字を足した結果が標準出力に表示される。

## plusコマンド説明

標準入力から読み込んだ数字を足し、結果を標準出力に表示する。

## ライセンス

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

© 2022 Soma Kobayashi


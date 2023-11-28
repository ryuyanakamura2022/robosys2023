![test](https://github.com/ryuyanakamura2022/robosys2023/actions/workflows/test.yml/badge.svg)

# robosys2023
このリポジトリはロボットシステム学の講義課題用のものです。

# plusコマンド
## 機能
標準入力で数字を入力する。読み込んだ数字まで繰り返し足し算を実行する。

## インストール方法
以下のコードをホームディレクトリで入力
```
git clone https://github.com/ryuyanakamura2022/robosys2023.git 
```
インストールが完了後、robosys2023のディレクトリに入る。
```
cd robosys2023
```
robosys2023に入れたならば、数値を入力する(実行例を参照)

## 実行例
robosys2023のディレクトリで標準入力を実行する。

標準入力
```
seq 4 | ./plus
```
結果
```
10
```
表示される。

任意の位置から計算する方法は以下のように実行する。

標準入力
```
seq 2 5 | ./plus
``` 
結果
```
14
```
表示される。

## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu 20.04 on windows

## ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです。
  * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022) 
* © 2023 Ryuya Nakamura

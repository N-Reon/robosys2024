# robosys2024 kadai1

# 概要
このコマンドは打球速度と打球角度を入力すると  
打球飛距離を算出ことができます。  
空気抵抗を無視して計算しているため  
非現実的な打球飛距離が算出されることがあります。

# 実行方法
$ python3 kadai1 打球速度(数字) 打球角度(数字)  
-注意-  
打球速度と打球角度に数字以外を入力するとエラーが出ます。

# 実行例
$ python3 kadai1 160 25  
打球飛距離は126 m

$ python3 kadai1 190 31  
打球飛距離は219 m

# ライセンスなど
#plusコマンド
![test](https://github.com/N-Reon/robosys2024/actions/workflows/test.yml/badge.savg)

このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
- このパッケージは，aaa由来のコード（© 2022 Hoge Fuge）を利用しています．
- このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
    - [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
- © 2024 Reon Nukui

# 必要なソフトウェア
- Python
  - テスト済みバージョン: 3.7~3.10

# テスト環境
- Ubuntu 24.24 LTS

@ 2024 Reon Nukui


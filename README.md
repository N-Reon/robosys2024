# 打球飛距離計算コマンド

## 概要
このコマンドは打球速度と打球角度を入力すると打球飛距離を算出ことができます。  
空気抵抗を無視して計算しているため  非現実的な打球飛距離が算出されることがあります。  
さぁ数字を入力して打球を飛ばせ！！

## 実行方法
実行方法は以下の通りです。  
```bash
$ python3 kadai1 打球速度(数字) 打球角度(数字)  
```
--注意--  
打球速度と打球角度に半角数字以外を入力するとエラーが出ます。

## 実行例
実行例は以下の通りです。
実行例１    
```bash
$ python3 kadai1 160 25  
打球飛距離は126 m
```
実行例２  
```bash
$ python3 kadai1 190 31  
打球飛距離は219 m
```

## インストール方法
インストール方法は以下の通りです。  
1, clone する。  
```bash
git clone https://github.com/N-Reon/robosys2024.git  
```
2, robosys2024に移動する。
```bash  
cd robosys2024
```
## ちょっとしたデータ
大谷選手の2024年シーズンの最高打球速度は191km/h  
NPBの平均速度は158.8km/h  
ホームランが出やすい角度は25~31度  

## ライセンスなど
#plusコマンド
![test](https://github.com/N-Reon/robosys2024/actions/workflows/test.yml/badge.savg)

このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．  
このコマンドは以下のサイトを参考にしています。  
https://nifs-k.repo.nii.ac.jp  
https://hiros-lab.com/barrelzone/  
https://keisan.casio.jp/exec/system/1204505751

## 必要なソフトウェア
- Python
  - テスト済みバージョン: 3.7~3.10

## テスト環境
- Ubuntu 22.24 LTS

@ 2024 Reon Nukui


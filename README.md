# robosys2020
ロボットシステム学　課題１

# 概要
LEDを点滅させることにより、モールス信号を表す。
今回は自分の名前「かいだん」というモールス信号を授業で扱ったソースコードを基準にして作成する。

# 動作環境
・ラズベリーパイ３B＋
・Ubuntu18.04

# 使用した部品
・5㎜LED
・抵抗（250Ω）

# インストール方法
```bash
$ git clone https://github.com/dankai0528/test.git
$ cd test
$ make
$ sudo insmod kadai.ko
$ sudo chmod 666 /dev/myled0
```

# 使用方法
```bash
$ echo 1 > /dev/myled0
```
これにより、光らせることができる。

# デモ動画
https://www.youtube.com/watch?v=WBCPGcDngKQ&feature=youtu.be

# ライセンス
GNU General Public License v3.0

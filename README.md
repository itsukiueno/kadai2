# ロボットシステム学課題２
2021年ロボットシステム学の講義で作成したROSのパッケージをベースに、作成・改造したものです。

コマンドを入力することによって数値が出力されます。

下に

# 動作環境
今回は以下の環境で動作を行いました。
〇Raspberry Pi 3 Model B

〇Os:ubuntu 20.04 server

# 利用したもの
〇Raspberry Pi 3 Model B

# インストール
以下の手順に従って入力してください。

① $ git@github.com:itsukiueno/kadai2.git


# 実行
以下のコマンドを打ち実行することができます。

### 手順１
まずは４つの端末を用意してそれぞれの端末で以下の表のコマンドを打ってください。

|  | 端末① | 端末② | 端末３ | 端末④ |
| :---: | :---: | :---: | :---: | :---: |
| コマンド | $ cd catkin_ws/src | $ cd catkin_ws | $ cd catkin_ws/src/mypkg/scripts | - |

### 手順２
端末①で $　roscore　と打ちます。

### 手順３
端末②で $　rosrun mypkg count.py　と打ちます。

### 手順４
端末③で $　rosrun mypkg twice.py　と打ちます。

### 手順５
端末④で $　rostopic echo /twice　と打ちます。

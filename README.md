# Jetson Nano Mouseのハードウェア情報

Jetson Nano Mouseのハードウェア情報 / Jetson Nano Mouse – Hardware Information

Jetson Nanoを使った左右独立二輪方式の小型移動プラットフォームロボットのハードウェア情報をまとめたリポジトリです。

![](https://rt-net.github.io/images/jetson-nano-mouse/jnmouse_step_cad.png)

公式サイトは[こちら(https://rt-net.jp/products/jetson-nano-mouse/)](https://rt-net.jp/products/jetson-nano-mouse/)です。

[3d_cad_data](./3d_cad_data)ディレクトリにはJetson Nano Mouseの3D CADデータが入っています。

[circuit diagram](./circuit_diagram)ディレクトリにはJetson Nano Mouseの回路図が入っています。

デバイスドライバは[rt-net/JetsonNanoMouse](https://github.com/rt-net/JetsonNanoMouse)のリポジトリで管理されています。

セットアップの際に使用するスクリプトや情報は[rt-net/jnmouse_utils](https://github.com/rt-net/jnmouse_utils)のリポジトリで管理されています。

## ロボットのハードウェアについて

### カメラ

カメラはSainSmart社の[IMX219 Camera Module for NVIDIA Jetson Nano Board | 8MP Sensor | 160 Degree FoV (SKU: 101-40-252)](https://www.sainsmart.com/products/sainsmart-imx219-camera-module-for-nvidia-jetson-nano-board-8mp-sensor-160-degree-fov)を採用しています。  
カメラの詳細なスペックについてはSainSmart社のページをご覧ください。  
搭載している2つのカメラ同士の距離は55mmとなるように設計されています。

![](https://rt-net.github.io/images/jetson-nano-mouse/jnmouse_dual_camera.png)

## 開発について

本リポジトリはオープンソースですが、開発はオープンではありません。  
機能追加については社内のガイドラインを優先します。  
誤植や不具合の修正は常時受け付けています。詳しくは[コントリビューションガイドライン](https://github.com/rt-net/.github/blob/master/CONTRIBUTING.md)に従ってください。

## ライセンス

(C) 2020 RT Corporation \<support@rt-net.jp\>

各ファイルはライセンスがファイル中に明記されている場合、そのライセンスに従います。特に明記されていない場合は、Apache License, Version 2.0に基づき公開されています。  
ライセンスの全文は[LICENSE](./LICENSE)または[https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)から確認できます。

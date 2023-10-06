# microservices

## 概要
- microservicesについて学習過程
- microservicesの概要をyoutubeなどで調べると、service単位で切り分けられたものを連携させることによるモジュール管理とわかった。
- Reactなどのフロントエンドでよく言われるアトミックデザインのバックエンド版なのかなとふと考える。

## 今回はサービスを連動させるところまで
- 今回はサービスをproduct-service, order-service, inventory-serviceの３つ
- discovery-server ３つ連動させる役割
- api-gateway URLを管理
# Nextcloudで自宅鯖プライベートクラウド
## はじめに

最近、YoutubeでStudy With Me動画を撮ることが趣味です。  
サボらないし、集中できるのでとても良いです。
そこで、撮影した動画データを自宅サーバーじ保存して、
一元的に管理できればなあと思い、Nextcloudを導入しました。

## Nextcloudとは

> Nextcloudは、オンラインストレージの作成と使用のためのクライアント・サーバ型のソフトウェアで、無料且つオープンソースソフトウェアでもある。機能的にはDropboxに似ているが、Dropboxはオンプレミスのオンラインストレージサービスは提供しない。Nextcloudはフリーかつオープンソースなので、誰でも自分のプライベートサーバ（英語版）にインストールして利用することができる。
（出典: Wikipedia）

要するに、自分専用のクラウドストレージを構築できるソフトウェアです。

## 基本的な手順

https://www.kagoya.jp/howto/cloud/vps/nextcloud_home/

このkagoyaの手順が非常に分かりやすいですが、もっとこうしたら良いのに、と思った点があったので
自分なりにアレンジした手順を以下に示します。


### 外付けHDDのマウント
マウントポイントの設定などはここでは割愛します。
Dockerコンテナ内にログインして、以下のコマンドを実行します。


## githubリポジトリ



https://www.reddit.com/r/NextCloud/comments/zzxogl/how_to_install_phpsmbclient_in_a_docker_container/?tl=ja
https://qiita.com/hiro-matsumoto/items/0648254dd5268db79978
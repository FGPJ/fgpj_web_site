# fgpj_wed_site

## 開発環境

Rails version: 6.1.4.4  
Ruby version: ruby 2.6.9p207 (2021-11-24 revision 67954) [x86_64-linux]  
Mysql 8.0  
Docker  

## 環境構築

1.Dockerの公式サイトからDockerをインストールしてください  
https://www.docker.com/

2.このプロジェクトからdevelopブランチをクローンしてください  

3.クローンしたプロジェクトフォルダ  ```/fgpj_wed_site```直下に以下の内容のファイルを作成する

.env  
```bash
DB_USERNAME="root"
DB_PASSWORD="password"
```
以降何か詰まったら追記すること　　

## ブランチ運用について

#### main 本番環境　　　
基本developからしかマージできない　　　

#### develop 開発環境　　
masterへマージするためのブランチ機能追加や改修を行うときはこのブランチから切っていく  
機能改修したものに関してはこのブランチにマージする

##### 新たブランチを切る時ときは目的に沿った名前でブランチを切ること  

* release 次にリリースするものを置くブランチ  
(例)release/brunch_name  

* feature　新機能開発中に使うブランチ  
(例)feature/brunch_name  

* hotfix　公開中のもののバグ修正用ブランチ  
(例)hotfix/brunch_name  

## 参考サイト

【Rails】Rails 6.0 x Docker x MySQLで環境構築（MACOS）  
https://qiita.com/nsy_13/items/9fbc929f173984c30b5d

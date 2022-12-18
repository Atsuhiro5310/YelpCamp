# YelpCamp

## 概要
ユーザーがキャンプ場を登録およびレビューできるWebサイトです。登録、レビューを作成するにはアカウントが必要です。
YelpCampはColt Steele氏の「The Web Developer Bootcamp」をKen Fukuyama氏が日本語版にしたUdemyのコースの一部になります。

## 機能
- ログイン前
  - キャンプ場の情報、書かれているレビューの閲覧
  - ユーザー登録
- ログイン後
  - キャンプ場の情報、書かれているレビューの閲覧
  - キャンプ場を新規登録、自分で登録したキャンプ場の編集、削除
  - レビューの追加、自分で登録したレビューの削除

## ローカルでの実行
1. [リポジトリのクローン](https://github.com/Atsuhiro5310/YelpCamp)を作成してください。
2. [MongoDB](https://www.mongodb.com/home)をインストールしてください。
3. [Cloudinary](https://cloudinary.com/)のアカウントを作成し、Cloud Name、API Key、API Secretの3つを取得してください。
4. [mapbox](https://www.mapbox.com/)のアカウントを作成し、Access tokenを取得してください。
5. .envファイルを作成し、手順3,4で取得した情報を入力してください。
```
CLOUDINARY_CLOUD_NAME=<Cloud Name>
CLOUDINARY_KEY=<API Key>
CLOUDINARY_SECRET=<API Secret>
MAPBOX_TOKEN=<Access token>
```
6. 以下のようにターミナルでNPMパッケージをインストール
```
$ cd YelpCamp-main
$ npm install
```
7. ターミナルで```mongod```と別のターミナルで```node app.js```を実行してください。
8. [localhost:3000](http://localhost:3000/)に移動し、サーバーを起動させます。

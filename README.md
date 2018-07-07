# 何やったか
https://dotinstall.com/lessons/hosting_firebase
を通して、firebase hosting の使い方について学んだ

# 行なった手順
``` bash
// Nuxt でやってみた
$ yarn create nuxt-app firebase-hosting
$ cd firebase-hosting
$ yarn install

// firebase でプロジェクト作った後に以下を実行
$ yarn global add firebase-tools
$ firebase login // firebase にログイン
$ firebase init // hosting サービスを使うよとか、公開するディレクトリの指定とかの設定を行なった
$ yarn generate // 公開ディレクトリにファイルを生成
$ firebase deploy // 公開
```

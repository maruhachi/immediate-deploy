# Immediate deploy

> Nuxt.js project

## ちゃっちゃかデプロイ4人衆
* pushしたら即公開！ **GitHubPages**
* みんなしってる！ **Heroku**
* Herokuっぽく使える！ **Netlify**
* は、早すぎる！ **Now**
  * https://zeit.co/now#whats-now

## GitHub Pages
* リポジトリの `setting` から
* 'master' ブランチを直で
* 'master' ブランチの 'docs' フォルダ
  * 'src' ブランチを公開するやつは無くなったみたい？

[実例はこちら](https://maruhachi.github.io/immediate-deploy/)

## [heroku](https://dashboard.heroku.com/apps/nuxt-suburi)
* いつもどおりGitHubと連携か、gitのremoteに追加
* 今回は連携して自動ビルド
* 普通に`nodejs`のビルドパックを選択しても動かない
  * [公式にある手順](https://ja.nuxtjs.org/faq/heroku-deployment/) でデプロイできるようになる

[実例はこちら](https://nuxt-suburi.herokuapp.com/) 

## [Netlify](https://app.netlify.com/sites/focused-babbage-bfd300/deploys/5b76af7e4ed62f2cd9a7f8d2)
* GitHubアカウントでOAuthログインすると
  選択肢にリポジトリが現れる。
* ビルドコマンドと静的ファイルの出力先ディレクトリを設定すると、そのディレクトリ配下をホスティングしてくれる。

[実例はこちら](https://focused-babbage-bfd300.netlify.com/)


## [Now](https://zeit.co/now)
* もはや3文字打つだけでデプロイ可能

[実例はこちら](https://docs-tsjqywbweh.now.sh/)


## Build Setup

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).


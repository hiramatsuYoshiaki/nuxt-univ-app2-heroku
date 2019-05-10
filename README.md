# nuxt-univ-app2-heroku

> nuxt universal SSR HEROKU EXPRESS

`heroku pipeline test`

## Build Setup

``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
 
### herokuのパイプラインを使う
1. GitHubにリポジトリを作りmasterブランチにプッシュする。
2. 開発用ブランチ(dev)を作りプッシュする。
3. 新規プロジェクト(nuxt-univ-app2)を作成する。
4. パイプラインを作成する
5. 
6. 
7. 
8. 
9. 
10. 

### Github
1. 新しいリポジトリを作ってプッシュする。
```
$ git add -A
$ git commit -m 'create-nuxt-app first commit'
$ git add remote origin https://github.com/hiramatsuYoshiaki/nuxt-univ-app2-heroku.git
$ git push --set-upstream origin master
```
2. 開発ブランチを作ってプッシュする。
```
$ git branch dev
$ git checkout branch
$ git push  --set-upstream origin dev 
```
master --- dev
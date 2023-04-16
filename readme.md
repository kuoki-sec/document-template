# 設計書テンプレート

## 目的
- このドキュメントは、プロジェクトの設計書を記述するためのテンプレートです。

## 概要

## インストール方法

1. 以下のコマンドを実行してください。

composer
```bash
composer install xxxx\https://github.com/kuoki-sec/document-template.git
```

npm
```bash
npm install xxxx\
```

## 使い方

1. GitHubのWikiを利用してください。
2. Create New Pageをクリックしてください。
3. Home.mdをクリックしてください。
4. 下記のコマンドを実行してください。

$ cd [project]
$ git submodule add https://github.com/[user]/[project].wiki.git

```
git submodule add https://github.com/kuoki-sec/document-template.wiki.git
```


## 参考
- GitHub 基本的な書き方とフォーマットの構文  
https://docs.github.com/ja/enterprise-server@3.8/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images

- GitHub ウィキについて
https://docs.github.com/ja/enterprise-server@3.8/communities/documenting-your-project-with-wikis/about-wikis

- GitHubで仕様書管理をしてみる  
https://blog.spacemarket.com/code/document/


## 参考

```
$ cd [project]
$ //git submodule add https://github.com/[user]/[project].wiki.git
$ git submodule add https://github.com/kuoki-sec/document-template.wiki.git
```


## フォントについて
'BIZ UDゴシック'推奨

## 画像パス確認

- images/Goole.png  
![相対パス1](images/Goole.png)

- /images/Goole.png  
![相対パス2](/images/Goole.png)

- /docs/images/Google.png  
![パス4](/docs/images/Google.png)

- https://github.com/[user]/[project].wiki/images/Google.png
![](https://github.com/kuoki-sec/document-template.wiki/images/Google.png)


- Issues URL  
![issuesのリンク](https://user-images.githubusercontent.com/2370633/232225693-aa8f0966-a388-4e29-8d9a-f7e349c45175.png)

## 他のMarkdownページからのリンク

[](docs/01.要件定義.md)
[](docs/01-youken.md)
[](/docs/01-youken.md)
# 設計書テンプレート

## 目的
- このドキュメントは、プロジェクトの設計書を記述するためのテンプレートです。


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

## 画像パス確認（検証）

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

- どれでもいける。

- [docs/01.要件定義.md](docs/01.要件定義.md)
- [docs/01-youken.md](docs/01-youken.md)
- [/docs/01-youken.md](/docs/01-youken.md)
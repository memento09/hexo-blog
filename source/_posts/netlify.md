---
title: netlify格闘日記 01
date: 2020-03-06 15:09:07
categories:
  - [dialy]
tags:
  - [netlify]
  - [hexo]
---

## netlify
CMSが使いたくてgithub pagesから移行中。
<!-- more -->
移行手順は豊富に情報があるので簡単でした。ただ、以下の点でうまくいかず格闘中。

1. 追加したテーマが読み込まれない
2. githubを介さずアップロードできない

1で色々試した末、デフォルトのlandscapeに戻したら読み込まれた。別のテーマを追加してまた試したい。
2はtokenとsite idを_config.ymlに設定してnetlifyに直接デプロイするというもの。
こちらはエラーメッセージから何かのパッケージが入っていないように思われる。

まずは外出先からも投稿できるようにしたい。

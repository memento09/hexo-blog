---
permalink: netlifycms-test
layout: blog
title: Netlify CMS配信テスト
date: '2020-03-08T20:43:51+09:00'
thumbnail: /images/uploads/bg.jpg
---
## やっとログインできた！

基本的には[公式ガイド](https://www.netlifycms.org/docs/add-to-your-site/ "Add to Your Site")の通りに設定。ただそれだとadmin画面でログインできず七転八倒。

結果、config.ymlの設定を以下の様に変更するとログインできた。

```html:config.yml
backend:
  name: github
```

---
title: 設定Hexo x 順利部屬GitHub page!
date: 2017-05-15 16:42:19
tags: Hexo, GitHub page
categories: 新手上路
---

開心的Hexo在local端架好後、當然要衝一下放到github page上!
然後就遇到了一些小小要注意的地方... 寫下來筆記一下...
這部分也可以參考Hexo官方的[deployment](https://hexo.io/zh-tw/docs/deployment.html)說明。

1.首先最重要的是 - 先去github上開新repo! 
repo name default就是 githubpage顯示名稱，所以開repo的時候最好想一下希望的pulibc URL顯示名稱，當然之後都還是可以再換成custom domain name。
以本blog為例，我的github account: shenevol, repo name: blog,
則default github page首頁URL為 https://shenevol.github.io/blog/

github ok後、回來local端準備:
我習慣先在local端看一下到底架起來長怎樣:　
```
Hexo Server
```
2.安裝 [hexo-deployer-git](https://github.com/hexojs/hexo-deployer-git)
```
$ npm install hexo-deployer-git --save
```
3.去Hexo目錄底下 _config.yml修改部屬位置:
```
deploy: 
  type: git
  repo: git@github.com:github_account_name/repo_name.git
```
除了這個之外還要記得修改url阿

```
url: http://github_account_name.github.io/repo_name/
root: /repo_name
```

4.local端git push, 我是用基本的master branch
```
git push -u origin master
```

5.成功push後去repo修改**Setting**，準備發佈
因為採用Hexo架構，要把Source調成**gh-pages branch** 。
(關於選擇master/gh-page差異，可以參考這篇問答:[link](http://stackoverflow.com/questions/25559292/github-page-shows-master-branch-not-gh-pages))

接下來就大功告成啦! 網址就是步驟3的URL囉。
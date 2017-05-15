---
title: 如何選擇適合你的Hexo Theme? 4款實用主題推薦。
date: 2017-05-15 18:02:46
tags:
---

把Hexo架起來後，立刻會遇到佈景主題選擇的困境。
Hexo官網有介紹不少主題: [Hexo Theme](https://hexo.io/themes/)，或是官方github上也有相同整理: [Themes](https://github.com/hexojs/hexo/wiki/Themes)。
前者有縮圖顯示，方便直接預覽layout，後者選項較多。

個人在選擇主題上花了一點時間，抉擇原則如下:

**1.滿意視覺設計:**
最重要的一點，簡單來說就是看起來爽啦! 看順眼才會用的喜歡、寫的開心。
喜不喜歡每個人很主觀，各取所好。像我個人偏好我就是愛小字(font-size <= 16px)，喜歡淺色背景，
若是筆電size螢幕時最好有sidebar固定在旁邊。
最方便的方式就是找你喜歡blog的Hexo樣式，或是live demo site。
多看多比較，看多款之後會慢慢對自己想要的樣式收斂。

**2.功能擴充方便:**
想讓訪客留言互動嗎? 那你需要留言板、像本站就採用最常見的的[Disqus](https://disqus.com/)。
想知道是誰來拜訪blog嗎? 那[Google Analytics](https://www.google.com.tw/intl/zh-TW/analytics/)就是必備武器。
Hexo 本質上還是一個網站，周邊功能要加一定都可以，差異是要自己手刻程式碼，
或主題就打包好一切、只要改config就一鍵完成。

懶人如我想當然就選擇後者...所以在挑主題時一看到喜歡的theme，就立刻去看<code>_config.yml</code>。
如果有打包好<code>disgus</code>就會省很多工。
有些主題定位就是給自己的生活記事本，敘事風格，不打算支援和他人交流，自然就會少此功能。

每個主題支援的功能擴充不盡相同，像我最終選的[maupassant](https://github.com/tufu9441/maupassant-hexo)就是我看過擴充最多的哈哈。
有時候主題挑了半天很開心、結果想要的功能沒支援就歪邀了，參考自己想要的功能去確認吧。

**3.元件樣式支援:**
每個主題都有自己支援的HTML元件樣式，像[maupassant](https://github.com/tufu9441/maupassant-hexo) link 就是 #01579f。
code的顯示方式如下，常見的~~murmur專用~~刪節線和程式語言高亮也有支援。
```
I am code block demo
```
雖說大多demo site做得很完整，通常樣式文都可以看到，但有些特殊效果還是要特別留意，
並非每個主題每種元件都有支援，或是元件顯示layout可能跟想像中不同。
最直接的方式就是裝主題發篇post就可以立即分曉了。

當然程式碼...要手刻一定可以做得到，
要怎樣把主題當成自己的repo然後用git submodule去小修成想要的樣式又是另個故事了...

**4.持續更新維護:**
Hexo框架推出也一段時間了... 代代優秀主題倍出，但有些主題author已失去聯絡、或是宣告不再更新。
有無持續維護重不重要見仁見智，但有人問總比沒人問好XD。
舉例來說，[maupassant](https://github.com/tufu9441/maupassant-hexo) 的作者tufu9441現在都還會在個人blog教導user如何使用，
完全是佛心客服來著，留言討論版可謂Hexo theme安裝101，主題近期新增的多國語言功能也很用心。

最後分享5款推薦主題，也都是我選擇時的口袋名單:

1. [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo) 
超可愛的主題、Star 902的人氣之作! 配色清爽明朗、版面設計乾淨簡單，非常討喜。
Disqus也有支援，常見元件也都有。使用上也有詳盡的document說明、甚至有影片指導如何安裝。
可惜的是作者已宣告不再接受新feature的pull request了。

2. [Anatole](https://github.com/Ben02/hexo-theme-Anatole)
有我喜愛的sidebar fix，配色和版面乾淨簡約，很符合主題名稱**無念**。
Disqus有支援，作者本身也歡迎客製化開發服務，若喜歡者可以以微信支付表達對該主題的愛。
這主題曾是我一時之選，但就在安裝後覺得nav字太小了...
要改又覺得有點麻煩，所以就這樣了...

3. [maupassant](https://github.com/tufu9441/maupassant-hexo)
就是本blog現在採用的主題。功能十分完整、如分類、標籤、關於，
接近一般網誌/個人網頁的功能皆有，<code>_config.yml</code>可見豐富擴充功能。
其他優點我想上述都已提及就不贅述 XD
Star 946完全展現高人氣和用心經營的結果。

4. [Apollo](https://github.com/joyceim/hexo-theme-apollo)
最後一個是私心推薦，和1同名的簡潔之作。
原始設計是從 [SANOGRAPHIX.NET](https://github.com/sanographix/tumblr/tree/master/apollo) apollo design for Tumblr theme開始，後來migrate到Hexo平台上。
配色大方簡單，版面配置比例和平衡都很好，很有設計感的主題。
缺點則是沒有現成disqus可使用。

因為喜歡才特別在意，主題也可以挑這麼久。
但老話一句，內容產出才最重要，所以選了喜歡的就開始吧!
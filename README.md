# NexT for ghost

forked from https://github.com/microud/ghost-theme-next

謹此 致謝 `microud`

## What's the Difference

- 僅留 `NexT.Mist` 主題以減少容量
- 移除文章內的圖片框線樣式
- 以 `articles` 取代 `records` 頁面
- 以 `disqus` 取代 `duoshuo`
- 用語繁中化

基本環境安裝與設定，可參考原repo。

## Config Injection
<pre>
  <div id="site-config">
  {
      "author_name": YOUR_NAME,
      "disqus_name": DISQUS_SHORT_NAME,
      "links": [
      {
          "name": LINK_NAME,
          "link": LINK_URL
      }
      ]
  }
  </div>
</pre>

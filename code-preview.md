---
layout: null
title: 程式碼展示中心
permalink: /code-preview/
---

<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }} - GTech</title>
    
    <link rel="stylesheet" href="../style.css">
</head>
<body>

    <div class="bg-glow"></div>
    <div class="floating-shape shape-green"></div>
    <div class="floating-shape shape-blue"></div>

    <div class="container container-wide">

      <div style="margin-top: 60px; margin-bottom: 30px;">
        <a href="../" class="btn">← 返回首頁</a>
      </div>

      <h1 style="margin-bottom: 10px;">程式碼預覽介面</h1>
      <p style="color: #888; margin-bottom: 50px; font-weight: 300;">
        這裡展示公司核心的技術解決方案與前端特效。
      </p>

      <div class="code-window">
        <div class="window-header">
          <div class="dot red"></div>
          <div class="dot yellow"></div>
          <div class="dot green"></div>
          <div class="window-title">css/neon-effect.css</div>
        </div>
        <div class="window-body">

```css
/* SEDA G-Tech 品牌綠霓虹燈特效 */
.neon-text:hover {
  text-shadow: 0 0 10px #fff, /* 白光核心 */ 0 0 20px #5ca761,
    /* 淺綠光暈 */ 0 0 40px #5ca761, /* 中層擴散 */ 0 0 80px #5ca761; /* 氛圍背光 */
}
```

</div> 
</div> 
</div>
</body>
</html>

---
layout: default
title: 程式碼展示中心
permalink: /code-preview/
---

<a href="../" style="display:inline-block; margin-bottom:20px; color:#aaa; text-decoration:none;">← 返回首頁</a>

# 程式碼預覽介面

這裡展示公司核心的技術解決方案與前端特效。

## 專案：Neon Light Effect

<div class="demo-box" style="border:1px solid #333; padding:40px; text-align:center; background:#000; margin:20px 0; border-radius:10px;">
  <div class="neon-text">HOVER ME</div>
</div>

<style>
  .neon-text {
    font-size: 3rem;
    color: #fff;
    font-weight: bold;
    text-shadow: 0 0 5px #fff;
    cursor: pointer;
    transition: 0.3s;
  }
  .neon-text:hover {
    text-shadow: 0 0 5px #fff, 0 0 20px #0ff, 0 0 40px #0ff;
  }
</style>

### 核心程式碼 (React / CSS)

```css
.neon-text:hover {
  text-shadow: 
    0 0 5px #fff, 
    0 0 20px #0ff, 
    0 0 40px #0ff;
}
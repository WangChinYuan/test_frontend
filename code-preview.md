---
layout: default
title: 程式碼展示中心
permalink: /code-preview/
---

<style>
  body {
    background-color: #1a1a1a !important;
    color: #e0e0e0 !important;
  }
  .wrapper { max-width: 1000px; margin: 0 auto; padding: 40px; }
  h1, h2 { color: #fff; border-bottom: 1px solid #333; padding-bottom: 10px; }
  code { background-color: #333 !important; color: #ff9 !important; }
  
  /* 返回按鈕 */
  .back-btn {
    display: inline-block;
    margin-bottom: 20px;
    color: #888;
    text-decoration: none;
    font-size: 0.9rem;
  }
  .back-btn:hover { color: #fff; }
</style>

<div class="wrapper">

<a href="../" class="back-btn">← 返回首頁</a>

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
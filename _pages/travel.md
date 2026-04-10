
---
layout: splash
title: Travel Footprints
permalink: /travel/
---

<!-- 页面介绍部分 -->
<div style="text-align: center; margin-bottom: 2.5rem;">
    <h1>🌍 世界在我的脚下</h1>
    <p style="color: #5a5a5a;">用双脚丈量世界，用镜头记录美好。</p>
    <hr style="width: 80px; border: none; height: 2px; background-color: #ddd; margin: 0.5rem auto;">
</div>

<!-- 照片画廊代码 -->
<style>
    .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 1.5rem;
        margin-top: 1.5rem;
    }
    .gallery-item {
        width: 300px;
        background: #fff;
        border-radius: 12px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        overflow: hidden;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .gallery-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
    .gallery-item img {
        width: 100%;
        height: 200px;
        object-fit: cover;
        display: block;
    }
    .caption {
        padding: 0.8rem 1rem;
        text-align: center;
        font-size: 0.9rem;
        color: #333;
        border-top: 1px solid #eee;
    }
    @media (max-width: 768px) {
        .gallery-item { width: 90%; }
        .gallery-item img { height: auto; }
    }
</style>

<div class="gallery">
    <!-- 每个 .gallery-item 是一张照片 -->
    <div class="gallery-item">
        <img src="/assets/images/travel/madrid.jpg" alt="马德里">
        <div class="caption">🇪🇸 马德里，2024夏</div>
    </div>
    <div class="gallery-item">
        <img src="/assets/images/travel/paris.jpg" alt="巴黎">
        <div class="caption">🇫🇷 巴黎，2024春</div>
    </div>
    <div class="gallery-item">
        <img src="/assets/images/travel/rome.jpg" alt="罗马">
        <div class="caption">🇮🇹 罗马，2023秋</div>
    </div>
    <!-- 继续添加更多照片 -->
</div>

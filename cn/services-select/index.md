---
layout: splash
title: 日本名品 · 优品选购
classes: wide
header:
  overlay_image: /assets/images/cn-hero.jpg
  overlay_filter: 0.3
  overlay_color: "#000"
  actions:
    - label: "联系我们"
      url: "/cn/contact/"
   - label: "🇯🇵 日本語"
      url: "/cn/services-select/"
      class: "btn--outline"     
---

<h2 style="text-align:center; margin-top:2.5em;">
  日本名品 · 优品选购
</h2>
<p style="text-align:center; color:#666;">
  精选日本市场高品质商品，提供选购建议与代办支持
</p>

<div class="product-grid">

  <!-- ⭐ 重点推荐商品 -->
  <div class="product-card">
    <img src="/assets/images/p01.jpg" alt="日本本土高端化妆品">
    <h3>SK-II、资生堂高端护肤套装</h3>
    <p class="tag">美妆 · 资生堂</p>
    <ul>
      <li>日本本土专供</li>
      <li>适合商务礼赠</li>
    </ul>
    <p class="price">价格以咨询时为准</p>
    <div class="spacer"></div>
    <a href="/cn/contact/" class="btn btn--outline btn--small">咨询选购</a>
  </div>

  <div class="product-card">
    <img src="/assets/images/p02.jpg" alt="日本机能性保健食品">
    <h3>日本机能性保健食品</h3>
    <p class="tag">健康 · 本土品牌</p>
    <ul>
      <li>机能性标示食品</li>
      <li>适合长期服用</li>
    </ul>
    <p class="price">价格以咨询时为准</p>
    <div class="spacer"></div>
    <a href="/cn/contact/" class="btn btn--outline btn--small">咨询选购</a>
  </div>

  <div class="product-card">
    <img src="/assets/images/p03.jpg" alt="日本高品质生活用品">
    <h3>日本高品质生活用品</h3>
    <p class="tag">生活 · 日用精选</p>
    <ul>
      <li>做工精细</li>
      <li>日本家庭常用</li>
    </ul>
    <p class="price">价格以咨询时为准</p>
    <div class="spacer"></div>
    <a href="/cn/contact/" class="btn btn--outline btn--small">咨询选购</a>
  </div>

  <div class="product-card">
    <img src="/assets/images/p04.jpg" alt="日本高品质小家电">
    <h3>日本原产地高品质小家电</h3>
    <p class="tag">生活 · 日用精选</p>
    <ul>
      <li>做工精细</li>
      <li>日本家庭常用</li>
    </ul>
    <p class="price">价格以咨询时为准</p>
    <div class="spacer"></div>
    <a href="/cn/contact/" class="btn btn--outline btn--small">咨询选购</a>
  </div>

  <div class="product-card">
    <img src="/assets/images/p05.jpg" alt="世界奢侈品代购">
    <h3>世界奢侈品代购</h3>
    <p class="tag">精选 · 高端品牌</p>
    <ul>
      <li>正规渠道</li>
      <li>适合定制选购</li>
    </ul>
    <p class="price">价格以咨询时为准</p>
    <div class="spacer"></div>
    <a href="/cn/contact/" class="btn btn--outline btn--small">咨询选购</a>
  </div>

  <div class="product-card">
    <img src="/assets/images/p06.jpg" alt="日本高端服饰系列">
    <h3>日本本土产高级服装、跑鞋</h3>
    <p class="tag">服饰 · 本土品牌</p>
    <ul>
      <li>舒适耐用</li>
      <li>日本市场主流款</li>
    </ul>
    <p class="price">价格以咨询时为准</p>
    <div class="spacer"></div>
    <a href="/cn/contact/" class="btn btn--outline btn--small">咨询选购</a>
  </div>

</div>
<style>
.product-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.8em;
  margin-top: 3em;
}

/* 平板 */
@media (max-width: 1024px) {
  .product-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* 手机 */
@media (max-width: 640px) {
  .product-grid {
    grid-template-columns: 1fr;
  }
}

.product-card {
  background: #fff;
  padding: 1.5em;
  border-radius: 14px;
  box-shadow: 0 10px 25px rgba(0,0,0,.08);
  display: flex;
  flex-direction: column;
  transition: transform .25s ease, box-shadow .25s ease;
}

.product-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 18px 40px rgba(0,0,0,.12);
}

.product-card.featured {
  grid-column: span 2;
}

.product-card img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 1em;
}

.product-card h3 {
  font-size: 1.05em;
  min-height: 2.6em;
}

.product-card .tag {
  color: #888;
  font-size: 0.9em;
}

.product-card ul {
  font-size: 0.9em;
  padding-left: 1.1em;
}

.product-card .price {
  color: #666;
  font-size: 0.9em;
}

.product-card .spacer {
  flex: 1;
}
</style>

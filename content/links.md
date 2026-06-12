---
title: "Links"
use_button_links: true
---

<style>
.links-page {
  width: min(920px, 100%);
  margin: 0 auto;
}

.links-lead {
  margin: 0 auto 1.5rem;
  max-width: 38rem;
  color: var(--md-sys-color-on-surface, rgb(25 28 24));
  line-height: 1.8;
}

.links-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

.link-card {
  display: flex;
  flex-direction: column;
  min-height: 100%;
  overflow: hidden;
  border: 1px solid color-mix(in srgb, var(--md-sys-color-outline-variant, rgb(193 201 187)) 72%, transparent);
  border-radius: 20px;
  background: color-mix(in srgb, var(--md-sys-color-surface-container-high, rgb(231 233 225)) 88%, transparent);
  color: inherit;
  text-align: left;
  text-decoration: none;
  box-shadow: 0 8px 24px color-mix(in srgb, var(--md-sys-color-shadow, rgb(0 0 0)) 16%, transparent);
  transition: border-color 0.2s ease, box-shadow 0.2s ease, transform 0.2s ease;
}

.link-card:hover,
.link-card:focus-visible {
  border-color: var(--md-sys-color-primary, rgb(0 45 5));
  box-shadow: 0 12px 28px color-mix(in srgb, var(--md-sys-color-shadow, rgb(0 0 0)) 24%, transparent);
  color: inherit;
  transform: translateY(-3px);
}

.link-card:focus-visible {
  outline: 3px solid color-mix(in srgb, var(--md-sys-color-primary, rgb(0 45 5)) 45%, transparent);
  outline-offset: 3px;
}

.link-card__banner {
  display: grid;
  min-height: 96px;
  padding: 0.75rem;
  background: color-mix(in srgb, var(--md-sys-color-surface-container-highest, rgb(225 227 220)) 88%, transparent);
  place-items: center;
}

.link-card__banner img {
  display: block;
  width: min(100%, 250px);
  max-height: 90px;
  object-fit: contain;
  border-radius: 12px;
}

.link-card__banner--icon img {
  width: 64px;
  height: 64px;
  max-height: none;
  padding: 0.65rem;
  border-radius: 18px;
  background: var(--md-sys-color-surface, rgb(248 250 242));
  box-shadow: inset 0 0 0 1px color-mix(in srgb, var(--md-sys-color-outline-variant, rgb(193 201 187)) 70%, transparent);
}

.link-card__body {
  display: flex;
  flex: 1;
  flex-direction: column;
  gap: 0.45rem;
  padding: 1rem;
}

.link-card__title {
  color: var(--md-sys-color-on-surface, rgb(25 28 24));
  font-size: 1.05rem;
  font-weight: 700;
  line-height: 1.4;
}

.link-card__text {
  color: var(--md-sys-color-on-surface-variant, rgb(65 73 63));
  font-size: 0.94rem;
  line-height: 1.7;
}
</style>

<div class="links-page">

ここにリンクを置いておく

## 相互リンク

<p class="links-lead">バナーの見え方をそろえ、説明文も同じcard内に整理。</p>

<div class="links-grid">
  <a class="link-card" href="https://157.f5.si/">
    <span class="link-card__banner">
      <img src="https://i.imgur.com/JEP1xa8.webp" alt="ちくにざき">
    </span>
    <span class="link-card__body">
      <span class="link-card__title">ちくにざき</span>
      <span class="link-card__text">自作のPHPエンジン作ってる凄い人</span>
    </span>
  </a>

  <a class="link-card" href="https://ta26.top/">
    <span class="link-card__banner link-card__banner--icon">
      <img src="https://www.google.com/s2/favicons?domain=ta26.top&amp;sz=128" alt="taitai2661">
    </span>
    <span class="link-card__body">
      <span class="link-card__title">taitai2661</span>
      <span class="link-card__text">最近rate制限のない超軽量AI作ったらしい</span>
    </span>
  </a>

  <a class="link-card" href="https://kzng.f5.si/">
    <span class="link-card__banner">
      <img src="https://i.imgur.com/94ifNlf.webp" alt="風止渚のホームページ">
    </span>
    <span class="link-card__body">
      <span class="link-card__title">風止渚のホームページ</span>
      <span class="link-card__text">一日にやってることが多い高専の人</span>
    </span>
  </a>

  <a class="link-card" href="https://soichi-portfolio.soichi1208.workers.dev/">
    <span class="link-card__banner">
      <img src="https://soichi-portfolio.soichi1208.workers.dev/header.svg" alt="𝓢o𝓲c𝓱i">
    </span>
    <span class="link-card__body">
      <span class="link-card__title">𝓢o𝓲c𝓱i</span>
      <span class="link-card__text">Tor鯖を運営している、天子ちゃん大好きな人</span>
    </span>
  </a>

  <a class="link-card" href="https://l-ituki8000.f5.si/">
    <span class="link-card__banner">
      <img src="https://site.l-ituki8000.workers.dev/images/slink.png" alt="一樹">
    </span>
    <span class="link-card__body">
      <span class="link-card__title">一樹</span>
      <span class="link-card__text">学タブの裏技の研究同胞</span>
    </span>
  </a>
</div>

</div>

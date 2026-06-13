---
title: "Links"
use_button_links: true
---

<style>
.links-page {
  width: min(840px, 100%);
  margin: 0 auto;
}

.links-lead {
  max-width: 42rem;
  margin: 0 auto 1.25rem;
  color: var(--md-sys-color-on-surface-variant, rgb(65 73 63));
  line-height: 1.8;
}

.links-list {
  display: block;
  width: min(760px, 100%);
  margin: 1rem auto 0;
  padding: 0.5rem;
  border: 1px solid color-mix(in srgb, var(--md-sys-color-outline-variant, rgb(193 201 187)) 72%, transparent);
  border-radius: 28px;
  background: color-mix(in srgb, var(--md-sys-color-surface-container-high, rgb(231 233 225)) 88%, transparent);
  box-shadow: 0 8px 24px color-mix(in srgb, var(--md-sys-color-shadow, rgb(0 0 0)) 16%, transparent);
  --md-list-container-color: transparent;
}

.links-list md-list-item {
  margin: 0.35rem 0;
  border-radius: 22px;
  overflow: hidden;
  --md-list-item-hover-state-layer-color: var(--md-sys-color-primary, rgb(0 45 5));
  --md-list-item-focus-state-layer-color: var(--md-sys-color-primary, rgb(0 45 5));
  --md-list-item-label-text-color: var(--md-sys-color-on-surface, rgb(25 28 24));
  --md-list-item-supporting-text-color: var(--md-sys-color-on-surface-variant, rgb(65 73 63));
  --md-list-item-label-text-weight: 700;
  --md-list-item-two-line-container-height: 124px;
  --md-list-item-leading-space: 0.75rem;
  --md-list-item-trailing-space: 0.75rem;
}

.links-list md-list-item:focus-visible {
  outline: 3px solid color-mix(in srgb, var(--md-sys-color-primary, rgb(0 45 5)) 45%, transparent);
  outline-offset: 3px;
}

.link-entry__media {
  display: grid;
  width: 250px;
  min-height: 96px;
  margin-inline-end: 1rem;
  border-radius: 18px;
  background: color-mix(in srgb, var(--md-sys-color-surface-container-highest, rgb(225 227 220)) 88%, transparent);
  place-items: center;
}

.link-entry__media img {
  display: block;
  width: min(100%, 250px);
  max-height: 90px;
  object-fit: contain;
  border-radius: 12px;
}

.link-entry__media--icon img {
  width: 64px;
  height: 64px;
  max-height: none;
  padding: 0.65rem;
  border-radius: 18px;
  background: var(--md-sys-color-surface, rgb(248 250 242));
  box-shadow: inset 0 0 0 1px color-mix(in srgb, var(--md-sys-color-outline-variant, rgb(193 201 187)) 70%, transparent);
}

@media (max-width: 640px) {
  .links-list {
    width: 100%;
    padding: 0.35rem;
  }

  .links-list md-list-item {
    --md-list-item-two-line-container-height: 148px;
  }

  .link-entry__media {
    width: 128px;
    min-height: 88px;
    margin-inline-end: 0.75rem;
  }

  .link-entry__media img {
    max-height: 80px;
  }
}
</style>

<div class="links-page">

ここにリンクを置いておく

## 相互リンク

<p class="links-lead">bannerの見え方をそろえ、説明文も同じ枠内に整理。</p>

<md-list class="links-list">
  <md-list-item type="link" href="https://157.f5.si/">
    ちくにざき
    <span slot="supporting-text">自作のPHPエンジン作ってる凄い人</span>
    <span class="link-entry__media" slot="start">
      <img src="https://i.imgur.com/JEP1xa8.webp" alt="ちくにざき">
    </span>
  </md-list-item>

  <md-divider></md-divider>

  <md-list-item type="link" href="https://ta26.top/">
    taitai2661
    <span slot="supporting-text">最近rate制限のない超軽量AI作ったらしい</span>
    <span class="link-entry__media link-entry__media--icon" slot="start">
      <img src="https://www.google.com/s2/favicons?domain=ta26.top&amp;sz=128" alt="taitai2661">
    </span>
  </md-list-item>

  <md-divider></md-divider>

  <md-list-item type="link" href="https://kzng.f5.si/">
    風止渚のホームページ
    <span slot="supporting-text">一日にやってることが多い高専の人</span>
    <span class="link-entry__media" slot="start">
      <img src="https://i.imgur.com/94ifNlf.webp" alt="風止渚のホームページ">
    </span>
  </md-list-item>

  <md-divider></md-divider>

  <md-list-item type="link" href="https://soichi-portfolio.soichi1208.workers.dev/">
    𝓢o𝓲c𝓱i
    <span slot="supporting-text">Tor鯖を運営している、天子ちゃん大好きな人</span>
    <span class="link-entry__media" slot="start">
      <img src="https://soichi-portfolio.soichi1208.workers.dev/header.svg" alt="𝓢o𝓲c𝓱i">
    </span>
  </md-list-item>

  <md-divider></md-divider>

  <md-list-item type="link" href="https://l-ituki8000.f5.si/">
    一樹
    <span slot="supporting-text">学タブの裏技の研究同胞</span>
    <span class="link-entry__media" slot="start">
      <img src="https://site.l-ituki8000.workers.dev/images/slink.png" alt="一樹">
    </span>
  </md-list-item>
</md-list>

</div>

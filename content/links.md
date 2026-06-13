---
title: "Links"
use_button_links: true
---

<style>
.links-page {
  width: min(1120px, 100%);
  margin: 0 auto;
}

.links-lead {
  max-width: 42rem;
  margin: 0 auto 1.25rem;
  color: var(--md-sys-color-on-surface-variant, rgb(65 73 63));
  line-height: 1.8;
}

.links-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1rem;
  width: min(1040px, 100%);
  margin: 1rem auto 0;
}

.links-grid md-elevated-button {
  width: 100%;
  min-width: 0;
  --md-elevated-button-container-height: auto;
  --md-elevated-button-leading-space: 0;
  --md-elevated-button-trailing-space: 0;
  --md-elevated-button-container-shape: 24px;
  --md-elevated-button-container-color: color-mix(in srgb, var(--md-sys-color-surface-container-high, rgb(231 233 225)) 90%, transparent);
  --md-elevated-button-container-elevation: 1;
  --md-elevated-button-hover-container-elevation: 2;
  --md-elevated-button-focus-container-elevation: 2;
  --md-elevated-button-pressed-container-elevation: 1;
  --md-elevated-button-label-text-color: var(--md-sys-color-on-surface, rgb(25 28 24));
  --md-elevated-button-hover-label-text-color: var(--md-sys-color-on-surface, rgb(25 28 24));
  --md-elevated-button-focus-label-text-color: var(--md-sys-color-on-surface, rgb(25 28 24));
  --md-elevated-button-pressed-label-text-color: var(--md-sys-color-on-surface, rgb(25 28 24));
  --md-elevated-button-label-text-size: 1rem;
  --md-elevated-button-label-text-line-height: 1.4;
  --md-elevated-button-label-text-weight: 700;
}

.link-entry {
  display: flex;
  width: 100%;
  min-height: 100%;
  flex-direction: column;
  overflow: hidden;
  border: 1px solid color-mix(in srgb, var(--md-sys-color-outline-variant, rgb(193 201 187)) 72%, transparent);
  border-radius: 24px;
  text-align: left;
}

.links-grid md-elevated-button:hover .link-entry,
.links-grid md-elevated-button:focus-within .link-entry {
  border-color: color-mix(in srgb, var(--md-sys-color-primary, rgb(0 45 5)) 70%, transparent);
}

.link-entry__media {
  display: grid;
  min-height: 104px;
  padding: 0.85rem;
  background:
    linear-gradient(135deg, color-mix(in srgb, var(--md-sys-color-primary-container, rgb(185 244 174)) 22%, transparent), transparent 55%),
    color-mix(in srgb, var(--md-sys-color-surface-container-highest, rgb(225 227 220)) 92%, transparent);
  place-items: center;
}

.link-entry__media img {
  display: block;
  width: min(100%, 250px);
  max-height: 92px;
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

.link-entry__body {
  display: flex;
  flex: 1;
  flex-direction: column;
  gap: 0.45rem;
  padding: 1rem;
}

.link-entry__title {
  color: var(--md-sys-color-on-surface, rgb(25 28 24));
  font-weight: 700;
}

.link-entry__text {
  color: var(--md-sys-color-on-surface-variant, rgb(65 73 63));
  font-size: 0.92rem;
  font-weight: 400;
  line-height: 1.7;
}

@media (max-width: 640px) {
  .links-grid {
    grid-template-columns: 1fr;
    gap: 0.85rem;
  }

  .link-entry__media {
    min-height: 96px;
    padding: 0.75rem;
  }
}
</style>

<div class="links-page">

ここにリンクを置いておく

## 相互リンク

<p class="links-lead">bannerが増えても見やすいよう、MWC buttonの自動gridで整理。</p>

<div class="links-grid">
  <md-elevated-button href="https://157.f5.si/">
    <span class="link-entry">
      <span class="link-entry__media">
        <img src="https://i.imgur.com/JEP1xa8.webp" alt="ちくにざき">
      </span>
      <span class="link-entry__body">
        <span class="link-entry__title">ちくにざき</span>
        <span class="link-entry__text">自作のPHPエンジン作ってる凄い人</span>
      </span>
    </span>
  </md-elevated-button>

  <md-elevated-button href="https://ta26.top/">
    <span class="link-entry">
      <span class="link-entry__media link-entry__media--icon">
        <img src="https://www.google.com/s2/favicons?domain=ta26.top&amp;sz=128" alt="taitai2661">
      </span>
      <span class="link-entry__body">
        <span class="link-entry__title">taitai2661</span>
        <span class="link-entry__text">最近rate制限のない超軽量AI作ったらしい</span>
      </span>
    </span>
  </md-elevated-button>

  <md-elevated-button href="https://kzng.f5.si/">
    <span class="link-entry">
      <span class="link-entry__media">
        <img src="https://i.imgur.com/94ifNlf.webp" alt="風止渚のホームページ">
      </span>
      <span class="link-entry__body">
        <span class="link-entry__title">風止渚のホームページ</span>
        <span class="link-entry__text">一日にやってることが多い高専の人</span>
      </span>
    </span>
  </md-elevated-button>

  <md-elevated-button href="https://soichi-portfolio.soichi1208.workers.dev/">
    <span class="link-entry">
      <span class="link-entry__media">
        <img src="https://soichi-portfolio.soichi1208.workers.dev/header.svg" alt="𝓢o𝓲c𝓱i">
      </span>
      <span class="link-entry__body">
        <span class="link-entry__title">𝓢o𝓲c𝓱i</span>
        <span class="link-entry__text">Tor鯖を運営している、天子ちゃん大好きな人</span>
      </span>
    </span>
  </md-elevated-button>

  <md-elevated-button href="https://l-ituki8000.f5.si/">
    <span class="link-entry">
      <span class="link-entry__media">
        <img src="https://site.l-ituki8000.workers.dev/images/slink.png" alt="一樹">
      </span>
      <span class="link-entry__body">
        <span class="link-entry__title">一樹</span>
        <span class="link-entry__text">学タブの裏技の研究同胞</span>
      </span>
    </span>
  </md-elevated-button>
</div>

</div>

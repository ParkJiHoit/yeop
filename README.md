<!doctype html>
<html lang="ko">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>옆커폰 창업 가이드북 | 미팅 전, 솔직하게 알려드립니다</title>
<meta name="description" content="경험 없어도 됩니다. 초기 비용 700만원~. 전국 700+ 점주가 증명한 대한민국 1등 휴대폰 프랜차이즈 옆커폰. 미팅 전 궁금한 것, 솔직하게 알려드립니다.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Gowun+Dodum&display=swap" rel="stylesheet">
<style>
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css');

:root {
  --navy:      #1A2744;
  --navy2:     #243356;
  --gold:      #F5A623;
  --gold2:     #FFC145;
  --coral:     #E8596A;
  --cream:     #FFFDF8;
  --soft:      #F2EFE8;
  --line:      #E6E0D5;
  --text:      #1A1A2E;
  --muted:     #7A7590;
  --grad-navy: linear-gradient(135deg, #1A2744 0%, #2D4070 100%);
  --grad-gold: linear-gradient(135deg, #F5A623 0%, #FFC145 100%);
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

body {
  background: #ECEAE4;
  font-family: 'Pretendard Variable', Pretendard, -apple-system, sans-serif;
  -webkit-font-smoothing: antialiased;
  letter-spacing: -0.02em;
  color: var(--text);
}

.page {
  max-width: 560px;
  margin: 0 auto;
  padding: 14px 14px 56px;
}

/* ── 공통 카드 ── */
.card {
  background: var(--cream);
  border-radius: 24px;
  overflow: hidden;
  margin-bottom: 12px;
  box-shadow: 0 4px 24px -8px rgba(26,39,68,.13);
}
.card-inner { padding: 24px 20px; }

.section-eyebrow {
  display: inline-flex; align-items: center; gap: 7px;
  font-size: 11px; font-weight: 800; letter-spacing: 0.22em;
  color: var(--gold); text-transform: uppercase; margin-bottom: 10px;
}
.section-eyebrow .dot { width: 6px; height: 6px; border-radius: 50%; background: var(--gold); }

.section-title {
  font-size: 22px; font-weight: 800; line-height: 1.3;
  letter-spacing: -0.035em; color: var(--navy); margin-bottom: 6px;
}
.section-title em { font-style: normal; color: var(--coral); }
.section-title .g  { color: var(--gold); }
.section-sub {
  font-size: 13px; color: var(--muted); font-weight: 500;
  line-height: 1.65; margin-bottom: 20px;
}

/* ════════════════════════
   인라인 로고
════════════════════════ */
.logo-mark {
  width: 30px; height: 30px; border-radius: 7px;
  background: var(--gold2);
  display: inline-flex; align-items: center; justify-content: center;
  font-size: 11px; font-weight: 900; color: var(--navy);
  flex-shrink: 0; letter-spacing: -0.03em;
}
.logo-mark-dark {
  background: rgba(255,255,255,.18);
  border: 1px solid rgba(255,255,255,.3);
  color: #fff;
}

/* ════════════════════════
   HERO
════════════════════════ */
.hero-card {
  background: var(--grad-navy);
  border-radius: 24px; overflow: hidden;
  margin-bottom: 12px; position: relative;
}
.hero-card::before {
  content: ""; position: absolute; inset: 0;
  background:
    radial-gradient(500px 300px at 100% -10%, rgba(245,166,35,.18), transparent 60%),
    radial-gradient(400px 300px at -10% 110%, rgba(232,89,106,.12), transparent 60%);
  pointer-events: none;
}

.hero-top {
  display: flex; align-items: center; justify-content: space-between;
  padding: 18px 20px 0;
}
.hero-logo { display: flex; align-items: center; gap: 8px; }
.hero-logo .wm { font-size: 13px; font-weight: 800; color: rgba(255,255,255,.75); }
.hero-tag {
  font-size: 10px; font-weight: 700; letter-spacing: 0.18em;
  color: var(--gold); display: flex; align-items: center; gap: 5px;
}
.hero-tag .dt { width: 5px; height: 5px; border-radius: 50%; background: var(--gold); }

.hero-body { padding: 22px 20px 0; }
.hero-pre {
  font-size: 12px; font-weight: 700; letter-spacing: 0.04em;
  color: rgba(255,255,255,.55); margin-bottom: 8px;
}
.hero-h1 {
  font-size: 27px; font-weight: 900; color: #fff;
  line-height: 1.2; letter-spacing: -0.04em; margin-bottom: 10px;
}
.hero-h1 .hl { color: var(--gold2); }
.hero-desc {
  font-size: 13.5px; color: rgba(255,255,255,.68);
  font-weight: 500; line-height: 1.7; margin-bottom: 22px;
}
.hero-desc strong { color: rgba(255,255,255,.92); font-weight: 700; }

.hero-badges {
  display: grid; grid-template-columns: repeat(3, 1fr);
  gap: 8px; padding: 0 20px 24px;
}
.hb {
  background: rgba(255,255,255,.09);
  border: 1px solid rgba(255,255,255,.15);
  border-radius: 14px; padding: 13px 10px;
  text-align: center; backdrop-filter: blur(6px);
}
.hb .hb-val {
  font-size: 20px; font-weight: 900; color: var(--gold2);
  line-height: 1; letter-spacing: -0.03em;
}
.hb .hb-val .u { font-size: 11px; font-weight: 700; margin-left: 2px; }
.hb .hb-lbl { font-size: 10px; font-weight: 600; color: rgba(255,255,255,.58); margin-top: 5px; line-height: 1.3; }

.hero-strip {
  background: rgba(255,255,255,.07);
  border-top: 1px solid rgba(255,255,255,.1);
  padding: 13px 20px;
  display: flex; align-items: center; gap: 10px;
}
.hero-strip .hs-icon { font-size: 20px; flex-shrink: 0; }
.hero-strip .hs-text { font-size: 12.5px; color: rgba(255,255,255,.72); font-weight: 500; line-height: 1.55; }
.hero-strip .hs-text strong { color: #fff; font-weight: 700; }

/* ════════════════════════
   FAQ
════════════════════════ */
.faq-intro {
  display: flex; align-items: center; gap: 10px;
  background: var(--soft); border-radius: 14px;
  padding: 13px 15px; margin-bottom: 16px;
  border: 1.5px solid var(--line);
}
.faq-intro .fi-icon { font-size: 22px; flex-shrink: 0; }
.faq-intro .fi-text { font-size: 12.5px; color: #4A4560; font-weight: 600; line-height: 1.55; }
.faq-intro .fi-text strong { color: var(--navy); }

.faq-list { display: flex; flex-direction: column; gap: 8px; }

.faq-item {
  border: 1.5px solid var(--line);
  border-radius: 16px; overflow: hidden; background: #fff;
  transition: border-color .22s ease, box-shadow .22s ease;
}
.faq-item.open {
  border-color: #BDB4E8;
  box-shadow: 0 6px 20px -8px rgba(26,39,68,.14);
}

.faq-q {
  display: flex; align-items: center; gap: 12px;
  padding: 15px 16px; cursor: pointer;
  -webkit-tap-highlight-color: transparent; user-select: none;
}
.faq-q .q-num {
  width: 28px; height: 28px; border-radius: 8px;
  background: var(--soft); flex-shrink: 0;
  display: flex; align-items: center; justify-content: center;
  font-size: 11px; font-weight: 900; color: var(--navy);
  transition: background .22s ease, color .22s ease;
}
.faq-item.open .faq-q .q-num { background: var(--navy); color: var(--gold2); }
.faq-q .q-text { flex: 1; font-size: 13.5px; font-weight: 700; color: var(--navy); line-height: 1.4; }
.faq-q .q-arrow {
  font-size: 16px; color: var(--muted); flex-shrink: 0;
  transition: transform .3s cubic-bezier(0.34, 1.56, 0.64, 1);
}
.faq-item.open .faq-q .q-arrow { transform: rotate(180deg); color: var(--navy); }

.faq-a { max-height: 0; overflow: hidden; transition: max-height .4s cubic-bezier(0.4, 0, 0.2, 1); }
.faq-a-inner {
  padding: 0 16px 16px 56px;
  font-size: 13px; color: #4A4560; font-weight: 500; line-height: 1.75;
}
.faq-a-inner strong { color: var(--navy); font-weight: 700; }
.faq-a-inner .highlight-box {
  background: var(--grad-navy);
  border-radius: 12px; padding: 12px 14px; margin-top: 10px;
  color: rgba(255,255,255,.8); font-size: 12px; line-height: 1.65;
}
.faq-a-inner .highlight-box strong { color: var(--gold2); }
.faq-a-inner .tag-row { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 10px; }
.faq-a-inner .tag {
  background: var(--soft); border: 1.5px solid var(--line);
  border-radius: 20px; padding: 4px 11px;
  font-size: 11.5px; font-weight: 700; color: var(--navy);
}
.faq-a-inner .tag.ok { background: #E8F5E9; border-color: #A5D6A7; color: #2E7D32; }

/* ════════════════════════
   수익 데이터
════════════════════════ */
.rev-grid {
  display: grid; grid-template-columns: 1fr 1.2fr 1fr;
  gap: 8px; margin-bottom: 16px;
}
.rev-box {
  border: 2px solid var(--line); border-radius: 14px;
  padding: 13px 10px; text-align: center; background: #fff;
}
.rev-box.center {
  background: var(--grad-navy); border-color: transparent;
  transform: translateY(-4px);
  box-shadow: 0 10px 26px -8px rgba(26,39,68,.4);
}
.rev-box .rb-lbl { font-size: 10.5px; font-weight: 700; color: var(--muted); }
.rev-box.center .rb-lbl { color: rgba(255,255,255,.6); }
.rev-box .rb-val { font-size: 21px; font-weight: 900; color: var(--navy); letter-spacing: -0.03em; line-height: 1; margin: 5px 0 3px; }
.rev-box.center .rb-val { color: var(--gold2); font-size: 26px; }
.rev-box .rb-val .u { font-size: 12px; font-weight: 700; margin-left: 1px; }
.rev-box .rb-note { font-size: 10px; color: var(--muted); }
.rev-box.center .rb-note { color: rgba(255,255,255,.5); }

.rev-note { font-size: 12px; font-weight: 700; color: var(--navy); text-align: center; margin-bottom: 14px; }
.rev-note span { color: var(--muted); font-weight: 500; }

/* ── 도넛 차트 ── */
.donut-wrap {
  display: flex; align-items: center; gap: 16px;
  background: var(--soft); border: 1.5px solid var(--line);
  border-radius: 18px; padding: 16px; margin-bottom: 14px;
}
.donut-svg-wrap { position: relative; flex-shrink: 0; }
.donut-svg-wrap svg { width: 120px; height: 120px; display: block; }
.donut-center {
  position: absolute; inset: 0;
  display: flex; flex-direction: column; align-items: center; justify-content: center;
}
.donut-center .dc-lbl { font-size: 9px; color: var(--muted); font-weight: 600; letter-spacing: 0.04em; }
.donut-center .dc-big { font-size: 16px; font-weight: 900; color: var(--navy); }

.donut-legend { flex: 1; display: flex; flex-direction: column; gap: 6px; }
.dl-row {
  display: flex; align-items: center; justify-content: space-between;
  padding: 7px 10px; background: #fff; border: 1.5px solid var(--line); border-radius: 10px;
}
.dl-left { display: flex; align-items: center; gap: 8px; }
.dl-dot { width: 10px; height: 10px; border-radius: 3px; flex-shrink: 0; }
.dl-name { font-size: 11.5px; font-weight: 700; color: var(--navy); }
.dl-sub  { font-size: 9.5px; color: var(--muted); margin-top: 1px; }
.dl-pct  { font-size: 16px; font-weight: 900; color: var(--navy); }

.daily-box {
  background: var(--grad-gold);
  border-radius: 16px; padding: 16px 18px;
  display: flex; align-items: center; gap: 14px;
  box-shadow: 0 8px 20px -8px rgba(245,166,35,.55);
}
.daily-box .db-icon { font-size: 30px; flex-shrink: 0; }
.daily-box .db-text { flex: 1; }
.daily-box .db-big { font-size: 17px; font-weight: 900; color: var(--navy); line-height: 1.25; letter-spacing: -0.03em; }
.daily-box .db-sub { font-size: 12px; font-weight: 600; color: rgba(26,39,68,.65); margin-top: 3px; }

/* ════════════════════════
   비교 테이블
════════════════════════ */
.compare-table { border-radius: 16px; overflow: hidden; margin-bottom: 14px; }

.ct-head {
  display: grid; grid-template-columns: 1.4fr 1fr 1fr 1fr;
  background: var(--navy); color: #fff;
  font-size: 11px; font-weight: 800; letter-spacing: 0.04em;
}
.ct-head > div { padding: 10px 8px; text-align: center; }
.ct-head .yeop { color: var(--gold2); }

.ct-row {
  display: grid; grid-template-columns: 1.4fr 1fr 1fr 1fr;
  background: #fff; border-bottom: 1px solid var(--line);
  opacity: 0; transform: translateX(-12px);
  transition: opacity .35s ease, transform .35s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.ct-row:last-child { border-bottom: none; }
.ct-row.row-in { opacity: 1; transform: translateX(0); }
.ct-row > div { padding: 11px 8px; text-align: center; font-size: 12px; font-weight: 600; color: #4A4560; display: flex; align-items: center; justify-content: center; }
.ct-row .ct-label { text-align: left; font-size: 12px; font-weight: 700; color: var(--navy); justify-content: flex-start; padding-left: 12px; }
.ct-row .yeop-col { color: var(--navy); font-weight: 800; }
.ct-row .neg { color: #B00020; }
.ct-row .ok  { color: #1B7A3E; }

/* ════════════════════════
   점주 인터뷰
════════════════════════ */
.store-count-bar {
  background: var(--navy); border-radius: 14px; padding: 14px 16px;
  display: flex; align-items: center; gap: 12px; margin-bottom: 16px;
}
.sc-num { font-size: 28px; font-weight: 900; color: var(--gold2); letter-spacing: -0.03em; flex-shrink: 0; }
.sc-num .u { font-size: 14px; margin-left: 2px; }
.sc-text { font-size: 12.5px; color: rgba(255,255,255,.72); font-weight: 500; line-height: 1.55; }
.sc-text strong { color: #fff; }

.yt-card {
  display: block; text-decoration: none; color: inherit;
  border: 1.5px solid var(--line); border-radius: 16px; overflow: hidden;
  background: #fff; margin-bottom: 10px;
  box-shadow: 0 4px 16px -8px rgba(26,39,68,.15);
  transition: transform .28s cubic-bezier(0.2, 0.8, 0.2, 1), box-shadow .28s ease, border-color .28s ease;
  -webkit-tap-highlight-color: transparent;
}
.yt-card:hover { transform: translateY(-5px); box-shadow: 0 16px 36px -10px rgba(26,39,68,.3); border-color: #BDB4E8; }
.yt-card:last-of-type { margin-bottom: 0; }
.yt-thumb {
  height: 165px; background: var(--grad-navy);
  background-size: cover; background-position: center;
  position: relative; display: flex; align-items: center; justify-content: center;
}
.yt-thumb::after {
  content: ""; position: absolute; inset: 0;
  background: linear-gradient(180deg, transparent 30%, rgba(0,0,0,.5) 100%);
}
.yt-play {
  position: absolute; z-index: 2;
  width: 48px; height: 48px; border-radius: 50%;
  background: rgba(255,255,255,.95);
  display: flex; align-items: center; justify-content: center;
  font-size: 17px; color: var(--navy);
  transition: transform .28s cubic-bezier(0.34, 1.56, 0.64, 1), background .22s ease, color .22s ease;
}
.yt-card:hover .yt-play { transform: scale(1.25); background: var(--gold); color: var(--navy); }
.yt-chip {
  position: absolute; bottom: 10px; left: 10px; z-index: 2;
  background: rgba(0,0,0,.55); color: #fff;
  font-size: 10px; font-weight: 600; padding: 4px 9px; border-radius: 6px;
}
.yt-body { padding: 13px 15px; }
.yt-title { font-size: 13.5px; font-weight: 800; color: var(--navy); line-height: 1.45; }

/* ════════════════════════
   미팅 안내
════════════════════════ */
.meeting-intro {
  background: var(--soft); border: 1.5px solid var(--line);
  border-radius: 14px; padding: 14px 16px; margin-bottom: 16px;
}
.meeting-intro .mi-title { font-size: 14px; font-weight: 800; color: var(--navy); margin-bottom: 4px; }
.meeting-intro .mi-sub  { font-size: 12px; color: var(--muted); font-weight: 500; line-height: 1.6; }

.meeting-steps { display: flex; flex-direction: column; gap: 0; margin-bottom: 16px; }

/* ── 미팅 스텝 순차 등장 애니메이션 ── */
.ms-item {
  display: flex; align-items: flex-start; gap: 14px;
  padding: 14px 0; border-bottom: 1px solid var(--line);
  opacity: 0; transform: translateX(-28px);
  transition: opacity .45s ease, transform .45s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.ms-item:last-child { border-bottom: none; }
.ms-item.ms-in { opacity: 1; transform: translateX(0); }

.ms-dot-col { display: flex; flex-direction: column; align-items: center; gap: 0; padding-top: 3px; }

.ms-num {
  width: 30px; height: 30px; border-radius: 50%;
  background: var(--navy); color: var(--gold2);
  display: flex; align-items: center; justify-content: center;
  font-size: 11px; font-weight: 900; flex-shrink: 0;
  transform: scale(0);
  transition: transform .5s cubic-bezier(0.34, 1.56, 0.64, 1) .08s;
}
.ms-item.ms-in .ms-num { transform: scale(1); }

.ms-line {
  width: 2px; flex: 1; min-height: 24px; background: var(--line); margin: 4px 0;
  transform: scaleY(0); transform-origin: top center;
  transition: transform .45s ease .32s;
}
.ms-item.ms-in .ms-line { transform: scaleY(1); }
.ms-item:last-child .ms-line { display: none; }

.ms-text {
  flex: 1; padding-bottom: 6px;
  opacity: 0; transform: translateX(-8px);
  transition: opacity .4s ease .15s, transform .4s ease .15s;
}
.ms-item.ms-in .ms-text { opacity: 1; transform: translateX(0); }

.ms-title { font-size: 13.5px; font-weight: 800; color: var(--navy); margin-bottom: 3px; }
.ms-desc { font-size: 12px; color: var(--muted); font-weight: 500; line-height: 1.6; }
.ms-badge {
  display: inline-block; margin-top: 5px;
  background: #E8F5E9; color: #2E7D32;
  font-size: 11px; font-weight: 700;
  padding: 3px 9px; border-radius: 20px; border: 1px solid #A5D6A7;
}
.ms-badge.warn { background: #FFF8E1; color: #F57F17; border-color: #FFD54F; }

.meeting-check { background: var(--grad-navy); border-radius: 16px; padding: 16px 18px; }
.mc-title { font-size: 13px; font-weight: 800; color: rgba(255,255,255,.7); margin-bottom: 10px; letter-spacing: 0.02em; }
.mc-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 7px; }
.mc-item {
  background: rgba(255,255,255,.09); border: 1px solid rgba(255,255,255,.14);
  border-radius: 11px; padding: 10px 12px;
  display: flex; align-items: flex-start; gap: 8px;
}
.mc-icon { font-size: 18px; flex-shrink: 0; margin-top: 1px; }
.mc-text { font-size: 12px; font-weight: 600; color: rgba(255,255,255,.82); line-height: 1.45; }

/* ════════════════════════
   혜택 & CTA
════════════════════════ */
.benefit-strip {
  background: var(--soft); border: 1.5px solid var(--line);
  border-radius: 16px; padding: 16px; margin-bottom: 14px;
}
.bs-title { font-size: 13px; font-weight: 800; color: var(--navy); margin-bottom: 10px; }
.bs-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 7px; }
.bs-item { background: #fff; border: 1.5px solid var(--line); border-radius: 12px; padding: 12px; }
.bs-item .bi-icon { font-size: 22px; margin-bottom: 5px; }
.bs-item .bi-main { font-size: 13px; font-weight: 800; color: var(--navy); line-height: 1.3; }
.bs-item .bi-sub  { font-size: 11px; color: var(--muted); margin-top: 2px; font-weight: 500; }

.urgency-box {
  background: linear-gradient(135deg, #C0392B 0%, #E8596A 100%);
  border-radius: 16px; padding: 16px 18px; margin-bottom: 14px;
  display: flex; align-items: center; gap: 14px;
  box-shadow: 0 8px 22px -8px rgba(200,40,60,.45);
}
.ub-icon { font-size: 28px; flex-shrink: 0; }
.ub-text { flex: 1; }
.ub-main { font-size: 15px; font-weight: 900; color: #fff; line-height: 1.3; letter-spacing: -0.02em; }
.ub-sub  { font-size: 12px; color: rgba(255,255,255,.75); margin-top: 4px; font-weight: 500; }
.ub-badge {
  background: rgba(255,255,255,.22); border: 1px solid rgba(255,255,255,.4);
  border-radius: 20px; padding: 3px 10px;
  font-size: 11px; font-weight: 700; color: #fff;
  margin-top: 6px; display: inline-block;
}

.cta-section { display: flex; gap: 10px; align-items: stretch; }

.cta-phone {
  flex: 1; background: var(--grad-navy);
  border-radius: 18px; padding: 16px; min-width: 0;
}
.cta-phone .cp-icon { font-size: 26px; float: right; opacity: .8; margin-top: -4px; }
.cta-phone .cp-lbl { font-size: 11px; font-weight: 700; color: rgba(255,255,255,.55); letter-spacing: 0.04em; margin-bottom: 4px; }
.cta-phone .cp-num { font-size: 22px; font-weight: 900; color: #fff; letter-spacing: -0.02em; line-height: 1.1; }
.cta-phone .cp-time { font-size: 11px; color: rgba(255,255,255,.55); margin-top: 5px; font-weight: 500; line-height: 1.5; }

.cta-site {
  flex-shrink: 0; width: 100px;
  background: var(--cream); border: 2px solid var(--navy);
  border-radius: 18px; padding: 14px 10px;
  display: flex; flex-direction: column; align-items: center; justify-content: center;
  gap: 5px; text-align: center; text-decoration: none; color: var(--navy);
  transition: background .15s ease, color .15s ease;
  box-shadow: 0 4px 14px -6px rgba(26,39,68,.25);
}
.cta-site:hover { background: var(--navy); color: #fff; }
.cta-site .cs-emoji { font-size: 34px; line-height: 1; }
.cta-site .cs-title { font-size: 11px; font-weight: 800; line-height: 1.25; }
.cta-site .cs-arrow { font-size: 14px; font-weight: 900; }

.disclaimer { font-size: 10px; color: var(--muted); line-height: 1.7; margin-top: 14px; }

/* ── 섹션 fade-up ── */
.fade-up {
  opacity: 0; transform: translateY(20px);
  transition: opacity .5s ease, transform .5s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.fade-up.fu-in { opacity: 1; transform: translateY(0); }

.app-footer { text-align: center; padding: 6px 0 4px; font-size: 11px; color: #a294bd; font-weight: 500; }
</style>
</head>
<body>
<div class="page">

  <!-- ══ HERO ══ -->
  <section class="hero-card">
    <div class="hero-top">
      <div class="hero-logo">
        <span class="logo-mark logo-mark-dark">옆</span>
        <span class="wm">옆커폰 창업 가이드북</span>
      </div>
      <div class="hero-tag"><span class="dt"></span>YOUR KIND PARTNER</div>
    </div>

    <div class="hero-body">
      <div class="hero-pre">상담 신청해 주셔서 감사합니다.</div>
      <h1 class="hero-h1">
        미팅 전,<br><span class="hl">솔직하게</span><br>알려드립니다.
      </h1>
      <p class="hero-desc">
        어떤 사업이든 <strong>믿을 수 있어야 결정</strong>할 수 있습니다.<br>
        궁금하신 것들, 숨기지 않고 먼저 꺼내 드릴게요.
      </p>
    </div>

    <div class="hero-badges">
      <div class="hb">
        <div class="hb-val"><span class="count" data-count="700">0</span><span class="u">+</span></div>
        <div class="hb-lbl">검증된<br>가맹점 수</div>
      </div>
      <div class="hb">
        <div class="hb-val"><span class="count" data-count="2800" data-format="comma">0</span><span class="u">만</span></div>
        <div class="hb-lbl">전국 월 평균<br>매출</div>
      </div>
      <div class="hb">
        <div class="hb-val"><span class="count" data-count="700">0</span><span class="u">만~</span></div>
        <div class="hb-lbl">최저<br>창업 비용</div>
      </div>
    </div>

    <div class="hero-strip">
      <div class="hs-icon">💬</div>
      <div class="hs-text">아래에서 <strong>가장 많이 묻는 질문 TOP 5</strong>에 바로 답해드립니다. 읽고 미팅을 결정하셔도 늦지 않습니다.</div>
    </div>
  </section>

  <!-- ══ FAQ ══ -->
  <section class="card fade-up">
    <div class="card-inner">
      <div class="section-eyebrow"><span class="dot"></span>FAQ</div>
      <h2 class="section-title">가장 많이 묻는<br>질문 <em>TOP 5</em></h2>

      <div class="faq-intro">
        <div class="fi-icon">🤔</div>
        <div class="fi-text">상담 신청자 분들이 <strong>미팅 전 가장 궁금해하시는 것</strong>들을 먼저 정리했습니다.</div>
      </div>

      <div class="faq-list">

        <div class="faq-item">
          <div class="faq-q">
            <div class="q-num">Q1</div>
            <div class="q-text">휴대폰 판매 경험이 없어도 할 수 있나요?</div>
            <div class="q-arrow">▾</div>
          </div>
          <div class="faq-a">
            <div class="faq-a-inner">
              <strong>네, 가능합니다.</strong> 현재 운영 중인 점주님의 약 60% 이상이 휴대폰 업계 경력이 전혀 없었습니다.<br><br>
              오픈 전 본사에서 운영 전반을 체계적으로 교육하며, 오픈 이후에도 담당 슈퍼바이저가 현장에서 함께합니다.
              <div class="highlight-box">
                <strong>교육 커리큘럼</strong> 포함 내용<br>
                · 요금제·기기 판매 프로세스 전 과정<br>
                · 고객 응대 스크립트 &amp; 협상 노하우<br>
                · 본사 전산 시스템 사용법<br>
                · 오픈 후 슈퍼바이저 현장 동행 지원
              </div>
            </div>
          </div>
        </div>

        <div class="faq-item">
          <div class="faq-q">
            <div class="q-num">Q2</div>
            <div class="q-text">초기 비용이 얼마나 필요한가요?</div>
            <div class="q-arrow">▾</div>
          </div>
          <div class="faq-a">
            <div class="faq-a-inner">
              최저 <strong>700만 원부터 시작</strong>할 수 있습니다. 현재 1,000호점 달성 전까지 가맹비·교육비 파격 할인이 적용됩니다.
              <div class="highlight-box">
                <strong>비용 구조 요약</strong><br>
                · 가맹비 + 교육비: 파격 할인 적용 중 (미팅에서 상세 안내)<br>
                · 인테리어: 규모·상권에 따라 협의<br>
                · 재고비: <strong>0원</strong> — 위탁 판매 구조<br>
                · 별도 인건비: 1인 운영 가능
              </div>
              <div class="tag-row">
                <span class="tag ok">✓ 재고 부담 없음</span>
                <span class="tag ok">✓ 1인 운영 가능</span>
                <span class="tag ok">✓ 할인 혜택 진행 중</span>
              </div>
            </div>
          </div>
        </div>

        <div class="faq-item">
          <div class="faq-q">
            <div class="q-num">Q3</div>
            <div class="q-text">정말 수익이 나오나요? 솔직히 얼마 버나요?</div>
            <div class="q-arrow">▾</div>
          </div>
          <div class="faq-a">
            <div class="faq-a-inner">
              <strong>데이터로만 말씀드립니다</strong> (2026년 4월 기준, 전국 가맹점 실적).
              <div class="highlight-box">
                · 전국 평균 월 매출: <strong>2,800만 원</strong><br>
                · 최저 (경기 C점): <strong>1,690만 원</strong><br>
                · 최고 (인천 B점): <strong>5,190만 원</strong><br>
                · 하루 상담 2~3건으로 월 최대 5,000만 원 매출 가능
              </div>
              수익 구조도 한 곳에만 의존하지 않습니다. 판매 수수료(50%) + 요금제 리베이트(30%) + 부가 수익(20%) 3-way 구조로 안정적입니다.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <div class="faq-q">
            <div class="q-num">Q4</div>
            <div class="q-text">일반 통신사 대리점·판매점과 뭐가 다른가요?</div>
            <div class="q-arrow">▾</div>
          </div>
          <div class="faq-a">
            <div class="faq-a-inner">
              일반 대리점·판매점은 <strong>단일 통신사</strong>에 묶여 있지만, 옆커폰은 <strong>SKT·KT·LGU+ 3사 모두</strong> 취급합니다. 고객에게 최적 조건을 제안할 수 있어 계약 성사율이 훨씬 높습니다.<br><br>
              또한 128만+ 커뮤니티(유튜브·네이버 카페·인스타그램)를 통해 <strong>본사가 마케팅을 대신</strong> 해줍니다. 점주님은 상담에만 집중하시면 됩니다.
              <div class="tag-row">
                <span class="tag ok">✓ 3사 전부 취급</span>
                <span class="tag ok">✓ 본사 마케팅 지원</span>
                <span class="tag ok">✓ 128만+ 잠재 고객</span>
              </div>
            </div>
          </div>
        </div>

        <div class="faq-item">
          <div class="faq-q">
            <div class="q-num">Q5</div>
            <div class="q-text">미팅은 어떻게 진행되나요? 계약 압박 있나요?</div>
            <div class="q-arrow">▾</div>
          </div>
          <div class="faq-a">
            <div class="faq-a-inner">
              <strong>약 30~40분</strong>의 정보 공유 미팅입니다. 계약을 강요하는 자리가 아닙니다.<br><br>
              미팅에서 확인하실 수 있는 것:
              <div class="highlight-box">
                · 내 지역 상권 분석 결과<br>
                · 예상 수익 시뮬레이션<br>
                · 가맹비·교육비 정확한 금액<br>
                · 궁금하신 모든 것 1:1 Q&amp;A
              </div>
              <div class="tag-row">
                <span class="tag ok">✓ 계약 압박 없음</span>
                <span class="tag ok">✓ 30~40분 소요</span>
                <span class="tag ok">✓ 무료 상담</span>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ══ 수익 데이터 ══ -->
  <section class="card fade-up">
    <div class="card-inner">
      <div class="section-eyebrow"><span class="dot"></span>REVENUE DATA</div>
      <h2 class="section-title">투명하게 공개하는<br><em>실적</em> 데이터</h2>
      <p class="section-sub">기대치가 아닙니다. 2026년 4월 기준 전국 가맹점이 실제로 달성한 수치입니다.</p>

      <div class="rev-grid">
        <div class="rev-box">
          <div class="rb-lbl">월 최저</div>
          <div class="rb-val"><span class="count" data-count="1690" data-format="comma">0</span><span class="u">만</span></div>
          <div class="rb-note">경기 C점</div>
        </div>
        <div class="rev-box center">
          <div class="rb-lbl">전국 평균</div>
          <div class="rb-val"><span class="count" data-count="2800" data-format="comma">0</span><span class="u">만</span></div>
          <div class="rb-note">전국 가맹점 기준</div>
        </div>
        <div class="rev-box">
          <div class="rb-lbl">월 최고</div>
          <div class="rb-val"><span class="count" data-count="5190" data-format="comma">0</span><span class="u">만</span></div>
          <div class="rb-note">인천 B점</div>
        </div>
      </div>

      <p class="rev-note">전국 <span class="count" data-count="2400" data-format="comma">0</span>만+ 건의 상담 데이터를 기반으로 만든 수익 구조</p>

      <div class="donut-wrap">
        <div class="donut-svg-wrap">
          <svg viewBox="0 0 200 200">
            <circle cx="100" cy="100" r="76" fill="none" stroke="#EDE8F8" stroke-width="28"/>
            <circle cx="100" cy="100" r="76" fill="none" stroke="#1A2744" stroke-width="28"
              class="donut-seg" data-dash="238.8" stroke-dasharray="0 477.5" stroke-dashoffset="0" transform="rotate(-90 100 100)"/>
            <circle cx="100" cy="100" r="76" fill="none" stroke="#F5A623" stroke-width="28"
              class="donut-seg" data-dash="143.3" stroke-dasharray="0 477.5" stroke-dashoffset="-238.8" transform="rotate(-90 100 100)"/>
            <circle cx="100" cy="100" r="76" fill="none" stroke="#E8596A" stroke-width="28"
              class="donut-seg" data-dash="95.5" stroke-dasharray="0 477.5" stroke-dashoffset="-382.1" transform="rotate(-90 100 100)"/>
          </svg>
          <div class="donut-center">
            <div class="dc-lbl">수익 구조</div>
            <div class="dc-big">3-way</div>
          </div>
        </div>
        <div class="donut-legend">
          <div class="dl-row">
            <div class="dl-left"><div class="dl-dot" style="background:#1A2744;"></div><div><div class="dl-name">판매 수수료</div><div class="dl-sub">기기 판매 수당</div></div></div>
            <div class="dl-pct">50%</div>
          </div>
          <div class="dl-row">
            <div class="dl-left"><div class="dl-dot" style="background:#F5A623;"></div><div><div class="dl-name">요금 수수료</div><div class="dl-sub">요금제 리베이트</div></div></div>
            <div class="dl-pct">30%</div>
          </div>
          <div class="dl-row">
            <div class="dl-left"><div class="dl-dot" style="background:#E8596A;"></div><div><div class="dl-name">부가 수익</div><div class="dl-sub">정수기·인터넷·렌탈</div></div></div>
            <div class="dl-pct">20%</div>
          </div>
        </div>
      </div>

      <div class="daily-box">
        <div class="db-icon">📞</div>
        <div class="db-text">
          <div class="db-big">하루 2~3건 상담으로<br>월 최대 5,000만 원</div>
          <div class="db-sub">고객이 먼저 찾아오는 구조, 이미 완성되어 있습니다.</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ══ 비교 테이블 ══ -->
  <section class="card fade-up">
    <div class="card-inner">
      <div class="section-eyebrow"><span class="dot"></span>COMPARISON</div>
      <h2 class="section-title">다른 창업과<br>비교하면 <span class="g">얼마나</span> 다를까요?</h2>
      <p class="section-sub">같은 창업이어도 구조가 다르면 결과가 완전히 달라집니다.</p>

      <div class="compare-table" id="compareTable">
        <div class="ct-head">
          <div></div>
          <div>요식업</div>
          <div>편의점</div>
          <div class="yeop">옆커폰</div>
        </div>
        <div class="ct-row">
          <div class="ct-label">초기 비용</div>
          <div class="neg">1.2억+</div>
          <div class="neg">8,000만+</div>
          <div class="yeop-col ok">700만~</div>
        </div>
        <div class="ct-row">
          <div class="ct-label">필요 인원</div>
          <div class="neg">3~5인</div>
          <div class="neg">24h 교대</div>
          <div class="yeop-col ok">1인 가능</div>
        </div>
        <div class="ct-row">
          <div class="ct-label">재고 부담</div>
          <div class="neg">식자재 필수</div>
          <div class="neg">대규모 재고</div>
          <div class="yeop-col ok">0원 (위탁)</div>
        </div>
        <div class="ct-row">
          <div class="ct-label">마케팅</div>
          <div class="neg">자체 부담</div>
          <div>일부 지원</div>
          <div class="yeop-col ok">본사 전담</div>
        </div>
        <div class="ct-row">
          <div class="ct-label">고객 유입</div>
          <div>유동 인구</div>
          <div>유동 인구</div>
          <div class="yeop-col ok">128만+ 커뮤니티</div>
        </div>
        <div class="ct-row">
          <div class="ct-label">영업 시간</div>
          <div class="neg">12h+</div>
          <div class="neg">24h</div>
          <div class="yeop-col ok">자유 조율</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ══ 점주 인터뷰 ══ -->
  <section class="card fade-up">
    <div class="card-inner">
      <div class="section-eyebrow"><span class="dot"></span>SUCCESS STORIES</div>
      <h2 class="section-title">먼저 시작한 <em>점주님</em>들이<br>직접 말씀해 주십니다.</h2>

      <div class="store-count-bar">
        <div class="sc-num"><span class="count" data-count="700">0</span><span class="u">+</span></div>
        <div class="sc-text"><strong>전국 700개 이상의 매장</strong>에서 점주님들이 일구어낸 실제 이야기입니다. 과장 없이, 본인들의 언어로 직접 전합니다.</div>
      </div>

      <a class="yt-card" href="https://www.youtube.com/watch?v=zEKyXljduE4" target="_blank" rel="noopener">
        <div class="yt-thumb" style="background-image:url('https://img.youtube.com/vi/zEKyXljduE4/hqdefault.jpg');"><div class="yt-play">▶</div><div class="yt-chip">YouTube · 점주 인터뷰</div></div>
        <div class="yt-body"><div class="yt-title">남들은 폐업할 때, 매장 4개로 늘렸습니다.</div></div>
      </a>
      <a class="yt-card" href="https://www.youtube.com/watch?v=oYW-0UT0sBE" target="_blank" rel="noopener">
        <div class="yt-thumb" style="background-image:url('https://img.youtube.com/vi/oYW-0UT0sBE/hqdefault.jpg');"><div class="yt-play">▶</div><div class="yt-chip">YouTube · 점주 인터뷰</div></div>
        <div class="yt-body"><div class="yt-title">15년차 학원 원장이었던 제가 본사 교육만으로 매장 3개를 운영합니다.</div></div>
      </a>
      <a class="yt-card" href="https://www.youtube.com/watch?v=4qXWxz9tIF4" target="_blank" rel="noopener">
        <div class="yt-thumb" style="background-image:url('https://img.youtube.com/vi/4qXWxz9tIF4/hqdefault.jpg');"><div class="yt-play">▶</div><div class="yt-chip">YouTube · 점주 인터뷰</div></div>
        <div class="yt-body"><div class="yt-title">사고로 생긴 1억 빚, 00개월 만에 다 갚았습니다.</div></div>
      </a>
    </div>
  </section>

  <!-- ══ 미팅 안내 ══ -->
  <section class="card fade-up">
    <div class="card-inner">
      <div class="section-eyebrow"><span class="dot"></span>MEETING GUIDE</div>
      <h2 class="section-title">미팅은 이렇게<br>진행됩니다.</h2>
      <p class="section-sub">처음 가시는 분들이 가장 많이 물어보시는 부분입니다. 미리 알고 가시면 훨씬 편합니다.</p>

      <div class="meeting-intro">
        <div class="mi-title">계약을 강요하지 않습니다.</div>
        <div class="mi-sub">이 미팅의 목적은 단 하나, <strong style="color:var(--navy);">정보를 투명하게 드리는 것</strong>입니다. 결정은 온전히 여러분의 몫입니다.</div>
      </div>

      <div class="meeting-steps" id="meetingSteps">
        <div class="ms-item">
          <div class="ms-dot-col"><div class="ms-num">1</div><div class="ms-line"></div></div>
          <div class="ms-text">
            <div class="ms-title">담당 지역장과 1:1 미팅 (약 30~40분)</div>
            <div class="ms-desc">강요·압박 없는 정보 공유 미팅입니다. 커피 한 잔 하며 편하게 이야기 나눕니다.</div>
            <span class="ms-badge">계약 의무 없음</span>
          </div>
        </div>
        <div class="ms-item">
          <div class="ms-dot-col"><div class="ms-num">2</div><div class="ms-line"></div></div>
          <div class="ms-text">
            <div class="ms-title">내 지역 상권 분석 공유</div>
            <div class="ms-desc">사전에 희망 지역의 상권 데이터를 분석해 드립니다. 어떤 입지가 좋은지 함께 살펴봅니다.</div>
          </div>
        </div>
        <div class="ms-item">
          <div class="ms-dot-col"><div class="ms-num">3</div><div class="ms-line"></div></div>
          <div class="ms-text">
            <div class="ms-title">수익 시뮬레이션 제시</div>
            <div class="ms-desc">내 상황에 맞는 예상 수익과 비용 구조를 구체적인 숫자로 보여드립니다.</div>
          </div>
        </div>
        <div class="ms-item">
          <div class="ms-dot-col"><div class="ms-num">4</div><div class="ms-line"></div></div>
          <div class="ms-text">
            <div class="ms-title">궁금한 것 모두 Q&amp;A</div>
            <div class="ms-desc">이 가이드북에서 해소되지 않은 질문이 있다면 무엇이든 물어보셔도 됩니다.</div>
            <span class="ms-badge warn">당일 결정 불필요</span>
          </div>
        </div>
      </div>

      <div class="meeting-check">
        <div class="mc-title">미팅 한 번으로 확인할 수 있는 것</div>
        <div class="mc-grid">
          <div class="mc-item"><div class="mc-icon">📍</div><div class="mc-text">내 지역<br>상권 분석 결과</div></div>
          <div class="mc-item"><div class="mc-icon">💰</div><div class="mc-text">나의 예상<br>수익 시뮬레이션</div></div>
          <div class="mc-item"><div class="mc-icon">🎓</div><div class="mc-text">교육 커리큘럼<br>전체 내용</div></div>
          <div class="mc-item"><div class="mc-icon">🤝</div><div class="mc-text">가맹비·교육비<br>정확한 금액</div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- ══ CTA ══ -->
  <section class="card fade-up">
    <div class="card-inner">
      <div class="section-eyebrow"><span class="dot"></span>NEXT STEP</div>
      <h2 class="section-title">지금 미팅을<br>결정해야 하는 이유</h2>

      <div class="benefit-strip">
        <div class="bs-title">미팅 확정 시 받을 수 있는 혜택</div>
        <div class="bs-grid">
          <div class="bs-item"><div class="bi-icon">💸</div><div class="bi-main">가맹비 · 교육비<br>파격 할인</div><div class="bi-sub">1,000호점 전까지 한정</div></div>
          <div class="bs-item"><div class="bi-icon">📍</div><div class="bi-main">희망 상권<br>사전 분석 제공</div><div class="bi-sub">무료 · 미팅 전 준비</div></div>
          <div class="bs-item"><div class="bi-icon">👑</div><div class="bi-main">상권 우선<br>배정 검토</div><div class="bi-sub">원하는 지역 선점 가능</div></div>
          <div class="bs-item"><div class="bi-icon">🎯</div><div class="bi-main">1:1 맞춤<br>컨설팅</div><div class="bi-sub">내 상황에 맞는 플랜</div></div>
        </div>
      </div>

      <div class="urgency-box">
        <div class="ub-icon">⚡</div>
        <div class="ub-text">
          <div class="ub-main">상권은<br>먼저 결정한 분의 것</div>
          <div class="ub-sub">옆커폰은 가맹점 보호를 위해 엄격한 상권 거리를 준수합니다. 같은 지역에 여러 분이 관심을 보이고 있습니다.</div>
          <div class="ub-badge">현재 700+ 호점 운영 중</div>
        </div>
      </div>

      <div class="cta-section">
        <div class="cta-phone">
          <div class="cp-icon">☎</div>
          <div class="cp-lbl">창업 전문 컨설턴트 직통</div>
          <div class="cp-num">000-0000-0000</div>
          <div class="cp-time">본 가이드를 수신하신 번호로 문의해 주시면,<br>최우선으로 안내를 도와드리겠습니다.</div>
        </div>
        <a class="cta-site" href="https://yeopkerphone.com/franchise/" target="_blank" rel="noopener">
          <div class="cs-emoji">📱</div>
          <div class="cs-title">홈페이지<br>바로가기</div>
          <div class="cs-arrow">→</div>
        </a>
      </div>

      <div class="disclaimer">
        ※ 본 자료의 수익·실적 수치는 2026년 4월 기준 전국 가맹점 평균 및 대표 사례이며, 개별 매장의 입지·운영·시기 여건에 따라 차이가 발생할 수 있습니다.<br>
        ※ 가맹비·교육비 할인 혜택은 1,000호점 달성 전까지 한정 지원됩니다.
      </div>
    </div>
  </section>

  <div class="app-footer">옆커폰 창업 가이드북 · 2026</div>
</div>

<script>
(function () {
  const DUR = 1600;
  function easeOut(t) { return 1 - Math.pow(1 - t, 4); }
  function fmt(v, f) {
    const r = Math.round(v);
    return f === 'comma' ? r.toLocaleString('ko-KR') : String(r);
  }

  function animCount(el) {
    if (el.dataset.animated) return;
    el.dataset.animated = '1';
    const target = parseFloat(el.dataset.count);
    const format = el.dataset.format || null;
    const s = performance.now();
    (function tick(now) {
      const p = Math.min((now - s) / DUR, 1);
      el.textContent = fmt(target * easeOut(p), format);
      if (p < 1) requestAnimationFrame(tick);
    })(s);
  }

  function animDonut(el) {
    if (el.dataset.animated) return;
    el.dataset.animated = '1';
    const dash = parseFloat(el.dataset.dash);
    const total = 477.5;
    const s = performance.now();
    (function tick(now) {
      const p = Math.min((now - s) / DUR, 1);
      el.setAttribute('stroke-dasharray', (dash * easeOut(p)) + ' ' + total);
      if (p < 1) requestAnimationFrame(tick);
    })(s);
  }

  /* ── fade-up: scroll 기반 (iOS Safari IntersectionObserver 버그 우회) ── */
  const fadeEls = Array.from(document.querySelectorAll('.fade-up'));
  function revealFadeUps() {
    const vh = window.innerHeight || document.documentElement.clientHeight;
    fadeEls.forEach(el => {
      if (el.classList.contains('fu-in')) return;
      if (el.getBoundingClientRect().top < vh + 80) el.classList.add('fu-in');
    });
  }
  window.addEventListener('scroll', revealFadeUps, { passive: true });
  window.addEventListener('resize', revealFadeUps, { passive: true });
  revealFadeUps();
  setTimeout(revealFadeUps, 300);
  setTimeout(() => fadeEls.forEach(el => el.classList.add('fu-in')), 6000);

  /* ── 카운트·도넛: IntersectionObserver 유지 ── */
  const io = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (!e.isIntersecting) return;
      const t = e.target;
      if (t.classList.contains('count'))     { animCount(t);  io.unobserve(t); }
      if (t.classList.contains('donut-seg')) { animDonut(t);  io.unobserve(t); }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.count[data-count]').forEach(el => io.observe(el));
  document.querySelectorAll('.donut-seg').forEach(el => io.observe(el));

  /* ── 비교 테이블 row stagger ── */
  const compareTable = document.getElementById('compareTable');
  if (compareTable) {
    const rows = compareTable.querySelectorAll('.ct-row');
    new IntersectionObserver(entries => {
      if (!entries[0].isIntersecting) return;
      rows.forEach((r, i) => setTimeout(() => r.classList.add('row-in'), i * 90));
    }, { threshold: 0.1 }).observe(compareTable);
  }

  /* ── 미팅 스텝 순차 등장 ── */
  const meetingSteps = document.getElementById('meetingSteps');
  if (meetingSteps) {
    const items = meetingSteps.querySelectorAll('.ms-item');
    new IntersectionObserver(entries => {
      if (!entries[0].isIntersecting) return;
      items.forEach((it, i) => setTimeout(() => it.classList.add('ms-in'), i * 380));
    }, { threshold: 0.05 }).observe(meetingSteps);
  }

  /* ── FAQ 아코디언 ── */
  document.querySelectorAll('.faq-item').forEach(item => {
    const q   = item.querySelector('.faq-q');
    const ans = item.querySelector('.faq-a');
    q.addEventListener('click', () => {
      const isOpen = item.classList.contains('open');
      document.querySelectorAll('.faq-item.open').forEach(other => {
        if (other !== item) {
          other.classList.remove('open');
          other.querySelector('.faq-a').style.maxHeight = null;
        }
      });
      if (isOpen) {
        item.classList.remove('open');
        ans.style.maxHeight = null;
      } else {
        item.classList.add('open');
        ans.style.maxHeight = ans.scrollHeight + 'px';
      }
    });
  });
})();
</script>
</body>
</html>

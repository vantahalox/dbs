<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>n/acc — Nepal Accelerates</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,900&family=IBM+Plex+Mono:wght@300;400;500&family=EB+Garamond:ital,wght@0,400;0,500;1,400&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --red: #C0392B;
  --deep-red: #8B1A10;
  --crimson: #E8402A;
  --cream: #EDE8DE;
  --dark: #060606;
  --mid: #0E0E0E;
  --surface: #111111;
  --muted: #555;
  --muted-light: #888;
  --border: rgba(255,255,255,0.06);
  --border-warm: rgba(192,57,43,0.2);
}

html { scroll-behavior: smooth; }

body {
  background: var(--dark);
  color: var(--cream);
  font-family: 'EB Garamond', Georgia, serif;
  font-size: 20px;
  line-height: 1.8;
  overflow-x: hidden;
}

body.loading { overflow: hidden; }

/* GRAIN */
body::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.035'/%3E%3C/svg%3E");
  pointer-events: none;
  z-index: 9999;
  opacity: 0.5;
}

/* ====== LOADER ====== */
#loader {
  position: fixed;
  inset: 0;
  background: #020202;
  z-index: 9000;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  overflow: hidden;
}

/* scanlines */
#loader::after {
  content: '';
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(
    0deg,
    transparent,
    transparent 2px,
    rgba(0,0,0,0.18) 2px,
    rgba(0,0,0,0.18) 4px
  );
  pointer-events: none;
  z-index: 3;
}

/* deep red radial glow */
.l-glow {
  position: absolute;
  width: 700px;
  height: 700px;
  background: radial-gradient(ellipse at center, rgba(160,30,15,0.22) 0%, transparent 70%);
  border-radius: 50%;
  animation: glowPulse 2s ease-in-out infinite;
}

@keyframes glowPulse {
  0%, 100% { transform: scale(1); opacity: 0.7; }
  50% { transform: scale(1.15); opacity: 1; }
}

/* corner marks */
.l-corner {
  position: absolute;
  width: 28px;
  height: 28px;
  opacity: 0;
  animation: cornerIn 0.4s ease forwards;
}
.l-corner::before, .l-corner::after {
  content: '';
  position: absolute;
  background: var(--red);
}
.l-corner::before { width: 1px; height: 100%; }
.l-corner::after  { height: 1px; width: 100%; }
.l-corner.tl { top: 40px; left: 40px; animation-delay: 0.5s; }
.l-corner.tr { top: 40px; right: 40px; animation-delay: 0.6s; transform: scaleX(-1); }
.l-corner.bl { bottom: 40px; left: 40px; animation-delay: 0.7s; transform: scaleY(-1); }
.l-corner.br { bottom: 40px; right: 40px; animation-delay: 0.8s; transform: scale(-1); }
@keyframes cornerIn { to { opacity: 0.5; } }

/* horizontal rule lines that slide in */
.l-rule {
  position: absolute;
  left: 0; right: 0;
  height: 1px;
  background: linear-gradient(to right, transparent, rgba(192,57,43,0.3), transparent);
  opacity: 0;
}
.l-rule.top    { top: 50%;    margin-top: -80px; animation: ruleIn 0.8s ease 0.6s forwards; }
.l-rule.bottom { top: 50%; margin-top:  80px; animation: ruleIn 0.8s ease 0.7s forwards; }
@keyframes ruleIn { to { opacity: 1; } }

/* center text block */
.l-center {
  position: relative;
  z-index: 2;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0;
}

/* the big n/acc — clips up from below */
.l-nacc-wrap {
  overflow: hidden;
  padding-bottom: 8px;
}

.l-nacc {
  font-family: 'Playfair Display', serif;
  font-weight: 900;
  font-style: italic;
  font-size: clamp(120px, 22vw, 280px);
  line-height: 0.88;
  letter-spacing: -0.04em;
  color: var(--cream);
  display: block;
  transform: translateY(110%);
  animation: slideUp 0.9s cubic-bezier(0.16, 1, 0.3, 1) 0.2s forwards;
  text-shadow: 0 0 120px rgba(192,57,43,0.35);
}

.l-nacc .s {
  color: var(--crimson);
  display: inline-block;
  animation: slashFlicker 0.08s steps(1) 1.4s 6 alternate;
}

@keyframes slideUp {
  to { transform: translateY(0); }
}

@keyframes slashFlicker {
  0%   { opacity: 1; color: var(--crimson); }
  25%  { opacity: 0; }
  50%  { opacity: 1; color: #fff; }
  75%  { opacity: 0.3; }
  100% { opacity: 1; color: var(--crimson); }
}

/* tagline fades in after */
.l-tag {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.45em;
  color: rgba(192,57,43,0.8);
  text-transform: uppercase;
  margin-top: 28px;
  opacity: 0;
  animation: tagIn 0.6s ease 1s forwards;
}

@keyframes tagIn {
  from { opacity: 0; transform: translateY(8px); letter-spacing: 0.6em; }
  to   { opacity: 1; transform: translateY(0);   letter-spacing: 0.45em; }
}

/* word cycling below */
.l-word-row {
  margin-top: 48px;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.25em;
  color: #2a2a2a;
  text-transform: uppercase;
  height: 16px;
  overflow: hidden;
  opacity: 0;
  animation: tagIn 0.4s ease 1.3s forwards;
}

.l-word {
  display: block;
  animation: wordCycle 0.4s ease forwards;
  color: #3a3a3a;
}

/* progress bar */
.l-bar-wrap {
  position: absolute;
  bottom: 44px;
  left: 50%;
  transform: translateX(-50%);
  width: 240px;
  z-index: 4;
}

.l-bar-track {
  width: 100%;
  height: 1px;
  background: #181818;
  position: relative;
  overflow: visible;
}

.l-bar-fill {
  height: 1px;
  background: linear-gradient(to right, var(--deep-red), var(--crimson));
  width: 0%;
  animation: barGo 3.2s cubic-bezier(0.4, 0, 0.2, 1) forwards;
  position: relative;
}

.l-bar-fill::after {
  content: '';
  position: absolute;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
  width: 4px;
  height: 4px;
  background: var(--crimson);
  border-radius: 50%;
  box-shadow: 0 0 8px var(--crimson), 0 0 16px rgba(232,64,42,0.5);
}

@keyframes barGo {
  0%   { width: 0%; }
  30%  { width: 38%; }
  60%  { width: 71%; }
  85%  { width: 92%; }
  100% { width: 100%; }
}

.l-pct {
  position: absolute;
  right: 0;
  bottom: 10px;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 9px;
  letter-spacing: 0.15em;
  color: #2e2e2e;
}

/* EXIT — curtain wipe upward */
#loader.exit {
  animation: curtainUp 0.8s cubic-bezier(0.7, 0, 1, 1) forwards;
}

@keyframes curtainUp {
  0%   { clip-path: inset(0 0 0 0);     opacity: 1; }
  100% { clip-path: inset(0 0 100% 0);  opacity: 1; }
}

/* ====== SCROLL LINE ====== */
.scroll-line {
  position: fixed;
  top: 0;
  left: 0;
  height: 1px;
  background: linear-gradient(to right, var(--deep-red), var(--crimson));
  z-index: 998;
  box-shadow: 0 0 6px rgba(232,64,42,0.6);
}

/* ====== NAV ====== */
nav {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 100;
  padding: 28px 44px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  opacity: 0;
  transition: opacity 0.8s ease, background 0.4s ease, padding 0.3s ease;
}

nav.show { opacity: 1; }

nav.scrolled {
  background: rgba(6,6,6,0.94);
  backdrop-filter: blur(16px);
  border-bottom: 1px solid var(--border);
  padding: 20px 44px;
}

.nav-mark {
  font-family: 'Playfair Display', serif;
  font-weight: 900;
  font-style: italic;
  font-size: 22px;
  color: var(--cream);
  letter-spacing: -0.02em;
}

.nav-mark span { color: var(--crimson); }

.nav-url {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.2em;
  color: var(--muted);
  text-transform: uppercase;
}

/* ====== HERO ====== */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 120px 24px 80px;
  position: relative;
  overflow: hidden;
}

.hero-glow {
  position: absolute;
  inset: 0;
  background: radial-gradient(ellipse 70% 55% at 50% 45%, rgba(139,26,16,0.14) 0%, transparent 70%);
  pointer-events: none;
}

.hero-grid {
  position: absolute;
  inset: 0;
  overflow: hidden;
  pointer-events: none;
}

.vline {
  position: absolute;
  top: 0;
  bottom: 0;
  width: 1px;
  background: var(--border);
  opacity: 0;
}

.vline:nth-child(1) { left: 20%; animation: vlineIn 1s ease 3.1s forwards; }
.vline:nth-child(2) { left: 40%; animation: vlineIn 1s ease 3.2s forwards; }
.vline:nth-child(3) { left: 60%; animation: vlineIn 1s ease 3.3s forwards; }
.vline:nth-child(4) { left: 80%; animation: vlineIn 1s ease 3.4s forwards; }

@keyframes vlineIn { to { opacity: 1; } }

.hero-eyebrow {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.4em;
  color: var(--red);
  text-transform: uppercase;
  margin-bottom: 56px;
  opacity: 0;
  animation: fadeUp 0.8s ease 3s forwards;
  display: flex;
  align-items: center;
  gap: 16px;
}

.hero-eyebrow::before, .hero-eyebrow::after {
  content: '';
  width: 36px;
  height: 1px;
  background: var(--deep-red);
}

.hero-title {
  font-family: 'Playfair Display', serif;
  font-size: clamp(100px, 19vw, 260px);
  font-weight: 900;
  line-height: 0.82;
  letter-spacing: -0.03em;
  color: var(--cream);
  opacity: 0;
  animation: heroIn 1s cubic-bezier(0.16, 1, 0.3, 1) 3.1s forwards;
}

.hero-title .s { color: var(--crimson); font-style: italic; }

@keyframes heroIn {
  from { opacity: 0; transform: translateY(50px) scale(0.96); filter: blur(6px); }
  to { opacity: 1; transform: translateY(0) scale(1); filter: blur(0); }
}

.hero-tag {
  font-family: 'EB Garamond', serif;
  font-size: clamp(18px, 2.5vw, 26px);
  font-style: italic;
  color: rgba(237,232,222,0.35);
  margin-top: 48px;
  opacity: 0;
  animation: fadeUp 0.8s ease 3.5s forwards;
}

.hero-scroll {
  position: absolute;
  bottom: 44px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;
  opacity: 0;
  animation: fadeUp 0.8s ease 3.9s forwards;
}

.hero-scroll span {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 9px;
  letter-spacing: 0.3em;
  color: var(--muted);
  text-transform: uppercase;
}

.hero-scroll-line {
  width: 1px;
  height: 52px;
  background: linear-gradient(to bottom, var(--red), transparent);
  animation: scrollPulse 2.4s ease-in-out infinite;
}

@keyframes scrollPulse {
  0%, 100% { transform: scaleY(1); opacity: 1; }
  50% { transform: scaleY(0.5); opacity: 0.3; }
}

/* ====== MANIFESTO ====== */
.manifesto {
  max-width: 780px;
  margin: 0 auto;
  padding: 140px 36px;
}

.manifesto-section {
  margin-bottom: 100px;
  opacity: 0;
  transform: translateY(44px);
  transition: opacity 0.9s cubic-bezier(0.16,1,0.3,1), transform 0.9s cubic-bezier(0.16,1,0.3,1);
}

.manifesto-section.visible {
  opacity: 1;
  transform: translateY(0);
}

.open-line {
  font-family: 'Playfair Display', serif;
  font-size: clamp(26px, 4vw, 40px);
  font-weight: 700;
  color: rgba(237,232,222,0.55);
  line-height: 1.25;
  margin-bottom: 36px;
}

.open-line .word {
  display: block;
  font-style: italic;
  font-size: clamp(72px, 14vw, 148px);
  font-weight: 900;
  color: var(--cream);
  letter-spacing: -0.03em;
  line-height: 0.88;
  margin-top: 14px;
}

p {
  color: rgba(237,232,222,0.6);
  margin-bottom: 28px;
  font-size: clamp(19px, 2.2vw, 22px);
  line-height: 1.9;
}

.heavy {
  font-family: 'Playfair Display', serif;
  font-size: clamp(22px, 3vw, 33px);
  font-weight: 700;
  color: var(--cream);
  line-height: 1.35;
}

.break-line {
  display: block;
  font-family: 'Playfair Display', serif;
  font-size: clamp(38px, 6.5vw, 70px);
  font-weight: 900;
  font-style: italic;
  color: var(--crimson);
  line-height: 1.1;
  margin: 60px 0;
}

.stacked {
  font-family: 'IBM Plex Mono', monospace;
  font-size: clamp(13px, 1.5vw, 15.5px);
  line-height: 2.5;
  color: rgba(237,232,222,0.8);
  border-left: 1px solid var(--red);
  padding: 32px 0 32px 32px;
  margin: 52px 0;
  background: linear-gradient(to right, rgba(192,57,43,0.05), transparent 80%);
}

.stacked .crossed {
  color: #303030;
  text-decoration: line-through;
  text-decoration-color: #4a1a10;
}

.stacked .after { color: rgba(237,232,222,0.85); }

em-block {
  display: block;
  font-style: italic;
  font-size: clamp(21px, 2.8vw, 28px);
  color: rgba(237,232,222,0.82);
  font-family: 'EB Garamond', serif;
  margin: 52px 0;
  line-height: 1.7;
  border-top: 1px solid var(--border);
  border-bottom: 1px solid var(--border);
  padding: 40px 0;
}

.divider {
  border: none;
  border-top: 1px solid var(--border);
  margin: 88px 0;
}

.red-divider {
  border: none;
  border-top: 1px solid var(--border-warm);
  margin: 88px 0;
  position: relative;
}

.red-divider::after {
  content: '◆';
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  background: var(--dark);
  padding: 0 20px;
  color: var(--deep-red);
  font-size: 7px;
  letter-spacing: 0;
}

/* BELIEFS */
.belief-list { list-style: none; margin: 44px 0; }

.belief-list li {
  font-size: clamp(17px, 2vw, 21px);
  color: rgba(237,232,222,0.55);
  padding: 22px 0 22px 28px;
  border-bottom: 1px solid var(--border);
  position: relative;
  line-height: 1.75;
  transition: color 0.3s ease;
}

.belief-list li::before {
  content: '—';
  color: var(--red);
  position: absolute;
  left: 0;
  opacity: 0.6;
}

.belief-list li:hover { color: var(--cream); }

/* ====== ENDING ====== */
.ending {
  text-align: center;
  padding: 100px 24px 64px;
  max-width: 800px;
  margin: 0 auto;
  border-top: 1px solid var(--border);
}

.ending-big {
  font-family: 'Playfair Display', serif;
  font-size: clamp(54px, 11vw, 130px);
  font-weight: 900;
  line-height: 0.93;
  color: var(--cream);
  margin-bottom: 24px;
  letter-spacing: -0.02em;
}

.ending-big span { color: var(--crimson); font-style: italic; }

.ending-sub {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.22em;
  color: var(--muted);
  margin-bottom: 84px;
}

/* ====== CTA ====== */
.cta-section {
  padding: 0 24px 140px;
  max-width: 1200px;
  margin: 0 auto;
}

.cta-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1px;
  background: var(--border);
  border: 1px solid var(--border);
}

.cta-card {
  background: var(--mid);
  padding: 52px 44px;
  cursor: pointer;
  transition: background 0.4s ease;
  position: relative;
  overflow: hidden;
}

.cta-card::before {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 1px;
  background: var(--red);
  transform: scaleX(0);
  transform-origin: left;
  transition: transform 0.5s cubic-bezier(0.16,1,0.3,1);
}

.cta-card:hover { background: #131313; }
.cta-card:hover::before { transform: scaleX(1); }

.cta-number {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  color: var(--red);
  letter-spacing: 0.28em;
  margin-bottom: 24px;
  opacity: 0.7;
}

.cta-title {
  font-family: 'Playfair Display', serif;
  font-size: 24px;
  font-weight: 700;
  color: var(--cream);
  margin-bottom: 16px;
  line-height: 1.3;
}

.cta-desc {
  font-size: 14px;
  color: var(--muted);
  line-height: 1.7;
  margin: 0;
  font-family: 'IBM Plex Mono', monospace;
  letter-spacing: 0.01em;
}

/* ====== CONTACT ====== */
.contact-section {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 24px 160px;
}

.contact-inner {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1px;
  background: var(--border);
  border: 1px solid var(--border);
}

.contact-left {
  background: var(--mid);
  padding: 72px 56px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  position: relative;
  overflow: hidden;
}

.contact-left::before {
  content: 'n/acc';
  position: absolute;
  bottom: -20px;
  right: -16px;
  font-family: 'Playfair Display', serif;
  font-weight: 900;
  font-style: italic;
  font-size: 180px;
  color: var(--red);
  opacity: 0.04;
  line-height: 1;
  letter-spacing: -0.03em;
  pointer-events: none;
  user-select: none;
}

.contact-left-tag {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.32em;
  color: var(--red);
  text-transform: uppercase;
  margin-bottom: 48px;
  display: flex;
  align-items: center;
  gap: 14px;
}

.contact-left-tag::before {
  content: '';
  width: 24px;
  height: 1px;
  background: var(--red);
  opacity: 0.5;
}

.contact-headline {
  font-family: 'Playfair Display', serif;
  font-size: clamp(36px, 4.5vw, 58px);
  font-weight: 900;
  line-height: 1.05;
  color: var(--cream);
  letter-spacing: -0.02em;
  margin-bottom: 36px;
}

.contact-headline span {
  color: var(--crimson);
  font-style: italic;
}

.contact-left-body {
  font-family: 'EB Garamond', serif;
  font-size: clamp(17px, 1.9vw, 20px);
  color: rgba(237,232,222,0.45);
  line-height: 1.85;
  margin-bottom: 56px;
}

.contact-stats {
  display: flex;
  flex-direction: column;
  gap: 24px;
}

.contact-stat {
  border-top: 1px solid var(--border);
  padding-top: 20px;
}

.contact-stat-num {
  font-family: 'Playfair Display', serif;
  font-size: 32px;
  font-weight: 900;
  font-style: italic;
  color: var(--crimson);
  line-height: 1;
  margin-bottom: 6px;
}

.contact-stat-label {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.18em;
  color: var(--muted);
  text-transform: uppercase;
}

.contact-right {
  background: var(--mid);
  padding: 72px 56px;
}

.contact-header {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.32em;
  color: var(--red);
  text-transform: uppercase;
  margin-bottom: 48px;
  display: flex;
  align-items: center;
  gap: 20px;
}

.contact-header::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--border);
}

@media (max-width: 900px) {
  .contact-inner { grid-template-columns: 1fr; }
  .contact-left { padding: 52px 36px; }
  .contact-right { padding: 52px 36px; }
}

.form-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
}

@media (max-width: 600px) {
  .form-row { grid-template-columns: 1fr; }
  nav { padding: 20px 20px; }
  nav.scrolled { padding: 16px 20px; }
  .manifesto { padding: 80px 20px; }
}

.field { margin-bottom: 36px; }

label {
  display: block;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  letter-spacing: 0.22em;
  color: var(--muted);
  text-transform: uppercase;
  margin-bottom: 12px;
}

input, textarea, select {
  width: 100%;
  background: transparent;
  border: none;
  border-bottom: 1px solid #1e1e1e;
  color: var(--cream);
  font-family: 'EB Garamond', serif;
  font-size: 19px;
  padding: 14px 0;
  outline: none;
  transition: border-color 0.3s ease;
  -webkit-appearance: none;
}

select { cursor: pointer; border-radius: 0; }
select option { background: #111; color: var(--cream); }
input:focus, textarea:focus, select:focus { border-bottom-color: var(--red); }
input::placeholder, textarea::placeholder { color: #252525; }
textarea { resize: none; min-height: 130px; }

.submit-btn {
  margin-top: 40px;
  background: transparent;
  border: 1px solid #333;
  color: rgba(237,232,222,0.6);
  font-family: 'IBM Plex Mono', monospace;
  font-size: 11px;
  letter-spacing: 0.32em;
  text-transform: uppercase;
  padding: 22px 60px;
  cursor: pointer;
  transition: border-color 0.4s ease, color 0.4s ease;
  display: block;
  width: 100%;
  position: relative;
  overflow: hidden;
}

.submit-btn::before {
  content: '';
  position: absolute;
  inset: 0;
  background: var(--red);
  transform: translateX(-101%);
  transition: transform 0.45s cubic-bezier(0.16,1,0.3,1);
  z-index: 0;
}

.submit-btn:hover { border-color: var(--red); color: var(--cream); }
.submit-btn:hover::before { transform: translateX(0); }
.submit-btn span { position: relative; z-index: 1; }
.submit-btn:disabled { opacity: 0.4; cursor: not-allowed; }

.form-note {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  color: #2a2a2a;
  margin-top: 24px;
  text-align: center;
  line-height: 2;
  letter-spacing: 0.06em;
}

.success-msg { display: none; text-align: center; padding: 80px 24px; }
.success-msg.show { display: block; }

.success-msg h3 {
  font-family: 'Playfair Display', serif;
  font-size: 52px;
  font-weight: 900;
  font-style: italic;
  color: var(--cream);
  margin-bottom: 20px;
}

.success-msg p {
  font-size: 14px;
  color: var(--muted);
  font-family: 'IBM Plex Mono', monospace;
  letter-spacing: 0.1em;
}

/* ====== FOOTER ====== */
footer {
  border-top: 1px solid var(--border);
  padding: 64px 24px;
  text-align: center;
}

.footer-mark {
  font-family: 'Playfair Display', serif;
  font-size: 72px;
  font-weight: 900;
  color: var(--red);
  font-style: italic;
  opacity: 0.07;
  margin-bottom: 20px;
  letter-spacing: -0.02em;
}

.footer-text {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 10px;
  color: #222;
  letter-spacing: 0.2em;
}

/* ====== UTIL ====== */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(24px); }
  to { opacity: 1; transform: translateY(0); }
}

::selection { background: var(--deep-red); color: var(--cream); }
</style>
</head>
<body class="loading">

<!-- LOADER -->
<div id="loader">
  <div class="l-glow"></div>
  <div class="l-corner tl"></div>
  <div class="l-corner tr"></div>
  <div class="l-corner bl"></div>
  <div class="l-corner br"></div>
  <div class="l-rule top"></div>
  <div class="l-rule bottom"></div>

  <div class="l-center">
    <div class="l-nacc-wrap">
      <span class="l-nacc">n<span class="s">/</span>acc</span>
    </div>
    <div class="l-tag">Nepal Accelerates</div>
    <div class="l-word-row">
      <span class="l-word" id="lWord">initializing</span>
    </div>
  </div>

  <div class="l-bar-wrap">
    <div class="l-bar-track">
      <div class="l-bar-fill" id="lBarFill"></div>
    </div>
    <div class="l-pct" id="lPct">0%</div>
  </div>
</div>

<div class="scroll-line" id="scrollLine"></div>

<!-- NAV -->
<nav id="nav">
  <div class="nav-mark">n<span>/</span>acc</div>
  <div class="nav-url">Manifesto</div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-glow"></div>
  <div class="hero-grid">
    <div class="vline"></div>
    <div class="vline"></div>
    <div class="vline"></div>
    <div class="vline"></div>
  </div>
  <div class="hero-eyebrow">🇳🇵 &nbsp; Nepal Accelerates</div>
  <h1 class="hero-title">n<span class="s">/</span>acc</h1>
  <p class="hero-tag">We were never waiting to be discovered.</p>
  <div class="hero-scroll">
    <span>scroll</span>
    <div class="hero-scroll-line"></div>
  </div>
</section>

<!-- MANIFESTO -->
<article class="manifesto">

  <div class="manifesto-section">
    <div class="open-line">
      Say it out loud.
      <span class="word">Nepal.</span>
    </div>
    <p>Say it like it costs something. Like your grandmother said it. Like your father said it on a foreign work site at 2am when nobody was listening. Like the eight hundred thousand who left last year whispered it at the border, looking back once, just once, before they crossed.</p>
    <p class="heavy">Say it like it's yours. Because it is.</p>
  </div>

  <hr class="divider">

  <div class="manifesto-section">
    <p>You were born at the roof of the world and somehow they made you feel like a basement.</p>
    <p>Think about what it takes to make a people who survived every empire, every earthquake, every betrayal — who sent their sons up the most brutal mountains on earth and watched them plant flags for other countries' glory — think about what it takes to make <em>those</em> people small.</p>
    <p>It took generations of being told the real world was somewhere else. It took watching the best leave and calling it success. It took aid that built dependency and elections that built nothing and development plans written in languages our grandmothers never spoke.</p>
    <p>It took all of that, for decades, relentlessly —</p>
    <span class="break-line">And even then,<br>they couldn't finish the job.</span>
    <p>You're still here. You're still trying. You're reading this at God-knows-what-hour because something in you refuses to go quiet.</p>
    <p class="heavy">That's not nothing. That is everything.</p>
  </div>

  <hr class="red-divider">

  <div class="manifesto-section">
    <p class="heavy" style="font-size: clamp(24px, 3.8vw, 44px); margin-bottom: 36px;">Let me tell you what I believe.</p>
    <p>I believe Nepal is not behind. Nepal is early.</p>
    <p>I believe the conditions that made us suffer — the infrastructure gaps, the institutional failures, the being-left-out of every system that was supposed to include us — I believe those conditions made us something the comfortable world has never had to become.</p>
    <div class="stacked">
      Resourceful beyond reason.<br>
      Patient beyond logic.<br>
      Creative in ways that don't have a framework yet<br>because the framework was built for people who had more.
    </div>
    <p class="heavy">We are not the third world. We are the first draft of what comes next.</p>
  </div>

  <hr class="divider">

  <div class="manifesto-section">
    <ul class="belief-list">
      <li>I believe in the woman in Butwal running a business that would have needed a bank and a building and a lawyer a generation ago.</li>
      <li>I believe in the engineer in Kathmandu solving problems at midnight that the world will discover in five years and call a breakthrough.</li>
      <li>I believe in the farmer in Mustang who knows more about his land than any outsider ever will.</li>
      <li>I believe in the student who couldn't afford the right school and taught themselves everything anyway and is quietly, furiously becoming someone nobody saw coming.</li>
      <li>I believe in every Nepali who was told this country would hold them back and decided to pull the country forward instead.</li>
    </ul>
    <em-block>I believe in you. Not the version of you that got out. Not the version waiting to get out. Not the future version. This version. Right now. Cracked and tired and still on fire.</em-block>
  </div>

  <hr class="divider">

  <div class="manifesto-section">
    <p>Here is the truth nobody says out loud in this country:</p>
    <span class="break-line">We are capable of things<br>this place has never seen.</span>
    <p>Not eventually. Not after the infrastructure improves and the politics stabilizes and the stars align into something resembling permission.</p>
    <p class="heavy">Now. With broken roads and load shedding and wifi that drops in the middle of everything important.</p>
    <p>And the reason it hasn't happened at scale is not talent. We have more talent per square kilometer than countries that are eating the world.</p>
    <p>The reason is belief. We have an ancient, deep, collective wound that says: <em>not us, not here, not yet.</em></p>
    <p class="heavy" style="color: var(--crimson);">This manifesto is a knife in that wound.</p>
  </div>

  <hr class="red-divider">

  <div class="manifesto-section">
    <p class="heavy" style="margin-bottom: 48px;">n/acc is not a brand. It is a before and after line.</p>
    <div class="stacked">
      <span class="crossed">Before: we exported our people and called it survival.</span><br>
      <span class="after">After: we build here and call it the beginning.</span><br><br>
      <span class="crossed">Before: we waited for systems never designed to include us.</span><br>
      <span class="after">After: we build systems and decide who they include.</span><br><br>
      <span class="crossed">Before: Nepal was a place people left to become something.</span><br>
      <span class="after">After: Nepal is a place people build to prove something.</span>
    </div>
  </div>

  <hr class="divider">

  <div class="manifesto-section">
    <p>We will be uncomfortable. We will fail in public. We will build companies that die and ideas that embarrass us and we will document every scar because the next person deserves a map, not a myth.</p>
    <p>We will disagree with each other. Loudly. Because that's what people who care do.</p>
    <p>We will not perform unity for foreign consumption. We will not make our struggle aesthetic for someone else's inspiration. We will not wait for validation from cities that have been validating themselves for decades while we watched.</p>
    <span class="break-line">But we will build.<br>God, we will build.</span>
    <p>We will build until the question stops being "why Nepal" and starts being "why did it take this long."</p>
    <p>We will build for every Nepali who was told to dream smaller. For every parent who worked themselves hollow so their child could have options. For every child who is right now, today, growing up in this country deciding whether they're allowed to want more.</p>
    <p class="heavy" style="font-size: clamp(28px, 5vw, 56px); text-align: center; margin: 60px 0; line-height: 1.2;">They are.<br><span style="color: var(--crimson); font-style: italic;">You are.</span></p>
  </div>

  <hr class="divider">

  <div class="manifesto-section" style="text-align: center;">
    <p style="font-family: 'Playfair Display', serif; font-size: clamp(22px, 3.5vw, 34px); font-style: italic; color: rgba(237,232,222,0.7);">The mountain was always ours.</p>
    <p style="color: var(--muted); margin-top: 12px;">We just forgot we were the ones who climbed it first.</p>
  </div>

  <hr class="red-divider">

  <div class="manifesto-section" style="text-align: center;">
    <p style="font-family: 'IBM Plex Mono', monospace; font-size: 11px; letter-spacing: 0.22em; color: var(--muted);">This is n/acc.</p>
    <p class="heavy" style="font-size: clamp(26px, 5vw, 52px); margin: 20px 0; line-height: 1.2;">This is Nepal accelerating.</p>
    <p>Not for anyone else's timeline. Not by anyone else's definition. Not toward anyone else's vision of what we should be.</p>
    <p class="heavy" style="color: var(--crimson); font-size: clamp(24px, 4.5vw, 46px); margin-top: 44px; line-height: 1.2;">Ours. Completely. Finally. Now.</p>
  </div>

  <hr class="divider">

  <div class="manifesto-section" style="text-align: center;">
    <p style="font-family: 'EB Garamond', serif; font-style: italic; font-size: clamp(19px, 2.8vw, 26px); color: rgba(237,232,222,0.35); line-height: 2.2;">
      We were never waiting to be discovered.<br>
      We were waiting for enough of us to stop waiting.<br>
      That moment is this one.
    </p>
    <span class="break-line" style="font-size: clamp(80px, 20vw, 180px); margin-top: 52px; display: block; line-height: 0.9;">Get up.</span>
  </div>

</article>

<!-- ENDING -->
<section class="ending">
  <div class="ending-big">Be a part<br>of <span>us.</span></div>
  <p class="ending-sub">We are laying the groundwork. The building starts now.</p>
</section>

<div class="cta-section">
  <div class="cta-grid">
    <div class="cta-card" onclick="selectRole('founder')">
      <div class="cta-number">01 —</div>
      <div class="cta-title">You have an idea and the hunger to execute.</div>
      <p class="cta-desc">You need awareness, community, and the right room. We want to hear from you.</p>
    </div>
    <div class="cta-card" onclick="selectRole('funded')">
      <div class="cta-number">02 —</div>
      <div class="cta-title">You're building and need to be funded.</div>
      <p class="cta-desc">You have traction or a vision sharp enough to cut. Tell us what you're building.</p>
    </div>
    <div class="cta-card" onclick="selectRole('funder')">
      <div class="cta-number">03 —</div>
      <div class="cta-title">You believe in this and want to fund it.</div>
      <p class="cta-desc">You see what we see. Nepal is early. Let's talk about what that's worth.</p>
    </div>
  </div>
</div>

<!-- CONTACT -->
<section class="contact-section">
  <div class="contact-inner">
    <div class="contact-left">
      <div>
        <div class="contact-left-tag">Write to us</div>
        <div class="contact-headline">Let's accelerate<br><span>Nepal</span><br>together.</div>
        <p class="contact-left-body">One message is all it takes. Whether you're building something, funding something, or just ready to stop watching from the side — this is where it starts.</p>
      </div>
      <div class="contact-stats" style="display:none"></div>
    </div>
    <div class="contact-right">
      <div class="contact-header">Your message</div>
      <div id="contactForm">
    <div class="form-row">
      <div class="field">
        <label>Your Name</label>
        <input type="text" id="name" placeholder="What do we call you">
      </div>
      <div class="field">
        <label>Email</label>
        <input type="email" id="email" placeholder="Where we reach you">
      </div>
    </div>
    <div class="field">
      <label>I am here because</label>
      <select id="role">
        <option value="" disabled selected>Choose your reason</option>
        <option value="idea">I have an idea and need awareness / community</option>
        <option value="funded">I'm building and need funding</option>
        <option value="funder">I want to fund n/acc or its companies</option>
        <option value="other">Something else entirely</option>
      </select>
    </div>
    <div class="field">
      <label>Tell us everything</label>
      <textarea id="message" placeholder="What are you building? What do you need? What do you believe?"></textarea>
    </div>
    <button class="submit-btn" onclick="handleSubmit()"><span>Send it —</span></button>
    <p class="form-note">
      No team, no office, no pretense.<br>
      Just conviction that this has to exist. Your message reaches the founder directly.
    </p>
  </div>

      <div class="success-msg" id="successMsg">
        <h3>We got you.</h3>
        <p>Your message reached us. We'll be in touch.<br>Keep building.</p>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="footer-mark">n/acc</div>
  <p class="footer-text">🇳🇵 &nbsp; nepalaccelerates.com &nbsp;—&nbsp; Founded in exhaustion. Built in spite of it.</p>
</footer>

<script>
// ——— LOADER ———
(function () {
  const loader = document.getElementById('loader');
  const nav    = document.getElementById('nav');
  const wordEl = document.getElementById('lWord');
  const pctEl  = document.getElementById('lPct');

  const words = ['initializing','kathmandu','accelerating','building','refusing','ascending','nepali','unstoppable','now'];
  let wi = 0;
  const wordInterval = setInterval(() => {
    wi = (wi + 1) % words.length;
    wordEl.style.opacity = '0';
    wordEl.style.transform = 'translateY(-6px)';
    setTimeout(() => {
      wordEl.textContent = words[wi];
      wordEl.style.transition = 'opacity 0.25s ease, transform 0.25s ease';
      wordEl.style.opacity = '1';
      wordEl.style.transform = 'translateY(0)';
    }, 140);
  }, 360);

  // drive the % counter in sync with the CSS bar animation
  const totalMs = 3200;
  const startTs = performance.now();
  // easing curve matching barGo keyframes
  function barEase(t) {
    if (t < 0.30) return t / 0.30 * 0.38;
    if (t < 0.60) return 0.38 + (t - 0.30) / 0.30 * 0.33;
    if (t < 0.85) return 0.71 + (t - 0.60) / 0.25 * 0.21;
    return 0.92 + (t - 0.85) / 0.15 * 0.08;
  }
  function tickPct(ts) {
    const elapsed = ts - startTs;
    const t = Math.min(elapsed / totalMs, 1);
    const pct = Math.round(barEase(t) * 100);
    pctEl.textContent = pct + '%';
    if (t < 1) requestAnimationFrame(tickPct);
  }
  requestAnimationFrame(tickPct);

  setTimeout(() => {
    clearInterval(wordInterval);
    wordEl.textContent = 'ready';
    pctEl.textContent = '100%';
    setTimeout(() => {
      loader.classList.add('exit');
      document.body.classList.remove('loading');
      nav.classList.add('show');
      setTimeout(() => { loader.style.display = 'none'; }, 850);
    }, 200);
  }, totalMs);
})();

// ——— SCROLL ———
window.addEventListener('scroll', () => {
  const st = window.scrollY;
  const dh = document.documentElement.scrollHeight - window.innerHeight;
  document.getElementById('scrollLine').style.width = (st / dh * 100) + '%';
  const nav = document.getElementById('nav');
  nav.classList.toggle('scrolled', st > 60);
}, { passive: true });

// ——— OBSERVER ———
const obs = new IntersectionObserver(entries => {
  entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
}, { threshold: 0.08 });

document.querySelectorAll('.manifesto-section').forEach(s => obs.observe(s));

// ——— CTA ———
function selectRole(r) {
  const map = { founder: 'idea', funded: 'funded', funder: 'funder' };
  document.getElementById('role').value = map[r];
  document.querySelector('.contact-section').scrollIntoView({ behavior: 'smooth' });
}

// ——— FORM ———
function handleSubmit() {
  const name = document.getElementById('name').value.trim();
  const email = document.getElementById('email').value.trim();
  const role = document.getElementById('role').value;
  const msg = document.getElementById('message').value.trim();
  if (!name || !email || !role || !msg) {
    alert('Fill in every field. We want to know who you are.');
    return;
  }
  const btn = document.querySelector('.submit-btn');
  btn.disabled = true;
  btn.querySelector('span').textContent = 'Sending...';
  const sub = encodeURIComponent('n/acc — ' + role);
  const body = encodeURIComponent('Name: ' + name + '\nEmail: ' + email + '\nReason: ' + role + '\n\n' + msg);
  window.open('mailto:hello@nepalaccelerates.com?subject=' + sub + '&body=' + body);
  setTimeout(() => {
    document.getElementById('contactForm').style.display = 'none';
    document.getElementById('successMsg').classList.add('show');
  }, 900);
}
</script>
</body>
</html>

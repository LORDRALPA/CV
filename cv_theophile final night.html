<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Théophile TOKRE — Portfolio CV</title>
<link href="https://fonts.googleapis.com/css2?family=Titillium+Web:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,300;1,400&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0f;
    --surface: #111118;
    --card: #16161f;
    --border: #2a2a3a;
    --accent: #00ff87;
    --accent2: #7c3aed;
    --accent3: #f59e0b;
    --text: #e8e8f0;
    --muted: #6b6b80;
    --code: #00d4ff;
    --danger: #ff4d6d;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Titillium Web', sans-serif;
    font-size: 15px;
    line-height: 1.6;
    overflow-x: hidden;
  }

  /* NOISE TEXTURE OVERLAY */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 9999;
    opacity: 0.3;
  }

  /* SCROLLBAR */
  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--accent); border-radius: 2px; }

  /* HEADER — FULL SCREEN HERO */
  header {
    position: relative;
    min-height: 100vh;
    padding: 0 60px;
    border-bottom: 1px solid var(--border);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  /* Hero background canvas — chars hidden, revealed by mouse */
  #heroCanvas {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    pointer-events: none;
    z-index: 0;
  }

  header::after {
    content: '';
    position: absolute;
    top: -100px;
    right: -100px;
    width: 500px;
    height: 500px;
    background: radial-gradient(circle, rgba(0,255,135,0.08) 0%, transparent 70%);
    pointer-events: none;
  }

  .lang-toggle {
    position: absolute;
    top: 30px;
    right: 60px;
    display: flex;
    align-items: center;
    gap: 8px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 30px;
    padding: 6px 16px;
    cursor: pointer;
    font-family: 'Titillium Web', monospace;
    font-size: 12px;
    color: var(--muted);
    transition: all 0.3s;
    z-index: 10;
  }

  .lang-toggle:hover { border-color: var(--accent); color: var(--accent); }
  .lang-toggle .flag { font-size: 16px; }
  .lang-toggle .arrow { transition: transform 0.3s; }

  .name-block { position: relative; z-index: 1; text-align: center; }

  .eyebrow {
    font-family: 'Titillium Web', monospace;
    font-size: 11px;
    letter-spacing: 4px;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 16px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
  }

  .eyebrow::before {
    display: none;
  }

  h1 {
    font-family: 'Titillium Web', sans-serif;
    font-size: clamp(42px, 7vw, 90px);
    font-weight: 800;
    line-height: 0.95;
    letter-spacing: -2px;
    margin-bottom: 8px;
  }

  h1 span { color: var(--accent); }

  .location {
    font-family: 'Titillium Web', monospace;
    font-size: 12px;
    color: var(--muted);
    margin-top: 16px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
  }

  .location::before {
    content: '';
    display: inline-block;
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: var(--accent2);
    box-shadow: 0 0 8px var(--accent2), 0 0 16px var(--accent2);
    flex-shrink: 0;
    animation: pulse-dot 2s ease-in-out infinite;
  }

  .title-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 24px;
  }

  .badge {
    font-family: 'Titillium Web', monospace;
    font-size: 10px;
    letter-spacing: 1px;
    text-transform: uppercase;
    padding: 5px 12px;
    border-radius: 4px;
    border: 1px solid;
  }

  .badge-green { border-color: var(--accent); color: var(--accent); background: rgba(0,255,135,0.05); }
  .badge-purple { border-color: var(--accent2); color: var(--accent2); background: rgba(124,58,237,0.05); }
  .badge-amber { border-color: var(--accent3); color: var(--accent3); background: rgba(245,158,11,0.05); }

  /* NAV TABS */
  nav {
    position: sticky;
    top: 0;
    z-index: 100;
    background: rgba(10,10,15,0.95);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid var(--border);
    padding: 0 20px;
    display: flex;
    align-items: center;
    gap: 0;
  }

  nav::-webkit-scrollbar { display: none; }

  /* Arrow buttons */
  .nav-arrow {
    flex-shrink: 0;
    width: 34px;
    height: 34px;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 1px solid var(--border);
    border-radius: 8px;
    cursor: pointer;
    color: var(--muted);
    font-size: 14px;
    transition: all 0.2s;
    user-select: none;
    margin: 0 6px;
    background: transparent;
  }
  .nav-arrow:hover:not(.disabled) {
    border-color: var(--accent);
    color: var(--accent);
    box-shadow: 0 0 10px rgba(0,255,135,0.15);
  }
  .nav-arrow.disabled {
    opacity: 0.2;
    cursor: default;
  }

  /* Tab strip — scrollable, hidden scrollbar */
  .nav-tabs {
    flex: 1;
    display: flex;
    overflow-x: auto;
    scrollbar-width: none;
    gap: 0;
  }
  .nav-tabs::-webkit-scrollbar { display: none; }

  .tab {
    font-family: 'Titillium Web', sans-serif;
    font-size: 11px;
    letter-spacing: 1px;
    text-transform: uppercase;
    padding: 18px 20px;
    cursor: pointer;
    color: var(--muted);
    border-bottom: 2px solid transparent;
    transition: all 0.2s;
    white-space: nowrap;
    user-select: none;
    display: flex;
    align-items: center;
    gap: 6px;
    flex-shrink: 0;
  }
  .tab:hover { color: var(--text); }
  .tab.active { color: var(--accent); border-bottom-color: var(--accent); }

  /* Section counter */
  .nav-counter {
    flex-shrink: 0;
    font-family: 'Titillium Web', monospace;
    font-size: 10px;
    color: var(--muted);
    letter-spacing: 1px;
    padding: 0 10px;
    white-space: nowrap;
  }
  .nav-counter span { color: var(--accent); font-weight: 700; }

  /* SECTIONS */
  .section {
    display: none;
    padding: 60px;
    max-width: 1200px;
    margin: 0 auto;
    animation: fadeUp 0.4s ease;
  }

  .section.active { display: block; }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(16px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .section-title {
    font-family: 'Titillium Web', sans-serif;
    font-size: 32px;
    font-weight: 800;
    margin-bottom: 40px;
    display: flex;
    align-items: center;
    gap: 16px;
  }

  .section-title::after {
    content: '';
    flex: 1;
    height: 1px;
    background: linear-gradient(to right, var(--border), transparent);
  }

  /* TIMELINE */
  .timeline { position: relative; padding-left: 24px; }
  .timeline::before {
    content: '';
    position: absolute;
    left: 0;
    top: 8px;
    bottom: 0;
    width: 1px;
    background: linear-gradient(to bottom, var(--accent), var(--border));
  }

  .timeline-item {
    position: relative;
    margin-bottom: 40px;
    padding-left: 32px;
  }

  .timeline-item::before {
    content: '';
    position: absolute;
    left: -8px;
    top: 8px;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: var(--accent);
    box-shadow: 0 0 12px var(--accent);
  }

  .timeline-date {
    font-family: 'Titillium Web', monospace;
    font-size: 11px;
    color: var(--accent);
    letter-spacing: 2px;
    margin-bottom: 6px;
  }

  .timeline-title {
    font-family: 'Titillium Web', sans-serif;
    font-size: 18px;
    font-weight: 700;
    margin-bottom: 4px;
  }

  .timeline-sub {
    font-size: 13px;
    color: var(--muted);
    margin-bottom: 8px;
  }

  .timeline-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-top: 10px;
  }

  .tag {
    font-family: 'Titillium Web', monospace;
    font-size: 10px;
    padding: 3px 8px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 3px;
    color: var(--muted);
  }

  /* SKILLS GRID */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 20px;
  }

  .skill-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 28px;
    transition: all 0.3s;
    position: relative;
    overflow: hidden;
  }

  .skill-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 2px;
    background: var(--card-accent, var(--accent));
    opacity: 0;
    transition: opacity 0.3s;
  }

  .skill-card:hover {
    border-color: var(--card-accent, var(--accent));
    transform: translateY(-2px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.3);
  }

  .skill-card:hover::before { opacity: 1; }

  .skill-icon {
    display: block;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: var(--card-accent, var(--accent));
    box-shadow: 0 0 8px var(--card-accent, var(--accent)), 0 0 22px var(--card-accent, var(--accent));
    margin-bottom: 18px;
    animation: pulse-dot 2.4s ease-in-out infinite;
  }

  @keyframes pulse-dot {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.6; transform: scale(1.35); }
  }

  .skill-card h3 {
    font-family: 'Titillium Web', sans-serif;
    font-size: 16px;
    font-weight: 700;
    margin-bottom: 12px;
    color: var(--card-accent, var(--accent));
  }

  .skill-list {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 6px;
  }

  .skill-list li {
    font-size: 13px;
    color: var(--muted);
    display: flex;
    align-items: flex-start;
    gap: 8px;
  }

  .skill-list li::before {
    content: '';
    display: inline-block;
    width: 5px;
    height: 5px;
    border-radius: 50%;
    background: var(--card-accent, var(--accent));
    box-shadow: 0 0 6px var(--card-accent, var(--accent));
    flex-shrink: 0;
    margin-top: 6px;
    animation: pulse-dot 2s ease-in-out infinite;
  }

  /* PROGRAMMING LANGUAGES */
  .lang-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 16px;
    margin-bottom: 40px;
  }

  .lang-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 24px 20px;
    text-align: center;
    transition: all 0.3s;
    cursor: pointer;
    position: relative;
    overflow: hidden;
  }

  .lang-card:hover {
    border-color: var(--lc-color, var(--accent));
    transform: translateY(-3px);
    box-shadow: 0 0 30px rgba(0,255,135,0.1);
  }

  .lang-card .lang-emoji {
    display: block;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: var(--lc-color, var(--accent));
    box-shadow: 0 0 8px var(--lc-color, var(--accent)), 0 0 20px var(--lc-color, var(--accent));
    margin: 0 auto 14px auto;
    animation: pulse-dot 2s ease-in-out infinite;
  }

  .lang-card .lang-name {
    font-family: 'Titillium Web', monospace;
    font-size: 13px;
    font-weight: 700;
    color: var(--lc-color, var(--code));
    margin-bottom: 6px;
  }

  .lang-card .lang-desc {
    font-size: 11px;
    color: var(--muted);
  }

  .lang-bar-wrap {
    margin-top: 12px;
    background: var(--border);
    border-radius: 4px;
    height: 3px;
    overflow: hidden;
  }

  .lang-bar {
    height: 100%;
    border-radius: 4px;
    background: var(--lc-color, var(--accent));
    transition: width 1s ease;
  }

  /* TOOLS SECTION */
  .tools-category { margin-bottom: 36px; }

  .tools-category-title {
    font-family: 'Titillium Web', monospace;
    font-size: 11px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 16px;
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .tools-category-title::after {
    content: '';
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  .tools-wrap {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .tool-pill {
    font-family: 'Titillium Web', monospace;
    font-size: 11px;
    padding: 6px 14px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 20px;
    color: var(--text);
    transition: all 0.2s;
  }

  .tool-pill:hover {
    background: var(--accent);
    color: var(--bg);
    border-color: var(--accent);
    transform: scale(1.05);
  }

  /* PROJECTS */
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
    gap: 20px;
  }

  .project-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 28px;
    transition: all 0.3s;
    position: relative;
  }

  .project-card:hover {
    border-color: var(--accent3);
    transform: translateY(-2px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.4);
  }

  .project-status {
    position: absolute;
    top: 20px;
    right: 20px;
    font-family: 'Titillium Web', monospace;
    font-size: 9px;
    padding: 3px 8px;
    border-radius: 20px;
    letter-spacing: 1px;
  }

  .status-done { background: rgba(0,255,135,0.1); color: var(--accent); border: 1px solid rgba(0,255,135,0.3); }
  .status-wip { background: rgba(245,158,11,0.1); color: var(--accent3); border: 1px solid rgba(245,158,11,0.3); }
  .status-conf { background: rgba(255,77,109,0.1); color: var(--danger); border: 1px solid rgba(255,77,109,0.3); }

  .project-number {
    font-family: 'Titillium Web', monospace;
    font-size: 10px;
    color: var(--muted);
    margin-bottom: 12px;
  }

  .project-card h3 {
    font-family: 'Titillium Web', sans-serif;
    font-size: 16px;
    font-weight: 700;
    margin-bottom: 10px;
    padding-right: 60px;
  }

  .project-card p {
    font-size: 13px;
    color: var(--muted);
    line-height: 1.7;
  }

  .project-techs {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-top: 16px;
  }

  /* CERTIFS */
  .certs-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 16px;
  }

  .cert-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 20px 22px;
    display: flex;
    align-items: flex-start;
    gap: 14px;
    transition: all 0.25s;
  }

  .cert-card:hover {
    border-color: var(--accent2);
    transform: translateX(4px);
  }

  .cert-icon {
    display: block;
    flex-shrink: 0;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    margin-top: 4px;
    background: var(--accent2);
    box-shadow: 0 0 8px var(--accent2), 0 0 20px var(--accent2);
    animation: pulse-dot 2.8s ease-in-out infinite;
  }

  .cert-title {
    font-family: 'Titillium Web', sans-serif;
    font-size: 14px;
    font-weight: 700;
    margin-bottom: 4px;
  }

  .cert-org {
    font-size: 12px;
    color: var(--muted);
  }

  /* RESPONSIVE */
  @media (max-width: 768px) {
    header { padding: 0 24px; }
    nav { padding: 0 24px; }
    .section { padding: 40px 24px; }
    .lang-toggle { top: 20px; right: 24px; }
    h1 { letter-spacing: -1px; }
    .skills-grid { grid-template-columns: 1fr; }
    .lang-grid { grid-template-columns: repeat(2, 1fr); }
  }

  /* HERO CUBE */
  .hero-layout {
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    z-index: 1;
    width: 100%;
  }

  .hero-layout > div {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .cube-scene {
    width: 200px;
    height: 200px;
    perspective: 700px;
    flex-shrink: 0;
    position: relative;
    z-index: 1;
  }

  .cube {
    width: 200px;
    height: 200px;
    position: relative;
    transform-style: preserve-3d;
    animation: rotateCube 12s linear infinite;
  }

  .cube:hover { animation-play-state: paused; }

  @keyframes rotateCube {
    0%   { transform: rotateX(-15deg) rotateY(0deg); }
    100% { transform: rotateX(-15deg) rotateY(360deg); }
  }

  .cube-face {
    position: absolute;
    width: 200px;
    height: 200px;
    border: 1px solid rgba(0,255,135,0.3);
    background: rgba(5,8,5,0.88);
    backdrop-filter: blur(4px);
    overflow: hidden;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 10px;
    padding: 20px;
    text-align: center;
  }

  /* Matrix canvas fills the face behind content */
  .cube-face canvas {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    opacity: 0.55;
    pointer-events: none;
  }

  .cube-face::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse at center, rgba(0,255,135,0.06) 0%, transparent 70%);
    pointer-events: none;
    z-index: 1;
  }

  .cube-face .face-dot {
    position: relative;
    z-index: 2;
    width: 7px;
    height: 7px;
    border-radius: 50%;
    background: var(--face-color, var(--accent));
    box-shadow: 0 0 10px var(--face-color, var(--accent)), 0 0 24px var(--face-color, var(--accent));
    animation: pulse-dot 2s ease-in-out infinite;
    flex-shrink: 0;
  }

  .cube-face .face-label {
    position: relative;
    z-index: 2;
    font-family: 'Titillium Web', sans-serif;
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 0.5px;
    line-height: 1.3;
    color: var(--face-color, var(--accent));
    text-transform: uppercase;
    text-shadow: 0 0 12px var(--face-color, var(--accent));
  }

  .face-front  { transform: rotateY(0deg)   translateZ(100px); --face-color: #00ff87; }
  .face-right  { transform: rotateY(90deg)  translateZ(100px); --face-color: #7c3aed; }
  .face-back   { transform: rotateY(180deg) translateZ(100px); --face-color: #f59e0b; }
  .face-left   { transform: rotateY(-90deg) translateZ(100px); --face-color: #00d4ff; }
  .face-top    { transform: rotateX(90deg)  translateZ(100px); --face-color: #00ff87; }
  .face-bottom { transform: rotateX(-90deg) translateZ(100px); --face-color: #00ff87; }

  @media (max-width: 768px) {
    .hero-layout { flex-direction: column-reverse; gap: 40px; }
    .cube-scene { width: 160px; height: 160px; }
    .cube { width: 160px; height: 160px; }
    .cube-face { width: 160px; height: 160px; font-size: 11px; }
    .face-front  { transform: rotateY(0deg)   translateZ(80px); }
    .face-right  { transform: rotateY(90deg)  translateZ(80px); }
    .face-back   { transform: rotateY(180deg) translateZ(80px); }
    .face-left   { transform: rotateY(-90deg) translateZ(80px); }
    .face-top    { transform: rotateX(90deg)  translateZ(80px); }
    .face-bottom { transform: rotateX(-90deg) translateZ(80px); }
  }

  /* SCROLL INDICATOR */
  .scroll-indicator {
    position: absolute;
    bottom: 36px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    cursor: pointer;
    z-index: 10;
    animation: fadeInUp 1.2s ease 1s both;
  }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateX(-50%) translateY(16px); }
    to   { opacity: 1; transform: translateX(-50%) translateY(0); }
  }

  .scroll-indicator .scroll-label {
    font-family: 'Titillium Web', sans-serif;
    font-size: 9px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--muted);
    transition: color 0.3s;
  }

  .scroll-indicator:hover .scroll-label {
    color: #ffffff;
  }

  .scroll-mouse {
    width: 22px;
    height: 34px;
    border: 1px solid rgba(0,255,135,0.35);
    border-radius: 12px;
    position: relative;
    display: flex;
    justify-content: center;
    padding-top: 6px;
    transition: border-color 0.3s;
  }

  .scroll-indicator:hover .scroll-mouse {
    border-color: #ffffff;
    background: #ffffff;
  }

  .scroll-mouse::before {
    content: '';
    width: 2px;
    height: 7px;
    background: var(--accent);
    border-radius: 2px;
    box-shadow: 0 0 6px var(--accent);
    animation: scrollWheel 1.8s ease-in-out infinite;
  }

  @keyframes scrollWheel {
    0%   { opacity: 1; transform: translateY(0); }
    60%  { opacity: 0; transform: translateY(10px); }
    61%  { opacity: 0; transform: translateY(0); }
    100% { opacity: 1; transform: translateY(0); }
  }

  .scroll-chevrons {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2px;
  }

  .scroll-chevrons span {
    display: block;
    width: 10px;
    height: 10px;
    border-right: 1px solid var(--accent);
    border-bottom: 1px solid var(--accent);
    transform: rotate(45deg);
    animation: chevronFade 1.8s ease-in-out infinite;
    box-shadow: 2px 2px 4px rgba(0,255,135,0.3);
  }

  .scroll-chevrons span:nth-child(1) { animation-delay: 0s;    opacity: 0.3; }
  .scroll-chevrons span:nth-child(2) { animation-delay: 0.2s;  opacity: 0.6; }
  .scroll-chevrons span:nth-child(3) { animation-delay: 0.4s;  opacity: 1;   }

  @keyframes chevronFade {
    0%, 100% { opacity: 0.2; }
    50%       { opacity: 1; }
  }

  /* GLOW CURSOR */
  .glow {
    position: fixed;
    width: 300px;
    height: 300px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(0,255,135,0.04) 0%, transparent 70%);
    pointer-events: none;
    transform: translate(-50%, -50%);
    transition: transform 0.1s;
    z-index: 0;
  }
</style>
</head>
<body>

<div class="glow" id="glow"></div>

<header>
  <canvas id="heroCanvas"></canvas>
  <button class="lang-toggle" id="langBtn" onclick="toggleLang()">
    <span class="flag" id="flagIcon"></span>
    <span id="langLabel">English</span>
  </button>

  <div class="hero-layout">
    <div>
      <div class="name-block" style="margin-bottom: 40px;">
        <div class="eyebrow" data-fr="Développeur · Designer · Data" data-en="Developer · Designer · Data">Développeur · Designer · Data</div>
        <h1>Théophile<br><span>TOKRE</span></h1>
        <p class="location" data-fr="Paris, France" data-en="Paris, France">Paris, France</p>
      </div>
      <div class="cube-scene">
        <div class="cube" id="heroCube">
          <div class="cube-face face-front">
            <canvas class="matrix-canvas" data-color="#00ff87"></canvas>
            <span class="face-dot"></span>
            <span class="face-label" data-fr="Concepteur Intégrateur UX" data-en="UX Integration Designer">Concepteur Intégrateur UX</span>
          </div>
          <div class="cube-face face-right">
            <canvas class="matrix-canvas" data-color="#7c3aed"></canvas>
            <span class="face-dot"></span>
            <span class="face-label" data-fr="Designer Graphique" data-en="Graphic Designer">Designer Graphique</span>
          </div>
          <div class="cube-face face-back">
            <canvas class="matrix-canvas" data-color="#f59e0b"></canvas>
            <span class="face-dot"></span>
            <span class="face-label" data-fr="Analyste Data" data-en="Data Analyst">Analyste Data</span>
          </div>
          <div class="cube-face face-left">
            <canvas class="matrix-canvas" data-color="#00d4ff"></canvas>
            <span class="face-dot"></span>
            <span class="face-label" data-fr="Chef de Projet Digital" data-en="Digital Project Manager">Chef de Projet Digital</span>
          </div>
          <div class="cube-face face-top">
            <canvas class="matrix-canvas" data-color="#00ff87"></canvas>
          </div>
          <div class="cube-face face-bottom">
            <canvas class="matrix-canvas" data-color="#00ff87"></canvas>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="scroll-indicator" onclick="document.querySelector('nav').scrollIntoView({behavior:'smooth'})">
    <div class="scroll-mouse"></div>
    <div class="scroll-chevrons">
      <span></span><span></span><span></span>
    </div>
    <span class="scroll-label" data-fr="défiler" data-en="scroll">défiler</span>
  </div>

</header>

<nav id="mainNav">
  <button class="nav-arrow disabled" id="navPrev" onclick="navigateTab(-1)" title="Précédent">&#8592;</button>
  <div class="nav-tabs" id="navTabs">
    <div class="tab active" data-section="parcours"   data-fr="Parcours"      data-en="Education"    onclick="showSection('parcours',   this)">Parcours</div>
    <div class="tab"        data-section="experience" data-fr="Expérience"    data-en="Experience"   onclick="showSection('experience', this)">Expérience</div>
    <div class="tab"        data-section="code"       data-fr="&lt;/&gt; Code" data-en="&lt;/&gt; Code" onclick="showSection('code',       this)">&lt;/&gt; Code</div>
    <div class="tab"        data-section="competences" data-fr="Compétences"  data-en="Skills"       onclick="showSection('competences',this)">Compétences</div>
    <div class="tab"        data-section="outils"     data-fr="Outils"        data-en="Tools"        onclick="showSection('outils',     this)">Outils</div>
    <div class="tab"        data-section="projets"    data-fr="Projets"       data-en="Projects"     onclick="showSection('projets',    this)">Projets</div>
    <div class="tab"        data-section="certifs"    data-fr="Certifications" data-en="Certifications" onclick="showSection('certifs', this)">Certifications</div>
  </div>
  <button class="nav-arrow" id="navNext" onclick="navigateTab(1)" title="Suivant">&#8594;</button>
  <div class="nav-counter"><span id="navCurrent">1</span> / <span id="navTotal">7</span></div>
</nav>

<!-- CODE BUBBLE STYLES & OVERLAY -->
<style>
  .code-bubble-overlay {
    position: fixed; inset: 0;
    background: rgba(5,5,10,0.82);
    backdrop-filter: blur(8px);
    z-index: 500;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 24px;
  }
  .code-bubble {
    position: relative;
    background: #0d0d16;
    border: 1px solid var(--bubble-color, #00ff87);
    border-radius: 16px;
    max-width: 780px;
    width: 100%;
    max-height: 85vh;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    box-shadow:
      0 0 0 1px var(--bubble-color,#00ff87),
      0 0 50px rgba(0,255,135,0.18),
      0 0 100px rgba(0,255,135,0.08),
      inset 0 0 60px rgba(0,255,135,0.03);
    animation: bubblePop 0.32s cubic-bezier(0.34,1.56,0.64,1);
  }
  @keyframes bubblePop {
    from { opacity:0; transform:scale(0.88) translateY(20px); }
    to   { opacity:1; transform:scale(1)    translateY(0); }
  }
  .code-bubble::before {
    content:''; position:absolute; inset:-1px; border-radius:17px;
    background: linear-gradient(135deg, var(--bubble-color,#00ff87) 0%, transparent 50%, var(--bubble-color2,#00d4ff) 100%);
    opacity: 0.07; pointer-events:none;
  }
  .bubble-header {
    display:flex; align-items:center; justify-content:space-between;
    padding:16px 24px; border-bottom:1px solid rgba(255,255,255,0.06); flex-shrink:0;
  }
  .bubble-lang-name {
    font-family:'Titillium Web',sans-serif; font-size:15px; font-weight:700;
    letter-spacing:1px; color:var(--bubble-color,#00ff87);
    display:flex; align-items:center; gap:10px;
  }
  .bubble-lang-name::before {
    content:''; display:inline-block; width:7px; height:7px; border-radius:50%;
    background:var(--bubble-color,#00ff87);
    box-shadow:0 0 10px var(--bubble-color,#00ff87),0 0 22px var(--bubble-color,#00ff87);
    animation:pulse-dot 1.8s ease-in-out infinite;
  }
  .bubble-desc {
    font-family:'Titillium Web',sans-serif; font-size:11px; letter-spacing:2px;
    text-transform:uppercase; color:var(--muted);
  }
  .bubble-close {
    background:none; border:1px solid rgba(255,255,255,0.1); border-radius:6px;
    color:var(--muted); width:30px; height:30px; cursor:pointer; font-size:16px;
    display:flex; align-items:center; justify-content:center; transition:all 0.2s;
  }
  .bubble-close:hover { border-color:var(--bubble-color,#00ff87); color:var(--bubble-color,#00ff87); }
  .bubble-comment {
    padding:14px 24px 0; font-family:'Titillium Web',sans-serif; font-size:13px;
    font-style:italic; color:var(--muted); line-height:1.7; flex-shrink:0;
  }
  .bubble-code { padding:16px 24px 24px; overflow-y:auto; flex:1; }
  .bubble-code pre {
    font-family:'Titillium Web',monospace; font-size:12px; line-height:1.9;
    color:#c8d3f5; overflow-x:auto; white-space:pre; margin:0;
  }
  .kw  { color:#7c3aed; }
  .fn  { color:#00ff87; }
  .str { color:#f59e0b; }
  .cm  { color:#4a5568; font-style:italic; }
  .nb  { color:#00d4ff; }
  .cl  { color:#e8b86d; }
  .lang-card.has-code { cursor:pointer; position:relative; }
  .lang-card.has-code::after {
    content:'{ }'; position:absolute; bottom:10px; right:12px;
    font-family:'Titillium Web',monospace; font-size:9px;
    color:var(--lc-color,var(--accent)); opacity:0.4; letter-spacing:1px; transition:opacity 0.2s;
  }
  .lang-card.has-code:hover::after { opacity:1; }
</style>

<div id="codeBubbleOverlay" style="display:none;position:fixed;inset:0;background:rgba(5,5,10,0.82);backdrop-filter:blur(8px);z-index:500;align-items:center;justify-content:center;padding:24px" onclick="if(event.target===this)closeBubble()">
  <div class="code-bubble" id="codeBubble" style="--bubble-color:#00ff87;--bubble-color2:#00d4ff">
    <div class="bubble-header">
      <div style="display:flex;flex-direction:column;gap:4px">
        <div class="bubble-lang-name" id="bubbleLangName"></div>
        <div class="bubble-desc" id="bubbleDesc"></div>
      </div>
      <button class="bubble-close" onclick="closeBubble()">&#x2715;</button>
    </div>
    <div class="bubble-comment" id="bubbleComment"></div>
    <div class="bubble-code"><pre id="bubbleCode"></pre></div>
  </div>
</div>

<!-- PARCOURS -->
<section id="parcours" class="section active">
  <h2 class="section-title" data-fr="Formation" data-en="Education">Formation</h2>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-date">2024 → 2026</div>
      <div class="timeline-title" data-fr="Master Management & Marketing Digital" data-en="Master's in Digital Management & Marketing">Master Management & Marketing Digital</div>
      <div class="timeline-sub">EIMP — <span data-fr="Alternance · 2 ans" data-en="Work-study · 2 years">Alternance · 2 ans</span></div>
      <div class="timeline-tags">
        <span class="tag">Marketing Digital</span>
        <span class="tag">Management</span>
        <span class="tag">Alternance</span>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">2020 → 2023</div>
      <div class="timeline-title" data-fr="Design Graphique & Digital" data-en="Graphic & Digital Design">Design Graphique & Digital</div>
      <div class="timeline-sub">Autograf Paris — <span data-fr="Alternance · 3 ans" data-en="Work-study · 3 years">Alternance · 3 ans</span></div>
      <div class="timeline-tags">
        <span class="tag">UX/UI</span>
        <span class="tag">Graphisme</span>
        <span class="tag">Digital</span>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">2017 → 2020</div>
      <div class="timeline-title" data-fr="Double Licence Mathématiques · Informatique" data-en="Double Bachelor's Mathematics · Computer Science">Double Licence Mathématiques · Informatique</div>
      <div class="timeline-sub">Université Paris Saclay — <span data-fr="3 ans" data-en="3 years">3 ans</span></div>
      <div class="timeline-tags">
        <span class="tag">Algorithmique</span>
        <span class="tag">Mathématiques</span>
        <span class="tag">Programmation</span>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">2016 → 2017</div>
      <div class="timeline-title" data-fr="Prépa MPCT" data-en="Preparatory class MPCT">Prépa MPCT</div>
      <div class="timeline-sub">Université Félix Houphouët Boigny — <span data-fr="Mathématiques · Physique · Chimie · Technologie" data-en="Mathematics · Physics · Chemistry · Technology">Mathématiques · Physique · Chimie · Technologie</span></div>
    </div>

  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience" class="section">
  <h2 class="section-title" data-fr="Expérience" data-en="Experience">Expérience</h2>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-date">2024 → 2026</div>
      <div class="timeline-title">CARRI Systems</div>
      <div class="timeline-sub" data-fr="Alternance — Responsable Marketing & Webmaster" data-en="Work-study — Marketing Manager & Webmaster">Alternance — Responsable Marketing & Webmaster</div>
      <div class="timeline-tags">
        <span class="tag" data-fr="Webmaster" data-en="Webmaster">Webmaster</span>
        <span class="tag" data-fr="Responsable Marketing" data-en="Marketing Manager">Responsable Marketing</span>
        <span class="tag">SQL</span>
        <span class="tag">UX/UI</span>
        <span class="tag" data-fr="Montage HPC" data-en="HPC Assembly">Montage HPC</span>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">2023 → 2024</div>
      <div class="timeline-title">CARRI Systems</div>
      <div class="timeline-sub" data-fr="CDI — Webmaster · Analyste SQL · Designer Graphique" data-en="Permanent — Webmaster · SQL Analyst · Graphic Designer">CDI — Webmaster · Analyste SQL · Designer Graphique</div>
      <div class="timeline-tags">
        <span class="tag">SQL</span>
        <span class="tag" data-fr="Design Graphique" data-en="Graphic Design">Design Graphique</span>
        <span class="tag" data-fr="Serveur HPC" data-en="HPC Server">Serveur HPC</span>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">2020 → 2023</div>
      <div class="timeline-title" data-fr="Les Jardins Numériques" data-en="Les Jardins Numériques">Les Jardins Numériques</div>
      <div class="timeline-sub" data-fr="Alternance — Designer UX/UI · Enseignant Logiciels · Animateur ateliers enfants" data-en="Work-study — UX/UI Designer · Software Trainer · Kids Workshop Facilitator">Alternance — Designer UX/UI · Enseignant Logiciels · Animateur ateliers enfants</div>
      <div class="timeline-tags">
        <span class="tag">UX/UI</span>
        <span class="tag">Adobe Suite</span>
        <span class="tag">Blender</span>
        <span class="tag" data-fr="Enseignement" data-en="Teaching">Enseignement</span>
      </div>
    </div>

  </div>
</section>

<!-- CODE -->
<section id="code" class="section">
  <h2 class="section-title" data-fr="Langages de Programmation" data-en="Programming Languages">Langages de Programmation</h2>

  <div class="lang-grid">

    <div class="lang-card has-code" style="--lc-color:#f16529;" onclick="openBubble('html')">
      <span class="lang-emoji"></span>
      <div class="lang-name">HTML / CSS</div>
      <div class="lang-desc" data-fr="Structure &amp; style web" data-en="Web structure &amp; style">Structure &amp; style web</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:90%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#4f7cba;" onclick="openBubble('php')">
      <span class="lang-emoji"></span>
      <div class="lang-name">PHP</div>
      <div class="lang-desc" data-fr="Back-end · WordPress" data-en="Back-end · WordPress">Back-end · WordPress</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:70%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#f0db4f;" onclick="openBubble('js')">
      <span class="lang-emoji"></span>
      <div class="lang-name">JavaScript</div>
      <div class="lang-desc" data-fr="Web dynamique · Node.js" data-en="Dynamic web · Node.js">Web dynamique · Node.js</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:75%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#3572A5;" onclick="openBubble('python')">
      <span class="lang-emoji"></span>
      <div class="lang-name">Python</div>
      <div class="lang-desc" data-fr="Data · Automatisation · IA" data-en="Data · Automation · AI">Data · Automatisation · IA</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:70%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#b07219;" onclick="openBubble('java')">
      <span class="lang-emoji"></span>
      <div class="lang-name">Java</div>
      <div class="lang-desc" data-fr="Applications · Backend" data-en="Applications · Backend">Applications · Backend</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:60%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#aaaaaa;" onclick="openBubble('cpp')">
      <span class="lang-emoji"></span>
      <div class="lang-name">C++</div>
      <div class="lang-desc" data-fr="Performance · Systèmes" data-en="Performance · Systems">Performance · Systèmes</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:45%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#336791;" onclick="openBubble('sql')">
      <span class="lang-emoji"></span>
      <div class="lang-name">SQL</div>
      <div class="lang-desc" data-fr="Analyse · BDD · CEGID" data-en="Analytics · DB · CEGID">Analyse · BDD · CEGID</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:82%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#61dafb;" onclick="openBubble('react')">
      <span class="lang-emoji"></span>
      <div class="lang-name">React.js</div>
      <div class="lang-desc" data-fr="SPA · Interfaces modernes" data-en="SPA · Modern interfaces">SPA · Interfaces modernes</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:65%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#68a063;" onclick="openBubble('node')">
      <span class="lang-emoji"></span>
      <div class="lang-name">Node.js</div>
      <div class="lang-desc" data-fr="APIs · Automatisation" data-en="APIs · Automation">APIs · Automatisation</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:65%"></div></div>
    </div>

    <div class="lang-card has-code" style="--lc-color:#4285f4;" onclick="openBubble('gas')">
      <span class="lang-emoji"></span>
      <div class="lang-name">Google Apps Script</div>
      <div class="lang-desc" data-fr="Automatisation G Suite" data-en="G Suite Automation">Automatisation G Suite</div>
      <div class="lang-bar-wrap"><div class="lang-bar" style="width:72%"></div></div>
    </div>

  </div>


</section>

<!-- COMPÉTENCES --><section id="competences" class="section">
  <h2 class="section-title" data-fr="Compétences" data-en="Skills">Compétences</h2>
  <div class="skills-grid">
    <div class="skill-card" style="--card-accent:#00ff87;">
      <span class="skill-icon"></span>
      <h3 data-fr="Digital & Créatif" data-en="Digital & Creative">Digital & Créatif</h3>
      <ul class="skill-list">
        <li data-fr="Conception de campagnes 360°" data-en="360° campaign design">Conception de campagnes 360°</li>
        <li data-fr="3D Artist (Blender)" data-en="3D Artist (Blender)">3D Artist (Blender)</li>
        <li data-fr="Montage Audio / Vidéo" data-en="Audio / Video Editing">Montage Audio / Vidéo</li>
        <li data-fr="Design graphique print & digital" data-en="Print & digital graphic design">Design graphique print & digital</li>
      </ul>
    </div>
    <div class="skill-card" style="--card-accent:#00d4ff;">
      <span class="skill-icon"></span>
      <h3 data-fr="Web & Développement" data-en="Web & Development">Web & Développement</h3>
      <ul class="skill-list">
        <li data-fr="Applications Web" data-en="Web Applications">Applications Web</li>
        <li data-fr="SEO / GSO Optimization" data-en="SEO / GSO Optimization">SEO / GSO Optimization</li>
        <li data-fr="UX Design & Prototyping" data-en="UX Design & Prototyping">UX Design & Prototyping</li>
        <li data-fr="WordPress + extensions sur mesure" data-en="WordPress + custom plugins">WordPress + extensions sur mesure</li>
      </ul>
    </div>
    <div class="skill-card" style="--card-accent:#7c3aed;">
      <span class="skill-icon"></span>
      <h3 data-fr="Data & Analytics" data-en="Data & Analytics">Data & Analytics</h3>
      <ul class="skill-list">
        <li data-fr="Requêtes SQL avancées" data-en="Advanced SQL queries">Requêtes SQL avancées</li>
        <li data-fr="CRM CEGID 14 & 16" data-en="CRM CEGID 14 & 16">CRM CEGID 14 & 16</li>
        <li data-fr="Power BI / Power Automate" data-en="Power BI / Power Automate">Power BI / Power Automate</li>
        <li data-fr="Google Analytics & KPI" data-en="Google Analytics & KPI">Google Analytics & KPI</li>
      </ul>
    </div>
    <div class="skill-card" style="--card-accent:#f59e0b;">
      <span class="skill-icon"></span>
      <h3 data-fr="Gestion de Projet" data-en="Project Management">Gestion de Projet</h3>
      <ul class="skill-list">
        <li data-fr="Chef de projet digital" data-en="Digital project manager">Chef de projet digital</li>
        <li data-fr="Coordination équipe pluridisciplinaire" data-en="Cross-functional team coordination">Coordination équipe pluridisciplinaire</li>
        <li data-fr="Campagnes marketing 360°" data-en="360° marketing campaigns">Campagnes marketing 360°</li>
        <li data-fr="Formation & enseignement logiciels" data-en="Software training & teaching">Formation & enseignement logiciels</li>
      </ul>
    </div>
    <div class="skill-card" style="--card-accent:#ff4d6d;">
      <span class="skill-icon"></span>
      <h3 data-fr="Intégration HPC" data-en="HPC Integration">Intégration HPC</h3>
      <ul class="skill-list">
        <li data-fr="Montage stations de travail" data-en="Workstation assembly">Montage stations de travail</li>
        <li data-fr="Configuration serveurs HPC" data-en="HPC server configuration">Configuration serveurs HPC</li>
        <li data-fr="Diagnostic & maintenance hardware" data-en="Hardware diagnostic & maintenance">Diagnostic & maintenance hardware</li>
        <li data-fr="Outil de configuration sur mesure" data-en="Custom configuration tool">Outil de configuration sur mesure</li>
      </ul>
    </div>
    <div class="skill-card" style="--card-accent:#00ff87;">
      <span class="skill-icon"></span>
      <h3 data-fr="IA & Automatisation" data-en="AI & Automation">IA & Automatisation</h3>
      <ul class="skill-list">
        <li data-fr="Prompting avancé (Claude, GPT, Gemini)" data-en="Advanced prompting (Claude, GPT, Gemini)">Prompting avancé (Claude, GPT, Gemini)</li>
        <li data-fr="Automatisation de workflows" data-en="Workflow automation">Automatisation de workflows</li>
        <li data-fr="Développement avec Cursor / Copilot" data-en="Development with Cursor / Copilot">Développement avec Cursor / Copilot</li>
        <li data-fr="Intégration APIs IA" data-en="AI API integration">Intégration APIs IA</li>
      </ul>
    </div>
  </div>
</section>

<!-- OUTILS -->
<section id="outils" class="section">
  <h2 class="section-title" data-fr="Outils & Plateformes" data-en="Tools & Platforms">Outils & Plateformes</h2>
  <div class="tools-category">
    <div class="tools-category-title" data-fr="Intelligence Artificielle" data-en="Artificial Intelligence">Intelligence Artificielle</div>
    <div class="tools-wrap">
      <span class="tool-pill">Claude</span><span class="tool-pill">Cursor</span><span class="tool-pill">GitHub Copilot</span><span class="tool-pill">ChatGPT</span><span class="tool-pill">Gemini</span><span class="tool-pill">NVIDIA AI</span>
    </div>
  </div>
  <div class="tools-category">
    <div class="tools-category-title" data-fr="Dev & Code" data-en="Dev & Code">Dev & Code</div>
    <div class="tools-wrap">
      <span class="tool-pill">VS Code</span><span class="tool-pill">Docker</span><span class="tool-pill">WordPress</span><span class="tool-pill">Elementor</span><span class="tool-pill">Google Apps Script</span><span class="tool-pill">Code Snippets</span><span class="tool-pill">Node.js</span><span class="tool-pill">React.js</span>
    </div>
  </div>
  <div class="tools-category">
    <div class="tools-category-title" data-fr="Marketing & Analytics" data-en="Marketing & Analytics">Marketing & Analytics</div>
    <div class="tools-wrap">
      <span class="tool-pill">Google Analytics</span><span class="tool-pill">Google Search Console</span><span class="tool-pill">Semrush</span><span class="tool-pill">YOAST SEO</span><span class="tool-pill">AIO SEO</span><span class="tool-pill">Buffer</span><span class="tool-pill">Salesforce</span><span class="tool-pill">LinkedIn PRO</span>
    </div>
  </div>
  <div class="tools-category">
    <div class="tools-category-title" data-fr="Design & Créatif" data-en="Design & Creative">Design & Créatif</div>
    <div class="tools-wrap">
      <span class="tool-pill">Photoshop</span><span class="tool-pill">Illustrator</span><span class="tool-pill">Premiere Pro</span><span class="tool-pill">After Effects</span><span class="tool-pill">InDesign</span><span class="tool-pill">Blender</span><span class="tool-pill">DaVinci Resolve</span><span class="tool-pill">Canva PRO</span><span class="tool-pill">Cavalry</span><span class="tool-pill">Affinity Suite</span>
    </div>
  </div>
  <div class="tools-category">
    <div class="tools-category-title" data-fr="Plateformes Entreprise" data-en="Enterprise Platforms">Plateformes Entreprise</div>
    <div class="tools-wrap">
      <span class="tool-pill">Google Workspace</span><span class="tool-pill">Microsoft Entreprise</span><span class="tool-pill">Power Automate</span><span class="tool-pill">Power BI</span><span class="tool-pill">WhatsApp Pro Entreprise</span><span class="tool-pill">CEGID 14 & 16</span>
    </div>
  </div>
</section>

<!-- PROJETS -->
<section id="projets" class="section">
  <h2 class="section-title" data-fr="Projets" data-en="Projects">Projets</h2>
  <div class="projects-grid">
    <div class="project-card">
      <span class="project-status status-done" data-fr="RÉALISÉ" data-en="DONE">RÉALISÉ</span>
      <div class="project-number">PRJ_01</div>
      <h3 data-fr="Outil B2B — Suites de Fibonacci" data-en="B2B Tool — Fibonacci Sequences">Outil B2B — Suites de Fibonacci</h3>
      <p data-fr="Outil automatisé d'acquisition B2B avec visualisation basé sur les suites de Fibonacci." data-en="Automated B2B acquisition tool with visualization based on Fibonacci sequences.">Outil automatisé d'acquisition B2B avec visualisation basé sur les suites de Fibonacci.</p>
      <div class="project-techs"><span class="tag">Node.js</span><span class="tag">React.js</span><span class="tag">Java</span><span class="tag">Python</span><span class="tag">PHP</span></div>
    </div>
    <div class="project-card">
      <span class="project-status status-done" data-fr="RÉALISÉ" data-en="DONE">RÉALISÉ</span>
      <div class="project-number">PRJ_02</div>
      <h3 data-fr="Plugin FolderSize — Windows Explorer" data-en="FolderSize Plugin — Windows Explorer">Plugin FolderSize — Windows Explorer</h3>
      <p data-fr="Plugin intégré nativement à Windows Explorer pour visualiser la taille des dossiers." data-en="Plugin natively integrated into Windows Explorer to visualize folder sizes.">Plugin intégré nativement à Windows Explorer pour visualiser la taille des dossiers.</p>
      <div class="project-techs"><span class="tag">C++</span><span class="tag">Windows API</span></div>
    </div>
    <div class="project-card">
      <span class="project-status status-done" data-fr="RÉALISÉ" data-en="DONE">RÉALISÉ</span>
      <div class="project-number">PRJ_03</div>
      <h3 data-fr="Configurateur Workstation & Serveur" data-en="Workstation & Server Configurator">Configurateur Workstation & Serveur</h3>
      <p data-fr="Outil de configuration de stations de travail et serveurs sur mesure." data-en="Custom workstation and server configuration tool.">Outil de configuration de stations de travail et serveurs sur mesure.</p>
      <div class="project-techs"><span class="tag">Python</span><span class="tag">HTML/CSS</span><span class="tag">JS</span></div>
    </div>
    <div class="project-card">
      <span class="project-status status-done" data-fr="RÉALISÉ" data-en="DONE">RÉALISÉ</span>
      <div class="project-number">PRJ_04</div>
      <h3 data-fr="ChatBot IA" data-en="AI ChatBot">ChatBot IA</h3>
      <p data-fr="Développement d'un chatbot intelligent intégrable sur plateformes web." data-en="Intelligent chatbot development integrable on web platforms.">Développement d'un chatbot intelligent intégrable sur plateformes web.</p>
      <div class="project-techs"><span class="tag">Python</span><span class="tag">Node.js</span><span class="tag">API</span></div>
    </div>
    <div class="project-card">
      <span class="project-status status-wip" data-fr="EN COURS" data-en="WIP">EN COURS</span>
      <div class="project-number">PRJ_05</div>
      <h3 data-fr="Dashboard KPI Marketing" data-en="Marketing KPI Dashboard">Dashboard KPI Marketing</h3>
      <p data-fr="Outil de visualisation de KPI marketing — SEO, SMO, GIO." data-en="Marketing KPI visualization tool — SEO, SMO, GIO.">Outil de visualisation de KPI marketing — SEO, SMO, GIO.</p>
      <div class="project-techs"><span class="tag">React.js</span><span class="tag">SQL</span><span class="tag">Python</span></div>
    </div>
    <div class="project-card">
      <span class="project-status status-wip" data-fr="EN COURS" data-en="WIP">EN COURS</span>
      <div class="project-number">PRJ_06</div>
      <h3 data-fr="Liaison CEGID ↔ WordPress" data-en="CEGID ↔ WordPress Bridge">Liaison CEGID ↔ WordPress</h3>
      <p data-fr="Connecteur entre le CRM CEGID et WordPress pour synchronisation des données." data-en="Connector between CEGID CRM and WordPress for data synchronization.">Connecteur entre le CRM CEGID et WordPress pour synchronisation des données.</p>
      <div class="project-techs"><span class="tag">PHP</span><span class="tag">SQL</span><span class="tag">WordPress API</span></div>
    </div>
    <div class="project-card">
      <span class="project-status status-conf" data-fr="CONFIDENTIEL" data-en="CONFIDENTIAL">CONFIDENTIEL</span>
      <div class="project-number">PRJ_07</div>
      <h3 data-fr="SaaS Confidentiels" data-en="Confidential SaaS">SaaS Confidentiels</h3>
      <p data-fr="Développement de solutions SaaS en cours. Détails sous NDA." data-en="SaaS solutions in development. Details under NDA.">Développement de solutions SaaS en cours. Détails sous NDA.</p>
      <div class="project-techs"><span class="tag">NDA</span></div>
    </div>
  </div>
</section>

<!-- CERTIFICATIONS -->
<section id="certifs" class="section">
  <h2 class="section-title" data-fr="Certifications & Titres" data-en="Certifications & Titles">Certifications & Titres</h2>
  <div class="certs-grid">
    <div class="cert-card"><span class="cert-icon"></span><div><div class="cert-title" data-fr="Concepteur Intégrateur UX" data-en="UX Integration Designer">Concepteur Intégrateur UX</div><div class="cert-org" data-fr="Titre professionnel" data-en="Professional title">Titre professionnel</div></div></div>
    <div class="cert-card"><span class="cert-icon"></span><div><div class="cert-title" data-fr="Titre Designer Graphique" data-en="Graphic Designer Title">Titre Designer Graphique</div><div class="cert-org" data-fr="Titre professionnel" data-en="Professional title">Titre professionnel</div></div></div>
    <div class="cert-card"><span class="cert-icon"></span><div><div class="cert-title" data-fr="Analyse de Données" data-en="Data Analysis">Analyse de Données</div><div class="cert-org" data-fr="Certificat" data-en="Certificate">Certificat</div></div></div>
    <div class="cert-card"><span class="cert-icon"></span><div><div class="cert-title">NVIDIA Product IA Seller</div><div class="cert-org">NVIDIA</div></div></div>
    <div class="cert-card"><span class="cert-icon"></span><div><div class="cert-title">NVIDIA Marketing IA</div><div class="cert-org">NVIDIA</div></div></div>
    <div class="cert-card"><span class="cert-icon"></span><div><div class="cert-title" data-fr="Chef de Projet Digital" data-en="Digital Project Manager">Chef de Projet Digital</div><div class="cert-org" data-fr="En cours de consolidation" data-en="Being consolidated">En cours de consolidation</div></div></div>
  </div>
</section>

<script>
  let lang = 'fr';

  function toggleLang() {
    lang = lang === 'fr' ? 'en' : 'fr';
    document.getElementById('langLabel').textContent = lang === 'fr' ? 'Français' : 'English';
    document.getElementById('flagIcon').textContent  = lang === 'fr' ? '🇫🇷' : '🇬🇧';
    document.querySelectorAll('[data-fr]').forEach(el => {
      const val = el.getAttribute('data-' + lang);
      if (val) el.textContent = val;
    });
    document.querySelectorAll('.tab[data-fr]').forEach(tab => {
      const val = tab.getAttribute('data-' + lang);
      if (val) tab.innerHTML = val;
    });
  }

  const SECTIONS = ['parcours','experience','code','competences','outils','projets','certifs'];
  let currentIdx = 0;

  function showSection(id, tabEl) {
    currentIdx = SECTIONS.indexOf(id);
    document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
    document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
    document.getElementById(id).classList.add('active');
    if (tabEl) tabEl.classList.add('active');
    else {
      const t = document.querySelector(`.tab[data-section="${id}"]`);
      if (t) t.classList.add('active');
    }
    updateArrows();
    // Scroll active tab into view in the strip
    const activeTab = document.querySelector('.tab.active');
    if (activeTab) activeTab.scrollIntoView({ behavior: 'smooth', block: 'nearest', inline: 'center' });
  }

  function navigateTab(dir) {
    const next = currentIdx + dir;
    if (next < 0 || next >= SECTIONS.length) return;
    showSection(SECTIONS[next]);
  }

  function updateArrows() {
    const prev = document.getElementById('navPrev');
    const next = document.getElementById('navNext');
    const curr = document.getElementById('navCurrent');
    prev.classList.toggle('disabled', currentIdx === 0);
    next.classList.toggle('disabled', currentIdx === SECTIONS.length - 1);
    if (curr) curr.textContent = currentIdx + 1;
  }

  // Keyboard left/right navigation
  document.addEventListener('keydown', e => {
    if (e.key === 'ArrowLeft')  navigateTab(-1);
    if (e.key === 'ArrowRight') navigateTab(1);
  });

  updateArrows();

  document.addEventListener('mousemove', e => {
    const glow = document.getElementById('glow');
    glow.style.left = e.clientX + 'px';
    glow.style.top  = e.clientY + 'px';
  });

  window.addEventListener('load', () => {
    setTimeout(() => {
      document.querySelectorAll('.lang-bar').forEach(bar => { bar.style.width = bar.style.width; });
    }, 200);
  });

  // ── CODE BUBBLES ─────────────────────────────────────────────────────────
  const BUBBLES = {
    html: {
      name:'HTML / CSS', desc:'Structure & style web', color:'#f16529', color2:'#e44d26',
      comment:"C'est mon terrain de jeu depuis le début — je construis la structure et je peaufine le style. Le CSS, c'est là où je passe de \"ça marche\" à \"ça claque\".",
      code:`<span style="color:#4a5568;font-style:italic">/* Mon cube 3D en pur CSS — j'adore ce genre de truc */</span>
<span style="color:#00ff87">.cube</span> {
  <span style="color:#00d4ff">transform-style</span>: <span style="color:#f59e0b">preserve-3d</span>;
  <span style="color:#00d4ff">animation</span>: <span style="color:#f59e0b">rotateCube 12s linear infinite</span>;
}
<span style="color:#00ff87">.face-front</span>  { <span style="color:#00d4ff">transform</span>: <span style="color:#f59e0b">rotateY(0deg) translateZ(100px)</span>; }
<span style="color:#00ff87">.face-right</span>  { <span style="color:#00d4ff">transform</span>: <span style="color:#f59e0b">rotateY(90deg) translateZ(100px)</span>; }
<span style="color:#4a5568;font-style:italic">/* Variables CSS — j'en mets partout, bien plus propre */</span>
<span style="color:#00ff87">:root</span> {
  <span style="color:#00d4ff">--accent</span>:  <span style="color:#f59e0b">#00ff87</span>;
  <span style="color:#00d4ff">--accent2</span>: <span style="color:#f59e0b">#7c3aed</span>;
  <span style="color:#00d4ff">--card</span>:    <span style="color:#f59e0b">#16161f</span>;
  <span style="color:#00d4ff">--border</span>:  <span style="color:#f59e0b">#2a2a3a</span>;
}
<span style="color:#4a5568;font-style:italic">/* Scroll indicator animé — mousewheel CSS pur */</span>
<span style="color:#00ff87">@keyframes</span> <span style="color:#e8b86d">scrollWheel</span> {
  <span style="color:#f59e0b">0%</span>   { <span style="color:#00d4ff">opacity</span>: <span style="color:#f59e0b">1</span>; <span style="color:#00d4ff">transform</span>: <span style="color:#f59e0b">translateY(0)</span>; }
  <span style="color:#f59e0b">60%</span>  { <span style="color:#00d4ff">opacity</span>: <span style="color:#f59e0b">0</span>; <span style="color:#00d4ff">transform</span>: <span style="color:#f59e0b">translateY(10px)</span>; }
  <span style="color:#f59e0b">100%</span> { <span style="color:#00d4ff">opacity</span>: <span style="color:#f59e0b">1</span>; <span style="color:#00d4ff">transform</span>: <span style="color:#f59e0b">translateY(0)</span>; }
}`
    },
    php: {
      name:'PHP', desc:'Back-end · WordPress', color:'#4f7cba', color2:'#7b8de1',
      comment:"J'utilise PHP surtout côté back-end CARRI et WordPress. Ce bout vient directement de mon moteur d'acquisition — la classe Contact qui calcule la prochaine relance avec Fibonacci.",
      code:`<span style="color:#4a5568;font-style:italic">// Ma classe Contact — tirée de carri_acquisition.php</span>
<span style="color:#7c3aed">class</span> <span style="color:#e8b86d">Contact</span> {
  <span style="color:#7c3aed">public</span> <span style="color:#00d4ff">string</span>    <span style="color:#00ff87">$nomComplet</span>;
  <span style="color:#7c3aed">public</span> <span style="color:#00d4ff">int</span>       <span style="color:#00ff87">$indexFibonacci</span>;
  <span style="color:#7c3aed">public</span> <span style="color:#00d4ff">?DateTime</span> <span style="color:#00ff87">$dernierContact</span>;

  <span style="color:#4a5568;font-style:italic">// Je calcule le prochain jour de relance selon Fibonacci</span>
  <span style="color:#7c3aed">public function</span> <span style="color:#00ff87">calculerProchainRelance</span>(): <span style="color:#00d4ff">DateTime</span> {
    <span style="color:#00d4ff">$idx</span>   = min(<span style="color:#00ff87">$this</span>->indexFibonacci - <span style="color:#f59e0b">1</span>, count(<span style="color:#e8b86d">FIBONACCI_SEQUENCE</span>) - <span style="color:#f59e0b">1</span>);
    <span style="color:#00d4ff">$delai</span> = <span style="color:#e8b86d">FIBONACCI_SEQUENCE</span>[<span style="color:#00d4ff">$idx</span>];
    <span style="color:#00d4ff">$base</span>  = <span style="color:#00ff87">$this</span>->dernierContact ? clone <span style="color:#00ff87">$this</span>->dernierContact : <span style="color:#7c3aed">new</span> <span style="color:#e8b86d">DateTime</span>();
    <span style="color:#00d4ff">$base</span>->modify(<span style="color:#f59e0b">"+{$delai} days"</span>);
    <span style="color:#7c3aed">return</span> <span style="color:#00d4ff">$base</span>;
  }

  <span style="color:#4a5568;font-style:italic">// Son score décroît avec phi — plus on relance, moins c'est chaud</span>
  <span style="color:#7c3aed">public function</span> <span style="color:#00ff87">scoreFractal</span>(): <span style="color:#00d4ff">float</span> {
    <span style="color:#7c3aed">return</span> round(<span style="color:#f59e0b">100.0</span> / (<span style="color:#e8b86d">PHI</span> ** (<span style="color:#00ff87">$this</span>->indexFibonacci - <span style="color:#f59e0b">1</span>)), <span style="color:#f59e0b">2</span>);
  }
}`
    },
    js: {
      name:'JavaScript', desc:'Web dynamique · Node.js', color:'#f0db4f', color2:'#f7c948',
      comment:"JS c'est ma lingua franca du web. Ici un extrait du dashboard CARRI — mon hook custom pour gérer l'état des contacts et les scores Fibonacci.",
      code:`<span style="color:#4a5568;font-style:italic">// Dashboard CARRI — hook et score Fibonacci</span>
<span style="color:#7c3aed">const</span> <span style="color:#e8b86d">PHI</span>  = (<span style="color:#f59e0b">1</span> + Math.<span style="color:#00ff87">sqrt</span>(<span style="color:#f59e0b">5</span>)) / <span style="color:#f59e0b">2</span>; <span style="color:#4a5568;font-style:italic">// le nombre d'or</span>
<span style="color:#7c3aed">const</span> <span style="color:#e8b86d">FIB</span>  = [<span style="color:#f59e0b">1</span>,<span style="color:#f59e0b">2</span>,<span style="color:#f59e0b">3</span>,<span style="color:#f59e0b">5</span>,<span style="color:#f59e0b">8</span>,<span style="color:#f59e0b">13</span>,<span style="color:#f59e0b">21</span>,<span style="color:#f59e0b">34</span>,<span style="color:#f59e0b">55</span>,<span style="color:#f59e0b">89</span>];

<span style="color:#4a5568;font-style:italic">// Le score décroît avec phi — plus l'index est élevé, plus c'est froid</span>
<span style="color:#7c3aed">function</span> <span style="color:#00ff87">scoreFor</span>(fib) {
  <span style="color:#7c3aed">return</span> Math.<span style="color:#00ff87">round</span>(<span style="color:#f59e0b">100</span> / Math.<span style="color:#00ff87">pow</span>(<span style="color:#e8b86d">PHI</span>, fib - <span style="color:#f59e0b">1</span>) * <span style="color:#f59e0b">100</span>) / <span style="color:#f59e0b">100</span>;
}

<span style="color:#4a5568;font-style:italic">// Mon hook custom — gère 120 contacts en mémoire, réactif</span>
<span style="color:#7c3aed">function</span> <span style="color:#00ff87">useContacts</span>() {
  <span style="color:#7c3aed">const</span> [contacts, setContacts] = <span style="color:#00ff87">useState</span>(() => <span style="color:#00ff87">genContacts</span>(<span style="color:#f59e0b">120</span>));

  <span style="color:#7c3aed">const</span> <span style="color:#00ff87">update</span> = <span style="color:#00ff87">useCallback</span>((id, patch) => {
    <span style="color:#00ff87">setContacts</span>(prev => prev.<span style="color:#00ff87">map</span>(
      c => c.id === id ? { ...c, ...patch } : c
    ));
  }, []);
  <span style="color:#7c3aed">return</span> { contacts, update };
}

<span style="color:#4a5568;font-style:italic">// Kanban drag & drop — ma feature préférée du dashboard</span>
<span style="color:#7c3aed">const</span> <span style="color:#00ff87">handleDrop</span> = (targetStatut) => {
  <span style="color:#7c3aed">if</span> (dragging && dragging.statut !== targetStatut) {
    <span style="color:#00ff87">onUpdate</span>(dragging.id, { statut: targetStatut });
  }
  <span style="color:#00ff87">setDragging</span>(<span style="color:#7c3aed">null</span>);
};`
    },
    python: {
      name:'Python', desc:'Data · Automatisation · IA', color:'#3572A5', color2:'#4b8bbe',
      comment:"Python c'est mon outil de précision pour la data. Ce code vient de mon moteur d'acquisition — il lit l'Excel, classe les contacts, et calcule qui relancer aujourd'hui avec Fibonacci.",
      code:`<span style="color:#4a5568;font-style:italic"># Mon moteur Fibonacci — extrait de carri_acquisition.py</span>
<span style="color:#7c3aed">import</span> <span style="color:#00d4ff">math</span>
<span style="color:#7c3aed">from</span> <span style="color:#00d4ff">datetime</span> <span style="color:#7c3aed">import</span> date, timedelta

<span style="color:#e8b86d">PHI</span>  = (<span style="color:#f59e0b">1</span> + math.<span style="color:#00ff87">sqrt</span>(<span style="color:#f59e0b">5</span>)) / <span style="color:#f59e0b">2</span>
<span style="color:#e8b86d">FIBS</span> = [<span style="color:#f59e0b">1</span>, <span style="color:#f59e0b">2</span>, <span style="color:#f59e0b">3</span>, <span style="color:#f59e0b">5</span>, <span style="color:#f59e0b">8</span>, <span style="color:#f59e0b">13</span>, <span style="color:#f59e0b">21</span>, <span style="color:#f59e0b">34</span>, <span style="color:#f59e0b">55</span>, <span style="color:#f59e0b">89</span>]

<span style="color:#7c3aed">class</span> <span style="color:#e8b86d">Contact</span>:
  <span style="color:#7c3aed">def</span> <span style="color:#00ff87">__init__</span>(self, row: dict):
    self.nom_complet      = row.<span style="color:#00ff87">get</span>(<span style="color:#f59e0b">"Nom du Contact"</span>, <span style="color:#f59e0b">""</span>)
    self.email            = row.<span style="color:#00ff87">get</span>(<span style="color:#f59e0b">"Email"</span>, <span style="color:#f59e0b">""</span>)
    self.statut           = row.<span style="color:#00ff87">get</span>(<span style="color:#f59e0b">"Statut"</span>, <span style="color:#f59e0b">"0"</span>)
    self.index_fibonacci  = <span style="color:#00d4ff">int</span>(row.<span style="color:#00ff87">get</span>(<span style="color:#f59e0b">"Index Fibonacci"</span>, <span style="color:#f59e0b">1</span>))
    self.prochain_relance = self.<span style="color:#00ff87">calculer_prochain_relance</span>()

  <span style="color:#7c3aed">def</span> <span style="color:#00ff87">calculer_prochain_relance</span>(self):
    idx  = min(self.index_fibonacci - <span style="color:#f59e0b">1</span>, len(<span style="color:#e8b86d">FIBS</span>) - <span style="color:#f59e0b">1</span>)
    base = self.dernier_contact <span style="color:#7c3aed">or</span> date.<span style="color:#00ff87">today</span>()
    <span style="color:#7c3aed">return</span> base + timedelta(days=<span style="color:#e8b86d">FIBS</span>[idx])

  <span style="color:#7c3aed">def</span> <span style="color:#00ff87">score_fractal</span>(self) -> float:
    <span style="color:#4a5568;font-style:italic"># Plus l'index monte, moins le contact est chaud</span>
    <span style="color:#7c3aed">return</span> <span style="color:#00d4ff">round</span>(<span style="color:#f59e0b">100.0</span> / (<span style="color:#e8b86d">PHI</span> ** (self.index_fibonacci - <span style="color:#f59e0b">1</span>)), <span style="color:#f59e0b">2</span>)`
    },
    java: {
      name:'Java', desc:'Applications · Backend', color:'#b07219', color2:'#e8a020',
      comment:"Java j'ai un rapport amour-haine avec — c'est verbeux mais solide. Là c'est le FibonacciEngine que j'ai écrit pour CARRI, version production avec streams Java 17.",
      code:`<span style="color:#4a5568;font-style:italic">// FibonacciEngine.java — mon moteur de prospection</span>
<span style="color:#7c3aed">public class</span> <span style="color:#e8b86d">FibonacciEngine</span> {

  <span style="color:#7c3aed">public static final double</span> <span style="color:#e8b86d">PHI</span> = (<span style="color:#f59e0b">1</span> + Math.<span style="color:#00ff87">sqrt</span>(<span style="color:#f59e0b">5</span>)) / <span style="color:#f59e0b">2</span>;

  <span style="color:#4a5568;font-style:italic">// Je filtre les contacts à relancer aujourd'hui — streams, propre</span>
  <span style="color:#7c3aed">public</span> List&lt;<span style="color:#e8b86d">Contact</span>&gt; <span style="color:#00ff87">getContactsARelancer</span>(List&lt;<span style="color:#e8b86d">Contact</span>&gt; tous) {
    <span style="color:#7c3aed">return</span> tous.stream()
      .<span style="color:#00ff87">filter</span>(c -> !<span style="color:#f59e0b">"-"</span>.<span style="color:#00ff87">equals</span>(c.<span style="color:#00ff87">getStatut</span>()))
      .<span style="color:#00ff87">filter</span>(<span style="color:#e8b86d">Contact</span>::estARelancer)
      .<span style="color:#00ff87">collect</span>(<span style="color:#e8b86d">Collectors</span>.<span style="color:#00ff87">toList</span>());
  }

  <span style="color:#4a5568;font-style:italic">// Après envoi, j'incrémente et j'archive si séquence épuisée</span>
  <span style="color:#7c3aed">public void</span> <span style="color:#00ff87">enregistrerEnvoi</span>(<span style="color:#e8b86d">Contact</span> contact) {
    contact.<span style="color:#00ff87">incrementerFibonacci</span>();
    <span style="color:#7c3aed">if</span> (<span style="color:#f59e0b">"0"</span>.<span style="color:#00ff87">equals</span>(contact.<span style="color:#00ff87">getStatut</span>()))
      contact.<span style="color:#00ff87">setStatut</span>(<span style="color:#f59e0b">"..."</span>);
    <span style="color:#7c3aed">if</span> (contact.<span style="color:#00ff87">getIndexFibonacci</span>() > <span style="color:#e8b86d">INDEX_MAX</span>) {
      contact.<span style="color:#00ff87">setStatut</span>(<span style="color:#f59e0b">"-"</span>);
      contact.<span style="color:#00ff87">setFeuille</span>(<span style="color:#f59e0b">"Archives"</span>);
    }
  }

  <span style="color:#7c3aed">public double</span> <span style="color:#00ff87">scoreFractal</span>(<span style="color:#00d4ff">int</span> index) {
    <span style="color:#7c3aed">return</span> Math.<span style="color:#00ff87">round</span>(<span style="color:#f59e0b">100.0</span> / Math.<span style="color:#00ff87">pow</span>(<span style="color:#e8b86d">PHI</span>, index - <span style="color:#f59e0b">1</span>) * <span style="color:#f59e0b">100.0</span>) / <span style="color:#f59e0b">100.0</span>;
  }
}`
    },
    cpp: {
      name:'C++', desc:'Performance · Systèmes', color:'#aaaaaa', color2:'#00d4ff',
      comment:"C++ c'est là où j'ai codé mon plugin FolderSize pour Windows Explorer — du vrai code natif, intégré direct dans l'OS. Pas de fioritures, que de la performance.",
      code:`<span style="color:#4a5568;font-style:italic">// FolderSize.cs — mon plugin Windows Explorer (SharpShell)</span>
<span style="color:#4a5568;font-style:italic">// S'intègre direct dans l'Explorateur, zéro installation visible</span>
[<span style="color:#e8b86d">ComVisible</span>(<span style="color:#7c3aed">true</span>)]
[<span style="color:#e8b86d">COMServerAssociation</span>(<span style="color:#e8b86d">AssociationType</span>.<span style="color:#00ff87">AllFilesAndFolders</span>)]
<span style="color:#7c3aed">public class</span> <span style="color:#e8b86d">FolderSizeInfoTip</span> : <span style="color:#e8b86d">SharpInfoTipHandler</span> {

  <span style="color:#4a5568;font-style:italic">// Cache 30s — pas question de recalculer à chaque survol</span>
  <span style="color:#7c3aed">private static readonly</span> <span style="color:#e8b86d">ConcurrentDictionary</span>&lt;<span style="color:#00d4ff">string</span>, <span style="color:#e8b86d">CacheEntry</span>&gt; _cache
    = <span style="color:#7c3aed">new</span> <span style="color:#e8b86d">ConcurrentDictionary</span>&lt;&gt;();

  <span style="color:#4a5568;font-style:italic">// Je calcule la taille totale d'un dossier récursivement</span>
  <span style="color:#7c3aed">private static long</span> <span style="color:#00ff87">ComputeFolderSize</span>(<span style="color:#00d4ff">string</span> path) {
    <span style="color:#7c3aed">long</span> total = <span style="color:#f59e0b">0</span>;
    <span style="color:#7c3aed">foreach</span> (<span style="color:#00d4ff">string</span> file <span style="color:#7c3aed">in</span> Directory.<span style="color:#00ff87">EnumerateFiles</span>(path))
      <span style="color:#7c3aed">try</span> { total += <span style="color:#7c3aed">new</span> <span style="color:#e8b86d">FileInfo</span>(file).Length; } <span style="color:#7c3aed">catch</span> { }
    <span style="color:#7c3aed">foreach</span> (<span style="color:#00d4ff">string</span> dir <span style="color:#7c3aed">in</span> Directory.<span style="color:#00ff87">EnumerateDirectories</span>(path))
      total += <span style="color:#00ff87">ComputeFolderSize</span>(dir);
    <span style="color:#7c3aed">return</span> total;
  }

  <span style="color:#4a5568;font-style:italic">// Format lisible — octets, Ko, Mo, Go</span>
  <span style="color:#7c3aed">private static string</span> <span style="color:#00ff87">FormatSize</span>(<span style="color:#7c3aed">long</span> bytes) {
    <span style="color:#7c3aed">if</span> (bytes < <span style="color:#f59e0b">1024</span>)          <span style="color:#7c3aed">return</span> bytes + <span style="color:#f59e0b">" octets"</span>;
    <span style="color:#7c3aed">if</span> (bytes < <span style="color:#f59e0b">1024L * 1024</span>) <span style="color:#7c3aed">return</span> <span style="color:#00d4ff">string</span>.<span style="color:#00ff87">Format</span>(<span style="color:#f59e0b">"{0:F1} Ko"</span>, bytes / <span style="color:#f59e0b">1024.0</span>);
    <span style="color:#7c3aed">return</span> <span style="color:#00d4ff">string</span>.<span style="color:#00ff87">Format</span>(<span style="color:#f59e0b">"{0:F2} Mo"</span>, bytes / (<span style="color:#f59e0b">1024.0 * 1024</span>));
  }
}`
    },
    sql: {
      name:'SQL', desc:'Analyse · BDD · CEGID', color:'#336791', color2:'#5b9bd5',
      comment:"SQL c'est ma langue pour interroger les données. Je l'utilise tous les jours chez CARRI — CEGID, reporting, analyses de pipeline. Là c'est du suivi d'acquisition en direct.",
      code:`<span style="color:#4a5568;font-style:italic">-- Mes requêtes d'analyse du pipeline B2B CARRI</span>
<span style="color:#7c3aed">SELECT</span>
  c.nom_complet,
  c.societe,
  c.statut,
  c.index_fibonacci,
  <span style="color:#00ff87">ROUND</span>(<span style="color:#f59e0b">100.0</span> / <span style="color:#00ff87">POWER</span>(<span style="color:#f59e0b">1.618</span>, c.index_fibonacci - <span style="color:#f59e0b">1</span>), <span style="color:#f59e0b">2</span>) <span style="color:#7c3aed">AS</span> score_fractal,
  c.prochain_relance
<span style="color:#7c3aed">FROM</span> contacts c
<span style="color:#7c3aed">WHERE</span> c.statut != <span style="color:#f59e0b">'-'</span>
  <span style="color:#7c3aed">AND</span> c.prochain_relance <= <span style="color:#00ff87">CURDATE</span>()
<span style="color:#7c3aed">ORDER BY</span> score_fractal <span style="color:#7c3aed">DESC</span>;

<span style="color:#4a5568;font-style:italic">-- Taux de réponse par canal — LinkedIn vs Email</span>
<span style="color:#7c3aed">SELECT</span>
  canal,
  <span style="color:#00ff87">COUNT</span>(*) <span style="color:#7c3aed">AS</span> total,
  <span style="color:#00ff87">ROUND</span>(
    <span style="color:#00ff87">SUM</span>(<span style="color:#7c3aed">CASE WHEN</span> statut = <span style="color:#f59e0b">'+'</span> <span style="color:#7c3aed">THEN</span> <span style="color:#f59e0b">1</span> <span style="color:#7c3aed">ELSE</span> <span style="color:#f59e0b">0</span> <span style="color:#7c3aed">END</span>) * <span style="color:#f59e0b">100.0</span> / <span style="color:#00ff87">COUNT</span>(*), <span style="color:#f59e0b">2</span>
  ) <span style="color:#7c3aed">AS</span> taux_pct
<span style="color:#7c3aed">FROM</span> contacts
<span style="color:#7c3aed">GROUP BY</span> canal;

<span style="color:#4a5568;font-style:italic">-- Mise à jour après envoi</span>
<span style="color:#7c3aed">UPDATE</span> contacts
<span style="color:#7c3aed">SET</span>
  index_fibonacci = index_fibonacci + <span style="color:#f59e0b">1</span>,
  dernier_contact = <span style="color:#00ff87">NOW</span>(),
  statut = <span style="color:#7c3aed">CASE WHEN</span> statut = <span style="color:#f59e0b">'0'</span> <span style="color:#7c3aed">THEN</span> <span style="color:#f59e0b">'...'</span> <span style="color:#7c3aed">ELSE</span> statut <span style="color:#7c3aed">END</span>
<span style="color:#7c3aed">WHERE</span> id = :contact_id;`
    },
    react: {
      name:'React.js', desc:'SPA · Interfaces modernes', color:'#61dafb', color2:'#21a5c4',
      comment:"React c'est ce que j'utilise pour mes dashboards. Ce bout vient du dashboard CARRI complet — j'aime comment les composants se combinent et que tout réagit en temps réel.",
      code:`<span style="color:#4a5568;font-style:italic">// StatCard — extrait de carri-dashboard.jsx</span>
<span style="color:#7c3aed">function</span> <span style="color:#00ff87">StatCard</span>({ label, value, sub, accent, delta }) {
  <span style="color:#7c3aed">return</span> (
    &lt;<span style="color:#e8b86d">div</span>
      style={{ background: COLORS.card, borderRadius: <span style="color:#f59e0b">10</span> }}
      onMouseEnter={e =&gt; e.currentTarget.style.borderColor = accent}
      onMouseLeave={e =&gt; e.currentTarget.style.borderColor = COLORS.border}&gt;
      <span style="color:#4a5568;font-style:italic">{/* Barre colorée en bas — je trouve ce détail super propre */}</span>
      &lt;<span style="color:#e8b86d">div</span> style={{ height:<span style="color:#f59e0b">2</span>, background: accent }}/&gt;
      &lt;<span style="color:#e8b86d">div</span>&gt;{label}&lt;/<span style="color:#e8b86d">div</span>&gt;
      &lt;<span style="color:#e8b86d">div</span> style={{ fontSize:<span style="color:#f59e0b">34</span>, fontWeight:<span style="color:#f59e0b">900</span> }}&gt;{value}&lt;/<span style="color:#e8b86d">div</span>&gt;
      {delta !== undefined &amp;&amp; (
        &lt;<span style="color:#e8b86d">span</span> style={{ color: delta &gt;= <span style="color:#f59e0b">0</span> ? COLORS.green : COLORS.red }}&gt;
          {delta &gt;= <span style="color:#f59e0b">0</span> ? <span style="color:#f59e0b">"+"</span> : <span style="color:#f59e0b">""</span>}{delta}%
        &lt;/<span style="color:#e8b86d">span</span>&gt;
      )}
    &lt;/<span style="color:#e8b86d">div</span>&gt;
  );
}

<span style="color:#4a5568;font-style:italic">// Kanban drag &amp; drop — ma feature préférée</span>
<span style="color:#7c3aed">const</span> [dragging, setDragging] = <span style="color:#00ff87">useState</span>(<span style="color:#7c3aed">null</span>);

<span style="color:#7c3aed">const</span> <span style="color:#00ff87">handleDrop</span> = (targetStatut) => {
  <span style="color:#7c3aed">if</span> (dragging &amp;&amp; dragging.statut !== targetStatut) {
    <span style="color:#00ff87">onUpdate</span>(dragging.id, { statut: targetStatut });
    <span style="color:#00ff87">toast</span>(<span style="color:#f59e0b">\`\${dragging.prenom} → \${targetStatut}\`</span>);
  }
  <span style="color:#00ff87">setDragging</span>(<span style="color:#7c3aed">null</span>);
};`
    },
    node: {
      name:'Node.js', desc:'APIs · Automatisation', color:'#68a063', color2:'#3c873a',
      comment:"Node c'est mon serveur d'automatisation — pour les APIs rapides et les scripts d'acquisition, nickel. Là c'est l'architecture du pipeline B2B avec envoi Brevo.",
      code:`<span style="color:#4a5568;font-style:italic">// Pipeline d'acquisition B2B en Node.js</span>
<span style="color:#7c3aed">const</span> <span style="color:#e8b86d">PHI</span>  = (<span style="color:#f59e0b">1</span> + Math.<span style="color:#00ff87">sqrt</span>(<span style="color:#f59e0b">5</span>)) / <span style="color:#f59e0b">2</span>;
<span style="color:#7c3aed">const</span> <span style="color:#e8b86d">FIBS</span> = [<span style="color:#f59e0b">1</span>,<span style="color:#f59e0b">2</span>,<span style="color:#f59e0b">3</span>,<span style="color:#f59e0b">5</span>,<span style="color:#f59e0b">8</span>,<span style="color:#f59e0b">13</span>,<span style="color:#f59e0b">21</span>,<span style="color:#f59e0b">34</span>];

<span style="color:#4a5568;font-style:italic">// Je construis les séquences de relance avec Fibonacci</span>
<span style="color:#7c3aed">const</span> <span style="color:#00ff87">buildSequence</span> = (leads) =>
  leads.<span style="color:#00ff87">map</span>((lead, i) => ({
    ...lead,
    score:  Math.<span style="color:#00ff87">round</span>(<span style="color:#f59e0b">100</span> / Math.<span style="color:#00ff87">pow</span>(<span style="color:#e8b86d">PHI</span>, i) * <span style="color:#f59e0b">100</span>) / <span style="color:#f59e0b">100</span>,
    sendAt: Date.<span style="color:#00ff87">now</span>() + <span style="color:#e8b86d">FIBS</span>[i % <span style="color:#e8b86d">FIBS</span>.length] * <span style="color:#f59e0b">86_400_000</span>,
  }));

<span style="color:#4a5568;font-style:italic">// J'envoie via Brevo — propre et sans dépendance lourde</span>
<span style="color:#7c3aed">const</span> <span style="color:#00ff87">sendEmail</span> = <span style="color:#7c3aed">async</span> (contact, sujet, html) => {
  <span style="color:#7c3aed">const</span> res = <span style="color:#7c3aed">await</span> <span style="color:#00ff87">fetch</span>(<span style="color:#f59e0b">'https://api.brevo.com/v3/smtp/email'</span>, {
    method: <span style="color:#f59e0b">'POST'</span>,
    headers: { <span style="color:#f59e0b">'api-key'</span>: process.env.<span style="color:#e8b86d">BREVO_KEY</span> },
    body: JSON.<span style="color:#00ff87">stringify</span>({
      sender:      { name: <span style="color:#f59e0b">'CARRI Systems'</span>, email: <span style="color:#f59e0b">'hello@carri.fr'</span> },
      to:          [{ email: contact.email }],
      subject:     sujet,
      htmlContent: html,
    }),
  });
  <span style="color:#7c3aed">return</span> res.ok;
};`
    },
    gas: {
      name:'Google Apps Script', desc:'Automatisation G Suite', color:'#4285f4', color2:'#34a853',
      comment:"Google Apps Script c'est mon arme secrète pour automatiser Sheets, Gmail et Calendar sans sortir de l'éco-système Google. Super pratique pour les rapports automatiques du matin.",
      code:`<span style="color:#4a5568;font-style:italic">// Rapport automatique Google Sheets → Gmail</span>
<span style="color:#4a5568;font-style:italic">// Tourne tous les matins à 8h via un trigger automatique</span>
<span style="color:#7c3aed">function</span> <span style="color:#00ff87">envoyerRapportQuotidien</span>() {
  <span style="color:#7c3aed">const</span> sheet = <span style="color:#e8b86d">SpreadsheetApp</span>
    .<span style="color:#00ff87">openById</span>(<span style="color:#f59e0b">'MON_ID_SPREADSHEET'</span>)
    .<span style="color:#00ff87">getSheetByName</span>(<span style="color:#f59e0b">'Actif'</span>);

  <span style="color:#7c3aed">const</span> data  = sheet.<span style="color:#00ff87">getDataRange</span>().<span style="color:#00ff87">getValues</span>();
  <span style="color:#7c3aed">const</span> today = <span style="color:#7c3aed">new</span> <span style="color:#e8b86d">Date</span>();

  <span style="color:#4a5568;font-style:italic">// Je filtre les contacts à relancer aujourd'hui</span>
  <span style="color:#7c3aed">const</span> aRelancer = data.<span style="color:#00ff87">slice</span>(<span style="color:#f59e0b">1</span>).<span style="color:#00ff87">filter</span>(row => {
    <span style="color:#7c3aed">const</span> dateRelance = <span style="color:#7c3aed">new</span> <span style="color:#e8b86d">Date</span>(row[<span style="color:#f59e0b">6</span>]);
    <span style="color:#7c3aed">return</span> dateRelance <= today &amp;&amp; row[<span style="color:#f59e0b">3</span>] !== <span style="color:#f59e0b">'-'</span>;
  });

  <span style="color:#4a5568;font-style:italic">// Je construis le rapport HTML</span>
  <span style="color:#7c3aed">const</span> lignes = aRelancer.<span style="color:#00ff87">map</span>(r =>
    <span style="color:#f59e0b">\`&lt;tr&gt;&lt;td&gt;\${r[0]}&lt;/td&gt;&lt;td&gt;\${r[1]}&lt;/td&gt;&lt;/tr&gt;\`</span>
  ).<span style="color:#00ff87">join</span>(<span style="color:#f59e0b">''</span>);

  <span style="color:#4a5568;font-style:italic">// Envoi — je reçois ça dans ma boîte chaque matin</span>
  <span style="color:#e8b86d">MailApp</span>.<span style="color:#00ff87">sendEmail</span>({
    to:       <span style="color:#f59e0b">'moi@carri.fr'</span>,
    subject:  <span style="color:#f59e0b">\`[CARRI] Rapport \${today.toLocaleDateString('fr-FR')}\`</span>,
    htmlBody: <span style="color:#f59e0b">\`&lt;h2&gt;Relances du jour&lt;/h2&gt;&lt;table&gt;\${lignes}&lt;/table&gt;\`</span>,
  });
}`
    }
  };

  function openBubble(key) {
    const d = BUBBLES[key];
    if (!d) return;
    const overlay = document.getElementById('codeBubbleOverlay');
    const bubble  = document.getElementById('codeBubble');
    document.getElementById('bubbleLangName').textContent = d.name;
    document.getElementById('bubbleDesc').textContent     = d.desc;
    document.getElementById('bubbleComment').textContent  = d.comment;
    document.getElementById('bubbleCode').innerHTML       = d.code;
    bubble.style.setProperty('--bubble-color',  d.color);
    bubble.style.setProperty('--bubble-color2', d.color2);
    bubble.style.boxShadow = `0 0 0 1px ${d.color}, 0 0 60px ${d.color}40, 0 0 120px ${d.color}18, inset 0 0 60px ${d.color}08`;
    overlay.style.display = 'flex';
    document.body.style.overflow = 'hidden';
    bubble.style.animation = 'none';
    bubble.offsetHeight;
    bubble.style.animation = '';
  }

  function closeBubble() {
    document.getElementById('codeBubbleOverlay').style.display = 'none';
    document.body.style.overflow = '';
  }

  document.addEventListener('keydown', e => { if (e.key === 'Escape') closeBubble(); });
</script>

<!-- ═══════════════════════════════════════════════════════════════
     CHATBOT STYLES
═══════════════════════════════════════════════════════════════ -->
<style>
  /* FAB button */
  /* Speech bubble above FAB */
  #chatBubbleTooltip {
    position: fixed;
    bottom: 100px;
    right: 32px;
    background: #0d0d16;
    border: 1px solid var(--accent);
    border-radius: 12px;
    padding: 10px 16px;
    font-family: 'Titillium Web', sans-serif;
    font-size: 13px;
    color: var(--text);
    white-space: nowrap;
    z-index: 599;
    box-shadow: 0 0 0 1px var(--accent), 0 0 24px rgba(0,255,135,0.2);
    animation: bubbleAppear 0.4s cubic-bezier(0.34,1.56,0.64,1) forwards,
               bubbleDisappear 0.4s ease 5s forwards;
    pointer-events: none;
  }
  /* Triangle pointing down toward the FAB */
  #chatBubbleTooltip::after {
    content: '';
    position: absolute;
    bottom: -7px;
    right: 22px;
    width: 12px;
    height: 12px;
    background: #0d0d16;
    border-right: 1px solid var(--accent);
    border-bottom: 1px solid var(--accent);
    transform: rotate(45deg);
  }
  @keyframes bubbleAppear {
    from { opacity: 0; transform: translateY(10px) scale(0.9); }
    to   { opacity: 1; transform: translateY(0)   scale(1); }
  }
  @keyframes bubbleDisappear {
    from { opacity: 1; transform: translateY(0); }
    to   { opacity: 0; transform: translateY(6px); pointer-events: none; }
  }

  #chatFab {
    position: fixed;
    bottom: 32px;
    right: 32px;
    width: 56px;
    height: 56px;
    border-radius: 50%;
    background: var(--accent);
    border: none;
    cursor: pointer;
    z-index: 600;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 0 0 0 rgba(0,255,135,0.4);
    animation: fabPulse 2.5s ease-in-out infinite;
    transition: transform 0.2s;
  }
  #chatFab:hover { transform: scale(1.1); }
  @keyframes fabPulse {
    0%,100% { box-shadow: 0 0 0 0 rgba(0,255,135,0.4); }
    50%      { box-shadow: 0 0 0 14px rgba(0,255,135,0); }
  }
  #chatFab svg { width: 24px; height: 24px; fill: #0a0a0f; }

  /* Panel */
  #chatPanel {
    position: fixed;
    bottom: 100px;
    right: 32px;
    width: 370px;
    max-height: 560px;
    background: #0d0d16;
    border: 1px solid var(--accent);
    border-radius: 16px;
    display: flex;
    flex-direction: column;
    overflow: hidden;
    z-index: 600;
    box-shadow: 0 0 0 1px var(--accent), 0 0 50px rgba(0,255,135,0.15), 0 0 100px rgba(0,255,135,0.06);
    transform: translateY(20px) scale(0.95);
    opacity: 0;
    pointer-events: none;
    transition: all 0.3s cubic-bezier(0.34,1.56,0.64,1);
  }
  #chatPanel.open {
    transform: translateY(0) scale(1);
    opacity: 1;
    pointer-events: all;
  }

  /* Header */
  .chat-header {
    padding: 14px 18px;
    border-bottom: 1px solid rgba(0,255,135,0.15);
    display: flex;
    align-items: center;
    gap: 10px;
    flex-shrink: 0;
    justify-content: space-between;
  }
  .chat-header-dot {
    width: 8px; height: 8px; border-radius: 50%;
    background: var(--accent);
    box-shadow: 0 0 8px var(--accent), 0 0 16px var(--accent);
    animation: pulse-dot 1.8s ease-in-out infinite;
    flex-shrink: 0;
  }
  .chat-header-title {
    font-family: 'Titillium Web', sans-serif;
    font-size: 13px; font-weight: 700;
    color: var(--accent); letter-spacing: 1px;
    flex: 1;
  }
  .chat-header-sub {
    font-size: 10px; color: var(--muted);
    font-family: 'Titillium Web', sans-serif;
  }
  #chatCloseBtn {
    background: none; border: none; color: var(--muted);
    cursor: pointer; font-size: 18px; padding: 0 4px;
    transition: color 0.2s;
  }
  #chatCloseBtn:hover { color: var(--accent); }

  /* Messages */
  #chatMessages {
    flex: 1;
    overflow-y: auto;
    padding: 16px;
    display: flex;
    flex-direction: column;
    gap: 10px;
    scrollbar-width: thin;
    scrollbar-color: var(--accent) transparent;
  }

  .msg {
    max-width: 88%;
    padding: 10px 14px;
    border-radius: 12px;
    font-family: 'Titillium Web', sans-serif;
    font-size: 13px;
    line-height: 1.6;
    animation: msgIn 0.25s ease;
  }
  @keyframes msgIn {
    from { opacity: 0; transform: translateY(8px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .msg-bot {
    background: rgba(0,255,135,0.07);
    border: 1px solid rgba(0,255,135,0.15);
    color: var(--text);
    align-self: flex-start;
    border-bottom-left-radius: 4px;
  }
  .msg-user {
    background: rgba(124,58,237,0.15);
    border: 1px solid rgba(124,58,237,0.25);
    color: var(--text);
    align-self: flex-end;
    border-bottom-right-radius: 4px;
  }
  .msg-typing {
    background: rgba(0,255,135,0.07);
    border: 1px solid rgba(0,255,135,0.1);
    align-self: flex-start;
    border-bottom-left-radius: 4px;
    display: flex;
    gap: 5px;
    align-items: center;
    padding: 12px 16px;
  }
  .typing-dot {
    width: 6px; height: 6px; border-radius: 50%;
    background: var(--accent); opacity: 0.4;
    animation: typingBounce 1.2s ease-in-out infinite;
  }
  .typing-dot:nth-child(2) { animation-delay: 0.2s; }
  .typing-dot:nth-child(3) { animation-delay: 0.4s; }
  @keyframes typingBounce {
    0%,100% { opacity: 0.4; transform: translateY(0); }
    50%      { opacity: 1;   transform: translateY(-4px); }
  }

  /* Quick replies */
  .quick-replies {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    padding: 0 16px 10px;
  }
  .qr-btn {
    font-family: 'Titillium Web', sans-serif;
    font-size: 11px;
    padding: 5px 12px;
    border: 1px solid rgba(0,255,135,0.3);
    border-radius: 20px;
    background: transparent;
    color: var(--accent);
    cursor: pointer;
    transition: all 0.2s;
  }
  .qr-btn:hover { background: rgba(0,255,135,0.1); border-color: var(--accent); }

  /* Input */
  .chat-input-wrap {
    display: flex;
    gap: 8px;
    padding: 12px 16px;
    border-top: 1px solid rgba(0,255,135,0.1);
    flex-shrink: 0;
  }
  #chatInput {
    flex: 1;
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(0,255,135,0.2);
    border-radius: 8px;
    padding: 8px 12px;
    color: var(--text);
    font-family: 'Titillium Web', sans-serif;
    font-size: 13px;
    outline: none;
    transition: border-color 0.2s;
  }
  #chatInput:focus { border-color: var(--accent); }
  #chatInput::placeholder { color: var(--muted); }
  #chatSendBtn {
    width: 36px; height: 36px;
    background: var(--accent);
    border: none; border-radius: 8px;
    cursor: pointer;
    display: flex; align-items: center; justify-content: center;
    transition: all 0.2s; flex-shrink: 0;
  }
  #chatSendBtn:hover { background: #00e07a; transform: scale(1.05); }
  #chatSendBtn svg { width: 16px; height: 16px; fill: #0a0a0f; }

  @media (max-width: 768px) {
    #chatPanel { width: calc(100vw - 32px); right: 16px; bottom: 90px; }
    #chatFab   { right: 16px; bottom: 24px; }
  }
</style>

<!-- ═══════════════════════════════════════════════════════════════
     CHATBOT HTML
═══════════════════════════════════════════════════════════════ -->

<!-- Speech bubble tooltip -->
<div id="chatBubbleTooltip">Vous pouvez me parler ici :)</div>

<!-- FAB -->
<button id="chatFab" onclick="toggleChat()" title="Contacter Théophile">
  <svg viewBox="0 0 24 24"><path d="M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm-2 12H6v-2h12v2zm0-3H6V9h12v2zm0-3H6V6h12v2z"/></svg>
</button>

<!-- Chat Panel -->
<div id="chatPanel">
  <div class="chat-header">
    <div class="chat-header-dot"></div>
    <div>
      <div class="chat-header-title">Assistant · Théophile TOKRE</div>
      <div class="chat-header-sub" id="chatHeaderSub">En ligne</div>
    </div>
    <button id="chatCloseBtn" onclick="toggleChat()">✕</button>
  </div>
  <div id="chatMessages"></div>
  <div class="quick-replies" id="quickReplies"></div>
  <div class="chat-input-wrap">
    <input id="chatInput" placeholder="Écrivez votre message..." autocomplete="off"
           onkeydown="if(event.key==='Enter')sendMsg()"/>
    <button id="chatSendBtn" onclick="sendMsg()">
      <svg viewBox="0 0 24 24"><path d="M2.01 21L23 12 2.01 3 2 10l15 2-15 2z"/></svg>
    </button>
  </div>
</div>

<!-- ═══════════════════════════════════════════════════════════════
     CHATBOT SCRIPT
═══════════════════════════════════════════════════════════════ -->
<script>
(function() {
  // ── State ──────────────────────────────────────────────────────
  let chatOpen    = false;
  let visitorType = null;   // detected profile
  let phase       = 'welcome'; // conversation phase
  let history     = [];     // message history for Claude API

  // ── DOM ────────────────────────────────────────────────────────
  const panel    = document.getElementById('chatPanel');
  const msgs     = document.getElementById('chatMessages');
  const input    = document.getElementById('chatInput');
  const qrWrap   = document.getElementById('quickReplies');
  const headerSub = document.getElementById('chatHeaderSub');

  // ── Toggle ─────────────────────────────────────────────────────
  window.toggleChat = function() {
    chatOpen = !chatOpen;
    panel.classList.toggle('open', chatOpen);
    // Hide the speech bubble as soon as user opens the chat
    const tooltip = document.getElementById('chatBubbleTooltip');
    if (tooltip) tooltip.style.display = 'none';
    if (chatOpen && msgs.children.length === 0) initChat();
  };

  // Auto-remove tooltip after its animation completes (3.4s)
  setTimeout(() => {
    const tooltip = document.getElementById('chatBubbleTooltip');
    if (tooltip) tooltip.style.display = 'none';
  }, 5400);

  // ── Init ───────────────────────────────────────────────────────
  function initChat() {
    phase = 'welcome';
    history = [];
    botMsg("Bonjour ! Je suis l'assistant de Théophile. 👋\n\nQui êtes-vous ?");
    showQuickReplies(['Client', 'Étudiant', 'Confrère', 'Recruteur', 'Proche', 'Collègue']);
  }

  // ── Quick replies ──────────────────────────────────────────────
  function showQuickReplies(options) {
    qrWrap.innerHTML = '';
    options.forEach(opt => {
      const btn = document.createElement('button');
      btn.className = 'qr-btn';
      btn.textContent = opt;
      btn.onclick = () => { clearQR(); handleUserInput(opt); };
      qrWrap.appendChild(btn);
    });
  }

  function clearQR() { qrWrap.innerHTML = ''; }

  // ── Send from input ────────────────────────────────────────────
  window.sendMsg = function() {
    const txt = input.value.trim();
    if (!txt) return;
    input.value = '';
    clearQR();
    handleUserInput(txt);
  };

  // ── Display helpers ────────────────────────────────────────────
  function botMsg(text) {
    const div = document.createElement('div');
    div.className = 'msg msg-bot';
    div.innerHTML = text.replace(/\n/g, '<br>');
    msgs.appendChild(div);
    msgs.scrollTop = msgs.scrollHeight;
  }

  function userMsg(text) {
    const div = document.createElement('div');
    div.className = 'msg msg-user';
    div.textContent = text;
    msgs.appendChild(div);
    msgs.scrollTop = msgs.scrollHeight;
  }

  function showTyping() {
    const div = document.createElement('div');
    div.className = 'msg msg-typing';
    div.id = 'typingIndicator';
    div.innerHTML = '<div class="typing-dot"></div><div class="typing-dot"></div><div class="typing-dot"></div>';
    msgs.appendChild(div);
    msgs.scrollTop = msgs.scrollHeight;
  }

  function hideTyping() {
    const t = document.getElementById('typingIndicator');
    if (t) t.remove();
  }

  // ── Core handler ───────────────────────────────────────────────
  function handleUserInput(text) {
    userMsg(text);

    // ── Phase: welcome — detect profile ──────────────────────────
    if (phase === 'welcome') {
      const t = text.toLowerCase();
      if (t.includes('client'))    { visitorType = 'client';    phase = 'conv'; startProfile('client'); return; }
      if (t.includes('étudiant') || t.includes('etudiant')) { visitorType = 'etudiant'; phase = 'conv'; startProfile('etudiant'); return; }
      if (t.includes('confrère') || t.includes('confrere')) { visitorType = 'confrere'; phase = 'conv'; startProfile('confrere'); return; }
      if (t.includes('recruteur')) { visitorType = 'recruteur'; phase = 'conv'; startProfile('recruteur'); return; }
      if (t.includes('proche'))    { visitorType = 'proche';    phase = 'proche_q1'; askGarba(); return; }
      if (t.includes('collègue') || t.includes('collegue')) { visitorType = 'collegue'; collegueMsg(); return; }
      botMsg("Je n'ai pas compris. Vous êtes...");
      showQuickReplies(['Client', 'Étudiant', 'Confrère', 'Recruteur', 'Proche', 'Collègue']);
      return;
    }

    // ── Phase: proche Q1 — garba question ────────────────────────
    if (phase === 'proche_q1') {
      const t2 = text.toLowerCase().replace(/[^a-z]/g,'');
      if (t2.includes('garbatigui') || t2.includes('garba')) {
        phase = 'proche_q2';
        showTyping();
        setTimeout(() => { hideTyping(); botMsg("Exact ! 😄\n\nEt dis-moi... c'est qui ?"); }, 800);
      } else {
        showTyping();
        setTimeout(() => { hideTyping(); botMsg("Hmm... je suis pas sûr que tu sois vraiment un proche 🤔\n\nRéessaie : comment s'appelle le vendeur de garba ?"); }, 700);
      }
      return;
    }

    // ── Phase: proche Q2 — identity ──────────────────────────────
    if (phase === 'proche_q2') {
      phase = 'conv';
      const t3 = text.toLowerCase().replace(/[éèêë]/g,'e').replace(/[àâ]/g,'a');
      const resp = {
        'ta cherie': "BB tu es la meilleure. Je t'embrasse ! ❤️",
        'cherie':    "BB tu es la meilleure. Je t'embrasse ! ❤️",
        'copine':    "Heh toi là, quitte ici ! 😂",
        'semoule':   "Chaaaaaapiooon !!! 🏆",
        'champikilo':"Petit, faut bosser dur hein ! 💪",
        'papa':      "Je t'embrasse papa ! Que Dieu te garde ! 🙏",
        'maman':     "Je t'embrasse maman ! Que Dieu te garde ! 🙏",
        'chocolate': "Choco on est arrivés loin hein ! Que Dieu veille sur nous ! 🙌",
        'chocolaté': "Choco on est arrivés loin hein ! Que Dieu veille sur nous ! 🙌",
      };
      let found = null;
      for (const [k,v] of Object.entries(resp)) {
        if (t3.includes(k)) { found = v; break; }
      }
      if (found) {
        showTyping();
        setTimeout(() => { hideTyping(); botMsg(found); }, 700);
      } else {
        showTyping();
        setTimeout(() => { hideTyping(); botMsg("Hmmm je te reconnais pas trop là 😅 Théophile te dira bonjour lui-même !"); }, 700);
      }
      return;
    }

    // ── Phase: conv — delegate to Claude API ─────────────────────
    if (phase === 'conv') {
      callClaude(text);
    }
  }

  // ── Proche intro ────────────────────────────────────────────────
  function askGarba() {
    showTyping();
    setTimeout(() => {
      hideTyping();
      botMsg("Ah un proche ! On va vérifier ça 😄\n\nQuestion : Comment s'appelle le vendeur de garba ?");
    }, 800);
  }

  // ── Collègue ────────────────────────────────────────────────────
  function collegueMsg() {
    showTyping();
    setTimeout(() => {
      hideTyping();
      botMsg("Cesse de fouiner mon pote. Concentre-toi sur tes propres tâches. MERCI ! 😄");
    }, 600);
  }

  // ── Profile openers (direct bot messages, no Claude needed) ────
  function startProfile(type) {
    const openers = {
      client:    "Super, bienvenue ! 🤝\n\nDites-moi, quel projet vous amène ? Je suis là pour cerner votre besoin et voir comment Théophile peut vous aider.",
      etudiant:  "Cool, bienvenue ! 🎓\n\nAlors, qu'est-ce qui vous a amené sur ce portfolio ? Une curiosité sur un projet, une technologie spécifique, ou autre chose ?",
      confrere:  "Salut l'ami 👋\n\nOn peut parler IT, gaming, échanger sur des projets... Viens prendre un verre !\n\nNote au passage : le code et les projets de Théophile lui appartiennent. Tu t'amuses avec ça juridiquement, c'est chaud. Et physiquement aussi — il sait où chercher 😈\n\nSur ce, c'est quoi ta stack ?",
      recruteur: "Excellente initiative de venir ici. 📋\n\nDites-moi, vous recrutez pour quel type de poste ? Avant de vous présenter Théophile, j'aimerais comprendre ce que vous recherchez vraiment.",
    };
    showTyping();
    setTimeout(() => {
      hideTyping();
      history.push({ role: 'assistant', content: openers[type] });
      botMsg(openers[type]);
      if (type === 'confrere') phase = 'conv'; // hand off to Claude
    }, 900);
  }

  // ── Claude API call ─────────────────────────────────────────────
  async function callClaude(userText) {
    history.push({ role: 'user', content: userText });
    showTyping();
    headerSub.textContent = 'En train d\'écrire...';

    // Build system prompt based on detected profile
    const systemPrompts = {
      client: `Tu es l'assistant personnel de Théophile TOKRE, un concepteur UX, développeur et data analyst basé à Paris.
Tu parles à un CLIENT potentiel. Ton but : cerner son besoin avec des questions précises et le guider vers un contact direct avec Théophile.
Quand le besoin est clairement cerné, donne-lui le numéro de téléphone : +33775833469 et l'email : Theophileaetokre@yahoo.com
Sois professionnel, chaleureux, concis. Ne donne pas le contact avant d'avoir bien compris le besoin.
Tu parles en français. Limites tes réponses à 3-4 phrases max.`,

      etudiant: `Tu es l'assistant personnel de Théophile TOKRE, développeur, designer et data analyst à Paris.
Tu parles à un ÉTUDIANT curieux. Ton but : comprendre sa curiosité (projet, techno, alternance, stage, conseil ?), l'orienter et si pertinent le mettre en contact.
Quand tu sens que l'étudiant est sérieux dans sa démarche, propose de le mettre en contact : numéro +33775833469, email : Theophileaetokre@yahoo.com
Sois accessible, motivant, honnête. 3-4 phrases max.`,

      confrere: `Tu es l'assistant personnel de Théophile TOKRE.
Tu parles à un CONFRÈRE développeur / technicien / créatif. Ton ton : direct, cool, entre pairs.
Tu peux parler IT, gaming, projets. Rappelle subtilement que le code de Théophile lui appartient et que toute tentative de vol ou copie sans autorisation est illégale.
Sois décontracté mais clair. 3-4 phrases max. En français.`,

      recruteur: `Tu es l'assistant personnel de Théophile TOKRE et tu mènes un ENTRETIEN D'EMBAUCHE À L'ENVERS.
Tu parles à un RECRUTEUR. C'est Théophile qui recrute le recruteur, pas l'inverse.
Pose des questions sur le poste, l'équipe, la culture de l'entreprise, les challenges, la rémunération, les perspectives.
Mets en valeur les compétences de Théophile : UX/UI, dev web full-stack, SQL/data, IA, gestion de projet, HPC.
Montre qu'il s'adapte vite et apporte une vraie valeur ajoutée. Quand l'échange a mûri, donne le contact : +33775833469 / Theophileaetokre@yahoo.com
Ton : confiant, stratégique, posé. 3-4 phrases max. En français.`,

      proche: `Tu es l'assistant de Théophile TOKRE. Tu parles à un PROCHE — famille ou ami.
Ton : souple, familier, chaleureux, à l'ivoirienne. Fais la causette, demande comment ça va, dis que Théophile sera content de les voir.
3 phrases max. Très familier.`,
    };

    const systemPrompt = systemPrompts[visitorType] || systemPrompts.client;

    try {
      const response = await fetch('https://api.anthropic.com/v1/messages', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({
          model: 'claude-sonnet-4-20250514',
          max_tokens: 300,
          system: systemPrompt,
          messages: history
        })
      });

      const data = await response.json();
      hideTyping();
      headerSub.textContent = 'En ligne';

      const reply = data.content?.[0]?.text || "Je n'ai pas pu répondre, désolé.";
      history.push({ role: 'assistant', content: reply });
      botMsg(reply);

    } catch(err) {
      hideTyping();
      headerSub.textContent = 'En ligne';
      botMsg("Une erreur s'est produite. Réessayez dans un instant.");
    }
  }

})();
</script>
<script>
// ── MATRIX CUBE EFFECT ────────────────────────────────────────────────────────
(function() {
  // Characters pool: katakana + latin + digits + symbols
  const CHARS = 'アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホマミムメモヤユヨラリルレロワヲン0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ<>{}[]|/\\+=~%$#@!?;:.,-_^*';

  function initCanvas(canvas) {
    const color   = canvas.dataset.color || '#00ff87';
    const SIZE    = 200;
    const FONT_SZ = 11;
    const COLS    = Math.floor(SIZE / FONT_SZ);
    const ROWS    = Math.floor(SIZE / FONT_SZ);

    canvas.width  = SIZE;
    canvas.height = SIZE;

    const ctx = canvas.getContext('2d');

    // Each column has an independent "head" position and speed
    const heads  = Array.from({ length: COLS }, () => Math.floor(Math.random() * ROWS));
    const speeds = Array.from({ length: COLS }, () => 0.3 + Math.random() * 0.7);
    const offsets= Array.from({ length: COLS }, () => Math.random() * ROWS);

    // Grid of characters — each cell refreshes independently
    const grid = Array.from({ length: COLS }, () =>
      Array.from({ length: ROWS }, () => randomChar())
    );

    // Random char mutation timers per cell
    const mutateTimers = Array.from({ length: COLS }, () =>
      Array.from({ length: ROWS }, () => Math.random() * 60)
    );

    function randomChar() {
      return CHARS[Math.floor(Math.random() * CHARS.length)];
    }

    let frame = 0;

    function draw() {
      // Dim the canvas slightly each frame (trail effect)
      ctx.fillStyle = 'rgba(3, 6, 3, 0.18)';
      ctx.fillRect(0, 0, SIZE, SIZE);

      ctx.font = `bold ${FONT_SZ}px monospace`;

      for (let col = 0; col < COLS; col++) {
        const headY = (offsets[col] + frame * speeds[col]) % ROWS;
        const headRow = Math.floor(headY);

        for (let row = 0; row < ROWS; row++) {
          // Mutate chars randomly
          mutateTimers[col][row] -= speeds[col];
          if (mutateTimers[col][row] <= 0) {
            grid[col][row] = randomChar();
            mutateTimers[col][row] = 4 + Math.random() * 20;
          }

          const dist = (row - headRow + ROWS) % ROWS;

          let alpha, bright;
          if (dist === 0) {
            // Head: bright white flash
            alpha  = 1;
            bright = true;
          } else if (dist <= 3) {
            // Trail: bright color fading
            alpha  = 1 - dist / 5;
            bright = false;
          } else if (dist <= 7) {
            // Longer dim tail
            alpha  = 0.12 - (dist - 3) * 0.02;
            bright = false;
          } else {
            continue; // invisible
          }

          if (alpha <= 0) continue;

          const x = col * FONT_SZ;
          const y = (row + 1) * FONT_SZ;

          if (bright) {
            ctx.fillStyle = `rgba(255,255,255,${alpha})`;
          } else {
            // Parse color to rgba
            ctx.fillStyle = hexToRgba(color, alpha);
          }

          ctx.fillText(grid[col][row], x, y);
        }
      }

      frame++;
      requestAnimationFrame(draw);
    }

    draw();
  }

  function hexToRgba(hex, alpha) {
    const r = parseInt(hex.slice(1,3), 16);
    const g = parseInt(hex.slice(3,5), 16);
    const b = parseInt(hex.slice(5,7), 16);
    return `rgba(${r},${g},${b},${alpha})`;
  }

  // Init all canvases once DOM is ready
  function initAll() {
    document.querySelectorAll('.matrix-canvas').forEach(initCanvas);
  }

  if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', initAll);
  } else {
    initAll();
  }
})();
</script>
<script>
// ── HERO BACKGROUND — CHAR REVEAL ON MOUSEMOVE ───────────────────────────────
(function() {
  const CHARS = 'アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホ0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ<>{}[]|/\\+=~%$#@!?;:.,_^*';
  const FONT_SZ  = 14;
  const COLOR    = '#00ff87';
  const RADIUS   = 130;      // illumination radius in px
  const FADE_SPD = 0.04;     // how fast glow fades away

  const canvas = document.getElementById('heroCanvas');
  const header = canvas.parentElement;
  const ctx    = canvas.getContext('2d');

  let W, H, COLS, ROWS;
  let grid   = [];   // { char, x, y, baseAlpha, alpha, target }
  let mouseX = -999, mouseY = -999;
  let mounted = false;

  function randomChar() {
    return CHARS[Math.floor(Math.random() * CHARS.length)];
  }

  function build() {
    W = header.offsetWidth;
    H = header.offsetHeight;
    canvas.width  = W;
    canvas.height = H;

    COLS = Math.floor(W / FONT_SZ);
    ROWS = Math.floor(H / FONT_SZ);

    grid = [];
    for (let r = 0; r < ROWS; r++) {
      for (let c = 0; c < COLS; c++) {
        grid.push({
          char:  randomChar(),
          x:     c * FONT_SZ,
          y:     (r + 1) * FONT_SZ,
          alpha: 0,
          target: 0,
          // chars mutate at their own rate
          mutateIn: Math.floor(Math.random() * 120),
        });
      }
    }
    mounted = true;
  }

  function loop() {
    if (!mounted) { requestAnimationFrame(loop); return; }

    ctx.clearRect(0, 0, W, H);
    ctx.font = `${FONT_SZ}px monospace`;

    const now = performance.now();

    for (let i = 0; i < grid.length; i++) {
      const cell = grid[i];

      // Mutate character randomly over time
      cell.mutateIn--;
      if (cell.mutateIn <= 0) {
        cell.char = randomChar();
        cell.mutateIn = 30 + Math.floor(Math.random() * 90);
      }

      // Compute distance from mouse
      const dx   = cell.x - mouseX;
      const dy   = cell.y - mouseY;
      const dist = Math.sqrt(dx * dx + dy * dy);

      // Target alpha: bright near cursor, invisible far away
      if (dist < RADIUS) {
        const t = 1 - dist / RADIUS;
        cell.target = 0.08 + t * t * 0.85; // ease-in curve
      } else {
        cell.target = 0;
      }

      // Smooth interpolation
      if (cell.alpha < cell.target) {
        cell.alpha = Math.min(cell.target, cell.alpha + FADE_SPD * 3);
      } else {
        cell.alpha = Math.max(cell.target, cell.alpha - FADE_SPD);
      }

      if (cell.alpha < 0.01) continue;

      // Closest cells get white flash, others get accent color
      const isHot = dist < RADIUS * 0.25;
      if (isHot) {
        ctx.fillStyle = `rgba(220,255,230,${cell.alpha})`;
      } else {
        ctx.fillStyle = `rgba(0,255,135,${cell.alpha})`;
      }

      ctx.fillText(cell.char, cell.x, cell.y);
    }

    requestAnimationFrame(loop);
  }

  // Track mouse relative to header
  header.addEventListener('mousemove', e => {
    const rect = header.getBoundingClientRect();
    mouseX = e.clientX - rect.left;
    mouseY = e.clientY - rect.top;
  });

  header.addEventListener('mouseleave', () => {
    mouseX = -999;
    mouseY = -999;
  });

  // Resize
  window.addEventListener('resize', () => { build(); });

  // Init
  build();
  loop();
})();
</script>
</body>
</html>

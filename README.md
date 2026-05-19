# Acorn-City-Kids
[index (2).html](https://github.com/user-attachments/files/27985143/index.2.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Acorn City Kids — Free & Affordable Family Fun in Raleigh NC</title>
<meta name="description" content="Acorn City Kids: Free and affordable family activities in Raleigh, Cary, Wake Forest and the greater Raleigh NC area — including special needs and inclusive programs. Be Kind.">
<meta name="keywords" content="free things to do Raleigh NC kids, affordable family activities Raleigh, special needs inclusive programs Raleigh, Cary family fun, Wake Forest kids activities, Acorn City Kids">
<meta property="og:title" content="Acorn City Kids — Free & Affordable Family Fun in Raleigh NC">
<meta property="og:description" content="Free and affordable family activities in Raleigh NC including special needs and inclusive programs.">
<meta property="og:type" content="website">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700&family=Nunito+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">
<style>
:root {
  --acorn:        #C4621D;
  --acorn-dark:   #9B4A10;
  --acorn-light:  #FDF0E6;
  --acorn-mid:    #E8873F;
  --forest:       #2D6A4F;
  --forest-light: #E5F4ED;
  --sky:          #1A6FA8;
  --sky-light:    #E3F1FB;
  --purple:       #5E44B3;
  --purple-light: #EDEAFC;
  --purple-dark:  #3D2D8C;
  --amber:        #B06F10;
  --amber-light:  #FDF3DC;
  --text:         #1C1410;
  --text-muted:   #6B5C52;
  --text-hint:    #A8998F;
  --bg:           #FBF7F3;
  --bg-card:      #FFFFFF;
  --border:       rgba(100,60,20,0.12);
  --border-hover: rgba(100,60,20,0.25);
  --radius:       14px;
  --radius-sm:    9px;
  --shadow:       0 2px 14px rgba(100,60,20,0.07);
  --shadow-hover: 0 5px 22px rgba(100,60,20,0.13);
  --nav-h:        56px;
}
* { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; }
body { font-family: 'Nunito Sans', sans-serif; background: var(--bg); color: var(--text); min-height: 100vh; line-height: 1.6; }

/* ═══════════════ NAV ═══════════════ */
nav {
  position: sticky; top: 0; z-index: 100;
  background: #fff;
  border-bottom: 1px solid var(--border);
  box-shadow: 0 1px 8px rgba(100,60,20,0.07);
  height: var(--nav-h);
  display: flex; align-items: center;
}
.nav-inner {
  max-width: 1120px; margin: 0 auto; padding: 0 1rem;
  width: 100%;
  display: flex; align-items: center; justify-content: space-between; gap: 12px;
}
.nav-brand {
  font-family: 'Fredoka One', cursive;
  font-size: 20px; font-weight: 400;
  color: var(--acorn); text-decoration: none;
  display: flex; align-items: center; gap: 7px;
  white-space: nowrap;
}
.nav-brand span { color: var(--acorn-dark); }
.nav-links {
  display: flex; align-items: center; gap: 4px;
  list-style: none;
}
.nav-links a {
  text-decoration: none;
  font-size: 13px; font-weight: 600;
  color: var(--text-muted);
  padding: 6px 12px;
  border-radius: 999px;
  transition: all .15s;
  white-space: nowrap;
}
.nav-links a:hover { background: var(--acorn-light); color: var(--acorn); }
.nav-links a.active { background: var(--acorn); color: #fff; }
.nav-newsletter {
  background: var(--acorn); color: #fff !important;
  padding: 7px 16px !important;
  border-radius: 999px;
  font-weight: 700 !important;
}
.nav-newsletter:hover { background: var(--acorn-dark) !important; color: #fff !important; }
.nav-hamburger {
  display: none;
  background: none; border: none; cursor: pointer;
  font-size: 24px; color: var(--text);
  padding: 4px;
}
.mobile-menu {
  display: none;
  position: fixed; top: var(--nav-h); left: 0; right: 0;
  background: #fff;
  border-bottom: 1px solid var(--border);
  padding: 1rem;
  z-index: 99;
  flex-direction: column; gap: 4px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
}
.mobile-menu a {
  text-decoration: none;
  font-size: 15px; font-weight: 600;
  color: var(--text-muted);
  padding: 10px 16px;
  border-radius: var(--radius-sm);
  display: block;
}
.mobile-menu a:hover { background: var(--acorn-light); color: var(--acorn); }
.mobile-menu .mob-nl { background: var(--acorn); color: #fff; text-align: center; margin-top: 4px; }
@media (max-width: 680px) {
  .nav-links { display: none; }
  .nav-hamburger { display: block; }
}

/* ═══════════════ HEADER ═══════════════ */
header {
  background: linear-gradient(135deg, #7B3A0E 0%, #C4621D 55%, #E8873F 100%);
  color: #fff;
  padding: 2.75rem 1rem 2.25rem;
  text-align: center;
  position: relative; overflow: hidden;
}
header::before { content:''; position:absolute; top:-80px; right:-80px; width:280px; height:280px; background:rgba(255,255,255,0.06); border-radius:50%; }
header::after  { content:''; position:absolute; bottom:-50px; left:-50px; width:200px; height:200px; background:rgba(0,0,0,0.08); border-radius:50%; }
.logo-wrap { position:relative; display:inline-flex; align-items:center; gap:12px; margin-bottom:10px; justify-content:center; }
.logo-acorn { font-size:44px; line-height:1; filter:drop-shadow(0 2px 4px rgba(0,0,0,0.2)); }
header h1 { font-family:'Fredoka One',cursive; font-size:clamp(28px,6vw,44px); font-weight:400; letter-spacing:.5px; position:relative; line-height:1.1; text-shadow:0 2px 8px rgba(0,0,0,0.15); }
header h1 span { color:#FFE0B2; }
.tagline { font-size:15px; opacity:0.9; max-width:500px; margin:6px auto 0; position:relative; font-weight:500; }
.header-badges { display:flex; flex-wrap:wrap; gap:8px; justify-content:center; margin-top:16px; position:relative; }
.header-badge { background:rgba(255,255,255,0.18); border:1px solid rgba(255,255,255,0.3); border-radius:999px; padding:4px 13px; font-size:12px; font-weight:600; }
.header-stats { display:flex; gap:18px; justify-content:center; margin-top:18px; position:relative; flex-wrap:wrap; }
.stat-chip { background:rgba(255,255,255,0.15); border:1px solid rgba(255,255,255,0.25); border-radius:10px; padding:8px 16px; text-align:center; }
.stat-chip .num { font-family:'Fredoka One',cursive; font-size:22px; font-weight:400; line-height:1; }
.stat-chip .lbl { font-size:10px; opacity:.8; text-transform:uppercase; letter-spacing:.06em; }

/* ═══════════════ MAIN ═══════════════ */
main { max-width:1120px; margin:0 auto; padding:1.5rem 1rem 3rem; }

/* ═══════════════ WELCOME ═══════════════ */
.welcome-banner { background:var(--bg-card); border:1px solid var(--border); border-radius:var(--radius); padding:1.75rem 1.75rem 1.5rem; margin-bottom:1rem; box-shadow:var(--shadow); text-align:center; }
.welcome-banner .wave { font-size:36px; display:block; margin-bottom:10px; }
.welcome-banner h2 { font-family:'Fredoka One',cursive; font-size:clamp(18px,4vw,26px); font-weight:400; color:var(--acorn); margin-bottom:10px; }
.welcome-banner p { font-size:14.5px; color:var(--text-muted); max-width:640px; margin:0 auto; line-height:1.7; }
.welcome-banner p+p { margin-top:8px; }
.kind-tag { display:inline-flex; align-items:center; gap:6px; background:var(--acorn-light); color:var(--acorn-dark); border-radius:999px; padding:5px 16px; font-size:13px; font-weight:700; margin-top:14px; letter-spacing:.02em; }

/* ═══════════════ INFO GRID ═══════════════ */
.info-grid { display:grid; grid-template-columns:1fr 1fr; gap:14px; margin-bottom:1rem; }
@media(max-width:680px){.info-grid{grid-template-columns:1fr;}}
.info-card { background:var(--bg-card); border:1px solid var(--border); border-radius:var(--radius); padding:1.5rem; box-shadow:var(--shadow); position:relative; overflow:hidden; }
.info-card::before { content:''; position:absolute; top:0; left:0; right:0; height:4px; border-radius:var(--radius) var(--radius) 0 0; }
.info-card.mission::before { background:linear-gradient(90deg,var(--acorn),var(--acorn-mid)); }
.info-card.about::before   { background:linear-gradient(90deg,var(--forest),#52b788); }
.info-card-icon { font-size:30px; margin-bottom:10px; display:block; }
.info-card h3 { font-family:'Fredoka One',cursive; font-size:18px; font-weight:400; margin-bottom:10px; }
.info-card.mission h3 { color:var(--acorn); }
.info-card.about   h3 { color:var(--forest); }
.info-card p { font-size:13.5px; color:var(--text-muted); line-height:1.7; margin-bottom:10px; }
.info-card p:last-of-type { margin-bottom:0; }
.values-list { list-style:none; margin-top:12px; display:flex; flex-direction:column; gap:7px; }
.values-list li { font-size:13px; color:var(--text-muted); display:flex; align-items:flex-start; gap:8px; line-height:1.5; }
.values-list li span.vi { font-size:16px; flex-shrink:0; margin-top:1px; }

/* ═══════════════ KIND BANNER ═══════════════ */
.kind-banner { background:linear-gradient(135deg,#FFF7F0,#FDF0E6); border:1.5px solid rgba(196,98,29,0.2); border-radius:var(--radius); padding:1.25rem 1.5rem; margin-bottom:1rem; display:flex; align-items:center; gap:14px; box-shadow:var(--shadow); }
.kind-banner-icon { font-size:32px; flex-shrink:0; }
.kind-banner-text h3 { font-family:'Fredoka One',cursive; font-size:17px; font-weight:400; color:var(--acorn); margin-bottom:4px; }
.kind-banner-text p { font-size:13px; color:var(--text-muted); line-height:1.6; }
@media(max-width:500px){.kind-banner{flex-direction:column;text-align:center;}}

/* ═══════════════ SEARCH ═══════════════ */
.search-wrap { position:relative; margin-bottom:1rem; }
.search-wrap i { position:absolute; left:14px; top:50%; transform:translateY(-50%); font-size:20px; color:var(--text-hint); pointer-events:none; }
.search-wrap input { width:100%; padding:13px 16px 13px 46px; font-size:15px; font-family:'Nunito Sans',sans-serif; border:1.5px solid var(--border); border-radius:var(--radius); background:var(--bg-card); color:var(--text); outline:none; box-shadow:var(--shadow); transition:border-color .2s,box-shadow .2s; }
.search-wrap input:focus { border-color:var(--acorn); box-shadow:0 0 0 3px rgba(196,98,29,0.13); }
.search-wrap input::placeholder { color:var(--text-hint); }

/* ═══════════════ FILTERS ═══════════════ */
.filter-section { background:var(--bg-card); border:1px solid var(--border); border-radius:var(--radius); padding:1rem 1.25rem; margin-bottom:1rem; box-shadow:var(--shadow); }
.filter-label { font-size:11px; font-weight:700; text-transform:uppercase; letter-spacing:.08em; color:var(--text-hint); margin-bottom:10px; }
.pills { display:flex; flex-wrap:wrap; gap:8px; }
.pill { padding:7px 16px; border-radius:999px; font-size:13px; font-family:'Nunito Sans',sans-serif; font-weight:600; border:1.5px solid var(--border); background:transparent; color:var(--text-muted); cursor:pointer; transition:all .15s; display:flex; align-items:center; gap:6px; }
.pill:hover { border-color:var(--border-hover); color:var(--text); background:var(--acorn-light); }
.pill.active-cat  { background:var(--acorn);  border-color:var(--acorn);  color:#fff; }
.pill.active-sn   { background:var(--purple); border-color:var(--purple); color:#fff; }
.pill.active-cost { background:var(--forest); border-color:var(--forest); color:#fff; }
.pill.active-age  { background:var(--sky);    border-color:var(--sky);    color:#fff; }

/* ═══════════════ SN BANNER ═══════════════ */
.sn-banner { background:var(--purple-light); border:1px solid #B8AFEC; border-radius:var(--radius-sm); padding:12px 16px; margin-bottom:1rem; font-size:13px; color:var(--purple-dark); display:none; align-items:flex-start; gap:10px; line-height:1.55; }
.sn-banner i { font-size:20px; flex-shrink:0; margin-top:1px; }

/* ═══════════════ RESULTS BAR ═══════════════ */
.results-bar { font-size:13px; color:var(--text-muted); margin-bottom:1rem; display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; gap:8px; }
.clear-btn { font-size:12px; font-weight:700; color:var(--acorn); background:var(--acorn-light); border:none; border-radius:999px; padding:4px 12px; cursor:pointer; transition:background .15s; }
.clear-btn:hover { background:#f5d9c0; }

/* ═══════════════ CARDS ═══════════════ */
.cards { display:grid; grid-template-columns:repeat(auto-fill,minmax(295px,1fr)); gap:14px; }
.card { background:var(--bg-card); border:1px solid var(--border); border-radius:var(--radius); padding:1.1rem 1.25rem; display:flex; flex-direction:column; gap:9px; box-shadow:var(--shadow); transition:box-shadow .2s,transform .2s,border-color .2s; }
.card:hover { box-shadow:var(--shadow-hover); transform:translateY(-2px); border-color:rgba(196,98,29,0.25); }
.card-top { display:flex; justify-content:space-between; align-items:flex-start; gap:10px; }
.card-title { font-family:'Nunito',sans-serif; font-size:15px; font-weight:700; line-height:1.3; color:var(--text); }
.card-icon { font-size:24px; color:var(--acorn); flex-shrink:0; opacity:.85; }
.card-loc { font-size:12px; color:var(--text-hint); display:flex; align-items:center; gap:4px; }
.card-loc i { font-size:13px; }
.card-ages { font-size:11px; color:var(--sky); font-weight:700; background:var(--sky-light); border-radius:999px; padding:2px 8px; display:inline-block; }
.card-desc { font-size:13px; color:var(--text-muted); line-height:1.55; flex:1; }
.card-meta { display:flex; flex-wrap:wrap; gap:6px; margin-top:2px; }
.badge { font-size:11px; font-weight:700; padding:3px 10px; border-radius:999px; display:inline-flex; align-items:center; gap:4px; }
.b-free    { background:#E5F4ED; color:#1E5C3A; }
.b-low     { background:var(--amber-light); color:var(--amber); }
.b-sn      { background:var(--purple-light); color:var(--purple-dark); }
.b-outdoor { background:var(--forest-light); color:var(--forest); }
.b-indoor  { background:var(--sky-light); color:var(--sky); }
.b-edu     { background:var(--acorn-light); color:var(--acorn-dark); }
.b-default { background:#F3EDE7; color:#7A5C48; }
.card-actions { display:flex; gap:8px; margin-top:4px; flex-wrap:wrap; }
.card-link { font-size:12px; font-weight:700; color:var(--acorn); text-decoration:none; display:inline-flex; align-items:center; gap:5px; transition:color .15s; }
.card-link:hover { color:var(--acorn-dark); text-decoration:underline; }
.card-map  { font-size:12px; font-weight:700; color:var(--forest); text-decoration:none; display:inline-flex; align-items:center; gap:5px; transition:color .15s; }
.card-map:hover { color:#1a4a33; text-decoration:underline; }

/* ═══════════════ EMPTY ═══════════════ */
.empty { grid-column:1/-1; text-align:center; padding:4rem 1rem; color:var(--text-muted); }
.empty i { font-size:48px; margin-bottom:12px; display:block; opacity:.35; }
.empty p { font-size:15px; }

/* ═══════════════ NEWSLETTER SECTION ═══════════════ */
.newsletter { background:linear-gradient(135deg,#7B3A0E 0%,#C4621D 60%,#E8873F 100%); border-radius:var(--radius); padding:2.25rem 2rem; margin:2rem 0 0; text-align:center; color:#fff; position:relative; overflow:hidden; }
.newsletter::before { content:''; position:absolute; top:-50px; right:-50px; width:180px; height:180px; background:rgba(255,255,255,0.07); border-radius:50%; pointer-events:none; }
.newsletter::after  { content:''; position:absolute; bottom:-40px; left:-40px; width:140px; height:140px; background:rgba(0,0,0,0.07); border-radius:50%; pointer-events:none; }
.newsletter-inner { position:relative; max-width:520px; margin:0 auto; }
.newsletter-icon { font-size:36px; margin-bottom:10px; display:block; }
.newsletter h2 { font-family:'Fredoka One',cursive; font-size:clamp(20px,4vw,28px); font-weight:400; margin-bottom:8px; letter-spacing:.3px; }
.newsletter p { font-size:14px; opacity:.88; margin-bottom:1.25rem; line-height:1.55; }
.nl-form { display:flex; gap:8px; flex-wrap:wrap; justify-content:center; }
.nl-input { flex:1; min-width:220px; max-width:320px; padding:12px 16px; font-size:14px; font-family:'Nunito Sans',sans-serif; border:2px solid rgba(255,255,255,0.4); border-radius:999px; background:rgba(255,255,255,0.15); color:#fff; outline:none; transition:border-color .2s,background .2s; }
.nl-input::placeholder { color:rgba(255,255,255,0.65); }
.nl-input:focus { border-color:#fff; background:rgba(255,255,255,0.22); }
.nl-btn { padding:12px 26px; border-radius:999px; background:#fff; color:var(--acorn-dark); font-size:14px; font-family:'Nunito Sans',sans-serif; font-weight:700; border:none; cursor:pointer; transition:transform .15s,box-shadow .15s; white-space:nowrap; display:inline-flex; align-items:center; gap:7px; box-shadow:0 3px 12px rgba(0,0,0,0.2); }
.nl-btn:hover { transform:translateY(-1px); box-shadow:0 5px 18px rgba(0,0,0,0.25); }
.nl-success { display:none; background:rgba(255,255,255,0.18); border:1.5px solid rgba(255,255,255,0.4); border-radius:var(--radius-sm); padding:12px 20px; font-size:14px; font-weight:600; margin-top:12px; align-items:center; justify-content:center; gap:8px; }
.nl-note { font-size:11px; opacity:.65; margin-top:10px; }

/* ═══════════════ NEWSLETTER LINK BANNER ═══════════════ */
.nl-link-banner { background:var(--acorn-light); border:1.5px solid rgba(196,98,29,0.25); border-radius:var(--radius); padding:1rem 1.25rem; margin-bottom:1rem; display:flex; align-items:center; justify-content:space-between; gap:12px; flex-wrap:wrap; box-shadow:var(--shadow); }
.nl-link-banner p { font-size:13px; color:var(--acorn-dark); font-weight:600; display:flex; align-items:center; gap:8px; }
.nl-link-banner a { font-size:13px; font-weight:700; color:var(--acorn-dark); background:#fff; border:1.5px solid var(--acorn); border-radius:999px; padding:6px 16px; text-decoration:none; white-space:nowrap; transition:background .15s; }
.nl-link-banner a:hover { background:var(--acorn); color:#fff; }

/* ═══════════════ CONTACT SECTION ═══════════════ */
.contact-section { background:var(--bg-card); border:1px solid var(--border); border-radius:var(--radius); padding:1.75rem; margin-top:2rem; box-shadow:var(--shadow); }
.contact-section h2 { font-family:'Fredoka One',cursive; font-size:22px; font-weight:400; color:var(--acorn); margin-bottom:6px; }
.contact-section p { font-size:13.5px; color:var(--text-muted); line-height:1.65; margin-bottom:1rem; }
.contact-grid { display:grid; grid-template-columns:1fr 1fr; gap:12px; }
@media(max-width:600px){.contact-grid{grid-template-columns:1fr;}}
.contact-item { background:var(--bg); border:1px solid var(--border); border-radius:var(--radius-sm); padding:14px 16px; display:flex; align-items:center; gap:12px; }
.contact-item i { font-size:22px; color:var(--acorn); }
.contact-item .ci-label { font-size:11px; font-weight:700; text-transform:uppercase; letter-spacing:.06em; color:var(--text-hint); }
.contact-item .ci-val { font-size:14px; font-weight:600; color:var(--text); }
.contact-item a { color:var(--acorn); text-decoration:none; }
.contact-item a:hover { text-decoration:underline; }

/* ═══════════════ SOCIAL STRIP ═══════════════ */
.social-strip { display:flex; gap:10px; flex-wrap:wrap; margin-top:1.25rem; }
.social-btn { display:inline-flex; align-items:center; gap:8px; padding:8px 16px; border-radius:999px; font-size:13px; font-weight:700; text-decoration:none; transition:opacity .15s,transform .15s; }
.social-btn:hover { opacity:.88; transform:translateY(-1px); }
.sb-instagram { background:#E1306C; color:#fff; }
.sb-facebook  { background:#1877F2; color:#fff; }
.sb-email     { background:var(--acorn); color:#fff; }
.sb-newsletter{ background:var(--forest); color:#fff; }

/* ═══════════════ FOOTER ═══════════════ */
footer { background:#3C1F0A; color:rgba(255,255,255,0.7); text-align:center; padding:2.5rem 1rem; margin-top:3rem; }
.footer-brand { font-family:'Fredoka One',cursive; font-size:24px; font-weight:400; color:#FFD599; margin-bottom:8px; }
footer p { font-size:12px; line-height:1.8; }
footer a { color:#FFB870; text-decoration:none; }
footer a:hover { text-decoration:underline; }
.footer-links { display:flex; gap:16px; justify-content:center; flex-wrap:wrap; margin:12px 0; }
.footer-links a { font-size:12px; font-weight:600; }
.footer-kind { font-size:13px; color:rgba(255,255,255,0.5); margin-top:14px; }
.footer-copy { font-size:11px; opacity:.4; margin-top:8px; }

/* ═══════════════ BACK TO TOP ═══════════════ */
#backToTop { position:fixed; bottom:24px; right:20px; background:var(--acorn); color:#fff; border:none; border-radius:50%; width:44px; height:44px; font-size:20px; cursor:pointer; display:none; align-items:center; justify-content:center; box-shadow:0 4px 14px rgba(196,98,29,0.4); transition:opacity .2s,transform .2s; z-index:99; }
#backToTop:hover { transform:translateY(-2px); }
#backToTop.visible { display:flex; }

/* ═══════════════ RESPONSIVE ═══════════════ */
@media(max-width:600px){
  .cards { grid-template-columns:1fr; }
  header { padding:2rem 1rem 1.75rem; }
  .newsletter { padding:1.75rem 1.25rem; }
}
</style>
</head>
<body>

<!-- ═══ STICKY NAV ═══ -->
<nav>
  <div class="nav-inner">
    <a href="#top" class="nav-brand">🌰 Acorn City <span>Kids</span></a>
    <ul class="nav-links">
      <li><a href="#activities">Activities</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#special-needs">Special Needs</a></li>
      <li><a href="#newsletter-section">Newsletter</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="newsletter-june-2026.html" class="nav-newsletter" target="_blank">📰 June Newsletter</a></li>
    </ul>
    <button class="nav-hamburger" onclick="toggleMenu()" aria-label="Menu">☰</button>
  </div>
</nav>
<div class="mobile-menu" id="mobileMenu">
  <a href="#activities" onclick="closeMenu()">🗺️ Activities</a>
  <a href="#about" onclick="closeMenu()">🌰 About Us</a>
  <a href="#special-needs" onclick="closeMenu()">♿ Special Needs</a>
  <a href="#newsletter-section" onclick="closeMenu()">📬 Newsletter</a>
  <a href="#contact" onclick="closeMenu()">✉️ Contact</a>
  <a href="newsletter-june-2026.html" target="_blank" class="mob-nl">📰 Read June Newsletter</a>
</div>

<!-- ═══ HEADER ═══ -->
<div id="top">
<header>
  <div class="logo-wrap">
    <span class="logo-acorn" aria-hidden="true">🌰</span>
    <h1>Acorn City <span>Kids</span></h1>
  </div>
  <p class="tagline">Free &amp; affordable family fun in the Raleigh NC area — including special needs &amp; inclusive programs</p>
  <div class="header-badges">
    <span class="header-badge">📍 Raleigh</span>
    <span class="header-badge">📍 Cary</span>
    <span class="header-badge">📍 Wake Forest</span>
    <span class="header-badge">📍 Holly Springs</span>
    <span class="header-badge">📍 Morrisville</span>
    <span class="header-badge">📍 Apex &amp; More</span>
  </div>
  <div class="header-stats">
    <div class="stat-chip"><div class="num">40+</div><div class="lbl">Activities</div></div>
    <div class="stat-chip"><div class="num">🆓</div><div class="lbl">Many Free</div></div>
    <div class="stat-chip"><div class="num">♿</div><div class="lbl">Inclusive</div></div>
    <div class="stat-chip"><div class="num">💛</div><div class="lbl">Be Kind</div></div>
  </div>
</header>
</div>

<main>

  <!-- ═══ WELCOME ═══ -->
  <div class="welcome-banner" id="about">
    <span class="wave" aria-hidden="true">👋🌿</span>
    <h2>Welcome to Acorn City Kids!</h2>
    <p>Hey Raleigh families — we're so glad you're here! Whether you're looking for a free afternoon at the park, a sensory-friendly museum morning, or an inclusive program where every child belongs, you've found your spot. Acorn City Kids was built by a local family, for local families — rooted right here in the greater Raleigh area and grown with love.</p>
    <p>We believe the best adventures don't cost much. We believe every child deserves joy, nature, animals, and community — regardless of budget or ability.</p>
    <div class="kind-tag"><i class="ti ti-heart" aria-hidden="true"></i> Where kindness leads the way</div>
  </div>

  <!-- ═══ MISSION + ABOUT ═══ -->
  <div class="info-grid">
    <div class="info-card mission">
      <span class="info-card-icon" aria-hidden="true">🎯</span>
      <h3>Our Mission</h3>
      <p>Every family deserves access to joyful, enriching experiences — no matter their budget, ability, or background. We make it easy for Raleigh-area families to find free and affordable activities where <em>every child is welcome, seen, and celebrated.</em></p>
      <p>We especially champion families raising children with special needs, because inclusion isn't an afterthought here — it's at the heart of everything we do.</p>
      <ul class="values-list">
        <li><span class="vi">🌳</span><span>Connect families to nature, parks &amp; the outdoors</span></li>
        <li><span class="vi">🐾</span><span>Foster a love of animals and the living world</span></li>
        <li><span class="vi">♿</span><span>Highlight inclusive &amp; special needs programs</span></li>
        <li><span class="vi">💚</span><span>Keep it free or affordable for every family</span></li>
        <li><span class="vi">💛</span><span>Lead with kindness in everything we do</span></li>
      </ul>
    </div>
    <div class="info-card about">
      <span class="info-card-icon" aria-hidden="true">🌰</span>
      <h3>About Us</h3>
      <p>Acorn City Kids started from a simple idea: families shouldn't have to scroll through dozens of websites to find something wonderful to do this weekend. We're a Raleigh-area family who loves exploring trails, discovering hidden parks, watching our kids light up around animals, and finding the little moments that turn into big memories.</p>
      <p>We believe the best adventures don't cost a lot. A walk through Umstead, a free storytime at the library, or a sunny afternoon at Pullen Park can be just as magical as any ticketed attraction.</p>
      <p>Most of all, we believe in showing up for each other — especially for families who sometimes feel left out. <strong>You belong here.</strong></p>
    </div>
  </div>

  <!-- ═══ BE KIND BANNER ═══ -->
  <div class="kind-banner">
    <div class="kind-banner-icon" aria-hidden="true">🤝</div>
    <div class="kind-banner-text">
      <h3>The Acorn City Kids Promise: Be Kind, Always</h3>
      <p>Kindness is our niche. Every person deserves to feel respected and welcomed. Lead with patience, extend grace to other families, and treat every child with the gentleness you'd want for your own. <strong>Be kind to people. Be kind to animals. Be kind to nature. Be kind to yourself.</strong> That's the Acorn City Kids way. 🌰💛</p>
    </div>
  </div>

  <!-- ═══ NEWSLETTER LINK BANNER ═══ -->
  <div class="nl-link-banner">
    <p>📰 <strong>June 2026 Newsletter is here!</strong> Free concerts, workshops, Juneteenth events, nature activities &amp; more.</p>
    <a href="newsletter-june-2026.html" target="_blank">Read Now →</a>
  </div>

  <!-- ═══ SEARCH ═══ -->
  <div class="search-wrap" id="activities">
    <i class="ti ti-search"></i>
    <input type="text" id="searchInput" placeholder="Search activities, parks, programs, locations..." oninput="render()" aria-label="Search activities">
  </div>

  <!-- ═══ CATEGORY FILTER ═══ -->
  <div class="filter-section">
    <div class="filter-label">Category</div>
    <div class="pills" id="catPills">
      <button class="pill active-cat" data-cat="all" onclick="setFilter(this,'cat')">All</button>
      <button class="pill" data-cat="parks"   onclick="setFilter(this,'cat')"><i class="ti ti-trees"></i> Parks &amp; Trails</button>
      <button class="pill" data-cat="museums" onclick="setFilter(this,'cat')"><i class="ti ti-building"></i> Museums</button>
      <button class="pill" data-cat="library" onclick="setFilter(this,'cat')"><i class="ti ti-books"></i> Library</button>
      <button class="pill" data-cat="rec"     onclick="setFilter(this,'cat')"><i class="ti ti-run"></i> Recreation</button>
      <button class="pill" data-cat="arts"    onclick="setFilter(this,'cat')"><i class="ti ti-palette"></i> Arts</button>
      <button class="pill" data-cat="animals" onclick="setFilter(this,'cat')"><i class="ti ti-paw"></i> Animals</button>
      <button class="pill" id="snCatBtn" data-cat="sn" onclick="setFilter(this,'cat')"><i class="ti ti-accessibility"></i> Special Needs &amp; Inclusive</button>
    </div>
  </div>

  <!-- ═══ COST + AGE FILTERS ═══ -->
  <div class="filter-section">
    <div style="display:flex;gap:2rem;flex-wrap:wrap;">
      <div style="flex:1;min-width:200px;">
        <div class="filter-label">Cost</div>
        <div class="pills" id="costPills">
          <button class="pill active-cost" data-cost="all" onclick="setFilter(this,'cost')">All</button>
          <button class="pill" data-cost="free" onclick="setFilter(this,'cost')">🆓 Free</button>
          <button class="pill" data-cost="low"  onclick="setFilter(this,'cost')">💚 Affordable ($1–$10)</button>
        </div>
      </div>
      <div style="flex:1;min-width:200px;">
        <div class="filter-label">Best Age Group</div>
        <div class="pills" id="agePills">
          <button class="pill active-age" data-age="all" onclick="setFilter(this,'age')">All Ages</button>
          <button class="pill" data-age="baby"  onclick="setFilter(this,'age')">👶 Baby–2</button>
          <button class="pill" data-age="toddler" onclick="setFilter(this,'age')">🧒 3–5</button>
          <button class="pill" data-age="kids"  onclick="setFilter(this,'age')">🧒 6–12</button>
          <button class="pill" data-age="teen"  onclick="setFilter(this,'age')">🧑 Teens</button>
        </div>
      </div>
    </div>
  </div>

  <!-- ═══ SN BANNER ═══ -->
  <div class="sn-banner" id="snBanner">
    <i class="ti ti-heart"></i>
    <div id="special-needs"><strong>Special needs &amp; inclusive resources.</strong> Many programs offer free or reduced-cost participation and are designed for individuals with developmental, physical, and sensory differences. Always call ahead to confirm current schedules and accommodations. Raleigh Parks Inclusion Services: 919-996-2147.</div>
  </div>

  <!-- ═══ RESULTS BAR ═══ -->
  <div class="results-bar">
    <span id="resCount"></span>
    <button class="clear-btn" onclick="clearFilters()" id="clearBtn" style="display:none">✕ Clear filters</button>
    <span style="font-size:12px;color:#bba898">Last updated June 2026 · Always verify hours before visiting</span>
  </div>

  <!-- ═══ CARD GRID ═══ -->
  <div class="cards" id="cardGrid"></div>

  <!-- ═══ NEWSLETTER SIGNUP ═══ -->
  <section class="newsletter" id="newsletter-section" aria-label="Newsletter signup">
    <div class="newsletter-inner">
      <span class="newsletter-icon" aria-hidden="true">🌰</span>
      <h2>Get the Acorn City Kids Newsletter</h2>
      <p>New free activities, upcoming events, inclusive programs, and local deals — delivered straight to your inbox. No spam, just good stuff for Raleigh families.</p>
      <div class="nl-form" id="nlForm">
        <input class="nl-input" type="email" id="nlEmail" placeholder="Your email address" aria-label="Email address" autocomplete="email">
        <button class="nl-btn" onclick="subscribeNewsletter()"><i class="ti ti-send"></i> Subscribe Free</button>
      </div>
      <div class="nl-success" id="nlSuccess">
        <i class="ti ti-circle-check" style="font-size:18px"></i> You're in! Welcome to the Acorn City Kids family. 🎉
      </div>
      <p class="nl-note">Join Raleigh-area families getting the best local tips. Unsubscribe anytime.</p>
    </div>
  </section>

  <!-- ═══ CONTACT ═══ -->
  <div class="contact-section" id="contact">
    <h2>📬 Get In Touch</h2>
    <p>Know of a great free or affordable activity we're missing? Want to suggest an inclusive program, partner with us, or advertise to Raleigh families? We'd love to hear from you — every message is read by a real local family.</p>
    <div class="contact-grid">
      <div class="contact-item"><i class="ti ti-mail"></i><div><div class="ci-label">Email</div><div class="ci-val"><a href="mailto:acorncitykids@gmail.com">acorncitykids@gmail.com</a></div></div></div>
      <div class="contact-item"><i class="ti ti-brand-instagram"></i><div><div class="ci-label">Instagram</div><div class="ci-val"><a href="https://instagram.com/acorncitykids" target="_blank">@AcornCityKids</a></div></div></div>
      <div class="contact-item"><i class="ti ti-brand-facebook"></i><div><div class="ci-label">Facebook</div><div class="ci-val"><a href="https://facebook.com/acorncitykids" target="_blank">Acorn City Kids</a></div></div></div>
      <div class="contact-item"><i class="ti ti-map-pin"></i><div><div class="ci-label">Serving</div><div class="ci-val">Greater Raleigh, NC Area</div></div></div>
    </div>
    <div class="social-strip">
      <a href="https://instagram.com/acorncitykids" target="_blank" class="social-btn sb-instagram"><i class="ti ti-brand-instagram"></i> Instagram</a>
      <a href="https://facebook.com/acorncitykids" target="_blank" class="social-btn sb-facebook"><i class="ti ti-brand-facebook"></i> Facebook</a>
      <a href="mailto:acorncitykids@gmail.com" class="social-btn sb-email"><i class="ti ti-mail"></i> Email Us</a>
      <a href="newsletter-june-2026.html" target="_blank" class="social-btn sb-newsletter"><i class="ti ti-news"></i> June Newsletter</a>
    </div>
  </div>

</main>

<!-- ═══ FOOTER ═══ -->
<footer>
  <div class="footer-brand">🌰 Acorn City Kids</div>
  <p>Your guide to free &amp; affordable family fun in the greater Raleigh, NC area</p>
  <div class="footer-links">
    <a href="#activities">Activities</a>
    <a href="#about">About</a>
    <a href="#special-needs">Special Needs</a>
    <a href="newsletter-june-2026.html" target="_blank">Newsletter</a>
    <a href="#contact">Contact</a>
    <a href="https://www.wake.gov/parks" target="_blank">Wake County Parks</a>
    <a href="https://library.wakegov.com" target="_blank">Wake Libraries</a>
    <a href="https://raleighnc.gov/sris" target="_blank">Inclusive Recreation</a>
  </div>
  <p class="footer-kind">🤝 Be Kind to People &nbsp;·&nbsp; 🐾 Be Kind to Animals &nbsp;·&nbsp; 🌿 Be Kind to Nature &nbsp;·&nbsp; 💛 Be Kind to Yourself</p>
  <p class="footer-copy">© 2026 Acorn City Kids · Serving Raleigh, Cary, Wake Forest, Holly Springs, Morrisville, Apex &amp; Beyond · Information is for general guidance — please verify before visiting.</p>
</footer>

<!-- BACK TO TOP -->
<button id="backToTop" onclick="window.scrollTo({top:0,behavior:'smooth'})" aria-label="Back to top">
  <i class="ti ti-arrow-up"></i>
</button>

<script>
// ─── DATA ───
const data = [
  // PARKS
  {id:1,  title:"Pullen Park",                      cat:"parks",  cost:"low",  sn:true,  ages:["baby","toddler","kids","teen"], icon:"ti-trees",            desc:"Raleigh's oldest amusement park. Carousel, train rides, pedal boats, playgrounds, and picnic areas. Rides ~$1 each. Accessible playground equipment and paved paths.",tags:["Affordable","Outdoor","Accessible"],link:"https://raleighnc.gov/pullen-park",                    map:"https://maps.google.com/?q=Pullen+Park+Raleigh+NC",                              loc:"Raleigh"},
  {id:2,  title:"William B. Umstead State Park",    cat:"parks",  cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-mountain",          desc:"Over 5,000 acres of trails, lakes, and wildlife. Free entry. Fishing, picnicking, hiking, and horseback riding. Paved trails for strollers and wheelchairs.",tags:["Free","Outdoor","Accessible"],link:"https://ncparks.gov/william-b-umstead-state-park",        map:"https://maps.google.com/?q=Umstead+State+Park+Cary+NC",                          loc:"Cary / Raleigh"},
  {id:3,  title:"American Tobacco Trail",           cat:"parks",  cost:"free", sn:true,  ages:["baby","toddler","kids","teen"], icon:"ti-bike",              desc:"Paved multi-use rail-trail open to walkers, runners, cyclists, and dog walkers. Flat and fully accessible for strollers and wheelchairs.",tags:["Free","Outdoor","Accessible"],link:"https://triangletrails.org",                               map:"https://maps.google.com/?q=American+Tobacco+Trail+Raleigh+NC",                   loc:"Raleigh Area"},
  {id:4,  title:"Shelley Lake Park",                cat:"parks",  cost:"free", sn:false, ages:["baby","toddler","kids"],        icon:"ti-droplet",           desc:"Beautiful lake with a 1.5-mile loop trail. Playground, picnic shelters, and a fishing pier. Ducks and geese year-round — kids love it!",tags:["Free","Outdoor","All ages"],link:"https://raleighnc.gov",                                       map:"https://maps.google.com/?q=Shelley+Lake+Park+Raleigh+NC",                        loc:"Raleigh"},
  {id:5,  title:"Downtown Cary Park",               cat:"parks",  cost:"free", sn:true,  ages:["baby","toddler","kids"],        icon:"ti-building-community",desc:"Stunning 7-acre urban park (2025). Sensory maze, water play mountain, swing terrace, adventure playground, fountains, and gardens. Designed for all ages and abilities.",tags:["Free","Outdoor","Sensory-friendly"],link:"https://www.townofcary.org",                              map:"https://maps.google.com/?q=Downtown+Cary+Park+NC",                               loc:"Cary"},
  {id:6,  title:"Lake Crabtree County Park",        cat:"parks",  cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-fish",              desc:"Fishing, mountain biking, kayaking, and picnicking. Free entry; small fee for boat rentals. 16+ miles of trails around a 215-acre lake.",tags:["Free","Outdoor","Water"],link:"https://www.wake.gov/parks",                                  map:"https://maps.google.com/?q=Lake+Crabtree+County+Park+Morrisville+NC",            loc:"Morrisville"},
  {id:7,  title:"Hemlock Bluffs Nature Preserve",   cat:"parks",  cost:"free", sn:false, ages:["baby","toddler","kids"],        icon:"ti-trees",             desc:"Rare hemlock trees and accessible boardwalk trails through a peaceful nature preserve. Wildlife viewing, seasonal wildflowers, and stroller-friendly paths.",tags:["Free","Outdoor","Accessible"],link:"https://www.townofcary.org",                              map:"https://maps.google.com/?q=Hemlock+Bluffs+Nature+Preserve+Cary+NC",              loc:"Cary"},
  {id:8,  title:"Neuse River Greenway Trail",       cat:"parks",  cost:"free", sn:true,  ages:["baby","toddler","kids","teen"], icon:"ti-route",             desc:"28+ miles of paved multi-use trail along the Neuse River. Fully accessible for strollers, wheelchairs, and cyclists. Frequent wildlife sightings including herons and deer.",tags:["Free","Outdoor","Accessible"],link:"https://raleighnc.gov",                                  map:"https://maps.google.com/?q=Neuse+River+Greenway+Raleigh+NC",                    loc:"Raleigh"},
  {id:9,  title:"Bass Lake Park",                   cat:"parks",  cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-ripple",            desc:"Open year-round 8am–sunset. Environmental education center, fishing, hiking trails, and wildlife observation. Spot great blue herons and beavers.",tags:["Free","Outdoor","Nature"],link:"https://www.wake.gov/parks",                                  map:"https://maps.google.com/?q=Bass+Lake+Park+Holly+Springs+NC",                    loc:"Holly Springs"},
  {id:10, title:"Durant Nature Preserve",           cat:"parks",  cost:"free", sn:true,  ages:["toddler","kids"],              icon:"ti-leaf",              desc:"237 acres of hardwood and pine forest with two lakes. Sensory and nature play area for children. Inclusion Services team available — call 919-996-2147.",tags:["Free","Outdoor","Sensory-friendly"],link:"https://raleighnc.gov/services/parks/nature-parks-programs", map:"https://maps.google.com/?q=Durant+Nature+Preserve+Raleigh+NC",                  loc:"Raleigh"},
  {id:11, title:"Walnut Creek Wetland Park",        cat:"parks",  cost:"free", sn:false, ages:["toddler","kids","teen"],        icon:"ti-seeding",           desc:"Free urban wetland park with boardwalk trails through marshland. Spot herons, turtles, dragonflies, and native wildflowers. Wonderful sensory experience.",tags:["Free","Outdoor","Nature"],link:"https://raleighnc.gov",                                       map:"https://maps.google.com/?q=Walnut+Creek+Wetland+Park+Raleigh+NC",               loc:"Raleigh"},
  {id:12, title:"Dorothea Dix Park",                cat:"parks",  cost:"free", sn:false, ages:["baby","toddler","kids","teen"], icon:"ti-sun",               desc:"Massive 308-acre park in the heart of Raleigh. Open fields, trails, and the famous annual sunflower field. Free kite flying, picnics, and disc golf. Stunning skyline views.",tags:["Free","Outdoor","All ages"],link:"https://dixpark.org",                                         map:"https://maps.google.com/?q=Dorothea+Dix+Park+Raleigh+NC",                       loc:"Raleigh"},

  // MUSEUMS
  {id:13, title:"NC Museum of Natural Sciences",    cat:"museums",cost:"free", sn:true,  ages:["toddler","kids","teen"],        icon:"ti-microscope",        desc:"Southeast's largest natural history museum — always free! Live animals, dinosaur fossils, whale skeletons, 4 floors of exhibits. Monthly sensory-friendly hours for autism and sensory needs.",tags:["Free","Indoor","Sensory-friendly"],link:"https://naturalsciences.org",                            map:"https://maps.google.com/?q=NC+Museum+of+Natural+Sciences+Raleigh",               loc:"Downtown Raleigh"},
  {id:14, title:"NC Museum of Art + Goodnight Park",cat:"museums",cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-photo",             desc:"Free admission to permanent galleries. 164-acre outdoor art park with sculptures, trails, and giant troll installations (2025). Art Cart in the Park and family programs.",tags:["Free","Outdoor","All ages"],link:"https://ncartmuseum.org",                                  map:"https://maps.google.com/?q=NC+Museum+of+Art+Raleigh",                            loc:"Raleigh"},
  {id:15, title:"NC Museum of History",             cat:"museums",cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-award",             desc:"Free admission. 14,000+ years of NC history through artifacts, multimedia, and dioramas. NC Sports Hall of Fame on-site. Great for school-age kids.",tags:["Free","Indoor","Educational"],link:"https://ncmuseumofhistory.org",                           map:"https://maps.google.com/?q=NC+Museum+of+History+Raleigh",                        loc:"Downtown Raleigh"},
  {id:16, title:"Marbles Kids Museum",              cat:"museums",cost:"low",  sn:true,  ages:["baby","toddler","kids"],        icon:"ti-puzzle",            desc:"Hands-on play-based STEAM exhibits designed for children. ~$8/child. Monthly Sensory Mornings for children with sensory processing differences. IMAX theater on-site.",tags:["Affordable","Indoor","Sensory-friendly"],link:"https://marbleskidsmuseum.org",                        map:"https://maps.google.com/?q=Marbles+Kids+Museum+Raleigh",                         loc:"Downtown Raleigh"},
  {id:17, title:"Mordecai Historic Park",           cat:"museums",cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-home",              desc:"Walk historic grounds for free anytime. Home to Raleigh's oldest building (1785) and birthplace of President Andrew Johnson. Free guided tours available.",tags:["Free","Outdoor","Historic"],link:"https://raleighnc.gov/mordecai",                             map:"https://maps.google.com/?q=Mordecai+Historic+Park+Raleigh",                      loc:"Raleigh"},
  {id:18, title:"NC State Capitol Grounds",         cat:"museums",cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-building-arch",     desc:"Free historic landmark built in 1840 and still in use today. Explore beautiful grounds and monuments. Great for a walking history lesson or picnic.",tags:["Free","Outdoor","Historic"],link:"https://ncstatecapitol.org",                                map:"https://maps.google.com/?q=NC+State+Capitol+Raleigh",                            loc:"Downtown Raleigh"},
  {id:19, title:"Historic Yates Mill County Park",  cat:"museums",cost:"low",  sn:false, ages:["kids","teen"],                 icon:"ti-windmill",          desc:"NC's last operating water-powered gristmill. $3–5 for mill tours, Sat & Sun through November. Free park entry, 0.8-mile pond trail. Visit Howling Cow ice cream nearby at NC State!",tags:["Affordable","Outdoor","Historic"],link:"https://www.wake.gov/parks",                            map:"https://maps.google.com/?q=Yates+Mill+County+Park+Raleigh+NC",                  loc:"Raleigh"},

  // LIBRARY
  {id:20, title:"Wake County Public Libraries",     cat:"library",cost:"free", sn:true,  ages:["baby","toddler","kids","teen"], icon:"ti-books",             desc:"Free storytimes, STEAM programs, book clubs, and pop-up events at 23 branches countywide. Summer Reading Program June 7–Aug 15. Special programs for kids with disabilities.",tags:["Free","Indoor","All ages"],link:"https://library.wakegov.com",                               map:"https://maps.google.com/?q=Wake+County+Library+Raleigh+NC",                      loc:"Countywide"},
  {id:21, title:"StoryWalk® Trails at Parks",       cat:"library",cost:"free", sn:false, ages:["baby","toddler","kids"],        icon:"ti-walk",              desc:"Read a children's picture book while enjoying a nature walk! Book pages are posted along trails at multiple Wake County parks. A magical way to combine reading and nature.",tags:["Free","Outdoor","Educational"],link:"https://www.wake.gov/parks",                              map:"https://maps.google.com/?q=Wake+County+Parks+NC",                                loc:"Countywide"},

  // RECREATION
  {id:22, title:"Wake County Parks Nature Programs",cat:"rec",    cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-leaf",              desc:"Free guided hikes, bird watching, environmental education, and nature talks at parks countywide year-round. Great for curious kids and outdoor families.",tags:["Free","Outdoor","All ages"],link:"https://www.wake.gov/parks",                                  map:"https://maps.google.com/?q=Wake+County+Parks+NC",                                loc:"Countywide"},
  {id:23, title:"JC Raulston Arboretum at NC State",cat:"rec",    cost:"free", sn:false, ages:["baby","toddler","kids"],        icon:"ti-flower",            desc:"One of the nation's top botanical gardens — completely free! June brings roses and summer blooms. Beautiful shaded canopy perfect for family strolls. Look for rabbits near the pavilion!",tags:["Free","Outdoor","Nature"],link:"https://jcra.ncsu.edu",                                      map:"https://maps.google.com/?q=JC+Raulston+Arboretum+Raleigh+NC",                   loc:"Raleigh (NC State)"},

  // ARTS
  {id:24, title:"Artspace Gallery",                 cat:"arts",   cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-palette",           desc:"NC's only visual arts center with 30+ studio artists and free rotating exhibition galleries. Family art education programs, story time events, and open studios.",tags:["Free","Indoor","Arts"],link:"https://artspacenc.org",                                     map:"https://maps.google.com/?q=Artspace+Gallery+Raleigh+NC",                         loc:"Downtown Raleigh"},
  {id:25, title:"Raleigh City Farm",                cat:"arts",   cost:"free", sn:false, ages:["toddler","kids"],              icon:"ti-plant",             desc:"Free urban farm with educational programs for families. Wednesday farmstands, garden storytimes, and seasonal events. Kids love meeting the chickens!",tags:["Free","Outdoor","Educational"],link:"https://www.raleighcityfarm.org",                         map:"https://maps.google.com/?q=Raleigh+City+Farm+NC",                                loc:"Raleigh"},

  // ANIMALS
  {id:26, title:"Raleigh Wild Bird Center",         cat:"animals",cost:"free", sn:false, ages:["toddler","kids","teen"],        icon:"ti-feather",           desc:"Free visit to browse birds, feeders, and nature supplies. Staff answer questions about local wildlife and bird feeding. Great first stop for young nature lovers.",tags:["Free","Indoor","Animals"],link:"https://raleighnc.gov",                                       map:"https://maps.google.com/?q=Raleigh+Wild+Bird+Center+NC",                         loc:"Raleigh"},
  {id:27, title:"Bond Lake Park + Wildlife",        cat:"animals",cost:"free", sn:false, ages:["baby","toddler","kids"],        icon:"ti-ripple",            desc:"Free park in Cary with a lake, trails, and abundant wildlife. Ducks, geese, turtles, and great blue herons are common sights. Accessible paved trail around the lake.",tags:["Free","Outdoor","Animals"],link:"https://www.townofcary.org",                               map:"https://maps.google.com/?q=Bond+Lake+Park+Cary+NC",                              loc:"Cary"},
  {id:28, title:"Juniper Level Botanic Garden",     cat:"animals",cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-bug",               desc:"28-acre campus with 27,000+ plant taxa and abundant butterflies, bees, and pollinators. Free self-guided tours. One of the most biodiverse gardens in the Southeast.",tags:["Free","Outdoor","Nature"],link:"https://www.jlbg.org",                                        map:"https://maps.google.com/?q=Juniper+Level+Botanic+Garden+Raleigh+NC",             loc:"Raleigh"},

  // SPECIAL NEEDS
  {id:29, title:"Specialized Recreation & Inclusion Services", cat:"sn", cost:"low", sn:true, ages:["toddler","kids","teen"], icon:"ti-accessibility", desc:"City of Raleigh programs for individuals of all ages with developmental and physical disabilities. Sports, arts, social events, dances, and camps. Low cost. Call 919-996-2147.", tags:["Affordable","Inclusive","All ages"], link:"https://raleighnc.gov/sris", map:"https://maps.google.com/?q=Raleigh+Parks+Recreation+NC", loc:"Raleigh"},
  {id:30, title:"Special Olympics Wake County",     cat:"sn",    cost:"free", sn:true,  ages:["kids","teen"],                 icon:"ti-trophy",            desc:"Year-round sport training and athletic competition for individuals with intellectual disabilities — completely free for athletes. Summer sports in full swing. Visit to register or volunteer.",tags:["Free","Inclusive","Sports"],link:"https://specialolympicsnc.org",                          map:"https://maps.google.com/?q=Special+Olympics+NC+Raleigh",                         loc:"Raleigh"},
  {id:31, title:"SPIRIT Wake Forest",               cat:"sn",    cost:"low",  sn:true,  ages:["kids","teen"],                 icon:"ti-heart",             desc:"Adaptive and inclusive recreation run by certified recreational therapists. Sports, art, cooking, social gatherings, dances, and more for individuals of all abilities.",tags:["Affordable","Inclusive","All ages"],link:"https://www.wakeforestnc.gov/spirit",                      map:"https://maps.google.com/?q=Wake+Forest+NC+Recreation+Center",                    loc:"Wake Forest"},
  {id:32, title:"GiGi's Playhouse",                 cat:"sn",    cost:"free", sn:true,  ages:["baby","toddler","kids","teen"], icon:"ti-star",              desc:"Free achievement center for individuals with Down syndrome and their families, from prenatal to adult. Tutoring, fitness, music, speech, and literacy programs. Walk-ins welcome.",tags:["Free","Inclusive","Educational"],link:"https://gigisplayhouse.org",                             map:"https://maps.google.com/?q=GiGi+Playhouse+Raleigh+NC",                           loc:"Raleigh"},
  {id:33, title:"Triangle Taiko Drumming",          cat:"sn",    cost:"free", sn:true,  ages:["kids","teen"],                 icon:"ti-music",             desc:"Free taiko drumming classes for teens and adults with developmental and physical disabilities. Builds fitness while learning Japanese drumming arts. Carolina Pines Community Center.",tags:["Free","Inclusive","Arts"],link:"https://raleighnc.gov/sris",                               map:"https://maps.google.com/?q=Carolina+Pines+Community+Center+Raleigh",             loc:"Raleigh"},
  {id:34, title:"Abilities Tennis of NC",           cat:"sn",    cost:"free", sn:true,  ages:["kids","teen"],                 icon:"ti-tennis",            desc:"Free tennis lessons and competitive play for individuals with disabilities. All equipment provided, all experience levels welcome. Millbrook Exchange Tennis Center.",tags:["Free","Inclusive","Sports"],link:"https://raleighnc.gov/sris",                               map:"https://maps.google.com/?q=Millbrook+Exchange+Park+Raleigh+NC",                  loc:"Raleigh"},
  {id:35, title:"No-Cost Respite Saturdays (SNCI)", cat:"sn",    cost:"free", sn:true,  ages:["toddler","kids"],              icon:"ti-users",             desc:"Free monthly Saturday respite for families of kids with special needs ages 2–16. Every child gets their own caring 'buddy' for crafts, games, and fun. 9:30am–12:30pm. Pre-register at snci-nc.org.",tags:["Free","Inclusive","Respite"],link:"https://www.snci-nc.org",                               map:"https://maps.google.com/?q=Raleigh+NC",                                          loc:"Raleigh Area"},
  {id:36, title:"Project Enlightenment",            cat:"sn",    cost:"free", sn:true,  ages:["baby","toddler"],              icon:"ti-sun",               desc:"Free early childhood education and intervention through Wake County Public Schools. Supports children birth–5 with developmental delays and their families.",tags:["Free","Inclusive","Educational"],link:"https://www.wcpss.net",                                   map:"https://maps.google.com/?q=Project+Enlightenment+Raleigh+NC",                   loc:"Raleigh"},
  {id:37, title:"Sassafras All Children's Playground",cat:"sn",  cost:"free", sn:true,  ages:["baby","toddler","kids"],        icon:"ti-playground",        desc:"Inclusive playground at Laurel Hills Park designed for children of all abilities. Sensory-rich activities, accessible equipment, rings over soft sand, and wide paved paths.",tags:["Free","Outdoor","Accessible"],link:"https://raleighnc.gov",                                  map:"https://maps.google.com/?q=Laurel+Hills+Park+Raleigh+NC",                        loc:"Raleigh"},
  {id:38, title:"Dance Class for Kids with Special Needs",cat:"sn",cost:"low",sn:true,  ages:["toddler","kids"],              icon:"ti-music",             desc:"Joyful inclusive dance class designed to empower young children with developmental special needs. Trained instructors create a safe, welcoming space where every child moves and belongs.",tags:["Affordable","Inclusive","Arts"],link:"https://fun4raleighkids.com",                              map:"https://maps.google.com/?q=Downtown+Cary+Park+NC",                               loc:"Cary"},

  // MORE FREE / SEASONAL
  {id:39, title:"Apex Farmers Market",              cat:"rec",   cost:"free", sn:false, ages:["baby","toddler","kids","teen"], icon:"ti-garden-cart",       desc:"Free to browse non-profit community farmers market in downtown Apex. Fresh local produce, eggs, honey, flowers, and crafts every Saturday morning. Fun for kids who love animals and food.",tags:["Free","Outdoor","All ages"],link:"https://apexfarmersmarket.org",                          map:"https://maps.google.com/?q=Apex+Farmers+Market+NC",                              loc:"Apex"},
  {id:40, title:"State Farmers Market — Raleigh",   cat:"rec",   cost:"free", sn:false, ages:["baby","toddler","kids","teen"], icon:"ti-tractor",           desc:"One of the nation's best farmers markets — open 7 days a week. Browse fresh NC produce, plants, and local foods. Free to explore. Kids love the garden center and produce stands.",tags:["Free","Outdoor","All ages"],link:"https://www.ncagr.gov/markets/facilities/markets/raleigh",map:"https://maps.google.com/?q=State+Farmers+Market+Raleigh+NC",                     loc:"Raleigh"},
  {id:41, title:"Cary Arts Center — Family Events", cat:"arts",  cost:"free", sn:false, ages:["kids","teen"],                 icon:"ti-building",          desc:"Free and low-cost family arts events at the Cary Arts Center throughout the year. Performances, workshops, and exhibits in a beautiful facility. Check calendar for monthly events.",tags:["Free","Indoor","Arts"],link:"https://www.townofcary.org/parks-recreation-culture",   map:"https://maps.google.com/?q=Cary+Arts+Center+NC",                                loc:"Cary"},
  {id:42, title:"Raleigh Little Theater Youth Programs",cat:"arts",cost:"low",sn:false, ages:["kids","teen"],                 icon:"ti-masks-theater",     desc:"Affordable youth theater arts classes and performances at Raleigh's beloved community theater. Kids build confidence, creativity, and friendships. Indoor accessible venue.",tags:["Affordable","Indoor","Arts"],link:"https://raleighlittletheatre.org",                        map:"https://maps.google.com/?q=Raleigh+Little+Theatre+NC",                           loc:"Raleigh"},
];

// ─── STATE ───
let activeCat  = 'all';
let activeCost = 'all';
let activeAge  = 'all';

// ─── FILTERS ───
function setFilter(el, type) {
  if (type === 'cat') {
    document.querySelectorAll('#catPills .pill').forEach(b => b.classList.remove('active-cat','active-sn'));
    activeCat = el.dataset.cat;
    el.classList.add(activeCat === 'sn' ? 'active-sn' : 'active-cat');
  } else if (type === 'cost') {
    document.querySelectorAll('#costPills .pill').forEach(b => b.classList.remove('active-cost'));
    activeCost = el.dataset.cost;
    el.classList.add('active-cost');
  } else if (type === 'age') {
    document.querySelectorAll('#agePills .pill').forEach(b => b.classList.remove('active-age'));
    activeAge = el.dataset.age;
    el.classList.add('active-age');
  }
  render();
}

function clearFilters() {
  activeCat = 'all'; activeCost = 'all'; activeAge = 'all';
  document.getElementById('searchInput').value = '';
  document.querySelectorAll('#catPills .pill').forEach(b => b.classList.remove('active-cat','active-sn'));
  document.querySelector('#catPills .pill').classList.add('active-cat');
  document.querySelectorAll('#costPills .pill').forEach(b => b.classList.remove('active-cost'));
  document.querySelector('#costPills .pill').classList.add('active-cost');
  document.querySelectorAll('#agePills .pill').forEach(b => b.classList.remove('active-age'));
  document.querySelector('#agePills .pill').classList.add('active-age');
  render();
}

// ─── BADGE CLASS ───
function badgeClass(tag) {
  const t = tag.toLowerCase();
  if (t === 'free') return 'b-free';
  if (t.includes('afford')) return 'b-low';
  if (['inclusive','sensory','accessible','adapt','respite'].some(k => t.includes(k))) return 'b-sn';
  if (['outdoor','trails','water','nature','animals','sports'].some(k => t.includes(k))) return 'b-outdoor';
  if (t === 'indoor') return 'b-indoor';
  if (['educational','historic','arts'].some(k => t.includes(k))) return 'b-edu';
  return 'b-default';
}

// ─── RENDER ───
function render() {
  const q = document.getElementById('searchInput').value.toLowerCase().trim();
  const isFiltered = activeCat !== 'all' || activeCost !== 'all' || activeAge !== 'all' || q;
  document.getElementById('snBanner').style.display = activeCat === 'sn' ? 'flex' : 'none';
  document.getElementById('clearBtn').style.display = isFiltered ? 'inline-block' : 'none';

  const filtered = data.filter(d => {
    const catMatch  = activeCat  === 'all' || d.cat === activeCat || (activeCat === 'sn' && d.sn);
    const costMatch = activeCost === 'all' || d.cost === activeCost;
    const ageMatch  = activeAge  === 'all' || d.ages.includes(activeAge);
    const qMatch    = !q ||
      d.title.toLowerCase().includes(q) ||
      d.desc.toLowerCase().includes(q)  ||
      d.loc.toLowerCase().includes(q)   ||
      d.tags.some(t => t.toLowerCase().includes(q));
    return catMatch && costMatch && ageMatch && qMatch;
  });

  document.getElementById('resCount').textContent =
    filtered.length + ' activit' + (filtered.length === 1 ? 'y' : 'ies') + ' found';

  const grid = document.getElementById('cardGrid');
  if (!filtered.length) {
    grid.innerHTML = `<div class="empty"><i class="ti ti-mood-sad"></i><p>No activities found. Try different keywords or clear your filters.</p></div>`;
    return;
  }

  grid.innerHTML = filtered.map(d => `
    <div class="card">
      <div class="card-top">
        <div class="card-title">${d.title}</div>
        <i class="ti ${d.icon} card-icon" aria-hidden="true"></i>
      </div>
      <div style="display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:4px;">
        <div class="card-loc"><i class="ti ti-map-pin"></i>${d.loc}</div>
        <span class="card-ages">${ageLabel(d.ages) }</span>
      </div>
      <div class="card-desc">${d.desc}</div>
      <div class="card-meta">
        ${d.tags.map(t => `<span class="badge ${badgeClass(t)}">${t}</span>`).join('')}
        ${d.sn ? `<span class="badge b-sn"><i class="ti ti-accessibility" style="font-size:11px"></i> Inclusive</span>` : ''}
      </div>
      <div class="card-actions">
        <a class="card-link" href="${d.link}" target="_blank" rel="noopener">Visit website <i class="ti ti-external-link" style="font-size:11px"></i></a>
        <a class="card-map"  href="${d.map}"  target="_blank" rel="noopener"><i class="ti ti-map-pin" style="font-size:12px"></i> Map</a>
      </div>
    </div>
  `).join('');
}

function ageLabel(ages) {
  if (ages.length === 4) return 'All Ages';
  const labels = { baby:'0–2', toddler:'3–5', kids:'6–12', teen:'Teens' };
  return ages.map(a => labels[a]).join(', ');
}

// ─── NEWSLETTER ───
function subscribeNewsletter() {
  const emailInput = document.getElementById('nlEmail');
  const email = emailInput.value.trim();
  if (!email || !/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)) {
    emailInput.style.borderColor = '#FFB3A0';
    emailInput.placeholder = 'Please enter a valid email';
    emailInput.value = '';
    setTimeout(() => { emailInput.style.borderColor = 'rgba(255,255,255,0.4)'; emailInput.placeholder = 'Your email address'; }, 2500);
    return;
  }
  document.getElementById('nlForm').style.display = 'none';
  document.getElementById('nlSuccess').style.display = 'flex';
  console.log('New subscriber:', email); // Connect to Mailchimp/MailerLite
}

// ─── NAV MOBILE ───
function toggleMenu() {
  const m = document.getElementById('mobileMenu');
  m.style.display = m.style.display === 'flex' ? 'none' : 'flex';
}
function closeMenu() {
  document.getElementById('mobileMenu').style.display = 'none';
}

// ─── BACK TO TOP ───
window.addEventListener('scroll', () => {
  const btn = document.getElementById('backToTop');
  btn.classList.toggle('visible', window.scrollY > 400);
});

// ─── INIT ───
render();
</script>
</body>
</html>

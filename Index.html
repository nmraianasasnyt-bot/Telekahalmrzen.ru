<!doctype html><html><head><meta charset=utf8><meta name=viewport content="width=device-width,initial-scale=1,viewport-fit=cover"><style>:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}html{scroll-padding-top:env(safe-area-inset-top,0px)}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#fff;color:#000}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}</style></head><body>
<title>MrZen&FM Эфир</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;700;800&family=Rubik+Wet+Paint&display=swap">
<style>
  /* Концепция: ночной хэллоуинский телеканал. Тёмный фиолет, тыквенный оранжевый, туман, летучие мыши. */
  :root{
    --bg:#0b0712; --bg2:#160c22; --fg:#f4edff; --muted:#a99bc0; --accent:#ff7a18; --accent2:#9b5cff;
    --card:rgba(22,12,34,.78); --line:rgba(255,255,255,.11);
    --display:"Rubik Wet Paint", Impact, "Arial Black", system-ui, sans-serif;
    --font:"Rubik", ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
    color-scheme:dark;
  }
  :root[data-look="classic"]{
    --bg:#07090c; --bg2:#10151b; --fg:#f1f3f5; --muted:#8e98a4; --accent:#b6ff3c; --accent2:#5ec8ff;
    --card:rgba(16,20,26,.78); --line:rgba(255,255,255,.1);
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth;scroll-padding-top:84px}
  body{font-family:var(--font);color:var(--fg);line-height:1.55;overflow-x:hidden;
    background:radial-gradient(1100px 700px at 78% 4%, color-mix(in srgb,var(--accent2) 22%,transparent) 0%, transparent 62%),
               radial-gradient(900px 600px at 4% 96%, color-mix(in srgb,var(--accent) 14%,transparent) 0%, transparent 60%), var(--bg);
    background-attachment:fixed}
  body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:60;opacity:.07;mix-blend-mode:overlay;
    background-image:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='160' height='160'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='2'/></filter><rect width='100%' height='100%' filter='url(%23n)'/></svg>")}
  #gl{position:fixed;inset:0;width:100%;height:100%;z-index:0;display:block}
  #fx{position:fixed;inset:0;width:100%;height:100%;z-index:3;pointer-events:none}
  main,footer{position:relative;z-index:2}
  :focus-visible{outline:2px solid var(--accent);outline-offset:3px;border-radius:6px}

  /* туман */
  .fog{position:fixed;inset:-10% -20%;z-index:1;pointer-events:none;opacity:.5;
    background:radial-gradient(40% 18% at 20% 85%, rgba(190,160,255,.18), transparent 70%),
               radial-gradient(45% 20% at 75% 92%, rgba(255,150,60,.12), transparent 70%),
               radial-gradient(35% 15% at 55% 70%, rgba(190,160,255,.10), transparent 70%);
    animation:fog 26s ease-in-out infinite alternate}
  .fog.b{animation-duration:38s;animation-direction:alternate-reverse;opacity:.35;transform:scaleX(-1)}
  @keyframes fog{to{transform:translateX(8%) scale(1.08)}}
  .nofx .fog,.nofx #fx{display:none}
  /* фонарик */
  #torch{position:fixed;inset:0;z-index:55;pointer-events:none;opacity:0;transition:opacity .4s;
    background:radial-gradient(circle 170px at var(--mx,50%) var(--my,50%), transparent 0, transparent 40%, rgba(0,0,0,.94) 100%)}
  .torch #torch{opacity:1}
  /* вспышка / тряска */
  #flash{position:fixed;inset:0;z-index:58;pointer-events:none;background:rgba(205,185,255,.38);opacity:0}
  #flash.go{animation:flash .75s steps(1,end)}
  @keyframes flash{0%{opacity:.9}12%{opacity:0}22%{opacity:.7}40%{opacity:0}100%{opacity:0}}
  .shake main{animation:shake .5s}
  @keyframes shake{20%{transform:translate(-4px,2px)}40%{transform:translate(5px,-2px)}60%{transform:translate(-3px,-1px)}80%{transform:translate(2px,2px)}}
  /* кинотеатр */
  main>section,main>.ticker,main>#story,#gl,.fog,#fx,.web{transition:opacity .6s}
  body.cinema main>section:not(#live),body.cinema main>.ticker,body.cinema main>#story,body.cinema .web{opacity:.06;pointer-events:none}
  body.cinema #gl,body.cinema .fog,body.cinema #fx,body.cinema .fb,body.cinema .fbc{opacity:.12}
  body.cinema #live .ptv{box-shadow:0 60px 160px -20px #000,0 0 160px -10px var(--accent),inset 0 2px 0 rgba(255,255,255,.13)}

  /* паутина */
  .web{position:fixed;top:0;left:0;width:min(34vw,280px);z-index:2;pointer-events:none;opacity:.5}

  /* шапка */
  header{position:fixed;top:0;left:0;right:0;z-index:30;display:flex;align-items:center;gap:22px;padding:14px 5vw;
    background:linear-gradient(180deg,rgba(11,7,18,.9),rgba(11,7,18,.55));backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);border-bottom:1px solid var(--line)}
  .logo{font-family:var(--display);font-size:26px;color:var(--fg);text-decoration:none;letter-spacing:.01em;margin-right:auto}
  .logo span{color:var(--accent)}
  nav{display:flex;gap:6px}
  nav a{color:var(--muted);text-decoration:none;font-weight:500;font-size:15px;padding:9px 15px;border-radius:999px;transition:.25s}
  nav a:hover{color:var(--fg)}
  nav a.on{color:#14090a;background:var(--accent)}
  #burger{display:none;font:inherit;font-size:22px;color:var(--fg);background:none;border:1px solid var(--line);border-radius:12px;width:44px;height:44px;cursor:pointer}
  #prog{position:fixed;top:0;left:0;height:3px;width:0;z-index:31;background:linear-gradient(90deg,var(--accent2),var(--accent));box-shadow:0 0 12px var(--accent)}

  /* типографика и кнопки */
  .eyebrow{display:inline-flex;align-items:center;gap:10px;font-size:13px;letter-spacing:.18em;text-transform:uppercase;color:var(--accent);font-weight:500}
  .eyebrow i{width:9px;height:9px;border-radius:50%;background:#ff3b3b;box-shadow:0 0 14px #ff3b3b;animation:pulse 1.4s infinite}
  @keyframes pulse{50%{opacity:.3}}
  h1,h2{font-family:var(--display);font-weight:400;text-wrap:balance}
  h1{font-size:clamp(46px,8.4vw,128px);line-height:.98;margin:20px 0 22px}
  h1 span{color:var(--accent);transition:color .4s}
  h2{font-size:clamp(34px,5.4vw,74px);line-height:1.02;margin-bottom:16px}
  h3{font-size:14px;letter-spacing:.16em;text-transform:uppercase;color:var(--accent);font-weight:700;margin:40px 0 0}
  p.lead{font-size:clamp(16px,1.6vw,20px);color:var(--muted);max-width:36ch}
  .btn{display:inline-flex;align-items:center;gap:10px;padding:16px 28px;border-radius:999px;font:inherit;font-weight:700;font-size:16px;text-decoration:none;cursor:pointer;border:0;
    color:#160a05;background:var(--accent);transition:transform .25s,background .4s,border-color .25s,color .25s;box-shadow:0 14px 44px -14px var(--accent)}
  .btn:hover{transform:translateY(-3px)}
  .btn.ghost{background:transparent;color:var(--fg);border:1px solid var(--line);box-shadow:none}
  .btn.ghost:hover{border-color:var(--accent);color:var(--accent)}
  .btn.sm{padding:10px 20px;font-size:14px}
  .row{display:flex;gap:14px;flex-wrap:wrap;margin-top:28px}
  section{padding:0 6vw}
  .reveal{opacity:0;transform:translateY(30px);transition:opacity .8s,transform .8s cubic-bezier(.2,.7,.2,1)}
  .reveal.in{opacity:1;transform:none}

  #hero{min-height:100vh;display:flex;flex-direction:column;justify-content:flex-end;padding-bottom:9vh;padding-top:90px}
  .hint{margin-top:34px;font-size:12px;letter-spacing:.22em;text-transform:uppercase;color:var(--muted)}

  .ticker{position:relative;z-index:2;overflow:hidden;border-block:1px solid var(--line);background:rgba(11,7,18,.75);backdrop-filter:blur(8px);-webkit-backdrop-filter:blur(8px);padding:16px 0}
  .ticker div{display:flex;gap:48px;white-space:nowrap;width:max-content;animation:tick 30s linear infinite;font-family:var(--display);font-size:clamp(22px,3vw,36px)}
  .ticker em{font-style:normal;color:var(--accent)}
  @keyframes tick{to{transform:translateX(-50%)}}

  .step{min-height:100vh;display:flex;align-items:center}
  .step.right{justify-content:flex-end}
  .step .txt{max-width:440px}

  /* плеер */
  #live{padding-top:14vh;padding-bottom:12vh;text-align:center}
  #live .lead{margin:0 auto}
  .tabs{display:inline-flex;padding:5px;border-radius:999px;background:rgba(255,255,255,.06);border:1px solid var(--line);margin:26px 0 56px}
  .tabs button{font:inherit;font-weight:700;color:var(--muted);background:none;border:0;padding:13px 30px;border-radius:999px;cursor:pointer;transition:.3s}
  .tabs button.on{background:var(--accent);color:#160a05}
  .ptv{position:relative;width:min(1080px,100%);margin:0 auto;padding:clamp(14px,2.4vw,30px);padding-bottom:clamp(40px,5vw,64px);border-radius:clamp(22px,3vw,44px);text-align:left;
    background:linear-gradient(160deg,#2a2234,#0d0a12);box-shadow:0 60px 120px -30px #000,0 0 90px -20px var(--accent),inset 0 2px 0 rgba(255,255,255,.13)}
  .ptv::before,.ptv::after{content:"";position:absolute;bottom:100%;width:4px;height:clamp(50px,9vw,110px);background:#b9b0c8;border-radius:4px}
  .ptv::before{left:44%;transform-origin:bottom;transform:rotate(-24deg)}
  .ptv::after{left:56%;transform-origin:bottom;transform:rotate(24deg)}
  .knobs{position:absolute;right:clamp(14px,2.6vw,34px);bottom:clamp(12px,1.6vw,20px);display:flex;gap:10px;align-items:center}
  .knobs i{width:14px;height:14px;border-radius:50%;background:radial-gradient(circle at 35% 30%,#d9d0e6,#6c6079)}
  .knobs b{width:9px;height:9px;border-radius:50%;background:var(--accent);box-shadow:0 0 12px var(--accent)}
  .pscr{position:relative;aspect-ratio:16/9;border-radius:16px;overflow:hidden;background:#000;box-shadow:inset 0 0 50px #000}
  .pscr iframe{position:absolute;inset:0;width:100%;height:100%;border:0;background:#000}
  .poster{position:absolute;inset:0;display:grid;place-items:center;text-align:center;padding:20px;
    background:repeating-linear-gradient(0deg,rgba(0,0,0,.22) 0 2px,transparent 2px 5px),
      radial-gradient(70% 90% at 50% 40%, color-mix(in srgb,var(--accent) 26%,#150a22), #06030a)}
  .poster.off{display:none}
  .poster h3{margin:0 0 6px}
  .poster .big{font-family:var(--display);font-size:clamp(30px,6.4vw,84px);line-height:1}
  .poster .play{margin:18px auto 0;width:clamp(64px,9vw,96px);aspect-ratio:1;border-radius:50%;border:0;cursor:pointer;background:var(--accent);color:#160a05;font-size:clamp(26px,4vw,40px);
    display:grid;place-items:center;box-shadow:0 0 0 0 var(--accent);animation:ring 2s infinite}
  @keyframes ring{70%{box-shadow:0 0 0 24px transparent}100%{box-shadow:0 0 0 0 transparent}}
  .poster small{display:block;margin-top:14px;color:var(--muted);font-size:13px}
  .ctrl{display:flex;flex-wrap:wrap;justify-content:center;gap:10px;margin-top:26px}
  .chip{font:inherit;font-size:14px;font-weight:500;color:var(--fg);background:rgba(255,255,255,.06);border:1px solid var(--line);padding:10px 18px;border-radius:999px;cursor:pointer;text-decoration:none;transition:.25s}
  .chip:hover,.chip.on{border-color:var(--accent);color:var(--accent)}
  .keys{margin-top:20px;font-size:13px;color:var(--muted)}
  kbd{font:inherit;font-size:12px;border:1px solid var(--line);border-bottom-width:2px;border-radius:6px;padding:1px 7px;background:rgba(255,255,255,.05);color:var(--fg)}

  /* блоки */
  #about,#features,#faq{padding-top:11vh;padding-bottom:6vh}
  .specs{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:1px;background:var(--line);border:1px solid var(--line);border-radius:26px;overflow:hidden;margin-top:34px}
  .specs div{background:rgba(14,8,22,.88);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);padding:24px 26px}
  .specs small{display:block;color:var(--muted);font-size:12px;letter-spacing:.14em;text-transform:uppercase;margin-bottom:6px}
  .specs em{font-style:normal;font-size:18px;font-weight:600}
  .count{margin-top:22px;display:flex;flex-wrap:wrap;gap:18px;align-items:center;justify-content:space-between;padding:26px 30px;border-radius:26px;border:1px solid var(--line);background:var(--card);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px)}
  .count span{color:var(--muted);font-size:15px;max-width:22ch}
  .clock{display:flex;gap:14px}
  .clock div{text-align:center;min-width:64px}
  .clock b{display:block;font-family:var(--display);font-weight:400;font-size:clamp(34px,5vw,56px);line-height:1;color:var(--accent);font-variant-numeric:tabular-nums}
  .clock small{font-size:11px;letter-spacing:.14em;text-transform:uppercase;color:var(--muted)}
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:22px}
  .card{background:var(--card);backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);border:1px solid var(--line);border-radius:26px;padding:26px;box-shadow:0 30px 60px -30px rgba(0,0,0,.8);transition:transform .3s,border-color .3s}
  .card:hover{transform:translateY(-6px);border-color:var(--accent)}
  .card b{display:block;font-size:19px;margin:14px 0 6px;letter-spacing:-.01em}
  .card span{color:var(--muted);font-size:15px}
  .ic{width:46px;height:46px;border-radius:15px;display:grid;place-items:center;background:color-mix(in srgb,var(--accent) 18%,transparent);color:var(--accent);font-size:20px}

  /* FAQ */
  .faqhead{display:flex;flex-wrap:wrap;gap:20px;align-items:flex-end;justify-content:space-between}
  #q{font:inherit;color:var(--fg);background:rgba(255,255,255,.06);border:1px solid var(--line);border-radius:999px;padding:14px 22px;min-width:min(320px,100%);transition:border-color .25s}
  #q:focus{outline:none;border-color:var(--accent)}
  .qa{border-bottom:1px solid var(--line)}
  .qa summary{list-style:none;cursor:pointer;display:flex;justify-content:space-between;gap:20px;align-items:center;padding:24px 4px;font-size:clamp(17px,2vw,22px);font-weight:600}
  .qa summary::-webkit-details-marker{display:none}
  .qa summary::after{content:"+";flex:none;width:36px;height:36px;border-radius:50%;border:1px solid var(--line);display:grid;place-items:center;font-size:22px;color:var(--accent);transition:.3s}
  .qa[open] summary::after{transform:rotate(45deg);background:var(--accent);color:#160a05}
  .qa p{color:var(--muted);padding:0 56px 26px 4px;max-width:70ch}
  #faqEmpty{display:none;color:var(--muted);padding:26px 4px}
  .faqlist{margin-top:26px;border-top:1px solid var(--line)}

  #cta{min-height:80vh;display:flex;flex-direction:column;justify-content:flex-end;align-items:center;text-align:center;padding-bottom:10vh}
  #cta h2{font-size:clamp(44px,9vw,130px)}
  #cta p{color:var(--muted)}
  footer{text-align:center;color:var(--muted);font-size:13px;padding:30px 6vw 50px}

  /* пульт */
  #dock{position:fixed;right:16px;bottom:16px;z-index:40;display:flex;flex-direction:column;gap:8px;padding:8px;border-radius:22px;background:rgba(14,8,22,.82);border:1px solid var(--line);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px)}
  #dock button{position:relative;width:46px;height:46px;border-radius:14px;border:1px solid transparent;background:rgba(255,255,255,.05);color:var(--fg);font-size:21px;cursor:pointer;transition:.25s}
  #dock button:hover{border-color:var(--accent)}
  #dock button.on{background:var(--accent);border-color:var(--accent)}
  #dock button::after{content:attr(data-tip);position:absolute;right:calc(100% + 10px);top:50%;transform:translateY(-50%);white-space:nowrap;font-size:12px;padding:6px 10px;border-radius:8px;background:#000;color:#fff;opacity:0;pointer-events:none;transition:.2s}
  #dock button:hover::after{opacity:1}
  #toast{position:fixed;left:50%;bottom:22px;transform:translate(-50%,30px);z-index:70;background:#000;color:#fff;border:1px solid var(--accent);padding:12px 22px;border-radius:999px;font-size:14px;opacity:0;pointer-events:none;transition:.35s;max-width:92vw;text-align:center}
  #toast.show{opacity:1;transform:translate(-50%,0)}

  /* запасной вариант без WebGL */
  .fb{display:none;position:fixed;z-index:1;left:76%;top:36%;transform:translate(-50%,-50%) rotate(-4deg);width:min(38vw,460px);aspect-ratio:1.7;border-radius:34px;
    background:linear-gradient(160deg,#2a2234,#0d0a12);padding:5%;box-shadow:0 60px 80px -30px #000,inset 0 2px 0 rgba(255,255,255,.12)}
  .fb::before,.fb::after{content:"";position:absolute;bottom:100%;width:3px;height:70%;background:#b9b0c8;border-radius:3px}
  .fb::before{left:42%;transform-origin:bottom;transform:rotate(-26deg)}
  .fb::after{left:58%;transform-origin:bottom;transform:rotate(26deg)}
  .fb div{width:100%;height:100%;border-radius:14px;display:grid;place-items:center;text-align:center;
    background:repeating-linear-gradient(0deg,rgba(0,0,0,.2) 0 2px,transparent 2px 5px),linear-gradient(135deg,#2a1030,#05030a);
    font-family:var(--display);font-size:clamp(26px,5vw,56px);box-shadow:inset 0 0 60px #000}
  .fb small{display:block;color:var(--accent);font-size:.5em;font-family:var(--font);letter-spacing:.2em}
  .fbc{display:none;position:fixed;z-index:1;left:76%;top:64%;transform:translateX(-50%);gap:26px}
  .fbc i{display:block;position:relative;width:46px;height:56px;border-radius:50% 50% 12px 12px/45% 45% 12px 12px;background:#120a1c;box-shadow:0 -2px 0 color-mix(in srgb,var(--accent) 30%,transparent)}
  .fbc i::before{content:"";position:absolute;left:50%;top:-24px;width:26px;height:26px;margin-left:-13px;border-radius:50%;background:#160d22}
  .fbc i:nth-child(even){transform:translateY(14px) scale(.9)}
  .no-webgl #gl{display:none}.no-webgl .fb,.no-webgl .fbc{display:block}.no-webgl .fbc{display:flex}

  @media (max-width:860px){
    #burger{display:block}
    nav{position:fixed;top:72px;left:12px;right:12px;flex-direction:column;padding:12px;border-radius:22px;background:rgba(14,8,22,.96);border:1px solid var(--line);display:none}
    nav.open{display:flex}
    nav a{padding:14px 16px;font-size:17px}
    header .btn.sm{display:none}
    .step,.step.right{justify-content:flex-start;align-items:flex-end;padding-bottom:12vh}
    .step .txt{background:linear-gradient(180deg,transparent,rgba(11,7,18,.9) 35%);padding:60px 0 0}
    .qa p{padding-right:4px}
    .fb{left:50%;top:26%;width:70vw}.fbc{left:50%;top:44%;gap:14px}.fbc i{width:34px;height:42px}
    #dock{flex-direction:row;right:50%;transform:translateX(50%);bottom:12px}
    #dock button{width:42px;height:42px;font-size:19px}
    #dock button::after{display:none}
    .tabs{margin-bottom:46px}
  }
  @media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}.eyebrow i,.ticker div,.fog,.poster .play{animation:none}.reveal{opacity:1;transform:none;transition:none}}
</style>

<canvas id="gl" aria-hidden="true"></canvas>
<div class="fog" aria-hidden="true"></div><div class="fog b" aria-hidden="true"></div>
<canvas id="fx" aria-hidden="true"></canvas>
<div id="torch" aria-hidden="true"></div><div id="flash" aria-hidden="true"></div>
<svg class="web" viewBox="0 0 200 200" fill="none" stroke="#fff" stroke-width="1" aria-hidden="true">
  <path d="M0 0 L200 0 M0 0 L190 70 M0 0 L150 150 M0 0 L70 190 M0 0 L0 200"/>
  <path d="M40 0 Q34 30 0 40 M80 0 Q66 62 0 80 M125 0 Q104 98 0 125 M170 0 Q140 140 0 170"/>
</svg>
<div class="fb" aria-hidden="true"><div><span>MrZen&amp;FM<small>ЭФИР · LIVE</small></span></div></div>
<div class="fbc" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i></div>

<header>
  <a class="logo" href="#hero">MrZen<span>&amp;</span>FM</a>
  <nav id="nav" aria-label="Меню">
    <a href="#live">Эфир</a><a href="#about">О канале</a><a href="#features">Фишки</a><a href="#faq">FAQ</a>
  </nav>
  <a class="btn sm" href="#live" data-watch="tv">▶ Смотреть</a>
  <button id="burger" aria-label="Открыть меню" aria-expanded="false" aria-controls="nav">☰</button>
</header>
<div id="prog"></div>

<main>
  <section id="hero">
    <span class="eyebrow"><i></i> В эфире · VK Видео Live</span>
    <h1>MrZen<span>&amp;</span>FM<br>Эфир</h1>
    <p class="lead">Телеканал и FM в одном месте. Включай картинку, если не боишься, или оставляй звук фоном.</p>
    <div class="row">
      <a class="btn" href="#live" data-watch="tv">▶ Смотреть эфир</a>
      <a class="btn ghost" href="#live" data-watch="fm">♪ Слушать FM</a>
    </div>
    <div class="hint">Скролль ↓</div>
  </section>

  <div class="ticker" aria-hidden="true"><div>
    <span>MrZen&amp;FM <em>●</em> Эфир <em>●</em> FM <em>●</em> Live <em>●</em> Бу! <em>●</em></span>
    <span>MrZen&amp;FM <em>●</em> Эфир <em>●</em> FM <em>●</em> Live <em>●</em> Бу! <em>●</em></span>
    <span>MrZen&amp;FM <em>●</em> Эфир <em>●</em> FM <em>●</em> Live <em>●</em> Бу! <em>●</em></span>
    <span>MrZen&amp;FM <em>●</em> Эфир <em>●</em> FM <em>●</em> Live <em>●</em> Бу! <em>●</em></span>
  </div></div>

  <div id="story">
    <section class="step"><div class="txt reveal"><h3>01</h3><h2>Телеканал</h2>
      <p class="lead">Основной эфир MrZen&amp;FM идёт в прямой трансляции на VK Видео Live.</p></div></section>
    <section class="step right"><div class="txt reveal"><h3>02</h3><h2>FM-поток</h2>
      <p class="lead">Отдельная FM-трансляция для тех, кому картинка не нужна, а настроение нужно.</p></div></section>
    <section class="step"><div class="txt reveal"><h3>03</h3><h2>Зрители уже тут</h2>
      <p class="lead">Занимай место перед экраном. Эфир идёт прямо на этом сайте.</p></div></section>
  </div>

  <section id="live">
    <span class="eyebrow reveal">Эфир на сайте</span>
    <h2 class="reveal" style="margin-top:14px">Смотри прямо здесь</h2>
    <p class="lead reveal">Выбери, что включить, и нажми на экран телевизора.</p>
    <div class="tabs reveal" role="tablist" aria-label="Что смотреть">
      <button class="on" data-mode="tv" role="tab" aria-selected="true">Эфир</button>
      <button data-mode="fm" role="tab" aria-selected="false">FM</button>
    </div>
    <div class="ptv reveal">
      <div class="pscr" id="pscr">
                <div class="poster" id="poster">
          <div>
            <h3 id="pkind">Телеканал</h3>
            <div class="big">MrZen&amp;FM</div>
            <a class="play" id="playBtn" href="https://live.vkvideo.ru/mraianasasn4yt?c=1793077496" target="_blank" rel="noopener" aria-label="Открыть трансляцию в VK Видео" style="text-decoration:none">▶</a>
            <small>Нажми, чтобы открыть трансляцию в VK Видео.</small>
          </div>
        </div>
      </div>
      <div class="knobs" aria-hidden="true"><b></b><i></i><i></i></div>
    </div>
    <div class="ctrl reveal">
      <button class="chip" id="cinemaBtn">🎬 Кинотеатр</button>
            <button class="chip" id="copyBtn">🔗 Скопировать ссылку</button>
      <a class="chip" id="vkBtn" href="https://live.vkvideo.ru/mraianasasn4yt?c=1793077496" target="_blank" rel="noopener">Открыть в VK Видео →</a>
    </div>
    <p class="keys reveal">Горячие клавиши: <kbd>1</kbd> эфир · <kbd>2</kbd> FM · <kbd>C</kbd> кинотеатр · <kbd>M</kbd> звук · <kbd>L</kbd> фонарик · <kbd>B</kbd> бу!</p>
  </section>

  <section id="about">
    <span class="eyebrow reveal">Коротко</span>
    <h2 class="reveal" style="margin-top:14px">О канале</h2>
    <div class="specs reveal">
      <div><small>Площадка</small><em>VK Видео Live</em></div>
      <div><small>Формат</small><em>Телеканал + FM</em></div>
      <div><small>Канал</small><em>mraianasasn4yt</em></div>
      <div><small>Расписание</small><em>[уточнить]</em></div>
      <div><small>Язык эфира</small><em>[уточнить]</em></div>
      <div><small>Возраст</small><em>[уточнить]</em></div>
    </div>
    <div class="count reveal">
      <span id="cdLabel">До следующего Хэллоуина</span>
      <div class="clock" id="clock" aria-live="off">
        <div><b id="cd">0</b><small>дней</small></div><div><b id="ch">00</b><small>часов</small></div>
        <div><b id="cm">00</b><small>минут</small></div><div><b id="cs">00</b><small>секунд</small></div>
      </div>
    </div>
  </section>

  <section id="features">
    <span class="eyebrow reveal">Что внутри</span>
    <h2 class="reveal" style="margin-top:14px">Два формата.<br>Один канал.</h2>
    <div class="grid">
      <div class="card reveal"><div class="ic">▶</div><b>Прямой эфир</b><span>Телеканал MrZen&amp;FM в лайве на VK Видео Live.</span></div>
      <div class="card reveal"><div class="ic">♪</div><b>FM-трансляция</b><span>Отдельный стрим для тех, кто слушает, а не смотрит.</span></div>
      <div class="card reveal"><div class="ic">⌁</div><b>Без установки</b><span>Смотри в браузере: плеер встроен прямо в страницу.</span></div>
      <div class="card reveal"><div class="ic">◐</div><b>Своя программа</b><span>Сетка вещания: [уточнить: расписание и рубрики].</span></div>
    </div>
    <h3 class="reveal">Колдовской пульт справа внизу</h3>
    <div class="grid">
      <div class="card reveal"><div class="ic">🎬</div><b>Кинотеатр</b><span>Гасит весь свет, остаётся только телевизор. Клавиша C.</span></div>
      <div class="card reveal"><div class="ic">🔦</div><b>Фонарик</b><span>Тьма вокруг курсора. Исследуй сайт при свете луча. Клавиша L.</span></div>
      <div class="card reveal"><div class="ic">🔊</div><b>Звук ночи</b><span>Ветер и низкий гул. Включается только по кнопке. Клавиша M.</span></div>
      <div class="card reveal"><div class="ic">👻</div><b>Бу!</b><span>Молния, тряска и стая летучих мышей. Клавиша B.</span></div>
      <div class="card reveal"><div class="ic">🦇</div><b>Эффекты</b><span>Мыши, туман и искры. Можно выключить, сайт запомнит.</span></div>
      <div class="card reveal"><div class="ic">🎃</div><b>Две темы</b><span>Хэллоуин или классика: сайт переоденется целиком.</span></div>
    </div>
  </section>

  <section id="faq">
    <div class="faqhead">
      <div><span class="eyebrow reveal">Вопросы</span><h2 class="reveal" style="margin:14px 0 0">FAQ</h2></div>
      <input id="q" type="search" placeholder="Найти вопрос…" aria-label="Поиск по вопросам" autocomplete="off">
    </div>
    <div class="faqlist reveal" id="faqlist">
      <details class="qa" open><summary>Где идёт эфир?</summary><p>На VK Видео Live, на канале mraianasasn4yt. Смотреть можно прямо на этом сайте или по ссылке в VK Видео.</p></details>
      <details class="qa"><summary>Чем «Эфир» отличается от FM?</summary><p>Эфир — основная трансляция телеканала, FM — отдельный стрим. Переключай вкладки над телевизором или клавишами 1 и 2.</p></details>
      <details class="qa"><summary>Почему эфир открывается в новой вкладке?</summary><p>В этой версии страницы трансляция открывается в VK Видео: нажми кнопку на экране телевизора или «Открыть в VK Видео» под ним.</p></details>
      <details class="qa"><summary>Когда выходит эфир?</summary><p>[уточнить: расписание эфира и рубрики]</p></details>
      <details class="qa"><summary>Нужна ли регистрация, чтобы смотреть?</summary><p>Это зависит от настроек трансляции в VK Видео: [уточнить].</p></details>
      <details class="qa"><summary>Как слушать FM, не глядя на картинку?</summary><p>Включи вкладку FM и оставь страницу открытой. Картинка не обязательна, звук идёт сам.</p></details>
      <details class="qa"><summary>Что за фонарик, звук и летучие мыши?</summary><p>Это украшения сайта в хэллоуинском стиле. Кнопки лежат справа внизу, любые эффекты можно выключить, сайт запомнит выбор.</p></details>
      <details class="qa"><summary>Как связаться с командой канала?</summary><p>[уточнить: контакты]</p></details>
    </div>
    <p id="faqEmpty">Ничего не нашлось. Попробуй другое слово или посмотри вопросы выше.</p>
  </section>

  <section id="cta">
    <h2 class="reveal">Включайся.</h2>
    <p class="reveal">Эфир уже идёт. Если не боишься.</p>
    <div class="row reveal">
      <a class="btn" href="#live" data-watch="tv">▶ Смотреть эфир</a>
      <a class="btn ghost" href="#live" data-watch="fm">♪ Слушать FM</a>
    </div>
  </section>
</main>
<footer>© MrZen&amp;FM · неофициальный лендинг-концепт</footer>

<div id="dock" role="toolbar" aria-label="Колдовской пульт">
  <button id="bFx" class="on" data-tip="Эффекты" aria-label="Эффекты" aria-pressed="true">🦇</button>
  <button id="bSnd" data-tip="Звук ночи (M)" aria-label="Звук ночи" aria-pressed="false">🔊</button>
  <button id="bTorch" data-tip="Фонарик (L)" aria-label="Фонарик" aria-pressed="false">🔦</button>
  <button id="bTheme" data-tip="Тема" aria-label="Сменить тему">🎃</button>
  <button id="bBoo" data-tip="Бу! (B)" aria-label="Испугать">👻</button>
</div>
<div id="toast" role="status" aria-live="polite"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
<script>
(function () {
  /* ================= настройки ================= */
  var URLS = {
    tv: 'https://live.vkvideo.ru/mraianasasn4yt?c=1793077496',
    fm: 'https://live.vkvideo.ru/mraianasasn4yt/stream/sl_73965?c=1793328614'
  };
  /* Если у VK Видео есть код для вставки (video_ext.php?...), вставь сюда ссылку из src, и плеер станет чище. */
  var EMBED = { tv: '', fm: '' };

  var reduced = matchMedia('(prefers-reduced-motion: reduce)').matches;
  var root = document.documentElement;
  var isMobile = function () { return innerWidth < 860; };
  function $(s) { return document.querySelector(s); }
  function $$(s) { return Array.prototype.slice.call(document.querySelectorAll(s)); }
  function store(k, v) { try { if (v === undefined) return localStorage.getItem(k); localStorage.setItem(k, v); } catch (e) {} return null; }

  var PAL = { halloween: { tv: '#ff7a18', fm: '#b57bff' }, classic: { tv: '#b6ff3c', fm: '#ffb02e' } };
  var state = {
    mode: store('mz-mode') === 'fm' ? 'fm' : 'tv',
    theme: store('mz-theme') === 'classic' ? 'classic' : 'halloween',
    fx: store('mz-fx') !== '0' && !reduced,
    sound: false, torch: false, cinema: false
  };
  function accent() { return PAL[state.theme][state.mode]; }
  var onColors = function () {};   // хук для 3D

  /* ================= уведомление ================= */
  var toastT;
  function toast(msg) { var t = $('#toast'); t.textContent = msg; t.classList.add('show'); clearTimeout(toastT); toastT = setTimeout(function () { t.classList.remove('show'); }, 2400); }

  /* ================= тема, режим ================= */
  function applyLook() {
    root.setAttribute('data-look', state.theme);
    root.style.setProperty('--accent', accent());
    root.classList.toggle('nofx', !state.fx);
    $('#bFx').classList.toggle('on', state.fx); $('#bFx').setAttribute('aria-pressed', state.fx);
    onColors();
  }
  function setMode(m, silent) {
    state.mode = m; store('mz-mode', m);
    $$('.tabs button').forEach(function (b) { var on = b.dataset.mode === m; b.classList.toggle('on', on); b.setAttribute('aria-selected', on); });
    $('#pkind').textContent = m === 'fm' ? 'FM-трансляция' : 'Телеканал';
    $('#vkBtn').href = URLS[m]; $('#playBtn').href = URLS[m];
    if (loaded) pframe.src = srcFor(m);
    applyLook();
    if (!silent) toast(m === 'fm' ? 'Включён FM' : 'Включён Эфир');
  }
  $$('.tabs button').forEach(function (b) { b.addEventListener('click', function () { setMode(b.dataset.mode); }); });

  $('#bTheme').addEventListener('click', function () {
    state.theme = state.theme === 'halloween' ? 'classic' : 'halloween'; store('mz-theme', state.theme);
    $('#bTheme').textContent = state.theme === 'halloween' ? '🎃' : '🧪';
    applyLook(); toast(state.theme === 'halloween' ? 'Хэллоуин' : 'Классика');
  });
  $('#bFx').addEventListener('click', function () {
    state.fx = !state.fx; store('mz-fx', state.fx ? '1' : '0'); applyLook(); toast(state.fx ? 'Эффекты включены' : 'Эффекты выключены');
  });

  /* ================= плеер ================= */
  var pframe = {}, loaded = false;
  function srcFor(m) { return EMBED[m] || URLS[m]; }
  function loadPlayer() {}
      $$('[data-watch]').forEach(function (a) {
    a.addEventListener('click', function () { setMode(a.dataset.watch, true); setTimeout(loadPlayer, 450); });
  });

  function setCinema(on) {
    state.cinema = on; document.body.classList.toggle('cinema', on);
    $('#cinemaBtn').classList.toggle('on', on);
    if (on) $('#live').scrollIntoView({ behavior: reduced ? 'auto' : 'smooth', block: 'center' });
  }
  $('#cinemaBtn').addEventListener('click', function () { setCinema(!state.cinema); });
  $('#copyBtn').addEventListener('click', function () {
    var u = URLS[state.mode];
    if (navigator.clipboard && navigator.clipboard.writeText) navigator.clipboard.writeText(u).then(function () { toast('Ссылка скопирована'); }, function () { toast(u); });
    else toast(u);
  });

  /* ================= меню ================= */
  var nav = $('#nav'), burger = $('#burger');
  burger.addEventListener('click', function () { var o = nav.classList.toggle('open'); burger.setAttribute('aria-expanded', o); burger.textContent = o ? '✕' : '☰'; });
  $$('#nav a').forEach(function (a) { a.addEventListener('click', function () { nav.classList.remove('open'); burger.setAttribute('aria-expanded', 'false'); burger.textContent = '☰'; }); });

  var prog = $('#prog');
  function onScroll() { var h = document.documentElement.scrollHeight - innerHeight; prog.style.width = (h > 0 ? scrollY / h * 100 : 0) + '%'; }
  addEventListener('scroll', onScroll, { passive: true }); onScroll();

  if ('IntersectionObserver' in window) {
    var spy = new IntersectionObserver(function (es) {
      es.forEach(function (e) { if (e.isIntersecting) $$('#nav a').forEach(function (a) { a.classList.toggle('on', a.getAttribute('href') === '#' + e.target.id); }); });
    }, { rootMargin: '-45% 0px -50% 0px' });
    ['live', 'about', 'features', 'faq'].forEach(function (id) { spy.observe(document.getElementById(id)); });
    var rv = new IntersectionObserver(function (es) { es.forEach(function (e) { if (e.isIntersecting) { e.target.classList.add('in'); rv.unobserve(e.target); } }); }, { threshold: .12 });
    $$('.reveal').forEach(function (el) { rv.observe(el); });
  } else { $$('.reveal').forEach(function (el) { el.classList.add('in'); }); }

  /* ================= FAQ: поиск ================= */
  $('#q').addEventListener('input', function () {
    var v = this.value.trim().toLowerCase(), any = false;
    $$('.qa').forEach(function (d) { var ok = !v || d.textContent.toLowerCase().indexOf(v) > -1; d.style.display = ok ? '' : 'none'; if (ok) any = true; if (v && ok) d.open = true; });
    $('#faqEmpty').style.display = any ? 'none' : 'block';
  });

  /* ================= обратный отсчёт до Хэллоуина ================= */
  function tickCd() {
    var now = new Date(), y = now.getFullYear(), t = new Date(y, 9, 31, 0, 0, 0);
    var isDay = now.getMonth() === 9 && now.getDate() === 31;
    if (now >= new Date(y, 10, 1)) t = new Date(y + 1, 9, 31, 0, 0, 0);
    else if (isDay) t = now;
    var d = Math.max(0, t - now), s = Math.floor(d / 1000);
    $('#cd').textContent = Math.floor(s / 86400);
    $('#ch').textContent = ('0' + Math.floor(s % 86400 / 3600)).slice(-2);
    $('#cm').textContent = ('0' + Math.floor(s % 3600 / 60)).slice(-2);
    $('#cs').textContent = ('0' + s % 60).slice(-2);
    $('#cdLabel').textContent = isDay ? 'Сегодня Хэллоуин!' : 'До следующего Хэллоуина';
  }
  tickCd(); setInterval(tickCd, 1000);

  /* ================= фонарик ================= */
  function setTorch(on) { state.torch = on; document.body.classList.toggle('torch', on); $('#bTorch').classList.toggle('on', on); $('#bTorch').setAttribute('aria-pressed', on); if (on) toast('Фонарик включён'); }
  addEventListener('pointermove', function (e) { root.style.setProperty('--mx', e.clientX + 'px'); root.style.setProperty('--my', e.clientY + 'px'); }, { passive: true });
  $('#bTorch').addEventListener('click', function () { setTorch(!state.torch); });

  /* ================= звук ночи (WebAudio, только по кнопке) ================= */
  var ac, master, noiseBuf;
  function initAudio() {
    var AC = window.AudioContext || window.webkitAudioContext; if (!AC) return false;
    ac = new AC(); master = ac.createGain(); master.gain.value = 0; master.connect(ac.destination);
    [55, 55.8, 82.4].forEach(function (f, i) {
      var o = ac.createOscillator(), g = ac.createGain(), lp = ac.createBiquadFilter();
      o.type = 'sawtooth'; o.frequency.value = f; lp.type = 'lowpass'; lp.frequency.value = 220; g.gain.value = i === 2 ? .012 : .03;
      o.connect(lp); lp.connect(g); g.connect(master); o.start();
    });
    noiseBuf = ac.createBuffer(1, ac.sampleRate * 2, ac.sampleRate);
    var ch = noiseBuf.getChannelData(0); for (var i = 0; i < ch.length; i++) ch[i] = Math.random() * 2 - 1;
    var n = ac.createBufferSource(); n.buffer = noiseBuf; n.loop = true;
    var bp = ac.createBiquadFilter(); bp.type = 'bandpass'; bp.frequency.value = 500; bp.Q.value = 1.2;
    var wg = ac.createGain(); wg.gain.value = .05;
    var lfo = ac.createOscillator(), lg = ac.createGain(); lfo.frequency.value = .09; lg.gain.value = 260; lfo.connect(lg); lg.connect(bp.frequency); lfo.start();
    n.connect(bp); bp.connect(wg); wg.connect(master); n.start();
    return true;
  }
  function thunder() {
    if (!ac || !state.sound) return;
    var n = ac.createBufferSource(); n.buffer = noiseBuf; var lp = ac.createBiquadFilter(); lp.type = 'lowpass'; lp.frequency.value = 140;
    var g = ac.createGain(); g.gain.setValueAtTime(.0001, ac.currentTime); g.gain.exponentialRampToValueAtTime(.5, ac.currentTime + .05); g.gain.exponentialRampToValueAtTime(.0001, ac.currentTime + 2.2);
    n.connect(lp); lp.connect(g); g.connect(ac.destination); n.start(); n.stop(ac.currentTime + 2.3);
  }
  function setSound(on) {
    if (on && !ac && !initAudio()) { toast('Звук не поддерживается'); return; }
    state.sound = on; $('#bSnd').classList.toggle('on', on); $('#bSnd').setAttribute('aria-pressed', on);
    if (ac) { if (on) ac.resume(); master.gain.cancelScheduledValues(ac.currentTime); master.gain.linearRampToValueAtTime(on ? .55 : 0, ac.currentTime + 1.2); }
    toast(on ? 'Звук ночи включён' : 'Звук выключен');
  }
  $('#bSnd').addEventListener('click', function () { setSound(!state.sound); });

  /* ================= эффекты: летучие мыши и искры ================= */
  var fx = $('#fx'), fc = fx.getContext('2d'), bats = [], embers = [], FW = 0, FH = 0;
  function sizeFx() { FW = fx.width = innerWidth; FH = fx.height = innerHeight; }
  addEventListener('resize', sizeFx); sizeFx();
  function spawnBat(x, y) {
    var dir = Math.random() < .5 ? 1 : -1;
    bats.push({ x: x !== undefined ? x : (dir > 0 ? -40 : FW + 40), y: y !== undefined ? y : 60 + Math.random() * FH * .55,
      vx: dir * (1.4 + Math.random() * 2.2), vy: (Math.random() - .5) * .6, s: 11 + Math.random() * 14, ph: Math.random() * 6, dir: dir, w: Math.random() * 6 });
  }
  for (var i = 0; i < 45; i++) embers.push({ x: Math.random() * 2000, y: Math.random() * 1200, r: .6 + Math.random() * 1.8, v: .15 + Math.random() * .5, ph: Math.random() * 6 });
  function drawBat(b, t) {
    var fl = Math.sin(t * 11 + b.ph), s = b.s;
    fc.save(); fc.translate(b.x, b.y); fc.scale(b.dir, 1);
    fc.fillStyle = '#2b1744'; fc.strokeStyle = 'rgba(255,140,40,.45)'; fc.lineWidth = 1;
    for (var k = 0; k < 2; k++) {
      fc.save(); if (k) fc.scale(-1, 1);
      fc.beginPath(); fc.moveTo(2, 0);
      fc.quadraticCurveTo(s * .5, -s * (.9 * fl + .3), s * 1.15, -s * .35 * fl);
      fc.quadraticCurveTo(s * .85, s * .1, s * .62, s * .02);
      fc.quadraticCurveTo(s * .4, s * .3, s * .22, s * .08);
      fc.quadraticCurveTo(s * .1, s * .3, 0, s * .22);
      fc.closePath(); fc.fill(); fc.stroke(); fc.restore();
    }
    fc.beginPath(); fc.ellipse(0, s * .08, s * .13, s * .24, 0, 0, 7); fc.fill();
    fc.beginPath(); fc.moveTo(-s * .1, -s * .1); fc.lineTo(-s * .06, -s * .3); fc.lineTo(0, -s * .14); fc.lineTo(s * .06, -s * .3); fc.lineTo(s * .1, -s * .1); fc.fill();
    fc.fillStyle = '#ff8a2a'; fc.fillRect(-s * .07, -s * .06, 2, 2); fc.fillRect(s * .04, -s * .06, 2, 2);
    fc.restore();
  }
  var nextBat = 1500, lastF = 0;
  function fxLoop(ts) {
    requestAnimationFrame(fxLoop);
    if (document.hidden) return;
    var dt = Math.min(50, ts - lastF); lastF = ts;
    fc.clearRect(0, 0, FW, FH);
    if (!state.fx) return;
    var t = ts / 1000;
    nextBat -= dt; if (nextBat <= 0 && bats.length < 7) { spawnBat(); nextBat = 3500 + Math.random() * 4500; }
    var col = accent();
    embers.forEach(function (e) {
      e.y -= e.v * dt * .06; e.x += Math.sin(t + e.ph) * .25;
      if (e.y < -10) { e.y = FH + 10; e.x = Math.random() * FW; }
      fc.globalAlpha = .25 + .35 * Math.abs(Math.sin(t * 1.5 + e.ph)); fc.fillStyle = col; fc.beginPath(); fc.arc(e.x % FW, e.y % FH, e.r, 0, 7); fc.fill();
    });
    fc.globalAlpha = 1;
    for (var i = bats.length - 1; i >= 0; i--) {
      var b = bats[i]; b.x += b.vx * dt * .06 * 1.6; b.w += dt * .004; b.y += Math.sin(b.w * 2 + b.ph) * .8 + b.vy;
      if (b.x < -80 || b.x > FW + 80 || b.y < -80 || b.y > FH + 80) { bats.splice(i, 1); continue; }
      drawBat(b, t);
    }
  }
  requestAnimationFrame(fxLoop);

  /* ================= Бу! ================= */
  function boo() {
    if (reduced) { toast('Бу!'); return; }
    var f = $('#flash'); f.classList.remove('go'); void f.offsetWidth; f.classList.add('go');
    root.classList.add('shake'); setTimeout(function () { root.classList.remove('shake'); }, 520);
    if (state.fx) for (var i = 0; i < 12; i++) spawnBat(FW / 2 + (Math.random() - .5) * 200, FH * .6 + Math.random() * 80);
    thunder(); toast('Бу!');
  }
  $('#bBoo').addEventListener('click', boo);
  setInterval(function () { if (state.fx && !state.cinema && !document.hidden && Math.random() < .3) { var f = $('#flash'); f.classList.remove('go'); void f.offsetWidth; f.classList.add('go'); thunder(); } }, 50000);

  /* ================= горячие клавиши ================= */
  addEventListener('keydown', function (e) {
    var tg = e.target && e.target.tagName; if (tg === 'INPUT' || tg === 'TEXTAREA' || e.ctrlKey || e.metaKey || e.altKey) return;
    var k = e.key.toLowerCase();
    if (k === '1') setMode('tv'); else if (k === '2') setMode('fm');
    else if (k === 'c' || k === 'с') setCinema(!state.cinema);
    else if (k === 'm' || k === 'ь') setSound(!state.sound);
    else if (k === 'l' || k === 'д') setTorch(!state.torch);
    else if (k === 'b' || k === 'и') boo();
    else if (k === 'escape') { if (state.cinema) setCinema(false); if (state.torch) setTorch(false); }
  });

  $('#bTheme').textContent = state.theme === 'halloween' ? '🎃' : '🧪';
  setMode(state.mode, true);

  /* ================= 3D ================= */
  function webgl() { try { var c = document.createElement('canvas'); return !!(c.getContext('webgl') || c.getContext('experimental-webgl')); } catch (e) { return false; } }
  var hasGsap = typeof gsap !== 'undefined' && typeof ScrollTrigger !== 'undefined';
  if (typeof THREE === 'undefined' || !hasGsap || !webgl()) { root.classList.add('no-webgl'); return; }
  try { init3d(); } catch (e) { console.error(e); root.classList.add('no-webgl'); }

  function init3d() {
    gsap.registerPlugin(ScrollTrigger);
    var canvas = $('#gl');
    var renderer = new THREE.WebGLRenderer({ canvas: canvas, antialias: !isMobile(), alpha: true });
    renderer.setPixelRatio(Math.min(devicePixelRatio, isMobile() ? 1.5 : 2));
    renderer.outputEncoding = THREE.sRGBEncoding;
    renderer.toneMapping = THREE.ACESFilmicToneMapping; renderer.toneMappingExposure = 1.1;
    renderer.shadowMap.enabled = !isMobile(); renderer.shadowMap.type = THREE.PCFSoftShadowMap;

    var scene = new THREE.Scene();
    var camera = new THREE.PerspectiveCamera(35, 1, 0.1, 60); camera.position.set(0, 0.2, 7);

    var envScene = new THREE.Scene();
    envScene.add(new THREE.Mesh(new THREE.BoxGeometry(20, 20, 20), new THREE.MeshBasicMaterial({ color: 0x150c20, side: THREE.BackSide })));
    function softbox(w, h, x, y, z, col) { var m = new THREE.Mesh(new THREE.PlaneGeometry(w, h), new THREE.MeshBasicMaterial({ color: col, side: THREE.DoubleSide })); m.position.set(x, y, z); m.lookAt(0, 0, 0); envScene.add(m); }
    softbox(8, 5, 6, 6, 6, 0xffe0c0); softbox(5, 8, -9, 2, 2, 0x8a5cff); softbox(10, 2, 0, 9, -3, 0xffb070); softbox(6, 3, 0, -3, 9, 0x4a3a66);
    var pmrem = new THREE.PMREMGenerator(renderer);
    scene.environment = pmrem.fromScene(envScene, 0.02).texture;

    var key = new THREE.DirectionalLight(0xffd2a8, 1.5); key.position.set(4, 5, 5); key.castShadow = !isMobile();
    key.shadow.mapSize.set(1024, 1024); key.shadow.radius = 8; key.shadow.bias = -0.0005;
    var sc2 = key.shadow.camera; sc2.left = -5; sc2.right = 5; sc2.top = 5; sc2.bottom = -5; sc2.near = 1; sc2.far = 20; scene.add(key);
    var fill = new THREE.DirectionalLight(0x8f7bff, 0.8); fill.position.set(-5, 1.5, 3); scene.add(fill);
    var rim = new THREE.PointLight(0xb88cff, 1.6, 25); rim.position.set(-2, 3, -4); scene.add(rim);

    /* экран */
    var SW = 1024, SH = 576, sc = document.createElement('canvas'); sc.width = SW; sc.height = SH;
    var ctx = sc.getContext('2d');
    var tex = new THREE.CanvasTexture(sc); tex.encoding = THREE.sRGBEncoding; tex.anisotropy = 4;
    var FONT = '"Rubik", ui-sans-serif, system-ui, Arial, sans-serif';
    var BARS = { halloween: ['#ff7a18', '#b57bff', '#3a1d5c', '#ffcf5a', '#7a2bd1', '#ff4d2e', '#241238'], classic: ['#d0d0d0', '#d0d000', '#00d0d0', '#00d000', '#d000d0', '#d00000', '#0000d0'] };
    function pumpkinIcon(x, y, r, col) {
      ctx.fillStyle = col; ctx.beginPath(); ctx.ellipse(x, y, r * 1.15, r, 0, 0, 7); ctx.fill();
      ctx.fillStyle = '#1a0a10';
      ctx.beginPath(); ctx.moveTo(x - r * .6, y - r * .1); ctx.lineTo(x - r * .2, y - r * .1); ctx.lineTo(x - r * .4, y - r * .5); ctx.fill();
      ctx.beginPath(); ctx.moveTo(x + r * .2, y - r * .1); ctx.lineTo(x + r * .6, y - r * .1); ctx.lineTo(x + r * .4, y - r * .5); ctx.fill();
      ctx.beginPath(); ctx.moveTo(x - r * .6, y + r * .25); ctx.lineTo(x - r * .3, y + r * .5); ctx.lineTo(x - r * .1, y + r * .3); ctx.lineTo(x + r * .1, y + r * .5); ctx.lineTo(x + r * .3, y + r * .3); ctx.lineTo(x + r * .6, y + r * .25); ctx.lineTo(x, y + r * .15); ctx.fill();
      ctx.fillStyle = '#3d6a1c'; ctx.fillRect(x - 4, y - r - 12, 8, 14);
    }
    function drawScreen(t) {
      var acc = accent(), i;
      ctx.globalAlpha = 1; ctx.fillStyle = '#05030a'; ctx.fillRect(0, 0, SW, SH);
      if (state.mode === 'tv') {
        var bh = SH * 0.6, bars = BARS[state.theme];
        for (i = 0; i < 7; i++) { ctx.globalAlpha = .32 + .07 * Math.sin(t * 1.6 + i); ctx.fillStyle = bars[i]; ctx.fillRect(i * SW / 7, 0, SW / 7 + 1, bh); }
        ctx.globalAlpha = 1;
        var g = ctx.createLinearGradient(0, bh - 120, 0, bh + 40); g.addColorStop(0, 'rgba(5,3,10,0)'); g.addColorStop(1, 'rgba(5,3,10,.95)');
        ctx.fillStyle = g; ctx.fillRect(0, bh - 120, SW, 160);
        ctx.textAlign = 'center'; ctx.fillStyle = '#fff'; ctx.font = '800 124px ' + FONT; ctx.fillText('MrZen&FM', SW / 2, SH * .6);
        ctx.fillStyle = acc; ctx.font = '800 70px ' + FONT; ctx.fillText('ЭФИР', SW / 2, SH * .86);
        ctx.textAlign = 'left';
        ctx.fillStyle = Math.sin(t * 4) > -0.3 ? '#ff3b3b' : '#601818'; ctx.beginPath(); ctx.arc(64, 60, 13, 0, 7); ctx.fill();
        ctx.fillStyle = '#fff'; ctx.font = '800 32px ' + FONT; ctx.fillText('LIVE', 90, 72);
        if (state.theme === 'halloween') pumpkinIcon(SW - 90, 80, 38 + Math.sin(t * 3) * 2, '#ff7a18');
      } else {
        var n = 34, bw = SW / n;
        for (i = 0; i < n; i++) {
          var v = .5 + .5 * Math.sin(t * 2.4 + i * .55) * Math.sin(t * 1.3 + i * .21), h = 30 + v * 260;
          var gg = ctx.createLinearGradient(0, SH * .72 - h, 0, SH * .72); gg.addColorStop(0, acc); gg.addColorStop(1, 'rgba(120,60,200,.15)');
          ctx.fillStyle = gg; ctx.fillRect(i * bw + 4, SH * .72 - h, bw - 8, h);
        }
        ctx.textAlign = 'left'; ctx.fillStyle = '#fff'; ctx.font = '800 110px ' + FONT; ctx.fillText('FM', 56, 125);
        ctx.fillStyle = '#a99bc0'; ctx.font = '600 30px ' + FONT; ctx.fillText('MrZen&FM', 60, 168);
        ctx.lineWidth = 2; ctx.strokeStyle = '#4a4058';
        for (i = 0; i <= 40; i++) { var x = 60 + i * (SW - 120) / 40; ctx.beginPath(); ctx.moveTo(x, SH * .85); ctx.lineTo(x, SH * (i % 5 ? .88 : .92)); ctx.stroke(); }
        var nx = 60 + (SW - 120) * (.5 + .38 * Math.sin(t * .6));
        ctx.strokeStyle = acc; ctx.lineWidth = 5; ctx.beginPath(); ctx.moveTo(nx, SH * .82); ctx.lineTo(nx, SH * .95); ctx.stroke();
        if (state.theme === 'halloween') pumpkinIcon(SW - 90, 80, 38, '#b57bff');
      }
      ctx.fillStyle = 'rgba(0,0,0,.15)'; for (var y = 0; y < SH; y += 4) ctx.fillRect(0, y, SW, 1.5);
      var vg = ctx.createRadialGradient(SW / 2, SH / 2, SH * .35, SW / 2, SH / 2, SW * .62);
      vg.addColorStop(0, 'rgba(0,0,0,0)'); vg.addColorStop(1, 'rgba(0,0,0,.55)'); ctx.fillStyle = vg; ctx.fillRect(0, 0, SW, SH);
      tex.needsUpdate = true;
    }
    drawScreen(0);

    function rbox(w, h, d, r, b) {
      var iw = w - 2 * b, ih = h - 2 * b, rr = Math.max(r - b, 0.001), x = -iw / 2, y = -ih / 2, s = new THREE.Shape();
      s.moveTo(x + rr, y); s.lineTo(x + iw - rr, y); s.quadraticCurveTo(x + iw, y, x + iw, y + rr);
      s.lineTo(x + iw, y + ih - rr); s.quadraticCurveTo(x + iw, y + ih, x + iw - rr, y + ih);
      s.lineTo(x + rr, y + ih); s.quadraticCurveTo(x, y + ih, x, y + ih - rr);
      s.lineTo(x, y + rr); s.quadraticCurveTo(x, y, x + rr, y);
      var g = new THREE.ExtrudeGeometry(s, { depth: d - 2 * b, bevelEnabled: true, bevelThickness: b, bevelSize: b, bevelSegments: 5, curveSegments: 14 });
      g.center(); return g;
    }

    var tv = new THREE.Group(), stage = new THREE.Group(); stage.add(tv); scene.add(stage);
    var plastic = new THREE.MeshPhysicalMaterial({ color: 0x1d1626, metalness: .4, roughness: .35, clearcoat: .9, clearcoatRoughness: .2 });
    var metal = new THREE.MeshPhysicalMaterial({ color: 0xb9b0c8, metalness: 1, roughness: .25 });
    var led = new THREE.MeshStandardMaterial({ color: 0xff7a18, emissive: 0xff7a18, emissiveIntensity: 2.5 });
    var stripe = new THREE.MeshStandardMaterial({ color: 0xff7a18, emissive: 0xff7a18, emissiveIntensity: .8, roughness: .4 });

    var body = new THREE.Mesh(rbox(3.4, 2.0, 0.9, 0.3, 0.1), plastic); body.position.y = 0.5; body.castShadow = true; tv.add(body);
    var bezel = new THREE.Mesh(new THREE.PlaneGeometry(2.92, 1.7), new THREE.MeshPhysicalMaterial({ color: 0x020204, roughness: .1, metalness: .3, clearcoat: 1 }));
    bezel.position.set(-0.15, 0.5, 0.455); tv.add(bezel);
    var screen = new THREE.Mesh(new THREE.PlaneGeometry(2.8, 1.575), new THREE.MeshBasicMaterial({ map: tex, toneMapped: false }));
    screen.position.set(-0.15, 0.5, 0.458); tv.add(screen);
    var plate = new THREE.Mesh(new THREE.BoxGeometry(0.9, 0.025, 0.01), stripe); plate.position.set(-0.15, -0.28, 0.455); tv.add(plate);
    [0.95, 0.4].forEach(function (y) {
      var k = new THREE.Mesh(new THREE.CylinderGeometry(0.12, 0.13, 0.12, 40), metal); k.rotation.x = Math.PI / 2; k.position.set(1.5, y, 0.5); tv.add(k);
      var m = new THREE.Mesh(new THREE.BoxGeometry(0.02, 0.1, 0.01), plastic); m.position.set(1.5, y + .02, 0.565); tv.add(m);
    });
    var ledM = new THREE.Mesh(new THREE.SphereGeometry(0.05, 16, 16), led); ledM.position.set(1.5, -0.1, 0.46); tv.add(ledM);
    for (var i = 0; i < 4; i++) { var sp = new THREE.Mesh(new THREE.BoxGeometry(0.28, 0.018, 0.02), metal); sp.position.set(1.5, -0.35 - i * 0.075, 0.455); tv.add(sp); }
    [-1, 1].forEach(function (s) {
      var a = 0.5, rod = new THREE.Mesh(new THREE.CylinderGeometry(0.022, 0.022, 1.4, 12), metal);
      rod.position.set(s * (0.1 + Math.sin(a) * 0.7), 1.5 + Math.cos(a) * 0.7, 0); rod.rotation.z = -s * a; rod.castShadow = true; tv.add(rod);
      var tip = new THREE.Mesh(new THREE.SphereGeometry(0.055, 16, 16), metal); tip.position.set(s * (0.1 + Math.sin(a) * 1.4), 1.5 + Math.cos(a) * 1.4, 0); tv.add(tip);
    });
    var dome = new THREE.Mesh(new THREE.CylinderGeometry(0.28, 0.34, 0.12, 32), metal); dome.position.set(0, 1.55, 0); tv.add(dome);
    var neck = new THREE.Mesh(new THREE.CylinderGeometry(0.16, 0.2, 0.6, 24), plastic); neck.position.y = -0.8; neck.castShadow = true; tv.add(neck);
    var base = new THREE.Mesh(new THREE.BoxGeometry(1.8, 0.12, 0.9), metal); base.position.y = -1.14; base.castShadow = true; tv.add(base);

    /* тыква с огоньком */
    var pump = new THREE.Group();
    var pm = new THREE.MeshStandardMaterial({ color: 0xff6a10, roughness: .55, metalness: .05, emissive: 0x3a1200, emissiveIntensity: .7 });
    var core = new THREE.Mesh(new THREE.SphereGeometry(.34, 24, 18), pm); core.scale.set(1, .82, 1); pump.add(core);
    for (var li = 0; li < 6; li++) {
      var an = li / 6 * Math.PI * 2, lobe = new THREE.Mesh(new THREE.SphereGeometry(.3, 20, 16), pm);
      lobe.scale.set(.62, .84, .62); lobe.position.set(Math.sin(an) * .21, 0, Math.cos(an) * .21); pump.add(lobe);
    }
    var stem = new THREE.Mesh(new THREE.CylinderGeometry(.04, .06, .2, 10), new THREE.MeshStandardMaterial({ color: 0x4a5a1c, roughness: .8 }));
    stem.position.set(0, .3, 0); stem.rotation.z = .3; pump.add(stem);
    var glowMat = new THREE.MeshBasicMaterial({ color: 0xffd36a, side: THREE.DoubleSide });
    function tri(x, y, w, h) { var sh = new THREE.Shape(); sh.moveTo(-w, 0); sh.lineTo(w, 0); sh.lineTo(0, h); var m = new THREE.Mesh(new THREE.ShapeGeometry(sh), glowMat); m.position.set(x, y, .445); pump.add(m); }
    tri(-.15, .06, .07, .13); tri(.15, .06, .07, .13);
    var mouth = new THREE.Shape(); mouth.moveTo(-.2, -.06); mouth.lineTo(-.1, -.14); mouth.lineTo(-.04, -.07); mouth.lineTo(.04, -.14); mouth.lineTo(.1, -.07); mouth.lineTo(.2, -.06); mouth.lineTo(0, -.02);
    var mm = new THREE.Mesh(new THREE.ShapeGeometry(mouth), glowMat); mm.position.set(0, -.02, .445); pump.add(mm);
    var pl = new THREE.PointLight(0xff7a18, 1.6, 4.5); pl.position.set(0, .1, .8); pump.add(pl);
    pump.position.set(2.25, -1.2 + .3, .9); tv.add(pump);

    /* пол и тень */
    var floor = new THREE.Mesh(new THREE.PlaneGeometry(30, 30), new THREE.ShadowMaterial({ opacity: .5 }));
    floor.rotation.x = -Math.PI / 2; floor.position.y = -1.2; floor.receiveShadow = true; stage.add(floor);
    var bc = document.createElement('canvas'); bc.width = bc.height = 128;
    var bx = bc.getContext('2d'), bg = bx.createRadialGradient(64, 64, 0, 64, 64, 64);
    bg.addColorStop(0, 'rgba(0,0,0,.6)'); bg.addColorStop(1, 'rgba(0,0,0,0)'); bx.fillStyle = bg; bx.fillRect(0, 0, 128, 128);
    var blob = new THREE.Mesh(new THREE.PlaneGeometry(4.8, 2.5), new THREE.MeshBasicMaterial({ map: new THREE.CanvasTexture(bc), transparent: true, depthWrite: false }));
    blob.rotation.x = -Math.PI / 2; blob.position.y = -1.19; stage.add(blob);
    var glow = new THREE.PointLight(0xff7a18, 2.2, 9); glow.position.set(-0.15, 0.5, 2.3); tv.add(glow);

    /* зрители */
    var crowd = new THREE.Group(); stage.add(crowd);
    var crowdMat = new THREE.MeshStandardMaterial({ color: 0x0c0714, roughness: .55, metalness: .1 });
    var headMat = new THREE.MeshStandardMaterial({ color: 0x140c1e, roughness: .5, metalness: .1 });
    var hatMat = new THREE.MeshStandardMaterial({ color: 0x1b0e2b, roughness: .6 });
    var hpMat = new THREE.MeshStandardMaterial({ color: 0xb57bff, emissive: 0xb57bff, emissiveIntensity: .8, roughness: .4 });
    var people = [];
    function person(x, z, h, phase, hat) {
      var g = new THREE.Group();
      var bd = new THREE.Mesh(new THREE.SphereGeometry(.2, 20, 14), crowdMat); bd.scale.set(1.15, .9, .8); bd.position.y = .22; g.add(bd);
      var nk = new THREE.Mesh(new THREE.CylinderGeometry(.05, .06, .14, 12), crowdMat); nk.position.y = .4; g.add(nk);
      var hd = new THREE.Mesh(new THREE.SphereGeometry(.13, 20, 16), headMat); hd.position.y = .56; g.add(hd);
      if (hat) {
        var brim = new THREE.Mesh(new THREE.CylinderGeometry(.2, .2, .015, 20), hatMat); brim.position.y = .1; hd.add(brim);
        var cone = new THREE.Mesh(new THREE.ConeGeometry(.12, .3, 16), hatMat); cone.position.y = .25; cone.rotation.z = .12; hd.add(cone);
      }
      var hp = new THREE.Group();
      var band = new THREE.Mesh(new THREE.TorusGeometry(.15, .018, 8, 28, Math.PI), hpMat); band.position.y = .56; hp.add(band);
      [-1, 1].forEach(function (s) { var c = new THREE.Mesh(new THREE.SphereGeometry(.05, 12, 10), hpMat); c.scale.set(.6, 1, 1); c.position.set(s * .15, .56, 0); hp.add(c); });
      hp.visible = false; g.add(hp);
      g.position.set(x, -1.2, z); g.scale.setScalar(h); crowd.add(g);
      people.push({ g: g, head: hd, hp: hp, base: -1.2, phase: phase });
    }
    [-2.0, -1.0, 0, 1.0, 2.0].forEach(function (x, i) { person(x, 2.7, .95 + (i % 3) * .07, i * 1.3, i % 2 === 0); });
    [-1.5, -.5, .5, 1.5].forEach(function (x, i) { person(x, 3.5, 1.0 + (i % 2) * .1, i * 2.1 + .7, i % 2 === 1); });
    var pulse = 0;
    function animateCrowd(t, dt, idl) {
      pulse = Math.max(0, pulse - dt * 1.1);
      people.forEach(function (p) {
        p.g.position.y = p.base + (Math.sin(t * 1.6 + p.phase) * .012 + pulse * .1 * Math.abs(Math.sin(t * 9 + p.phase))) * idl;
        p.head.rotation.y = Math.sin(t * .5 + p.phase) * .25 * idl;
      });
    }

    /* цвета под режим и тему */
    var clock = new THREE.Clock();
    onColors = function () {
      var c = accent();
      led.color.set(c); led.emissive.set(c); stripe.color.set(c); stripe.emissive.set(c); glow.color.set(c); hpMat.color.set(PAL[state.theme].fm); hpMat.emissive.set(PAL[state.theme].fm);
      people.forEach(function (p) { p.hp.visible = state.mode === 'fm'; });
      pulse = 1; drawScreen(clock.getElapsedTime());
    };
    onColors();

    /* позы под скролл */
    var st = { x: 0, y: 0, z: 0, rx: 0, ry: 0, s: 1 };
    var poses = [
      { x: 1.7, y: .55, z: -.6, rx: 0, ry: -.25, s: .9 },
      { x: 1.6, y: 0, z: 0, rx: .05, ry: -.7, s: 1 },
      { x: -1.6, y: .1, z: .3, rx: -.05, ry: .7, s: 1 },
      { x: 0, y: .1, z: 1.5, rx: 0, ry: 0, s: 1 },
      { x: 2.4, y: .9, z: -3.2, rx: .05, ry: -.5, s: .7 }
    ];
    for (var k in poses[0]) st[k] = poses[0][k];
    var tl = gsap.timeline({ defaults: { ease: 'none', duration: 1 }, scrollTrigger: { trigger: '#hero', start: 'top top', endTrigger: '#live', end: 'top 60%', scrub: reduced ? true : 1 } });
    poses.slice(1).forEach(function (p) { tl.to(st, p); });

    var ptr = { x: 0, y: 0 }, ps = { x: 0, y: 0 };
    addEventListener('pointermove', function (e) { ptr.x = (e.clientX / innerWidth - .5) * 2; ptr.y = (e.clientY / innerHeight - .5) * 2; }, { passive: true });

    var fit = 1;
    function resize() {
      var w = innerWidth, h = innerHeight; renderer.setSize(w, h, false); camera.aspect = w / h; camera.updateProjectionMatrix();
      var visH = 2 * 7 * Math.tan(THREE.MathUtils.degToRad(camera.fov / 2)); fit = Math.min(1, (camera.aspect * visH * 0.82) / 3.8);
    }
    addEventListener('resize', resize); resize();

    var last = 0, lastT = 0;
    function frame() {
      requestAnimationFrame(frame);
      if (document.hidden) return;
      var t = clock.getElapsedTime(), mob = isMobile(), kx = mob ? 0 : 1, id = reduced ? 0 : 1;
      var dt = Math.min(.05, t - lastT); lastT = t;
      animateCrowd(t, dt, id); crowd.position.z = -st.z * (mob ? .5 : 1);
      pl.intensity = 1.5 + (Math.sin(t * 17) * .15 + Math.sin(t * 7.3) * .2) * id;
      ps.x += (ptr.x - ps.x) * .06; ps.y += (ptr.y - ps.y) * .06;
      stage.position.set(st.x * kx, st.y + (mob ? .55 : 0) + Math.sin(t * .8) * .04 * id, st.z * (mob ? .5 : 1));
      stage.rotation.x = st.rx + ps.y * .08 * id;
      stage.rotation.y = st.ry + ps.x * .14 * id + Math.sin(t * .35) * .08 * id;
      stage.scale.setScalar(st.s * fit * (mob ? .95 : 1));
      if (!reduced && t - last > 1 / 30) { last = t; drawScreen(t); }
      renderer.render(scene, camera);
    }
    frame();
  }
})();
</script>

</body></html>

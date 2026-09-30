<!-- Bryan Antoine · VHS Case File Profile · Monarch Labs -->

<div class="vhs-root">

<style>
.vhs-root{--paper:#e7d9b7;--paper3:#f5eacb;--ink:#231812;--muted:#6b5842;--line:#b5a072;--red:#90221c;--red2:#d64b37;--cream:#fff0cf;--black:#070504;--dark:#0b0806;--tape:#bda668;font-family:"Courier New",monospace;color:var(--ink);max-width:920px;margin:0 auto}
.vhs-root *{box-sizing:border-box}
.vhs-shell{margin:12px 0;padding:14px;background:repeating-linear-gradient(0deg,var(--dark) 0,var(--dark) 2px,#000 3px,#18110d 4px);border:1px solid var(--red2);outline:2px dashed #5b1511;outline-offset:-6px;position:relative}
.vhs-shell:after{content:"PLAY ▸ MONARCH_LABS";position:absolute;bottom:8px;right:14px;color:var(--red2);font-size:8px;letter-spacing:3px;opacity:.85}
.vhs-grid{display:table;width:100%;border-collapse:separate;border-spacing:10px}
.vhs-side,.vhs-main{display:table-cell;vertical-align:top}
.vhs-side{width:260px;background:radial-gradient(circle at 50% 10%,rgba(180,28,22,.25),transparent 40%),var(--dark);border:1px solid #5b1511;padding:14px;color:var(--cream)}
.vhs-main{background:var(--black);border:1px solid #5b1511;padding:8px;box-shadow:inset 0 0 0 1px #79613f,0 0 18px rgba(0,0,0,.7)}
.vhs-hero{background:var(--paper3);padding:8px 8px 22px;border:1px solid var(--cream);transform:rotate(-2deg);margin-bottom:10px;position:relative;box-shadow:6px 6px 0 rgba(0,0,0,.15)}
.vhs-hero:before{content:"";position:absolute;top:-10px;left:50px;width:90px;height:18px;background:var(--tape);transform:rotate(4deg);opacity:.9}
.vhs-hero img{width:100%;height:220px;object-fit:cover;display:block;border:1px solid #79613f;filter:contrast(1.2) brightness(.82) sepia(.15)}
.vhs-rec{position:absolute;left:12px;bottom:6px;font-size:8px;color:var(--red2);letter-spacing:2px;font-weight:bold}
.vhs-name{font-family:Impact,"Arial Black",sans-serif;font-size:38px;line-height:.85;color:var(--red2);text-transform:uppercase;transform:rotate(-3deg);text-shadow:3px 3px 0 #000,4px 4px 0 #5b1511;margin:8px 0}
.vhs-sub{font-size:9px;letter-spacing:3px;text-transform:uppercase;border-top:1px solid #79613f;border-bottom:1px solid #79613f;padding:6px 0}
.vhs-deck{margin-top:14px;border:1px solid #5b1511;background:#000;padding:10px;font-size:9px;line-height:1.45}
.vhs-deck b{color:var(--red2);display:block;font-family:Impact,sans-serif;font-size:18px;margin-bottom:4px}
.vhs-nav{margin:0 0 8px;padding:0 6px}
.vhs-nav a{display:inline-block;margin:2px 3px 2px 0;padding:6px 10px;background:linear-gradient(180deg,#18110d,#000);color:var(--cream);border:1px solid #5b1511;font-size:9px;font-weight:bold;text-transform:uppercase;text-decoration:none;transform:skew(-6deg)}
.vhs-nav a:hover,.vhs-nav a:focus{background:linear-gradient(180deg,var(--red2),var(--red));color:var(--cream)}
.vhs-paper{background:linear-gradient(90deg,#d0bd91 0,var(--paper) 8%,var(--paper3) 35%,var(--paper) 100%);border:1px solid #5b1511;padding:16px 16px 20px 42px;position:relative;box-shadow:inset 12px 0 0 #d0bd91}
.vhs-paper:before{content:"";position:absolute;left:28px;top:0;bottom:0;width:2px;background:var(--red);opacity:.45}
.vhs-h2{display:inline-block;margin:0 0 12px;background:linear-gradient(90deg,#5b1511,var(--red),var(--red2));color:var(--cream);font-family:Impact,sans-serif;font-size:28px;letter-spacing:2px;text-transform:uppercase;padding:5px 16px 7px;transform:rotate(-1deg);border:1px solid var(--cream);box-shadow:4px 4px 0 #000}
.vhs-stamp{float:right;color:var(--red);border:1px solid var(--red);background:var(--paper3);padding:4px 10px;font-family:Impact,sans-serif;font-size:13px;letter-spacing:1px;text-transform:uppercase;transform:rotate(4deg);opacity:.8}
.vhs-card{background:linear-gradient(135deg,var(--paper3),var(--paper));border:1px solid #79613f;padding:12px;margin:10px 0;box-shadow:5px 5px 0 rgba(0,0,0,.12);position:relative}
.vhs-card:before{content:"";position:absolute;top:-8px;left:34px;width:76px;height:16px;background:var(--tape);transform:rotate(-3deg)}
.vhs-label{display:inline-block;background:#000;color:var(--cream);padding:3px 8px;font-size:9px;letter-spacing:2px;text-transform:uppercase;margin-bottom:8px}
.vhs-profile li{display:grid;grid-template-columns:78px 1fr;gap:6px;padding:4px 0;border-bottom:1px solid var(--line);font-size:11px;list-style:none;margin:0}
.vhs-profile b{color:var(--red);font-size:10px;text-transform:uppercase}
.vhs-profile ul{padding:0;margin:0}
.vhs-words{display:grid;grid-template-columns:repeat(3,1fr);gap:6px;margin-top:8px}
.vhs-word{background:#000;color:var(--cream);font-family:Impact,sans-serif;font-size:14px;text-align:center;padding:18px 6px;border:1px solid #5b1511;text-transform:uppercase;line-height:1.05}
.vhs-file{display:grid;grid-template-columns:1fr;gap:10px}
.vhs-case{border-left:4px solid var(--red);padding:10px 10px 10px 12px;background:linear-gradient(135deg,var(--paper3),var(--paper));border:1px solid #79613f;box-shadow:5px 5px 0 rgba(0,0,0,.1)}
.vhs-case h4{margin:0 0 4px;font-family:Impact,sans-serif;color:var(--red);font-size:16px;text-transform:uppercase;letter-spacing:1px}
.vhs-tag{display:inline-block;background:#000;color:var(--cream);font-size:8px;padding:3px 7px;letter-spacing:2px;text-transform:uppercase;margin-bottom:6px}
.vhs-bar{height:9px;border:1px solid #5b1511;background:#000;margin:4px 0 10px;padding:1px}
.vhs-fill{height:100%;background:linear-gradient(90deg,#5b1511,var(--red),var(--red2))}
.vhs-row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.vhs-poster{border:1px solid #79613f;padding:10px;background:linear-gradient(135deg,var(--paper3),var(--paper));box-shadow:4px 4px 0 rgba(0,0,0,.12);text-decoration:none;color:var(--ink);display:block}
.vhs-poster:hover{transform:translateY(-2px);box-shadow:0 0 12px rgba(180,30,22,.35)}
.vhs-poster strong{font-family:Impact,sans-serif;color:var(--red);font-size:16px;text-transform:uppercase;display:block}
.vhs-poster span{font-size:9px;letter-spacing:1px;text-transform:uppercase;color:var(--muted)}
.vhs-links{margin:10px 0;text-align:center}
.vhs-links a{margin:3px}
.vhs-foot{text-align:center;font-size:8px;letter-spacing:2px;color:var(--red2);text-transform:uppercase;margin-top:12px}
@media(max-width:720px){.vhs-grid,.vhs-side,.vhs-main{display:block;width:100%!important}.vhs-row{grid-template-columns:1fr}}
</style>

<div class="vhs-shell">
<div class="vhs-grid">

<div class="vhs-side">
<div class="vhs-hero">
<img src="https://www.monarch-labs.com/headshot-bryan.PNG" alt="Bryan Antoine"/>
<div class="vhs-rec">REC ● BRYAN_CAM</div>
</div>
<div class="vhs-name">Bryan<br/>Antoine</div>
<div class="vhs-sub">Producer · Engineer · Monarch</div>
<div class="vhs-deck">
<b>SESSION LOG</b>
Platinum producer & recording engineer.<br/>
Full-stack / backend · iOS · Android · Web · APIs · JUCE DSP · AI products.<br/>
Co-founder — <a href="https://www.monarch-labs.com/" style="color:var(--cream)">Monarch Labs Collective</a>
</div>
</div>

<div class="vhs-main">
<div class="vhs-nav">
<a href="#01-persona">01 Persona</a>
<a href="#02-signal">02 Signal</a>
<a href="#03-work">03 Work</a>
<a href="#04-traits">04 Traits</a>
<a href="#05-tapes">05 Tapes</a>
<a href="#06-stats">06 Stats</a>
</div>

<div class="vhs-paper">

<div class="vhs-links">
<a href="mailto:B.Antoine.SE@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/bantoinese/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://www.monarch-labs.com/"><img src="https://img.shields.io/badge/Portfolio-Monarch_Labs-90221c?style=for-the-badge"/></a>
<a href="https://apps.apple.com/us/developer/monarch-labs-collective/id1891368463"><img src="https://img.shields.io/badge/App_Store-Live_Apps-0D96F6?style=for-the-badge&logo=appstore&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=bantoinese83&color=d64b37&style=for-the-badge&label=VIEWS"/>
</div>

<h3 id="01-persona"><span class="vhs-h2">01 · Persona</span></h3>
<span class="vhs-stamp">Case #BA-2026</span>

<div class="vhs-row">
<div class="vhs-card">
<div class="vhs-label">Profile data</div>
<ul class="vhs-profile">
<li><b>Name</b><span>Bryan Antoine</span></li>
<li><b>Studio</b><span>Monarch Labs Collective Inc. · NYC</span></li>
<li><b>Roles</b><span>Music producer · Recording engineer · Software engineer</span></li>
<li><b>Stack</b><span>SwiftUI · Expo · Next.js · FastAPI · Django · AWS</span></li>
<li><b>Audio</b><span>JUCE / C++ plugins · mastering · AI music tools</span></li>
<li><b>Repos</b><span>500+ projects · 6+ App Store titles · 25+ live web products</span></li>
<li><b>Known for</b><span>Studio ears + shipping code — same day, different medium.</span></li>
</ul>
</div>
<div class="vhs-card">
<div class="vhs-label">Character notes</div>
<p style="font-size:11px;line-height:1.55;text-align:justify;margin:0">
Multi-platinum production credits on one side of the board; APIs, mobile apps, and SaaS on the other. I build for myself, for Monarch Labs, and for clients — thrift rebuilds, accounting portals, compliance tooling, family apps, dating products, audio plugins, and AI-native workflows. Creative first, engineering second, ship date always in sight.
</p>
<div class="vhs-words">
<div class="vhs-word">Platinum<br/>Credits</div>
<div class="vhs-word">Ship<br/>Daily</div>
<div class="vhs-word">Full<br/>Stack</div>
</div>
</div>
</div>

<h3 id="02-signal"><span class="vhs-h2">02 · Signal</span></h3>
<div class="vhs-card">
<div class="vhs-label">Visual evidence — what I build</div>
<div class="vhs-words">
<div class="vhs-word">iOS<br/>SwiftUI</div>
<div class="vhs-word">Android<br/>Expo</div>
<div class="vhs-word">Web<br/>Next.js</div>
<div class="vhs-word">API<br/>FastAPI</div>
<div class="vhs-word">DSP<br/>JUCE</div>
<div class="vhs-word">AI<br/>LLM</div>
</div>
<p style="font-size:10px;margin:10px 0 0;text-align:center">
<img src="https://skillicons.dev/icons?i=swift,react,nextjs,python,fastapi,aws,docker,postgres,git&theme=dark&perline=9" alt="Stack icons"/>
</p>
</div>

<h3 id="03-work"><span class="vhs-h2">03 · Work files</span></h3>
<div class="vhs-file">
<div class="vhs-case">
<span class="vhs-tag">Mobile · Consumer</span>
<h4>iOS & cross-platform</h4>
<p style="font-size:11px;line-height:1.5;margin:0">Native apps on the App Store — <b>KYN</b> (family), <b>Signal</b> & <b>AccessDate</b>, <b>OnRecord</b>, <b>Velocity</b>, <b>Mixtran</b>, <b>Home Proof</b>, <b>BLUPRNT.AI</b>, and more. Expo / React Native for Android + shared codebases.</p>
</div>
<div class="vhs-case">
<span class="vhs-tag">Web · SaaS</span>
<h4>Next.js & monorepos</h4>
<p style="font-size:11px;line-height:1.5;margin:0"><b>LaunchStack</b> (Turborepo + Expo + Supabase), client sites, marketplaces, staff consoles — SVdP thrift rebuild, <b>Friday-File</b> (certified payroll), tax & accounting portals, Stripe billing.</p>
</div>
<div class="vhs-case">
<span class="vhs-tag">Backend · AI</span>
<h4>APIs & automation</h4>
<p style="font-size:11px;line-height:1.5;margin:0">Gateways, importers, OCR/compliance, medical & legal doc pipelines, voice AI (Gemini Live), RAG, micro-SaaS — Python, TypeScript, event-driven services on AWS.</p>
</div>
<div class="vhs-case">
<span class="vhs-tag">Music · Audio</span>
<h4>Studio & plugins</h4>
<p style="font-size:11px;line-height:1.5;margin:0">Recording / mix / master, <b>Monarch</b> DSP (<b>VCA-1</b>, <b>Dynik</b>, <b>GRAB</b>, <b>Bambee</b>), <b>MonarchSDK</b>, beat licensing, <b>TrackRights</b> (AI contract review), generative audio experiments.</p>
</div>
</div>

<h3 id="04-traits"><span class="vhs-h2">04 · Traits</span></h3>
<div class="vhs-row">
<div class="vhs-card">
<div class="vhs-label">Live readout</div>
<p style="font-size:10px;margin:0 0 4px">Backend engineering <em style="float:right">96%</em></p>
<div class="vhs-bar"><div class="vhs-fill" style="width:96%"></div></div>
<p style="font-size:10px;margin:0 0 4px">iOS / mobile <em style="float:right">94%</em></p>
<div class="vhs-bar"><div class="vhs-fill" style="width:94%"></div></div>
<p style="font-size:10px;margin:0 0 4px">Music production <em style="float:right">98%</em></p>
<div class="vhs-bar"><div class="vhs-fill" style="width:98%"></div></div>
<p style="font-size:10px;margin:0 0 4px">AI / product design <em style="float:right">90%</em></p>
<div class="vhs-bar"><div class="vhs-fill" style="width:90%"></div></div>
<p style="font-size:10px;margin:0 0 4px">Creativity <em style="float:right">99%</em></p>
<div class="vhs-bar"><div class="vhs-fill" style="width:99%"></div></div>
</div>
<div class="vhs-card">
<div class="vhs-label">Active focus</div>
<p style="font-size:10px;line-height:1.6;margin:0">
<code>KYN</code> · <code>Signal</code> · <code>AccessDate</code> · <code>Friday-File</code> · <code>SVdP Platform</code> · <code>Monarch-Labs-Inc</code> · <code>LaunchStack</code> · <code>JUCE plugins</code>
</p>
<div class="vhs-label" style="margin-top:10px">Likes</div>
<p style="font-size:10px;margin:0">Analog gear · loud mixes · clean APIs · SwiftUI polish · shipping MVPs · collaboration with founders</p>
</div>
</div>

<h3 id="05-tapes"><span class="vhs-h2">05 · Public tapes</span></h3>
<div class="vhs-row">
<a class="vhs-poster" href="https://github.com/bantoinese83/LaunchStack"><strong>LaunchStack</strong><span>B2B SaaS + mobile monorepo</span></a>
<a class="vhs-poster" href="https://github.com/bantoinese83/api-gateway"><strong>API Gateway</strong><span>FastAPI · auth · rate limits</span></a>
<a class="vhs-poster" href="https://github.com/bantoinese83/Gemini-Live-Assistant"><strong>Gemini Live</strong><span>Voice / video AI</span></a>
<a class="vhs-poster" href="https://github.com/bantoinese83/Monarch-Mastering"><strong>Monarch Mastering</strong><span>Python DSP pipeline</span></a>
<a class="vhs-poster" href="https://github.com/bantoinese83/trackrights"><strong>TrackRights</strong><span>AI contract review</span></a>
<a class="vhs-poster" href="https://github.com/bantoinese83/npm-fuzzy"><strong>npm-fuzzy</strong><span>TS fuzzy matching lib</span></a>
</div>
<p style="font-size:9px;text-align:center;margin-top:8px">Private studio & client repos — <a href="https://www.monarch-labs.com/#portfolio">full portfolio</a></p>

<h3 id="06-stats"><span class="vhs-h2">06 · Stats</span></h3>
<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=bantoinese83&show_icons=true&hide_border=true&bg_color=070504&title_color=d64b37&icon_color=d64b37&text_color=e7d9b7&include_all_commits=true&count_private=true"/>
<img height="165" src="https://github-readme-streak-stats.demolab.com/?user=bantoinese83&hide_border=true&background=070504&ring=d64b37&fire=d64b37&currStreakLabel=d64b37&sideLabels=d64b37&dates=e7d9b7"/>
<br/>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=bantoinese83&bg_color=070504&color=d64b37&line=d64b37&point=fff0cf&area=true&hide_border=true"/>
<br/>
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bantoinese83/bantoinese83/output/github-contribution-grid-snake-dark.svg"/>
<img alt="Contribution snake" src="https://raw.githubusercontent.com/bantoinese83/bantoinese83/output/github-contribution-grid-snake.svg"/>
</picture>
</div>

</div>
</div>

</div>
</div>

<div class="vhs-foot">Layout inspired by VHS case-file UI · <a href="https://www.monarch-labs.com/">Monarch Labs</a> · Studio + lab + ship</div>

</div>

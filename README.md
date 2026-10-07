# Vanta-Digital

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Vanta Digital | Premium Web Design & Development</title>
<meta name="description" content="Vanta Digital designs clean, fast, premium websites that help businesses look established, attract customers and get more enquiries.">
<link rel="canonical" href="https://YOUR-DOMAIN.com/">
<meta property="og:type" content="website"><meta property="og:title" content="Vanta Digital | Premium Web Design & Development">
<meta property="og:description" content="Websites built to make your business impossible to overlook."><meta name="twitter:card" content="summary_large_image">
<meta name="theme-color" content="#0a0a0a">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Manrope:wght@300;400;500&display=swap" rel="stylesheet">
<script type="application/ld+json">{"@context":"https://schema.org","@type":"ProfessionalService","name":"Vanta Digital","url":"https://YOUR-DOMAIN.com/","email":"tristen.els@icloud.com","telephone":"+27662044329","serviceType":["Web design","Web development"]}</script>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div id="ld" aria-hidden="true"><b>Vanta Digital</b></div><div id="cr" aria-hidden="true"><span id="crt"></span></div>
<header id="hd"><div class="wrap nv"><a class="logo" href="#home" aria-label="Vanta Digital home">Vanta Digital</a><nav class="links" id="lk" aria-label="Main"></nav><button class="bg" id="bg" aria-label="Open menu" aria-expanded="false"><i></i><i></i></button></div></header>
<div class="menu" id="mn"><nav id="mnl" aria-label="Mobile"></nav><p class="mut sm" id="mnf"></p></div>
<main id="main"></main>
<footer><div class="wrap ft"><span id="cp"></span><nav id="fn" aria-label="Footer"></nav></div></footer>
<div class="md" id="md" role="dialog" aria-modal="true" aria-label="Project details"><div class="box" id="mb"></div></div>
<script src="script.js" defer></script>
</body>
</html>


:root{--bg:#0a0a0a;--tx:#ece9e2;--mut:#8f8d88;--ln:rgba(255,255,255,.1);--ac:#cdbb98;--e:cubic-bezier(.16,1,.3,1);--w:cubic-bezier(.76,0,.24,1)}
*{box-sizing:border-box;margin:0;padding:0}html{-webkit-text-size-adjust:100%}
body{background:var(--bg);color:var(--tx);font:300 1.02rem/1.7 Manrope,system-ui,sans-serif;overflow-x:hidden;-webkit-font-smoothing:antialiased}
a{color:inherit;text-decoration:none}button,input,select,textarea{font:inherit;color:inherit}
:focus-visible{outline:2px solid var(--ac);outline-offset:3px}
h1,h2,h3{font-family:'Instrument Serif',Georgia,serif;font-weight:400;line-height:1.04;letter-spacing:-.02em}
h1{font-size:clamp(2.7rem,8vw,6.4rem)}h2{font-size:clamp(2rem,5vw,3.8rem)}h3{font-size:clamp(1.5rem,2.6vw,2rem)}
.wrap{width:min(1100px,100% - 44px);margin:auto}.sec{padding:clamp(70px,11vw,130px) 0}.mut{color:var(--mut)}.sm{font-size:.88rem}.sub{color:var(--mut);max-width:520px;margin-top:22px}
/* header */
header{position:fixed;top:0;left:0;right:0;z-index:50;padding:calc(16px + env(safe-area-inset-top)) 0 16px;transition:transform .5s var(--e),background .4s}
header.sc{background:rgba(10,10,10,.8);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px)}header.hd{transform:translateY(-100%)}
.nv{display:flex;justify-content:space-between;align-items:center}.logo{font-family:'Instrument Serif',serif;font-size:1.5rem;position:relative;z-index:70}
.links{display:flex;gap:30px;font-size:.88rem}.links a{color:var(--mut);transition:color .3s;padding:6px 0;border-bottom:1px solid transparent}.links a:hover{color:var(--tx)}.links a.on{color:var(--tx);border-color:var(--ac)}
.bg{display:none;position:relative;z-index:70;width:48px;height:48px;border:1px solid var(--ln);border-radius:50%;background:none;cursor:pointer}
.bg i{position:absolute;left:15px;width:16px;height:1.5px;background:var(--tx);transition:.5s var(--e)}.bg i:first-child{top:19px}.bg i:last-child{top:27px}
.mo .bg i:first-child{top:23px;transform:rotate(45deg)}.mo .bg i:last-child{top:23px;transform:rotate(-45deg)}
.menu{position:fixed;inset:0;z-index:60;background:var(--bg);padding:120px 28px 40px;display:flex;flex-direction:column;justify-content:space-between;opacity:0;visibility:hidden;transition:opacity .5s,visibility .5s}
.mo .menu{opacity:1;visibility:visible}.menu a{display:block;font-family:'Instrument Serif',serif;font-size:clamp(2.2rem,10vw,3.2rem);line-height:1.25;opacity:0;transform:translateY(24px);transition:.7s var(--e)}.mo .menu a{opacity:1;transform:none;transition-delay:calc(.15s + var(--i)*.05s)}
@media(max-width:900px){.links{display:none}.bg{display:block}}
/* buttons */
.btn{display:inline-flex;align-items:center;gap:10px;min-height:50px;padding:14px 28px;border-radius:99px;border:1px solid var(--tx);background:var(--tx);color:#0a0a0a;font-weight:400;font-size:.95rem;cursor:pointer;transition:background .3s,border-color .3s,color .3s}
.btn i{font-style:normal;transition:transform .4s var(--e)}.btn:hover i{transform:translate(3px,-3px)}.btn:hover{background:var(--ac);border-color:var(--ac)}.btn.g{background:none;color:var(--tx);border-color:var(--ln)}.btn.g:hover{border-color:var(--tx)}
.row{display:flex;gap:12px;flex-wrap:wrap}
/* hero */
.hero{min-height:100svh;display:flex;align-items:center;position:relative;overflow:hidden;padding:130px 0 90px}
.glow{position:absolute;width:min(80vw,760px);aspect-ratio:1;right:-18%;top:6%;border-radius:50%;background:radial-gradient(circle,rgba(205,187,152,.17),transparent 65%);animation:dr 16s ease-in-out infinite alternate}@keyframes dr{to{transform:translate(-9%,12%) scale(1.15)}}
.hero .wrap{position:relative}.hero h1{max-width:960px}.hero .lead{max-width:460px;color:var(--mut);margin:30px 0 40px;font-size:1.1rem}
/* reveal */
.split .w{display:inline-block;overflow:hidden;vertical-align:top;padding-bottom:.12em;margin-bottom:-.12em}.split .w>span{display:inline-block;transform:translateY(110%);transition:transform 1.1s var(--e);transition-delay:calc(var(--i)*.05s)}.split.in .w>span{transform:none}
.rv{opacity:0;transform:translateY(22px);transition:opacity .9s var(--e),transform .9s var(--e);transition-delay:var(--d,0s)}.rv.in{opacity:1;transform:none}
/* quiz */
.qz{border:1px solid var(--ln);border-radius:26px;padding:clamp(26px,5vw,56px);margin-top:44px;min-height:310px;position:relative;overflow:hidden}.qz>div{animation:fi .6s var(--e)}@keyframes fi{from{opacity:0;transform:translateY(14px)}}
.qz h3{font-size:clamp(1.7rem,3.8vw,2.8rem);margin:14px 0 34px;max-width:720px}.pb{position:absolute;left:0;top:0;height:2px;background:var(--ac);transition:width .6s var(--e)}
/* rows */
.tr{display:flex;justify-content:space-between;align-items:baseline;gap:20px;padding:34px 0;border-top:1px solid var(--ln);transition:padding .5s var(--e)}.tr:last-of-type{border-bottom:1px solid var(--ln)}
.tr span{font-family:'Instrument Serif',serif;font-size:clamp(2rem,5vw,3.6rem);line-height:1.1}.tr small{color:var(--mut);font-size:.9rem;text-align:right}.tr:hover{padding-left:14px}.tr:hover span{color:var(--ac)}
/* page head */
.ph1{padding:clamp(150px,19vw,230px) 0 clamp(30px,5vw,60px)}.ph1 h1{font-size:clamp(2.6rem,7.5vw,5.6rem);max-width:900px}
/* work */
.pg{display:grid;grid-template-columns:repeat(3,1fr);gap:24px}@media(max-width:900px){.pg{grid-template-columns:1fr}}
.pc{background:none;border:0;text-align:left;cursor:pointer;display:block;width:100%}.mock{aspect-ratio:4/3;border-radius:18px;border:1px solid var(--ln);background:linear-gradient(var(--a),#171718,#0d0d0e);display:grid;place-items:center;transition:transform .8s var(--e),border-color .4s;position:relative;overflow:hidden}
.mock:before{content:"";position:absolute;left:16px;top:16px;width:44px;height:6px;border-radius:9px;background:radial-gradient(circle at 3px 3px,#555 3px,transparent 4px) 0 0/14px 6px repeat-x}.mock b{font-family:'Instrument Serif',serif;font-weight:400;font-size:clamp(1.7rem,3vw,2.2rem);color:rgba(236,233,226,.4);text-align:center;padding:0 14px}
.pc:hover .mock{transform:translateY(-6px);border-color:rgba(205,187,152,.45)}.pc h3{margin:18px 0 2px;font-size:1.6rem}.pc p{color:var(--mut);font-size:.9rem}
.tg2{display:grid;grid-template-columns:repeat(3,1fr);gap:40px}@media(max-width:900px){.tg2{grid-template-columns:1fr}}.tt q{font-family:'Instrument Serif',serif;font-size:1.45rem;line-height:1.3;display:block;quotes:none}.tt small{display:block;margin-top:14px;color:var(--mut)}
/* services */
.sd{display:grid;grid-template-columns:1fr 1fr;gap:30px 60px;padding:48px 0;border-top:1px solid var(--ln)}@media(max-width:800px){.sd{grid-template-columns:1fr}}.sd ul{list-style:none}.sd li{padding:10px 0;border-bottom:1px solid var(--ln);color:var(--mut);font-size:.95rem}.sd li:first-child{padding-top:0}
/* process */
.st{display:grid;grid-template-columns:90px 1fr;gap:10px 20px;padding:44px 0;border-top:1px solid var(--ln)}.st b{font-family:'Instrument Serif',serif;font-weight:400;font-size:2.4rem;color:var(--ac);line-height:1}.st p{color:var(--mut);max-width:520px;margin-top:10px}
/* pricing */
.pgr{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;align-items:stretch}@media(max-width:900px){.pgr{grid-template-columns:1fr}}
.pp{border:1px solid var(--ln);border-radius:24px;padding:clamp(26px,3vw,40px);display:flex;flex-direction:column;position:relative}.pp.f{border-color:rgba(205,187,152,.55);background:linear-gradient(180deg,rgba(205,187,152,.07),transparent)}
.tag{position:absolute;top:-12px;left:30px;background:var(--ac);color:#0a0a0a;font-size:.76rem;padding:3px 14px;border-radius:99px;font-weight:500}
.pr2{font-family:'Instrument Serif',serif;font-size:3.4rem;line-height:1;margin:22px 0 0}.pp ul{list-style:none;margin:26px 0 32px;flex:1}.pp li{padding:10px 0;border-top:1px solid var(--ln);font-size:.92rem;color:var(--mut)}
/* about / contact */
.two{display:grid;grid-template-columns:1.2fr 1fr;gap:clamp(30px,6vw,90px)}@media(max-width:800px){.two{grid-template-columns:1fr}}
.state{font-family:'Instrument Serif',serif;font-size:clamp(1.8rem,3.6vw,2.8rem);line-height:1.15}
.cl a{display:block;padding:18px 0;border-bottom:1px solid var(--ln);transition:padding .4s var(--e),color .3s}.cl a:hover{padding-left:12px;color:var(--ac)}.cl small{display:block;color:var(--mut);font-size:.8rem}
.fd{margin-bottom:20px}.fd label{display:block;font-size:.82rem;color:var(--mut)}.fd input,.fd select,.fd textarea{width:100%;background:none;border:0;border-bottom:1px solid var(--ln);border-radius:0;padding:10px 0;min-height:46px;font-size:1rem;transition:border-color .3s}
.fd select option{background:#111}.fd textarea{min-height:100px;resize:vertical}.fd input:focus,.fd select:focus,.fd textarea:focus{outline:0;border-color:var(--ac)}.f2{display:grid;grid-template-columns:1fr 1fr;gap:0 26px}@media(max-width:560px){.f2{grid-template-columns:1fr}}
.cta{text-align:center;padding:clamp(90px,14vw,190px) 0;border-top:1px solid var(--ln)}.cta h2{max-width:820px;margin:0 auto}.cta p{color:var(--mut);margin:22px auto 34px;max-width:420px}.cta .row{justify-content:center}
footer{border-top:1px solid var(--ln);padding:44px 0 36px;color:var(--mut);font-size:.86rem}.ft{display:flex;justify-content:space-between;gap:24px;flex-wrap:wrap}.ft nav{display:flex;gap:22px;flex-wrap:wrap}.ft a:hover{color:var(--tx)}
.md{position:fixed;inset:0;z-index:90;background:rgba(8,8,8,.88);backdrop-filter:blur(12px);display:none;overflow-y:auto;padding:60px 0}.md.on{display:block;animation:fi2 .4s}@keyframes fi2{from{opacity:0}}
.box{width:min(760px,100% - 32px);margin:auto;background:#101011;border:1px solid var(--ln);border-radius:24px;padding:clamp(24px,5vw,48px)}.box .x{float:right;width:46px;height:46px;border-radius:50%;border:1px solid var(--ln);background:none;cursor:pointer;font-size:1.2rem}
#ld{position:fixed;inset:0;z-index:200;background:var(--bg);display:grid;place-items:center;transition:transform 1s var(--w)}#ld.go{transform:translateY(-100%)}#ld b{font-family:'Instrument Serif',serif;font-weight:400;font-size:clamp(2rem,6vw,3.2rem);animation:pl 1.2s ease-in-out infinite alternate}@keyframes pl{from{opacity:.25}}
#cr{position:fixed;inset:0;z-index:150;background:#0e0e0e;transform:translateY(100%);pointer-events:none;display:grid;place-items:center}#cr span{font-family:'Instrument Serif',serif;font-size:clamp(2rem,7vw,3.8rem);color:var(--ac);opacity:0;transition:opacity .4s}#cr.on span{opacity:1}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{animation:none!important;transition-duration:.01ms!important;transition-delay:0s!important}.rv,.split .w>span{opacity:1;transform:none}}

/* ========== EDIT YOUR CONTENT HERE ========== */
const C={
 name:"Vanta Digital",owner:"Tristen Els",email:"tristen.els@icloud.com",phone:"+27 66 204 4329",wa:"27662044329",
 pages:[["home","Home"],["work","Work"],["services","Services"],["process","Process"],["pricing","Pricing"],["about","About"],["contact","Contact"]],
 plans:[
  {n:"Starter",for:"A clean one-page website",p:"R3,500",f:["One-page custom design","Mobile-friendly","WhatsApp and contact button","Basic SEO setup","Live link ready to share"]},
  {n:"Business",for:"A more advanced, multi-page website",p:"R5,000",hot:1,f:["Up to 5 pages","Custom design and smooth animations","Enquiry form","On-page SEO","Speed optimised","Support after launch"]},
  {n:"Signature",for:"A high-end, fully bespoke build",p:"R12,500",f:["Fully bespoke design","Up to 10 pages or an online store","Advanced animations and interactions","SEO and analytics setup","Priority support"]}],
 services:[
  ["Business Websites","A complete site that explains what you do and makes it easy to get in touch.",["Multi-page custom design","Enquiry form and WhatsApp link","Mobile-first build","Search-ready structure"]],
  ["Landing Pages","One focused page built to turn visitors into enquiries.",["Single-page custom design","Clear call to action","Fast loading","Basic SEO"]],
  ["Online Stores","Sell products online with a simple, smooth checkout.",["Product pages and cart","Payment setup","Mobile-first design","Speed optimised"]],
  ["Redesigns and Care","Refresh an outdated site, speed it up and keep it updated.",["Modern redesign","Performance improvements","Updates and small changes","Ongoing support"]]],
 /* SAMPLE projects: replace with your real work */
 projects:[{n:"Coastal Café",t:"Hospitality, one-page site",d:"A warm, simple one-page site that puts the menu and location front and centre."},{n:"Northline Builders",t:"Services, business website",d:"A confident multi-page site built to turn local searches into enquiries."},{n:"Atelier Store",t:"E-commerce, online store",d:"A clean online store with a fast, simple checkout."}],
 /* SAMPLE testimonials: replace with real client feedback before launch */
 tests:[["It was simple from start to finish, and the site looks far more professional than I expected.","Restaurant owner"],["The design felt like us from the very first draft. Communication was clear all the way.","Small business owner"],["Quick, clear and it works perfectly on my phone.","Online store owner"]]
};
/* =========================================== */
const $=(s,r=document)=>r.querySelector(s),$$=(s,r=document)=>[...r.querySelectorAll(s)];
const RM=matchMedia("(prefers-reduced-motion:reduce)").matches;history.scrollRestoration="manual";
const btn=(t,h="#contact",g="")=>`<a class="btn ${g}" href="${h}">${t}<i>↗</i></a>`;
const head=(t,s)=>`<h2 class="split">${t}</h2>${s?`<p class="sub rv">${s}</p>`:""}`;
const fin=()=>`<section class="cta"><div class="wrap"><h2 class="split">Your next website should do more than exist.</h2><p class="rv">Tell us about your business and we'll reply with a clear plan.</p><div class="row rv">${btn("Start your project")}</div></div></section>`;
const price=()=>`<div class="pgr">${C.plans.map(p=>`<div class="pp rv${p.hot?" f":""}">${p.hot?'<span class="tag">Recommended</span>':""}<h3>${p.n}</h3><p class="mut sm">${p.for}</p><div class="pr2">${p.p}</div><ul>${p.f.map(x=>`<li>${x}</li>`).join("")}</ul>${btn("Get started","#contact",p.hot?"":"g")}</div>`).join("")}</div><p class="mut sm rv" style="margin-top:28px">Prices are starting points. The final price depends on what you need. <a href="#contact" style="color:var(--ac)">Ask for a custom quote.</a></p>`;
const steps=[["Discovery","We learn what you do, who you serve and what the site needs to achieve."],["Design","You see a custom design before anything is built, and we refine it with you."],["Build","We develop it to be fast, responsive and easy to use on every device."],["Launch","We test everything, go live and hand it over, with support after."]];
const P={
home:()=>`<section class="hero"><div class="glow" aria-hidden="true"></div><div class="wrap"><h1 class="split">Your website is either winning you customers or quietly losing them.</h1><p class="lead rv">Most owners never find out which. Four questions will tell you where yours stands.</p><div class="row rv"><a class="btn" href="#test" id="tb">Take the test<i>↓</i></a>${btn("Start a project","#contact","g")}</div></div></section>
<section class="sec" id="test" style="padding-top:20px"><div class="wrap"><h2 class="split">Before anyone calls you, they look you up. What do they find?</h2><div class="qz rv" id="qz" aria-live="polite"></div></div></section>
<section class="sec" style="padding-top:0"><div class="wrap"><a class="tr rv" href="#work"><span>Our work</span><small>See what we build</small></a><a class="tr rv" href="#services"><span>Services</span><small>What we do</small></a><a class="tr rv" href="#pricing"><span>Pricing</span><small>From R3,500</small></a></div></section>${fin()}`,
work:()=>`<section class="ph1"><div class="wrap"><h1 class="split">Selected work.</h1></div></section><section class="sec" style="padding-top:30px"><div class="wrap"><div class="pg">${C.projects.map((p,k)=>`<button class="pc rv" data-p="${k}" style="--d:${k*.1}s" aria-label="View ${p.n}"><div class="mock" style="--a:${135+k*40}deg"><b>${p.n}</b></div><h3>${p.n}</h3><p>${p.t}</p></button>`).join("")}</div></div></section>
<section class="sec" style="padding-top:0"><div class="wrap">${head("What clients say.")}<div class="tg2" style="margin-top:50px">${C.tests.map(t=>`<figure class="tt rv"><q>${t[0]}</q><small>${t[1]}</small></figure>`).join("")}</div></div></section>${fin()}`,
services:()=>`<section class="ph1"><div class="wrap"><h1 class="split">What we do.</h1><p class="sub rv">Four things, done properly.</p></div></section><section class="sec" style="padding-top:30px"><div class="wrap">${C.services.map(s=>`<div class="sd rv"><div><h2 style="font-size:clamp(1.9rem,3.6vw,2.8rem)">${s[0]}</h2><p class="mut" style="margin:14px 0 24px;max-width:380px">${s[1]}</p>${btn("Enquire","#contact","g")}</div><ul>${s[2].map(i=>`<li>${i}</li>`).join("")}</ul></div>`).join("")}</div></section>${fin()}`,
process:()=>`<section class="ph1"><div class="wrap"><h1 class="split">A clear path from idea to launch.</h1></div></section><section class="sec" style="padding-top:30px"><div class="wrap">${steps.map((s,k)=>`<div class="st rv"><b>${k+1}</b><div><h3>${s[0]}</h3><p>${s[1]}</p></div></div>`).join("")}</div></section>${fin()}`,
pricing:()=>`<section class="ph1"><div class="wrap"><h1 class="split">Simple, honest pricing.</h1></div></section><section class="sec" style="padding-top:40px"><div class="wrap">${price()}</div></section>${fin()}`,
about:()=>`<section class="ph1"><div class="wrap"><h1 class="split">A small studio that cares about the details.</h1></div></section><section class="sec" style="padding-top:30px"><div class="wrap two"><p class="state rv">Vanta Digital builds clean, fast websites for businesses that want to look established online.</p><div class="rv mut"><p>We're a small independent studio, which means you deal directly with the people designing and building your site.</p><p style="margin-top:18px">We focus on three things: design that feels considered, code that loads fast, and results you can measure in enquiries.</p></div></div></section>${fin()}`,
contact:()=>`<section class="ph1"><div class="wrap"><h1 class="split">Let's build something that works for you.</h1></div></section><section class="sec" style="padding-top:30px"><div class="wrap two"><div class="cl rv"><a href="tel:+27662044329"><small>${C.owner}</small>${C.phone}</a><a href="mailto:${C.email}"><small>Email</small>${C.email}</a><a href="https://wa.me/${C.wa}" target="_blank" rel="noopener"><small>WhatsApp</small>Message us</a></div>
<form id="fm" class="rv" novalidate><div class="f2"><div class="fd"><label for="n">Name</label><input id="n" name="Name" required autocomplete="name"></div><div class="fd"><label for="b">Business</label><input id="b" name="Business" autocomplete="organization"></div><div class="fd"><label for="e">Email</label><input id="e" name="Email" type="email" required autocomplete="email"></div><div class="fd"><label for="t">Phone</label><input id="t" name="Phone" type="tel" autocomplete="tel"></div></div>
<div class="f2"><div class="fd"><label for="x">What do you need?</label><select id="x" name="Need">${["A one-page website","A multi-page website","A premium custom build","An online store","A redesign","Not sure yet"].map(o=>`<option>${o}</option>`).join("")}</select></div><div class="fd"><label for="u">Budget</label><select id="u" name="Budget">${["Around R3,500","Around R5,000","R12,500 or more","Not sure yet"].map(o=>`<option>${o}</option>`).join("")}</select></div></div>
<div class="fd"><label for="d">Tell us about your business</label><textarea id="d" name="Details"></textarea></div><div class="row"><button class="btn" type="submit">Start my project<i>↗</i></button><button class="btn g" type="button" id="wab">Send on WhatsApp<i>↗</i></button></div><p class="mut sm" id="fs" role="status" style="margin-top:16px"></p></form></div></section>`
};
const main=$("#main"),cr=$("#cr");let cur="",busy=0;
function split(el){const t=el.textContent.trim().split(/\s+/);el.setAttribute("aria-label",t.join(" "));el.innerHTML=t.map((w,i)=>`<span class="w" aria-hidden="true"><span style="--i:${i}">${w}</span></span> `).join("")}
function nav(){const l=C.pages.map(p=>`<a href="#${p[0]}" data-r="${p[0]}">${p[1]}</a>`).join("");$("#lk").innerHTML=l;$("#fn").innerHTML=l;$("#mnl").innerHTML=C.pages.map((p,i)=>`<a href="#${p[0]}" style="--i:${i}">${p[1]}</a>`).join("");$("#mnf").textContent=C.email;$("#cp").textContent="© "+new Date().getFullYear()+" "+C.name}
function mount(r){cur=r;main.innerHTML=P[r]();document.title=(r=="home"?"Vanta Digital | Premium Web Design & Development":C.pages.find(p=>p[0]==r)[1]+" | Vanta Digital");$$("[data-r]").forEach(a=>a.classList.toggle("on",a.dataset.r==r));$$(".split",main).forEach(split);scrollTo(0,0);setTimeout(reveal,60);bind(r)}
function reveal(){const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in");io.unobserve(e.target)}}),{threshold:.12,rootMargin:"0px 0px -5% 0px"});$$(".rv,.split",main).forEach(e=>RM?e.classList.add("in"):io.observe(e))}
function go(r){if(!P[r])r="home";if(r==cur||busy)return;if(RM||!cur){mount(r);return}busy=1;cr.style.transition="none";cr.style.transform="translateY(100%)";$("#crt").textContent=C.pages.find(p=>p[0]==r)[1];cr.offsetHeight;cr.style.transition="transform .7s var(--w)";cr.style.transform="translateY(0)";cr.classList.add("on");setTimeout(()=>{mount(r);cr.style.transform="translateY(-100%)";cr.classList.remove("on");setTimeout(()=>busy=0,700)},750)}
function menu(o){document.body.classList.toggle("mo",o);$("#bg").setAttribute("aria-expanded",o);$("#bg").setAttribute("aria-label",o?"Close menu":"Open menu")}
addEventListener("hashchange",()=>{menu(false);go(location.hash.slice(1)||"home")});$("#bg").onclick=()=>menu(!document.body.classList.contains("mo"));
let ly=0;addEventListener("scroll",()=>{const y=scrollY,h=$("#hd");h.classList.toggle("sc",y>30);h.classList.toggle("hd",y>ly&&y>300&&!document.body.classList.contains("mo"));ly=y},{passive:true});
const Q=["Does your website load in under 3 seconds on a phone?","Could a stranger tell what you do within 5 seconds?","Does every visitor have one clear next step?","Would you proudly send it to your ideal client?"];
const R=[["Your website is probably costing you customers.","The good news: this is one of the most fixable problems in a business."],["Some customers are slipping past.","Gaps like these are common, and usually quick to fix."],["Strong foundation.","A premium finish can still set you apart from every competitor who looks the same."]];
function quiz(){const b=$("#qz");let i=0,s=0;const draw=()=>{if(i<4){b.innerHTML=`<div><i class="pb" style="width:${i*25}%"></i><p class="mut sm">Question ${i+1} of 4</p><h3>${Q[i]}</h3><div class="row"><button class="btn" data-a="1">Yes</button><button class="btn g" data-a="0">Not sure</button><button class="btn g" data-a="0">No</button></div></div>`;$$("button",b).forEach(x=>x.onclick=()=>{s+=+x.dataset.a;i++;draw()})}else{const r=R[s>3?2:s>1?1:0];b.innerHTML=`<div><i class="pb" style="width:100%"></i><p class="mut sm">Your result</p><h3>${r[0]}</h3><p class="mut" style="margin:-10px 0 30px;max-width:520px">${r[1]}</p><div class="row">${btn("Let's improve it")}<button class="btn g" id="rt">Retake</button></div></div>`;$("#rt").onclick=()=>{i=0;s=0;draw()}}};draw()}
function modal(p){const m=$("#md");$("#mb").innerHTML=`<button class="x" aria-label="Close">×</button><h2 style="font-size:clamp(2rem,5vw,3.2rem)">${p.n}</h2><p class="mut" style="margin:8px 0 26px">${p.t}</p><div class="mock" style="--a:150deg;margin-bottom:24px"><b>${p.n}</b></div><p class="mut" style="margin-bottom:28px">${p.d}</p>${btn("Start a similar project")}`;m.classList.add("on");document.body.style.overflow="hidden";const c=$(".x",m),cl=()=>{m.classList.remove("on");document.body.style.overflow=""};c.focus();c.onclick=cl;m.onclick=e=>{if(e.target==m)cl()};$("#mb .btn").onclick=cl;m.onkeydown=e=>{if(e.key=="Escape")cl()}}
function form(){const f=$("#fm"),msg=()=>[...new FormData(f)].filter(x=>x[1]).map(x=>x[0]+": "+x[1]).join("\n");f.onsubmit=e=>{e.preventDefault();if(!f.checkValidity()){f.reportValidity();return}location.href=`mailto:${C.email}?subject=${encodeURIComponent("New project enquiry")}&body=${encodeURIComponent(msg())}`;$("#fs").textContent="Opening your email app with your details ready to send."};$("#wab").onclick=()=>{if(!$("#n").value){$("#n").focus();return}open(`https://wa.me/${C.wa}?text=${encodeURIComponent("New project enquiry\n"+msg())}`,"_blank")}}
function bind(r){$$(".pc").forEach(b=>b.onclick=()=>modal(C.projects[b.dataset.p]));if(r=="home"){quiz();$("#tb").onclick=e=>{e.preventDefault();$("#test").scrollIntoView({behavior:RM?"auto":"smooth"})}}if(r=="contact")form()}
let sx,sy;addEventListener("touchstart",e=>{if(e.target.closest(".md,input,textarea,select"))sx=null;else{sx=e.touches[0].clientX;sy=e.touches[0].clientY}},{passive:true});
addEventListener("touchend",e=>{if(sx==null||document.body.classList.contains("mo"))return;const dx=e.changedTouches[0].clientX-sx,dy=e.changedTouches[0].clientY-sy;if(Math.abs(dx)>110&&Math.abs(dy)<45){const i=C.pages.findIndex(p=>p[0]==cur),n=C.pages[i+(dx<0?1:-1)];if(n)location.hash=n[0]}},{passive:true});
nav();const f0=location.hash.slice(1);mount(P[f0]?f0:"home");
addEventListener("load",()=>setTimeout(()=>{$("#ld").classList.add("go");setTimeout(()=>$("#ld").remove(),1000)},RM?0:600));

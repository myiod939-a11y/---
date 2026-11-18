[Uploadingindex.html]()
# ---
المحاسبه
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self' 'unsafe-inline'; style-src 'self' 'unsafe-inline'; img-src 'self' data:; connect-src 'none'; frame-src 'none'; base-uri 'none'; form-action 'none';">
<title>دليل المحاسبة</title>
<style>
:root{--bg:#f6f7fb;--card:#fff;--tx:#1b2438;--mu:#5c677d;--pr:#0f6e56;--pr2:#e1f5ee;--bd:#e2e6ee;--ok:#1d8a4c;--no:#c0392b;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#10151f;--card:#19202e;--tx:#e8ecf4;--mu:#9aa6bd;--pr:#3ecf9f;--pr2:#16322b;--bd:#2a3347;--ok:#4cc77f;--no:#ff7b6b;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#10151f;--card:#19202e;--tx:#e8ecf4;--mu:#9aa6bd;--pr:#3ecf9f;--pr2:#16322b;--bd:#2a3347;--ok:#4cc77f;--no:#ff7b6b;color-scheme:dark}
*{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--tx);font-family:"Segoe UI",Tahoma,"Noto Naskh Arabic",Arial,sans-serif;line-height:1.8;padding-bottom:84px}
header{background:var(--pr);color:#fff;padding:18px 16px 14px;display:flex;justify-content:space-between;align-items:center;gap:10px}
:root[data-theme="dark"] header,:root:not([data-theme="light"]) header{color:#07251c}
@media (prefers-color-scheme:light){:root:not([data-theme="dark"]) header{color:#fff}}
header h1{margin:0;font-size:20px}header p{margin:0;font-size:13px;opacity:.9}
#th{background:rgba(255,255,255,.2);border:0;border-radius:50%;width:38px;height:38px;font-size:18px;cursor:pointer}
main{max-width:860px;margin:0 auto;padding:14px}
.tab{display:none}.tab.on{display:block}
.card{background:var(--card);border:1px solid var(--bd);border-radius:14px;padding:14px 16px;margin-bottom:12px}
.card h3{margin:0 0 8px;font-size:16px;color:var(--pr)}
input[type=search]{width:100%;padding:11px 14px;border-radius:12px;border:1px solid var(--bd);background:var(--card);color:var(--tx);font:inherit;margin-bottom:12px}
details{background:var(--card);border:1px solid var(--bd);border-radius:14px;margin-bottom:10px;overflow:hidden}
summary{padding:13px 16px;font-weight:700;cursor:pointer;list-style:none;display:flex;justify-content:space-between}
summary::after{content:"＋";color:var(--pr)}details[open] summary::after{content:"－"}
details .b{padding:0 16px 12px}details ul{margin:0;padding-inline-start:20px}details li{margin-bottom:4px}
.eq{background:var(--pr2);color:var(--pr);border-radius:12px;padding:12px;text-align:center;font-weight:700;font-size:17px;margin-bottom:10px}
.wrap{overflow-x:auto}table{border-collapse:collapse;width:100%;font-size:14px}
th,td{border:1px solid var(--bd);padding:8px 10px;text-align:center}th{background:var(--pr2);color:var(--pr)}
label{display:block;font-size:13px;color:var(--mu);margin:8px 0 2px}
input[type=number]{width:100%;padding:10px;border-radius:10px;border:1px solid var(--bd);background:var(--bg);color:var(--tx);font:inherit}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:0 10px}
.res{background:var(--pr2);border-radius:10px;padding:10px 12px;margin-top:10px;font-weight:700;color:var(--pr);min-height:44px}
button.p{background:var(--pr);color:#fff;border:0;border-radius:10px;padding:10px 18px;font:inherit;font-weight:700;cursor:pointer;margin-top:10px}
:root[data-theme="dark"] button.p{color:#07251c}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]) button.p{color:#07251c}}
.opt{display:block;width:100%;text-align:start;background:var(--bg);color:var(--tx);border:1px solid var(--bd);border-radius:10px;padding:10px 12px;margin-top:8px;font:inherit;cursor:pointer}
.opt.ok{border-color:var(--ok);background:var(--pr2)}.opt.no{border-color:var(--no)}
.ex{color:var(--mu);font-size:14px;margin-top:8px}
nav{overflow-x:auto;position:fixed;bottom:0;left:0;right:0;background:var(--card);border-top:1px solid var(--bd);display:flex;padding:6px 4px calc(6px + env(safe-area-inset-bottom,0px));z-index:5}
nav button{min-width:66px;flex:1;background:none;border:0;color:var(--mu);font:inherit;font-size:12px;cursor:pointer;padding:4px 0}
nav button span{display:block;font-size:20px}nav button.on{color:var(--pr);font-weight:700}
select,input[type=text]{width:100%;padding:10px;border-radius:10px;border:1px solid var(--bd);background:var(--bg);color:var(--tx);font:inherit}
.bd{display:inline-block;padding:3px 12px;border-radius:20px;background:var(--pr2);color:var(--ok);font-weight:700;font-size:13px}
.x{background:none;border:0;color:var(--no);cursor:pointer;font-size:16px}
.tt td{font-weight:800;background:var(--pr2)}
.big{font-size:30px;font-weight:800;color:var(--pr)}
#cine{height:430vh;position:relative;background:#3a2d24;direction:ltr}
.stg{position:sticky;top:0;height:100vh;height:100svh;overflow:hidden;background:#3a2d24}
.sc{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;will-change:transform,opacity}
#s1{background:radial-gradient(circle at 50% 40%,#6d5646,#2b211b)}
.pw{width:min(46vw,250px);aspect-ratio:.78;border-radius:50%/42%;border:14px solid #ebe5dc;box-shadow:0 10px 40px #0008,inset 0 0 30px #0005;background:linear-gradient(#4f9be0,#b5dcf6 68%,#fff);will-change:transform}
.tx,.w{position:absolute;top:50%;margin-top:-.6em;font-weight:800;font-size:clamp(24px,7vw,64px);line-height:1.2;white-space:nowrap;direction:rtl}
.tx{color:#f3ece3}.w{color:#2b211b;z-index:2}
.l{left:5%}.r{right:5%}
#cl{background:radial-gradient(ellipse at 30% 70%,#fff 0,#f7c9d4 25%,transparent 55%),radial-gradient(ellipse at 70% 40%,#fff 0,#bfe0f7 30%,transparent 60%),linear-gradient(#5a9ee0,#dfeefa);opacity:0}
#s2{background:#f1ede6;opacity:0}
#jet{height:72vh;max-height:560px;will-change:transform;filter:drop-shadow(0 20px 20px #0003)}
#s3{background:#0e0d0c;opacity:0;flex-direction:column}
.big3{position:absolute;top:18%;font-size:34vw;font-weight:900;color:#2a2622;line-height:1;white-space:nowrap}
#gb{width:min(62vw,300px);position:relative;will-change:transform}
#mr ellipse{animation:sp 6s linear infinite;transform-origin:110px 110px}
#mr ellipse:nth-child(2){animation-delay:-1.5s}#mr ellipse:nth-child(3){animation-delay:-3s}#mr ellipse:nth-child(4){animation-delay:-4.5s}
@keyframes sp{0%{transform:scaleX(1)}50%{transform:scaleX(-1)}100%{transform:scaleX(1)}}
.cp{position:absolute;bottom:calc(9% + env(safe-area-inset-bottom,0px));text-align:center;color:#e9e2d8;direction:rtl;padding:0 18px}
.cp p{margin:0 0 12px;font-size:14px;opacity:.85}
#go{background:#f3ece3;color:#2b211b;border:0;border-radius:30px;padding:11px 28px;font:inherit;font-weight:800;cursor:pointer}
.hint{position:absolute;bottom:calc(22px + env(safe-area-inset-bottom,0px));left:50%;transform:translateX(-50%);color:#f3ece3;font-size:13px;animation:bn 1.6s ease-in-out infinite;direction:rtl}
@keyframes bn{50%{transform:translate(-50%,8px)}}
#skip{position:absolute;top:12px;right:12px;background:#ffffff26;color:#fff;border:0;border-radius:20px;padding:6px 14px;font:inherit;font-size:13px;cursor:pointer;z-index:5;backdrop-filter:blur(6px)}
body.in nav{display:none}
.tab.on{animation:fi .5s ease}
@keyframes fi{from{opacity:0}}
@media (prefers-reduced-motion:reduce){#cine{display:none}.tab.on{animation:none}body.in nav{display:flex}}
#otp{position:fixed;inset:0;z-index:1000;display:flex;align-items:center;justify-content:center;background:#0a0a0b;transition:opacity .7s,transform .7s;overflow:hidden}
#otp::before{content:"";position:absolute;inset:-20%;background:linear-gradient(115deg,transparent 38%,#5a3d0e 44%,#e0a53a 47%,#3a2608 50%,transparent 56%),linear-gradient(115deg,transparent 52%,#2a1b06 58%,#b9852a 60%,transparent 64%);opacity:.8}
#otp.out{opacity:0;transform:scale(1.06);pointer-events:none}
.gc{position:relative;width:min(92vw,380px);padding:30px 24px 24px;border-radius:26px;background:rgba(255,255,255,.07);backdrop-filter:blur(18px);-webkit-backdrop-filter:blur(18px);border:1px solid rgba(255,255,255,.16);box-shadow:0 30px 80px #000a;text-align:center;color:#fff;direction:rtl}
.ki{width:40px;height:40px;margin:0 auto 12px;border-radius:12px;display:flex;align-items:center;justify-content:center;background:#ffffff10;border:1px solid #e0a53a66;box-shadow:0 0 18px #e0a53a44}
.gc h2{margin:0 0 6px;font-size:22px}.gc h2 b{color:#f0c040}.gc h2 b.gr{color:#35d49a}
.gc p{margin:0;font-size:13px;color:#b9b3a8}
#stg2{height:170px;display:flex;align-items:center;justify-content:center;position:relative}
#bx{display:flex;gap:10px;direction:ltr}
#bx input{width:54px;height:62px;border-radius:14px;text-align:center;font-size:26px;font-weight:800;color:#fff;background:#ffffff0d;border:1.5px solid #e0a53a77;outline:0;caret-color:#f0c040;font-family:inherit;padding:0;box-shadow:0 0 12px #e0a53a22}
#bx input:focus{border-color:#f0c040;box-shadow:0 0 18px #f0c04088}
#bx.bad input{border-color:#ff5a5a;box-shadow:0 0 16px #ff5a5a77}
#bx.bad{animation:shk .5s}
@keyframes shk{20%,60%{transform:translateX(-10px)}40%,80%{transform:translateX(10px)}}
#core{position:absolute;width:120px;height:120px;display:flex;align-items:center;justify-content:center;opacity:0;transform:scale(.6);transition:.5s}
#core.on{opacity:1;transform:scale(1)}
.rg{position:absolute;inset:0;border-radius:50%;border:2px solid #35d49a55;border-top-color:#35d49a;animation:rot 1s linear infinite}
#core.ok .rg{animation:none;border-color:#35d49a;box-shadow:0 0 30px #35d49a77}
.cb{width:52px;height:52px;border-radius:14px;border:2px solid #35d49a;background:#35d49a14;display:flex;align-items:center;justify-content:center;box-shadow:0 0 18px #35d49a55}
.cb svg{width:26px;opacity:0;transition:.4s .1s}#core.ok .cb svg{opacity:1}
@keyframes rot{to{transform:rotate(360deg)}}
#ob{width:100%;border:0;border-radius:12px;padding:13px;font:inherit;font-weight:800;color:#201808;background:linear-gradient(#c8a52e,#9c7f1c);cursor:pointer;opacity:.7;transition:.3s}
#ob.rd{opacity:1}#ob.ok{background:linear-gradient(#2fd69c,#1ba87a);color:#042;opacity:1}
.sp{display:inline-block;width:14px;height:14px;border:2px solid #20180866;border-top-color:#201808;border-radius:50%;animation:rot .8s linear infinite;vertical-align:-2px;margin-inline-end:6px}
#om{min-height:20px;color:#ff7a7a;font-size:13px;margin:6px 0}
body.lock{overflow:hidden}
nav{left:10px;right:10px;bottom:calc(10px + env(safe-area-inset-bottom,0px));max-width:560px;margin:0 auto;display:block;padding:0;border:0;background:#141416;border-radius:30px;box-shadow:0 14px 34px #0008,0 0 0 1px #ffffff12;overflow-y:hidden;scrollbar-width:none}
nav::-webkit-scrollbar{display:none}
.nt{position:relative;display:flex;width:100%;min-width:max-content;height:64px}
.nt::after{content:"";position:absolute;left:16px;right:16px;bottom:0;height:2px;border-radius:2px;background:linear-gradient(90deg,transparent,#ff3b4e,transparent);opacity:.75}
.nt button{position:relative;z-index:1;flex:1 0 58px;min-width:58px;height:64px;padding:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:4px;color:#a3a3ad;font-size:11px;font-weight:600;-webkit-tap-highlight-color:transparent;transition:color .3s}
.nt button.on{color:#ff3b4e}
.nt svg{width:22px;height:22px;stroke:currentColor;fill:none;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round;transition:transform .4s cubic-bezier(.3,1.5,.5,1)}
.nt button.on svg{transform:translateY(-3px) scale(1.15)}
.nt em{font-style:normal;line-height:1}
.ind{position:absolute;left:0;bottom:0;height:46px;pointer-events:none;z-index:0;transition:transform .5s cubic-bezier(.3,1.25,.5,1),width .4s;filter:drop-shadow(0 0 6px #ff3b4e99)}
.ind svg{display:block;width:100%;height:100%}
.ind path{fill:#ff3b4e1f;stroke:#ff3b4e;stroke-width:2;vector-effect:non-scaling-stroke}
.ind .dt{position:absolute;left:50%;bottom:6px;width:4px;height:4px;margin-left:-2px;border-radius:50%;background:#ff3b4e;box-shadow:0 0 8px #ff3b4e}
.fs{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(90px + env(safe-area-inset-bottom,0px));width:min(92vw,420px);z-index:6;display:flex;align-items:center;gap:8px;background:#141416;border-radius:26px;padding:6px 10px;box-shadow:0 12px 30px #0007,0 0 0 1px #ffffff12;animation:up .45s cubic-bezier(.3,1.3,.5,1)}
@keyframes up{from{opacity:0;transform:translate(-50%,24px) scale(.9)}}
.fs svg{width:20px;height:20px;stroke:#ff3b4e;fill:none;stroke-width:2.2;stroke-linecap:round;flex:none}
.fs input[type=search]{flex:1;width:auto;margin:0;padding:8px 2px;border:0;border-radius:0;background:none;color:#f1f1f4;outline:0}
.fs button{width:28px;height:28px;border-radius:50%;border:0;background:#ffffff1a;color:#cfcfd6;cursor:pointer;font-size:13px;flex:none}
body.in .fs,body.lock .fs{display:none}
#sum{padding-bottom:70px}
.rv{opacity:0;transform:translateY(22px);transition:opacity .6s ease,transform .6s cubic-bezier(.2,.8,.2,1),box-shadow .3s,border-color .3s}
.rv.in2{opacity:1;transform:none}
.card.in2:hover{transform:translateY(-3px);box-shadow:0 12px 26px #0000001f}
details[open]{border-color:var(--pr);box-shadow:0 6px 18px #0000001a}
details[open]>.b{animation:dn .35s ease}
@keyframes dn{from{opacity:0;transform:translateY(-8px)}}
.opt{position:relative;overflow:hidden;transition:transform .15s,border-color .25s,background .25s}
.opt:not(:disabled):hover{border-color:var(--pr)}.opt:active{transform:scale(.985)}
button.p{position:relative;overflow:hidden;transition:transform .15s,filter .2s}button.p:hover{filter:brightness(1.08)}button.p:active{transform:scale(.96)}
.opt.ok{animation:pop .45s}.opt.no{animation:shk2 .4s}
@keyframes pop{40%{transform:scale(1.04)}}@keyframes shk2{25%{transform:translateX(-6px)}75%{transform:translateX(6px)}}
.res.fl{animation:fl .7s}@keyframes fl{0%{box-shadow:0 0 0 0 var(--pr)}100%{box-shadow:0 0 0 12px transparent}}
header{position:relative;overflow:hidden}header::after{content:"";position:absolute;inset:0;pointer-events:none;background:linear-gradient(110deg,transparent 35%,rgba(255,255,255,.28) 50%,transparent 65%);transform:translateX(-120%);animation:sh 5s ease-in-out infinite}
@keyframes sh{0%,55%{transform:translateX(-120%)}100%{transform:translateX(120%)}}
.rp{position:absolute;border-radius:50%;background:rgba(255,255,255,.35);transform:scale(0);animation:rp .6s ease-out forwards;pointer-events:none}@keyframes rp{to{transform:scale(1);opacity:0}}
.pb{height:5px;border-radius:5px;background:var(--pr2);margin-bottom:12px;overflow:hidden}.pb i{display:block;height:100%;background:var(--pr);border-radius:5px;transition:width .6s cubic-bezier(.2,.8,.2,1)}
#sp{position:fixed;top:0;left:0;height:3px;width:0;background:#ff3b4e;z-index:30;box-shadow:0 0 8px #ff3b4e}body.in #sp,body.lock #sp{display:none}
.cf{position:fixed;top:40%;left:50%;width:8px;height:12px;z-index:2000;pointer-events:none;animation:fall 1.7s ease-out forwards}
@keyframes fall{to{transform:translate(var(--x),var(--y)) rotate(var(--r));opacity:0}}
@media (prefers-reduced-motion:reduce){.rv{opacity:1;transform:none}header::after{animation:none}.cf{display:none}}
:root{--bg:#f2f5f8;--card:#fff;--tx:#13202b;--mu:#5a6b7a;--pr:#0a6b58;--pr2:#e2f3ee;--bd:#e1e8ed;--ac:#d6a93a;--nc:#3dd0a5}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0b1117;--card:#141d26;--tx:#e8eef3;--mu:#8da0b0;--pr:#3dd0a5;--pr2:#112c27;--bd:#233140;--ac:#f0c24b}}
:root[data-theme="dark"]{--bg:#0b1117;--card:#141d26;--tx:#e8eef3;--mu:#8da0b0;--pr:#3dd0a5;--pr2:#112c27;--bd:#233140;--ac:#f0c24b}
body{font-size:15px;background:radial-gradient(1100px 480px at 50% -120px,color-mix(in srgb,var(--pr) 12%,transparent),transparent),var(--bg)}
header#app{color:#fff;background:linear-gradient(135deg,#0a6b58 0%,#0c4a5a 100%);padding:26px 20px 32px;border-radius:0 0 30px 30px;box-shadow:0 14px 30px -14px #0a4a5a}
header#app::before{content:"";position:absolute;inset:0;pointer-events:none;background:radial-gradient(circle at 10% 125%,#ffffff22 0 24%,transparent 25%),radial-gradient(circle at 94% -25%,#f0c24b40 0 30%,transparent 31%)}
header h1{font-size:24px;letter-spacing:.2px}header p{font-size:13px;opacity:.85;margin-top:2px}
#th{background:#ffffff26;color:#fff;border:1px solid #ffffff33;backdrop-filter:blur(6px)}
main{padding:20px 14px}
.card{border-radius:18px;padding:16px 18px;box-shadow:0 1px 2px #0000000a,0 12px 28px -16px #00000033}
.card h3{display:flex;align-items:center;gap:8px;font-size:16px;margin-bottom:12px}
.card h3::before{content:"";width:4px;height:18px;border-radius:3px;background:var(--ac);flex:none}
details{border-radius:16px;box-shadow:0 1px 2px #0000000a,0 10px 24px -18px #00000040}
summary{padding:15px 18px}
summary::after{width:26px;height:26px;border-radius:50%;background:var(--pr2);display:flex;align-items:center;justify-content:center;font-size:14px;flex:none}
.eq{background:linear-gradient(135deg,#0a6b58,#0c4a5a);color:#fff;border-radius:18px;padding:18px;font-size:18px;box-shadow:0 14px 28px -14px #0a6b58}
th{background:var(--pr2);color:var(--pr);font-weight:700}
th,td{border-color:var(--bd)}
input[type=number],select,input[type=text]{border-radius:12px;padding:11px 12px;transition:border-color .2s,box-shadow .2s}
input:focus,select:focus{outline:0;border-color:var(--pr);box-shadow:0 0 0 3px color-mix(in srgb,var(--pr) 25%,transparent)}
.res{border-radius:14px;padding:12px 14px;border:1px solid color-mix(in srgb,var(--pr) 22%,transparent);line-height:1.9}
button.p{background:linear-gradient(135deg,var(--pr),color-mix(in srgb,var(--pr) 65%,#0a3d4a));border-radius:12px;padding:11px 20px;box-shadow:0 10px 20px -10px var(--pr)}
.opt{border-radius:14px;padding:12px 14px}
.big{background:linear-gradient(135deg,var(--pr),var(--ac));-webkit-background-clip:text;background-clip:text;color:transparent}
.pb i{background:linear-gradient(90deg,var(--pr),var(--ac))}
nav{background:#0f1a22}.fs{background:#0f1a22}
.nt button.on{color:var(--nc)}
.nt::after{background:linear-gradient(90deg,transparent,var(--nc),transparent)}
.ind{filter:drop-shadow(0 0 6px color-mix(in srgb,var(--nc) 60%,transparent))}
.ind path{fill:color-mix(in srgb,var(--nc) 14%,transparent);stroke:var(--nc)}
.ind .dt{background:var(--nc);box-shadow:0 0 8px var(--nc)}
.fs svg{stroke:var(--nc)}
#sp{background:linear-gradient(90deg,var(--pr),var(--ac));box-shadow:none}
header#app p{font-size:16px;font-weight:700;opacity:1;margin:0;line-height:1.8}
#cine{display:none!important}
#cafe{direction:rtl;background:#0a0907;color:#f3e9d2;font-family:Amiri,"Noto Naskh Arabic",Georgia,serif;position:relative;overflow-x:clip}
#cafe .gd{color:#d9a441}
.hr{min-height:100vh;min-height:100svh;display:flex;flex-direction:column;justify-content:center;padding:0 24px;position:relative;background:radial-gradient(ellipse at 20% 8%,#3d2c0f 0,transparent 55%),radial-gradient(ellipse at 95% 95%,#2a1c08 0,transparent 50%)}
.hh{font-size:clamp(50px,16vw,138px);line-height:1.12;margin:0;font-weight:700}
.ln{display:block;overflow:hidden;padding-bottom:.08em}.ln>span{display:block;transform:translateY(118%);transition:transform 1.1s cubic-bezier(.2,.8,.2,1)}
#cafe.go .ln>span{transform:none}.ln:nth-child(2)>span{transition-delay:.18s}
.sb{max-width:520px;font-family:system-ui,sans-serif;font-size:15px;line-height:1.9;opacity:0;transform:translateY(16px);transition:opacity 1s .8s,transform 1s .8s;margin:18px 0 0}
#cafe.go .sb,#cafe.go .bt{opacity:.85;transform:none}
.bt{display:block;margin-top:24px;background:#f3e9d2;color:#14110c;border:0;border-radius:40px;padding:13px 32px;font-family:system-ui,sans-serif;font-weight:800;font-size:15px;cursor:pointer;width:max-content;opacity:0;transform:translateY(16px);transition:opacity 1s 1s,transform 1s 1s,filter .2s}.bt:hover{filter:brightness(.92)}
.fl3{position:absolute;width:86px;height:86px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:38px;background:radial-gradient(circle at 30% 25%,#5a4217,#17120a);border:1px solid #d9a44166;box-shadow:0 18px 40px #000a;transform:translateY(calc(var(--y,0px)*-1));animation:fy 5s ease-in-out infinite}
@keyframes fy{50%{margin-top:-14px}}
.mq{overflow:hidden;border-block:1px solid #d9a44155;padding:16px 0;white-space:nowrap;background:#0d0b08}
.mq div{display:inline-block;animation:mq 24s linear infinite;font-size:clamp(28px,8vw,54px)}.mq span{margin:0 20px}.mq b{color:#d9a441;font-weight:400}
@keyframes mq{to{transform:translateX(50%)}}
.sec{padding:90px 24px}
.eb{color:#d9a441;font-family:system-ui,sans-serif;font-size:13px;margin-bottom:10px}
.t2{font-size:clamp(34px,10vw,72px);line-height:1.2;margin:0 0 16px;font-weight:700}
.p3{font-family:system-ui,sans-serif;font-size:15px;line-height:1.9;opacity:.8;max-width:520px}
.rv3{opacity:0;transform:translateY(34px);transition:opacity .9s,transform .9s cubic-bezier(.2,.8,.2,1)}.rv3.v{opacity:1;transform:none}
.im{aspect-ratio:4/4.6;border-radius:24px;margin-bottom:26px;position:relative;overflow:hidden;background:repeating-linear-gradient(0deg,transparent 0 33px,#d9a44126 34px),linear-gradient(160deg,#3d2c0f,#0f0c07);clip-path:inset(0 0 100% 0);transition:clip-path 1.3s cubic-bezier(.7,0,.2,1);display:flex;align-items:center;justify-content:center;font-size:84px;color:#d9a441}.im.v{clip-path:inset(0)}
.gr3{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:12px;margin-top:26px}
.cd3{background:#14110c;border:1px solid #d9a44133;border-radius:20px;padding:20px 16px;cursor:pointer;transition:transform .3s,border-color .3s,opacity .9s}.cd3:hover{transform:translateY(-5px);border-color:#d9a441}
.cd3 b{display:block;font-size:30px;margin:6px 0}.cd3 small{font-family:system-ui,sans-serif;opacity:.7;font-size:12.5px;line-height:1.6;display:block}
.pn{position:sticky;top:9vh;margin-bottom:26px;background:linear-gradient(145deg,#1d160c,#0e0b07);border:1px solid #d9a44144;border-radius:28px;padding:26px 22px;min-height:50vh;display:flex;flex-direction:column;justify-content:space-between;box-shadow:0 -20px 40px #0008}
.pn:nth-of-type(2){top:12vh}.pn:nth-of-type(3){top:15vh}
.nm{font-size:110px;color:#d9a441;line-height:1;opacity:.9}.pn h3{font-size:34px;margin:0 0 8px}
.cta{text-align:center;padding:110px 24px 130px;background:radial-gradient(ellipse at 50% 100%,#3d2c0f,transparent 60%)}.cta .bt{margin:26px auto 0;opacity:1;transform:none}
@media (prefers-reduced-motion:reduce){.ln>span,.sb,.bt{transform:none;opacity:1}.mq div,.fl3{animation:none}.im{clip-path:none}}
#cafe,#cine{display:none!important}
#intro{position:fixed;inset:0;z-index:900;display:flex;align-items:center;justify-content:center;direction:rtl;overflow:hidden}
.cu{position:absolute;left:0;right:0;height:50.3%;background:#0a0907;transition:transform 1.1s cubic-bezier(.76,0,.24,1);z-index:0}
.cu.t{top:0;background:radial-gradient(ellipse at 50% 130%,#3d2c0f 0,#0a0907 70%)}.cu.b{bottom:0;background:radial-gradient(ellipse at 50% -30%,#2a1c08 0,#0a0907 70%)}
#intro.open .t{transform:translateY(-101%)}#intro.open .b{transform:translateY(101%)}
.ic{position:relative;z-index:1;text-align:center;color:#f3e9d2;transition:opacity .5s,transform .8s}
#intro.open .ic{opacity:0;transform:scale(1.15)}
.rg2{width:150px;height:150px;position:relative;margin:0 auto 24px}.rg2 svg{width:100%;height:100%;transform:rotate(-90deg)}
.rg2 circle{fill:none;stroke-width:3;stroke-linecap:round}.rg2 .bg{stroke:#d9a44122}.rg2 .fg{stroke:#d9a441;stroke-dasharray:408.4;stroke-dashoffset:408.4;filter:drop-shadow(0 0 6px #d9a44199)}
#intro.go .fg{animation:dr 2.4s cubic-bezier(.6,0,.2,1) forwards}@keyframes dr{to{stroke-dashoffset:0}}
.rg2 b{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;font:700 32px Amiri,Georgia,serif;color:#d9a441;direction:ltr}
.il{display:block;overflow:hidden;padding-bottom:.1em;font:700 clamp(30px,9vw,54px)/1.25 Amiri,"Noto Naskh Arabic",serif}.il>span{display:block;transform:translateY(120%);transition:transform 1s cubic-bezier(.2,.8,.2,1)}
#intro.go .il>span{transform:none}.il:nth-of-type(2)>span{transition-delay:.25s;color:#d9a441}
.sk{position:absolute;bottom:calc(28px + env(safe-area-inset-bottom,0px));z-index:2;color:#a89a7e;font:13px system-ui,sans-serif;background:none;border:0;cursor:pointer}
#ft{max-width:860px;margin:6px auto 0;padding:10px 14px 26px;text-align:center;color:var(--mu);font-size:13px}
#ft .ln2{display:block;width:56px;height:3px;border-radius:3px;margin:0 auto 12px;background:linear-gradient(90deg,var(--pr),var(--ac))}
#ft p{margin:0}
#ft .cr{margin-top:6px;font-weight:600}#ft .cr b{color:var(--pr)}
.cr2{display:block;margin-top:18px;font:600 13px system-ui,sans-serif;color:#a89a7e;opacity:0;transition:opacity 1s 1.2s}#intro.go .cr2{opacity:1}
.gc{animation:cin .7s cubic-bezier(.2,.8,.2,1)}@keyframes cin{from{opacity:0;transform:translateY(24px) scale(.97)}}
.gc.sh{animation:shk .5s}
.lo{width:66px;height:66px;margin:0 auto 14px;border-radius:22px;display:flex;align-items:center;justify-content:center;font:700 34px Amiri,Georgia,serif;color:#d9a441;background:radial-gradient(circle at 30% 25%,#5a4217,#17120a);border:1px solid #d9a44166;box-shadow:0 10px 30px #d9a44133}
.fld{position:relative;margin-bottom:12px;text-align:right}
.fld input:not([type=checkbox]){width:100%;height:54px;border-radius:14px;border:1.5px solid #ffffff22;background:#ffffff0d;color:#fff;padding:20px 46px 0 46px;font:inherit;font-size:15px;outline:0;transition:border-color .25s,box-shadow .25s,background .25s}
.fld input:focus{border-color:#d9a441;background:#ffffff14;box-shadow:0 0 0 3px #d9a44133}
.fld label{position:absolute;right:46px;top:17px;font-size:14px;color:#b9b3a8;pointer-events:none;transition:all .2s;transform-origin:right}
.fld input:focus+label,.fld input:not(:placeholder-shown)+label{top:8px;font-size:11px;color:#f0c040}
.fld .ic{position:absolute;right:15px;top:17px;width:20px;height:20px;stroke:#b9b3a8;transition:stroke .25s}.fld:focus-within .ic{stroke:#f0c040}
.eye{position:absolute;left:8px;top:9px;width:36px;height:36px;border:0;background:none;color:#b9b3a8;cursor:pointer;font-size:17px;border-radius:50%}.eye:hover{background:#ffffff14}
.rw{display:flex;justify-content:space-between;align-items:center;font-size:13px;margin:6px 0 12px;color:#cfc8bb}
.rw label{display:flex;gap:8px;align-items:center;cursor:pointer}.rw input{accent-color:#d9a441;width:16px;height:16px}
.rw a{color:#f0c040;cursor:pointer}.rw a:hover{text-decoration:underline}
#le{min-height:20px;color:#ff7a7a;font-size:13px;margin-bottom:8px;text-align:right}
#lc{font-size:12px;color:#f0c040;text-align:right;margin:-4px 0 4px}
.gb{width:100%;border:0;border-radius:14px;padding:14px;font:inherit;font-weight:800;font-size:16px;color:#201808;background:linear-gradient(#e6c24e,#b88f1f);cursor:pointer;box-shadow:0 14px 26px -12px #d9a441cc;transition:transform .15s,filter .2s,opacity .2s}.gb:hover{filter:brightness(1.07)}.gb:active{transform:scale(.97)}.gb:disabled{opacity:.7;cursor:default}
.lf2{margin-top:18px;font-size:12px;color:#8f8672}
.sw{margin-top:14px;font-size:13px;color:#cfc8bb}.sw a{color:#f0c040;cursor:pointer}.sw a:hover{text-decoration:underline}
#re2{min-height:20px;color:#ff7a7a;font-size:13px;margin-bottom:8px;text-align:right}
.wa{display:block;margin:0 0 12px;padding:12px;border-radius:14px;background:#25d366;color:#072b14;font-weight:800;text-decoration:none;font-size:15px;box-shadow:0 12px 24px -12px #25d366}
.wa[hidden]{display:none}
.sw,#rgc,#wa{display:none!important}
.shr{display:flex;gap:10px;flex-wrap:wrap;align-items:center;margin-top:16px;padding-top:14px;border-top:1px dashed var(--bd)}
.shr .who{width:100%;font-size:13px;color:var(--mu)}
.wa2{display:inline-block;padding:11px 16px;border-radius:12px;background:#25d366;color:#072b14;font-weight:800;text-decoration:none;font-size:14px}
.shr button.p{margin-top:0}
#intro.open .sk{opacity:0;pointer-events:none}
.rw label{color:#cfc8bb;font-size:13px}
</style>
</head>
<body>
<section id="cafe">
<div class="hr"><div class="fl3" style="top:12%;left:8%">🧾</div><div class="fl3" style="top:26%;right:10%;width:64px;height:64px;font-size:28px">📊</div><div class="fl3" style="bottom:14%;left:22%;width:70px;height:70px;font-size:30px">🧮</div>
<h2 class="hh"><span class="ln"><span>محاسبة</span></span><span class="ln"><span>بدقة <i class="gd" style="font-style:normal">وأناقة</i></span></span></h2>
<p class="sb">ملخص وقيود وزكاة وضريبة وتكاليف واختبارات، كلها في مكان واحد.</p><button class="bt" id="cfs">ابدأ التعلّم</button></div>
<div class="mq"><div><span>القيود</span><b>✦</b><span>الزكاة والضريبة</span><b>✦</b><span>التكاليف</span><b>✦</b><span>المراجعة</span><b>✦</b><span>المبادئ</span><b>✦</b><span>القيود</span><b>✦</b><span>الزكاة والضريبة</span><b>✦</b><span>التكاليف</span><b>✦</b><span>المراجعة</span><b>✦</b><span>المبادئ</span><b>✦</b></div></div>
<div class="sec"><div class="im">١٢٣</div><div class="eb rv3">من البداية إلى النهاية</div><h2 class="t2 rv3">من دفتر اليومية <span class="gd">إلى القوائم المالية</span></h2><p class="p3 rv3">سجّل القيد، رحّله للأستاذ، استخرج ميزان المراجعة، ثم شاهد قائمة الدخل والمركز المالي تتكونان أمامك.</p></div>
<div class="sec" style="padding-top:20px"><div class="eb rv3">أقسام التطبيق</div><h2 class="t2 rv3">أقسام صغيرة، <span class="gd">معرفة كبيرة.</span></h2>
<div class="gr3"><div class="cd3 rv3" data-go="0">📚<b>الملخص</b><small>مبادئ وقوانين ومراجعة</small></div><div class="cd3 rv3" data-go="2" style="transition-delay:.1s">🧮<b>الحاسبات</b><small>النسب والتعادل والإهلاك</small></div><div class="cd3 rv3" data-go="3" style="transition-delay:.2s">📝<b>الاختبارات</b><small>50 سؤالاً مع الدرجات</small></div><div class="cd3 rv3" data-go="5" style="transition-delay:.3s">🕌<b>الزكاة</b><small>قواعد وحاسبات الضريبة</small></div></div></div>
<div class="sec"><div class="eb rv3">ما نقدّمه</div><h2 class="t2 rv3">ثلاثة أشياء <span class="gd">تستخدمها كل يوم.</span></h2>
<div class="pn"><div class="nm">01</div><div><h3>القيد المزدوج</h3><p class="p3">سجّل عملياتك ودع التطبيق يبني ميزان المراجعة والقوائم تلقائياً.</p></div></div>
<div class="pn"><div class="nm">02</div><div><h3>الزكاة والضريبة</h3><p class="p3">احسب الوعاء الزكوي والقيمة المضافة والاستقطاع بخطوات واضحة.</p></div></div>
<div class="pn"><div class="nm">03</div><div><h3>التكاليف والتعادل</h3><p class="p3">قائمة التكلفة ونقطة التعادل والانحرافات في حاسبات جاهزة.</p></div></div></div>
<div class="cta"><h2 class="t2 rv3">جاهز <span class="gd">نبدأ؟</span></h2><button class="bt" id="cfe">ادخل إلى التطبيق</button></div>
</section>
<section id="cine" aria-label="مقدمة"><div class="stg">
<div class="sc" id="s1"><div class="tx l" id="ct1">نحن دقة</div><div class="tx r" id="ct2">نحن وضوح</div><div class="pw" id="pw"></div></div>
<div class="sc" id="cl"></div>
<div class="sc" id="s2"><span class="w l" id="cw1">احسب</span><svg id="jet" viewBox="0 0 200 420" aria-hidden="true"><defs><linearGradient id="gd" x1="0" x2="1"><stop offset="0" stop-color="#d9b88f"/><stop offset=".5" stop-color="#f6e6cb"/><stop offset="1" stop-color="#d0a874"/></linearGradient></defs><g fill="url(#gd)" stroke="#b98d5e" stroke-width="2"><path d="M90 150L8 290L10 306L92 262Z"/><path d="M110 150L192 290L190 306L108 262Z"/><path d="M92 350L50 400L52 410L96 385Z"/><path d="M108 350L150 400L148 410L104 385Z"/><path d="M100 10C112 40 114 120 114 300L100 410L86 300C86 120 88 40 100 10Z"/></g><path d="M100 40V300" stroke="#6aa6d8" stroke-width="3" stroke-dasharray="2 6"/></svg><span class="w r" id="cw2">بدقة</span></div>
<div class="sc" id="s3"><div class="big3" id="cb3">عالمي</div><svg id="gb" viewBox="0 0 220 220" aria-hidden="true"><defs><radialGradient id="gg" cx=".35" cy=".3"><stop offset="0" stop-color="#f4efe8"/><stop offset="1" stop-color="#8d8478"/></radialGradient></defs><circle cx="110" cy="110" r="100" fill="url(#gg)"/><g fill="none" stroke="#3a322b" stroke-width="1.2"><ellipse cx="110" cy="110" rx="100" ry="30"/><ellipse cx="110" cy="110" rx="100" ry="62"/><path d="M10 110H210"/><g id="mr"><ellipse cx="110" cy="110" rx="100" ry="100"/><ellipse cx="110" cy="110" rx="100" ry="100"/><ellipse cx="110" cy="110" rx="100" ry="100"/><ellipse cx="110" cy="110" rx="100" ry="100"/></g></g></svg><div class="cp" id="cp"><p>معايير دولية وأنظمة محلية، ملخص وحاسبات واختبارات في مكان واحد</p><button id="go">ابدأ الآن</button></div></div>
<div class="hint" id="hn">مرّر لأسفل ↓</div><button id="skip">تخطّي</button>
</div></section>
<div id="intro"><div class="cu t"></div><div class="cu b"></div><div class="ic"><div class="rg2"><svg viewBox="0 0 150 150" aria-hidden="true"><circle class="bg" cx="75" cy="75" r="65"/><circle class="fg" cx="75" cy="75" r="65"/></svg><b id="inum">0%</b></div><span class="il"><span>محاسبة</span></span><span class="il"><span>بدقة وأناقة</span></span><span class="cr2">© جميع الحقوق محفوظة لـ بلال</span></div><button class="sk" id="isk">تخطّي</button></div>
<header id="app"><div><p>ملخص + محاسبة + زكاة وضريبة + تكاليف + اختبارات</p></div><button id="th" aria-label="الوضع">🌓</button></header>
<main>
<section class="tab on" id="t0">
<div class="eq">الأصول = الالتزامات + حقوق الملكية</div>
<div class="fs"><svg viewBox="0 0 24 24" aria-hidden="true"><circle cx="11" cy="11" r="7"/><path d="M20 20l-4-4"/></svg><input type="search" id="q" placeholder="ابحث في الملخص…"><button id="qx" aria-label="مسح">✕</button></div>
<div id="sum"></div>
<details><summary>📚 المراجع</summary><div class="b">
<p style="margin:4px 0"><b>أولاً: الأنظمة والجهات الرسمية</b></p><ul>
<li>هيئة الزكاة والضريبة والجمارك (زاتكا): الموقع الرسمي — <a href="https://zatca.gov.sa" target="_blank" rel="noopener">zatca.gov.sa</a> (اللوائح والأدلة الإرشادية للزكاة وضريبة الدخل والقيمة المضافة والاستقطاع).</li>
<li>نظام ضريبة القيمة المضافة، المرسوم الملكي رقم (م/113) لعام 1438هـ، ولائحته التنفيذية.</li>
<li>نظام ضريبة الدخل السعودي ولائحته التنفيذية، واللائحة التنفيذية لجباية الزكاة.</li>
<li>الهيئة السعودية للمراجعين والمحاسبين (SOCPA): المعايير المعتمدة في المملكة — <a href="https://socpa.org.sa" target="_blank" rel="noopener">socpa.org.sa</a>.</li>
<li>موقع هيئة الخبراء بمجلس الوزراء للاطلاع على نصوص الأنظمة — <a href="https://laws.boe.gov.sa" target="_blank" rel="noopener">laws.boe.gov.sa</a>.</li></ul>
<p style="margin:10px 0 4px"><b>ثانياً: المعايير الدولية</b></p><ul>
<li>المعايير الدولية للتقارير المالية (IFRS) — <a href="https://www.ifrs.org" target="_blank" rel="noopener">ifrs.org</a>.</li>
<li>معايير المراجعة الدولية (ISA) من مجلس IAASB — <a href="https://www.iaasb.org" target="_blank" rel="noopener">iaasb.org</a>.</li></ul>
<p style="margin:10px 0 4px"><b>ثالثاً: كتب مرجعية معروفة</b></p><ul>
<li>Kieso, Weygandt &amp; Warfield, <i>Intermediate Accounting</i> — للمحاسبة المالية.</li>
<li>Horngren, Datar &amp; Rajan, <i>Cost Accounting: A Managerial Emphasis</i> — لمحاسبة التكاليف.</li>
<li>Arens, Elder &amp; Beasley, <i>Auditing and Assurance Services</i> — للمراجعة.</li></ul>
<p style="margin:10px 0 4px"><b>رابعاً: مصادر شخصية</b></p><ul><li>ملخص مادة المراجعة (الفصول العشرة) المقدم من مادة المقرر.</li></ul>
<p class="ex">ملاحظة: هذه قائمة مصادر عامة للمواضيع المذكورة، وليست توثيقاً لكل معلومة. عند التسليم أضف الطبعة وسنة النشر وتاريخ الاطلاع، وراجع المعدلات والمواعيد من الموقع الرسمي لزاتكا، لأنها تتغير.</p>
</div></details>
</section>

<section class="tab" id="t1">
<div class="card"><h3>قواعد المدين والدائن</h3><div class="wrap"><table><tr><th>الحساب</th><th>يزيد بـ</th><th>ينقص بـ</th></tr>
<tr><td>الأصول</td><td>مدين</td><td>دائن</td></tr><tr><td>المصروفات</td><td>مدين</td><td>دائن</td></tr>
<tr><td>الالتزامات</td><td>دائن</td><td>مدين</td></tr><tr><td>حقوق الملكية</td><td>دائن</td><td>مدين</td></tr>
<tr><td>الإيرادات</td><td>دائن</td><td>مدين</td></tr></table></div>
<p class="ex">القاعدة الذهبية: مجموع المدين = مجموع الدائن في كل قيد.</p></div>
<div class="card"><h3>🎯 تدرب: ما طبيعة الرصيد؟</h3><div id="tr"></div></div>
<div class="card"><h3>مثال قيد يومية</h3><p>شراء بضاعة نقداً بـ 1,000 ريال:</p>
<p>من ح/ المشتريات (مدين) <b>1,000</b><br>إلى ح/ النقدية (دائن) <b>1,000</b></p></div>
</section>

<section class="tab" id="t2">
<div class="card"><h3>المعادلة المحاسبية</h3><div class="grid"><div><label>الأصول</label><input type="number" id="a1"></div><div><label>الالتزامات</label><input type="number" id="a2"></div></div><div class="res" id="r1">حقوق الملكية = —</div></div>
<div class="card"><h3>النسب المالية</h3><div class="grid">
<div><label>أصول متداولة</label><input type="number" id="f1"></div><div><label>خصوم متداولة</label><input type="number" id="f2"></div>
<div><label>صافي الربح</label><input type="number" id="f3"></div><div><label>المبيعات</label><input type="number" id="f4"></div>
<div><label>إجمالي الديون</label><input type="number" id="f5"></div><div><label>إجمالي الأصول</label><input type="number" id="f6"></div></div>
<div class="res" id="r2">أدخل الأرقام</div></div>
<div class="card"><h3>نقطة التعادل</h3><div class="grid">
<div><label>التكاليف الثابتة</label><input type="number" id="b1"></div><div><label>سعر بيع الوحدة</label><input type="number" id="b2"></div><div><label>التكلفة المتغيرة للوحدة</label><input type="number" id="b3"></div></div>
<div class="res" id="r3">—</div></div>
<div class="card"><h3>الإهلاك</h3><div class="grid">
<div><label>تكلفة الأصل</label><input type="number" id="d1"></div><div><label>قيمة الخردة</label><input type="number" id="d2"></div><div><label>العمر (سنوات)</label><input type="number" id="d3"></div></div>
<div class="res" id="r4">—</div></div>
</section>

<section class="tab" id="t3"><div class="card" id="qz"></div></section>
<section class="tab" id="t6">
<h3 style="color:var(--pr);margin:4px 0 10px">🏭 محاسبة التكاليف</h3>
<details open><summary>أنواع التكاليف ومعادلاتها</summary><div class="b"><ul>
<li><b>حسب العلاقة بالمنتج:</b> مباشرة (مواد، أجور) وغير مباشرة (إيجار المصنع، كهرباء، إهلاك).</li>
<li><b>حسب السلوك:</b> ثابتة (لا تتغير بتغير الإنتاج)، متغيرة (تتغير معه)، شبه متغيرة.</li>
<li><b>حسب الوظيفة:</b> إنتاجية، تسويقية، إدارية وتمويلية. وتُقسم إلى تكلفة منتج (تُحمل على المخزون) وتكلفة فترة (تظهر مصروفاً).</li>
<li><b>التكلفة الأولية</b> = مواد مباشرة + أجور مباشرة.</li>
<li><b>تكلفة التحويل</b> = أجور مباشرة + تكاليف صناعية غير مباشرة.</li>
<li><b>تكلفة الإنتاج</b> = مواد + أجور + تكاليف غير مباشرة، وتكلفة الوحدة = الإجمالي ÷ عدد الوحدات.</li>
<li><b>الأنظمة:</b> أوامر الإنتاج (للطلبيات الخاصة)، المراحل (للإنتاج المستمر)، المعيارية (مقارنة الفعلي بالمعيار وتحليل الانحرافات).</li></ul></div></details>
<details><summary>مفاهيم أساسية وفروق</summary><div class="b"><ul>
<li><b>التكلفة:</b> ما يُضحَّى به للحصول على سلعة أو خدمة، وتبقى أصلاً (مخزوناً) حتى تُستنفد.</li>
<li><b>المصروف:</b> تكلفة استُنفدت في تحقيق الإيراد. <b>الخسارة:</b> تضحية بلا منفعة.</li>
<li><b>أهداف المحاسبة:</b> تحديد تكلفة المنتج، التسعير، الرقابة وتخفيض التكاليف، دعم قرارات الإدارة.</li>
<li><b>الفرق عن المالية:</b> التكاليف داخلية وتفصيلية للإدارة، والمالية قوائم خارجية للمستخدمين.</li>
<li><b>الملائمة للقرار:</b> التكاليف الغارقة لا تؤثر في القرار، وتكلفة الفرصة البديلة تؤثر فيه، والتكاليف الملائمة هي المستقبلية المختلفة بين البدائل.</li></ul></div></details>
<details><summary>قوانين قائمة تكلفة الإنتاج والبضاعة المباعة</summary><div class="b"><ul>
<li>المواد المستخدمة = مخزون المواد أول + المشتريات + مصروفات الشراء − المردودات والخصم − مخزون المواد آخر.</li>
<li>تكلفة الإنتاج خلال الفترة = المواد المستخدمة + الأجور المباشرة + التكاليف الصناعية غير المباشرة.</li>
<li>تكلفة الإنتاج التام = تكلفة الإنتاج + إنتاج تحت التشغيل أول − إنتاج تحت التشغيل آخر.</li>
<li>تكلفة البضاعة المباعة = الإنتاج التام + مخزون تام أول − مخزون تام آخر.</li>
<li>مجمل الربح = المبيعات − تكلفة البضاعة المباعة، وصافي الربح = المجمل − مصروفات البيع والإدارة.</li></ul></div></details>
<details><summary>تحميل التكاليف غير المباشرة</summary><div class="b"><ul>
<li>معدل التحميل = التكاليف غير المباشرة المقدرة ÷ أساس التحميل المقدر (ساعات عمل مباشرة، ساعات آلة، أجور مباشرة، أو وحدات).</li>
<li>التكلفة المحملة = المعدل × الأساس الفعلي.</li>
<li>الانحراف = الفعلية − المحملة، فإن زادت الفعلية فالتحميل ناقص، وإن قلّت فالتحميل زائد، ويُعالج في نهاية الفترة.</li></ul></div></details>
<details><summary>التحليل بين التكلفة والحجم والربح (CVP)</summary><div class="b"><ul>
<li>هامش المساهمة للوحدة = سعر البيع − التكلفة المتغيرة للوحدة.</li>
<li>نسبة هامش المساهمة = هامش المساهمة ÷ سعر البيع.</li>
<li>نقطة التعادل بالوحدات = الثابتة ÷ هامش مساهمة الوحدة، وبالقيمة = الثابتة ÷ نسبة الهامش.</li>
<li>الوحدات المستهدفة = (الثابتة + الربح المستهدف) ÷ هامش مساهمة الوحدة.</li>
<li>هامش الأمان = (المبيعات الفعلية − مبيعات التعادل) ÷ المبيعات الفعلية.</li>
<li>الربح = (الوحدات × هامش المساهمة) − الثابتة.</li></ul></div></details>
<details><summary>تكاليف المراحل</summary><div class="b"><ul>
<li>الوحدات المكافئة = وحدات تامة + (وحدات تحت التشغيل × نسبة الإنجاز).</li>
<li>تكلفة الوحدة المكافئة = تكلفة العنصر ÷ الوحدات المكافئة (تُحسب للمواد وللتحويل منفصلتين).</li>
<li>تكلفة الإنتاج تحت التشغيل = الوحدات المكافئة × تكلفة الوحدة المكافئة.</li>
<li>الفاقد الطبيعي يُحمَّل على الجيد، والفاقد غير الطبيعي يُحمَّل خسارةً.</li></ul></div></details>
<details><summary>التكاليف المعيارية والانحرافات</summary><div class="b"><ul>
<li>انحراف سعر المواد = (السعر الفعلي − المعياري) × الكمية الفعلية.</li>
<li>انحراف كمية المواد = (الكمية الفعلية − المعيارية للإنتاج الفعلي) × السعر المعياري.</li>
<li>انحراف معدل الأجور = (المعدل الفعلي − المعياري) × الساعات الفعلية.</li>
<li>انحراف كفاءة الأجور = (الساعات الفعلية − المعيارية) × المعدل المعياري.</li>
<li>إذا زادت الفعلية على المعيارية فالانحراف غير مناسب (U)، وإن قلّت فمناسب (F).</li></ul></div></details>
<details><summary>الموازنات التقديرية</summary><div class="b"><ul>
<li>تبدأ بموازنة المبيعات ثم الإنتاج ثم المواد والأجور والتكاليف غير المباشرة ثم النقدية.</li>
<li>أنواعها: ثابتة، مرنة (تتغير مع النشاط)، مستمرة، وصفرية الأساس.</li>
<li>الرقابة بمقارنة الفعلي بالمخطط وتحليل الانحرافات واتخاذ الإجراء التصحيحي.</li></ul></div></details>
<div class="card"><h3>🧮 قائمة تكلفة الإنتاج والتسعير</h3><div class="grid"><div><label>مواد مباشرة</label><input type="number" id="c1"></div><div><label>أجور مباشرة</label><input type="number" id="c2"></div><div><label>تكاليف غير مباشرة</label><input type="number" id="c3"></div><div><label>عدد الوحدات</label><input type="number" id="c4"></div><div><label>هامش الربح على التكلفة %</label><input type="number" id="c5"></div></div><div class="res" id="rc">—</div></div>
<div class="card"><h3>📈 حاسبة CVP وهامش الأمان</h3><div class="grid"><div><label>سعر بيع الوحدة</label><input type="number" id="p1"></div><div><label>التكلفة المتغيرة للوحدة</label><input type="number" id="p2"></div><div><label>التكاليف الثابتة</label><input type="number" id="p3"></div><div><label>الربح المستهدف</label><input type="number" id="p4"></div><div><label>الوحدات المباعة فعلياً</label><input type="number" id="p5"></div></div><div class="res" id="rp">—</div></div>
<div class="card"><h3>⚖️ حاسبة انحرافات المواد</h3><div class="grid"><div><label>السعر المعياري</label><input type="number" id="q1"></div><div><label>السعر الفعلي</label><input type="number" id="q2"></div><div><label>الكمية المعيارية للإنتاج الفعلي</label><input type="number" id="q3"></div><div><label>الكمية الفعلية</label><input type="number" id="q4"></div></div><div class="res" id="rq">—</div></div>
<h3 style="color:var(--pr);margin:14px 0 10px">🏛️ المنشآت الربحية وغير الربحية</h3>
<div class="card"><div class="wrap"><table><tr><th>البند</th><th>ربحية</th><th>غير ربحية</th></tr>
<tr><td>الهدف</td><td>تحقيق الربح للمالكين</td><td>خدمة المجتمع وتحقيق رسالة الجهة</td></tr>
<tr><td>مصدر التمويل</td><td>أصحاب الملكية والمبيعات</td><td>تبرعات ومنح واشتراكات</td></tr>
<tr><td>ناتج النشاط</td><td>صافي ربح أو خسارة</td><td>فائض أو عجز (لا يُوزّع على أعضائها)</td></tr>
<tr><td>حقوق الملكية</td><td>رأس مال وأرباح محتجزة</td><td>صافي الأصول (غير مقيدة ومقيدة)</td></tr>
<tr><td>القوائم</td><td>الدخل، المركز المالي، التدفقات، حقوق الملكية</td><td>قائمة الأنشطة، المركز المالي، التدفقات</td></tr>
<tr><td>المساءلة</td><td>للملاك والمستثمرين</td><td>للمتبرعين والجهات المشرفة</td></tr>
<tr><td>معيار النجاح</td><td>الربحية والعائد</td><td>كفاءة إنفاق الموارد على البرامج</td></tr></table></div></div>
<details><summary>قواعد المحاسبة في المنشآت غير الربحية</summary><div class="b"><ul>
<li><b>محاسبة الصناديق:</b> تُفصل الموارد حسب الغرض.</li>
<li><b>موارد مقيدة:</b> من متبرع حدد لها غرضاً معيناً فلا تُنفق في غيره. <b>غير مقيدة:</b> للإدارة حرية استخدامها.</li>
<li><b>التبرعات تُثبت إيراداً</b> عند استحقاقها أو تلقيها.</li>
<li><b>تصنيف المصروفات:</b> برامج وأنشطة، إدارية وعمومية، وجمع تبرعات.</li>
<li>تخضع لأنظمة ولوائح الجهة الإشرافية، وقد تتمتع بإعفاءات ضريبية حسب النظام.</li></ul></div></details>
<div class="card"><h3>🤝 حاسبة الفائض للجمعية غير الربحية</h3><div class="grid"><div><label>تبرعات غير مقيدة</label><input type="number" id="n1"></div><div><label>تبرعات مقيدة</label><input type="number" id="n2"></div><div><label>إيرادات أخرى</label><input type="number" id="n3"></div><div><label>مصروفات البرامج</label><input type="number" id="n4"></div><div><label>مصروفات إدارية</label><input type="number" id="n5"></div><div><label>مصروفات جمع التبرعات</label><input type="number" id="n6"></div></div><div class="res" id="rn">—</div></div>
</section>
<section class="tab" id="t5">
<h3 style="color:var(--pr);margin:4px 0 10px">📜 القواعد التفصيلية</h3>
<details open><summary>١. قواعد الزكاة</summary><div class="b"><ul>
<li><b>من تجب عليه:</b> المنشآت المملوكة لسعوديين أو خليجيين، بحسب نسبة ملكيتهم.</li>
<li><b>المعدل:</b> 2.5% من الوعاء الزكوي، وتُحسب على الوعاء (الأصول الزكوية) لا على الربح، فقد تُستحق حتى مع الخسارة.</li>
<li><b>الوعاء بطريقة صافي حقوق الملكية:</b> حقوق الملكية (رأس المال، الاحتياطيات، الأرباح المبقاة) + القروض طويلة الأجل + الربح المعدل − (صافي الأصول الثابتة + الأصول غير المتداولة الأخرى + الحسومات).</li>
<li><b>الحد الأدنى للوعاء:</b> صافي الربح المعدل، ويُعتمد الأعلى بين الطريقتين.</li>
<li><b>الحول:</b> تُحسب الزكاة على سنة مالية كاملة (حولان الحول).</li>
<li><b>الإقرار:</b> خلال 120 يوماً من نهاية السنة المالية، مع القوائم المالية، ويُسدد المستحق عند التقديم.</li>
<li><b>الأفراد:</b> 2.5% على عروض التجارة والنقد إذا بلغت النصاب (ما يعادل 85 جراماً من الذهب) ومضى عليها الحول.</li>
<li><b>الجهة:</b> هيئة الزكاة والضريبة والجمارك (زاتكا).</li></ul></div></details>
<details><summary>٢. قواعد ضريبة القيمة المضافة</summary><div class="b"><ul>
<li><b>المعدل:</b> 15% على التوريدات الخاضعة، وهي ضريبة غير مباشرة يتحملها المستهلك النهائي.</li>
<li><b>التسجيل:</b> إلزامي عند تجاوز الإيرادات السنوية 375,000 ريال، واختياري عند تجاوز 187,500 ريال.</li>
<li><b>معدل الصفر:</b> الصادرات والنقل الدولي، ويحق للمنشأة استرداد ضريبة مدخلاتها.</li>
<li><b>المعفاة:</b> الخدمات المالية، وتأجير العقار السكني، ولا يحق استرداد ضريبة المدخلات المتعلقة بها.</li>
<li><b>الصافي المستحق:</b> ضريبة المخرجات − ضريبة المدخلات القابلة للخصم، وإن كانت سالبة فهي رصيد دائن.</li>
<li><b>الفاتورة:</b> يجب أن تتضمن الرقم الضريبي وقيمة الضريبة بشكل منفصل، والفوترة الإلكترونية إلزامية.</li>
<li><b>الإقرار:</b> شهرياً للمنشآت فوق 40 مليون ريال، وربع سنوياً لغيرها.</li>
<li><b>المستندات:</b> يجب الاحتفاظ بالفواتير والسجلات للمدة النظامية، ويترتب على التأخير أو الخطأ غرامات.</li></ul></div></details>
<details><summary>٣. قواعد ضريبة الدخل</summary><div class="b"><ul>
<li><b>المعدل:</b> 20% على صافي الربح المعدل الخاص بحصة الشركاء غير السعوديين وغير الخليجيين.</li>
<li><b>الشركات المختلطة:</b> الزكاة على حصة السعودي/الخليجي، وضريبة الدخل على حصة الأجنبي، ولكل منهما أساس حسابه.</li>
<li><b>الربح الضريبي:</b> الإيرادات − المصروفات المقبولة نظاماً (± تسويات).</li>
<li><b>المصروفات المقبولة:</b> ما كان لازماً ومرتبطاً بالنشاط ومدعوماً بمستندات، ومنها الإهلاك بالنسب النظامية.</li>
<li><b>غير المقبولة:</b> المصروفات الشخصية للشركاء، والغرامات والعقوبات، وما لا مستند له.</li>
<li><b>الخسائر:</b> تُرحَّل لسنوات لاحقة بحدود نظامية.</li>
<li><b>الإقرار:</b> خلال 120 يوماً من نهاية السنة المالية.</li></ul></div></details>
<details><summary>٤. قواعد الاستقطاع</summary><div class="b"><ul>
<li>تُستقطع على الدفعات من مقيم لغير مقيم، ويلتزم الدافع بالخصم والتوريد.</li>
<li>المعدلات: 5% (خدمات فنية، فوائد، أرباح موزعة)، 15% (إتاوات)، 20% (رسوم إدارة).</li>
<li>يُورَّد المبلغ لزاتكا خلال أول 10 أيام من الشهر التالي للدفع.</li>
<li>عدم الاستقطاع يجعل الدافع مسؤولاً عن الضريبة وغرامة التأخير.</li></ul></div></details>
<details><summary>٥. الفرق بين الزكاة والضريبة</summary><div class="b"><div class="wrap"><table><tr><th>البند</th><th>الزكاة</th><th>ضريبة الدخل</th></tr><tr><td>الأساس</td><td>الوعاء (صافي الأصول)</td><td>صافي الربح</td></tr><tr><td>المعدل</td><td>2.5%</td><td>20%</td></tr><tr><td>تُفرض على</td><td>سعوديين وخليجيين</td><td>أجانب</td></tr><tr><td>مع الخسارة</td><td>قد تُستحق</td><td>لا تُستحق</td></tr></table></div></div></details>
<p class="ex">ملاحظة: القواعد ملخّصة للتعلم، وللتطبيق الفعلي يُرجع لأنظمة ولوائح زاتكا المحدثة.</p>
<div class="card"><h3>📊 الأنظمة الضريبية في السعودية (ملخص)</h3><div class="wrap"><table><tr><th>الضريبة</th><th>المعدل</th><th>على من / الأساس</th></tr>
<tr><td>ضريبة القيمة المضافة</td><td>15%</td><td>التوريدات الخاضعة؛ التسجيل إلزامي فوق 375,000 ريال</td></tr>
<tr><td>الزكاة</td><td>2.5%</td><td>الوعاء الزكوي لحصة السعوديين والخليجيين</td></tr>
<tr><td>ضريبة الدخل</td><td>20%</td><td>صافي الربح المعدل لحصة الأجانب</td></tr>
<tr><td>الاستقطاع (خدمات فنية)</td><td>5%</td><td>الدفعات للمقيمين خارج المملكة</td></tr>
<tr><td>الاستقطاع (إتاوات)</td><td>15%</td><td>الدفعات للأجانب</td></tr>
<tr><td>الاستقطاع (إدارة)</td><td>20%</td><td>رسوم الإدارة للأجانب</td></tr>
<tr><td>ضريبة التصرفات العقارية</td><td>5%</td><td>قيمة بيع العقار</td></tr></table></div>
<p class="ex">المواعيد: الإقرار الزكوي/الضريبي خلال 120 يوماً من نهاية السنة المالية. الاستقطاع يُسدَّد خلال أول 10 أيام من الشهر التالي. إقرار القيمة المضافة شهري للمنشآت فوق 40 مليون ريال، وغير ذلك ربع سنوي. الجهة: زاتكا.</p></div>
<div class="card"><h3>🧾 حاسبة ضريبة القيمة المضافة 15%</h3><div class="grid"><div><label>المبلغ</label><input type="number" id="v1"></div><div><label>طبيعة المبلغ</label><select id="v2"><option value="a">قبل الضريبة</option><option value="i">شامل الضريبة</option></select></div></div><div class="res" id="rv">—</div>
<div class="grid"><div><label>ضريبة المخرجات (المبيعات)</label><input type="number" id="v3"></div><div><label>ضريبة المدخلات (المشتريات)</label><input type="number" id="v4"></div></div><div class="res" id="rv2">—</div></div>
<div class="card"><h3>🕌 حاسبة الزكاة وضريبة الدخل</h3><button class="p" id="zl" style="margin-top:0">📥 سحب الأرقام من تبويب المحاسب</button>
<div class="grid"><div><label>حقوق الملكية</label><input type="number" id="z1"></div><div><label>قروض طويلة الأجل</label><input type="number" id="z2"></div><div><label>صافي الربح المعدل</label><input type="number" id="z3"></div><div><label>صافي الأصول الثابتة</label><input type="number" id="z4"></div><div><label>حسومات أخرى (استثمارات…)</label><input type="number" id="z5"></div><div><label>حصة السعوديين/الخليجيين %</label><input type="number" id="z6" value="100"></div></div><div class="res" id="rz">—</div>
<p class="ex">الوعاء = حقوق الملكية + القروض طويلة الأجل + الربح المعدل − (الأصول الثابتة + الحسومات)، ويُعتمد الأعلى بينه وبين صافي الربح المعدل. الحساب مبسّط للتعلم؛ الرجوع للائحة زاتكا للحالات الفعلية.</p></div>
<div class="card"><h3>✂️ ضريبة الاستقطاع</h3><div class="grid"><div><label>مبلغ الدفعة لغير المقيم</label><input type="number" id="w1"></div><div><label>نوع الدفعة</label><select id="w2"><option value=".05">خدمات فنية/فوائد/أرباح (5%)</option><option value=".15">إتاوات (15%)</option><option value=".2">رسوم إدارة (20%)</option></select></div></div><div class="res" id="rw">—</div></div>
</section>
<section class="tab" id="t4"><div class="card"><h3>🏛️ المحاسب الآلي: سجّل قيودك وشاهد القوائم المالية تُبنى تلقائياً</h3><div class="grid"><div><label>من ح/ (مدين)</label><select id="ed"></select></div><div><label>إلى ح/ (دائن)</label><select id="ec"></select></div><div><label>المبلغ</label><input type="number" id="ev"></div><div><label>البيان</label><input type="text" id="et"></div></div><button class="p" id="ea">➕ إضافة القيد</button> <button class="p" id="ex">📥 تحميل مثال كامل</button> <button class="p" id="er">🗑️ مسح</button></div><div id="out"></div></section>
</main>
<footer id="ft"><span class="ln2"></span><p class="cr">© 2026 جميع الحقوق محفوظة لـ <b>بلال</b></p></footer>
<nav>
<button class="on" data-t="0"><span>📚</span>الملخص</button><button data-t="1"><span>⚖️</span>القيود</button>
<button data-t="2"><span>🧮</span>المحاسبة</button><button data-t="3"><span>📝</span>اختبار</button><button data-t="4"><span>🏛️</span>المحاسب</button><button data-t="5"><span>🕌</span>زكاة وضريبة</button><button data-t="6"><span>🏭</span>تكاليف ومنشآت</button>
</nav>
<script>
const S=[
["١. ما هي المحاسبة؟",["تسجيل وتصنيف وتلخيص العمليات المالية ثم تحليلها وإيصال نتائجها لمتخذي القرار.","<b>الفروع:</b> مالية، تكاليف، إدارية، مراجعة، ضريبية، حكومية وغير ربحية."]],
["٢. المبادئ والفروض",["الكيان المستقل، الاستمرارية، الوحدة النقدية، الفترة المحاسبية.","التكلفة التاريخية، الاستحقاق، المقابلة، الحيطة والحذر، الثبات.","الأهمية النسبية والإفصاح الكامل.","<b>المعايير:</b> IFRS في السعودية (SOCPA)، وGAAP في أمريكا."]],
["٣. الدورة المحاسبية",["تحليل العملية والمستند ← قيد اليومية ← الترحيل لدفتر الأستاذ.","ميزان المراجعة ← قيود التسوية ← الميزان المعدل.","القوائم المالية ← قيود الإقفال ← ميزان ما بعد الإقفال."]],
["٤. القوائم المالية",["<b>الدخل:</b> الإيرادات − المصروفات = صافي الربح.","<b>المركز المالي:</b> الأصول والالتزامات وحقوق الملكية.","<b>التدفقات النقدية:</b> تشغيلية، استثمارية، تمويلية.","التغيرات في حقوق الملكية، والإيضاحات المتممة."]],
["٥. موضوعات رئيسية",["النقدية والبنوك: مذكرة التسوية البنكية.","العملاء: مخصص الديون المشكوك فيها.","المخزون: FIFO والمتوسط المرجح، بالتكلفة أو صافي القيمة البيعية أيهما أقل.","الأصول الثابتة: إهلاك (قسط ثابت، متناقص، وحدات إنتاج). غير الملموسة: تُطفأ.","الشركات: أشخاص (تضامن، توصية) وأموال (مساهمة، محدودة). القوائم المجمعة."]],
["٦. محاسبة التكاليف والإدارية",["مواد مباشرة، أجور مباشرة، تكاليف صناعية غير مباشرة.","نقطة التعادل = الثابتة ÷ (السعر − المتغيرة للوحدة).","أنظمة: أوامر الإنتاج، المراحل، المعيارية. الموازنات وتحليل الانحرافات."]],
["٧. التحليل المالي",["<b>السيولة:</b> نسبة التداول = أصول متداولة ÷ خصوم متداولة.","<b>الربحية:</b> هامش الربح، ROA، ROE.","<b>النشاط:</b> دوران المخزون والعملاء. <b>المديونية:</b> الديون ÷ الأصول."]],
["٨. المراجعة والرقابة",["خارجية وداخلية. الرأي: نظيف، متحفظ، سلبي، الامتناع.","الرقابة الداخلية: فصل المهام، التفويض، التوثيق، حماية الأصول."]],
["٩. الضرائب والزكاة (السعودية)",["القيمة المضافة 15%. الزكاة 2.5% من الوعاء الزكوي. ضريبة الدخل على الشريك الأجنبي 20%.","الجهة: هيئة الزكاة والضريبة والجمارك، والفوترة الإلكترونية إلزامية."]],
["١٠. الأدوات والمهارات",["Excel، قيود، دفترة، Odoo، QuickBooks، SAP.","الشهادات: SOCPA، CPA، CMA، CIA، ACCA.","الوظائف: محاسب، مراجع، محلل مالي، محاسب تكاليف، مستشار ضريبي، مدير مالي."]],
["١١. المراجعة: المفهوم والأهداف والأنواع",["<b>التعريف:</b> فحص وتقييم السجلات والبيانات والقوائم المالية للتأكد من صحتها وعدالتها، وإبداء رأي مهني مستقل بشأنها.","<b>الأهداف:</b> التأكد من صحة البيانات المالية، اكتشاف الأخطاء الجوهرية، الحد من الغش والاختلاس، التأكد من الالتزام بالأنظمة، وإبداء رأي فني مستقل.","<b>الأنواع:</b><div class=\"wrap\"><table><tr><th>النوع</th><th>التعريف</th></tr><tr><td>داخلية</td><td>تقوم بها إدارة المنشأة أو موظفوها</td></tr><tr><td>خارجية</td><td>يقوم بها مراجع مستقل</td></tr><tr><td>مالية</td><td>فحص القوائم المالية</td></tr><tr><td>تشغيلية</td><td>تقييم كفاءة العمليات</td></tr><tr><td>حكومية</td><td>فحص الجهات الحكومية</td></tr></table></div>"]],
["١٢. المراجع القانوني",["شخص مهني مستقل ومؤهل يفحص القوائم المالية ويبدي رأيه فيها.","<b>صفاته:</b> الاستقلال، الأمانة، النزاهة، الكفاءة المهنية، السرية، الموضوعية.","<b>مسؤولياته:</b> فحص المستندات والسجلات، جمع أدلة المراجعة، تقييم المخاطر، فحص الرقابة الداخلية، وإعداد تقرير المراجعة."]],
["١٣. معايير المراجعة والتخطيط",["<b>معايير عامة:</b> تأهيل المراجع واستقلاله وعنايته المهنية.","<b>معايير العمل الميداني:</b> التخطيط والإشراف وفحص الأدلة.","<b>معايير التقرير:</b> إبداء الرأي وإعداد التقرير.","<b>التخطيط:</b> وضع خطة منظمة لتنفيذ المراجعة بكفاءة وفاعلية، وأهميته: تحديد النطاق والوقت وتوزيع المهام والمخاطر وإجراءات الفحص.","<b>برنامج المراجعة:</b> مستند مكتوب بإجراءات المراجعة الواجب تنفيذها."]],
["١٤. أدلة المراجعة والرقابة الداخلية",["<b>الأدلة:</b> المعلومات التي يعتمد عليها المراجع في استنتاجاته، مثل الفواتير وكشوف البنوك والعقود والمصادقات الخارجية ومحاضر الجرد والمستندات المحاسبية.","<b>صفات الدليل الجيد:</b> الكفاية، الملاءمة، الموثوقية.","<b>الرقابة الداخلية:</b> سياسات وإجراءات تضعها المنشأة لحماية أصولها وضمان دقة المعلومات المالية وتحقيق أهدافها.","<b>أهدافها:</b> حماية الأصول، منع الغش والاختلاس، ضمان صحة البيانات، تحسين كفاءة العمل، الالتزام بالأنظمة."]],
["١٥. الغش والأخطاء وملفات المراجعة",["<div class=\"wrap\"><table><tr><th>الغش</th><th>الخطأ</th></tr><tr><td>تصرف متعمد</td><td>تصرف غير متعمد</td></tr><tr><td>تزوير مستند</td><td>خطأ حسابي</td></tr><tr><td>إخفاء الإيرادات عمداً</td><td>تسجيل مبلغ بصورة خاطئة</td></tr><tr><td>اختلاس الأموال</td><td>نسيان تسجيل عملية</td></tr></table></div>","<b>الملف الدائم:</b> معلومات تفيد عدة سنوات: عقد التأسيس، النظام الأساسي، الهيكل التنظيمي، العقود طويلة الأجل.","<b>الملف الجاري:</b> خاص بسنة المراجعة الحالية: ميزان المراجعة، القوائم المالية، أوراق العمل، نتائج الفحص، تقرير المراجعة."]],
["١٦. تقرير المراجع واستقلاله وسريته",["<div class=\"wrap\"><table><tr><th>نوع الرأي</th><th>المعنى</th></tr><tr><td>غير معدل</td><td>القوائم معروضة بعدالة من جميع النواحي الجوهرية</td></tr><tr><td>متحفظ</td><td>توجد مشكلة جوهرية لكنها غير منتشرة</td></tr><tr><td>معاكس</td><td>القوائم تتضمن تحريفات جوهرية ومنتشرة</td></tr><tr><td>الامتناع عن إبداء الرأي</td><td>تعذر الحصول على أدلة كافية ومناسبة، وأثره جوهري ومنتشر</td></tr></table></div>","<b>الاستقلال والسرية:</b> ألا تكون للمراجع مصلحة شخصية تؤثر على رأيه، والمحافظة على أسرار العميل، وتجنب تضارب المصالح، والالتزام بالعناية المهنية، وأن يكون الرأي مستقلاً وموضوعياً."]],
["الفصل الأول: مفهوم المحاسبة",["علم تسجيل وتبويب وتلخيص العمليات المالية للمنشأة، لتوفير معلومات تساعد في اتخاذ القرارات.","<b>الأهداف:</b> تسجيل العمليات، معرفة الأرباح والخسائر، تحديد المركز المالي، معرفة حقوق المنشأة والتزاماتها، مساعدة الإدارة، وتوفير معلومات للمستثمرين والدائنين.","<div class='wrap'><table><tr><th>النوع</th><th>وظيفته</th></tr><tr><td>المالية</td><td>إعداد القوائم المالية</td></tr><tr><td>الإدارية</td><td>مساعدة الإدارة</td></tr><tr><td>التكاليف</td><td>تحديد تكلفة الإنتاج</td></tr><tr><td>الحكومية</td><td>تسجيل العمليات الحكومية</td></tr><tr><td>الضريبية</td><td>حساب الضرائب</td></tr><tr><td>المراجعة</td><td>فحص السجلات والقوائم</td></tr></table></div>"]],
["الفصل الثاني: المبادئ والفروض",["<b>المبادئ:</b> الاستمرارية (المنشأة مستمرة)، الاستحقاق (تسجيل الإيرادات والمصروفات عند تحققها لا عند القبض أو الدفع فقط)، المقابلة (مصروفات الفترة مقابل إيراداتها)، التكلفة التاريخية، الإفصاح الكامل، الثبات، وتحقق الإيراد.","<b>الفروض:</b> الوحدة المحاسبية، الاستمرارية، الفترة المحاسبية، وحدة القياس النقدي."]],
["الفصل الثالث: المعادلة المحاسبية",["<b>الأصول = الخصوم + حقوق الملكية</b>","<b>مثال:</b> أصول 100,000 وخصوم 30,000 ← حقوق الملكية = 70,000 ريال.","<b>الأصول:</b> ما تملكه المنشأة وله منفعة اقتصادية: نقدية، بنك، أراضي، مباني، سيارات، أثاث، مخزون، عملاء.","<b>الخصوم:</b> التزامات للغير: دائنون، قروض، أوراق دفع، رواتب وإيجار مستحق.","<b>حقوق الملكية:</b> حق المالك في صافي الأصول: رأس المال، الأرباح المحتجزة، صافي الربح."]],
["الفصل الرابع: الحسابات المدينة والدائنة",["<div class='wrap'><table><tr><th>الحساب</th><th>الزيادة</th><th>النقص</th></tr><tr><td>الأصول</td><td>مدين</td><td>دائن</td></tr><tr><td>المصروفات</td><td>مدين</td><td>دائن</td></tr><tr><td>المسحوبات</td><td>مدين</td><td>دائن</td></tr><tr><td>الخصوم</td><td>دائن</td><td>مدين</td></tr><tr><td>رأس المال</td><td>دائن</td><td>مدين</td></tr><tr><td>الإيرادات</td><td>دائن</td><td>مدين</td></tr></table></div>","<b>قاعدة الحفظ:</b> الأصول والمصروفات والمسحوبات طبيعتها مدينة، والخصوم وحقوق الملكية والإيرادات دائنة.","<b>مثال:</b> شراء أثاث نقداً بـ 5,000 ← الأثاث زاد (مدين)، الصندوق نقص (دائن)."]],
["الفصل الخامس: القيد المزدوج",["كل عملية مالية تؤثر في حسابين على الأقل، و<b>مجموع المدين = مجموع الدائن</b>.","<b>رأس مال نقدي 50,000:</b> من ح/ الصندوق (مدين) إلى ح/ رأس المال (دائن).","<b>شراء أجهزة نقداً 10,000:</b> من ح/ الأجهزة (مدين) إلى ح/ الصندوق (دائن).","<b>شراء بضاعة على الحساب 8,000:</b> من ح/ المشتريات (مدين) إلى ح/ الدائنون (دائن)."]],
["الفصل السادس والسابع: دفتر اليومية ودفتر الأستاذ",["<b>اليومية:</b> تُسجَّل فيها العمليات حسب تاريخ حدوثها. القيد البسيط: حساب مدين وحساب دائن، والمركب: أكثر من حساب في أحد الطرفين.","<b>مثال مركب:</b> إيجار 3,000 ورواتب 2,000 نقداً ← من مذكورين: مصروف الإيجار 3,000 + مصروف الرواتب 2,000 إلى الصندوق 5,000.","<b>الأستاذ:</b> تُرحَّل إليه العمليات من اليومية إلى حساباتها.","<b>مثال ح/ الصندوق:</b> مدين 50,000 + 5,000 = 55,000، دائن 10,000 + 3,000 = 13,000 ← <b>الرصيد المدين 42,000</b>."]],
["الفصل الثامن: ميزان المراجعة",["كشف بأرصدة الحسابات المدينة والدائنة للتأكد من تساوي الطرفين.","<div class='wrap'><table><tr><th>الحساب</th><th>مدين</th><th>دائن</th></tr><tr><td>الصندوق</td><td>20,000</td><td>—</td></tr><tr><td>الأثاث</td><td>10,000</td><td>—</td></tr><tr><td>المصروفات</td><td>5,000</td><td>—</td></tr><tr><td>رأس المال</td><td>—</td><td>30,000</td></tr><tr><td>الإيرادات</td><td>—</td><td>5,000</td></tr><tr><td><b>المجموع</b></td><td><b>35,000</b></td><td><b>35,000</b></td></tr></table></div>","<b>ملاحظة:</b> تساوي الميزان لا يعني بالضرورة خلو الدفاتر من الأخطاء."]],
["الفصل التاسع: التسويات الجردية",["تعديلات في نهاية الفترة لإظهار الإيرادات والمصروفات في الفترة الصحيحة.","<b>أنواعها:</b> مصروفات مستحقة، مصروفات مقدمة، إيرادات مستحقة، إيرادات مقدمة، الإهلاك، والديون المشكوك في تحصيلها.","<b>مثال:</b> إيجار مدفوع مقدماً 12,000 لسنة ← 12,000 ÷ 12 = 1,000 شهرياً. بعد شهر: من ح/ مصروف الإيجار 1,000 إلى ح/ الإيجار المدفوع مقدماً 1,000."]],
["الفصل العاشر: القوائم المالية",["<b>قائمة الدخل:</b> صافي الربح = الإيرادات − المصروفات. مثال: 80,000 − 50,000 = 30,000 ريال.","<b>المركز المالي:</b> الأصول والخصوم وحقوق الملكية في تاريخ معين.","<b>التدفقات النقدية:</b> أنشطة تشغيلية واستثمارية وتمويلية.","<b>التغيرات في حقوق الملكية:</b> ما طرأ على حقوق الملكية خلال الفترة."]],
["الفصل الحادي عشر: الإهلاك",["توزيع تكلفة الأصل الثابت القابل للإهلاك على عمره الإنتاجي.","<b>القسط الثابت:</b> (التكلفة − القيمة التخريدية) ÷ العمر الإنتاجي.","<b>مثال:</b> سيارة تكلفتها 100,000 وتخريدية 10,000 وعمرها 5 سنوات ← (100,000 − 10,000) ÷ 5 = <b>18,000 سنوياً</b>."]],
["الفصل الثاني عشر: المخزون والمشتريات والمبيعات",["<b>الجرد الدوري:</b> يُحدد المخزون وتكلفة المباع بالجرد في نهاية الفترة. <b>الجرد المستمر:</b> يُحدث حساب المخزون مع كل عملية.","<b>تكلفة البضاعة المباعة</b> = مخزون أول المدة + صافي المشتريات − مخزون آخر المدة.","<b>مثال:</b> 10,000 + 40,000 − 15,000 = <b>35,000 ريال</b>."]],
["الفصلان الثالث والرابع عشر: المردودات والخصومات والأوراق التجارية",["<b>مردودات المشتريات:</b> بضاعة أعادتها المنشأة للمورد. <b>مردودات المبيعات:</b> بضاعة أعادها العميل.","<b>الخصم التجاري:</b> تخفيض في سعر البيع أو الشراء. <b>الخصم النقدي:</b> مقابل السداد خلال مدة محددة.","<b>أوراق القبض:</b> حقوق للمنشأة، <b>أوراق الدفع:</b> التزامات عليها. مثال: استلام ورقة قبض 5,000 ← من ح/ أوراق القبض (مدين) إلى ح/ العملاء (دائن)."]],
["الفصل الخامس عشر: إقفال الحسابات",["يُقفَل في نهاية الفترة المالية الحسابات المؤقتة: الإيرادات والمصروفات والمسحوبات.","ثم يُحدد صافي الربح أو الخسارة ويُرحَّل إلى حقوق الملكية."]],
["أهم القوانين للحفظ",["<div class='wrap'><table><tr><th>القانون</th><th>المعادلة</th></tr><tr><td>المعادلة المحاسبية</td><td>الأصول = الخصوم + حقوق الملكية</td></tr><tr><td>حقوق الملكية</td><td>الأصول − الخصوم</td></tr><tr><td>صافي الربح</td><td>الإيرادات − المصروفات</td></tr><tr><td>صافي المشتريات</td><td>المشتريات − مردوداتها − خصوماتها + مصاريف نقل المشتريات</td></tr><tr><td>تكلفة البضاعة المباعة</td><td>مخزون أول المدة + صافي المشتريات − مخزون آخر المدة</td></tr><tr><td>مجمل الربح</td><td>صافي المبيعات − تكلفة البضاعة المباعة</td></tr><tr><td>الإهلاك السنوي</td><td>(التكلفة − التخريدية) ÷ العمر الإنتاجي</td></tr></table></div>"]],
["١. تعريف المحاسبة (Accounting)",["<div dir='ltr' style='text-align:left'><b>Accounting:</b> The process of recording, classifying, summarizing and interpreting financial transactions.</div>","<b>الترجمة:</b> المحاسبة هي عملية تسجيل وتصنيف وتلخيص وتفسير العمليات المالية."]],
["٢. أنواع المحاسبة (Types of Accounting)",["<div class='wrap'><table><tr><th>English</th><th>العربية</th></tr><tr><td dir='ltr'>Financial Accounting</td><td>المحاسبة المالية</td></tr><tr><td dir='ltr'>Managerial Accounting</td><td>المحاسبة الإدارية</td></tr><tr><td dir='ltr'>Cost Accounting</td><td>محاسبة التكاليف</td></tr><tr><td dir='ltr'>Tax Accounting</td><td>المحاسبة الضريبية</td></tr><tr><td dir='ltr'>Auditing</td><td>المراجعة والتدقيق</td></tr></table></div>"]],
["٣. المعادلة المحاسبية (Accounting Equation)",["<div dir='ltr' style='text-align:center'><b>Assets = Liabilities + Owner's Equity</b></div>","<b>Assets:</b> الأصول. <b>Liabilities:</b> الالتزامات. <b>Owner's Equity:</b> حقوق الملكية.","<b>مثال:</b> أصول 100,000 ريال والتزامات 40,000 ريال ← حقوق الملكية = 60,000 ريال."]],
["٤. عناصر المحاسبة الأساسية",["<div class='wrap'><table><tr><th>English</th><th>العربية</th><th>طبيعتها</th></tr><tr><td dir='ltr'>Assets</td><td>الأصول</td><td>مدينة</td></tr><tr><td dir='ltr'>Liabilities</td><td>الالتزامات</td><td>دائنة</td></tr><tr><td dir='ltr'>Capital</td><td>رأس المال</td><td>دائن</td></tr><tr><td dir='ltr'>Revenue</td><td>الإيرادات</td><td>دائنة</td></tr><tr><td dir='ltr'>Expenses</td><td>المصروفات</td><td>مدينة</td></tr><tr><td dir='ltr'>Drawings</td><td>المسحوبات</td><td>مدينة</td></tr></table></div>"]],
["٥. المدين والدائن (Debit and Credit)",["<b>Debit (Dr):</b> مدين. <b>Credit (Cr):</b> دائن.","<div class='wrap'><table><tr><th>الحساب</th><th>الزيادة</th></tr><tr><td dir='ltr'>Assets</td><td dir='ltr'>Debit</td></tr><tr><td dir='ltr'>Expenses</td><td dir='ltr'>Debit</td></tr><tr><td dir='ltr'>Drawings</td><td dir='ltr'>Debit</td></tr><tr><td dir='ltr'>Liabilities</td><td dir='ltr'>Credit</td></tr><tr><td dir='ltr'>Capital</td><td dir='ltr'>Credit</td></tr><tr><td dir='ltr'>Revenue</td><td dir='ltr'>Credit</td></tr></table></div>"]],
["٦. القوائم المالية (Financial Statements)",["<b>Income Statement:</b> قائمة الدخل.","<b>Balance Sheet:</b> قائمة المركز المالي.","<b>Cash Flow Statement:</b> قائمة التدفقات النقدية.","<b>Statement of Owner's Equity:</b> قائمة حقوق الملكية."]],
["٧. أهم المصطلحات المحاسبية",["<div class='wrap'><table><tr><th>English</th><th>العربية</th></tr><tr><td dir='ltr'>Account</td><td>حساب</td></tr><tr><td dir='ltr'>Transaction</td><td>عملية مالية</td></tr><tr><td dir='ltr'>Journal</td><td>دفتر اليومية</td></tr><tr><td dir='ltr'>Ledger</td><td>دفتر الأستاذ</td></tr><tr><td dir='ltr'>Trial Balance</td><td>ميزان المراجعة</td></tr><tr><td dir='ltr'>Invoice</td><td>فاتورة</td></tr><tr><td dir='ltr'>Cash</td><td>النقدية</td></tr><tr><td dir='ltr'>Bank</td><td>البنك</td></tr><tr><td dir='ltr'>Inventory</td><td>المخزون</td></tr><tr><td dir='ltr'>Accounts Receivable</td><td>حسابات المدينين</td></tr><tr><td dir='ltr'>Accounts Payable</td><td>حسابات الدائنين</td></tr><tr><td dir='ltr'>Net Income</td><td>صافي الدخل</td></tr><tr><td dir='ltr'>Net Loss</td><td>صافي الخسارة</td></tr><tr><td dir='ltr'>Profit</td><td>الربح</td></tr><tr><td dir='ltr'>Loss</td><td>الخسارة</td></tr></table></div>"]],
["٨. القيود المحاسبية (Journal Entries)",["<b>مثال 1:</b> بدأ صاحب المشروع برأس مال نقدي 10,000 ريال.<div class='wrap'><table dir='ltr'><tr><th>Account</th><th>Debit</th><th>Credit</th></tr><tr><td>Cash</td><td>10,000</td><td></td></tr><tr><td>Capital</td><td></td><td>10,000</td></tr></table></div>","<b>مثال 2:</b> دفع المشروع إيجار 2,000 ريال نقداً.<div class='wrap'><table dir='ltr'><tr><th>Account</th><th>Debit</th><th>Credit</th></tr><tr><td>Rent Expense</td><td>2,000</td><td></td></tr><tr><td>Cash</td><td></td><td>2,000</td></tr></table></div>"]],
["٩. أهم المعادلات (Accounting Formulas)",["<b>صافي الربح:</b><div dir='ltr' style='text-align:center'>Net Income = Revenue − Expenses</div>","<b>حقوق الملكية:</b><div dir='ltr' style='text-align:center'>Owner's Equity = Assets − Liabilities</div>","<b>صافي المبيعات:</b><div dir='ltr' style='text-align:center'>Net Sales = Sales − Sales Returns</div>"]],
["١٠. اختصارات مهمة للاختبار",["<div class='wrap'><table><tr><th>الاختصار</th><th>المعنى</th></tr><tr><td dir='ltr'>A</td><td dir='ltr'>Assets</td></tr><tr><td dir='ltr'>L</td><td dir='ltr'>Liabilities</td></tr><tr><td dir='ltr'>E</td><td dir='ltr'>Equity</td></tr><tr><td dir='ltr'>R</td><td dir='ltr'>Revenue</td></tr><tr><td dir='ltr'>EX</td><td dir='ltr'>Expenses</td></tr><tr><td dir='ltr'>Dr</td><td dir='ltr'>Debit</td></tr><tr><td dir='ltr'>Cr</td><td dir='ltr'>Credit</td></tr><tr><td dir='ltr'>BS</td><td dir='ltr'>Balance Sheet</td></tr><tr><td dir='ltr'>IS</td><td dir='ltr'>Income Statement</td></tr></table></div>"]],
["١. المخزون (Inventory)",["<div dir='ltr' style='text-align:left'><b>Inventory:</b> Goods held for sale in the ordinary course of business.</div>","<b>الترجمة:</b> البضاعة التي تحتفظ بها المنشأة بغرض البيع.","<b>أنواع المخزون:</b> <b>Raw Materials</b> المواد الخام، <b>Work in Process</b> إنتاج تحت التشغيل، <b>Finished Goods</b> البضاعة تامة الصنع.","<div class='wrap'><table><tr><th>English</th><th>العربية</th></tr><tr><td dir='ltr'>FIFO</td><td>الوارد أولاً صادر أولاً</td></tr><tr><td dir='ltr'>LIFO</td><td>الوارد أخيراً صادر أولاً</td></tr><tr><td dir='ltr'>Weighted Average</td><td>المتوسط المرجح</td></tr></table></div>"]],
["٢. الأصول الثابتة (Property, Plant and Equipment)",["الأصول التي تستخدمها المنشأة لفترة طويلة.","<b>أمثلة:</b> <b>Land</b> الأراضي، <b>Buildings</b> المباني، <b>Machinery</b> الآلات، <b>Equipment</b> المعدات، <b>Vehicles</b> السيارات.","<b>Depreciation – الإهلاك:</b> توزيع تكلفة الأصل على عمره الإنتاجي.","<div dir='ltr' style='text-align:center'><b>Depreciation = (Cost − Residual Value) ÷ Useful Life</b></div>","<b>مثال:</b> تكلفة آلة 50,000 وقيمة متبقية 5,000 وعمر 5 سنوات ← (50,000 − 5,000) ÷ 5 = <b>9,000 ريال سنوياً</b>."]],
["٣. الأصول غير الملموسة (Intangible Assets)",["أصول ليس لها وجود مادي.","<b>Goodwill:</b> الشهرة. <b>Patent:</b> براءة الاختراع. <b>Copyright:</b> حقوق النشر. <b>Trademark:</b> العلامة التجارية."]],
["٤. الالتزامات المتداولة (Current Liabilities)",["الالتزامات التي تستحق خلال سنة أو دورة التشغيل، أيهما أطول.","<div class='wrap'><table><tr><th>English</th><th>العربية</th></tr><tr><td dir='ltr'>Accounts Payable</td><td>الحسابات الدائنة</td></tr><tr><td dir='ltr'>Notes Payable</td><td>أوراق الدفع</td></tr><tr><td dir='ltr'>Salaries Payable</td><td>الرواتب المستحقة</td></tr><tr><td dir='ltr'>Interest Payable</td><td>الفوائد المستحقة</td></tr><tr><td dir='ltr'>Unearned Revenue</td><td>الإيرادات غير المكتسبة</td></tr></table></div>"]],
["٥. الالتزامات طويلة الأجل (Long-term Liabilities)",["التزامات تستحق بعد أكثر من سنة أو دورة التشغيل.","<b>Bonds Payable:</b> السندات المستحقة. <b>Long-term Loans:</b> القروض طويلة الأجل. <b>Mortgage Payable:</b> الرهون العقارية المستحقة."]],
["٦. حقوق الملكية (Stockholders' Equity)",["تمثل حقوق أصحاب الأسهم في الشركة.","<div class='wrap'><table><tr><th>English</th><th>العربية</th></tr><tr><td dir='ltr'>Common Stock</td><td>الأسهم العادية</td></tr><tr><td dir='ltr'>Preferred Stock</td><td>الأسهم الممتازة</td></tr><tr><td dir='ltr'>Retained Earnings</td><td>الأرباح المحتجزة</td></tr><tr><td dir='ltr'>Dividends</td><td>توزيعات الأرباح</td></tr><tr><td dir='ltr'>Treasury Stock</td><td>أسهم الخزينة</td></tr></table></div>"]],
["٧. الاستثمارات (Investments)",["استثمار الأموال في أصول مالية لتحقيق عائد.","<b>Bonds:</b> السندات. <b>Stocks:</b> الأسهم. <b>Securities:</b> الأوراق المالية."]],
["٨. قائمة التدفقات النقدية (Cash Flow Statement)",["تنقسم إلى ثلاثة أقسام:","<b>Operating Activities:</b> الأنشطة التشغيلية.","<b>Investing Activities:</b> الأنشطة الاستثمارية.","<b>Financing Activities:</b> الأنشطة التمويلية."]],
["٩. أهم المصطلحات للحفظ",["<div class='wrap'><table><tr><th>المصطلح</th><th>الترجمة</th></tr><tr><td dir='ltr'>Cost</td><td>التكلفة</td></tr><tr><td dir='ltr'>Depreciation</td><td>الإهلاك</td></tr><tr><td dir='ltr'>Accumulated Depreciation</td><td>مجمع الإهلاك</td></tr><tr><td dir='ltr'>Carrying Amount</td><td>القيمة الدفترية</td></tr><tr><td dir='ltr'>Residual Value</td><td>القيمة المتبقية</td></tr><tr><td dir='ltr'>Useful Life</td><td>العمر الإنتاجي</td></tr><tr><td dir='ltr'>Impairment</td><td>انخفاض القيمة</td></tr><tr><td dir='ltr'>Amortization</td><td>الإطفاء</td></tr><tr><td dir='ltr'>Liability</td><td>الالتزام</td></tr><tr><td dir='ltr'>Equity</td><td>حقوق الملكية</td></tr><tr><td dir='ltr'>Revenue</td><td>الإيراد</td></tr><tr><td dir='ltr'>Expense</td><td>المصروف</td></tr></table></div>"]]];
const $=id=>document.getElementById(id);
function render(f=""){const m=S.map((s,i)=>({s,i})).filter(o=>(o.s[0]+o.s[1].join(" ")).includes(f)),g=o=>o.i==7||(o.i>=10&&o.i<16);
const one=(o,st)=>`<details${f?" open":""}><summary>${st?o.s[0].replace(/^[\u0660-\u0669]+\.\s*/,""):o.s[0]}</summary><div class="b"><ul>${o.s[1].map(x=>`<li>${x}</li>`).join("")}</ul></div></details>`;
let h="",d=0;const pg=m.filter(o=>o.i>=16&&o.i<30),eg=m.filter(o=>o.i>=30&&o.i<40),mg=m.filter(o=>o.i>=40);if(pg.length)h+=`<details${f?" open":""}><summary>📘 مبادئ المحاسبة المالية</summary><div class="b">${pg.map(x=>one(x,1)).join("")}</div></details>`;if(eg.length)h+=`<details${f?" open":""}><summary>🌐 المحاسبة بالإنجليزية (Accounting in English)</summary><div class="b">${eg.map(x=>one(x,1)).join("")}</div></details>`;if(mg.length)h+=`<details${f?" open":""}><summary>📗 محاسبة متوسطة 2 (Intermediate Accounting 2)</summary><div class="b">${mg.map(x=>one(x,1)).join("")}</div></details>`;m.forEach(o=>{if(o.i>=16)return;if(!g(o))h+=one(o);else if(!d){d=1;h+=`<details${f?" open":""}><summary>٨. موضوعات مختارة: المراجعة والرقابة</summary><div class="b">${m.filter(g).map(x=>one(x,1)).join("")}</div></details>`}});
$("sum").innerHTML=h||'<p class="ex">لا توجد نتائج</p>'}
render();$("q").oninput=e=>render(e.target.value.trim());
document.querySelectorAll("nav button").forEach(b=>b.onclick=()=>{document.querySelectorAll("nav button,.tab").forEach(x=>x.classList.remove("on"));b.classList.add("on");$("t"+b.dataset.t).classList.add("on");$("app").scrollIntoView()});
$("th").onclick=()=>{const r=document.documentElement,d=matchMedia("(prefers-color-scheme:dark)").matches,cur=r.dataset.theme||(d?"dark":"light");r.dataset.theme=cur==="dark"?"light":"dark"};
const n=id=>parseFloat($(id).value),f=x=>isFinite(x)?x.toLocaleString("en",{maximumFractionDigits:2}):"—";
function calc(){
const a=n("a1"),l=n("a2");$("r1").textContent="حقوق الملكية = "+f(a-l);
const c=n("f1")/n("f2"),m=n("f3")/n("f4")*100,d=n("f5")/n("f6")*100;
$("r2").innerHTML=`نسبة التداول: ${f(c)}<br>هامش صافي الربح: ${f(m)}%<br>المديونية: ${f(d)}%`;
const u=n("b1")/(n("b2")-n("b3"));$("r3").innerHTML=isFinite(u)&&u>0?`الوحدات: ${f(Math.ceil(u))}<br>المبيعات: ${f(u*n("b2"))} ريال`:"—";
const k=n("d1"),s=n("d2")||0,y=n("d3"),sl=(k-s)/y;$("r4").innerHTML=y>0?`القسط الثابت السنوي: ${f(sl)}<br>المتناقص (السنة 1): ${f(k*2/y)}`:"—"}
document.querySelectorAll("input[type=number]").forEach(i=>i.oninput=calc);
const T=[["النقدية","أصل","مدين"],["المشتريات","مصروف","مدين"],["الموردون","التزام","دائن"],["رأس المال","حقوق ملكية","دائن"],["المبيعات","إيراد","دائن"],["المعدات","أصل","مدين"],["الرواتب","مصروف","مدين"],["قروض","التزام","دائن"],["العملاء","أصل","مدين"],["الأرباح المحتجزة","حقوق ملكية","دائن"]];
function tr(){const t=T[Math.random()*T.length|0];$("tr").innerHTML=`<p>حساب <b>${t[0]}</b> ← طبيعته (${t[1]}). يزيد بـ:</p><button class="opt" data-v="مدين">مدين</button><button class="opt" data-v="دائن">دائن</button><p class="ex" id="trm"></p>`;
document.querySelectorAll("#tr .opt").forEach(b=>b.onclick=()=>{const ok=b.dataset.v===t[2];b.classList.add(ok?"ok":"no");$("trm").textContent=ok?"✅ صحيح":"❌ الصحيح: "+t[2];setTimeout(tr,1100)})}
tr();
const Q=[["ما معادلة المحاسبة الأساسية؟",["الأصول = الالتزامات + حقوق الملكية","الأصول = الإيرادات − المصروفات","الالتزامات = الأصول + الملكية"],0,"هي الأساس الأول للمحاسبة."],
["أي مبدأ يسجّل الإيراد عند اكتسابه لا عند القبض؟",["التكلفة التاريخية","الاستحقاق","الثبات"],1,"مبدأ الاستحقاق."],
["الإيرادات تزيد بـ:",["مدين","دائن"],1,"الإيرادات والالتزامات والملكية تزيد بالدائن."],
["يُقيَّم المخزون بـ:",["التكلفة أو صافي القيمة البيعية أيهما أقل","القيمة السوقية دائماً","سعر البيع"],0,"تطبيقاً للحيطة والحذر."],
["نسبة ضريبة القيمة المضافة في السعودية:",["5%","10%","15%"],2,"15%."],
["نسبة الزكاة من الوعاء الزكوي:",["2.5%","5%","20%"],0,"2.5%."],
["نقطة التعادل =",["الثابتة ÷ (السعر − المتغيرة للوحدة)","المتغيرة ÷ السعر","الربح ÷ المبيعات"],0,"التكاليف الثابتة مقسومة على هامش المساهمة للوحدة."],
["الرأي الذي يعني القوائم عادلة بلا تحفظات:",["متحفظ","سلبي","نظيف"],2,"الرأي النظيف."],
["ما هي المعادلة المحاسبية الصحيحة؟",["الأصول = الخصوم + حقوق الملكية","الأصول = الإيرادات + المصروفات","الخصوم = الأصول + المصروفات"],0,"الأصول = الخصوم + حقوق الملكية."],
["زيادة الأصول تسجل في أي طرف؟",["الدائن","المدين","لا تسجل"],1,"الأصول تزيد بالمدين وتنقص بالدائن."],
["الإيرادات طبيعتها؟",["مدينة","دائنة","ليس لها طبيعة"],1,"الإيرادات تزيد بالدائن وتنقص بالمدين."],
["شراء معدات نقداً يؤدي إلى؟",["زيادة المعدات ونقص النقدية","نقص المعدات وزيادة النقدية","زيادة الخصوم"],0,"من ح/ المعدات (مدين) إلى ح/ النقدية (دائن)، فتتبدل الأصول فقط."],
["كيف نحسب صافي الربح؟",["المصروفات - الإيرادات","الإيرادات - المصروفات","الأصول - الخصوم"],1,"صافي الربح = الإيرادات − المصروفات."]];
let qi=0,sc=0;
function qs(){const c=$("qz");if(qi>=Q.length){c.innerHTML=`<h3>النتيجة</h3><div class="big">${sc} / ${Q.length}</div><button class="p" id="rs">إعادة الاختبار</button>`;$("rs").onclick=()=>{qi=0;sc=0;qs()};return}
const q=Q[qi];c.innerHTML=`<h3>سؤال ${qi+1} من ${Q.length}</h3><p><b>${q[0]}</b></p>${q[1].map((o,i)=>`<button class="opt" data-i="${i}">${o}</button>`).join("")}<p class="ex" id="qm"></p>`;
c.querySelectorAll(".opt").forEach(b=>b.onclick=()=>{const ok=+b.dataset.i===q[2];if(ok)sc++;c.querySelectorAll(".opt").forEach(x=>{x.disabled=true;if(+x.dataset.i===q[2])x.classList.add("ok")});if(!ok)b.classList.add("no");$("qm").textContent=q[3];const nx=document.createElement("button");nx.className="p";nx.textContent="التالي";nx.onclick=()=>{qi++;qs()};c.appendChild(nx)})}
const A=[["النقدية","a"],["العملاء","a"],["المخزون","a"],["المعدات","a"],["الموردون","l"],["القروض","l"],["رأس المال","e"],["المبيعات","r"],["تكلفة المبيعات","x"],["الرواتب","x"],["الإيجار","x"]];
let E=[];
const ty={a:"أصل",l:"التزام",e:"ملكية",r:"إيراد",x:"مصروف"};
["ed","ec"].forEach(i=>$(i).innerHTML=A.map(a=>`<option>${a[0]}</option>`).join(""));$("ec").selectedIndex=6;
const tb=(h,r)=>`<div class="wrap"><table><tr>${h.map(x=>`<th>${x}</th>`).join("")}</tr>${r}</table></div>`;
function led(){
const b={};A.forEach(a=>b[a[0]]=0);E.forEach(e=>{b[e.d]+=e.v;b[e.c]-=e.v});
const sm=t=>A.filter(a=>a[1]==t).reduce((s,a)=>s+b[a[0]],0);
const as=sm("a"),li=-sm("l"),cap=-sm("e"),rev=-sm("r"),ex=sm("x"),ni=rev-ex,eq=cap+ni,ok=Math.abs(as-li-eq)<.005;
const tot=E.reduce((s,e)=>s+e.v,0);window.L={cap,ni,ln:-b["القروض"],fa:b["المعدات"]};
const row=(a,v)=>`<tr><td>${a}</td><td>${f(v)}</td></tr>`;
const names=t=>A.filter(a=>a[1]==t&&b[a[0]]);
$("out").innerHTML=E.length?`<div class="card"><h3>دفتر اليومية</h3>${tb(["#","مدين","دائن","المبلغ","البيان",""],E.map((e,i)=>`<tr><td>${i+1}</td><td>${e.d}</td><td>${e.c}</td><td>${f(e.v)}</td><td>${e.t||"—"}</td><td><button class="x" onclick="E.splice(${i},1);led()">✕</button></td></tr>`).join(""))}</div>
<div class="card"><h3>ميزان المراجعة <span class="bd">${"✔ متوازن"}</span></h3>${tb(["الحساب","النوع","مدين","دائن"],A.filter(a=>b[a[0]]).map(a=>`<tr><td>${a[0]}</td><td>${ty[a[1]]}</td><td>${b[a[0]]>0?f(b[a[0]]):""}</td><td>${b[a[0]]<0?f(-b[a[0]]):""}</td></tr>`).join("")+`<tr class="tt"><td colspan="2">الإجمالي</td><td>${f(tot)}</td><td>${f(tot)}</td></tr>`)}</div>
<div class="card"><h3>قائمة الدخل</h3>${tb(["البند","المبلغ"],row("الإيرادات",rev)+names("x").map(a=>row("(−) "+a[0],b[a[0]])).join("")+`<tr class="tt"><td>${ni>=0?"صافي الربح":"صافي الخسارة"}</td><td>${f(ni)}</td></tr>`)}</div>
<div class="card"><h3>قائمة المركز المالي <span class="bd" style="color:${ok?"var(--ok)":"var(--no)"}">${ok?"✔ الأصول = الالتزامات + الملكية":"✘ غير متوازنة"}</span></h3>${tb(["الأصول","المبلغ","الالتزامات والملكية","المبلغ"],`<tr><td>${names("a").map(a=>a[0]+": "+f(b[a[0]])).join("<br>")||"—"}</td><td></td><td>${names("l").map(a=>a[0]+": "+f(-b[a[0]])).join("<br>")}${cap?"<br>رأس المال: "+f(cap):""}<br>أرباح الفترة: ${f(ni)}</td><td></td></tr><tr class="tt"><td>إجمالي الأصول</td><td>${f(as)}</td><td>إجمالي الالتزامات والملكية</td><td>${f(li+eq)}</td></tr>`)}</div>`:'<p class="ex">أضف قيداً أو حمّل المثال لتظهر الميزان والقوائم.</p>'}
$("ea").onclick=()=>{const v=+$("ev").value;if(!(v>0)||$("ed").value===$("ec").value)return;E.push({d:$("ed").value,c:$("ec").value,v,t:$("et").value.replace(/[<>&"]/g,"").replace(/[\u0000-\u001f]/g,"").trim().slice(0,120)});$("ev").value="";$("et").value="";led()};
$("er").onclick=()=>{E=[];led()};
$("ex").onclick=()=>{E=[["النقدية","رأس المال",50000,"تأسيس الشركة"],["المعدات","النقدية",12000,"شراء معدات"],["المخزون","الموردون",8000,"شراء بضاعة بالآجل"],["النقدية","المبيعات",15000,"مبيعات نقدية"],["تكلفة المبيعات","المخزون",6000,"تكلفة البضاعة المباعة"],["الرواتب","النقدية",3000,"رواتب"],["الإيجار","النقدية",2000,"إيجار"]].map(x=>({d:x[0],c:x[1],v:x[2],t:x[3]}));led()};
led();
function tx(){const g=id=>+$(id).value||0;
const a=g("v1"),net=$("v2").value=="a"?a:a/1.15,vt=net*.15;
$("rv").innerHTML=`المبلغ قبل الضريبة: ${f(net)}<br>الضريبة 15%: ${f(vt)}<br>الإجمالي: ${f(net+vt)}`;
const p=g("v3")-g("v4");$("rv2").innerHTML=p>=0?`المستحق سداده لزاتكا: ${f(p)}`:`رصيد دائن قابل للاسترداد/الترحيل: ${f(-p)}`;
const sh=Math.min(100,Math.max(0,g("z6")))/100,ni=g("z3"),bs=g("z1")+g("z2")+ni-g("z4")-g("z5"),base=Math.max(bs,ni),zk=base*.025*sh,ct=Math.max(ni,0)*(1-sh)*.2;
$("rz").innerHTML=`الوعاء الزكوي: ${f(base)}<br>الزكاة 2.5% (حصة ${f(sh*100)}%): ${f(zk)}<br>ضريبة الدخل 20% (الحصة الأجنبية): ${f(ct)}<br>الإجمالي: ${f(zk+ct)}`;
const w=g("w1"),r=+$("w2").value;$("rw").innerHTML=`الضريبة المستقطعة: ${f(w*r)}<br>صافي المدفوع للمورد: ${f(w*(1-r))}`}
document.querySelectorAll("#t5 input,#t5 select").forEach(i=>{i.oninput=tx;i.onchange=tx});
$("zl").onclick=()=>{if(!window.L)return;[["z1",L.cap],["z2",L.ln],["z3",L.ni],["z4",L.fa]].forEach(x=>$(x[0]).value=Math.round(x[1]*100)/100);tx()};
tx();
function cs(){const g=id=>+$(id).value||0,m=g("c1"),l=g("c2"),o=g("c3"),u=g("c4"),t=m+l+o,uc=u>0?t/u:NaN;
$("rc").innerHTML=`التكلفة الأولية: ${f(m+l)}<br>تكلفة التحويل: ${f(l+o)}<br>تكلفة الإنتاج: ${f(t)}<br>تكلفة الوحدة: ${f(uc)}<br>سعر البيع المقترح: ${f(uc*(1+g("c5")/100))}`;
const rv=g("n1")+g("n2")+g("n3"),ex=g("n4")+g("n5")+g("n6");
$("rn").innerHTML=`إجمالي الإيرادات: ${f(rv)}<br>إجمالي المصروفات: ${f(ex)}<br>${rv>=ex?"الفائض":"العجز"}: ${f(Math.abs(rv-ex))}<br>نسبة مصروفات البرامج: ${f(g("n4")/ex*100)}%<br>تبرعات مقيدة يجب صرفها في غرضها: ${f(g("n2"))}`}
function cv(){const g=id=>+$(id).value||0,p=g("p1"),v=g("p2"),F=g("p3"),T=g("p4"),A=g("p5"),cm=p-v,be=F/cm;
$("rp").innerHTML=cm>0?`هامش مساهمة الوحدة: ${f(cm)} (${f(cm/p*100)}%)<br>التعادل: ${f(Math.ceil(be))} وحدة = ${f(be*p)}<br>الوحدات المستهدفة: ${f(Math.ceil((F+T)/cm))}<br>الربح الفعلي: ${f(A*cm-F)}<br>هامش الأمان: ${A>0?f((A-be)/A*100)+"%":"—"}`:"السعر يجب أن يزيد على التكلفة المتغيرة";
const pv=(g("q2")-g("q1"))*g("q4"),qv=(g("q4")-g("q3"))*g("q1"),fu=x=>x>0?"غير مناسب (U)":x<0?"مناسب (F)":"لا انحراف";
$("rq").innerHTML=`انحراف السعر: ${f(Math.abs(pv))} ${fu(pv)}<br>انحراف الكمية: ${f(Math.abs(qv))} ${fu(qv)}<br>الإجمالي: ${f(Math.abs(pv+qv))} ${fu(pv+qv)}`}
document.querySelectorAll("#t6 input").forEach(i=>i.oninput=()=>{cs();cv()});cs();cv();
const ZQ=[["حد التسجيل الإلزامي في ضريبة القيمة المضافة (إيرادات سنوية):",["187,500 ريال","375,000 ريال","1,000,000 ريال"],1,"التسجيل الإلزامي 375,000، والاختياري 187,500."],
["استقطاع رسوم الإدارة للأجانب:",["5%","15%","20%"],2,"رسوم الإدارة 20%، والإتاوات 15%."],
["ضريبة الدخل 20% تُفرض على:",["حصة السعوديين والخليجيين","حصة الشركاء غير السعوديين وغير الخليجيين","جميع المنشآت دون استثناء"],1,"الزكاة لحصة السعوديين والخليجيين، والضريبة لحصة الأجانب."],
["تُحسب الزكاة على:",["صافي الربح فقط","الوعاء الزكوي","إجمالي المبيعات"],1,"تُحسب على الوعاء، ولا تقتصر على الربح."],
["مدة تقديم الإقرار بعد نهاية السنة المالية:",["30 يوماً","120 يوماً","365 يوماً"],1,"خلال 120 يوماً."],
["ضريبة مخرجات 10,000 ومدخلات 3,000، المستحق سداده:",["7,000","13,000","3,000"],0,"10,000 − 3,000 = 7,000."],
["مبلغ شامل الضريبة 1,150، قيمة الضريبة 15%:",["150","172.5","115"],0,"1,150 ÷ 1.15 = 1,000، والضريبة 150."],
["تُورَّد ضريبة الاستقطاع خلال:",["أول 10 أيام من الشهر التالي","نهاية السنة","120 يوماً"],0,"خلال أول 10 أيام من الشهر التالي."],
["الإيجار السكني في ضريبة القيمة المضافة:",["معفى","خاضع بمعدل 15%","خاضع بمعدل صفر"],0,"تأجير العقار السكني معفى من الضريبة."],
["تُحسب الزكاة عن:",["سنة مالية كاملة","كل شهر","كل أسبوع"],0,"تُحسب على سنة مالية كاملة (حول)."],
["استقطاع الإتاوات للأجانب:",["5%","15%","20%"],1,"الإتاوات 15%."]];
const KQ=[["التكلفة الأولية =",["مواد مباشرة + أجور مباشرة","أجور مباشرة + تكاليف غير مباشرة","مواد + تكاليف غير مباشرة"],0,"المواد المباشرة + الأجور المباشرة."],
["تكلفة التحويل =",["مواد + أجور","أجور مباشرة + تكاليف غير مباشرة","مواد + تكاليف غير مباشرة"],1,"تكلفة التحويل تشمل الأجور المباشرة والتكاليف غير المباشرة."],
["ثابتة 10,000، سعر البيع 50، متغيرة 30، نقطة التعادل:",["500 وحدة","200 وحدة","1,000 وحدة"],0,"10,000 ÷ (50 − 30) = 500."],
["إيجار المصنع يُصنف:",["مباشر متغير","غير مباشر ثابت","مباشر ثابت"],1,"لا يرتبط بمنتج معين ولا يتغير بحجم الإنتاج."],
["وحدات مكتملة 800 وتحت التشغيل 200 بنسبة إنجاز 50%، الوحدات المكافئة:",["900","1,000","800"],0,"800 + (200 × 50%) = 900."],
["انحراف السعر = (الفعلي − المعياري) ×",["الكمية الفعلية","الكمية المعيارية","لا شيء"],0,"انحراف السعر يُضرب في الكمية الفعلية."],
["إذا زادت التكلفة الفعلية عن المعيارية فالانحراف:",["مناسب F","غير مناسب U","لا انحراف"],1,"زيادة التكلفة انحراف غير مناسب."],
["التكاليف الغارقة في اتخاذ القرار:",["تؤثر فيه","لا تؤثر فيه","هي المستقبلية فقط"],1,"الغارقة ماضية ولا تتغير بتغير القرار."],
["فائض الجمعية غير الربحية:",["يُوزّع على أعضائها","لا يُوزّع على أعضائها","يُسجّل ربحاً للملاك"],1,"الفائض يُستخدم في أهداف الجهة ولا يُوزّع."],
["المصروف هو:",["تكلفة استُنفدت في تحقيق الإيراد","ما يُدفع نقداً فقط","أصل ثابت"],0,"التكلفة تصبح مصروفاً عند استنفادها في تحقيق الإيراد."],
["معدل التحميل = التكاليف غير المباشرة المقدرة ÷",["أساس التحميل المقدر","المبيعات","الأرباح"],0,"مثل ساعات العمل المباشرة أو ساعات الآلة."],
["ثابتة 20,000، هامش مساهمة الوحدة 10، ربح مستهدف 5,000، الوحدات:",["2,500","2,000","500"],0,"(20,000 + 5,000) ÷ 10 = 2,500."]];
const AQ=[["المراجعة الخارجية يقوم بها:",["مراجع مستقل","موظفو المنشأة","المدير المالي"],0,"مراجع مستقل عن المنشأة."],
["رأي يعني وجود مشكلة جوهرية غير منتشرة:",["متحفظ","معاكس","الامتناع"],0,"الرأي المتحفظ."],
["تعذر الحصول على أدلة كافية وأثره جوهري ومنتشر:",["الامتناع عن إبداء الرأي","رأي غير معدل","رأي متحفظ"],0,"الامتناع عن إبداء الرأي."],
["الغش يتميز بأنه:",["غير متعمد","متعمد","خطأ حسابي فقط"],1,"الغش تصرف متعمد، بخلاف الخطأ."],
["نسيان تسجيل عملية يُعد:",["غشاً","خطأ","اختلاساً"],1,"تصرف غير متعمد فهو خطأ."],
["الملف الدائم يحتوي على:",["عقد التأسيس والنظام الأساسي","ميزان المراجعة للسنة","تقرير السنة الحالية"],0,"معلومات تفيد عدة سنوات."],
["من صفات الدليل الجيد:",["الكفاية والملاءمة والموثوقية","السرعة والتكلفة","الحجم فقط"],0,"الكفاية والملاءمة والموثوقية."],
["معايير العمل الميداني تتعلق ب:",["التخطيط والإشراف وفحص الأدلة","تأهيل المراجع","إبداء الرأي"],0,"التخطيط والإشراف وفحص الأدلة."],
["الرأي المعاكس يعني:",["تحريفات جوهرية ومنتشرة","قوائم عادلة","تعذر الحصول على أدلة"],0,"القوائم تتضمن تحريفات جوهرية ومنتشرة."],
["المراجعة الداخلية يقوم بها:",["موظفو المنشأة أو إدارتها","مراجع مستقل خارجي","جهة حكومية دائماً"],0,"هي مراجعة من داخل المنشأة."],
["من صفات المراجع القانوني:",["الاستقلال والموضوعية","السرعة","ملكية أسهم العميل"],0,"الاستقلال والموضوعية من أهم صفاته."],
["من أهداف الرقابة الداخلية:",["حماية الأصول ومنع الغش","زيادة الأرباح فقط","تقليل الضرائب"],0,"مع ضمان صحة البيانات والالتزام بالأنظمة."]];
const GX=[["مبدأ الاستحقاق يعني تسجيل الإيراد:",["عند اكتسابه","عند القبض فقط","في آخر السنة"],0,"يُسجَّل عند اكتسابه لا عند القبض."],
["ميزان المراجعة يُعد للتأكد من:",["تساوي مجموع المدين والدائن","صحة كل القيود","تحقيق الربح"],0,"يثبت توازن الأرصدة، لكنه لا يكشف كل الأخطاء."],
["إهلاك أصل تكلفته 12,000 وخردته 2,000 وعمره 5 سنوات (قسط ثابت):",["2,000","2,400","2,800"],0,"(12,000 − 2,000) ÷ 5 = 2,000 سنوياً."],
["نسبة التداول =",["أصول متداولة ÷ خصوم متداولة","خصوم ÷ أصول","صافي الربح ÷ المبيعات"],0,"تقيس السيولة قصيرة الأجل."]];
const QZ=[["مبادئ المحاسبة العامة",Q.concat(GX)],["الزكاة والضريبة",ZQ],["التكاليف والمنشآت",KQ],["المراجعة",AQ]];
let cur=-1,R={};
const gr=p=>p>=90?"ممتاز":p>=80?"جيد جداً":p>=70?"جيد":p>=60?"مقبول":"يحتاج إلى مراجعة";
function qs(){const c=$("qz");
if(cur==-1){c.innerHTML=`<h3>📝 اختر اختباراً</h3>${QZ.map((z,i)=>`<button class="opt" data-i="${i}">${z[0]} — ${z[1].length>10?z[1].length+" سؤالاً":z[1].length+" أسئلة"}${R[i]?` ✅ ${R[i].s}/${z[1].length}`:""}</button>`).join("")}<button class="p" id="fin">📊 الدرجات النهائية</button>`;
c.querySelectorAll(".opt").forEach(b=>b.onclick=()=>{cur=+b.dataset.i;qi=0;sc=0;qs()});$("fin").onclick=()=>{cur=99;qs()};return}
if(cur==99){let ts=0,tt=0;const rows=QZ.map((z,i)=>{const r=R[i];if(r){ts+=r.s;tt+=z[1].length}return r?`<tr><td>${z[0]}</td><td>${r.s}/${z[1].length}</td><td>${f(r.s/z[1].length*100)}%</td><td>${gr(r.s/z[1].length*100)}</td></tr>`:`<tr><td>${z[0]}</td><td colspan="3">لم تُجرَ بعد</td></tr>`}).join("");
const P=tt?ts/tt*100:0;c.innerHTML=`<h3>📊 الدرجات النهائية</h3>${tb(["الاختبار","الدرجة","النسبة","التقدير"],rows+`<tr class="tt"><td>المجموع</td><td>${ts}/${tt}</td><td>${f(P)}%</td><td>${tt?gr(P):"—"}</td></tr>`)}<button class="p" id="bk">العودة للاختبارات</button>`;$("bk").onclick=()=>{cur=-1;qs()};return}
const CQ=QZ[cur][1];
if(qi>=CQ.length){R[cur]={s:sc};const p=sc/CQ.length*100;c.innerHTML=`<h3>${QZ[cur][0]}</h3><div class="big" dir="ltr">${sc} / ${CQ.length}</div><p><b>${f(p)}%</b> — التقدير: <b>${gr(p)}</b></p><button class="p" id="rs">إعادة</button> <button class="p" id="mn">الاختبارات</button> <button class="p" id="fn">📊 الدرجات النهائية</button>`;
$("rs").onclick=()=>{qi=0;sc=0;qs()};$("mn").onclick=()=>{cur=-1;qs()};$("fn").onclick=()=>{cur=99;qs()};return}
const q=CQ[qi];c.innerHTML=`<h3>${QZ[cur][0]} — سؤال ${qi+1} من ${CQ.length}</h3><p><b>${q[0]}</b></p>${q[1].map((o,i)=>`<button class="opt" data-i="${i}">${o}</button>`).join("")}<p class="ex" id="qm"></p>`;
c.querySelectorAll(".opt").forEach(b=>b.onclick=()=>{const ok=+b.dataset.i===q[2];if(ok)sc++;c.querySelectorAll(".opt").forEach(x=>{x.disabled=true;if(+x.dataset.i===q[2])x.classList.add("ok")});if(!ok)b.classList.add("no");$("qm").textContent=q[3];const nx=document.createElement("button");nx.className="p";nx.textContent="التالي";nx.onclick=()=>{qi++;qs()};c.appendChild(nx)})}
const sh=a=>a.map(x=>[Math.random(),x]).sort((p,q)=>p[0]-q[0]).map(x=>x[1]),ri=(a,b)=>a+Math.floor(Math.random()*(b-a+1)),fm=x=>(Math.round(x*100)/100).toLocaleString("en"),r2=x=>Math.round(x*100)/100;
function N(q,c,d,ex){c=r2(c);const s=[c];d.map(r2).forEach(x=>{if(s.length<3&&!s.includes(x)&&x>=0)s.push(x)});let k=1;while(s.length<3){const x=r2(c+k*Math.max(1,Math.round(c*.1)));if(!s.includes(x))s.push(x);k++}const o=sh(s);return[q,o.map(fm),o.indexOf(c),ex]}
const GG=[
()=>{const a=ri(5,30)*10000,l=ri(1,a/10000-1)*5000;return N(`أصول المنشأة ${fm(a)} وخصومها ${fm(l)}، فحقوق الملكية =`,a-l,[a+l,l,a],"الأصول = الخصوم + حقوق الملكية.")},
()=>{const r=ri(10,90)*1000,e=ri(5,r/1000-1)*1000;return N(`إيرادات ${fm(r)} ومصروفات ${fm(e)}، صافي الربح =`,r-e,[r+e,e,r],"صافي الربح = الإيرادات − المصروفات.")},
()=>{const u=ri(5,30)*100,s=ri(1,5)*1000,y=[4,5,10][ri(0,2)],c=s+u*y;return N(`أصل تكلفته ${fm(c)} وخردته ${fm(s)} وعمره ${y} سنوات؛ إهلاكه السنوي (قسط ثابت) =`,u,[c/y,u*y,(c+s)/y],"(التكلفة − الخردة) ÷ العمر.")},
()=>{const a=ri(2,8)*10000,l=ri(1,4)*10000;return N(`أصول متداولة ${fm(a)} وخصوم متداولة ${fm(l)}، نسبة التداول =`,a/l,[l/a,a-l,a+l],"الأصول المتداولة ÷ الخصوم المتداولة.")},
()=>{const p=ri(1,5)*1000,s=p*ri(4,10);return N(`صافي ربح ${fm(p)} ومبيعات ${fm(s)}، هامش صافي الربح (%) =`,p/s*100,[s/p*100,p/s,(s-p)/s*100],"صافي الربح ÷ المبيعات × 100.")},
()=>{const a=ri(2,10)*100000,d=a*ri(2,8)/10;return N(`ديون ${fm(d)} وأصول ${fm(a)}، نسبة المديونية (%) =`,d/a*100,[a/d*100,d/a,(a-d)/a*100],"إجمالي الديون ÷ إجمالي الأصول × 100.")}];
const ZG=[
()=>{const n=ri(1,50)*1000;return N(`مبيعات خاضعة ${fm(n)} قبل الضريبة، ضريبة القيمة المضافة 15% =`,n*.15,[n*.05,n*.1,n*1.15],"الضريبة = المبلغ × 15%.")},
()=>{const n=ri(1,50)*1000,g=n*1.15;return N(`مبلغ شامل الضريبة ${fm(g)}، قيمة الضريبة =`,n*.15,[g*.15,n,g/15],"المبلغ قبل الضريبة = الشامل ÷ 1.15.")},
()=>{const o=ri(6,40)*1000,i=ri(1,5)*1000;return N(`ضريبة مخرجات ${fm(o)} ومدخلات ${fm(i)}، المستحق لزاتكا =`,o-i,[o+i,i,o],"المستحق = المخرجات − المدخلات.")},
()=>{const t=[["خدمات فنية",5],["إتاوات",15],["رسوم إدارة",20]][ri(0,2)],p=ri(1,50)*1000;return N(`دفعة ${t[0]} لغير مقيم بقيمة ${fm(p)}، الضريبة المستقطعة (${t[1]}%) =`,p*t[1]/100,[p*.05,p*.15,p*.2],"الاستقطاع = الدفعة × المعدل.")},
()=>{const b=ri(1,50)*40000;return N(`وعاء زكوي ${fm(b)} لمنشأة سعودية بالكامل، الزكاة =`,b*.025,[b*.2,b*.05,b*.25],"الزكاة = الوعاء × 2.5%.")},
()=>{const i=ri(1,20)*100000,s=[20,40,50][ri(0,2)];return N(`ربح معدل ${fm(i)} وحصة الأجانب ${s}%، ضريبة الدخل 20% =`,i*s/100*.2,[i*.2,i*s/100,i*(100-s)/100*.2],"الربح × حصة الأجانب × 20%.")},
()=>{const e=ri(5,20)*100000,l=ri(1,5)*100000,n=ri(1,5)*100000,f=ri(3,10)*50000;return N(`حقوق ملكية ${fm(e)} وقروض طويلة ${fm(l)} وربح معدل ${fm(n)} وأصول ثابتة ${fm(f)}، الوعاء =`,e+l+n-f,[e+l+n,e+l-f,e+n-f],"الملكية + القروض + الربح − الأصول الثابتة.")}];
const KG=[
()=>{const m=ri(2,9)*1000,w=ri(1,6)*1000,o=ri(1,5)*1000;return N(`مواد مباشرة ${fm(m)} وأجور مباشرة ${fm(w)} وغير مباشرة ${fm(o)}؛ التكلفة الأولية =`,m+w,[w+o,m+o,m+w+o],"مواد مباشرة + أجور مباشرة.")},
()=>{const m=ri(2,9)*1000,w=ri(1,6)*1000,o=ri(1,5)*1000;return N(`مواد مباشرة ${fm(m)} وأجور مباشرة ${fm(w)} وغير مباشرة ${fm(o)}؛ تكلفة التحويل =`,w+o,[m+w,m+o,m+w+o],"أجور مباشرة + تكاليف غير مباشرة.")},
()=>{const u=ri(1,5)*100,k=ri(5,30),t=u*k;return N(`تكلفة إنتاج ${fm(t)} لعدد ${fm(u)} وحدة، تكلفة الوحدة =`,k,[k*2,k+5,t/10],"الإجمالي ÷ عدد الوحدات.")},
()=>{const cm=ri(10,30),p=cm+ri(15,40),F=cm*ri(10,50)*10;return N(`ثابتة ${fm(F)} وسعر ${p} ومتغيرة ${p-cm}؛ نقطة التعادل (وحدة) =`,F/cm,[F/p,F/(p-cm),F/(p+cm)],"الثابتة ÷ هامش مساهمة الوحدة.")},
()=>{const d=ri(2,8)*100,w=ri(1,4)*100,pc=[25,50,75][ri(0,2)];return N(`وحدات تامة ${d} وتحت التشغيل ${w} بنسبة إنجاز ${pc}%؛ الوحدات المكافئة =`,d+w*pc/100,[d+w,d,d+w*(100-pc)/100],"تامة + (تحت التشغيل × نسبة الإنجاز).")},
()=>{const s=ri(5,20),a=s+ri(1,5),q=ri(1,10)*100;return N(`سعر معياري ${s} وفعلي ${a} وكمية فعلية ${fm(q)}؛ انحراف السعر (غير مناسب) =`,(a-s)*q,[(a-s)*q*2,a*q,(a-s)*q/2],"(الفعلي − المعياري) × الكمية الفعلية.")},
()=>{const A=ri(5,10)*100,B=ri(1,4)*100;return N(`مبيعات فعلية ${A} وحدة وتعادل ${B}؛ هامش الأمان (%) =`,(A-B)/A*100,[B/A*100,A-B,(A-B)/B*100],"(الفعلي − التعادل) ÷ الفعلي.")},
()=>{const cm=ri(5,20),F=cm*ri(10,30)*10,T=cm*ri(5,20)*10;return N(`ثابتة ${fm(F)} وهامش الوحدة ${cm} وربح مستهدف ${fm(T)}؛ الوحدات المستهدفة =`,(F+T)/cm,[F/cm,T/cm,(F-T)/cm],"(الثابتة + الربح) ÷ هامش الوحدة.")}];
function FB(b){return b.map(([g,q,a])=>{const pl=[...new Set(b.filter(x=>x[0]==g).map(x=>x[2]))].filter(x=>x!==a),o=sh([a,...sh(pl).slice(0,2)]);return[q,o,o.indexOf(a),"الإجابة: "+a]})}
const fl=(b,g,n=50)=>{const r=[],s=new Set();b.forEach(q=>{if(!s.has(q[0])){s.add(q[0]);r.push(q)}});let k=0;while(r.length<n&&g.length&&k++<500){const q=g[ri(0,g.length-1)]();if(!s.has(q[0])){s.add(q[0]);r.push(q)}}b.forEach(q=>{if(r.length<n&&!r.includes(q))r.push(q)});return sh(r)};
const ZB=[["r","معدل ضريبة القيمة المضافة:","15%"],["r","معدل الزكاة على الوعاء:","2.5%"],["r","ضريبة الدخل على حصة الشركاء الأجانب:","20%"],["r","استقطاع الخدمات الفنية لغير المقيمين:","5%"],["r","استقطاع الإتاوات:","15%"],["r","استقطاع رسوم الإدارة:","20%"],["r","ضريبة التصرفات العقارية:","5%"]];
const CB=[["t","أجور عمال خط الإنتاج تُصنف:","مباشرة"],["t","إيجار المصنع يُصنف:","غير مباشرة"],["t","المواد الخام الداخلة في المنتج تُصنف:","مباشرة"],["t","كهرباء المصنع تُصنف:","غير مباشرة"],["t","إهلاك آلات المصنع يُصنف:","غير مباشرة"],["b","راتب مدير المصنع الشهري يُعد تكلفة:","ثابتة"],["b","المواد المباشرة تُعد تكلفة:","متغيرة"],["b","عمولة مبيعات بنسبة من المبيعات تُعد تكلفة:","متغيرة"]];
const AB=[["op","قوائم معروضة بعدالة من جميع النواحي الجوهرية تعني:","رأي غير معدل"],["op","مشكلة جوهرية لكنها غير منتشرة تعني:","رأي متحفظ"],["op","تحريفات جوهرية ومنتشرة تعني:","رأي معاكس"],["op","تعذر الحصول على أدلة كافية مع أثر جوهري ومنتشر يعني:","الامتناع عن إبداء الرأي"],
["ty","مراجعة تقوم بها إدارة المنشأة أو موظفوها:","المراجعة الداخلية"],["ty","مراجعة يقوم بها مراجع مستقل:","المراجعة الخارجية"],["ty","مراجعة فحص القوائم المالية:","المراجعة المالية"],["ty","مراجعة تقييم كفاءة العمليات:","المراجعة التشغيلية"],["ty","مراجعة فحص الجهات الحكومية:","المراجعة الحكومية"],
["st","معايير تتعلق بتأهيل المراجع واستقلاله وعنايته:","المعايير العامة"],["st","معايير تتعلق بالتخطيط والإشراف وفحص الأدلة:","معايير العمل الميداني"],["st","معايير تتعلق بإبداء الرأي وإعداد التقرير:","معايير التقرير"],
["fi","عقد تأسيس الشركة يوضع في:","الملف الدائم"],["fi","النظام الأساسي يوضع في:","الملف الدائم"],["fi","الهيكل التنظيمي يوضع في:","الملف الدائم"],["fi","ميزان مراجعة سنة الفحص يوضع في:","الملف الجاري"],["fi","أوراق العمل ونتائج الفحص توضع في:","الملف الجاري"],["fi","تقرير المراجعة للسنة يوضع في:","الملف الجاري"],
["fe","تزوير مستند يُعد:","غشاً"],["fe","خطأ حسابي يُعد:","خطأ"],["fe","إخفاء الإيرادات عمداً يُعد:","غشاً"],["fe","نسيان تسجيل عملية يُعد:","خطأ"],["fe","اختلاس الأموال يُعد:","غشاً"],["fe","تسجيل مبلغ بصورة خاطئة يُعد:","خطأ"],
["ev","أدلة تكفي لتكوين رأي من صفاتها:","الكفاية"],["ev","أدلة مرتبطة بهدف الفحص من صفاتها:","الملاءمة"],["ev","أدلة يمكن الاعتماد عليها من صفاتها:","الموثوقية"],
["tr","عدم وجود مصلحة شخصية تؤثر على الرأي هو:","الاستقلال"],["tr","المحافظة على أسرار العميل هي:","السرية"],["tr","عدم الانحياز في الحكم هو:","الموضوعية"],["tr","امتلاك المعرفة والمهارة اللازمة هو:","الكفاءة المهنية"],
["ic","هدف رقابي يتعلق بسلامة ممتلكات المنشأة:","حماية الأصول"],["ic","هدف رقابي يتعلق بالتصرفات المتعمدة الضارة:","منع الغش والاختلاس"],["ic","هدف رقابي يتعلق بدقة السجلات:","ضمان صحة البيانات"],["ic","هدف رقابي يتعلق بجودة الأداء:","تحسين كفاءة العمل"],["ic","هدف رقابي يتعلق بالقوانين واللوائح:","الالتزام بالأنظمة"],
["pl","مستند مكتوب يتضمن إجراءات المراجعة هو:","برنامج المراجعة"],["pl","وضع خطة منظمة لتنفيذ المراجعة بكفاءة هو:","التخطيط"]];
QZ[0][1]=fl(QZ[0][1],GG);QZ[1][1]=fl(QZ[1][1].concat(FB(ZB)),ZG);QZ[2][1]=fl(QZ[2][1].concat(FB(CB)),KG);QZ[3][1]=fl(QZ[3][1].concat(FB(AB)),[]);
QZ.push(["اختبار المحاسبة الإنجليزية",[["1. What does Assets mean?",["الأصول","الالتزامات","الإيرادات"],0,"Assets = الأصول."],["2. Revenue increases on which side?",["Debit","Credit","Both"],1,"Revenue increases on the Credit side."],["3. What is the meaning of Expenses?",["الأرباح","المصروفات","رأس المال"],1,"Expenses = المصروفات."],["4. What is the Accounting Equation?",["Assets = Revenue - Expenses","Assets = Liabilities + Equity","Assets = Capital - Cash"],1,"Assets = Liabilities + Equity."],["5. What does Debit mean?",["دائن","مدين","ربح"],1,"Debit = مدين."]]]);
QZ.push(["أسئلة المحاسبة المتوسطة (2)",[["1. What is Depreciation?",["الإيراد","الإهلاك","المخزون"],1,"Depreciation = الإهلاك."],["2. What does FIFO mean?",["الوارد أولاً صادر أولاً","الوارد أخيراً صادر أولاً","المتوسط المرجح"],0,"FIFO = First In, First Out."],["3. What is Goodwill?",["المخزون","الشهرة","الأراضي"],1,"Goodwill = الشهرة."],["4. Which is a current liability?",["Buildings","Accounts Payable","Land"],1,"Accounts Payable is a current liability."],["5. How many sections are in the Cash Flow Statement?",["Two","Three","Four"],1,"Operating, Investing and Financing."]]]);
(function(){const C=$("cine"),g=id=>$(id).style,cl=(a,b,x)=>Math.min(1,Math.max(0,(x-a)/(b-a))),ap=()=>$("app").scrollIntoView({behavior:"smooth"});
let tk=0;function up(){tk=0;const r=C.getBoundingClientRect(),h=C.offsetHeight-innerHeight,p=Math.min(1,Math.max(0,-r.top/h)),c=(a,b)=>cl(a,b,p);

const z=c(.04,.3);g("pw").transform=`scale(${1+z*z*16})`;g("ct1").transform=`translateX(${-c(0,.2)*70}vw)`;g("ct2").transform=`translateX(${c(0,.2)*70}vw)`;
g("s1").opacity=1-c(.28,.34);g("hn").opacity=1-c(0,.04);
g("cl").opacity=c(.2,.32)*(1-c(.42,.5));g("cl").transform=`scale(${1+c(.2,.5)*.35})`;
g("s2").opacity=c(.4,.5)*(1-c(.74,.82));g("jet").transform=`translateY(${(1-c(.44,.62))*30}vh) scale(${.3+c(.44,.74)*1.1})`;
g("cw1").transform=`translateX(${-c(.62,.76)*60}vw)`;g("cw2").transform=`translateX(${c(.62,.76)*60}vw)`;
g("s3").opacity=c(.72,.84);g("cb3").transform=`scale(${1.35-c(.72,1)*.35})`;g("gb").transform=`translateY(${(1-c(.72,.9))*20}vh) scale(${.55+c(.72,.92)*.45})`;g("cp").opacity=c(.84,.95)}
addEventListener("scroll",()=>{if(!tk)tk=requestAnimationFrame(up)},{passive:true});addEventListener("resize",up);
$("go").onclick=ap;$("skip").onclick=ap;up()})();
(function(){const nav=document.querySelector("nav"),bs=[...nav.querySelectorAll("button")],S=d=>`<svg viewBox="0 0 24 24" aria-hidden="true">${d}</svg>`;
const IC=[S('<path d="M4 4h12a3 3 0 0 1 3 3v13H7a3 3 0 0 1-3-3z"/><path d="M8 9h7M8 13h7"/>'),S('<path d="M12 3v18M5 21h14M5 7h14"/><path d="M5 7l-3 7a3 3 0 0 0 6 0zM19 7l-3 7a3 3 0 0 0 6 0z"/>'),S('<rect x="5" y="3" width="14" height="18" rx="2"/><path d="M8 7h8M8 12h2M14 12h2M8 16h2M14 16h2"/>'),S('<circle cx="12" cy="12" r="9"/><path d="M8 12l3 3 5-6"/>'),S('<path d="M3 10l9-6 9 6M5 10v8M9 10v8M15 10v8M19 10v8M3 21h18"/>'),S('<circle cx="7" cy="7" r="2"/><circle cx="17" cy="17" r="2"/><path d="M19 5L5 19"/>'),S('<path d="M3 21V9l6 4V9l6 4V5h6v16z"/>')],
LB=["الملخص","القيود","المحاسبة","اختبار","المحاسب","الزكاة","التكاليف"],tr=document.createElement("div");tr.className="nt";
bs.forEach(b=>{const i=+b.dataset.t;b.innerHTML=IC[i]+"<em>"+LB[i]+"</em>";tr.appendChild(b)});
const ind=document.createElement("div");ind.className="ind";ind.innerHTML='<svg viewBox="0 0 100 40" preserveAspectRatio="none"><path d="M0 40C22 40 22 4 50 4S78 40 100 40"/></svg><i class="dt"></i>';tr.prepend(ind);nav.appendChild(tr);
function pos(){const a=tr.querySelector("button.on");if(!a)return;ind.style.width=a.offsetWidth+40+"px";ind.style.transform=`translateX(${a.offsetLeft-20}px)`}
bs.forEach(b=>b.addEventListener("click",()=>{pos();b.scrollIntoView({inline:"center",block:"nearest",behavior:"smooth"})}));
addEventListener("resize",pos);pos();setTimeout(pos,300);
$("qx").onclick=()=>{$("q").value="";render("");$("q").focus()}})();
(function(){const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in2");io.unobserve(e.target)}}),{threshold:.08});
document.querySelectorAll(".tab .card:not(#qz),.tab>details").forEach(el=>{el.classList.add("rv");io.observe(el)});
document.addEventListener("pointerdown",e=>{const b=e.target.closest("button.p,.opt");if(!b||b.disabled)return;const r=b.getBoundingClientRect(),s=Math.max(r.width,r.height)*2,sp=document.createElement("span");sp.className="rp";sp.style.cssText=`width:${s}px;height:${s}px;left:${e.clientX-r.left-s/2}px;top:${e.clientY-r.top-s/2}px`;b.appendChild(sp);setTimeout(()=>sp.remove(),650)});
const fo=new MutationObserver(ms=>ms.forEach(m=>{const t=m.target.nodeType==3?m.target.parentElement:m.target,r=t&&t.closest&&t.closest(".res");if(r){r.classList.remove("fl");void r.offsetWidth;r.classList.add("fl")}}));
document.querySelectorAll(".res").forEach(r=>fo.observe(r,{childList:true,characterData:true,subtree:true}));
function conf(){const cs=["#ff3b4e","#f0c040","#35d49a","#4f9be0","#fff"];for(let i=0;i<44;i++){const c=document.createElement("i");c.className="cf";c.style.cssText=`background:${cs[i%5]};--x:${(Math.random()-.5)*520}px;--y:${180+Math.random()*320}px;--r:${Math.random()*720}deg`;document.body.appendChild(c);setTimeout(()=>c.remove(),1800)}}
const qz=$("qz");let last=0;
new MutationObserver(()=>{const h=qz.querySelector("h3"),m=h&&h.textContent.match(/سؤال (\d+) من (\d+)/);let pb=qz.querySelector(".pb");
if(m&&!pb){pb=document.createElement("div");pb.className="pb";pb.innerHTML=`<i style="width:${last}%"></i>`;qz.prepend(pb);const p=+m[1]/+m[2]*100;requestAnimationFrame(()=>requestAnimationFrame(()=>{pb.firstChild.style.width=p+"%";last=p}))}
const bg=qz.querySelector(".big");if(bg&&!bg.dataset.d){bg.dataset.d=1;const mm=bg.textContent.match(/(\d+)\s*\/\s*(\d+)/);if(mm){const n=+mm[1],t0=performance.now(),st=now=>{const k=Math.min(1,(now-t0)/800);bg.textContent=Math.round(n*k)+" / "+mm[2];if(k<1)requestAnimationFrame(st)};requestAnimationFrame(st);const pc=qz.textContent.match(/([\d.]+)%/);if(pc&&+pc[1]>=80)conf()}}}).observe(qz,{childList:true});
const sp=document.createElement("div");sp.id="sp";document.body.appendChild(sp);addEventListener("scroll",()=>{const h=document.documentElement.scrollHeight-innerHeight;sp.style.width=(h>0?scrollY/h*100:0)+"%"},{passive:true})})();
(function(){const cf=$("cafe"),io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("v");io.unobserve(e.target)}}),{threshold:.15});
cf.querySelectorAll(".rv3,.im").forEach(el=>io.observe(el));
const start=()=>cf.classList.add("go");
start();
cf.querySelectorAll("[data-go]").forEach(c=>c.onclick=()=>document.querySelector('nav button[data-t="'+c.dataset.go+'"]').click());
const ap=()=>$("app").scrollIntoView({behavior:"smooth"});$("cfs").onclick=ap;$("cfe").onclick=ap;
const fl=[...cf.querySelectorAll(".fl3")];
function tick(){const r=cf.getBoundingClientRect();document.body.classList.toggle("in",r.bottom>innerHeight*.7);fl.forEach((f,i)=>f.style.setProperty("--y",(Math.max(0,scrollY)*(.12+i*.07))+"px"))}
addEventListener("scroll",tick,{passive:true});tick()})();
(function(){const it=$("intro");if(!it)return;if(matchMedia("(prefers-reduced-motion:reduce)").matches){it.remove();return}
const num=$("inum");let done=0;const close=()=>{if(done)return;done=1;it.classList.add("open");setTimeout(()=>it.remove(),1300)};
function run(){it.classList.add("go");const t0=performance.now(),D=2400,e=k=>k<.5?4*k*k*k:1-Math.pow(-2*k+2,3)/2;
(function st(n){const k=Math.min(1,Math.max(0,(n-t0)/D));num.textContent=Math.round(e(k)*100)+"%";if(k<1&&!done)requestAnimationFrame(st);else if(k>=1)setTimeout(close,300)})(t0)}
$("isk").onclick=close;
run()})();
(function(){const qz=$("qz"),pn=()=>{if(window.PN)return window.PN;try{return localStorage.getItem("pn")||""}catch(e){return""}};

function mk(txt){const w=document.createElement("div");w.className="shr";const who=document.createElement("div");who.className="who";who.textContent="المشارك: "+(pn()||"—");const a=document.createElement("a");a.className="wa2";a.target="_blank";a.rel="noopener";a.href="https://wa.me/?text="+encodeURIComponent(txt);a.textContent="إرسال النتيجة عبر واتساب";const b=document.createElement("button");b.className="p";b.textContent="نسخ النتيجة";b.onclick=()=>{(navigator.clipboard?navigator.clipboard.writeText(txt):Promise.reject()).then(()=>{b.textContent="✓ تم النسخ"},()=>{prompt("انسخ النتيجة:",txt)})};w.append(b);return w}
new MutationObserver(()=>{if(qz.querySelector(".shr"))return;let t="";
if(cur==99){const L=[];let ts=0,tt=0;QZ.forEach((z,i)=>{const r=R[i];if(r){ts+=r.s;tt+=z[1].length;L.push(z[0]+": "+r.s+"/"+z[1].length+" ("+gr(r.s/z[1].length*100)+")")}});if(!tt)return;t="الدرجات النهائية لـ "+(pn()||"مشارك")+":\n"+L.join("\n")+"\nالمجموع: "+ts+"/"+tt+" ("+gr(ts/tt*100)+")"}
else if(cur>=0&&qz.querySelector(".big")&&R[cur]){const z=QZ[cur],r=R[cur],p=Math.round(r.s/z[1].length*100);t="نتيجة "+(pn()||"مشارك")+" في اختبار «"+z[0]+"»: "+r.s+"/"+z[1].length+" ("+p+"%) - التقدير: "+gr(p)}
if(t)qz.appendChild(mk(t))}).observe(qz,{childList:true})})();
qs();
</script>
</body>
</html>

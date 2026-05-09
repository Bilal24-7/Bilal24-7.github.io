# Bilal24-7.github.io

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!--
╔══════════════════════════════════════════════════════════════════╗
║              DRIVELINK PRO — CUSTOMISATION GUIDE                 ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  STORE NAME & LOGO                                               ║
║    Search "BMTECH" and replace everywhere you see it.     ║
║    The <span> inside .logo colours the second word blue.         ║
║                                                                  ║
║  COLOURS  (edit the :root block near the top of <style>)         ║
║    --blue     main accent (buttons, badges, links)               ║
║    --blue-lt  lighter accent (labels, tags, hover)               ║
║    --bg       page background colour                             ║
║    --card     card / panel background                            ║
║                                                                  ║
║  PRODUCTS  (find `const products = [...]` in <script>)           ║
║    Edit name, desc, tags, price, orig (RRP), and IMAGE.          ║
║    IMAGE: '' shows the default graphic; set it to a URL or       ║
║    file path to use your own photo, e.g. 'images/10inch.jpg'     ║
║                                                                  ║
║  HERO BACKGROUND IMAGE                                           ║
║    Find id="hero-bg-img" and set src="YOUR_IMAGE_URL"            ║
║    Leave src="" to keep the dark gradient.                       ║
║                                                                  ║
║  HERO TEXT                                                       ║
║    Edit the <div class="hero"> section directly in the HTML.     ║
║                                                                  ║
║  TRUST BAR  (Free Shipping, Returns etc.)                        ║
║    Find <div class="trust-bar"> and edit items.                  ║
║                                                                  ║
║  COMPATIBILITY LIST  (find `const compatibility = [...]`)        ║
║    Add or remove BMW models from the array.                      ║
║                                                                  ║
║  STRIPE PAYMENTS                                                 ║
║    Set STRIPE_KEY to your publishable key (dashboard.stripe.com) ║
║    You also need a backend endpoint — see stripe.com/docs        ║
║                                                                  ║
║  GOOGLE ADDRESS AUTOCOMPLETE                                     ║
║    Set GOOGLE_PLACES_KEY to your API key.                        ║
║    Get one free: console.cloud.google.com → Enable "Places API"  ║
║    Restrict the key to your domain for security.                 ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
-->

<title>BMTECH — BMW Wireless CarPlay Screens</title>
<link href="https://fonts.googleapis.com/css2?family=Barlow:wght@300;400;500;600;700&family=Barlow+Condensed:wght@600;700;800&display=swap" rel="stylesheet">
<script src="https://js.stripe.com/v3/"></script>
<style>
*{margin:0;padding:0;box-sizing:border-box}

/* ── COLOUR VARIABLES — edit to retheme the whole site ─────── */
:root{
  --bg:#07070F;
  --card:#0E0E1C;
  --card2:#141426;
  --blue:#1C69D4;
  --blue-lt:#3D8EFF;
  --white:#fff;
  --gray:rgba(255,255,255,.55);
  --border:rgba(255,255,255,.07);
  --border2:rgba(255,255,255,.13)
}
html{scroll-behavior:smooth}
body{font-family:'Barlow',sans-serif;background:var(--bg);color:var(--white);overflow-x:hidden}

nav{position:fixed;top:0;left:0;right:0;z-index:100;display:flex;align-items:center;justify-content:space-between;padding:0 2.5rem;height:64px;background:rgba(7,7,15,.9);backdrop-filter:blur(20px);border-bottom:1px solid var(--border)}
.logo{font-family:'Barlow Condensed',sans-serif;font-size:1.4rem;font-weight:800;letter-spacing:.06em;text-transform:uppercase}
.logo span{color:var(--blue-lt)}
.nav-links{display:flex;gap:2rem;list-style:none}
.nav-links a{color:var(--gray);text-decoration:none;font-size:.8125rem;font-weight:600;letter-spacing:.08em;text-transform:uppercase;transition:color .2s}
.nav-links a:hover{color:var(--white)}
.cart-btn{background:var(--blue);color:#fff;border:none;cursor:pointer;display:flex;align-items:center;gap:8px;padding:.5rem 1.2rem;border-radius:6px;font-family:'Barlow',sans-serif;font-size:.875rem;font-weight:600;transition:background .2s}
.cart-btn:hover{background:var(--blue-lt)}
.cart-badge{background:#fff;color:var(--blue);width:20px;height:20px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:.7rem;font-weight:700}

.hero{min-height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;padding:8rem 2rem 4rem;position:relative;overflow:hidden}
#hero-bg-img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;opacity:.18;pointer-events:none}
.hero-glow{position:absolute;width:700px;height:700px;background:radial-gradient(circle,rgba(28,105,212,.15) 0%,transparent 70%);top:50%;left:50%;transform:translate(-50%,-50%);pointer-events:none}
.hero-content{position:relative;z-index:1;display:flex;flex-direction:column;align-items:center}
.hero-badge{display:inline-flex;align-items:center;gap:7px;background:rgba(28,105,212,.14);border:1px solid rgba(28,105,212,.3);color:var(--blue-lt);font-size:.72rem;font-weight:700;letter-spacing:.12em;text-transform:uppercase;padding:.4rem 1rem;border-radius:100px;margin-bottom:1.5rem}
.hero-dot{width:6px;height:6px;background:var(--blue-lt);border-radius:50%;animation:blink 2s infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.2}}
.hero h1{font-family:'Barlow Condensed',sans-serif;font-size:clamp(3rem,8vw,6rem);font-weight:800;line-height:.93;text-transform:uppercase;letter-spacing:-.01em;margin-bottom:1.5rem}
.hero h1 em{color:var(--blue-lt);font-style:normal}
.hero p{font-size:1.1rem;color:var(--gray);max-width:520px;line-height:1.7;margin-bottom:2.5rem}
.ctas{display:flex;gap:1rem;flex-wrap:wrap;justify-content:center}
.btn-primary{background:var(--blue);color:#fff;border:none;cursor:pointer;padding:.875rem 2rem;border-radius:8px;font-family:'Barlow',sans-serif;font-size:.9375rem;font-weight:600;transition:all .2s;text-decoration:none;display:inline-block}
.btn-primary:hover{background:var(--blue-lt);transform:translateY(-1px)}
.btn-outline{background:transparent;color:var(--white);border:1px solid var(--border2);cursor:pointer;padding:.875rem 2rem;border-radius:8px;font-family:'Barlow',sans-serif;font-size:.9375rem;font-weight:600;transition:all .2s;text-decoration:none;display:inline-block}
.btn-outline:hover{border-color:rgba(255,255,255,.3);background:rgba(255,255,255,.05)}

.hero-screen{width:100%;max-width:640px;margin:3.5rem auto 0}
.screen-frame{background:#0A0A14;border:2px solid rgba(255,255,255,.1);border-radius:16px;padding:7px;position:relative}
.screen-frame::before{content:'';position:absolute;inset:-1px;border-radius:17px;background:linear-gradient(135deg,rgba(28,105,212,.4),transparent 50%,rgba(28,105,212,.15));z-index:-1}
.screen-inner{background:linear-gradient(135deg,#0D1829 0%,#060912 100%);border-radius:10px;height:230px;overflow:hidden;display:flex}
.cp-dock{width:76px;background:rgba(0,0,0,.35);border-right:1px solid rgba(255,255,255,.06);display:flex;flex-direction:column;align-items:center;padding:14px 0;gap:10px}
.cp-icon{width:46px;height:46px;border-radius:11px;background:rgba(255,255,255,.05);display:flex;align-items:center;justify-content:center;font-size:1.25rem}
.cp-main{flex:1;padding:14px;display:flex;flex-direction:column;gap:10px}
.cp-top{display:flex;justify-content:space-between;align-items:center}
.cp-time{font-family:'Barlow Condensed',sans-serif;font-size:1.6rem;font-weight:700}
.cp-weather{font-size:.72rem;color:rgba(255,255,255,.5)}
.now-playing{background:rgba(28,105,212,.18);border:1px solid rgba(28,105,212,.28);border-radius:9px;padding:9px;display:flex;gap:9px;align-items:center}
.album{width:40px;height:40px;background:var(--blue);border-radius:7px;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:1.1rem}
.track-name{font-size:.75rem;font-weight:600;color:#fff}
.track-artist{font-size:.65rem;color:rgba(255,255,255,.45)}
.app-row{display:flex;gap:7px}
.app-tile{flex:1;background:rgba(255,255,255,.05);border-radius:7px;height:62px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:3px;font-size:1.1rem}
.app-label{font-size:.55rem;color:rgba(255,255,255,.45)}

.trust-bar{background:var(--card2);border-top:1px solid var(--border);border-bottom:1px solid var(--border);padding:1.75rem 2.5rem}
.trust-inner{max-width:1200px;margin:0 auto;display:flex;justify-content:center;align-items:center;gap:3rem;flex-wrap:wrap}
.trust-item{display:flex;align-items:center;gap:.6rem;font-size:.875rem;color:var(--gray);font-weight:500}

section{padding:5.5rem 2.5rem;max-width:1200px;margin:0 auto}
.section-label{font-size:.72rem;font-weight:700;letter-spacing:.16em;text-transform:uppercase;color:var(--blue-lt);margin-bottom:.6rem}
.section-title{font-family:'Barlow Condensed',sans-serif;font-size:clamp(2rem,4vw,3rem);font-weight:800;text-transform:uppercase;line-height:1;margin-bottom:.875rem}
.section-sub{color:var(--gray);font-size:.9375rem;max-width:500px;line-height:1.75}
.products-hdr{text-align:center;margin-bottom:3rem}
.products-hdr .section-sub{margin:0 auto}

.products-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:1.5rem}
.product-card{background:var(--card);border:1px solid var(--border);border-radius:16px;overflow:hidden;transition:border-color .25s,transform .25s;position:relative}
.product-card:hover{border-color:rgba(28,105,212,.4);transform:translateY(-3px)}
.product-card.featured{border-color:rgba(28,105,212,.45);background:linear-gradient(180deg,rgba(28,105,212,.07) 0%,var(--card) 60%)}
.feat-badge{position:absolute;top:14px;right:14px;z-index:2;background:var(--blue);color:#fff;font-size:.6rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;padding:4px 10px;border-radius:100px}
.product-visual{position:relative;height:220px;overflow:hidden;background:var(--card2)}
.product-img{width:100%;height:100%;object-fit:cover;display:block;transition:transform .4s}
.product-card:hover .product-img{transform:scale(1.04)}
.product-fallback{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:8px}
.mini-screen{border-radius:6px;border:1.5px solid rgba(255,255,255,.14);background:#050910;display:flex;align-items:center;justify-content:center;box-shadow:0 0 28px rgba(28,105,212,.2)}
.mini-screen-inner{width:calc(100% - 4px);height:calc(100% - 4px);background:linear-gradient(135deg,#0C1626,#050910);border-radius:4px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:4px;color:var(--blue-lt)}
.apple-mark{font-size:1.75rem;opacity:.75}
.screen-size-lbl{font-family:'Barlow Condensed',sans-serif;font-size:.65rem;font-weight:700;letter-spacing:.1em;opacity:.55}
.visual-fade{position:absolute;bottom:0;left:0;right:0;height:50px;background:linear-gradient(to top,var(--card),transparent);pointer-events:none}
.product-info{padding:1.25rem 1.35rem}
.product-compat{font-size:.68rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--blue-lt);margin-bottom:.35rem}
.product-name{font-family:'Barlow Condensed',sans-serif;font-size:1.35rem;font-weight:700;text-transform:uppercase;margin-bottom:.45rem;line-height:1.15}
.product-desc{font-size:.825rem;color:var(--gray);line-height:1.65;margin-bottom:.875rem}
.product-tags{display:flex;flex-wrap:wrap;gap:5px;margin-bottom:.875rem}
.tag{font-size:.62rem;font-weight:700;letter-spacing:.07em;text-transform:uppercase;padding:3px 8px;border-radius:4px;background:rgba(28,105,212,.11);color:var(--blue-lt);border:1px solid rgba(28,105,212,.2)}
.product-footer{display:flex;align-items:center;justify-content:space-between;border-top:1px solid var(--border);padding-top:.875rem}
.product-price{font-family:'Barlow Condensed',sans-serif;font-size:1.6rem;font-weight:700}
.product-orig{font-size:.72rem;color:var(--gray);text-decoration:line-through;margin-top:-2px}
.add-btn{background:var(--blue);color:#fff;border:none;cursor:pointer;padding:.6rem 1.2rem;border-radius:8px;font-family:'Barlow',sans-serif;font-size:.875rem;font-weight:600;transition:all .2s;white-space:nowrap}
.add-btn:hover{background:var(--blue-lt)}
.add-btn.added{background:#00BB73}

.features-wrap{background:var(--card);border-top:1px solid var(--border);border-bottom:1px solid var(--border);padding:5.5rem 2.5rem}
.features-inner{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:center}
.feat-grid{display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin-top:2rem}
.feat-icon{font-size:1.5rem;margin-bottom:.5rem}
.feat-title{font-weight:600;font-size:.9375rem;margin-bottom:.25rem}
.feat-desc{font-size:.8125rem;color:var(--gray);line-height:1.65}

.compat-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(175px,1fr));gap:.75rem;margin-top:2rem}
.compat-card{background:var(--card);border:1px solid var(--border);border-radius:10px;padding:.875rem 1rem;font-size:.875rem;font-weight:500;transition:border-color .2s}
.compat-card:hover{border-color:rgba(28,105,212,.35)}
.compat-card span{display:block;font-size:.7rem;color:var(--gray);margin-top:3px}

.cart-overlay{position:fixed;inset:0;z-index:200;background:rgba(0,0,0,.5);opacity:0;pointer-events:none;transition:opacity .3s}
.cart-overlay.open{opacity:1;pointer-events:all}
.cart-sidebar{position:fixed;top:0;right:0;bottom:0;width:390px;z-index:201;background:#0C0C1E;border-left:1px solid var(--border2);display:flex;flex-direction:column;transform:translateX(100%);transition:transform .3s cubic-bezier(.4,0,.2,1)}
.cart-sidebar.open{transform:translateX(0)}
.cart-hdr{display:flex;align-items:center;justify-content:space-between;padding:1.5rem;border-bottom:1px solid var(--border)}
.cart-hdr h3{font-family:'Barlow Condensed',sans-serif;font-size:1.2rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em}
.close-btn{background:none;border:none;color:var(--gray);cursor:pointer;font-size:1.25rem;padding:4px;line-height:1;transition:color .2s}
.close-btn:hover{color:#fff}
.cart-items{flex:1;overflow-y:auto;padding:1rem 1.5rem;display:flex;flex-direction:column;gap:.875rem}
.cart-empty{display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;gap:1rem;color:var(--gray)}
.cart-empty-icon{font-size:2.75rem;opacity:.3}
.cart-item{background:var(--card);border:1px solid var(--border);border-radius:10px;padding:.875rem;display:flex;gap:.875rem;align-items:flex-start}
.cart-thumb{width:52px;height:52px;border-radius:7px;background:var(--card2);flex-shrink:0;overflow:hidden;display:flex;align-items:center;justify-content:center;font-size:1.25rem;border:1px solid var(--border)}
.cart-thumb img{width:100%;height:100%;object-fit:cover}
.cart-item-info{flex:1}
.cart-item-name{font-weight:600;font-size:.875rem;margin-bottom:2px}
.cart-item-sub{font-size:.72rem;color:var(--gray);margin-bottom:.5rem}
.qty-row{display:flex;align-items:center;gap:7px}
.qty-btn{width:24px;height:24px;border-radius:4px;background:var(--card2);border:1px solid var(--border2);color:#fff;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:.875rem;transition:background .2s}
.qty-btn:hover{background:rgba(255,255,255,.1)}
.qty-val{font-size:.875rem;font-weight:600;min-width:18px;text-align:center}
.remove-btn{background:none;border:none;color:rgba(255,255,255,.2);cursor:pointer;font-size:.72rem;padding:2px;transition:color .2s;margin-left:4px}
.remove-btn:hover{color:#FF6B6B}
.cart-item-price{font-family:'Barlow Condensed',sans-serif;font-size:1.15rem;font-weight:700;flex-shrink:0}
.cart-footer{padding:1.25rem 1.5rem;border-top:1px solid var(--border)}
.cart-row{display:flex;justify-content:space-between;font-size:.875rem;color:var(--gray);margin-bottom:.35rem}
.cart-total-row{display:flex;justify-content:space-between;font-family:'Barlow Condensed',sans-serif;font-size:1.4rem;font-weight:700;margin-top:.5rem;margin-bottom:1rem}
.checkout-btn{width:100%;background:var(--blue);color:#fff;border:none;cursor:pointer;padding:.9375rem;border-radius:10px;font-family:'Barlow',sans-serif;font-size:.9375rem;font-weight:600;transition:all .2s;display:flex;align-items:center;justify-content:center;gap:8px}
.checkout-btn:hover{background:var(--blue-lt)}

.modal-overlay{position:fixed;inset:0;z-index:300;background:rgba(0,0,0,.72);display:flex;align-items:center;justify-content:center;opacity:0;pointer-events:none;transition:opacity .3s;padding:1rem}
.modal-overlay.open{opacity:1;pointer-events:all}
.modal{background:#0C0C1E;border:1px solid var(--border2);border-radius:20px;width:100%;max-width:520px;max-height:90vh;overflow-y:auto;transform:scale(.95);transition:transform .3s}
.modal-overlay.open .modal{transform:scale(1)}
.modal-hdr{display:flex;align-items:center;justify-content:space-between;padding:1.5rem;border-bottom:1px solid var(--border);position:sticky;top:0;background:#0C0C1E;z-index:2}
.modal-hdr h3{font-family:'Barlow Condensed',sans-serif;font-size:1.2rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em}
.modal-body{padding:1.5rem}
.setup-note{background:rgba(28,105,212,.1);border:1px solid rgba(28,105,212,.22);border-radius:9px;padding:.875rem 1.1rem;font-size:.775rem;color:var(--blue-lt);margin-bottom:1.25rem;line-height:1.7}
.setup-note strong{color:#fff}
.setup-note code{background:rgba(0,0,0,.35);padding:1px 5px;border-radius:4px;font-size:.72rem}
.setup-note a{color:var(--blue-lt)}
.order-summary{background:var(--card2);border-radius:10px;padding:.875rem 1rem;margin-bottom:.25rem}
.summary-label{font-size:.68rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--gray);margin-bottom:.625rem}
.summary-line{display:flex;justify-content:space-between;font-size:.8125rem;margin-bottom:3px;color:var(--gray)}
.summary-line.total{color:#fff;font-weight:700;font-size:.9375rem;margin-top:7px;padding-top:7px;border-top:1px solid var(--border)}
.form-section{font-family:'Barlow Condensed',sans-serif;font-size:.85rem;font-weight:700;text-transform:uppercase;letter-spacing:.1em;color:var(--blue-lt);margin:1.25rem 0 .625rem;padding-bottom:.45rem;border-bottom:1px solid var(--border)}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:.875rem}
.form-group{margin-bottom:.75rem}
.form-group label{display:block;font-size:.68rem;font-weight:700;letter-spacing:.09em;text-transform:uppercase;color:var(--gray);margin-bottom:5px;display:flex;align-items:center;gap:6px}
.form-group input,.form-group select{width:100%;background:var(--card);border:1px solid var(--border2);border-radius:8px;padding:.7rem .9rem;color:#fff;font-family:'Barlow',sans-serif;font-size:.9375rem;outline:none;transition:border-color .2s}
.form-group input::placeholder{color:rgba(255,255,255,.22)}
.form-group input:focus,.form-group select:focus{border-color:var(--blue)}
.form-group select{cursor:pointer}
.form-group select option{background:#0C0C1E}
#card-element{background:var(--card);border:1px solid var(--border2);border-radius:8px;padding:.7rem .9rem;transition:border-color .2s}
.card-errors{color:#FF6B6B;font-size:.7875rem;margin-top:5px;min-height:17px}
.pay-btn{width:100%;background:var(--blue);color:#fff;border:none;cursor:pointer;padding:.9375rem;border-radius:10px;font-family:'Barlow',sans-serif;font-size:.9375rem;font-weight:600;transition:all .2s;display:flex;align-items:center;justify-content:center;gap:8px;margin-top:.875rem}
.pay-btn:hover{background:var(--blue-lt)}
.pay-btn:disabled{opacity:.6;cursor:not-allowed}
.stripe-powered{display:flex;align-items:center;justify-content:center;gap:5px;font-size:.72rem;color:rgba(255,255,255,.28);margin-top:.625rem}
.success-state{display:none;flex-direction:column;align-items:center;justify-content:center;padding:3rem;text-align:center;gap:1rem}
.success-circle{width:64px;height:64px;border-radius:50%;background:rgba(0,187,115,.14);border:2px solid #00BB73;display:flex;align-items:center;justify-content:center;font-size:1.75rem}
.ac-hint{font-family:'Barlow',sans-serif;font-size:.68rem;font-weight:400;letter-spacing:0;text-transform:none;color:rgba(255,255,255,.3)}

/* Google Places dropdown dark theme */
.pac-container{background:#13132A!important;border:1px solid var(--border2)!important;border-radius:10px!important;box-shadow:0 8px 32px rgba(0,0,0,.5)!important;font-family:'Barlow',sans-serif!important;margin-top:4px;padding:4px}
.pac-item{padding:9px 12px!important;color:rgba(255,255,255,.75)!important;font-size:.875rem!important;cursor:pointer;border-top:1px solid rgba(255,255,255,.05)!important;border-radius:6px}
.pac-item:first-child{border-top:none!important}
.pac-item:hover,.pac-item-selected{background:rgba(28,105,212,.2)!important;color:#fff!important}
.pac-item-query{color:#fff!important;font-weight:600!important;font-size:.875rem!important}
.pac-matched{color:var(--blue-lt)!important}
.pac-icon,.pac-logo:after{display:none!important}

footer{background:var(--card);border-top:1px solid var(--border);padding:3.5rem 2.5rem 2rem}
.footer-grid{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:1.5fr 1fr 1fr;gap:2.5rem;margin-bottom:2.5rem}
.footer-logo{font-family:'Barlow Condensed',sans-serif;font-size:1.25rem;font-weight:800;letter-spacing:.06em;text-transform:uppercase;margin-bottom:.5rem}
.footer-logo span{color:var(--blue-lt)}
.footer-tagline{font-size:.8125rem;color:var(--gray);line-height:1.7;max-width:240px}
.footer-col h4{font-size:.68rem;font-weight:700;letter-spacing:.12em;text-transform:uppercase;color:var(--gray);margin-bottom:.875rem}
.footer-col ul{list-style:none;display:flex;flex-direction:column;gap:.4rem}
.footer-col ul a{color:rgba(255,255,255,.45);text-decoration:none;font-size:.8125rem;transition:color .2s}
.footer-col ul a:hover{color:#fff}
.footer-bottom{max-width:1200px;margin:0 auto;border-top:1px solid var(--border);padding-top:1.5rem;font-size:.75rem;color:rgba(255,255,255,.22)}
</style>
</head>
<body>

<!-- NAV — change store name here and in footer -->
<nav>
  <div class="logo">BM<span>TECH</span></div>
  <ul class="nav-links">
    <li><a href="#products">Products</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#compatibility">Compatibility</a></li>
  </ul>
  <button class="cart-btn" onclick="openCart()">
    🛒 Cart <span class="cart-badge" id="cart-count">0</span>
  </button>
</nav>

<!-- HERO — edit headline, subtext, and button labels here -->
<div class="hero">
  <!-- HERO BG IMAGE — set src="your-image.jpg" or leave "" for dark gradient -->
  <img id="hero-bg-img" src="" alt="" aria-hidden="true" onerror="this.style.display='none'">
  <div class="hero-glow"></div>
  <div class="hero-content">
    <div class="hero-badge"><span class="hero-dot"></span>Now Shipping Across Australia</div>
    <h1>Wireless CarPlay<br><em>for Your BMW</em></h1>
    <p>Premium plug-and-play touchscreen upgrades built specifically for your BMW. No coding, no dealership — just connect and drive.</p>
    <div class="ctas">
      <a href="#products" class="btn-primary">Shop Screens</a>
      <a href="#features" class="btn-outline">How It Works</a>
    </div>
    <div class="hero-screen">
      <div class="screen-frame">
        <div class="screen-inner">
          <div class="cp-dock">
            <div class="cp-icon">📱</div><div class="cp-icon">🗺️</div>
            <div class="cp-icon">🎵</div><div class="cp-icon">📞</div><div class="cp-icon">⚙️</div>
          </div>
          <div class="cp-main">
            <div class="cp-top">
              <div class="cp-time">09:41</div>
              <div class="cp-weather">Melbourne &middot; 18°C ☁️</div>
            </div>
            <div class="now-playing">
              <div class="album">🎵</div>
              <div><div class="track-name">Highway to Hell</div><div class="track-artist">AC/DC &bull; Apple Music</div></div>
              <div style="margin-left:auto;opacity:.7">▶</div>
            </div>
            <div class="app-row">
              <div class="app-tile">🗺️<div class="app-label">Maps</div></div>
              <div class="app-tile">📞<div class="app-label">Phone</div></div>
              <div class="app-tile">🎙️<div class="app-label">Siri</div></div>
              <div class="app-tile">💬<div class="app-label">Messages</div></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- TRUST BAR — edit these selling points -->
<div class="trust-bar">
  <div class="trust-inner">
    <div class="trust-item">🔌 True Plug &amp; Play</div>
    <div class="trust-item">📦 Free Express Shipping</div>
    <div class="trust-item">↩️ 30-Day Returns</div>
    <div class="trust-item">🛡️ 12-Month Warranty</div>
    <div class="trust-item">🇦🇺 Australian Support</div>
  </div>
</div>

<!-- PRODUCTS -->
<section id="products">
  <div class="products-hdr">
    <div class="section-label">Shop</div>
    <div class="section-title">Choose Your Screen</div>
    <div class="section-sub">Two sizes, both fully plug-and-play. Pick the one that fits your BMW's dashboard.</div>
  </div>
  <div class="products-grid" id="products-grid"></div>
</section>

<!-- FEATURES -->
<div class="features-wrap" id="features">
  <div class="features-inner">
    <div>
      <div class="section-label">Why BMTECH</div>
      <div class="section-title">Everything<br>You Need,<br>Nothing<br>You Don't</div>
      <p style="color:var(--gray);font-size:.9rem;line-height:1.75;margin-top:1rem;max-width:300px">Designed for BMW's existing wiring harness — no drilling, no coding, no voided warranty.</p>
    </div>
    <div class="feat-grid">
      <div><div class="feat-icon">🔌</div><div class="feat-title">True Plug &amp; Play</div><div class="feat-desc">Slots into your BMW's OEM harness in under 30 minutes with no professional installer needed.</div></div>
      <div><div class="feat-icon">📱</div><div class="feat-title">Wireless CarPlay</div><div class="feat-desc">Pair once and it auto-connects every time you get in the car. Zero cables, ever.</div></div>
      <div><div class="feat-icon">🤖</div><div class="feat-title">Android Auto</div><div class="feat-desc">Full wireless Android Auto for Samsung, Google Pixel, and all major Android phones.</div></div>
      <div><div class="feat-icon">🎛️</div><div class="feat-title">iDrive Retained</div><div class="feat-desc">All original BMW iDrive controls and steering wheel buttons keep working perfectly.</div></div>
      <div><div class="feat-icon">📷</div><div class="feat-title">Reverse Camera</div><div class="feat-desc">Works with your existing factory or aftermarket reverse camera out of the box.</div></div>
      <div><div class="feat-icon">⚡</div><div class="feat-title">5-Second Boot</div><div class="feat-desc">Ready before you've buckled up. No waiting, every single time.</div></div>
    </div>
  </div>
</div>

<!-- COMPATIBILITY -->
<section id="compatibility">
  <div class="section-label">Vehicle Compatibility</div>
  <div class="section-title">Supported BMW Models</div>
  <div class="section-sub">Not sure about your exact model? Contact us before ordering and we'll confirm fit.</div>
  <div class="compat-grid" id="compat-grid"></div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-grid">
    <div>
      <div class="footer-logo">BM<span>TECH</span></div>
      <div class="footer-tagline">Premium wireless CarPlay upgrades for BMW owners who demand the best in-car experience.</div>
    </div>
    <div class="footer-col">
      <h4>Products</h4>
      <ul><li><a href="#products">10" CarPlay Screen</a></li><li><a href="#products">12" CarPlay Screen</a></li></ul>
    </div>
    <div class="footer-col">
      <h4>Support</h4>
      <ul>
        <li><a href="#">Installation Guide</a></li>
        <li><a href="#">Compatibility Checker</a></li>
        <li><a href="#">30-Day Returns</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">© 2026 BMTECH. All rights reserved. Not affiliated with BMW AG or Apple Inc.</div>
</footer>

<!-- CART SIDEBAR -->
<div class="cart-overlay" id="cart-overlay" onclick="closeCart()"></div>
<div class="cart-sidebar" id="cart-sidebar">
  <div class="cart-hdr"><h3>Your Cart</h3><button class="close-btn" onclick="closeCart()">✕</button></div>
  <div class="cart-items" id="cart-items-el"></div>
  <div class="cart-footer" id="cart-footer" style="display:none">
    <div class="cart-row"><span>Subtotal</span><span id="cart-sub">$0.00</span></div>
    <div class="cart-row"><span>Shipping</span><span style="color:#00BB73">FREE Express</span></div>
    <div class="cart-total-row"><span>Total (AUD)</span><span id="cart-total">$0.00</span></div>
    <button class="checkout-btn" onclick="openCheckout()">🔒 Secure Checkout</button>
  </div>
</div>

<!-- CHECKOUT MODAL -->
<div class="modal-overlay" id="checkout-modal">
  <div class="modal">
    <div class="modal-hdr"><h3>Secure Checkout</h3><button class="close-btn" onclick="closeCheckout()">✕</button></div>
    <div class="modal-body" id="checkout-body">
      <div class="setup-note">
        <strong>⚙️ Developer setup:</strong> Add your <a href="https://dashboard.stripe.com/apikeys" target="_blank">Stripe key</a> (<code>STRIPE_KEY</code>) and <a href="https://console.cloud.google.com" target="_blank">Google Places key</a> (<code>GOOGLE_PLACES_KEY</code>) in the config block at the top of &lt;script&gt;. Until then, payments are in demo mode and address autocomplete is disabled.
      </div>
      <div class="order-summary" id="checkout-summary"></div>

      <div class="form-section">Contact</div>
      <div class="form-row">
        <div class="form-group"><label>First Name</label><input type="text" id="fname" placeholder="John" autocomplete="given-name"></div>
        <div class="form-group"><label>Last Name</label><input type="text" id="lname" placeholder="Smith" autocomplete="family-name"></div>
      </div>
      <div class="form-group"><label>Email</label><input type="email" id="email" placeholder="john@example.com" autocomplete="email"></div>

      <div class="form-section">Shipping Address</div>
      <div class="form-group">
        <label>Street Address <span class="ac-hint" id="ac-hint"></span></label>
        <input type="text" id="addr" placeholder="Start typing your address…" autocomplete="off">
      </div>
      <div class="form-row">
        <div class="form-group"><label>Suburb</label><input type="text" id="suburb" placeholder="Melbourne"></div>
        <div class="form-group"><label>Postcode</label><input type="text" id="postcode" placeholder="3000"></div>
      </div>
      <div class="form-group">
        <label>State</label>
        <select id="state">
          <option value="">Select state…</option>
          <option>VIC</option><option>NSW</option><option>QLD</option>
          <option>SA</option><option>WA</option><option>TAS</option><option>NT</option><option>ACT</option>
        </select>
      </div>

      <div class="form-section">Payment</div>
      <div class="form-group"><label>Card Details</label><div id="card-element"></div><div class="card-errors" id="card-errors"></div></div>
      <button class="pay-btn" id="pay-btn" onclick="handlePayment()">🔒 Pay Now — <span id="pay-total">$0.00</span></button>
      <div class="stripe-powered">🔒 Payments secured by Stripe</div>
    </div>
    <div class="success-state" id="success-state">
      <div class="success-circle">✅</div>
      <div style="font-family:'Barlow Condensed',sans-serif;font-size:1.75rem;font-weight:800;text-transform:uppercase">Order Confirmed!</div>
      <p style="color:var(--gray);font-size:.9rem;max-width:300px;line-height:1.7">Thanks for your order! A confirmation is heading to your inbox now.</p>
      <button class="btn-primary" onclick="closeCheckout()">Continue Shopping</button>
    </div>
  </div>
</div>

<script>
/* ══════════════════════════════════════════════════════════════
   CONFIG — put your keys here to go live
   ══════════════════════════════════════════════════════════════ */
const STRIPE_KEY         = 'pk_test_YOUR_PUBLISHABLE_KEY_HERE';
const GOOGLE_PLACES_KEY  = 'YOUR_GOOGLE_PLACES_API_KEY_HERE';
const PAYMENT_ENDPOINT   = '/api/create-payment-intent';

/* ══════════════════════════════════════════════════════════════
   PRODUCTS — edit name, desc, price, orig (RRP), tags, IMAGE
   IMAGE: '' = default graphic  |  'images/photo.jpg' = your photo
   ══════════════════════════════════════════════════════════════ */
const products = [
  {
    id: 1,
    compat: 'Compatible with Most BMW Models',
    name: '10" Wireless CarPlay Screen',
    desc: 'Our most popular size. The 10" HD touchscreen fits a wide range of BMW models and delivers a crisp, factory-quality upgrade with zero modifications needed.',
    tags: ['Wireless CarPlay', 'Android Auto', 'iDrive Retained', 'Backup Cam'],
    price: 399,   // ← selling price
    orig: 449,    // ← RRP / crossed-out price
    size: '10"',
    featured: false,
    IMAGE: '',    // ← e.g. 'images/10inch.jpg' or 'https://cdn.example.com/10.jpg'
  },
  {
    id: 2,
    compat: 'Compatible with Most BMW Models',
    name: '12" Wireless CarPlay Screen',
    desc: 'The ultimate BMW upgrade. Our largest screen fills the dash with a stunning 12" display — sharper, more immersive, and perfect for navigation and media.',
    tags: ['Wireless CarPlay', 'Android Auto', 'iDrive Retained', 'Split View', 'Backup Cam'],
    price: 449,
    orig: 499,
    size: '12"',
    featured: true,
    IMAGE: '',    // ← e.g. 'images/12inch.jpg'
  }
];

/* ══════════════════════════════════════════════════════════════
   COMPATIBILITY — add or remove BMW models here
   ══════════════════════════════════════════════════════════════ */
const compatibility = [
  {model:'BMW 1 Series (F20/F21)',years:'2012–2019'},{model:'BMW 2 Series (F22/F23)',years:'2013–2020'},
  {model:'BMW 3 Series (F30/F31)',years:'2013–2019'},{model:'BMW 4 Series (F32/F33/F36)',years:'2013–2020'},
  {model:'BMW 5 Series (F10/F11)',years:'2010–2017'},{model:'BMW 6 Series (F12/F13)',years:'2011–2018'},
  {model:'BMW 7 Series (F01/F02)',years:'2009–2015'},{model:'BMW X1 (F48)',years:'2015–2019'},
  {model:'BMW X3 (F25)',years:'2011–2017'},{model:'BMW X4 (F26)',years:'2014–2018'},
  {model:'BMW X5 (F15/E70)',years:'2013–2018'},{model:'BMW X6 (F16/E71)',years:'2014–2019'},
];

/* ── RENDER PRODUCTS ──────────────────────────────────────── */
function fallbackHTML(size) {
  const w = Math.min(parseInt(size)*16, 210), h = Math.min(parseInt(size)*10, 135);
  return `<div class="product-fallback"><div class="mini-screen" style="width:${w}px;height:${h}px"><div class="mini-screen-inner"><div class="apple-mark"></div><div class="screen-size-lbl">${size} HD CarPlay</div></div></div></div>`;
}

const grid = document.getElementById('products-grid');
products.forEach(p => {
  const visual = (p.IMAGE && p.IMAGE.trim())
    ? `<img class="product-img" src="${p.IMAGE}" alt="${p.name}" onerror="this.outerHTML=\`${fallbackHTML(p.size).replace(/`/g,"'")}\`">`
    : fallbackHTML(p.size);
  grid.innerHTML += `
    <div class="product-card ${p.featured?'featured':''}">
      ${p.featured?'<div class="feat-badge">Most Popular</div>':''}
      <div class="product-visual">${visual}<div class="visual-fade"></div></div>
      <div class="product-info">
        <div class="product-compat">${p.compat}</div>
        <div class="product-name">${p.name}</div>
        <div class="product-desc">${p.desc}</div>
        <div class="product-tags">${p.tags.map(t=>`<span class="tag">${t}</span>`).join('')}</div>
        <div class="product-footer">
          <div><div class="product-price">$${p.price}</div><div class="product-orig">RRP $${p.orig}</div></div>
          <button class="add-btn" id="atc-${p.id}" onclick="addToCart(${p.id})">Add to Cart</button>
        </div>
      </div>
    </div>`;
});

const cg = document.getElementById('compat-grid');
compatibility.forEach(c => { cg.innerHTML += `<div class="compat-card">${c.model}<span>${c.years}</span></div>`; });

/* ── CART ─────────────────────────────────────────────────── */
let cart = [];
function addToCart(id) {
  const p = products.find(x=>x.id===id), ex = cart.find(x=>x.id===id);
  if (ex) ex.qty++; else cart.push({...p,qty:1});
  renderCart();
  const b = document.getElementById(`atc-${id}`);
  b.textContent='✓ Added'; b.classList.add('added');
  setTimeout(()=>{b.textContent='Add to Cart';b.classList.remove('added');},2000);
}
function removeFromCart(id){cart=cart.filter(x=>x.id!==id);renderCart();}
function changeQty(id,d){const i=cart.find(x=>x.id===id);if(!i)return;i.qty+=d;if(i.qty<=0){removeFromCart(id);return;}renderCart();}
function getTotal(){return cart.reduce((s,i)=>s+i.price*i.qty,0);}

function renderCart() {
  const count = cart.reduce((s,i)=>s+i.qty,0);
  document.getElementById('cart-count').textContent = count;
  const el = document.getElementById('cart-items-el'), ft = document.getElementById('cart-footer');
  if (!cart.length) {
    el.innerHTML=`<div class="cart-empty"><div class="cart-empty-icon">🛒</div><div style="font-size:.875rem">Your cart is empty</div><button class="btn-outline" onclick="closeCart()" style="font-size:.8125rem;padding:.5rem 1.25rem;margin-top:.25rem">Browse Products</button></div>`;
    ft.style.display='none';
  } else {
    el.innerHTML=cart.map(i=>{
      const thumb=(i.IMAGE&&i.IMAGE.trim())?`<img src="${i.IMAGE}" alt="${i.name}" onerror="this.parentElement.textContent='🖥️'">`:'🖥️';
      return `<div class="cart-item"><div class="cart-thumb">${thumb}</div><div class="cart-item-info"><div class="cart-item-name">${i.name}</div><div class="cart-item-sub">${i.size} screen</div><div class="qty-row"><button class="qty-btn" onclick="changeQty(${i.id},-1)">−</button><span class="qty-val">${i.qty}</span><button class="qty-btn" onclick="changeQty(${i.id},1)">+</button><button class="remove-btn" onclick="removeFromCart(${i.id})">✕ Remove</button></div></div><div class="cart-item-price">$${(i.price*i.qty).toFixed(0)}</div></div>`;
    }).join('');
    ft.style.display='block';
    const t=getTotal();
    document.getElementById('cart-sub').textContent=`$${t.toFixed(2)}`;
    document.getElementById('cart-total').textContent=`$${t.toFixed(2)}`;
  }
}
function openCart(){document.getElementById('cart-overlay').classList.add('open');document.getElementById('cart-sidebar').classList.add('open');document.body.style.overflow='hidden';}
function closeCart(){document.getElementById('cart-overlay').classList.remove('open');document.getElementById('cart-sidebar').classList.remove('open');document.body.style.overflow='';}

/* ── GOOGLE PLACES AUTOCOMPLETE ───────────────────────────── */
let placesLoaded = false;
function loadGooglePlaces() {
  if (GOOGLE_PLACES_KEY === 'YOUR_GOOGLE_PLACES_API_KEY_HERE') {
    document.getElementById('ac-hint').textContent = '— add Google Places key to enable autocomplete';
    return;
  }
  if (placesLoaded) return;
  placesLoaded = true;
  document.getElementById('ac-hint').textContent = '— type to search';
  const s = document.createElement('script');
  s.src = `https://maps.googleapis.com/maps/api/js?key=${GOOGLE_PLACES_KEY}&libraries=places&callback=initAutocomplete`;
  s.async = true; s.defer = true;
  document.head.appendChild(s);
}

function initAutocomplete() {
  document.getElementById('ac-hint').textContent = '— start typing for suggestions';
  const input = document.getElementById('addr');
  const ac = new google.maps.places.Autocomplete(input, {
    componentRestrictions: { country: 'au' }, // ← change for other countries
    fields: ['address_components'],
    types: ['address']
  });
  ac.addListener('place_changed', () => {
    const place = ac.getPlace();
    if (!place.address_components) return;
    let num = '', route = '';
    document.getElementById('suburb').value = '';
    document.getElementById('postcode').value = '';
    document.getElementById('state').value = '';
    place.address_components.forEach(c => {
      const t = c.types[0];
      if (t==='street_number')              num   = c.long_name;
      if (t==='route')                      route = c.long_name;
      if (t==='locality')                   document.getElementById('suburb').value   = c.long_name;
      if (t==='postal_code')                document.getElementById('postcode').value = c.short_name;
      if (t==='administrative_area_level_1')document.getElementById('state').value    = c.short_name;
    });
    if (num || route) input.value = [num, route].filter(Boolean).join(' ');
    // focus the next empty field
    ['suburb','postcode'].find(id => { if (!document.getElementById(id).value) { document.getElementById(id).focus(); return true; } });
  });
}

/* ── STRIPE CHECKOUT ──────────────────────────────────────── */
let stripe, cardEl;
function initStripe() {
  if (STRIPE_KEY==='pk_test_YOUR_PUBLISHABLE_KEY_HERE'||stripe) return;
  try {
    stripe=Stripe(STRIPE_KEY);
    const els=stripe.elements();
    cardEl=els.create('card',{style:{base:{color:'#fff',fontFamily:'Barlow,sans-serif',fontSize:'15px','::placeholder':{color:'rgba(255,255,255,.22)'},iconColor:'#3D8EFF'},invalid:{color:'#FF6B6B'}}});
    cardEl.mount('#card-element');
    cardEl.on('change',e=>{document.getElementById('card-errors').textContent=e.error?e.error.message:'';});
  } catch(e){console.warn('Stripe init failed:',e);}
}

function openCheckout() {
  closeCart();
  const t=getTotal();
  document.getElementById('checkout-summary').innerHTML=`<div class="summary-label">Order Summary</div>${cart.map(i=>`<div class="summary-line"><span>${i.name} &times; ${i.qty}</span><span>$${(i.price*i.qty).toFixed(2)}</span></div>`).join('')}<div class="summary-line" style="color:rgba(255,255,255,.35)"><span>Shipping</span><span>Free Express</span></div><div class="summary-line total"><span>Total (AUD)</span><span>$${t.toFixed(2)}</span></div>`;
  document.getElementById('pay-total').textContent=`$${t.toFixed(2)}`;
  document.getElementById('checkout-modal').classList.add('open');
  document.body.style.overflow='hidden';
  initStripe();
  loadGooglePlaces();
}
function closeCheckout() {
  document.getElementById('checkout-modal').classList.remove('open');
  document.getElementById('success-state').style.display='none';
  document.getElementById('checkout-body').style.display='block';
  document.body.style.overflow='';
}
async function handlePayment() {
  const btn=document.getElementById('pay-btn');
  btn.disabled=true; btn.textContent='Processing…';
  if (STRIPE_KEY==='pk_test_YOUR_PUBLISHABLE_KEY_HERE') {
    await new Promise(r=>setTimeout(r,1600));
    document.getElementById('checkout-body').style.display='none';
    document.getElementById('success-state').style.display='flex';
    cart=[]; renderCart(); return;
  }
  try {
    const res=await fetch(PAYMENT_ENDPOINT,{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify({amount:Math.round(getTotal()*100),currency:'aud'})});
    const {client_secret}=await res.json();
    const result=await stripe.confirmCardPayment(client_secret,{payment_method:{card:cardEl,billing_details:{name:`${document.getElementById('fname').value} ${document.getElementById('lname').value}`,email:document.getElementById('email').value,address:{line1:document.getElementById('addr').value,city:document.getElementById('suburb').value,postal_code:document.getElementById('postcode').value,state:document.getElementById('state').value,country:'AU'}}}});
    if (result.error) {
      document.getElementById('card-errors').textContent=result.error.message;
      btn.disabled=false; btn.innerHTML=`🔒 Pay Now — $${getTotal().toFixed(2)}`;
    } else {
      document.getElementById('checkout-body').style.display='none';
      document.getElementById('success-state').style.display='flex';
      cart=[]; renderCart();
    }
  } catch(e) {
    document.getElementById('card-errors').textContent='Something went wrong. Please try again.';
    btn.disabled=false; btn.innerHTML=`🔒 Pay Now — $${getTotal().toFixed(2)}`;
  }
}

renderCart();
</script>
</body>
</html>

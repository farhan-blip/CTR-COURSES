<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CTR — Program Pelaut Malaysia</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Nunito:wght@300;400;600;700;800;900&family=Nunito+Sans:wght@400;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --blue-dark:  #0b3d91;
    --blue-mid:   #1565c0;
    --blue-bright:#1e88e5;
    --blue-light: #e3f0ff;
    --blue-pale:  #f0f6ff;
    --white:      #ffffff;
    --off-white:  #f7faff;
    --text-dark:  #0d1f3c;
    --text-body:  #2e4a72;
    --text-muted: #6b89b0;
    --gold:       #f4a900;
    --gold-light: #fff8e7;
    --success:    #0d9e6e;
    --border:     #d0e3f7;
    --shadow:     rgba(11,61,145,0.10);
  }

  * { margin:0; padding:0; box-sizing:border-box; }
  html { scroll-behavior:smooth; }

  body {
    background: var(--off-white);
    color: var(--text-dark);
    font-family: 'Nunito Sans', sans-serif;
    overflow-x: hidden;
  }

  /* NAV */
  nav {
    position: fixed;
    top:0; left:0; right:0;
    z-index: 100;
    height: 68px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 5%;
    background: var(--white);
    border-bottom: 2px solid var(--blue-light);
    box-shadow: 0 2px 20px var(--shadow);
  }

  .nav-logo { display:flex; align-items:center; gap:0.75rem; }

  .nav-logo-box {
    width:42px; height:42px;
    background: var(--blue-dark);
    border-radius:8px;
    display:flex; align-items:center; justify-content:center;
    color:white; font-family:'Bebas Neue',sans-serif; font-size:1.1rem; letter-spacing:2px;
  }

  .nav-logo-text { font-family:'Bebas Neue',sans-serif; font-size:1.5rem; letter-spacing:3px; color:var(--blue-dark); line-height:1; }
  .nav-logo-text span { color:var(--gold); }
  .nav-logo-sub { font-size:0.62rem; font-weight:700; letter-spacing:1.5px; text-transform:uppercase; color:var(--text-muted); }

  .nav-links { display:flex; gap:2rem; align-items:center; }
  .nav-links a { color:var(--text-body); text-decoration:none; font-size:0.85rem; font-weight:700; transition:color 0.2s; }
  .nav-links a:hover { color:var(--blue-bright); }

  .nav-auth { display:flex; gap:0.75rem; }

  .btn-outline { padding:0.5rem 1.2rem; border:2px solid var(--blue-mid); background:transparent; color:var(--blue-mid); font-family:'Nunito Sans',sans-serif; font-size:0.82rem; font-weight:700; cursor:pointer; border-radius:6px; transition:all 0.2s; }
  .btn-outline:hover { background:var(--blue-mid); color:white; }

  .btn-solid { padding:0.5rem 1.4rem; background:var(--blue-dark); color:white; font-family:'Nunito Sans',sans-serif; font-size:0.82rem; font-weight:700; cursor:pointer; border:2px solid var(--blue-dark); border-radius:6px; transition:all 0.2s; }
  .btn-solid:hover { background:var(--blue-bright); border-color:var(--blue-bright); transform:translateY(-1px); }

  /* HERO */
  #hero {
    min-height:100vh;
    background:linear-gradient(135deg, var(--blue-dark) 0%, var(--blue-mid) 50%, var(--blue-bright) 100%);
    position:relative;
    display:flex; align-items:center;
    padding:100px 5% 60px;
    overflow:hidden;
  }

  #hero::before {
    content:''; position:absolute; inset:0;
    background-image: repeating-linear-gradient(0deg,rgba(255,255,255,0.03) 0px,rgba(255,255,255,0.03) 1px,transparent 1px,transparent 60px),
      repeating-linear-gradient(90deg,rgba(255,255,255,0.03) 0px,rgba(255,255,255,0.03) 1px,transparent 1px,transparent 60px);
  }

  .hero-circle { position:absolute; border-radius:50%; }
  .hc1 { width:500px; height:500px; top:-150px; right:-100px; background:rgba(255,255,255,0.05); }
  .hc2 { width:300px; height:300px; bottom:-80px; right:200px; background:rgba(255,255,255,0.04); }
  .hc3 { width:200px; height:200px; top:100px; right:350px; background:rgba(244,169,0,0.08); }

  .hero-wrap {
    position:relative; z-index:2;
    display:grid; grid-template-columns:1fr 1fr; gap:4rem;
    align-items:center; width:100%; max-width:1200px; margin:0 auto;
  }

  @media(max-width:900px){ .hero-wrap{grid-template-columns:1fr} .hero-right{display:none} .nav-links{display:none} }

  .hero-tag {
    display:inline-flex; align-items:center; gap:0.5rem;
    padding:0.35rem 1rem; background:rgba(255,255,255,0.15); border:1px solid rgba(255,255,255,0.3);
    border-radius:20px; font-size:0.75rem; font-weight:700; letter-spacing:2px; text-transform:uppercase;
    color:rgba(255,255,255,0.9); margin-bottom:1.5rem;
    animation:fadeUp 0.7s ease both;
  }

  .hero-title {
    font-family:'Bebas Neue',sans-serif;
    font-size:clamp(3.5rem,8vw,7rem);
    line-height:0.92; letter-spacing:3px; color:white;
    margin-bottom:1.5rem;
    animation:fadeUp 0.7s 0.1s ease both;
  }
  .hero-title .gold { color:var(--gold); }

  .hero-desc { font-size:1rem; color:rgba(255,255,255,0.8); line-height:1.8; max-width:460px; margin-bottom:2.5rem; font-weight:400; animation:fadeUp 0.7s 0.2s ease both; }

  .hero-btns { display:flex; gap:1rem; flex-wrap:wrap; animation:fadeUp 0.7s 0.3s ease both; }

  .btn-hero-p { padding:0.85rem 2.2rem; background:white; color:var(--blue-dark); font-family:'Nunito Sans',sans-serif; font-size:0.9rem; font-weight:800; border:none; border-radius:8px; cursor:pointer; transition:all 0.2s; }
  .btn-hero-p:hover { background:var(--gold); transform:translateY(-2px); box-shadow:0 8px 25px rgba(0,0,0,0.2); }

  .btn-hero-o { padding:0.85rem 2.2rem; background:transparent; color:white; font-family:'Nunito Sans',sans-serif; font-size:0.9rem; font-weight:700; border:2px solid rgba(255,255,255,0.5); border-radius:8px; cursor:pointer; transition:all 0.2s; }
  .btn-hero-o:hover { border-color:white; background:rgba(255,255,255,0.1); }

  .hero-right { display:flex; flex-direction:column; gap:1.2rem; animation:fadeUp 0.7s 0.4s ease both; }

  .hero-stat-row { display:grid; grid-template-columns:1fr 1fr; gap:1.2rem; }

  .hero-stat { background:rgba(255,255,255,0.12); border:1px solid rgba(255,255,255,0.2); border-radius:12px; padding:1.5rem; backdrop-filter:blur(10px); text-align:center; }
  .hero-stat .num { font-family:'Bebas Neue',sans-serif; font-size:2.8rem; color:white; line-height:1; letter-spacing:2px; }
  .hero-stat .num span { color:var(--gold); }
  .hero-stat .lbl { font-size:0.72rem; font-weight:700; letter-spacing:1.5px; text-transform:uppercase; color:rgba(255,255,255,0.65); margin-top:0.3rem; }

  .hero-info { background:rgba(255,255,255,0.12); border:1px solid rgba(255,255,255,0.2); border-radius:12px; padding:1.5rem; backdrop-filter:blur(10px); }
  .hero-info h4 { font-size:0.75rem; font-weight:800; letter-spacing:2px; text-transform:uppercase; color:var(--gold); margin-bottom:0.75rem; }
  .hero-info p { font-size:0.88rem; color:rgba(255,255,255,0.8); line-height:1.6; }

  /* SECTIONS */
  .section-inner { max-width:1200px; margin:0 auto; padding:6rem 5%; }

  .sec-label { display:inline-block; padding:0.25rem 0.9rem; background:var(--blue-light); color:var(--blue-dark); font-size:0.7rem; font-weight:800; letter-spacing:2.5px; text-transform:uppercase; border-radius:4px; margin-bottom:0.8rem; }

  .sec-title { font-family:'Bebas Neue',sans-serif; font-size:clamp(2.2rem,4.5vw,3.8rem); letter-spacing:2px; color:var(--text-dark); line-height:1; margin-bottom:0.8rem; }
  .sec-title .blue { color:var(--blue-dark); }

  .sec-sub { font-size:1rem; color:var(--text-muted); line-height:1.7; max-width:540px; margin-bottom:3rem; font-weight:400; }

  /* SYARAT */
  #syarat { background:var(--white); }

  .syarat-intro {
    background:linear-gradient(135deg,var(--blue-pale),var(--blue-light));
    border:1px solid var(--border); border-radius:14px; padding:2rem 2.5rem;
    margin-bottom:3rem; display:flex; align-items:flex-start; gap:1.5rem;
  }

  .s-intro-icon { width:50px; height:50px; background:var(--blue-dark); border-radius:12px; display:flex; align-items:center; justify-content:center; font-size:1.5rem; flex-shrink:0; }
  .syarat-intro h3 { font-size:1.05rem; font-weight:800; color:var(--blue-dark); margin-bottom:0.4rem; }
  .syarat-intro p { font-size:0.9rem; color:var(--text-body); line-height:1.6; }

  .syarat-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:1.5rem; }

  .s-card { background:var(--white); border:2px solid var(--border); border-radius:14px; overflow:hidden; transition:transform 0.3s,border-color 0.3s,box-shadow 0.3s; }
  .s-card:hover { transform:translateY(-5px); border-color:var(--blue-bright); box-shadow:0 12px 35px var(--shadow); }

  .s-card-top { background:linear-gradient(135deg,var(--blue-dark),var(--blue-mid)); padding:1.5rem; display:flex; align-items:center; gap:1rem; }
  .s-card-icon { width:48px; height:48px; background:rgba(255,255,255,0.15); border-radius:10px; display:flex; align-items:center; justify-content:center; font-size:1.5rem; flex-shrink:0; }
  .s-card-top h3 { font-size:1rem; font-weight:800; color:white; }
  .s-card-top .tag { font-size:0.68rem; font-weight:700; letter-spacing:1px; text-transform:uppercase; color:rgba(255,255,255,0.6); margin-top:0.2rem; }

  .s-card-body { padding:1.5rem; }

  .s-item { display:flex; align-items:flex-start; gap:0.75rem; padding:0.65rem 0; border-bottom:1px solid var(--blue-light); font-size:0.88rem; color:var(--text-body); line-height:1.5; }
  .s-item:last-of-type { border-bottom:none; }
  .s-item .dot { width:8px; height:8px; background:var(--blue-bright); border-radius:50%; flex-shrink:0; margin-top:5px; }

  .s-note { margin-top:1rem; padding:0.75rem 1rem; background:var(--gold-light); border-left:3px solid var(--gold); border-radius:0 6px 6px 0; font-size:0.8rem; color:#7a5000; line-height:1.5; }

  /* FASA */
  #fasa { background:var(--off-white); }

  .fasa-tabs { display:flex; border-radius:12px; overflow:hidden; border:2px solid var(--border); margin-bottom:3rem; }

  .f-tab { flex:1; padding:1.5rem 2rem; background:var(--white); cursor:pointer; transition:all 0.3s; border-right:2px solid var(--border); }
  .f-tab:last-child { border-right:none; }
  .f-tab.active { background:var(--blue-dark); }

  .f-tab-num { font-family:'Bebas Neue',sans-serif; font-size:0.8rem; letter-spacing:2px; text-transform:uppercase; margin-bottom:0.3rem; }
  .f-tab:not(.active) .f-tab-num { color:var(--text-muted); }
  .f-tab.active .f-tab-num { color:rgba(255,255,255,0.6); }

  .f-tab h3 { font-family:'Bebas Neue',sans-serif; font-size:1.6rem; letter-spacing:2px; }
  .f-tab:not(.active) h3 { color:var(--text-dark); }
  .f-tab.active h3 { color:white; }

  .f-tab p { font-size:0.8rem; margin-top:0.3rem; }
  .f-tab:not(.active) p { color:var(--text-muted); }
  .f-tab.active p { color:rgba(255,255,255,0.7); }

  .f-panel { display:none; }
  .f-panel.active { display:block; }

  .f1-grid { display:grid; grid-template-columns:1fr 1fr; gap:1.5rem; margin-bottom:1.5rem; }
  @media(max-width:700px){ .f1-grid{grid-template-columns:1fr} }

  .doc-card { background:var(--white); border:2px solid var(--border); border-radius:12px; overflow:hidden; transition:border-color 0.3s,box-shadow 0.3s; }
  .doc-card:hover { border-color:var(--blue-bright); box-shadow:0 8px 25px var(--shadow); }

  .doc-head { background:linear-gradient(90deg,var(--blue-dark),var(--blue-mid)); padding:1.2rem 1.5rem; display:flex; align-items:center; gap:1rem; }
  .doc-head .icon { font-size:1.6rem; background:rgba(255,255,255,0.15); width:44px; height:44px; border-radius:8px; display:flex; align-items:center; justify-content:center; flex-shrink:0; }
  .doc-head h4 { font-size:1rem; font-weight:800; color:white; }
  .doc-head p { font-size:0.75rem; color:rgba(255,255,255,0.65); margin-top:0.1rem; }

  .doc-body { padding:1.4rem; }
  .doc-item { display:flex; gap:0.75rem; padding:0.6rem 0; border-bottom:1px solid var(--blue-light); font-size:0.87rem; color:var(--text-body); line-height:1.5; }
  .doc-item:last-child { border-bottom:none; }
  .doc-item .ck { color:var(--success); font-weight:700; flex-shrink:0; }

  .f1-warn { background:var(--gold-light); border:2px solid var(--gold); border-radius:12px; padding:1.5rem; display:flex; gap:1rem; align-items:flex-start; }
  .f1-warn .wi { font-size:1.5rem; flex-shrink:0; }
  .f1-warn h4 { font-size:0.9rem; font-weight:800; color:#7a5000; margin-bottom:0.3rem; }
  .f1-warn p { font-size:0.84rem; color:#8a6010; line-height:1.6; }

  .pakej-grid { display:grid; grid-template-columns:1fr 1fr; gap:1.5rem; }
  @media(max-width:700px){ .pakej-grid{grid-template-columns:1fr} }

  .p-box { background:var(--white); border:2px solid var(--border); border-radius:14px; overflow:hidden; transition:border-color 0.3s,box-shadow 0.3s,transform 0.3s; }
  .p-box:hover { border-color:var(--blue-bright); box-shadow:0 12px 35px var(--shadow); transform:translateY(-4px); }
  .p-box.feat { border-color:var(--gold); }

  .p-head { background:linear-gradient(135deg,var(--blue-dark),var(--blue-mid)); padding:1.8rem; position:relative; }
  .p-box.feat .p-head { background:linear-gradient(135deg,#7a5000,var(--gold)); }

  .p-badge { position:absolute; top:1rem; right:1rem; padding:0.25rem 0.75rem; background:white; color:var(--blue-dark); font-size:0.65rem; font-weight:800; letter-spacing:1px; text-transform:uppercase; border-radius:20px; }
  .p-box.feat .p-badge { color:#7a5000; }

  .p-num { font-size:0.7rem; font-weight:800; letter-spacing:2px; text-transform:uppercase; color:rgba(255,255,255,0.65); margin-bottom:0.3rem; }
  .p-head h3 { font-family:'Bebas Neue',sans-serif; font-size:2rem; letter-spacing:2px; color:white; }
  .p-price { margin-top:0.5rem; font-size:0.82rem; color:rgba(255,255,255,0.7); }
  .p-price strong { font-family:'Bebas Neue',sans-serif; font-size:2rem; color:white; letter-spacing:1px; }

  .p-body { padding:1.5rem; }

  .p-feat { display:flex; align-items:flex-start; gap:0.75rem; padding:0.7rem 0; border-bottom:1px solid var(--blue-light); font-size:0.88rem; color:var(--text-body); line-height:1.4; }
  .p-feat:last-of-type { border-bottom:none; }
  .p-feat .ck { color:var(--success); font-weight:700; flex-shrink:0; font-size:1rem; }
  .p-feat .cx { color:#ccc; flex-shrink:0; font-size:1rem; }
  .p-feat .sub { font-size:0.75rem; color:var(--text-muted); margin-top:0.15rem; }

  .p-highlight { margin-top:1rem; padding:0.8rem 1rem; background:var(--blue-pale); border-radius:8px; font-size:0.8rem; color:var(--blue-dark); font-weight:600; display:flex; align-items:center; gap:0.5rem; }

  .p-foot { padding:0 1.5rem 1.5rem; }

  /* BOOKING */
  #booking { background:var(--white); }

  .bk-layout { display:grid; grid-template-columns:1fr 1.5fr; gap:3.5rem; align-items:start; }
  @media(max-width:900px){ .bk-layout{grid-template-columns:1fr} }

  .bk-steps { margin-top:2rem; }
  .bk-step { display:flex; gap:1.2rem; padding:1.2rem 0; border-bottom:1px solid var(--border); align-items:flex-start; }
  .bk-step:last-child { border-bottom:none; }
  .bk-num { width:36px; height:36px; background:var(--blue-dark); color:white; border-radius:50%; display:flex; align-items:center; justify-content:center; font-family:'Bebas Neue',sans-serif; font-size:1.1rem; letter-spacing:1px; flex-shrink:0; }
  .bk-step h4 { font-size:0.92rem; font-weight:800; color:var(--text-dark); margin-bottom:0.25rem; }
  .bk-step p { font-size:0.82rem; color:var(--text-muted); line-height:1.5; }

  .form-card { background:var(--white); border:2px solid var(--border); border-radius:16px; padding:2.5rem; box-shadow:0 4px 30px var(--shadow); }
  .fc-title { font-family:'Bebas Neue',sans-serif; font-size:1.8rem; letter-spacing:2px; color:var(--blue-dark); margin-bottom:0.3rem; }
  .fc-sub { font-size:0.82rem; color:var(--text-muted); margin-bottom:2rem; }

  .f-row { display:grid; grid-template-columns:1fr 1fr; gap:1rem; }
  @media(max-width:600px){ .f-row{grid-template-columns:1fr} }
  .f-g { margin-bottom:1rem; }
  .f-g label { display:block; font-size:0.75rem; font-weight:800; letter-spacing:1px; text-transform:uppercase; color:var(--text-muted); margin-bottom:0.45rem; }
  .f-g input, .f-g select, .f-g textarea { width:100%; padding:0.75rem 1rem; background:var(--off-white); border:2px solid var(--border); color:var(--text-dark); font-family:'Nunito Sans',sans-serif; font-size:0.9rem; border-radius:8px; outline:none; transition:border-color 0.2s,background 0.2s; -webkit-appearance:none; }
  .f-g select option { background:white; }
  .f-g input:focus, .f-g select:focus, .f-g textarea:focus { border-color:var(--blue-bright); background:white; }
  .f-g input::placeholder, .f-g textarea::placeholder { color:#bbb; }

  .btn-blue { width:100%; padding:1rem; background:var(--blue-dark); color:white; font-family:'Nunito Sans',sans-serif; font-size:0.92rem; font-weight:800; letter-spacing:1px; border:none; border-radius:8px; cursor:pointer; margin-top:0.5rem; transition:all 0.2s; }
  .btn-blue:hover { background:var(--blue-bright); transform:translateY(-2px); box-shadow:0 8px 25px rgba(11,61,145,0.25); }

  .success-box { display:none; padding:1.2rem 1.5rem; background:#e8faf3; border:2px solid var(--success); border-radius:10px; margin-bottom:1.5rem; font-size:0.88rem; color:var(--success); font-weight:700; }

  /* PAYMENT */
  #payment { background:var(--off-white); }

  .pay-methods { display:grid; grid-template-columns:repeat(auto-fit,minmax(230px,1fr)); gap:1.2rem; margin-bottom:3rem; }

  .pay-m { background:var(--white); border:2px solid var(--border); border-radius:12px; padding:1.5rem; cursor:pointer; transition:all 0.2s; display:flex; align-items:flex-start; gap:1rem; }
  .pay-m:hover { border-color:var(--blue-bright); box-shadow:0 6px 20px var(--shadow); }
  .pay-m.active { border-color:var(--blue-dark); background:var(--blue-pale); }

  .pay-m-icon { width:44px; height:44px; background:var(--blue-light); border-radius:10px; display:flex; align-items:center; justify-content:center; font-size:1.4rem; flex-shrink:0; }
  .pay-m.active .pay-m-icon { background:var(--blue-dark); }
  .pay-m h4 { font-size:0.9rem; font-weight:800; color:var(--text-dark); margin-bottom:0.3rem; }
  .pay-m p { font-size:0.78rem; color:var(--text-muted); line-height:1.4; }
  .pay-chk { margin-left:auto; width:22px; height:22px; border-radius:50%; border:2px solid var(--border); flex-shrink:0; display:flex; align-items:center; justify-content:center; font-size:0.7rem; color:transparent; transition:all 0.2s; }
  .pay-m.active .pay-chk { background:var(--blue-dark); border-color:var(--blue-dark); color:white; }

  .pay-bottom { display:grid; grid-template-columns:1fr 1.4fr; gap:2rem; align-items:start; }
  @media(max-width:900px){ .pay-bottom{grid-template-columns:1fr} }

  .pay-sum { background:var(--white); border:2px solid var(--border); border-radius:14px; overflow:hidden; }
  .pay-sum-head { background:linear-gradient(90deg,var(--blue-dark),var(--blue-mid)); padding:1.2rem 1.5rem; font-family:'Bebas Neue',sans-serif; font-size:1.2rem; letter-spacing:2px; color:white; }
  .pay-sum-body { padding:1.5rem; }
  .pay-r { display:flex; justify-content:space-between; align-items:center; padding:0.65rem 0; font-size:0.88rem; border-bottom:1px solid var(--blue-light); }
  .pay-r:last-child { border-bottom:none; padding-top:1rem; }
  .pay-r .l { color:var(--text-muted); }
  .pay-r .v { font-weight:700; color:var(--text-dark); }
  .pay-r.tot .v { color:var(--blue-dark); font-size:1.4rem; font-family:'Bebas Neue',sans-serif; letter-spacing:1px; }

  .pay-form { background:var(--white); border:2px solid var(--border); border-radius:14px; padding:2rem; }

  /* FOOTER */
  footer { background:var(--blue-dark); color:white; padding:4rem 5% 2rem; }
  .footer-inner { max-width:1200px; margin:0 auto; }
  .footer-grid { display:grid; grid-template-columns:2fr 1fr 1fr 1fr; gap:3rem; margin-bottom:3rem; }
  @media(max-width:800px){ .footer-grid{grid-template-columns:1fr 1fr} }
  .f-logo { font-family:'Bebas Neue',sans-serif; font-size:2rem; letter-spacing:3px; color:white; margin-bottom:1rem; }
  .f-logo span { color:var(--gold); }
  .footer-brand p { font-size:0.85rem; color:rgba(255,255,255,0.6); line-height:1.7; max-width:280px; }
  .f-contact { margin-top:1.5rem; }
  .f-contact div { font-size:0.82rem; color:rgba(255,255,255,0.6); margin-bottom:0.5rem; display:flex; align-items:flex-start; gap:0.5rem; }
  .footer-col h4 { font-size:0.75rem; font-weight:800; letter-spacing:2px; text-transform:uppercase; color:rgba(255,255,255,0.4); margin-bottom:1.2rem; }
  .footer-col a { display:block; font-size:0.85rem; color:rgba(255,255,255,0.7); text-decoration:none; margin-bottom:0.65rem; transition:color 0.2s; }
  .footer-col a:hover { color:white; }
  .footer-btm { border-top:1px solid rgba(255,255,255,0.1); padding-top:1.5rem; display:flex; justify-content:space-between; align-items:center; font-size:0.78rem; color:rgba(255,255,255,0.4); flex-wrap:wrap; gap:0.5rem; }
  .uitm-tag { padding:0.3rem 0.9rem; background:rgba(244,169,0,0.15); border:1px solid rgba(244,169,0,0.3); border-radius:20px; font-size:0.72rem; color:var(--gold); font-weight:700; }

  /* MODALS */
  .overlay { display:none; position:fixed; inset:0; background:rgba(11,61,145,0.4); backdrop-filter:blur(6px); z-index:999; align-items:center; justify-content:center; padding:1rem; }
  .overlay.open { display:flex; }
  .modal { background:white; border-radius:16px; padding:2.5rem; width:100%; max-width:440px; position:relative; box-shadow:0 25px 60px rgba(11,61,145,0.25); animation:popIn 0.3s ease; }
  @keyframes popIn { from{opacity:0;transform:scale(0.94) translateY(16px)} to{opacity:1;transform:none} }
  .m-close { position:absolute; top:1.2rem; right:1.2rem; width:32px; height:32px; background:var(--blue-light); border:none; border-radius:50%; cursor:pointer; font-size:1rem; color:var(--blue-dark); display:flex; align-items:center; justify-content:center; transition:background 0.2s; }
  .m-close:hover { background:var(--border); }
  .m-logo-wrap { display:flex; align-items:center; gap:0.75rem; margin-bottom:1.8rem; }
  .m-logo-box { width:40px; height:40px; background:var(--blue-dark); border-radius:8px; display:flex; align-items:center; justify-content:center; color:white; font-family:'Bebas Neue',sans-serif; font-size:1rem; letter-spacing:2px; }
  .m-logo-text { font-family:'Bebas Neue',sans-serif; font-size:1.4rem; letter-spacing:3px; color:var(--blue-dark); }
  .m-logo-text span { color:var(--gold); }
  .modal h2 { font-family:'Bebas Neue',sans-serif; font-size:2rem; letter-spacing:2px; color:var(--text-dark); margin-bottom:1.8rem; }
  .m-footer { text-align:center; margin-top:1.5rem; font-size:0.82rem; color:var(--text-muted); }
  .m-footer a { color:var(--blue-bright); cursor:pointer; font-weight:700; }

  /* TOAST */
  .toast { position:fixed; bottom:2rem; right:2rem; padding:1rem 1.5rem; background:var(--blue-dark); color:white; border-radius:10px; font-size:0.88rem; font-weight:600; z-index:9999; transform:translateY(80px); opacity:0; transition:all 0.35s; max-width:320px; box-shadow:0 8px 30px rgba(11,61,145,0.3); }
  .toast.show { transform:translateY(0); opacity:1; }

  @keyframes fadeUp { from{opacity:0;transform:translateY(28px)} to{opacity:1;transform:none} }
  .fade-up { opacity:0; transform:translateY(20px); transition:opacity 0.6s ease,transform 0.6s ease; }
  .fade-up.vis { opacity:1; transform:none; }

  ::-webkit-scrollbar { width:5px; }
  ::-webkit-scrollbar-track { background:#e3f0ff; }
  ::-webkit-scrollbar-thumb { background:var(--blue-mid); border-radius:3px; }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">
    <div class="nav-logo-box">CTR</div>
    <div>
      <div class="nav-logo-text">C<span>T</span>R</div>
      <div class="nav-logo-sub">Central Tech Resources</div>
    </div>
  </div>
  <div class="nav-links">
    <a href="#syarat">Syarat</a>
    <a href="#fasa">Program</a>
    <a href="#booking">Daftar</a>
    <a href="#payment">Bayaran</a>
  </div>
  <div class="nav-auth">
    <button class="btn-outline" onclick="openM('login')">Log Masuk</button>
    <button class="btn-solid" onclick="openM('register')">Daftar Sekarang</button>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-circle hc1"></div>
  <div class="hero-circle hc2"></div>
  <div class="hero-circle hc3"></div>
  <div class="hero-wrap">
    <div>
      <div class="hero-tag">⚓ Program Maritim Bertauliah</div>
      <h1 class="hero-title">Program<br>Pelaut<br><span class="gold">Malaysia</span></h1>
      <p class="hero-desc">Program latihan komprehensif oleh Central Tech Resources untuk melahirkan pelaut profesional bertaraf antarabangsa. Terbuka kepada semua individu yang berminat dalam bidang perkapalan.</p>
      <div class="hero-btns">
        <button class="btn-hero-p" onclick="document.getElementById('booking').scrollIntoView({behavior:'smooth'})">Mohon Sekarang</button>
        <button class="btn-hero-o" onclick="document.getElementById('fasa').scrollIntoView({behavior:'smooth'})">Lihat Program →</button>
      </div>
    </div>
    <div class="hero-right">
      <div class="hero-stat-row">
        <div class="hero-stat"><div class="num">18<span>-</span>35</div><div class="lbl">Lingkungan Umur</div></div>
        <div class="hero-stat"><div class="num">6<span style="font-size:1.5rem"> BLN</span></div><div class="lbl">Praktikal Di Kapal</div></div>
      </div>
      <div class="hero-info">
        <h4>📍 Lokasi Pusat Latihan</h4>
        <p>A31, Tingkat 1, IM 5/2, Jalan Persiaran Sultan Abu Bakar, Indera Mahkota, 25200 Kuantan, Pahang</p>
      </div>
      <div class="hero-info">
        <h4>📞 Hubungi Kami</h4>
        <p>013-8047141 &nbsp;|&nbsp; 09-5729971<br>www.centraltech.com.my</p>
      </div>
    </div>
  </div>
</section>

<!-- SYARAT -->
<section id="syarat">
  <div class="section-inner">
    <div class="fade-up">
      <div class="sec-label">Kelayakan</div>
      <h2 class="sec-title">Syarat-Syarat <span class="blue">Pendaftaran</span></h2>
      <p class="sec-sub">Semak kelayakan anda sebelum membuat permohonan. Semua syarat mesti dipenuhi sepenuhnya.</p>
    </div>

    <div class="syarat-intro fade-up">
      <div class="s-intro-icon">📋</div>
      <div>
        <h3>Tentang Program Ini</h3>
        <p>Program Pelaut Malaysia adalah program latihan maritim yang terbuka kepada individu yang berminat menceburi dalam bidang perkapalan. Program ini merangkumi latihan teknikal, sijil profesional dan penempatan praktikal di atas kapal atau feri selama 6 bulan bagi pakej lengkap.</p>
      </div>
    </div>

    <div class="syarat-grid fade-up">

      <div class="s-card">
        <div class="s-card-top">
          <div class="s-card-icon">🎂</div>
          <div><h3>Umur 18 – 35 Tahun</h3><div class="tag">Had Umur</div></div>
        </div>
        <div class="s-card-body">
          <div class="s-item"><div class="dot"></div>Calon mestilah berumur sekurang-kurangnya <strong>18 tahun</strong> pada tarikh pendaftaran.</div>
          <div class="s-item"><div class="dot"></div>Had umur maksimum adalah <strong>35 tahun</strong> semasa memohon program.</div>
          <div class="s-item"><div class="dot"></div>Umur dikira berdasarkan tarikh lahir dalam Kad Pengenalan (MyKad) atau Pasport.</div>
          <div class="s-item"><div class="dot"></div>Calon yang hampir mencapai 35 tahun digalakkan mendaftar segera kerana tempat adalah terhad.</div>
          <div class="s-note">💡 Dokumen diperlukan: Salinan MyKad atau Pasport yang masih sah.</div>
        </div>
      </div>

      <div class="s-card">
        <div class="s-card-top">
          <div class="s-card-icon">👁️</div>
          <div><h3>Tidak Rabun Warna</h3><div class="tag">Ujian Penglihatan</div></div>
        </div>
        <div class="s-card-body">
          <div class="s-item"><div class="dot"></div>Calon mesti lulus ujian <strong>Ishihara Colour Vision Test</strong> — ujian standard penglihatan warna maritim.</div>
          <div class="s-item"><div class="dot"></div>Ini adalah keperluan wajib mengikut standard <strong>STCW (Standards of Training, Certification and Watchkeeping)</strong> antarabangsa.</div>
          <div class="s-item"><div class="dot"></div>Rabun warna boleh menjejaskan keselamatan di atas kapal terutama dalam mengenali lampu isyarat dan bendera maritim.</div>
          <div class="s-item"><div class="dot"></div>Ujian ini akan dilakukan oleh doktor bertauliah semasa Marine Medical Check Up dalam Fasa 1.</div>
          <div class="s-note">💡 Ujian penglihatan dijalankan secara automatik semasa pemeriksaan perubatan Fasa 1.</div>
        </div>
      </div>

      <div class="s-card">
        <div class="s-card-top">
          <div class="s-card-icon">📖</div>
          <div><h3>Boleh Membaca, Menulis & Mengira</h3><div class="tag">Kemahiran Asas</div></div>
        </div>
        <div class="s-card-body">
          <div class="s-item"><div class="dot"></div>Berkebolehan membaca dan memahami teks dalam <strong>Bahasa Malaysia</strong> dan/atau <strong>Bahasa Inggeris</strong> asas.</div>
          <div class="s-item"><div class="dot"></div>Boleh menulis dengan jelas untuk tujuan laporan dan rekod pelayaran di atas kapal.</div>
          <div class="s-item"><div class="dot"></div>Berkebolehan mengira asas untuk keperluan navigasi, pengukuran bahan dan rekod kerja harian.</div>
          <div class="s-item"><div class="dot"></div>Kemahiran Bahasa Inggeris asas adalah kelebihan kerana dokumentasi maritim antarabangsa menggunakan Bahasa Inggeris.</div>
          <div class="s-note">💡 Tiada keperluan kelulusan akademik minimum — kemahiran asas sudah mencukupi untuk mendaftar.</div>
        </div>
      </div>

      <div class="s-card">
        <div class="s-card-top">
          <div class="s-card-icon">💪</div>
          <div><h3>Sihat Tubuh Badan</h3><div class="tag">Kesihatan Fizikal & Mental</div></div>
        </div>
        <div class="s-card-body">
          <div class="s-item"><div class="dot"></div>Bebas daripada penyakit kronik yang boleh menjejaskan prestasi kerja di atas kapal seperti jantung, asma teruk, atau epilepsi.</div>
          <div class="s-item"><div class="dot"></div>Tidak mengalami masalah kesihatan mental yang serius yang boleh menjejaskan keselamatan.</div>
          <div class="s-item"><div class="dot"></div>Berupaya melakukan kerja fizikal — memanjat, mengangkat peralatan, dan bekerja dalam pelbagai keadaan cuaca.</div>
          <div class="s-item"><div class="dot"></div>Bebas daripada pergantungan dadah dan alkohol. Ujian saringan dadah akan dijalankan.</div>
          <div class="s-item"><div class="dot"></div>Sijil <strong>Medical Fitness Certificate</strong> dikeluarkan oleh doktor bertauliah Kementerian Kesihatan Malaysia.</div>
          <div class="s-note">💡 Pemeriksaan kesihatan penuh akan dilakukan dalam Fasa 1 sebelum kursus bermula.</div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- FASA -->
<section id="fasa">
  <div class="section-inner">
    <div class="fade-up">
      <div class="sec-label">Struktur Program</div>
      <h2 class="sec-title">Fasa & Pakej <span class="blue">Latihan</span></h2>
      <p class="sec-sub">Program dibahagikan kepada dua fasa. Fasa 1 adalah persediaan wajib sebelum memasuki Fasa 2.</p>
    </div>

    <div class="fasa-tabs fade-up">
      <div class="f-tab active" onclick="switchFasa(0)">
        <div class="f-tab-num">Fasa 01</div>
        <h3>Persediaan Asas</h3>
        <p>Dokumen wajib sebelum kursus</p>
      </div>
      <div class="f-tab" onclick="switchFasa(1)">
        <div class="f-tab-num">Fasa 02</div>
        <h3>Latihan Teknikal</h3>
        <p>Pilih Pakej 1 atau Pakej 2</p>
      </div>
    </div>

    <!-- FASA 1 -->
    <div class="f-panel active" id="panel-0">
      <div class="f1-grid">
        <div class="doc-card">
          <div class="doc-head">
            <div class="icon">🏥</div>
            <div><h4>Marine Medical Check Up</h4><p>Pemeriksaan Perubatan Maritim</p></div>
          </div>
          <div class="doc-body">
            <div class="doc-item"><span class="ck">✓</span>Pemeriksaan fizikal menyeluruh oleh doktor bertauliah maritim.</div>
            <div class="doc-item"><span class="ck">✓</span>Ujian penglihatan termasuk ujian warna (Ishihara Test).</div>
            <div class="doc-item"><span class="ck">✓</span>Ujian pendengaran dan tekanan darah.</div>
            <div class="doc-item"><span class="ck">✓</span>Ujian makmal asas (darah dan air kencing).</div>
            <div class="doc-item"><span class="ck">✓</span>Sijil Medical Fitness diiktiraf oleh Jabatan Laut Malaysia (JLM).</div>
            <div class="doc-item"><span class="ck">✓</span>Sijil sah selama 2 tahun dari tarikh pemeriksaan.</div>
          </div>
        </div>
        <div class="doc-card">
          <div class="doc-head">
            <div class="icon">🪪</div>
            <div><h4>Seaman Card</h4><p>Kad Kelasi / Buku Pelaut</p></div>
          </div>
          <div class="doc-body">
            <div class="doc-item"><span class="ck">✓</span>Kad pengenalan rasmi pelaut Malaysia dikeluarkan oleh Jabatan Laut Malaysia.</div>
            <div class="doc-item"><span class="ck">✓</span>Diperlukan untuk menaiki kapal dan menjalani penempatan praktikal.</div>
            <div class="doc-item"><span class="ck">✓</span>Dokumen diperlukan: MyKad, gambar pasport terbaru, sijil perubatan.</div>
            <div class="doc-item"><span class="ck">✓</span>Proses permohonan mengambil masa 1–2 minggu bekerja.</div>
            <div class="doc-item"><span class="ck">✓</span>Mesti sah dan aktif sebelum mendaftar kursus Fasa 2.</div>
            <div class="doc-item"><span class="ck">✓</span>CTR boleh membantu proses permohonan Seaman Card anda.</div>
          </div>
        </div>
      </div>
      <div class="f1-warn">
        <div class="wi">⚠️</div>
        <div>
          <h4>Penting — Sila Baca Sebelum Mendaftar</h4>
          <p>Kedua-dua dokumen dalam Fasa 1 <strong>(Marine Medical Check Up dan Seaman Card)</strong> mesti disediakan dan disahkan <strong>sebelum</strong> anda boleh mendaftar untuk kursus Fasa 2. Tanpa dokumen ini, pendaftaran Fasa 2 tidak akan dapat diproses. Hubungi CTR untuk panduan lanjut.</p>
        </div>
      </div>
    </div>

    <!-- FASA 2 -->
    <div class="f-panel" id="panel-1">
      <div class="pakej-grid">
        <div class="p-box">
          <div class="p-head">
            <div class="p-num">Pakej 01 — Lengkap</div>
            <h3>Pakej Lengkap</h3>
            <div class="p-price">Mulai dari <strong>RM 3,500</strong></div>
          </div>
          <div class="p-body">
            <div class="p-feat"><span class="ck">✓</span><div><div>Basic Training (BT)</div><div class="sub">Latihan asas keselamatan dan survival di laut</div></div></div>
            <div class="p-feat"><span class="ck">✓</span><div><div>Designated Security Duties (DSD)</div><div class="sub">Latihan tugas keselamatan kapal ISPS Code</div></div></div>
            <div class="p-feat"><span class="ck">✓</span><div><div>BTOCT (Tanker)</div><div class="sub">Latihan asas kapal tangki minyak / kimia</div></div></div>
            <div class="p-feat"><span class="ck">✓</span><div><div>Crowd Management</div><div class="sub">Pengurusan penumpang dalam situasi kecemasan</div></div></div>
            <div class="p-feat"><span class="ck">✓</span><div><div>Penempatan Praktikal 6 Bulan</div><div class="sub">Di atas kapal @ feri — pengalaman sebenar industri</div></div></div>
            <div class="p-highlight">🎓 Semua 4 sijil STCW + pengalaman praktikal penuh</div>
          </div>
          <div class="p-foot"><button class="btn-blue" onclick="pilihPakej('Pakej 1 — Lengkap', 3500)">Pilih Pakej Ini →</button></div>
        </div>

        <div class="p-box feat">
          <div class="p-head">
            <div class="p-badge">⭐ Popular</div>
            <div class="p-num">Pakej 02 — Asas</div>
            <h3>Pakej Asas</h3>
            <div class="p-price">Mulai dari <strong>RM 2,800</strong></div>
          </div>
          <div class="p-body">
            <div class="p-feat"><span class="ck">✓</span><div><div>Basic Training (BT)</div><div class="sub">Latihan asas keselamatan dan survival di laut</div></div></div>
            <div class="p-feat"><span class="ck">✓</span><div><div>Designated Security Duties (DSD)</div><div class="sub">Latihan tugas keselamatan kapal ISPS Code</div></div></div>
            <div class="p-feat"><span class="ck">✓</span><div><div>BTOCT (Tanker)</div><div class="sub">Latihan asas kapal tangki minyak / kimia</div></div></div>
            <div class="p-feat"><span class="cx">✗</span><div style="color:#bbb"><div>Crowd Management</div><div class="sub">Tidak termasuk dalam pakej ini</div></div></div>
            <div class="p-feat"><span class="cx">✗</span><div style="color:#bbb"><div>Penempatan Praktikal</div><div class="sub">Tidak termasuk — boleh ditambah kemudian</div></div></div>
            <div class="p-highlight" style="background:#fff8e7;color:#7a5000;">💰 Sesuai untuk bermula — jimat kos awal</div>
          </div>
          <div class="p-foot"><button class="btn-blue" style="background:linear-gradient(90deg,#7a5000,var(--gold));border:none" onclick="pilihPakej('Pakej 2 — Asas', 2800)">Pilih Pakej Ini →</button></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- BOOKING -->
<section id="booking">
  <div class="section-inner">
    <div class="bk-layout">
      <div class="fade-up">
        <div class="sec-label">Pendaftaran</div>
        <h2 class="sec-title">Daftar <span class="blue">Program</span></h2>
        <p class="sec-sub">Isi borang untuk menempah tempat anda. Tempat adalah terhad setiap sesi.</p>
        <div class="bk-steps">
          <div class="bk-step"><div class="bk-num">1</div><div><h4>Isi Borang Pendaftaran</h4><p>Lengkapkan semua maklumat peribadi dan pilih pakej yang diminati.</p></div></div>
          <div class="bk-step"><div class="bk-num">2</div><div><h4>Sediakan Dokumen Fasa 1</h4><p>Marine Medical Check Up dan Seaman Card mesti sedia sebelum kursus.</p></div></div>
          <div class="bk-step"><div class="bk-num">3</div><div><h4>Bayar Deposit</h4><p>Bayar deposit untuk mengesahkan tempahan anda dalam sistem.</p></div></div>
          <div class="bk-step"><div class="bk-num">4</div><div><h4>Mula Latihan</h4><p>Terima pengesahan dan sertai program pada tarikh ditetapkan.</p></div></div>
        </div>
      </div>

      <div class="form-card fade-up">
        <div class="fc-title">Borang Pendaftaran</div>
        <div class="fc-sub">Sila lengkapkan semua maklumat di bawah dengan tepat.</div>
        <div class="success-box" id="bk-ok">✅ Pendaftaran berjaya dihantar! Kami akan menghubungi anda dalam masa 1-2 hari bekerja.</div>
        <div class="f-row">
          <div class="f-g"><label>Nama Penuh</label><input type="text" id="b-nama" placeholder="Ahmad bin Ali"></div>
          <div class="f-g"><label>No. KP / Pasport</label><input type="text" placeholder="XXXXXX-XX-XXXX"></div>
        </div>
        <div class="f-row">
          <div class="f-g"><label>No. Telefon</label><input type="tel" placeholder="01X-XXXXXXXX"></div>
          <div class="f-g"><label>E-mel</label><input type="email" placeholder="nama@email.com"></div>
        </div>
        <div class="f-g"><label>Universiti / Institusi</label><input type="text" placeholder="e.g. UiTM Shah Alam, Politeknik, dll."></div>
        <div class="f-row">
          <div class="f-g">
            <label>Pilihan Pakej</label>
            <select>
              <option value="">-- Pilih Pakej --</option>
              <option>Fasa 1 Sahaja</option>
              <option>Fasa 2 — Pakej 1 Lengkap (RM 3,500)</option>
              <option>Fasa 2 — Pakej 2 Asas (RM 2,800)</option>
              <option>Fasa 1 + Pakej 1</option>
              <option>Fasa 1 + Pakej 2</option>
            </select>
          </div>
          <div class="f-g"><label>Tarikh Mula Pilihan</label><input type="date"></div>
        </div>
        <div class="f-g"><label>Maklumat Tambahan</label><textarea rows="3" placeholder="Soalan, keperluan khas, atau maklumat lain..."></textarea></div>
        <div style="display:flex;align-items:center;gap:0.75rem;margin-bottom:1.2rem">
          <input type="checkbox" id="b-agree" style="width:16px;height:16px;accent-color:var(--blue-dark)">
          <label for="b-agree" style="font-size:0.8rem;color:var(--text-muted);cursor:pointer">Saya bersetuju dengan <a href="#" style="color:var(--blue-bright)">terma &amp; syarat</a> program CTR.</label>
        </div>
        <button class="btn-blue" onclick="submitBk()">Hantar Pendaftaran →</button>
      </div>
    </div>
  </div>
</section>

<!-- PAYMENT -->
<section id="payment">
  <div class="section-inner">
    <div class="fade-up">
      <div class="sec-label">Bayaran</div>
      <h2 class="sec-title">Pilihan <span class="blue">Pembayaran</span></h2>
      <p class="sec-sub">Pilih kaedah pembayaran yang paling sesuai untuk anda.</p>
    </div>

    <div class="pay-methods fade-up">
      <div class="pay-m active" onclick="selPay(this,'FPX / Online Banking')">
        <div class="pay-m-icon">🏦</div>
        <div><h4>FPX / Online Banking</h4><p>Maybank2u, CIMB Clicks, RHB, Hong Leong dan lain-lain.</p></div>
        <div class="pay-chk">✓</div>
      </div>
      <div class="pay-m" onclick="selPay(this,'Kad Kredit / Debit')">
        <div class="pay-m-icon">💳</div>
        <div><h4>Kad Kredit / Debit</h4><p>Visa, Mastercard & American Express diterima.</p></div>
        <div class="pay-chk">✓</div>
      </div>
      <div class="pay-m" onclick="selPay(this,'DuitNow / QR')">
        <div class="pay-m-icon">📱</div>
        <div><h4>DuitNow / QR</h4><p>Imbas QR dan bayar melalui aplikasi bank anda.</p></div>
        <div class="pay-chk">✓</div>
      </div>
      <div class="pay-m" onclick="selPay(this,'PTPK / MARA / Biasiswa')">
        <div class="pay-m-icon">🎓</div>
        <div><h4>PTPK / MARA / Biasiswa</h4><p>Program diiktiraf untuk pinjaman & biasiswa kerajaan.</p></div>
        <div class="pay-chk">✓</div>
      </div>
    </div>

    <div class="pay-bottom fade-up">
      <div class="pay-sum">
        <div class="pay-sum-head">Ringkasan Bayaran</div>
        <div class="pay-sum-body">
          <div class="pay-r"><span class="l">Program Dipilih</span><span class="v" id="pp-prog">—</span></div>
          <div class="pay-r"><span class="l">Kaedah Bayaran</span><span class="v" id="pp-meth">FPX / Online Banking</span></div>
          <div class="pay-r"><span class="l">Harga Penuh</span><span class="v" id="pp-full">—</span></div>
          <div class="pay-r"><span class="l">Deposit (30%)</span><span class="v" id="pp-dep">—</span></div>
          <div class="pay-r tot"><span class="l">Bayar Hari Ini</span><span class="v" id="pp-tot">—</span></div>
        </div>
      </div>

      <div class="pay-form">
        <div class="fc-title" style="font-size:1.4rem;margin-bottom:0.3rem">Maklumat Bayaran</div>
        <div class="fc-sub" style="margin-bottom:1.5rem">Sila lengkapkan maklumat untuk proses bayaran.</div>
        <div class="f-g"><label>Nama Penuh</label><input type="text" placeholder="Nama seperti dalam kad / bank"></div>
        <div class="f-g"><label>No. Telefon</label><input type="tel" placeholder="01X-XXXXXXXX"></div>
        <div id="card-fields" style="display:none">
          <div class="f-g"><label>Nombor Kad</label><input type="text" placeholder="XXXX XXXX XXXX XXXX" maxlength="19" oninput="fmtCard(this)"></div>
          <div class="f-row">
            <div class="f-g"><label>Tarikh Luput</label><input type="text" placeholder="MM/YY" maxlength="5"></div>
            <div class="f-g"><label>CVV</label><input type="text" placeholder="XXX" maxlength="3"></div>
          </div>
        </div>
        <button class="btn-blue" onclick="submitPay()">Bayar Sekarang →</button>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div class="footer-grid">
      <div class="footer-brand">
        <div class="f-logo">C<span>T</span>R</div>
        <p>Central Tech Resources — Pusat latihan maritim bertauliah yang komited melahirkan pelaut profesional Malaysia bertaraf antarabangsa.</p>
        <div class="f-contact">
          <div>📞 013-8047141 / 09-5729971</div>
          <div>🌐 www.centraltech.com.my</div>
          <div>📍 A31, Tingkat 1, IM 5/2, Jalan Persiaran Sultan Abu Bakar, Indera Mahkota, 25200 Kuantan, Pahang</div>
        </div>
      </div>
      <div class="footer-col">
        <h4>Program</h4>
        <a href="#fasa">Fasa 1</a>
        <a href="#fasa">Fasa 2 — Pakej 1</a>
        <a href="#fasa">Fasa 2 — Pakej 2</a>
        <a href="#syarat">Syarat Kelayakan</a>
      </div>
      <div class="footer-col">
        <h4>Pautan</h4>
        <a href="#booking">Daftar Sekarang</a>
        <a href="#payment">Bayaran</a>
        <a href="#" onclick="openM('login')">Log Masuk</a>
        <a href="#" onclick="openM('register')">Buka Akaun</a>
      </div>
      <div class="footer-col">
        <h4>Sokongan</h4>
        <a href="#">FAQ</a>
        <a href="#">Hubungi Kami</a>
        <a href="#">Dasar Privasi</a>
        <a href="#">Terma & Syarat</a>
      </div>
    </div>
    <div class="footer-btm">
      <span>© 2024 Central Tech Resources Sdn. Bhd. Hak cipta terpelihara.</span>
      <span class="uitm-tag">🎓 UiTM Student Project</span>
    </div>
  </div>
</footer>

<!-- LOGIN MODAL -->
<div class="overlay" id="m-login">
  <div class="modal">
    <button class="m-close" onclick="closeM('login')">✕</button>
    <div class="m-logo-wrap">
      <div class="m-logo-box">CTR</div>
      <div>
        <div class="m-logo-text">C<span>T</span>R</div>
        <div style="font-size:0.65rem;color:var(--text-muted);font-weight:700;letter-spacing:1px;text-transform:uppercase">Program Pelaut Malaysia</div>
      </div>
    </div>
    <h2>Log Masuk</h2>
    <div class="f-g"><label>E-mel / No. KP</label><input type="text" placeholder="nama@email.com"></div>
    <div class="f-g"><label>Kata Laluan</label><input type="password" placeholder="••••••••"></div>
    <div style="text-align:right;margin-bottom:1.5rem"><a href="#" style="font-size:0.8rem;color:var(--blue-bright);font-weight:700">Lupa kata laluan?</a></div>
    <button class="btn-blue" onclick="doLogin()">Log Masuk →</button>
    <div class="m-footer">Belum ada akaun? <a onclick="switchM('login','register')">Daftar sekarang</a></div>
  </div>
</div>

<!-- REGISTER MODAL -->
<div class="overlay" id="m-register">
  <div class="modal" style="max-width:500px">
    <button class="m-close" onclick="closeM('register')">✕</button>
    <div class="m-logo-wrap">
      <div class="m-logo-box">CTR</div>
      <div>
        <div class="m-logo-text">C<span>T</span>R</div>
        <div style="font-size:0.65rem;color:var(--text-muted);font-weight:700;letter-spacing:1px;text-transform:uppercase">Program Pelaut Malaysia</div>
      </div>
    </div>
    <h2>Buka Akaun</h2>
    <div class="f-row">
      <div class="f-g"><label>Nama Penuh</label><input type="text" placeholder="Ahmad bin Ali"></div>
      <div class="f-g"><label>No. KP</label><input type="text" placeholder="XXXXXX-XX-XXXX"></div>
    </div>
    <div class="f-g"><label>E-mel</label><input type="email" placeholder="nama@email.com"></div>
    <div class="f-g"><label>No. Telefon</label><input type="tel" placeholder="01X-XXXXXXXX"></div>
    <div class="f-g"><label>Universiti / Institusi</label><input type="text" placeholder="e.g. UiTM Shah Alam"></div>
    <div class="f-row">
      <div class="f-g"><label>Kata Laluan</label><input type="password" placeholder="Min. 8 aksara"></div>
      <div class="f-g"><label>Sahkan Kata Laluan</label><input type="password" placeholder="Ulang kata laluan"></div>
    </div>
    <div style="display:flex;align-items:flex-start;gap:0.7rem;margin-bottom:1.5rem">
      <input type="checkbox" style="width:14px;height:14px;accent-color:var(--blue-dark);margin-top:3px;flex-shrink:0">
      <span style="font-size:0.78rem;color:var(--text-muted)">Saya bersetuju dengan <a href="#" style="color:var(--blue-bright)">Terma & Syarat</a> dan <a href="#" style="color:var(--blue-bright)">Dasar Privasi</a> CTR.</span>
    </div>
    <button class="btn-blue" onclick="doRegister()">Cipta Akaun →</button>
    <div class="m-footer">Sudah ada akaun? <a onclick="switchM('register','login')">Log masuk di sini</a></div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
  function openM(t){ document.getElementById('m-'+t).classList.add('open'); document.body.style.overflow='hidden'; }
  function closeM(t){ document.getElementById('m-'+t).classList.remove('open'); document.body.style.overflow=''; }
  function switchM(a,b){ closeM(a); setTimeout(()=>openM(b),200); }
  document.querySelectorAll('.overlay').forEach(o=>o.addEventListener('click',e=>{ if(e.target===o){o.classList.remove('open');document.body.style.overflow='';} }));

  function toast(msg){ const t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show'); setTimeout(()=>t.classList.remove('show'),3500); }
  function doLogin(){ closeM('login'); toast('✓ Berjaya log masuk! Selamat datang kembali.'); }
  function doRegister(){ closeM('register'); toast('✓ Akaun berjaya dicipta! Semak e-mel untuk pengesahan.'); }

  function switchFasa(i){
    document.querySelectorAll('.f-tab').forEach((t,idx)=>t.classList.toggle('active',idx===i));
    document.querySelectorAll('.f-panel').forEach((p,idx)=>p.classList.toggle('active',idx===i));
  }

  function pilihPakej(name, amt){
    document.getElementById('pp-prog').textContent=name;
    document.getElementById('pp-full').textContent='RM '+amt.toLocaleString();
    const dep=Math.round(amt*0.3);
    document.getElementById('pp-dep').textContent='RM '+dep.toLocaleString();
    document.getElementById('pp-tot').textContent='RM '+dep.toLocaleString();
    toast('✓ '+name+' dipilih!');
    setTimeout(()=>document.getElementById('payment').scrollIntoView({behavior:'smooth'}),700);
  }

  function selPay(el,method){
    document.querySelectorAll('.pay-m').forEach(m=>m.classList.remove('active'));
    el.classList.add('active');
    document.getElementById('pp-meth').textContent=method;
    document.getElementById('card-fields').style.display=method==='Kad Kredit / Debit'?'block':'none';
  }

  function submitBk(){
    const nama=document.getElementById('b-nama').value;
    const agree=document.getElementById('b-agree').checked;
    if(!nama){ toast('⚠ Sila masukkan nama penuh anda.'); return; }
    if(!agree){ toast('⚠ Sila bersetuju dengan terma & syarat.'); return; }
    document.getElementById('bk-ok').style.display='block';
    toast('✓ Pendaftaran dihantar berjaya!');
    setTimeout(()=>document.getElementById('payment').scrollIntoView({behavior:'smooth'}),1200);
  }

  function submitPay(){
    const total=document.getElementById('pp-tot').textContent;
    if(total==='—'){ toast('⚠ Sila pilih pakej program terlebih dahulu.'); return; }
    toast('✓ Pembayaran '+total+' sedang diproses...');
  }

  function fmtCard(el){ let v=el.value.replace(/\D/g,'').slice(0,16); el.value=v.replace(/(.{4})/g,'$1 ').trim(); }

  const obs=new IntersectionObserver(entries=>entries.forEach(e=>{ if(e.isIntersecting){e.target.classList.add('vis');obs.unobserve(e.target);} }),{threshold:0.1});
  document.querySelectorAll('.fade-up').forEach(el=>obs.observe(el));
</script>
</body>
</html>

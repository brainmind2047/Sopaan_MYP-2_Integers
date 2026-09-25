<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Integers</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}

  .theory{display:flex;flex-direction:column;gap:16px;padding-bottom:40px;}
  .hub{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .hub{grid-template-columns:repeat(3,1fr);} }
  .hub-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:16px;display:flex;flex-direction:column;gap:8px;}
  .hub-card h3{font-family:'Fraunces',serif;font-size:18px;margin:0;color:var(--accent-text);}
  .hub-card p{margin:0;font-size:14px;color:var(--ink-soft);line-height:1.5;}
  .hub-btns{display:flex;flex-wrap:wrap;gap:8px;margin-top:auto;}
  .hub-btn{min-height:40px;border:1.5px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:10px;padding:8px 12px;font:600 14px 'Source Sans 3',sans-serif;cursor:pointer;text-align:left;}
  .hub-btn:hover{border-color:var(--gold);}
  .hub-btn.primary{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .note{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:18px;scroll-margin-top:120px;}
  .note h2{font-family:'Fraunces',serif;font-size:22px;margin:0 0 4px;color:var(--ink);}
  .note .lt{font-size:13.5px;color:var(--ink-soft);margin:0 0 12px;}
  .note .lt b{color:var(--accent-text);}
  .note h4{font:700 15px 'Source Sans 3',sans-serif;margin:16px 0 6px;color:var(--accent-text);}
  .note p,.note li{font-size:15.5px;line-height:1.6;}
  .note ul{padding-left:20px;margin:6px 0;}
  .keybox{background:var(--gold-soft);border-left:4px solid var(--gold);border-radius:8px;padding:10px 12px;margin:10px 0;font-size:15px;line-height:1.6;}
  .keybox b{color:var(--ink);}
  .ex{background:var(--paper-2);border-radius:10px;padding:12px;margin:10px 0;}
  .ex .exh{font-family:'Fraunces',serif;font-weight:700;color:var(--accent-text);margin-bottom:4px;}
  .ex .exl{font-size:15px;line-height:1.7;}
  .ttab{width:100%;border-collapse:collapse;font-size:14.5px;margin:8px 0;}
  .ttab th,.ttab td{border:1px solid var(--rule);padding:7px 8px;text-align:left;vertical-align:top;}
  .ttab th{background:var(--paper-2);}
  .tscroll{overflow-x:auto;}
  .mono{font-family:'IBM Plex Mono',monospace;font-size:.92em;}
  @media (max-width:480px){ .ttab{font-size:13.5px;} .ttab th,.ttab td{padding:6px;} }
  .note .figsvg{max-width:100%;height:auto;display:block;margin:8px auto;}


  .rep-top{display:flex;flex-wrap:wrap;gap:18px;align-items:center;justify-content:center;margin-top:8px;}
  .rep-legend{flex:1;min-width:220px;display:flex;flex-direction:column;gap:8px;}
  .rep-cap{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);text-transform:uppercase;letter-spacing:.05em;}
  .rep-li{display:flex;align-items:center;gap:6px;font-size:15px;}
  .rep-n{margin-left:auto;white-space:nowrap;padding-left:8px;font-family:'IBM Plex Mono',monospace;font-weight:600;}
  .sw{display:inline-block;width:12px;height:12px;border-radius:3px;flex:none;}
  .rep-grid{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .rep-grid{grid-template-columns:1fr 1fr;} }
  .rep-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:14px;display:flex;flex-direction:column;gap:10px;}
  .rep-h{display:flex;align-items:center;gap:8px;font:700 16px 'Source Sans 3',sans-serif;}
  .crit{display:inline-grid;place-items:center;width:28px;height:28px;border-radius:50%;color:var(--card);font:700 15px Fraunces,serif;flex:none;}
  .rep-row{display:flex;gap:14px;align-items:center;}
  .rep-stats{display:flex;flex-direction:column;gap:5px;font-size:14.5px;}
  .rep-stats div{display:flex;align-items:center;gap:6px;}
  .rep-lvl{margin-top:4px;color:var(--accent-text);} .rep-lvl span{color:var(--ink-soft);font-size:13px;}
  .rep-note{font-size:13px;color:var(--ink-soft);}


  .skip-chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:12px 0;}
  .skip-chips .chip{min-width:48px;min-height:40px;cursor:pointer;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--retry-text);border-radius:10px;font:600 14px 'IBM Plex Mono',monospace;}
  .skip-btns{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-top:12px;}

</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest">BM</div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">MYP Mathematics 2 · Unit 3</div>
  <div class="chapter-title">Integers</div>
  <div class="chapter-sub">Theory Notes · Objective-wise Practice · Criterion Tests A–D</div><div class="chapter-credit">Follows the unit structure of MYP Mathematics 2 (Oxford), Unit 3</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series · MYP Mathematics 2 · Unit 3<br>Unit objectives and structure follow <i>MYP Mathematics 2: A concept-based approach</i> (Oxford University Press), Unit 3. Theory notes, questions, tests and worked solutions are written by Brain &amp; Mind Academy.</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).toLowerCase().replace(/\s+/g,'').replace(/^[a-z]\(x\)=/i,'').replace(/^y=/i,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/⁴/g,'^4').replace(/⁵/g,'^5').replace(/⁶/g,'^6').replace(/⁷/g,'^7').replace(/⁸/g,'^8').replace(/⁹/g,'^9').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[], absDepth=0;
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if(ch==='|'){ var pv=toks[toks.length-1]; var opn=(absDepth===0)||!pv||('+-*/^(['.indexOf(pv.k)>=0); if(opn){ absDepth++; toks.push({k:'['}); } else { absDepth--; toks.push({k:']'}); } i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')'||b.k===']') && (a.k==='n'||a.k==='v'||a.k==='('||a.k==='[')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    if(t.k==='['){ var m=parseE(); if(!peek()||peek().k!==']') throw 0; p++; return function(e){ return Math.abs(m(e)); }; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(\d+)(?: |\+|-)(\d+)\/(\d+)$/))){ if(+m[3]===0) return null; return {v:+m[1]+m[2]/m[3],form:'mixed',w:+m[1],n:+m[2],d:+m[3]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ if(/\d/.test(a)) return norm(a)===norm(input); var w=wordsNorm(a); return w!=='' && w===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).replace(/[−–—]/g,'-').match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    var alt=String(input).replace(/\/\s*(\d+(?:\.\d+)?)\s*([a-zA-Z(])/g,'/$1*$2'); if(alt!==String(input) && exprEqual(alt,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null){ if(Math.abs(n1-n2)<1e-3) return true; return (accept||[]).some(function(a){ var n3=parseNum(a); return n3!==null && Math.abs(n1-n3)<1e-3; }); }
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var THEORY = "<div class=\"hub\"><div class=\"hub-card\"><h3>📖 Theory notes</h3><p>Explained notes for each part of the unit, with rules, diagrams and worked examples.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-jump=\"n31\">3.1 notes</button><button class=\"hub-btn\" data-jump=\"n32\">3.2 notes</button><button class=\"hub-btn\" data-jump=\"n33\">3.3 notes</button><button class=\"hub-btn\" data-jump=\"n34\">3.4 notes</button><button class=\"hub-btn\" data-jump=\"n35\">3.5 notes</button><button class=\"hub-btn\" data-jump=\"n36\">3.6 notes</button></div></div><div class=\"hub-card\"><h3>🎯 Objective-wise practice</h3><p>One practice sheet for each unit objective: multiple-choice questions first, then step-by-step fill-in-the-blanks.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s1\">3.1 · Integers: comparing and ordering</button><button class=\"hub-btn\" data-go=\"s2\">3.2 · Absolute value</button><button class=\"hub-btn\" data-go=\"s3\">3.3 · The Cartesian plane</button><button class=\"hub-btn\" data-go=\"s4\">3.4 · Multiplying and dividing integers</button><button class=\"hub-btn\" data-go=\"s5\">3.5 · Adding and subtracting integers</button><button class=\"hub-btn\" data-go=\"s6\">3.6 · Order of operations and problem solving</button></div></div><div class=\"hub-card\"><h3>📝 Chapter test</h3><p>Four tests, one for each MYP criterion. Take them in Quiz mode, then open the report to see your results as pie charts.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s7\">Test A · Knowing and understanding</button><button class=\"hub-btn\" data-go=\"s8\">Test B · Investigating patterns</button><button class=\"hub-btn\" data-go=\"s9\">Test C · Communicating</button><button class=\"hub-btn\" data-go=\"s10\">Test D · Applying mathematics in real-life contexts</button><button class=\"hub-btn primary\" data-go=\"report\">📊 View my report</button></div></div></div><section class=\"note\" id=\"nintro\"><h2>About this unit</h2><p><b>Key concept:</b> Form &nbsp;·&nbsp; <b>Related concepts:</b> Quantity, Representation &nbsp;·&nbsp; <b>Global context:</b> Orientation in space and time (human explorations).</p><p>Explorers climb mountains, dive to the ocean floor, cross frozen deserts and travel into space. To describe heights above and depths below sea level, temperatures above and below zero, and positions on a map, we need numbers with a direction: the <b>integers</b>.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Test</th><th>MYP criterion</th><th>What it checks</th></tr><tr><td>Test A</td><td>Knowing and understanding</td><td>Using the skills of the unit correctly in familiar and unfamiliar questions.</td></tr><tr><td>Test B</td><td>Investigating patterns</td><td>Finding the patterns behind the integer rules, stating them and testing them.</td></tr><tr><td>Test C</td><td>Communicating</td><td>Correct notation and vocabulary, clear working and choosing the clearest representation.</td></tr><tr><td>Test D</td><td>Applying mathematics in real-life contexts</td><td>Using integers to describe and solve real situations and judging whether answers make sense.</td></tr></table></div></section><section class=\"note\" id=\"n31\"><h2>3.1 Integers: comparing and ordering</h2><p class=\"lt\"><b>Objective:</b> Define integers, and compare and order integers using a number line.</p><h4>What is an integer?</h4><p>The <b>integers</b> are the whole numbers, their opposites and zero: …, −3, −2, −1, 0, 1, 2, 3, … &nbsp;Fractions and decimals such as <span class=\"fq\"><span>1</span><span>2</span></span> or −4.7 are <b>not</b> integers. Zero is neither positive nor negative.</p><p>Every integer has an <b>opposite</b>: the number the same distance from 0 on the other side. The opposite of 6 is −6 (read “negative six”), and the opposite of −6 is 6. A positive number can be written with or without its sign: +6 = 6.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Situation</th><th>Positive</th><th>Negative</th></tr><tr><td>height and depth</td><td>above sea level: +850 m</td><td>below sea level: −60 m</td></tr><tr><td>temperature</td><td>above zero: 12 °C</td><td>below zero: −12 °C</td></tr><tr><td>money</td><td>profit or deposit: +₹500</td><td>loss or withdrawal: −₹500</td></tr><tr><td>building floors</td><td>floor 3</td><td>basement level 2: −2</td></tr></table></div><h4>Comparing on a number line</h4><p>On a horizontal number line, numbers <b>increase to the right</b>. The number further right is greater. On a vertical number line (like a thermometer), numbers increase upwards.</p><svg class=\"figsvg\" viewBox=\"0 0 330 56\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"8.0\" y1=\"24.0\" x2=\"322.0\" y2=\"24.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"16.0\" y1=\"19\" x2=\"16.0\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"16.0\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−8</text><line x1=\"37.3\" y1=\"19\" x2=\"37.3\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"37.3\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−7</text><line x1=\"58.6\" y1=\"19\" x2=\"58.6\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"58.6\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−6</text><line x1=\"79.9\" y1=\"19\" x2=\"79.9\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"79.9\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><line x1=\"101.1\" y1=\"19\" x2=\"101.1\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"101.1\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><line x1=\"122.4\" y1=\"19\" x2=\"122.4\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"122.4\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><line x1=\"143.7\" y1=\"19\" x2=\"143.7\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"143.7\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><line x1=\"165.0\" y1=\"19\" x2=\"165.0\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"165.0\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"186.3\" y1=\"19\" x2=\"186.3\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"186.3\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"207.6\" y1=\"19\" x2=\"207.6\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"207.6\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"228.9\" y1=\"19\" x2=\"228.9\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"228.9\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"250.1\" y1=\"19\" x2=\"250.1\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"250.1\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line x1=\"271.4\" y1=\"19\" x2=\"271.4\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"271.4\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><line x1=\"292.7\" y1=\"19\" x2=\"292.7\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"292.7\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><line x1=\"314.0\" y1=\"19\" x2=\"314.0\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"314.0\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><circle cx=\"58.6\" cy=\"24\" r=\"4.2\" style=\"fill:var(--accent-text)\"/><text class=\"al\" x=\"58.6\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">A</text><circle cx=\"165.0\" cy=\"24\" r=\"4.2\" style=\"fill:var(--accent-text)\"/><text class=\"al\" x=\"165.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">B</text><circle cx=\"271.4\" cy=\"24\" r=\"4.2\" style=\"fill:var(--accent-text)\"/><text class=\"al\" x=\"271.4\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">C</text></svg><p>On the line, A = −6, B = −1 and C = 4. So −6 &lt; −1 &lt; 4.</p><div class=\"keybox\"><b>For negative numbers, the bigger digit means the smaller number.</b> −9 is further left than −2, so −9 &lt; −2. Think of temperature: −9 °C is colder than −2 °C.</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Ordering</div><div class=\"exl\">Write in ascending order: −7, 3, −12, 0, 5, −1.<br>Negatives first, most negative first: −12, −7, −1; then 0; then positives.<br><b>−12, −7, −1, 0, 3, 5</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Writing integers</div><div class=\"exl\">Write each as an integer: a diver 45 m below sea level; a gain of 8 points; 3 floors below ground.<br><b>−45</b>, <b>+8</b>, <b>−3</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Comparing</div><div class=\"exl\">Insert &lt; or &gt;: −15 ▢ −9.<br>−15 is further left on the number line, so <b>−15 &lt; −9</b>.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s1\">Practise 3.1 →</button></div></section><section class=\"note\" id=\"n32\"><h2>3.2 Absolute value</h2><p class=\"lt\"><b>Objective:</b> Define and evaluate the absolute value of a number, and use it to compare sizes.</p><p>The <b>absolute value</b> of a number is its <b>distance from zero</b> on the number line. It is written with two vertical bars: |−4| is read “the absolute value of negative four”.</p><svg class=\"figsvg\" viewBox=\"0 0 330 74\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"8.0\" y1=\"42.0\" x2=\"322.0\" y2=\"42.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"16.0\" y1=\"37\" x2=\"16.0\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"16.0\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><line x1=\"45.8\" y1=\"37\" x2=\"45.8\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"45.8\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><line x1=\"75.6\" y1=\"37\" x2=\"75.6\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"75.6\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><line x1=\"105.4\" y1=\"37\" x2=\"105.4\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"105.4\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><line x1=\"135.2\" y1=\"37\" x2=\"135.2\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"135.2\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"165.0\" y1=\"37\" x2=\"165.0\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"165.0\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"194.8\" y1=\"37\" x2=\"194.8\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"194.8\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"224.6\" y1=\"37\" x2=\"224.6\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"224.6\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"254.4\" y1=\"37\" x2=\"254.4\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"254.4\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line x1=\"284.2\" y1=\"37\" x2=\"284.2\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"284.2\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><line x1=\"314.0\" y1=\"37\" x2=\"314.0\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"314.0\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><path d=\"M165.0,38 Q105.4,-22.0 45.8,38\" style=\"fill:none;stroke:var(--danger);stroke-width:1.8\" marker-end=\"url(#ah)\"/><text class=\"al\" x=\"105.4\" y=\"2.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4 units</text><path d=\"M165.0,38 Q224.6,-22.0 284.2,38\" style=\"fill:none;stroke:var(--danger);stroke-width:1.8\" marker-end=\"url(#ah)\"/><text class=\"al\" x=\"224.6\" y=\"2.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4 units</text><circle cx=\"45.8\" cy=\"42\" r=\"4.2\" style=\"fill:var(--accent-text)\"/><circle cx=\"284.2\" cy=\"42\" r=\"4.2\" style=\"fill:var(--accent-text)\"/></svg><p>Both −4 and 4 are 4 units from 0, so |−4| = 4 and |4| = 4. A number and its opposite always have the same absolute value.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Number</th><th>Distance from 0</th><th>Absolute value</th></tr><tr><td class=\"mono\">−23</td><td>23 units</td><td class=\"mono\">|−23| = 23</td></tr><tr><td class=\"mono\">15</td><td>15 units</td><td class=\"mono\">|15| = 15</td></tr><tr><td class=\"mono\">0</td><td>0 units</td><td class=\"mono\">|0| = 0</td></tr></table></div><div class=\"keybox\"><b>An absolute value is never negative</b>, because a distance cannot be negative. But be careful: −|6| means “the opposite of |6|”, which is −6.</div><h4>Why it is useful</h4><p>Absolute value measures <b>size</b> (magnitude) without direction. A submarine at −300 m is further from sea level than a plane at 250 m, because |−300| &gt; |250|.</p><div class=\"ex\"><div class=\"exh\">Worked example 1 · Evaluating</div><div class=\"exl\">Find |−18| + |7|.<br>|−18| = 18 and |7| = 7, so the answer is <b>25</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Comparing magnitudes</div><div class=\"exl\">Which is further from 0: −13 or 11?<br>|−13| = 13 and |11| = 11, so <b>−13</b> is further from 0, even though −13 &lt; 11.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Distance between two integers</div><div class=\"exl\">How far apart are −5 and 3 on the number line?<br>Count: from −5 to 0 is 5 units, from 0 to 3 is 3 units, total <b>8</b>.<br>This is the same as |3 − (−5)| = |8| = 8.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s2\">Practise 3.2 →</button></div></section><section class=\"note\" id=\"n33\"><h2>3.3 The Cartesian plane</h2><p class=\"lt\"><b>Objective:</b> Plot and read points in all four quadrants of the Cartesian plane.</p><p>The <b>Cartesian plane</b> (coordinate grid) is made from two number lines that cross at right angles at zero. The horizontal one is the <b>x-axis</b>, the vertical one is the <b>y-axis</b>, and the point where they cross is the <b>origin</b>, (0, 0).</p><p>A point is located with an <b>ordered pair</b> (x, y): first move along the x-axis (right +, left −), then along the y-axis (up +, down −).</p><svg class=\"figsvg\" style=\"max-width:300px\" viewBox=\"0 0 300 308\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line x1=\"14.0\" y1=\"286.0\" x2=\"14.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"36.7\" y1=\"286.0\" x2=\"36.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"59.3\" y1=\"286.0\" x2=\"59.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"82.0\" y1=\"286.0\" x2=\"82.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"104.7\" y1=\"286.0\" x2=\"104.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"127.3\" y1=\"286.0\" x2=\"127.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"150.0\" y1=\"286.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"172.7\" y1=\"286.0\" x2=\"172.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"195.3\" y1=\"286.0\" x2=\"195.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"218.0\" y1=\"286.0\" x2=\"218.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"240.7\" y1=\"286.0\" x2=\"240.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"263.3\" y1=\"286.0\" x2=\"263.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"286.0\" y1=\"286.0\" x2=\"286.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"286.0\" x2=\"286.0\" y2=\"286.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"263.3\" x2=\"286.0\" y2=\"263.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"240.7\" x2=\"286.0\" y2=\"240.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"218.0\" x2=\"286.0\" y2=\"218.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"195.3\" x2=\"286.0\" y2=\"195.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"172.7\" x2=\"286.0\" y2=\"172.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"150.0\" x2=\"286.0\" y2=\"150.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"127.3\" x2=\"286.0\" y2=\"127.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"104.7\" x2=\"286.0\" y2=\"104.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"82.0\" x2=\"286.0\" y2=\"82.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"59.3\" x2=\"286.0\" y2=\"59.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"36.7\" x2=\"286.0\" y2=\"36.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"14.0\" x2=\"286.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"150.0\" x2=\"286.0\" y2=\"150.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><line x1=\"150.0\" y1=\"286.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><text class=\"po\" x=\"14.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−6</text><text class=\"po\" x=\"36.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"59.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"82.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"104.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"127.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"172.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"195.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"218.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"240.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"263.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"286.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><text class=\"po\" x=\"146.0\" y=\"286.0\" text-anchor=\"end\" dominant-baseline=\"middle\">−6</text><text class=\"po\" x=\"146.0\" y=\"263.3\" text-anchor=\"end\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"146.0\" y=\"240.7\" text-anchor=\"end\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"146.0\" y=\"218.0\" text-anchor=\"end\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"146.0\" y=\"195.3\" text-anchor=\"end\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"146.0\" y=\"172.7\" text-anchor=\"end\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"146.0\" y=\"127.3\" text-anchor=\"end\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"146.0\" y=\"104.7\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"146.0\" y=\"82.0\" text-anchor=\"end\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"146.0\" y=\"59.3\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"146.0\" y=\"36.7\" text-anchor=\"end\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"146.0\" y=\"14.0\" text-anchor=\"end\" dominant-baseline=\"middle\">6</text><text class=\"po\" x=\"145.0\" y=\"159.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><text class=\"al\" x=\"284.0\" y=\"142.0\" text-anchor=\"end\" dominant-baseline=\"middle\">x</text><text class=\"al\" x=\"158.0\" y=\"18.0\" text-anchor=\"start\" dominant-baseline=\"middle\">y</text><text x=\"231.6\" y=\"41.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--gold);font:700 22px Fraunces,serif;opacity:.85\">I</text><text x=\"68.4\" y=\"41.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--gold);font:700 22px Fraunces,serif;opacity:.85\">II</text><text x=\"68.4\" y=\"258.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--gold);font:700 22px Fraunces,serif;opacity:.85\">III</text><text x=\"231.6\" y=\"258.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--gold);font:700 22px Fraunces,serif;opacity:.85\">IV</text><circle cx=\"218.0\" cy=\"104.7\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"224.0\" y=\"96.7\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">A</text><circle cx=\"59.3\" cy=\"127.3\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"65.3\" y=\"119.3\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">B</text><circle cx=\"104.7\" cy=\"218.0\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"110.7\" y=\"210.0\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">C</text><circle cx=\"263.3\" cy=\"240.7\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"269.3\" y=\"232.7\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">D</text></svg><p>A(3, 2), B(−4, 1), C(−2, −3), D(5, −4). The axes divide the plane into four <b>quadrants</b>, numbered I to IV anticlockwise starting from the top right.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Quadrant</th><th>x</th><th>y</th><th>Example</th></tr><tr><td>I</td><td>+</td><td>+</td><td class=\"mono\">(3, 2)</td></tr><tr><td>II</td><td>−</td><td>+</td><td class=\"mono\">(−4, 1)</td></tr><tr><td>III</td><td>−</td><td>−</td><td class=\"mono\">(−2, −3)</td></tr><tr><td>IV</td><td>+</td><td>−</td><td class=\"mono\">(5, −4)</td></tr></table></div><div class=\"keybox\"><b>Order matters: x first, then y.</b> (2, −5) and (−5, 2) are different points. A point with a 0 coordinate, such as (0, −3) or (6, 0), lies <b>on an axis</b> and is not in any quadrant.</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Plotting</div><div class=\"exl\">Plot P(−3, 4).<br>Start at the origin. Move 3 left (x = −3), then 4 up (y = 4). P is in quadrant II.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Distance along a grid line</div><div class=\"exl\">Find the distance from (−3, 2) to (4, 2).<br>The y-coordinates are equal, so the points lie on a horizontal line.<br>Distance = |4 − (−3)| = <b>7 units</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Completing a shape</div><div class=\"exl\">Three corners of a rectangle are (−2, 3), (4, 3) and (4, −1). Find the fourth.<br>It must line up with (−2, 3) vertically and with (4, −1) horizontally: <b>(−2, −1)</b>.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s3\">Practise 3.3 →</button></div></section><section class=\"note\" id=\"n34\"><h2>3.4 Multiplying and dividing integers</h2><p class=\"lt\"><b>Objective:</b> Multiply and divide integers, including several factors and powers of negative numbers.</p><h4>Discovering the rule from a pattern</h4><p>Look at 3 × 2 = 6, 3 × 1 = 3, 3 × 0 = 0. Each answer goes down by 3, so the pattern continues 3 × (−1) = −3, 3 × (−2) = −6. <b>Positive × negative is negative.</b></p><p>Now (−3) × 2 = −6, (−3) × 1 = −3, (−3) × 0 = 0. Each answer goes <b>up</b> by 3, so (−3) × (−1) = 3 and (−3) × (−2) = 6. <b>Negative × negative is positive.</b></p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Signs</th><th>Product or quotient</th><th>Examples</th></tr><tr><td>same signs (+ and +, or − and −)</td><td><b>positive</b></td><td class=\"mono\">(−6) × (−4) = 24, &nbsp;(−36) ÷ (−9) = 4</td></tr><tr><td>different signs</td><td><b>negative</b></td><td class=\"mono\">(−6) × 4 = −24, &nbsp;36 ÷ (−9) = −4</td></tr></table></div><p>Division is the inverse of multiplication, so it follows the same sign rules: because (−4) × (−9) = 36, we know 36 ÷ (−9) = −4.</p><h4>Several factors</h4><p>Count the negative factors. An <b>even</b> number of negatives gives a positive answer; an <b>odd</b> number gives a negative answer.</p><div class=\"ex\"><div class=\"exh\">Worked example 1 · Three negative factors</div><div class=\"exl\">(−2) × 5 × (−3) × (−1)<br>Three negative factors (odd), so the answer is negative.<br>2 × 5 × 3 × 1 = 30, so the answer is <b>−30</b>.</div></div><h4>Powers of negative numbers</h4><p>(−2)³ = (−2) × (−2) × (−2) = −8 (odd power: negative). (−2)⁴ = 16 (even power: positive).</p><div class=\"keybox\"><b>Watch the brackets.</b> (−3)² = (−3) × (−3) = 9, but −3² means −(3²) = −9. The power only applies to what is directly in front of it.</div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Division</div><div class=\"exl\">Find −84 ÷ 7 and −84 ÷ (−7).<br>84 ÷ 7 = 12. Different signs: <b>−12</b>. Same signs: <b>12</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · In context</div><div class=\"exl\">A diver descends 4 m every minute, a change of −4 m per minute. What is her change in depth after 9 minutes?<br>9 × (−4) = <b>−36 m</b>, so she is 36 m deeper.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s4\">Practise 3.4 →</button></div></section><section class=\"note\" id=\"n35\"><h2>3.5 Adding and subtracting integers</h2><p class=\"lt\"><b>Objective:</b> Add and subtract integers using number lines, tokens and rules.</p><h4>Model 1 · Moving on a number line</h4><p>Start at the first number. <b>Adding a positive</b> moves right (up); <b>adding a negative</b> moves left (down). Think of a hot-air balloon: adding hot air (+) lifts it, adding a sandbag (−) lowers it.</p><svg class=\"figsvg\" viewBox=\"0 0 330 74\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"8.0\" y1=\"42.0\" x2=\"322.0\" y2=\"42.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"16.0\" y1=\"37\" x2=\"16.0\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"16.0\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−6</text><line x1=\"40.8\" y1=\"37\" x2=\"40.8\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"40.8\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><line x1=\"65.7\" y1=\"37\" x2=\"65.7\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"65.7\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><line x1=\"90.5\" y1=\"37\" x2=\"90.5\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"90.5\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><line x1=\"115.3\" y1=\"37\" x2=\"115.3\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"115.3\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><line x1=\"140.2\" y1=\"37\" x2=\"140.2\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"140.2\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"165.0\" y1=\"37\" x2=\"165.0\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"165.0\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"189.8\" y1=\"37\" x2=\"189.8\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"189.8\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"214.7\" y1=\"37\" x2=\"214.7\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"214.7\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"239.5\" y1=\"37\" x2=\"239.5\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"239.5\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line x1=\"264.3\" y1=\"37\" x2=\"264.3\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"264.3\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><line x1=\"289.2\" y1=\"37\" x2=\"289.2\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"289.2\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><line x1=\"314.0\" y1=\"37\" x2=\"314.0\" y2=\"47\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"314.0\" y=\"57.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><path d=\"M115.3,38 Q177.4,-22.0 239.5,38\" style=\"fill:none;stroke:var(--danger);stroke-width:1.8\" marker-end=\"url(#ah)\"/><text class=\"al\" x=\"177.4\" y=\"2.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">+5</text><circle cx=\"115.3\" cy=\"42\" r=\"4.2\" style=\"fill:var(--accent-text)\"/><circle cx=\"239.5\" cy=\"42\" r=\"4.2\" style=\"fill:var(--accent-text)\"/></svg><p>−2 + 5: start at −2 and move 5 right to <b>3</b>.</p><h4>Model 2 · Tokens and zero pairs</h4><p>A + token and a − token cancel: (+1) + (−1) = 0, a <b>zero pair</b>. A number and its opposite are <b>additive inverses</b>: their sum is always 0.</p><svg class=\"figsvg\" style=\"max-width:300px\" viewBox=\"0 0 300 86\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><circle cx=\"24\" cy=\"24\" r=\"12\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"24.0\" y=\"24.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">+</text><circle cx=\"54\" cy=\"24\" r=\"12\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"54.0\" y=\"24.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">+</text><circle cx=\"84\" cy=\"24\" r=\"12\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"84.0\" y=\"24.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">+</text><circle cx=\"24\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"24\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"54\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"54\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"84\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"84\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"114\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"114\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"144\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"144\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><rect x=\"9\" y=\"8\" width=\"30\" height=\"68\" rx=\"14\" style=\"fill:none;stroke:var(--gold);stroke-width:2;stroke-dasharray:4 3\"/><rect x=\"39\" y=\"8\" width=\"30\" height=\"68\" rx=\"14\" style=\"fill:none;stroke:var(--gold);stroke-width:2;stroke-dasharray:4 3\"/><rect x=\"69\" y=\"8\" width=\"30\" height=\"68\" rx=\"14\" style=\"fill:none;stroke:var(--gold);stroke-width:2;stroke-dasharray:4 3\"/></svg><p>3 + (−5): make 3 zero pairs; 2 negative tokens are left, so 3 + (−5) = <b>−2</b>.</p><h4>Subtracting: add the opposite</h4><p>Subtracting a number gives the same result as adding its opposite. Removing a sandbag makes the balloon go <b>up</b>, just like adding hot air.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Calculation</th><th>Rewrite as addition</th><th>Answer</th></tr><tr><td class=\"mono\">7 − 10</td><td class=\"mono\">7 + (−10)</td><td class=\"mono\">−3</td></tr><tr><td class=\"mono\">−4 − 6</td><td class=\"mono\">−4 + (−6)</td><td class=\"mono\">−10</td></tr><tr><td class=\"mono\">5 − (−8)</td><td class=\"mono\">5 + 8</td><td class=\"mono\">13</td></tr><tr><td class=\"mono\">−9 − (−3)</td><td class=\"mono\">−9 + 3</td><td class=\"mono\">−6</td></tr></table></div><div class=\"keybox\"><b>Two signs next to each other:</b> + (−) and − (+) both mean “go down” (−); − (−) and + (+) both mean “go up” (+). So 6 + (−2) = 6 − 2 and 6 − (−2) = 6 + 2.</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Temperature change</div><div class=\"exl\">At 5 a.m. in Leh it was −9 °C. By noon it had risen 14 °C.<br>−9 + 14 = <b>5 °C</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Difference</div><div class=\"exl\">Find the difference between 42 °C and −17 °C.<br>42 − (−17) = 42 + 17 = <b>59 °C</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Adding two negatives</div><div class=\"exl\">A trekker’s bank balance is −₹300 (overdrawn). She withdraws another ₹450.<br>−300 + (−450) = <b>−₹750</b>.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s5\">Practise 3.5 →</button></div></section><section class=\"note\" id=\"n36\"><h2>3.6 Order of operations and problem solving</h2><p class=\"lt\"><b>Objective:</b> Apply the order of operations with integers and solve real-life problems involving integers.</p><p>Integer calculations follow the same order of operations as other numbers:</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Order</th><th>Operation</th></tr><tr><td>1</td><td><b>B</b>rackets (and anything above or below a fraction bar)</td></tr><tr><td>2</td><td><b>E</b>xponents (powers)</td></tr><tr><td>3</td><td><b>D</b>ivision and <b>M</b>ultiplication, from left to right</td></tr><tr><td>4</td><td><b>A</b>ddition and <b>S</b>ubtraction, from left to right</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Multiply before adding</div><div class=\"exl\">−5 + 3 × (−4)<br>Multiply first: 3 × (−4) = −12.<br>−5 + (−12) = <b>−17</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Brackets and powers</div><div class=\"exl\">(−6 − 2)² ÷ (−4)<br>Brackets: −6 − 2 = −8. Power: (−8)² = 64.<br>64 ÷ (−4) = <b>−16</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · A fraction bar</div><div class=\"exl\">Evaluate (−20 + 2) ÷ (5 − 8), written as a fraction with −20 + 2 on top and 5 − 8 below.<br>Top: −18. Bottom: −3.<br>−18 ÷ (−3) = <b>6</b>.</div></div><div class=\"keybox\"><b>Show each step on a new line</b> and keep negative numbers in brackets when they follow an operation sign: write 4 × (−3), not 4 × −3.</div><h4>Problem solving</h4><p>Turn the story into one expression, then use the order of operations. Choose a sign for each direction (up/down, gain/loss) and stay consistent.</p><div class=\"ex\"><div class=\"exh\">Worked example 4 · A diving submersible</div><div class=\"exl\">A submersible starts 20 m below sea level and descends 45 m per minute for 6 minutes.<br>Depth = −20 + 6 × (−45) = −20 + (−270) = <b>−290 m</b>, i.e. 290 m below sea level.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s6\">Practise 3.6 →</button></div></section><section class=\"note\" id=\"nsum\"><h2>Unit checklist</h2><ul><li>I can recognise integers, write opposites and use integers to describe real situations.</li><li>I can compare and order integers using a number line and the symbols &lt; and &gt;.</li><li>I can find absolute values and use them to compare distances from zero.</li><li>I can plot and read points in all four quadrants and name the quadrant.</li><li>I can multiply and divide integers, including several factors and powers of negatives.</li><li>I can add and subtract integers with a number line, tokens or the “add the opposite” rule.</li><li>I can use the order of operations with integers and solve multi-step problems.</li></ul><div class=\"hub-btns\" style=\"margin-top:10px\"><button class=\"hub-btn\" data-go=\"s7\">Test A</button><button class=\"hub-btn\" data-go=\"s8\">Test B</button><button class=\"hub-btn\" data-go=\"s9\">Test C</button><button class=\"hub-btn\" data-go=\"s10\">Test D</button><button class=\"hub-btn primary\" data-go=\"report\">📊 Report</button></div></section>";
var REPORT = [["s7", "A", "Knowing and understanding"], ["s8", "B", "Investigating patterns"], ["s9", "C", "Communicating"], ["s10", "D", "Applying mathematics in real-life contexts"]];
var SECTIONS = [{"id": "s1", "label": "3.1 Integers", "sub": "Integers — define, compare and order integers", "slides": [{"kind": "mcq", "text": "Which of these is NOT an integer?", "opts": ["−8", "0", "4.5", "312"], "correct": 2, "tag": "", "sol": "Integers are whole numbers, their opposites and zero. 4.5 is a decimal."}, {"kind": "mcq", "text": "What is the opposite of −14?", "opts": ["−14", "14", "{1/14}", "0"], "correct": 1, "tag": "", "sol": "The opposite is the same distance from 0 on the other side: 14."}, {"kind": "mcq", "text": "Which statement is true?", "opts": ["−6 < −2", "−2 < −6", "−6 > −2", "0 < −1"], "correct": 0, "tag": "", "sol": "−6 is further left on the number line than −2, so −6 is smaller."}, {"kind": "mcq", "text": "Which list is in ascending order?", "opts": ["−9, −4, 0, 2", "0, −4, −9, 2", "2, 0, −4, −9", "−4, −9, 0, 2"], "correct": 0, "tag": "", "sol": "Ascending means smallest first: the most negative number comes first."}, {"kind": "mcq", "text": "Which is the greatest?", "opts": ["−20", "−11", "−7", "−3"], "correct": 3, "tag": "", "sol": "−3 is closest to 0 and furthest right on the number line."}, {"kind": "mcq", "text": "A car park is two floors below ground level. Which integer describes it?", "opts": ["−20", "0", "2", "−2"], "correct": 3, "tag": "", "sol": "Below ground level is negative: −2."}, {"kind": "mcq", "text": "One winter night Leh was −12 °C, Shimla −3 °C and Delhi 8 °C. Which was coldest?", "opts": ["Shimla", "Leh", "Shimla and Leh were equal", "Delhi"], "correct": 1, "tag": "", "sol": "−12 is the smallest of the three temperatures."}, {"kind": "mcq", "text": "Which integer does the point P mark?", "opts": ["−5", "4", "−4", "−3"], "correct": 2, "tag": "", "sol": "P is 4 steps to the left of 0, so it marks −4.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 56\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"8.0\" y1=\"24.0\" x2=\"322.0\" y2=\"24.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"16.0\" y1=\"19\" x2=\"16.0\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"16.0\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−6</text><line x1=\"40.8\" y1=\"19\" x2=\"40.8\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"40.8\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><line x1=\"65.7\" y1=\"19\" x2=\"65.7\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"65.7\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><line x1=\"90.5\" y1=\"19\" x2=\"90.5\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"90.5\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><line x1=\"115.3\" y1=\"19\" x2=\"115.3\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"115.3\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><line x1=\"140.2\" y1=\"19\" x2=\"140.2\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"140.2\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"165.0\" y1=\"19\" x2=\"165.0\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"165.0\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"189.8\" y1=\"19\" x2=\"189.8\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"189.8\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"214.7\" y1=\"19\" x2=\"214.7\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"214.7\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"239.5\" y1=\"19\" x2=\"239.5\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"239.5\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line x1=\"264.3\" y1=\"19\" x2=\"264.3\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"264.3\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><line x1=\"289.2\" y1=\"19\" x2=\"289.2\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"289.2\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><line x1=\"314.0\" y1=\"19\" x2=\"314.0\" y2=\"29\" style=\"stroke:var(--ink);stroke-width:1.2\"/><text class=\"po\" x=\"314.0\" y=\"39.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><circle cx=\"65.7\" cy=\"24\" r=\"4.2\" style=\"fill:var(--accent-text)\"/><text class=\"al\" x=\"65.7\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">P</text></svg>"}, {"kind": "blank", "p": "Insert < or > to make each statement true.", "tag": "", "marks": "", "flat": [{"t": "−8 __B1__ −3", "a": {"B1": "<"}, "accept": ["less than"]}, {"t": "5 __B1__ −10", "a": {"B1": ">"}, "accept": ["greater than"]}, {"t": "−1 __B1__ 0", "a": {"B1": "<"}, "accept": ["less than"]}], "sol": "−8 is further left, so −8 < −3.\nAny positive number is greater than any negative number.\n−1 is left of 0."}, {"kind": "blank", "p": "Write these integers in descending order (largest first), separated by commas (type - for negative):\n−5, 7, −13, 0, 2, −1", "tag": "", "marks": "", "flat": [{"t": "__B1__", "a": {"B1": "7, 2, 0, -1, -5, -13"}, "expr": "dlist"}], "sol": "Positives from largest, then 0, then negatives from closest to 0: 7, 2, 0, −1, −5, −13."}, {"kind": "blank", "p": "Write each quantity as an integer.", "tag": "", "marks": "", "flat": [{"t": "a loss of ₹250: __B1__", "a": {"B1": "-250"}}, {"t": "5 floors above the ground floor: __B1__", "a": {"B1": "5"}}, {"t": "a diver 12 m below sea level: __B1__", "a": {"B1": "-12"}}], "sol": "A loss is negative: −250.\nAbove is positive: +5.\nBelow sea level is negative: −12."}, {"kind": "blank", "p": "Think about the integers that lie strictly between −4 and 3.", "tag": "", "marks": "", "flat": [{"t": "How many are there? __B1__", "a": {"B1": "6"}}, {"t": "The smallest of them is __B1__", "a": {"B1": "-3"}}, {"t": "The opposite of the largest of them is __B1__", "a": {"B1": "-2"}}], "sol": "−3, −2, −1, 0, 1, 2: six integers (−4 and 3 are not included).\n−3.\nThe largest is 2, and its opposite is −2."}]}, {"id": "s2", "label": "3.2 Absolute value", "sub": "Absolute value — distance from zero", "slides": [{"kind": "mcq", "text": "Evaluate |−18|.", "opts": ["{1/18}", "18", "−18", "0"], "correct": 1, "tag": "", "sol": "−18 is 18 units from 0."}, {"kind": "mcq", "text": "Which number has the greatest absolute value?", "opts": ["−7", "−25", "24", "19"], "correct": 1, "tag": "", "sol": "|−25| = 25 is larger than 24, 19 and 7."}, {"kind": "mcq", "text": "Evaluate |−6| − |4|.", "opts": ["10", "−10", "2", "−2"], "correct": 2, "tag": "", "sol": "6 − 4 = 2."}, {"kind": "mcq", "text": "Which pair of numbers have the same absolute value?", "opts": ["11 and 1", "−11 and −1", "−11 and 0", "−11 and 11"], "correct": 3, "tag": "", "sol": "A number and its opposite are the same distance from 0."}, {"kind": "mcq", "text": "Which statement is true?", "opts": ["|−5| > |3|", "|−5| < |3|", "−5 > 3", "|−5| = −5"], "correct": 0, "tag": "", "sol": "|−5| = 5 and |3| = 3, and 5 > 3. An absolute value is never negative."}, {"kind": "mcq", "text": "Which numbers have an absolute value of 9?", "opts": ["0 and 9", "9 and −9", "9 only", "−9 only"], "correct": 1, "tag": "", "sol": "Both 9 and −9 are 9 units from 0."}, {"kind": "mcq", "text": "A submarine is at −120 m and a plane is at 95 m. Which is further from sea level?", "opts": ["The plane, because 95 > −120", "The submarine, because |−120| > 95", "The plane, because it is positive", "They are equally far"], "correct": 1, "tag": "", "sol": "Distance from sea level is the absolute value: 120 m against 95 m."}, {"kind": "mcq", "text": "Which could never be the value of an absolute value?", "opts": ["300", "−3", "0", "3"], "correct": 1, "tag": "", "sol": "Absolute value is a distance, so it cannot be negative."}, {"kind": "blank", "p": "Evaluate each absolute value.", "tag": "", "marks": "", "flat": [{"t": "|−14| = __B1__", "a": {"B1": "14"}}, {"t": "|0| = __B1__", "a": {"B1": "0"}}, {"t": "|31| = __B1__", "a": {"B1": "31"}}], "sol": "14 units from 0.\n0 is 0 units from itself.\n31."}, {"kind": "blank", "p": "Evaluate.", "tag": "", "marks": "", "flat": [{"t": "|−8| + |−5| = __B1__", "a": {"B1": "13"}}, {"t": "|−12| − |−7| = __B1__", "a": {"B1": "5"}}, {"t": "|−3| × |4| = __B1__", "a": {"B1": "12"}}], "sol": "8 + 5 = 13.\n12 − 7 = 5.\n3 × 4 = 12."}, {"kind": "blank", "p": "Insert <, > or = to make each statement true.", "tag": "", "marks": "", "flat": [{"t": "|−9| __B1__ |9|", "a": {"B1": "="}, "accept": ["equals", "equal"]}, {"t": "|−4| __B1__ |−10|", "a": {"B1": "<"}, "accept": ["less than"]}, {"t": "−15 __B1__ |−2|", "a": {"B1": "<"}, "accept": ["less than"]}], "sol": "Both are 9.\n4 < 10.\n−15 is negative and |−2| = 2 is positive."}, {"kind": "blank", "p": "Order these numbers by absolute value, smallest first, separated by commas (type - for negative):\n−6, 2, −11, 9, −1", "tag": "", "marks": "", "flat": [{"t": "__B1__", "a": {"B1": "-1, 2, -6, 9, -11"}, "expr": "dlist"}], "sol": "The absolute values are 6, 2, 11, 9, 1. Smallest first: −1, 2, −6, 9, −11."}, {"kind": "blank", "p": "At midnight, a town in the hills recorded −14 °C and a desert town recorded 11 °C.", "tag": "", "marks": "", "flat": [{"t": "The temperature further from 0 °C is __B1__ °C.", "a": {"B1": "-14"}}, {"t": "Its distance from 0 °C is __B1__ degrees.", "a": {"B1": "14"}}], "sol": "|−14| = 14 is more than |11| = 11.\n14 degrees."}]}, {"id": "s3", "label": "3.3 Cartesian plane", "sub": "The Cartesian plane — plotting and reading points in four quadrants", "slides": [{"kind": "mcq", "text": "What are the coordinates of the origin?", "opts": ["(1, 1)", "(0, 1)", "(1, 0)", "(0, 0)"], "correct": 3, "tag": "", "sol": "The origin is where the axes cross, at x = 0 and y = 0."}, {"kind": "mcq", "text": "In which quadrant is the point (−3, 5)?", "opts": ["I", "IV", "III", "II"], "correct": 3, "tag": "", "sol": "x is negative and y is positive: quadrant II (top left)."}, {"kind": "mcq", "text": "How do you plot (4, −2) starting from the origin?", "opts": ["4 up, then 2 left", "4 right, then 2 down", "4 left, then 2 up", "2 right, then 4 down"], "correct": 1, "tag": "", "sol": "The x-coordinate comes first: +4 is right. Then y = −2 is down."}, {"kind": "mcq", "text": "Which point lies on the y-axis?", "opts": ["(−6, −6)", "(0, −6)", "(−6, 0)", "(6, 6)"], "correct": 1, "tag": "", "sol": "Points on the y-axis have x = 0."}, {"kind": "mcq", "text": "In which quadrant are both coordinates negative?", "opts": ["IV", "I", "II", "III"], "correct": 3, "tag": "", "sol": "Left of the y-axis and below the x-axis: quadrant III."}, {"kind": "mcq", "text": "What are the coordinates of P?", "opts": ["(3, −4)", "(4, −3)", "(−4, 3)", "(−3, 4)"], "correct": 2, "tag": "", "sol": "P is 4 left of the origin (x = −4) and 3 up (y = 3).", "fig": "<svg class=\"figsvg\" style=\"max-width:260px\" viewBox=\"0 0 260 268\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line x1=\"14.0\" y1=\"246.0\" x2=\"14.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"37.2\" y1=\"246.0\" x2=\"37.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"60.4\" y1=\"246.0\" x2=\"60.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"83.6\" y1=\"246.0\" x2=\"83.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"106.8\" y1=\"246.0\" x2=\"106.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"130.0\" y1=\"246.0\" x2=\"130.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"153.2\" y1=\"246.0\" x2=\"153.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"176.4\" y1=\"246.0\" x2=\"176.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"199.6\" y1=\"246.0\" x2=\"199.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"222.8\" y1=\"246.0\" x2=\"222.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"246.0\" y1=\"246.0\" x2=\"246.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"246.0\" x2=\"246.0\" y2=\"246.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"222.8\" x2=\"246.0\" y2=\"222.8\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"199.6\" x2=\"246.0\" y2=\"199.6\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"176.4\" x2=\"246.0\" y2=\"176.4\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"153.2\" x2=\"246.0\" y2=\"153.2\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"130.0\" x2=\"246.0\" y2=\"130.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"106.8\" x2=\"246.0\" y2=\"106.8\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"83.6\" x2=\"246.0\" y2=\"83.6\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"60.4\" x2=\"246.0\" y2=\"60.4\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"37.2\" x2=\"246.0\" y2=\"37.2\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"14.0\" x2=\"246.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"130.0\" x2=\"246.0\" y2=\"130.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><line x1=\"130.0\" y1=\"246.0\" x2=\"130.0\" y2=\"14.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><text class=\"po\" x=\"14.0\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"37.2\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"60.4\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"83.6\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"106.8\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"153.2\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"176.4\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"199.6\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"222.8\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"246.0\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"126.0\" y=\"246.0\" text-anchor=\"end\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"126.0\" y=\"222.8\" text-anchor=\"end\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"126.0\" y=\"199.6\" text-anchor=\"end\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"126.0\" y=\"176.4\" text-anchor=\"end\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"126.0\" y=\"153.2\" text-anchor=\"end\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"126.0\" y=\"106.8\" text-anchor=\"end\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"126.0\" y=\"83.6\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"126.0\" y=\"60.4\" text-anchor=\"end\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"126.0\" y=\"37.2\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"126.0\" y=\"14.0\" text-anchor=\"end\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"125.0\" y=\"139.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><text class=\"al\" x=\"244.0\" y=\"122.0\" text-anchor=\"end\" dominant-baseline=\"middle\">x</text><text class=\"al\" x=\"138.0\" y=\"18.0\" text-anchor=\"start\" dominant-baseline=\"middle\">y</text><circle cx=\"37.2\" cy=\"60.4\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"43.2\" y=\"52.4\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">P</text></svg>"}, {"kind": "mcq", "text": "Point A(−2, 4) moves 5 units to the right. Where is it now?", "opts": ["(−7, 4)", "(−2, 9)", "(3, 4)", "(−2, −1)"], "correct": 2, "tag": "", "sol": "Moving right changes only x: −2 + 5 = 3."}, {"kind": "mcq", "text": "Three corners of a rectangle are (−3, 2), (4, 2) and (4, −1). What is the fourth corner?", "opts": ["(3, −1)", "(−3, 1)", "(−1, −3)", "(−3, −1)"], "correct": 3, "tag": "", "sol": "It is below (−3, 2) and level with (4, −1): x = −3, y = −1."}, {"kind": "blank", "p": "Write down the coordinates of each point, like (2, −3).", "tag": "", "marks": "", "flat": [{"t": "A = __B1__", "a": {"B1": "(2,4)"}, "expr": "coord"}, {"t": "B = __B1__", "a": {"B1": "(-5,1)"}, "expr": "coord"}, {"t": "C = __B1__", "a": {"B1": "(-3,-4)"}, "expr": "coord"}, {"t": "D = __B1__", "a": {"B1": "(4,-2)"}, "expr": "coord"}], "sol": "A: 2 right, 4 up.\nB: 5 left, 1 up.\nC: 3 left, 4 down.\nD: 4 right, 2 down.", "fig": "<svg class=\"figsvg\" style=\"max-width:300px\" viewBox=\"0 0 300 308\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line x1=\"14.0\" y1=\"286.0\" x2=\"14.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"36.7\" y1=\"286.0\" x2=\"36.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"59.3\" y1=\"286.0\" x2=\"59.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"82.0\" y1=\"286.0\" x2=\"82.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"104.7\" y1=\"286.0\" x2=\"104.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"127.3\" y1=\"286.0\" x2=\"127.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"150.0\" y1=\"286.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"172.7\" y1=\"286.0\" x2=\"172.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"195.3\" y1=\"286.0\" x2=\"195.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"218.0\" y1=\"286.0\" x2=\"218.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"240.7\" y1=\"286.0\" x2=\"240.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"263.3\" y1=\"286.0\" x2=\"263.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"286.0\" y1=\"286.0\" x2=\"286.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"286.0\" x2=\"286.0\" y2=\"286.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"263.3\" x2=\"286.0\" y2=\"263.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"240.7\" x2=\"286.0\" y2=\"240.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"218.0\" x2=\"286.0\" y2=\"218.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"195.3\" x2=\"286.0\" y2=\"195.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"172.7\" x2=\"286.0\" y2=\"172.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"150.0\" x2=\"286.0\" y2=\"150.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"127.3\" x2=\"286.0\" y2=\"127.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"104.7\" x2=\"286.0\" y2=\"104.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"82.0\" x2=\"286.0\" y2=\"82.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"59.3\" x2=\"286.0\" y2=\"59.3\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"36.7\" x2=\"286.0\" y2=\"36.7\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"14.0\" x2=\"286.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"150.0\" x2=\"286.0\" y2=\"150.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><line x1=\"150.0\" y1=\"286.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><text class=\"po\" x=\"14.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−6</text><text class=\"po\" x=\"36.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"59.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"82.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"104.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"127.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"172.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"195.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"218.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"240.7\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"263.3\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"286.0\" y=\"159.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><text class=\"po\" x=\"146.0\" y=\"286.0\" text-anchor=\"end\" dominant-baseline=\"middle\">−6</text><text class=\"po\" x=\"146.0\" y=\"263.3\" text-anchor=\"end\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"146.0\" y=\"240.7\" text-anchor=\"end\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"146.0\" y=\"218.0\" text-anchor=\"end\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"146.0\" y=\"195.3\" text-anchor=\"end\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"146.0\" y=\"172.7\" text-anchor=\"end\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"146.0\" y=\"127.3\" text-anchor=\"end\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"146.0\" y=\"104.7\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"146.0\" y=\"82.0\" text-anchor=\"end\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"146.0\" y=\"59.3\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"146.0\" y=\"36.7\" text-anchor=\"end\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"146.0\" y=\"14.0\" text-anchor=\"end\" dominant-baseline=\"middle\">6</text><text class=\"po\" x=\"145.0\" y=\"159.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><text class=\"al\" x=\"284.0\" y=\"142.0\" text-anchor=\"end\" dominant-baseline=\"middle\">x</text><text class=\"al\" x=\"158.0\" y=\"18.0\" text-anchor=\"start\" dominant-baseline=\"middle\">y</text><circle cx=\"195.3\" cy=\"59.3\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"201.3\" y=\"51.3\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">A</text><circle cx=\"36.7\" cy=\"127.3\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"42.7\" y=\"119.3\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">B</text><circle cx=\"82.0\" cy=\"240.7\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"88.0\" y=\"232.7\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">C</text><circle cx=\"240.7\" cy=\"195.3\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"246.7\" y=\"187.3\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">D</text></svg>"}, {"kind": "blank", "p": "Name where each point is.", "tag": "", "marks": "", "flat": [{"t": "(−7, −2) is in quadrant __B1__ (write I, II, III or IV).", "a": {"B1": "III"}, "expr": "words", "accept": ["3", "3rd", "three", "third", "quadrant 3", "quadrant three", "quadrant iii", "q3", "third quadrant"]}, {"t": "(6, 0) lies on the __B1__-axis.", "a": {"B1": "x"}, "expr": "words", "accept": ["x axis", "x-axis"]}, {"t": "(1, −9) is in quadrant __B1__.", "a": {"B1": "IV"}, "expr": "words", "accept": ["4", "4th", "four", "fourth", "quadrant 4", "quadrant four", "quadrant iv", "q4", "fourth quadrant"]}], "sol": "x negative, y negative: III.\ny = 0, so it is on the x-axis.\nx positive, y negative: IV."}, {"kind": "blank", "p": "Find the distance between each pair of points.", "tag": "", "marks": "", "flat": [{"t": "(−3, 2) and (5, 2): __B1__ units", "a": {"B1": "8"}}, {"t": "(1, −4) and (1, 3): __B1__ units", "a": {"B1": "7"}}], "sol": "Same y, so count along x: from −3 to 5 is 3 + 5 = 8.\nSame x, so count along y: from −4 to 3 is 4 + 3 = 7."}, {"kind": "blank", "p": "Three corners of a square are (−2, −1), (3, −1) and (3, 4).", "tag": "", "marks": "", "flat": [{"t": "The fourth corner is __B1__", "a": {"B1": "(-2,4)"}, "expr": "coord"}, {"t": "The side length is __B1__ units.", "a": {"B1": "5"}}, {"t": "The area is __B1__ square units.", "a": {"B1": "25"}}], "sol": "Level with (3, 4) and above (−2, −1): (−2, 4).\nFrom x = −2 to x = 3 is 5 units.\n5 × 5 = 25."}]}, {"id": "s4", "label": "3.4 Multiply and divide", "sub": "Multiplying and dividing integers — sign rules, several factors and powers", "slides": [{"kind": "mcq", "text": "Evaluate −6 × 7.", "opts": ["42", "−13", "−42", "1"], "correct": 2, "tag": "", "sol": "Different signs give a negative product: −42."}, {"kind": "mcq", "text": "Evaluate (−8) × (−5).", "opts": ["−40", "3", "−13", "40"], "correct": 3, "tag": "", "sol": "Same signs give a positive product."}, {"kind": "mcq", "text": "Evaluate −54 ÷ 9.", "opts": ["6", "−45", "−63", "−6"], "correct": 3, "tag": "", "sol": "Different signs: −6."}, {"kind": "mcq", "text": "Evaluate (−72) ÷ (−8).", "opts": ["−9", "9", "−64", "80"], "correct": 1, "tag": "", "sol": "Same signs: positive 9."}, {"kind": "mcq", "text": "Evaluate (−2) × (−3) × (−5).", "opts": ["30", "−10", "10", "−30"], "correct": 3, "tag": "", "sol": "Three negative factors (odd number), so the product is negative: −30."}, {"kind": "mcq", "text": "Evaluate (−3)⁴.", "opts": ["−12", "−81", "81", "12"], "correct": 2, "tag": "", "sol": "(−3) × (−3) × (−3) × (−3): four negatives, so positive 81."}, {"kind": "mcq", "text": "Evaluate −4².", "opts": ["8", "−16", "−8", "16"], "correct": 1, "tag": "", "sol": "The power applies only to 4: −(4 × 4) = −16. Compare (−4)² = 16."}, {"kind": "mcq", "text": "What number goes in the box? −7 × ▢ = 63", "opts": ["−9", "70", "9", "−56"], "correct": 0, "tag": "", "sol": "63 ÷ (−7) = −9. Check: −7 × (−9) = 63."}, {"kind": "blank", "p": "Continue the pattern.\n4 × 2 = 8,   4 × 1 = 4,   4 × 0 = 0", "tag": "", "marks": "", "flat": [{"t": "4 × (−1) = __B1__", "a": {"B1": "-4"}}, {"t": "4 × (−2) = __B1__", "a": {"B1": "-8"}}, {"t": "Each answer decreases by __B1__.", "a": {"B1": "4"}}], "sol": "The answers go down by 4 each time: 0 − 4 = −4.\n−4 − 4 = −8.\nEach time the second factor falls by 1, the product falls by 4."}, {"kind": "blank", "p": "Evaluate.", "tag": "", "marks": "", "flat": [{"t": "−9 × 6 = __B1__", "a": {"B1": "-54"}}, {"t": "−48 ÷ (−6) = __B1__", "a": {"B1": "8"}}, {"t": "0 ÷ (−5) = __B1__", "a": {"B1": "0"}}], "sol": "Different signs: −54.\nSame signs: 8.\n0 divided by any non-zero number is 0."}, {"kind": "blank", "p": "Evaluate (−1) × (−2) × (−3) × (−4).", "tag": "", "marks": "", "flat": [{"t": "Number of negative factors = __B1__", "a": {"B1": "4"}}, {"t": "So the answer is __B1__ (positive / negative).", "a": {"B1": "positive"}, "expr": "words"}, {"t": "Value = __B1__", "a": {"B1": "24"}}], "sol": "All four factors are negative.\nAn even number of negatives gives a positive answer.\n1 × 2 × 3 × 4 = 24."}, {"kind": "blank", "p": "Evaluate the powers.", "tag": "", "marks": "", "flat": [{"t": "(−2)⁵ = __B1__", "a": {"B1": "-32"}}, {"t": "(−5)² = __B1__", "a": {"B1": "25"}}, {"t": "−5² = __B1__", "a": {"B1": "-25"}}], "sol": "Odd power of a negative: −32.\n(−5) × (−5) = 25.\n−(5 × 5) = −25."}, {"kind": "blank", "p": "On Earth, the force of gravity on an object (in newtons) is about its mass in kg × (−10).", "tag": "", "marks": "", "flat": [{"t": "For a 65 kg trekker, force = __B1__ N", "a": {"B1": "-650"}}, {"t": "A diver changes depth by −3 m every second. Change after 12 seconds = __B1__ m", "a": {"B1": "-36"}}], "sol": "65 × (−10) = −650 N (the minus sign shows the force is downwards).\n12 × (−3) = −36 m."}]}, {"id": "s5", "label": "3.5 Add and subtract", "sub": "Adding and subtracting integers — number lines, tokens and adding the opposite", "slides": [{"kind": "mcq", "text": "Evaluate −7 + 4.", "opts": ["−3", "−11", "11", "3"], "correct": 0, "tag": "", "sol": "Start at −7 and move 4 right: −3."}, {"kind": "mcq", "text": "Evaluate −6 + (−9).", "opts": ["15", "−15", "−3", "3"], "correct": 1, "tag": "", "sol": "Adding a negative moves left: −6 − 9 = −15."}, {"kind": "mcq", "text": "Evaluate 5 − 12.", "opts": ["7", "−17", "17", "−7"], "correct": 3, "tag": "", "sol": "Start at 5 and move 12 left: −7."}, {"kind": "mcq", "text": "Evaluate −3 − (−8).", "opts": ["5", "−11", "11", "−5"], "correct": 0, "tag": "", "sol": "Subtracting −8 is adding 8: −3 + 8 = 5."}, {"kind": "mcq", "text": "Evaluate 8 − (−6).", "opts": ["−2", "2", "14", "−14"], "correct": 2, "tag": "", "sol": "8 + 6 = 14."}, {"kind": "mcq", "text": "The temperature at dawn was −4 °C. By noon it had risen 9 degrees. What was the noon temperature?", "opts": ["−5 °C", "13 °C", "5 °C", "−13 °C"], "correct": 2, "tag": "", "sol": "−4 + 9 = 5."}, {"kind": "mcq", "text": "Which calculation gives the same answer as −10 − (−3)?", "opts": ["10 − 3", "−10 − 3", "−10 + 3", "−10 + (−3)"], "correct": 2, "tag": "", "sol": "Subtracting a number is the same as adding its opposite: −(−3) becomes +3."}, {"kind": "mcq", "text": "The tokens show 3 positive and 7 negative counters. What number do they represent?", "opts": ["−10", "−4", "10", "4"], "correct": 1, "tag": "", "sol": "3 zero pairs cancel, leaving 4 negative tokens: −4.", "fig": "<svg class=\"figsvg\" style=\"max-width:300px\" viewBox=\"0 0 300 86\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><circle cx=\"24\" cy=\"24\" r=\"12\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"24.0\" y=\"24.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">+</text><circle cx=\"54\" cy=\"24\" r=\"12\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"54.0\" y=\"24.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">+</text><circle cx=\"84\" cy=\"24\" r=\"12\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"84.0\" y=\"24.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">+</text><circle cx=\"24\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"24\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"54\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"54\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"84\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"84\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"114\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"114\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"144\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"144\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"174\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"174\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text><circle cx=\"204\" cy=\"60\" r=\"12\" style=\"fill:var(--danger);stroke:var(--danger);stroke-width:1.6\"/><text x=\"204\" y=\"60\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#fff;font:700 15px 'Source Sans 3',sans-serif\">−</text></svg>"}, {"kind": "blank", "p": "Rewrite each subtraction as an addition, then evaluate.", "tag": "", "marks": "", "flat": [{"t": "4 − (−9) = 4 + __B1__ = __B2__", "a": {"B1": "9", "B2": "13"}}, {"t": "−2 − 5 = −2 + (__B1__) = __B2__", "a": {"B1": "-5", "B2": "-7"}}], "sol": "Add the opposite of −9, which is 9: 13.\nAdd the opposite of 5, which is −5: −7."}, {"kind": "blank", "p": "Evaluate.", "tag": "", "marks": "", "flat": [{"t": "−15 + 22 = __B1__", "a": {"B1": "7"}}, {"t": "−11 − 13 = __B1__", "a": {"B1": "-24"}}, {"t": "−20 − (−20) = __B1__", "a": {"B1": "0"}}], "sol": "Move 22 right from −15: 7.\n−11 + (−13) = −24.\n−20 + 20 = 0."}, {"kind": "blank", "p": "Find the missing numbers.", "tag": "", "marks": "", "flat": [{"t": "−6 + __B1__ = −2", "a": {"B1": "4"}}, {"t": "3 − __B1__ = 10", "a": {"B1": "-7"}}], "sol": "From −6 to −2 is 4 steps up.\n3 − (−7) = 3 + 7 = 10."}, {"kind": "blank", "p": "A diver is at −35 m. She rises 18 m, then descends 9 m.", "tag": "", "marks": "", "flat": [{"t": "After rising she is at __B1__ m.", "a": {"B1": "-17"}}, {"t": "After descending she is at __B1__ m.", "a": {"B1": "-26"}}], "sol": "−35 + 18 = −17.\n−17 − 9 = −26."}, {"kind": "blank", "p": "The highest temperature recorded in a desert town was 48 °C and the lowest recorded in a mountain town was −12 °C.", "tag": "", "marks": "", "flat": [{"t": "Difference = 48 − (__B1__) = __B2__ °C", "a": {"B1": "-12", "B2": "60"}}], "sol": "Difference = higher − lower = 48 − (−12) = 48 + 12 = 60 °C."}]}, {"id": "s6", "label": "3.6 Order of operations", "sub": "Order of operations and problem solving with integers", "slides": [{"kind": "mcq", "text": "Evaluate −8 + 2 × (−3).", "opts": ["−14", "2", "18", "−30"], "correct": 0, "tag": "", "sol": "Multiply first: 2 × (−3) = −6. Then −8 + (−6) = −14."}, {"kind": "mcq", "text": "Evaluate (−8 + 2) × (−3).", "opts": ["−14", "18", "14", "−18"], "correct": 1, "tag": "", "sol": "Brackets first: −6. Then −6 × (−3) = 18."}, {"kind": "mcq", "text": "Evaluate 20 ÷ (−4) − 3.", "opts": ["8", "−2", "−8", "−20"], "correct": 2, "tag": "", "sol": "20 ÷ (−4) = −5; −5 − 3 = −8."}, {"kind": "mcq", "text": "Evaluate (−3)² − 4 × 2.", "opts": ["−17", "1", "10", "−1"], "correct": 1, "tag": "", "sol": "(−3)² = 9, 4 × 2 = 8, 9 − 8 = 1."}, {"kind": "mcq", "text": "Evaluate (−12 − 6) ÷ (−3).", "opts": ["−6", "−2", "6", "2"], "correct": 2, "tag": "", "sol": "Brackets: −18. Then −18 ÷ (−3) = 6."}, {"kind": "mcq", "text": "Evaluate 7 − 3 × (−2)².", "opts": ["64", "19", "−16", "−5"], "correct": 3, "tag": "", "sol": "Power: (−2)² = 4. Multiply: 3 × 4 = 12. Subtract: 7 − 12 = −5."}, {"kind": "mcq", "text": "Where should brackets go so that −4 × 3 + 5 = −32?", "opts": ["(−4 × 3 + 5)", "(−4 × 3) + 5", "−4 × (3 + 5)", "No brackets are needed"], "correct": 2, "tag": "", "sol": "−4 × 8 = −32. Without brackets the answer is −12 + 5 = −7."}, {"kind": "mcq", "text": "A student writes −2² + 10 = 14. What is the correct answer?", "opts": ["−14", "8", "14", "6"], "correct": 3, "tag": "", "sol": "−2² = −4 (the square applies only to 2), so −4 + 10 = 6."}, {"kind": "blank", "p": "Evaluate −6 × (−2) − 15 ÷ (−3).", "tag": "", "marks": "", "flat": [{"t": "−6 × (−2) = __B1__", "a": {"B1": "12"}}, {"t": "15 ÷ (−3) = __B1__", "a": {"B1": "-5"}}, {"t": "Answer = __B1__", "a": {"B1": "17"}}], "sol": "Same signs: 12.\nDifferent signs: −5.\n12 − (−5) = 12 + 5 = 17."}, {"kind": "blank", "p": "Evaluate (−24 + 6) ÷ (−9 + 3).", "tag": "", "marks": "", "flat": [{"t": "Numerator: −24 + 6 = __B1__", "a": {"B1": "-18"}}, {"t": "Denominator: −9 + 3 = __B1__", "a": {"B1": "-6"}}, {"t": "Value = __B1__", "a": {"B1": "3"}}], "sol": "−18.\n−6.\n−18 ÷ (−6) = 3."}, {"kind": "blank", "p": "Riya had ₹500. She spent ₹120 three times and then received ₹200.", "tag": "", "marks": "", "flat": [{"t": "Expression: 500 + 3 × (−120) + __B1__", "a": {"B1": "200"}, "expr": true}, {"t": "She now has ₹__B1__", "a": {"B1": "340"}}], "sol": "Money received is positive: +200.\n500 − 360 + 200 = 340."}, {"kind": "blank", "p": "At a mountain base camp it is −4 °C. The temperature falls 6 °C for every 1000 m climbed.", "tag": "", "marks": "", "flat": [{"t": "Change after climbing 3000 m = __B1__ °C", "a": {"B1": "-18"}}, {"t": "Temperature at that height = __B1__ °C", "a": {"B1": "-22"}}], "sol": "3 × (−6) = −18.\n−4 + (−18) = −22."}, {"kind": "blank", "p": "A research submersible starts at −40 m and descends 15 m every minute for 6 minutes.", "tag": "", "marks": "", "flat": [{"t": "Change in depth = __B1__ m", "a": {"B1": "-90"}}, {"t": "Final position = __B1__ m", "a": {"B1": "-130"}}], "sol": "6 × (−15) = −90.\n−40 + (−90) = −130 m (130 m below sea level)."}]}, {"id": "s7", "label": "Test A", "sub": "Criterion A — Knowing and understanding", "slides": [{"kind": "mcq", "text": "Which list is in ascending order?", "opts": ["−10, −5, −2, 4", "−10, −2, −5, 4", "4, −2, −5, −10", "−2, −5, −10, 4"], "correct": 0, "tag": "", "sol": "Smallest first: −10 < −5 < −2 < 4."}, {"kind": "mcq", "text": "Evaluate |−37|.", "opts": ["−37", "0", "{1/37}", "37"], "correct": 3, "tag": "", "sol": "−37 is 37 units from 0."}, {"kind": "mcq", "text": "Evaluate (−9) × 4.", "opts": ["−36", "−13", "36", "−5"], "correct": 0, "tag": "", "sol": "Different signs: −36."}, {"kind": "mcq", "text": "Evaluate −13 + 20.", "opts": ["33", "−33", "−7", "7"], "correct": 3, "tag": "", "sol": "Start at −13 and move 20 right: 7."}, {"kind": "mcq", "text": "Evaluate −4 − 9.", "opts": ["−5", "−13", "5", "13"], "correct": 1, "tag": "", "sol": "−4 + (−9) = −13."}, {"kind": "mcq", "text": "Evaluate (−56) ÷ (−7).", "opts": ["63", "−8", "8", "−49"], "correct": 2, "tag": "", "sol": "Same signs: 8."}, {"kind": "mcq", "text": "In which quadrant is the point (−5, −1)?", "opts": ["IV", "II", "I", "III"], "correct": 3, "tag": "", "sol": "Both coordinates are negative: quadrant III."}, {"kind": "mcq", "text": "Evaluate −3 × (4 − 9).", "opts": ["3", "−15", "−21", "15"], "correct": 3, "tag": "", "sol": "Brackets: 4 − 9 = −5. Then −3 × (−5) = 15."}, {"kind": "blank", "p": "Evaluate.", "tag": "", "marks": "", "flat": [{"t": "6 − (−11) = __B1__", "a": {"B1": "17"}}, {"t": "−7 + (−8) = __B1__", "a": {"B1": "-15"}}], "sol": "6 + 11 = 17.\n−7 − 8 = −15."}, {"kind": "blank", "p": "Evaluate the powers.", "tag": "", "marks": "", "flat": [{"t": "(−2)³ = __B1__", "a": {"B1": "-8"}}, {"t": "(−1)¹⁰ = __B1__", "a": {"B1": "1"}}], "sol": "(−2) × (−2) × (−2) = −8.\nAn even power of −1 is 1."}, {"kind": "blank", "p": "Write the coordinates of E and F, like (2, −3).", "tag": "", "marks": "", "flat": [{"t": "E = __B1__", "a": {"B1": "(-3,2)"}, "expr": "coord"}, {"t": "F = __B1__", "a": {"B1": "(1,-4)"}, "expr": "coord"}], "sol": "3 left, 2 up.\n1 right, 4 down.", "fig": "<svg class=\"figsvg\" style=\"max-width:260px\" viewBox=\"0 0 260 268\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line x1=\"14.0\" y1=\"246.0\" x2=\"14.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"37.2\" y1=\"246.0\" x2=\"37.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"60.4\" y1=\"246.0\" x2=\"60.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"83.6\" y1=\"246.0\" x2=\"83.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"106.8\" y1=\"246.0\" x2=\"106.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"130.0\" y1=\"246.0\" x2=\"130.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"153.2\" y1=\"246.0\" x2=\"153.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"176.4\" y1=\"246.0\" x2=\"176.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"199.6\" y1=\"246.0\" x2=\"199.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"222.8\" y1=\"246.0\" x2=\"222.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"246.0\" y1=\"246.0\" x2=\"246.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"246.0\" x2=\"246.0\" y2=\"246.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"222.8\" x2=\"246.0\" y2=\"222.8\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"199.6\" x2=\"246.0\" y2=\"199.6\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"176.4\" x2=\"246.0\" y2=\"176.4\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"153.2\" x2=\"246.0\" y2=\"153.2\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"130.0\" x2=\"246.0\" y2=\"130.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"106.8\" x2=\"246.0\" y2=\"106.8\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"83.6\" x2=\"246.0\" y2=\"83.6\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"60.4\" x2=\"246.0\" y2=\"60.4\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"37.2\" x2=\"246.0\" y2=\"37.2\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"14.0\" x2=\"246.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><line x1=\"14.0\" y1=\"130.0\" x2=\"246.0\" y2=\"130.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><line x1=\"130.0\" y1=\"246.0\" x2=\"130.0\" y2=\"14.0\" style=\"stroke:var(--ink-soft);stroke-width:1.4\"/><text class=\"po\" x=\"14.0\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"37.2\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"60.4\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"83.6\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"106.8\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"153.2\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"176.4\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"199.6\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"222.8\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"246.0\" y=\"139.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"126.0\" y=\"246.0\" text-anchor=\"end\" dominant-baseline=\"middle\">−5</text><text class=\"po\" x=\"126.0\" y=\"222.8\" text-anchor=\"end\" dominant-baseline=\"middle\">−4</text><text class=\"po\" x=\"126.0\" y=\"199.6\" text-anchor=\"end\" dominant-baseline=\"middle\">−3</text><text class=\"po\" x=\"126.0\" y=\"176.4\" text-anchor=\"end\" dominant-baseline=\"middle\">−2</text><text class=\"po\" x=\"126.0\" y=\"153.2\" text-anchor=\"end\" dominant-baseline=\"middle\">−1</text><text class=\"po\" x=\"126.0\" y=\"106.8\" text-anchor=\"end\" dominant-baseline=\"middle\">1</text><text class=\"po\" x=\"126.0\" y=\"83.6\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><text class=\"po\" x=\"126.0\" y=\"60.4\" text-anchor=\"end\" dominant-baseline=\"middle\">3</text><text class=\"po\" x=\"126.0\" y=\"37.2\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"126.0\" y=\"14.0\" text-anchor=\"end\" dominant-baseline=\"middle\">5</text><text class=\"po\" x=\"125.0\" y=\"139.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><text class=\"al\" x=\"244.0\" y=\"122.0\" text-anchor=\"end\" dominant-baseline=\"middle\">x</text><text class=\"al\" x=\"138.0\" y=\"18.0\" text-anchor=\"start\" dominant-baseline=\"middle\">y</text><circle cx=\"60.4\" cy=\"83.6\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"66.4\" y=\"75.6\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">E</text><circle cx=\"153.2\" cy=\"222.8\" r=\"3.8\" style=\"fill:var(--danger)\"/><text x=\"159.2\" y=\"214.8\" text-anchor=\"start\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif;paint-order:stroke;stroke:var(--card);stroke-width:3px\">F</text></svg>"}, {"kind": "blank", "p": "Evaluate 18 ÷ (−3) + (−2) × 5.", "tag": "", "marks": "", "flat": [{"t": "18 ÷ (−3) = __B1__", "a": {"B1": "-6"}}, {"t": "(−2) × 5 = __B1__", "a": {"B1": "-10"}}, {"t": "Answer = __B1__", "a": {"B1": "-16"}}], "sol": "Different signs: −6.\n−10.\n−6 + (−10) = −16."}]}, {"id": "s8", "label": "Test B", "sub": "Criterion B — Investigating patterns", "slides": [{"kind": "mcq", "text": "7 × 2 = 14, 7 × 1 = 7, 7 × 0 = 0. If the pattern continues, what is 7 × (−1)?", "opts": ["−1", "7", "0", "−7"], "correct": 3, "tag": "", "sol": "The products go down by 7 each time: 0 − 7 = −7."}, {"kind": "mcq", "text": "Look at the pattern: −5 × 3 = −15, −5 × 2 = −10, −5 × 1 = −5, −5 × 0 = 0. If it continues, what is −5 × (−2)?", "opts": ["5, because the second factor went down by 2", "−7, because −5 + (−2) = −7", "10, because each answer is 5 more than the one before", "−10, because each answer is 5 less than the one before"], "correct": 2, "tag": "", "sol": "The answers go up by 5 each time: −15, −10, −5, 0, then 5 for −5 × (−1) and 10 for −5 × (−2). The pattern shows that negative × negative is positive."}, {"kind": "mcq", "text": "The sequence 11, 7, 3, −1, … continues. What are the next two terms?", "opts": ["5, 9", "−5, −10", "−5, −9", "−3, −5"], "correct": 2, "tag": "", "sol": "Each term is 4 less than the one before: −1 − 4 = −5, −5 − 4 = −9."}, {"kind": "mcq", "text": "The points (1, −2), (2, −4) and (3, −6) follow a rule. Which one?", "opts": ["x = −2y", "y = 2x", "y = x − 3", "y = −2x"], "correct": 3, "tag": "", "sol": "Each y is −2 times its x: −2 × 3 = −6."}, {"kind": "blank", "p": "Investigate powers of −1.", "tag": "", "marks": "", "flat": [{"t": "(−1)¹ = __B1__ and (−1)² = __B2__", "a": {"B1": "-1", "B2": "1"}}, {"t": "(−1)³ = __B1__ and (−1)⁴ = __B2__", "a": {"B1": "-1", "B2": "1"}}, {"t": "Rule: (−1)ⁿ = 1 when n is __B1__ (even / odd).", "a": {"B1": "even"}, "expr": "words"}, {"t": "Extend the rule: (−1)¹⁵ = __B1__", "a": {"B1": "-1"}}, {"t": "(−1)¹⁰⁰ = __B1__", "a": {"B1": "1"}}], "sol": "(−1)¹ = −1; (−1) × (−1) = 1.\n1 × (−1) = −1; (−1) × (−1) = 1.\nEach extra factor of −1 flips the sign, so even powers give 1 and odd powers give −1.\n15 is odd: −1.\n100 is even: 1."}, {"kind": "blank", "p": "Investigate powers of −3.", "tag": "", "marks": "", "flat": [{"t": "(−3)² = __B1__ and (−3)³ = __B2__", "a": {"B1": "9", "B2": "-27"}}, {"t": "(−3)⁴ = __B1__ and (−3)⁵ = __B2__", "a": {"B1": "81", "B2": "-243"}}, {"t": "(−3)ⁿ is positive when n is __B1__ (even / odd).", "a": {"B1": "even"}, "expr": "words"}, {"t": "Use the rule: (−3)⁶ = __B1__", "a": {"B1": "729"}}], "sol": "(−3) × (−3) = 9; 9 × (−3) = −27.\n−27 × (−3) = 81; 81 × (−3) = −243.\nEach extra factor of −3 flips the sign, so even powers are positive.\n3⁶ = 729 and 6 is even, so (−3)⁶ = 729."}, {"kind": "blank", "p": "Investigate subtracting a negative.\n5 − 2 = 3,   5 − 1 = 4,   5 − 0 = 5", "tag": "", "marks": "", "flat": [{"t": "5 − (−1) = __B1__", "a": {"B1": "6"}}, {"t": "5 − (−2) = __B1__", "a": {"B1": "7"}}, {"t": "Rule: subtracting a negative number is the same as __B1__ its opposite.", "a": {"B1": "adding"}, "expr": "words", "accept": ["add"]}], "sol": "As the number subtracted goes down by 1, the answer goes up by 1: 6.\n7.\n5 − (−2) = 5 + 2: subtract a negative = add the positive."}, {"kind": "blank", "p": "The sequence −8, −5, −2, 1, … continues in the same way.", "tag": "", "marks": "", "flat": [{"t": "The common difference is __B1__", "a": {"B1": "3"}}, {"t": "The 10th term is __B1__", "a": {"B1": "19"}}, {"t": "The nth term is __B1__", "a": {"B1": "3n-11"}, "expr": true}], "sol": "−5 − (−8) = 3.\n−8 + 9 × 3 = 19.\nnth term = −8 + (n − 1) × 3 = 3n − 11. Check n = 1: 3 − 11 = −8 ✓."}, {"kind": "blank", "p": "Investigate the distance between two integers on a number line.", "tag": "", "marks": "", "flat": [{"t": "Distance between −3 and 5 (count the steps) = __B1__", "a": {"B1": "8"}}, {"t": "Distance between −9 and −2 = __B1__", "a": {"B1": "7"}}, {"t": "Test a rule: |−9 − (−2)| = __B1__", "a": {"B1": "7"}}, {"t": "So the distance between a and b is the __B1__ value of a − b.", "a": {"B1": "absolute"}, "expr": "words"}], "sol": "3 steps to 0, then 5 more: 8.\nFrom −9 up to −2 is 7 steps.\n|−9 + 2| = |−7| = 7 ✓, the same as counting.\nDistance = |a − b|, which is never negative whichever order you subtract in."}]}, {"id": "s9", "label": "Test C", "sub": "Criterion C — Communicating", "slides": [{"kind": "mcq", "text": "How should “negative five minus negative three” be written?", "opts": ["−5 − (−3)", "5 − 3", "−(5 − 3)", "−5 − 3"], "correct": 0, "tag": "", "sol": "Keep each negative number with its sign, and put brackets around a negative that follows an operation sign."}, {"kind": "mcq", "text": "What is the name for the distance of a number from zero?", "opts": ["Opposite", "Integer", "Absolute value", "Origin"], "correct": 2, "tag": "", "sol": "|x| means the distance of x from 0."}, {"kind": "mcq", "text": "A student writes −8 − 3 = −5. What is the mistake?", "opts": ["The answer should be 5", "Subtracting 3 moves left, so the answer is −11", "The answer should be 11", "There is no mistake"], "correct": 1, "tag": "", "sol": "Starting at −8 and moving 3 to the left gives −11. The student moved right."}, {"kind": "mcq", "text": "Kabir describes a point as “3 units right and 6 units down” and writes it as (−6, 3). Which is the best correction?", "opts": ["It should be (6, −3)", "It should be (3, −6): the x-coordinate (right +) comes first, then y (down −)", "It should be (−3, 6)", "It is correct because both numbers appear"], "correct": 1, "tag": "", "sol": "An ordered pair is always (x, y). Right 3 gives x = 3 and down 6 gives y = −6, so the point is (3, −6). Kabir used the right numbers but swapped their order."}, {"kind": "mcq", "text": "A student writes (−3)² = −9. Which explanation corrects this?", "opts": ["(−3)² = 3² = 6", "(−3)² = (−3) × (−3) = 9, because two negatives multiply to a positive", "(−3)² = −9 is correct", "(−3)² = −3 × 2 = −6"], "correct": 1, "tag": "", "sol": "Squaring means multiplying the number by itself, and (−3) × (−3) = 9."}, {"kind": "mcq", "text": "Which representation shows most clearly a temperature of 5 °C falling by 8 degrees?", "opts": ["A table with one row", "A coordinate grid with the point (5, 8)", "A vertical number line (thermometer) with an arrow down 8 steps", "A list of the numbers 5 and 8"], "correct": 2, "tag": "", "sol": "A vertical number line matches the context and shows the movement from 5 down to −3."}, {"kind": "mcq", "text": "Which is the best justification that −4 > −9?", "opts": ["Both are negative", "−9 has more digits", "4 is less than 9", "−4 is to the right of −9 on the number line"], "correct": 3, "tag": "", "sol": "On a horizontal number line, numbers to the right are greater."}, {"kind": "mcq", "text": "A diver at −12 m descends another 7 m. Which is the clearest final answer?", "opts": ["The diver is at 19 m.", "19", "The diver is 19 m below sea level (−19 m).", "−19 m above"], "correct": 2, "tag": "", "sol": "−12 + (−7) = −19. A full answer states the depth with units and says it is below sea level."}, {"kind": "blank", "p": "Complete the explanation of −6 × (−4).", "tag": "", "marks": "", "flat": [{"t": "The two factors have the __B1__ sign (same / different).", "a": {"B1": "same"}, "expr": "words"}, {"t": "So the product is __B1__ (positive / negative).", "a": {"B1": "positive"}, "expr": "words"}, {"t": "−6 × (−4) = __B1__", "a": {"B1": "24"}}], "sol": "Both factors are negative.\nSame signs give a positive product.\n6 × 4 = 24."}, {"kind": "blank", "p": "Complete the explanation of 3 − (−7).", "tag": "", "marks": "", "flat": [{"t": "Subtracting a number is the same as adding its __B1__.", "a": {"B1": "opposite"}, "expr": "words", "accept": ["additive inverse", "inverse"]}, {"t": "So 3 − (−7) = 3 + __B1__", "a": {"B1": "7"}}, {"t": "= __B1__", "a": {"B1": "10"}}], "sol": "For example, 5 − 2 = 5 + (−2).\nThe opposite of −7 is 7.\n3 + 7 = 10."}]}, {"id": "s10", "label": "Test D", "sub": "Criterion D — Applying mathematics in real-life contexts", "slides": [{"kind": "mcq", "text": "In Drass (Ladakh) the temperature was −22 °C at night and 3 °C the next afternoon. By how much did it rise?", "opts": ["−25 °C", "19 °C", "−19 °C", "25 °C"], "correct": 3, "tag": "", "sol": "3 − (−22) = 3 + 22 = 25."}, {"kind": "mcq", "text": "A shop recorded weekly results of +₹850, −₹300, +₹420 and −₹610. What was the total over the four weeks?", "opts": ["+₹360", "+₹1270", "+₹2180", "−₹360"], "correct": 0, "tag": "", "sol": "850 − 300 + 420 − 610 = 360."}, {"kind": "mcq", "text": "The summit of Everest is about 8849 m and an ocean trench floor is at −7450 m. What is the vertical distance between them?", "opts": ["1399 m", "16 299 m", "8849 m", "−16 299 m"], "correct": 1, "tag": "", "sol": "8849 − (−7450) = 8849 + 7450 = 16 299 m."}, {"kind": "mcq", "text": "A mall lift starts at parking level −2 and goes up 7 floors. Which level does it reach?", "opts": ["9", "5", "−9", "−5"], "correct": 1, "tag": "", "sol": "−2 + 7 = 5."}, {"kind": "mcq", "text": "A freezer is at −18 °C and the kitchen is 27 °C. Aman says the difference is 9 °C. Is he right?", "opts": ["No: the difference is −45 °C", "No: 27 − (−18) = 45 °C", "Yes: temperatures cannot be subtracted", "Yes: 27 − 18 = 9"], "correct": 1, "tag": "", "sol": "He ignored the negative sign. The difference is 45 °C, which makes sense: 18 degrees down to 0, then 27 more."}, {"kind": "mcq", "text": "An emperor was born in 304 BCE (−304) and died in 232 BCE (−232). About how old was he when he died?", "opts": ["536", "72", "232", "−72"], "correct": 1, "tag": "", "sol": "−232 − (−304) = 72 years."}, {"kind": "mcq", "text": "A submersible descends from the surface at 25 m per minute. How long does it take to reach −300 m?", "opts": ["7500 minutes", "275 minutes", "−12 minutes", "12 minutes"], "correct": 3, "tag": "", "sol": "−300 ÷ (−25) = 12."}, {"kind": "blank", "p": "A maths quiz gives +4 for a correct answer, −1 for a wrong answer and 0 for a blank.", "tag": "", "marks": "", "flat": [{"t": "Meera: 18 correct, 7 wrong, 5 blank. Score = __B1__", "a": {"B1": "65"}}, {"t": "Karan: 15 correct, 3 wrong, 12 blank. Score = __B1__", "a": {"B1": "57"}}, {"t": "__B1__ scored higher.", "a": {"B1": "Meera"}, "expr": "words"}], "sol": "18 × 4 + 7 × (−1) = 72 − 7 = 65.\n15 × 4 + 3 × (−1) = 60 − 3 = 57.\n65 > 57."}, {"kind": "blank", "p": "A hill town at 2000 m is 6 °C. The temperature falls 6 °C for every 1000 m climbed.", "tag": "", "marks": "", "flat": [{"t": "Temperature at 5000 m = __B1__ °C", "a": {"B1": "-12"}}, {"t": "The temperature is 0 °C at __B1__ m.", "a": {"B1": "3000"}}], "sol": "3000 m higher: 6 + 3 × (−6) = −12 °C.\nIt must fall 6 degrees: 1000 m above 2000 m, so 3000 m."}, {"kind": "blank", "p": "On a town map, the school is at the origin and each unit is 1 km. Home is at (−3, 4), the library at (5, 4) and the market at (5, −2). Roads run along grid lines.", "tag": "", "marks": "", "flat": [{"t": "Home to library = __B1__ km", "a": {"B1": "8"}}, {"t": "Library to market = __B1__ km", "a": {"B1": "6"}}, {"t": "Total journey = __B1__ km", "a": {"B1": "14"}}], "sol": "Same y: from x = −3 to x = 5 is 8 km.\nSame x: from y = 4 to y = −2 is 6 km.\n8 + 6 = 14 km."}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-myp2-u3';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Integers</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = '<button class="tab-btn'+(activeTab==='theory'?' active':'')+'" data-tab="theory">Theory<span class="tab-count">notes</span></button>' + TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('') + '<button class="tab-btn'+(activeTab==='report'?' active':'')+'" data-tab="report">📊 Report<span class="tab-count">pie</span></button>';
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d','e','f'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — you can answer it now: fill it in and press <b>Check</b>, or come back later from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+((item.status!=='unanswered'&&item.status!=='skipped')?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  if(item.status==='skipped') item.status='unanswered';
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick); activeTab='theory';
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };


/* ================= theory tab ================= */
function renderTheory(){
  var wrap=document.getElementById('wrap');
  wrap.innerHTML='<div class="theory">'+fr(THEORY)+'</div>';
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Theory — notes, key ideas and worked examples';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
  wrap.querySelectorAll('[data-jump]').forEach(function(b){ b.addEventListener('click',function(){ var t=document.getElementById(b.dataset.jump); if(t) t.scrollIntoView({behavior:'smooth',block:'start'}); }); });
}
var _rsTheory = renderSlide;
renderSlide = function(){
  if(activeTab==='theory'){ renderTheory(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  document.querySelector('.slide-progress').style.display='';
  document.querySelector('.navbar').style.display='';
  document.getElementById('paletteFab').style.display='';
  _rsTheory();
};


/* ================= MYP criterion report ================= */
var CRIT_COL={A:'var(--accent-text)',B:'var(--gold)',C:'#8A6FC4',D:'#2F9AA0'};
function critStats(){
  return REPORT.map(function(r){
    var tabId=r[0], slides=SLIDES[tabId], ts=state&&state.tabs[tabId];
    var c=0,w=0,n=0;
    slides.forEach(function(sl,i){
      if(!ts||!ts.items[i]){ n++; return; }
      var it=ts.items[i];
      if(MODE==='learning'){
        if(it.status==='correct') c++; else if(it.status==='revealed') w++; else n++;
      } else {
        if(isSlideCorrect(tabId,i)) c++; else if(isSlideAttempted(tabId,i)) w++; else n++;
      }
    });
    var tot=slides.length, pct=tot?Math.round(c/tot*100):0;
    var lvl=Math.round(c/Math.max(tot,1)*8);
    return {tab:tabId,letter:r[1],name:r[2],c:c,w:w,n:n,tot:tot,pct:pct,lvl:lvl};
  });
}
function arcPath(cx,cy,r,a0,a1){
  if(a1-a0>=Math.PI*2-1e-6){ return 'M'+(cx-r)+','+cy+' a'+r+','+r+' 0 1,0 '+(2*r)+',0 a'+r+','+r+' 0 1,0 '+(-2*r)+',0 Z'; }
  var x0=cx+r*Math.sin(a0), y0=cy-r*Math.cos(a0), x1=cx+r*Math.sin(a1), y1=cy-r*Math.cos(a1);
  return 'M'+cx+','+cy+' L'+x0.toFixed(2)+','+y0.toFixed(2)+' A'+r+','+r+' 0 '+((a1-a0)>Math.PI?1:0)+',1 '+x1.toFixed(2)+','+y1.toFixed(2)+' Z';
}
function pieSVG(parts,size,hole,center,sub){
  var tot=parts.reduce(function(s,p){return s+p.v;},0), cx=size/2, cy=size/2, r=size/2-4, a=0, h='';
  if(!tot){ h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+r+'" style="fill:var(--paper-2);stroke:var(--rule)"/>'; }
  parts.forEach(function(p){ if(!p.v) return; var b=a+p.v/tot*Math.PI*2; h+='<path d="'+arcPath(cx,cy,r,a,b)+'" style="fill:'+p.col+';stroke:var(--card);stroke-width:2"><title>'+esc(p.label)+': '+p.v+'</title></path>'; a=b; });
  if(hole) h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+(r*hole)+'" style="fill:var(--card)"/>';
  if(center) h+='<text x="'+cx+'" y="'+(cy-(sub?4:0))+'" text-anchor="middle" dominant-baseline="middle" style="fill:var(--ink);font:700 '+(size>150?22:15)+'px Fraunces,serif">'+center+'</text>';
  if(sub) h+='<text x="'+cx+'" y="'+(cy+16)+'" text-anchor="middle" style="fill:var(--ink-soft);font:600 11px \'Source Sans 3\',sans-serif">'+sub+'</text>';
  return '<svg viewBox="0 0 '+size+' '+size+'" width="'+size+'" height="'+size+'" role="img">'+h+'</svg>';
}
function band(l){ return l===0?'0':(l<=2?'1–2':(l<=4?'3–4':(l<=6?'5–6':'7–8'))); }
function renderReport(){
  var st=critStats(), totC=0, totQ=0;
  st.forEach(function(s){ totC+=s.c; totQ+=s.tot; });
  var h='<div class="theory">';
  h+='<section class="note"><h2>Chapter test report</h2><p class="lt">'+(MODE==='quiz'?'<b>Quiz mode</b> results: answers are marked when you finish each test tab.':'<b>Learning mode</b> results: a question counts as correct only if you got it without the answer being revealed. Switch to Quiz mode for an exam-style score.')+'</p>';
  h+='<div class="rep-top"><div class="rep-pie">'+pieSVG(st.map(function(s){return {v:s.c,col:CRIT_COL[s.letter],label:'Criterion '+s.letter};}),200,0.55,totC+'/'+totQ,'correct')+'</div>';
  h+='<div class="rep-legend"><div class="rep-cap">Marks earned, by criterion</div>'+st.map(function(s){ return '<div class="rep-li"><span class="sw" style="background:'+CRIT_COL[s.letter]+'"></span><b>'+s.letter+'</b>&nbsp;'+esc(s.name)+'<span class="rep-n">'+s.c+' / '+s.tot+'</span></div>'; }).join('')+'</div></div></section>';
  h+='<div class="rep-grid">'+st.map(function(s){
    return '<div class="rep-card"><div class="rep-h"><span class="crit" style="background:'+CRIT_COL[s.letter]+'">'+s.letter+'</span>'+esc(s.name)+'</div>'+
      '<div class="rep-row">'+pieSVG([{v:s.c,col:'var(--success)',label:'Correct'},{v:s.w,col:'var(--danger)',label:'Incorrect'},{v:s.n,col:'var(--locked)',label:'Not attempted'}],120,0.5,s.pct+'%')+
      '<div class="rep-stats"><div><span class="sw" style="background:var(--success)"></span>Correct <b>'+s.c+'</b></div><div><span class="sw" style="background:var(--danger)"></span>Incorrect <b>'+s.w+'</b></div><div><span class="sw" style="background:var(--locked)"></span>Not attempted <b>'+s.n+'</b></div>'+
      '<div class="rep-lvl">Indicative level <b>'+s.lvl+'</b> / 8 <span>(band '+band(s.lvl)+')</span></div></div></div>'+
      '<button class="hub-btn" data-go="'+s.tab+'">Open Test '+s.letter+' →</button></div>';
  }).join('')+'</div>';
  h+='<p class="rep-note">Indicative level = fraction of questions correct × 8, rounded. It is a practice guide only; your teacher awards the real MYP criterion levels.</p></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Report — chapter test results by MYP criterion';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
}
var _rsReport = renderSlide;
renderSlide = function(){
  if(activeTab==='report'){ renderReport(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  _rsReport();
};


/* ================= skipped-question return ================= */
function firstSkippedIdx(ts){
  for(var i=0;i<ts.items.length;i++){
    var it=ts.items[i];
    if(MODE==='quiz'){ if(!isSlideAttempted(activeTab,i)) return i; }
    else if(it.status==='skipped'||it.status==='unanswered') return i;
  }
  return -1;
}
function skippedList(ts){
  var out=[]; for(var i=0;i<ts.items.length;i++){ var it=ts.items[i];
    if(MODE==='quiz' ? !isSlideAttempted(activeTab,i) : (it.status==='skipped'||it.status==='unanswered')) out.push(i); }
  return out;
}
function renderSkipGate(ts){
  var list=skippedList(ts);
  var h='<div class="qcard done-card"><div class="big">⏭️</div><h2>You skipped '+list.length+' question'+(list.length>1?'s':'')+'</h2>'+
    '<p style="color:var(--ink-soft);font-size:14px;">Answer them now, or submit the tab as it is. Answers are marked only when you submit.</p>'+
    '<div class="skip-chips">'+list.map(function(i){ return '<button class="chip skip-go" data-i="'+i+'">Q'+(i+1)+'</button>'; }).join('')+'</div>'+
    '<div class="skip-btns"><button class="btn btn-primary" id="btnGoSkipped">Answer skipped questions</button><button class="btn" id="btnSubmitAnyway">Submit anyway</button></div></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  var go=function(i){ ts.idx=i; ts.maxReached=Math.max(ts.maxReached,i); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); };
  document.getElementById('btnGoSkipped').addEventListener('click',function(){ go(list[0]); });
  document.querySelectorAll('.skip-go').forEach(function(b){ b.addEventListener('click',function(){ go(parseInt(b.dataset.i,10)); }); });
  document.getElementById('btnSubmitAnyway').addEventListener('click',function(){ ts.submitOK=true; renderFinished(); ts.submitOK=false; });
  saveState();
}
var _rfSkip = renderFinished;
renderFinished = function(){
  var ts=state.tabs[activeTab];
  if(MODE==='quiz' && !ts.submitOK && skippedList(ts).length){ renderSkipGate(ts); return; }
  _rfSkip();
  if(MODE==='learning'){
    var list=skippedList(ts);
    if(list.length){
      var card=document.querySelector('.done-card');
      if(card){ var d=document.createElement('div'); d.className='skip-btns';
        d.innerHTML='<button class="btn btn-primary" id="btnGoSkipped">Attempt skipped questions ('+list.length+')</button>';
        card.appendChild(d);
        document.getElementById('btnGoSkipped').addEventListener('click',function(){ ts.idx=list[0]; ts.recorded=false; renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); }
    }
  }
};

renderLogin();
})();
</script>
</body>
</html>

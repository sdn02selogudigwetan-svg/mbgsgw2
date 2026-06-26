<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pembukuan Insentif MBG SGW 2</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@3.19.0/dist/tabler-icons.min.css">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --primary: #1a3a5c;
    --primary-light: #1e4976;
    --accent: #2ecc8f;
    --accent-dark: #25a873;
    --income: #27ae60;
    --income-bg: #e8f8f0;
    --expense: #e74c3c;
    --expense-bg: #fdecea;
    --balance: #2980b9;
    --balance-bg: #e8f4fc;
    --sidebar-w: 240px;
    --header-h: 60px;
    --bg: #f0f4f8;
    --surface: #ffffff;
    --border: #dde3eb;
    --text: #1a2535;
    --text-muted: #637086;
    --radius: 10px;
    --shadow: 0 2px 8px rgba(0,0,0,0.08);
  }
  body { font-family: 'Segoe UI', system-ui, sans-serif; background: var(--bg); color: var(--text); display: flex; flex-direction: column; min-height: 100vh; }

  /* ===== LOGIN SCREEN ===== */
  #loginScreen {
    position: fixed; inset: 0; z-index: 9999;
    background: linear-gradient(135deg, #0f2440 0%, #1a3a5c 50%, #1e5799 100%);
    display: flex; align-items: center; justify-content: center;
  }
  #loginScreen.hidden { display: none; }

  .login-bg-decor {
    position: absolute; inset: 0; overflow: hidden; pointer-events: none;
  }
  .login-bg-decor span {
    position: absolute; border-radius: 50%;
    background: rgba(46,204,143,0.06);
    animation: floatCircle 8s ease-in-out infinite;
  }
  .login-bg-decor span:nth-child(1) { width: 320px; height: 320px; top: -80px; right: -80px; animation-delay: 0s; }
  .login-bg-decor span:nth-child(2) { width: 200px; height: 200px; bottom: 60px; left: -60px; animation-delay: 3s; }
  .login-bg-decor span:nth-child(3) { width: 150px; height: 150px; top: 40%; right: 10%; animation-delay: 5s; }
  @keyframes floatCircle {
    0%, 100% { transform: translateY(0) scale(1); }
    50% { transform: translateY(-20px) scale(1.05); }
  }

  .login-card {
    position: relative; z-index: 1;
    background: #fff; border-radius: 16px;
    padding: 40px 36px; width: 380px; max-width: 94vw;
    box-shadow: 0 24px 64px rgba(0,0,0,0.28);
    animation: loginSlideUp 0.4s cubic-bezier(.22,.68,0,1.2);
  }
  @keyframes loginSlideUp {
    from { opacity: 0; transform: translateY(30px) scale(0.97); }
    to { opacity: 1; transform: translateY(0) scale(1); }
  }

  .login-logo {
    display: flex; flex-direction: column; align-items: center; margin-bottom: 28px;
  }
  .login-logo-icon {
    width: 64px; height: 64px; background: var(--primary);
    border-radius: 16px; display: flex; align-items: center; justify-content: center;
    font-size: 30px; color: #fff; margin-bottom: 14px;
    box-shadow: 0 8px 20px rgba(26,58,92,0.35);
  }
  .login-logo h1 { font-size: 17px; font-weight: 800; color: var(--primary); text-align: center; }
  .login-logo p { font-size: 12px; color: var(--text-muted); margin-top: 4px; text-align: center; }

  .login-divider {
    height: 1px; background: var(--border); margin: 0 0 24px;
  }

  .login-field { margin-bottom: 16px; }
  .login-field label {
    display: block; font-size: 12px; font-weight: 700;
    color: var(--text-muted); text-transform: uppercase; letter-spacing: 0.6px;
    margin-bottom: 6px;
  }
  .login-input-wrap {
    position: relative;
  }
  .login-input-wrap i {
    position: absolute; left: 12px; top: 50%; transform: translateY(-50%);
    font-size: 17px; color: var(--text-muted);
    pointer-events: none;
  }
  .login-field input {
    width: 100%; padding: 10px 12px 10px 38px;
    border: 1.5px solid var(--border); border-radius: 9px;
    font-size: 14px; color: var(--text); background: #f9fbfd;
    outline: none; transition: border-color 0.2s, box-shadow 0.2s;
  }
  .login-field input:focus {
    border-color: var(--primary); background: #fff;
    box-shadow: 0 0 0 3px rgba(26,58,92,0.1);
  }
  .toggle-pw {
    position: absolute; right: 10px; top: 50%; transform: translateY(-50%);
    background: none; border: none; cursor: pointer;
    color: var(--text-muted); font-size: 17px; padding: 4px;
    display: flex; align-items: center;
  }
  .toggle-pw:hover { color: var(--primary); }

  .login-error {
    background: var(--expense-bg); border: 1px solid #f5c6c2;
    color: var(--expense); border-radius: 8px; padding: 10px 12px;
    font-size: 13px; margin-bottom: 14px; display: none;
    align-items: center; gap: 8px;
  }
  .login-error.show { display: flex; }

  .btn-login {
    width: 100%; padding: 12px; background: var(--primary); color: #fff;
    border: none; border-radius: 9px; font-size: 14px; font-weight: 700;
    cursor: pointer; letter-spacing: 0.3px; margin-top: 4px;
    transition: background 0.2s, transform 0.1s, box-shadow 0.2s;
    display: flex; align-items: center; justify-content: center; gap: 8px;
  }
  .btn-login:hover { background: var(--primary-light); box-shadow: 0 6px 18px rgba(26,58,92,0.3); }
  .btn-login:active { transform: scale(0.98); }
  .btn-login:disabled { opacity: 0.6; cursor: not-allowed; }

  .login-hint {
    margin-top: 20px; padding: 12px; background: #f5f8fc;
    border-radius: 8px; border: 1px solid var(--border);
    font-size: 12px; color: var(--text-muted); text-align: center;
  }
  .login-hint strong { color: var(--primary); }

  /* ===== LOGOUT MODAL ===== */
  #logoutModal {
    position: fixed; inset: 0; z-index: 9998;
    background: rgba(0,0,0,0.45); backdrop-filter: blur(3px);
    display: none; align-items: center; justify-content: center;
  }
  #logoutModal.show { display: flex; }
  .modal-card {
    background: #fff; border-radius: 14px; padding: 32px 28px;
    width: 340px; max-width: 90vw;
    box-shadow: 0 20px 50px rgba(0,0,0,0.25);
    animation: loginSlideUp 0.25s ease;
    text-align: center;
  }
  .modal-icon {
    width: 56px; height: 56px; background: var(--expense-bg);
    border-radius: 50%; display: flex; align-items: center; justify-content: center;
    margin: 0 auto 16px; font-size: 26px; color: var(--expense);
  }
  .modal-card h3 { font-size: 17px; font-weight: 700; color: var(--text); margin-bottom: 8px; }
  .modal-card p { font-size: 13px; color: var(--text-muted); line-height: 1.5; }
  .modal-actions { display: flex; gap: 10px; margin-top: 22px; }
  .btn-modal-cancel {
    flex: 1; padding: 10px; border: 1.5px solid var(--border);
    border-radius: 8px; background: none; color: var(--text-muted);
    font-size: 13px; font-weight: 600; cursor: pointer; transition: all 0.2s;
  }
  .btn-modal-cancel:hover { border-color: var(--primary); color: var(--primary); }
  .btn-modal-logout {
    flex: 1; padding: 10px; border: none;
    border-radius: 8px; background: var(--expense); color: #fff;
    font-size: 13px; font-weight: 700; cursor: pointer; transition: background 0.2s;
    display: flex; align-items: center; justify-content: center; gap: 6px;
  }
  .btn-modal-logout:hover { background: #c0392b; }

  /* ===== TOAST ===== */
  #toast {
    position: fixed; bottom: 24px; left: 50%; transform: translateX(-50%) translateY(20px);
    background: #1a2535; color: #fff; padding: 12px 20px; border-radius: 10px;
    font-size: 13px; font-weight: 500; z-index: 9997;
    display: flex; align-items: center; gap: 8px;
    opacity: 0; transition: opacity 0.3s, transform 0.3s;
    pointer-events: none; white-space: nowrap;
  }
  #toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }
  #toast i { font-size: 16px; }
  #toast.success i { color: var(--accent); }
  #toast.error i { color: var(--expense); }

  /* ===== APP (hidden until login) ===== */
  #appWrapper { display: none; flex-direction: column; min-height: 100vh; }
  #appWrapper.visible { display: flex; }

  /* HEADER */
  header {
    position: fixed; top: 0; left: 0; right: 0; height: var(--header-h);
    background: var(--primary); color: #fff;
    display: flex; align-items: center; justify-content: space-between;
    padding: 0 1rem; z-index: 100;
    box-shadow: 0 2px 10px rgba(0,0,0,0.2);
  }
  .header-left { display: flex; align-items: center; gap: 12px; }
  #toggleSidebar {
    background: none; border: none; color: #fff; cursor: pointer;
    font-size: 22px; padding: 6px; border-radius: 6px;
    display: flex; align-items: center;
    transition: background 0.2s;
  }
  #toggleSidebar:hover { background: rgba(255,255,255,0.15); }
  .header-title { font-size: 15px; font-weight: 700; letter-spacing: 0.3px; }
  .header-title span { color: var(--accent); }
  .header-right { display: flex; align-items: center; gap: 10px; }
  .user-btn {
    display: flex; align-items: center; gap: 8px;
    background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.2);
    color: #fff; padding: 6px 12px; border-radius: 8px;
    font-size: 13px; font-weight: 500;
  }
  .avatar { width: 28px; height: 28px; background: var(--accent); border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 12px; font-weight: 700; color: #fff; }
  #headerUsername { font-size: 13px; }
  .logout-btn {
    display: flex; align-items: center; gap: 6px;
    background: rgba(231,76,60,0.15); border: 1px solid rgba(231,76,60,0.35);
    color: #ffadad; padding: 6px 10px; border-radius: 8px; cursor: pointer;
    font-size: 12px; font-weight: 500; transition: background 0.2s;
  }
  .logout-btn:hover { background: rgba(231,76,60,0.3); }

  /* LAYOUT */
  .layout { display: flex; margin-top: var(--header-h); min-height: calc(100vh - var(--header-h)); }

  /* SIDEBAR */
  aside {
    width: var(--sidebar-w); background: var(--primary);
    position: fixed; top: var(--header-h); left: 0; bottom: 0;
    overflow-y: auto; transition: transform 0.3s ease;
    z-index: 90; display: flex; flex-direction: column;
  }
  aside.collapsed { transform: translateX(-100%); }
  .sidebar-section { padding: 12px 0 4px; }
  .sidebar-label {
    font-size: 10px; font-weight: 700; color: rgba(255,255,255,0.35);
    letter-spacing: 1.2px; text-transform: uppercase;
    padding: 0 16px 6px;
  }
  .nav-item {
    display: flex; align-items: center; gap: 10px;
    padding: 10px 16px; color: rgba(255,255,255,0.75);
    cursor: pointer; font-size: 13.5px; font-weight: 500;
    border-left: 3px solid transparent;
    transition: all 0.18s; user-select: none;
  }
  .nav-item:hover { background: rgba(255,255,255,0.08); color: #fff; }
  .nav-item.active { background: rgba(46,204,143,0.12); color: var(--accent); border-left-color: var(--accent); }
  .nav-item i { font-size: 17px; width: 20px; flex-shrink: 0; }
  .nav-chevron { margin-left: auto; font-size: 13px; transition: transform 0.2s; }
  .nav-item.open .nav-chevron { transform: rotate(180deg); }
  .sub-menu { overflow: hidden; max-height: 0; transition: max-height 0.3s ease; background: rgba(0,0,0,0.15); }
  .sub-menu.open { max-height: 200px; }
  .sub-item {
    display: flex; align-items: center; gap: 10px;
    padding: 9px 16px 9px 44px; color: rgba(255,255,255,0.65);
    cursor: pointer; font-size: 13px;
    border-left: 3px solid transparent;
    transition: all 0.15s;
  }
  .sub-item:hover { color: #fff; background: rgba(255,255,255,0.06); }
  .sub-item.active { color: var(--accent); border-left-color: var(--accent); background: rgba(46,204,143,0.08); }
  .sub-item i { font-size: 15px; }
  aside .sidebar-bottom { margin-top: auto; padding: 12px 16px; border-top: 1px solid rgba(255,255,255,0.1); }
  .sidebar-bottom p { font-size: 11px; color: rgba(255,255,255,0.3); text-align: center; }

  /* MAIN */
  main {
    margin-left: var(--sidebar-w); flex: 1; padding: 24px;
    transition: margin-left 0.3s ease;
    min-height: calc(100vh - var(--header-h));
    display: flex; flex-direction: column;
  }
  main.full { margin-left: 0; }

  /* STATS CARDS */
  .stats-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px; margin-bottom: 24px; }
  .stat-card {
    background: var(--surface); border-radius: var(--radius);
    padding: 18px 20px; border: 1px solid var(--border);
    box-shadow: var(--shadow); display: flex; align-items: center; gap: 16px;
    position: relative; overflow: hidden;
  }
  .stat-card::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 3px; }
  .stat-card.income::before { background: var(--income); }
  .stat-card.expense::before { background: var(--expense); }
  .stat-card.balance::before { background: var(--balance); }
  .stat-icon { width: 48px; height: 48px; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 22px; flex-shrink: 0; }
  .stat-card.income .stat-icon { background: var(--income-bg); color: var(--income); }
  .stat-card.expense .stat-icon { background: var(--expense-bg); color: var(--expense); }
  .stat-card.balance .stat-icon { background: var(--balance-bg); color: var(--balance); }
  .stat-info { flex: 1; }
  .stat-label { font-size: 12px; color: var(--text-muted); font-weight: 600; letter-spacing: 0.4px; text-transform: uppercase; }
  .stat-value { font-size: 22px; font-weight: 700; margin-top: 3px; }
  .stat-card.income .stat-value { color: var(--income); }
  .stat-card.expense .stat-value { color: var(--expense); }
  .stat-card.balance .stat-value { color: var(--balance); }

  /* CONTENT CARD */
  .content-card {
    background: var(--surface); border-radius: var(--radius);
    border: 1px solid var(--border); box-shadow: var(--shadow);
    flex: 1; display: flex; flex-direction: column;
  }
  .card-header {
    padding: 16px 20px; border-bottom: 1px solid var(--border);
    display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 10px;
  }
  .card-title { display: flex; align-items: center; gap: 10px; }
  .card-title i { font-size: 20px; color: var(--primary); }
  .card-title h2 { font-size: 15px; font-weight: 700; color: var(--text); }
  .card-actions { display: flex; gap: 8px; align-items: center; }
  .btn-add {
    display: flex; align-items: center; gap: 6px;
    background: var(--primary); color: #fff; border: none;
    padding: 8px 14px; border-radius: 8px; cursor: pointer;
    font-size: 13px; font-weight: 600; transition: background 0.2s;
  }
  .btn-add:hover { background: var(--primary-light); }
  .btn-add.green { background: var(--income); }
  .btn-add.green:hover { background: var(--accent-dark); }
  .btn-export {
    display: flex; align-items: center; gap: 6px;
    background: none; color: var(--text-muted); border: 1px solid var(--border);
    padding: 8px 12px; border-radius: 8px; cursor: pointer;
    font-size: 13px; font-weight: 500; transition: all 0.2s;
  }
  .btn-export:hover { border-color: var(--primary); color: var(--primary); }

  /* TABLE */
  .table-wrap { overflow-x: auto; flex: 1; }
  table { width: 100%; border-collapse: collapse; font-size: 13px; }
  thead tr { background: #f5f8fc; }
  th {
    padding: 11px 14px; text-align: left; font-weight: 700; font-size: 12px;
    color: var(--text-muted); text-transform: uppercase; letter-spacing: 0.5px;
    border-bottom: 1px solid var(--border); white-space: nowrap;
  }
  td { padding: 11px 14px; border-bottom: 1px solid #eef1f5; vertical-align: middle; }
  tbody tr:hover { background: #fafbfd; }
  tbody tr:last-child td { border-bottom: none; }
  .no-data { text-align: center; padding: 40px; color: var(--text-muted); }
  .no-data i { font-size: 40px; display: block; margin-bottom: 10px; opacity: 0.4; }
  .badge-no { display: inline-block; background: #eef1f5; color: var(--text-muted); padding: 2px 8px; border-radius: 5px; font-weight: 600; font-size: 11px; }
  .income-val { color: var(--income); font-weight: 600; }
  .expense-val { color: var(--expense); font-weight: 600; }
  .saldo-val { color: var(--balance); font-weight: 700; }
  .action-btn {
    background: none; border: none; cursor: pointer; padding: 4px 6px;
    border-radius: 5px; font-size: 15px; transition: background 0.15s;
    color: var(--text-muted);
  }
  .action-btn.del:hover { background: var(--expense-bg); color: var(--expense); }

  /* FORM ROW */
  .form-row { background: #f0f8ff; border-top: 1px solid #cce4f5; padding: 12px 14px; display: none; animation: slideDown 0.2s ease; }
  .form-row.show { display: table-row; }
  @keyframes slideDown { from { opacity: 0; transform: translateY(-4px); } to { opacity: 1; transform: translateY(0); } }
  .form-row td { padding: 10px 14px; }
  .form-inner { display: flex; gap: 8px; align-items: center; flex-wrap: wrap; }
  .form-inner input, .form-inner select {
    padding: 7px 10px; border: 1px solid var(--border); border-radius: 7px;
    font-size: 13px; background: #fff; color: var(--text);
    outline: none; transition: border-color 0.15s;
  }
  .form-inner input:focus, .form-inner select:focus { border-color: var(--primary); }
  .form-inner input[type="date"] { width: 140px; }
  .form-inner input[name="nokwitansi"] { width: 130px; }
  .form-inner input[name="uraian"] { flex: 1; min-width: 180px; }
  .form-inner input[name="nominal"] { width: 150px; }
  .btn-save {
    background: var(--income); color: #fff; border: none;
    padding: 7px 14px; border-radius: 7px; cursor: pointer;
    font-size: 13px; font-weight: 600; display: flex; align-items: center; gap: 5px;
    transition: background 0.2s;
  }
  .btn-save:hover { background: var(--accent-dark); }
  .btn-cancel {
    background: none; color: var(--text-muted); border: 1px solid var(--border);
    padding: 7px 12px; border-radius: 7px; cursor: pointer;
    font-size: 13px; transition: all 0.2s;
  }
  .btn-cancel:hover { border-color: var(--expense); color: var(--expense); }

  /* LAPORAN */
  .laporan-footer {
    padding: 14px 20px; border-top: 2px solid var(--primary);
    background: #f5f8fc; border-radius: 0 0 var(--radius) var(--radius);
    display: flex; justify-content: flex-end; align-items: center; gap: 24px;
  }
  .footer-item { text-align: right; }
  .footer-item .fl { font-size: 11px; color: var(--text-muted); font-weight: 600; text-transform: uppercase; letter-spacing: 0.4px; }
  .footer-item .fv { font-size: 16px; font-weight: 800; }
  .footer-item .fv.inc { color: var(--income); }
  .footer-item .fv.exp { color: var(--expense); }
  .footer-item .fv.bal { color: var(--balance); }

  /* PAGE SECTIONS */
  .page { display: none; flex-direction: column; gap: 0; flex: 1; }
  .page.active { display: flex; flex-direction: column; gap: 0; }

  /* FOOTER */
  .app-footer {
    margin-top: auto; padding: 14px 20px;
    text-align: center; font-size: 11.5px; color: var(--text-muted);
    border-top: 1px solid var(--border); margin-left: var(--sidebar-w);
    background: var(--surface); transition: margin-left 0.3s;
  }
  .app-footer.full { margin-left: 0; }
  .app-footer strong { color: var(--primary); }

  /* WELCOME */
  .welcome-banner {
    background: linear-gradient(135deg, var(--primary) 0%, #2563a8 100%);
    border-radius: var(--radius); padding: 28px 28px; color: #fff;
    margin-bottom: 24px; position: relative; overflow: hidden;
  }
  .welcome-banner::after {
    content: ''; position: absolute; right: -20px; top: -20px;
    width: 160px; height: 160px; background: rgba(255,255,255,0.05);
    border-radius: 50%;
  }
  .welcome-banner h1 { font-size: 20px; font-weight: 700; }
  .welcome-banner h1 span { color: var(--accent); }
  .welcome-banner p { margin-top: 6px; font-size: 13.5px; color: rgba(255,255,255,0.75); }

  @media (max-width: 768px) {
    .stats-grid { grid-template-columns: 1fr; }
    aside { transform: translateX(-100%); }
    aside.collapsed { transform: translateX(-100%); }
    aside.open { transform: translateX(0); }
    main, .app-footer { margin-left: 0 !important; }
    .form-inner input[name="uraian"] { min-width: 120px; }
  }
</style>
</head>
<body>

<!-- ===== LOGIN SCREEN ===== -->
<div id="loginScreen">
  <div class="login-bg-decor">
    <span></span><span></span><span></span>
  </div>
  <div class="login-card">
    <div class="login-logo">
      <div class="login-logo-icon"><i class="ti ti-book-2"></i></div>
      <h1>Pembukuan Insentif MBG</h1>
      <p>SGW 2 — Sistem Manajemen Keuangan</p>
    </div>
    <div class="login-divider"></div>

    <div class="login-error" id="loginError">
      <i class="ti ti-alert-circle"></i>
      <span id="loginErrorMsg">Username atau password salah.</span>
    </div>

    <div class="login-field">
      <label>Username</label>
      <div class="login-input-wrap">
        <i class="ti ti-user"></i>
        <input type="text" id="loginUsername" placeholder="Masukkan username" autocomplete="username" onkeydown="handleLoginKey(event)">
      </div>
    </div>

    <div class="login-field">
      <label>Password</label>
      <div class="login-input-wrap">
        <i class="ti ti-lock"></i>
        <input type="password" id="loginPassword" placeholder="Masukkan password" autocomplete="current-password" onkeydown="handleLoginKey(event)">
        <button class="toggle-pw" type="button" onclick="togglePassword()" title="Tampilkan/Sembunyikan Password">
          <i class="ti ti-eye" id="eyeIcon"></i>
        </button>
      </div>
    </div>

    <button class="btn-login" id="btnLogin" onclick="doLogin()">
      <i class="ti ti-login"></i> Masuk
    </button>

    <div class="login-hint">
      Demo: <strong>admin</strong> / <strong>12345</strong>
    </div>
  </div>
</div>

<!-- ===== LOGOUT MODAL ===== -->
<div id="logoutModal">
  <div class="modal-card">
    <div class="modal-icon"><i class="ti ti-logout"></i></div>
    <h3>Konfirmasi Keluar</h3>
    <p>Apakah Anda yakin ingin keluar dari sistem? Sesi Anda akan diakhiri.</p>
    <div class="modal-actions">
      <button class="btn-modal-cancel" onclick="closeLogoutModal()">Batal</button>
      <button class="btn-modal-logout" onclick="doLogout()">
        <i class="ti ti-logout"></i> Keluar
      </button>
    </div>
  </div>
</div>

<!-- ===== TOAST ===== -->
<div id="toast"><i class="ti ti-check"></i> <span id="toastMsg"></span></div>

<!-- ===== APP WRAPPER ===== -->
<div id="appWrapper">

  <!-- HEADER -->
  <header>
    <div class="header-left">
      <button id="toggleSidebar" title="Menu"><i class="ti ti-menu-2"></i></button>
      <span class="header-title">PEMBUKUAN <span>INSENTIF MBG SGW 2</span></span>
    </div>
    <div class="header-right">
      <div class="user-btn">
        <div class="avatar" id="headerAvatar">AD</div>
        <span id="headerUsername">Admin</span>
      </div>
      <button class="logout-btn" onclick="openLogoutModal()">
        <i class="ti ti-logout"></i> Keluar
      </button>
    </div>
  </header>

  <!-- LAYOUT -->
  <div class="layout">

    <!-- SIDEBAR -->
    <aside id="sidebar">
      <div class="sidebar-section">
        <div class="nav-item active" onclick="showPage('dashboard')">
          <i class="ti ti-dashboard"></i> Beranda
        </div>
      </div>

      <div class="sidebar-section">
        <div class="sidebar-label">Transaksi</div>
        <div class="nav-item" id="navInputData" onclick="toggleMenu('menuInputData', this)">
          <i class="ti ti-database-import"></i> Input Data
          <i class="ti ti-chevron-down nav-chevron"></i>
        </div>
        <div class="sub-menu" id="menuInputData">
          <div class="sub-item" id="subPemasukan" onclick="showPage('pemasukan')">
            <i class="ti ti-trending-up"></i> Pemasukan
          </div>
          <div class="sub-item" id="subPengeluaran" onclick="showPage('pengeluaran')">
            <i class="ti ti-trending-down"></i> Pengeluaran
          </div>
        </div>
      </div>

      <div class="sidebar-section">
        <div class="sidebar-label">Rekap</div>
        <div class="nav-item" id="navLaporan" onclick="showPage('laporan')">
          <i class="ti ti-file-report"></i> Laporan
        </div>
      </div>

      <div class="sidebar-bottom">
        <p>© 2025 MBG SGW 2</p>
      </div>
    </aside>

    <!-- MAIN -->
    <main id="mainContent">

      <!-- STATS -->
      <div class="stats-grid">
        <div class="stat-card income">
          <div class="stat-icon"><i class="ti ti-trending-up"></i></div>
          <div class="stat-info">
            <div class="stat-label">Total Pemasukan</div>
            <div class="stat-value" id="statIncome">Rp 0</div>
          </div>
        </div>
        <div class="stat-card expense">
          <div class="stat-icon"><i class="ti ti-trending-down"></i></div>
          <div class="stat-info">
            <div class="stat-label">Total Pengeluaran</div>
            <div class="stat-value" id="statExpense">Rp 0</div>
          </div>
        </div>
        <div class="stat-card balance">
          <div class="stat-icon"><i class="ti ti-wallet"></i></div>
          <div class="stat-info">
            <div class="stat-label">Saldo Akhir</div>
            <div class="stat-value" id="statBalance">Rp 0</div>
          </div>
        </div>
      </div>

      <!-- DASHBOARD PAGE -->
      <div class="page active" id="pageDashboard">
        <div class="welcome-banner">
          <h1>Selamat Datang, <span id="welcomeName">Admin</span>!</h1>
          <p>Kelola pemasukan dan pengeluaran Insentif MBG SGW 2 dengan mudah dan terstruktur.</p>
        </div>
        <div class="content-card" style="padding: 24px; align-items: center; justify-content: center; min-height: 200px;">
          <div style="text-align: center; color: var(--text-muted);">
            <i class="ti ti-chart-pie" style="font-size: 48px; opacity: 0.3; display: block; margin-bottom: 12px;"></i>
            <p style="font-size: 15px; font-weight: 600;">Pilih menu di sidebar untuk mulai</p>
            <p style="font-size: 13px; margin-top: 6px;">Input data pemasukan, pengeluaran, atau lihat laporan lengkap.</p>
          </div>
        </div>
      </div>

      <!-- PEMASUKAN PAGE -->
      <div class="page" id="pagePemasukan">
        <div class="content-card">
          <div class="card-header">
            <div class="card-title">
              <i class="ti ti-trending-up" style="color: var(--income);"></i>
              <h2>Data Pemasukan</h2>
            </div>
            <div class="card-actions">
              <button class="btn-export" onclick="exportCSV('pemasukan')"><i class="ti ti-download"></i> Ekspor</button>
              <button class="btn-add green" id="btnAddPemasukan" onclick="toggleForm('pemasukan')"><i class="ti ti-plus"></i> Tambah</button>
            </div>
          </div>
          <div class="table-wrap">
            <table id="tablePemasukan">
              <thead>
                <tr>
                  <th>No.</th><th>Tanggal</th><th>No. Kwitansi</th><th>Uraian</th>
                  <th>Pemasukan (Rp)</th><th>Saldo (Rp)</th><th>Aksi</th>
                </tr>
              </thead>
              <tbody id="tbodyPemasukan">
                <tr id="formRowPemasukan" class="form-row">
                  <td colspan="7">
                    <div class="form-inner">
                      <input type="date" name="tanggal" id="pTanggal">
                      <input type="text" name="nokwitansi" id="pKwitansi" placeholder="No. Kwitansi">
                      <input type="text" name="uraian" id="pUraian" placeholder="Uraian / Keterangan">
                      <input type="number" name="nominal" id="pNominal" placeholder="Jumlah (Rp)">
                      <button class="btn-save" onclick="saveEntry('pemasukan')"><i class="ti ti-check"></i> Simpan</button>
                      <button class="btn-cancel" onclick="toggleForm('pemasukan')">Batal</button>
                    </div>
                  </td>
                </tr>
                <tr id="noDataPemasukan">
                  <td colspan="7" class="no-data">
                    <i class="ti ti-inbox"></i>
                    Belum ada data pemasukan. Klik "Tambah" untuk menambahkan.
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- PENGELUARAN PAGE -->
      <div class="page" id="pagePengeluaran">
        <div class="content-card">
          <div class="card-header">
            <div class="card-title">
              <i class="ti ti-trending-down" style="color: var(--expense);"></i>
              <h2>Data Pengeluaran</h2>
            </div>
            <div class="card-actions">
              <button class="btn-export" onclick="exportCSV('pengeluaran')"><i class="ti ti-download"></i> Ekspor</button>
              <button class="btn-add" id="btnAddPengeluaran" onclick="toggleForm('pengeluaran')"><i class="ti ti-plus"></i> Tambah</button>
            </div>
          </div>
          <div class="table-wrap">
            <table id="tablePengeluaran">
              <thead>
                <tr>
                  <th>No.</th><th>Tanggal</th><th>No. Kwitansi</th><th>Uraian</th>
                  <th>Pengeluaran (Rp)</th><th>Saldo (Rp)</th><th>Aksi</th>
                </tr>
              </thead>
              <tbody id="tbodyPengeluaran">
                <tr id="formRowPengeluaran" class="form-row">
                  <td colspan="7">
                    <div class="form-inner">
                      <input type="date" name="tanggal" id="eTanggal">
                      <input type="text" name="nokwitansi" id="eKwitansi" placeholder="No. Kwitansi">
                      <input type="text" name="uraian" id="eUraian" placeholder="Uraian / Keterangan">
                      <input type="number" name="nominal" id="eNominal" placeholder="Jumlah (Rp)">
                      <button class="btn-save" onclick="saveEntry('pengeluaran')"><i class="ti ti-check"></i> Simpan</button>
                      <button class="btn-cancel" onclick="toggleForm('pengeluaran')">Batal</button>
                    </div>
                  </td>
                </tr>
                <tr id="noDataPengeluaran">
                  <td colspan="7" class="no-data">
                    <i class="ti ti-inbox"></i>
                    Belum ada data pengeluaran. Klik "Tambah" untuk menambahkan.
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- LAPORAN PAGE -->
      <div class="page" id="pageLaporan">
        <div class="content-card">
          <div class="card-header">
            <div class="card-title">
              <i class="ti ti-file-report" style="color: var(--primary);"></i>
              <h2>Laporan Keuangan</h2>
            </div>
            <div class="card-actions">
              <button class="btn-export" onclick="exportCSV('laporan')"><i class="ti ti-download"></i> Ekspor</button>
              <button class="btn-export" onclick="window.print()"><i class="ti ti-printer"></i> Cetak</button>
            </div>
          </div>
          <div class="table-wrap">
            <table>
              <thead>
                <tr>
                  <th>No.</th><th>Tanggal</th><th>No. Kwitansi</th><th>Uraian</th>
                  <th>Pemasukan (Rp)</th><th>Pengeluaran (Rp)</th><th>Saldo (Rp)</th>
                </tr>
              </thead>
              <tbody id="tbodyLaporan">
                <tr id="noDataLaporan">
                  <td colspan="7" class="no-data">
                    <i class="ti ti-file-off"></i>
                    Belum ada data transaksi.
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="laporan-footer" id="laporanFooter" style="display:none;">
            <div class="footer-item">
              <div class="fl">Total Pemasukan</div>
              <div class="fv inc" id="footerIncome">Rp 0</div>
            </div>
            <div class="footer-item">
              <div class="fl">Total Pengeluaran</div>
              <div class="fv exp" id="footerExpense">Rp 0</div>
            </div>
            <div class="footer-item">
              <div class="fl">Saldo Akhir</div>
              <div class="fv bal" id="footerBalance">Rp 0</div>
            </div>
          </div>
        </div>
      </div>

    </main>
  </div>

  <!-- FOOTER -->
  <footer class="app-footer" id="appFooter">
    © 2026 &nbsp;<strong>Pembukuan Insentif MBG SGW 2</strong>&nbsp; — Hak Cipta Dilindungi
  </footer>

</div><!-- end #appWrapper -->

<script>
// ===== USERS DATABASE (kredensial) =====
const USERS = [
  { username: 'admin', password: '12345', displayName: 'Admin', avatar: 'AD' },
  { username: 'bendahara', password: 'sgw2024', displayName: 'Bendahara', avatar: 'BD' },
  { username: 'ketua', password: 'ketua2025', displayName: 'Ketua', avatar: 'KT' },
];

// ===== AUTH STATE =====
let currentUser = null;

// ===== LOGIN =====
function doLogin() {
  const username = document.getElementById('loginUsername').value.trim();
  const password = document.getElementById('loginPassword').value;
  const errEl = document.getElementById('loginError');
  const btn = document.getElementById('btnLogin');

  if (!username || !password) {
    showLoginError('Username dan password tidak boleh kosong.');
    return;
  }

  // Simulasi loading
  btn.disabled = true;
  btn.innerHTML = '<i class="ti ti-loader-2" style="animation:spin 0.8s linear infinite"></i> Memverifikasi...';

  setTimeout(() => {
    const user = USERS.find(u => u.username === username && u.password === password);

    if (user) {
      currentUser = user;
      errEl.classList.remove('show');

      // Update UI dengan info user
      document.getElementById('headerUsername').textContent = user.displayName;
      document.getElementById('headerAvatar').textContent = user.avatar;
      document.getElementById('welcomeName').textContent = user.displayName;

      // Tampilkan app, sembunyikan login
      document.getElementById('loginScreen').classList.add('hidden');
      document.getElementById('appWrapper').classList.add('visible');

      showToast('success', `Selamat datang, ${user.displayName}!`);
    } else {
      showLoginError('Username atau password salah. Silakan coba lagi.');
    }

    btn.disabled = false;
    btn.innerHTML = '<i class="ti ti-login"></i> Masuk';
  }, 800);
}

function showLoginError(msg) {
  const errEl = document.getElementById('loginError');
  document.getElementById('loginErrorMsg').textContent = msg;
  errEl.classList.add('show');
  document.getElementById('loginPassword').value = '';
  document.getElementById('loginPassword').focus();

  // Shake animation
  errEl.style.animation = 'none';
  setTimeout(() => {
    errEl.style.animation = '';
  }, 10);
}

function handleLoginKey(e) {
  if (e.key === 'Enter') doLogin();
}

function togglePassword() {
  const input = document.getElementById('loginPassword');
  const icon = document.getElementById('eyeIcon');
  if (input.type === 'password') {
    input.type = 'text';
    icon.className = 'ti ti-eye-off';
  } else {
    input.type = 'password';
    icon.className = 'ti ti-eye';
  }
}

// ===== LOGOUT =====
function openLogoutModal() {
  document.getElementById('logoutModal').classList.add('show');
}

function closeLogoutModal() {
  document.getElementById('logoutModal').classList.remove('show');
}

function doLogout() {
  closeLogoutModal();
  const name = currentUser ? currentUser.displayName : 'Pengguna';

  // Reset app state
  currentUser = null;
  state.pemasukan = [];
  state.pengeluaran = [];
  state.formOpen = { pemasukan: false, pengeluaran: false };

  // Reset form fields
  document.getElementById('loginUsername').value = '';
  document.getElementById('loginPassword').value = '';
  document.getElementById('loginError').classList.remove('show');

  // Kembali ke login
  document.getElementById('appWrapper').classList.remove('visible');
  document.getElementById('loginScreen').classList.remove('hidden');

  // Reset page ke dashboard
  showPage('dashboard');
  updateStats();

  showToast('success', `Berhasil keluar. Sampai jumpa, ${name}!`);
}

// Tutup modal jika klik di luar
document.getElementById('logoutModal').addEventListener('click', function(e) {
  if (e.target === this) closeLogoutModal();
});

// ===== TOAST =====
let toastTimer;
function showToast(type, msg) {
  const toast = document.getElementById('toast');
  const icon = toast.querySelector('i');
  document.getElementById('toastMsg').textContent = msg;
  toast.className = `show ${type}`;
  icon.className = type === 'success' ? 'ti ti-check' : 'ti ti-x';
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => { toast.className = ''; }, 3000);
}

// ===== CSS SPIN =====
const style = document.createElement('style');
style.textContent = `@keyframes spin { to { transform: rotate(360deg); } }`;
document.head.appendChild(style);

// ===== APP STATE =====
const state = {
  pemasukan: [],
  pengeluaran: [],
  formOpen: { pemasukan: false, pengeluaran: false },
  sidebarOpen: true
};

function fmt(n) {
  return 'Rp ' + Math.round(n).toLocaleString('id-ID');
}
function fmtDate(d) {
  if (!d) return '-';
  const [y, m, day] = d.split('-');
  return `${day}/${m}/${y}`;
}

// SIDEBAR
document.getElementById('toggleSidebar').addEventListener('click', () => {
  const sidebar = document.getElementById('sidebar');
  const main = document.getElementById('mainContent');
  const footer = document.getElementById('appFooter');
  state.sidebarOpen = !state.sidebarOpen;
  sidebar.classList.toggle('collapsed', !state.sidebarOpen);
  main.classList.toggle('full', !state.sidebarOpen);
  footer.classList.toggle('full', !state.sidebarOpen);
});

function toggleMenu(menuId, el) {
  const menu = document.getElementById(menuId);
  const isOpen = menu.classList.contains('open');
  document.querySelectorAll('.sub-menu').forEach(m => m.classList.remove('open'));
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('open'));
  if (!isOpen) { menu.classList.add('open'); el.classList.add('open'); }
}

function setActiveNav(page) {
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
  document.querySelectorAll('.sub-item').forEach(n => n.classList.remove('active'));
  if (page === 'dashboard') document.querySelector('[onclick="showPage(\'dashboard\')"]').classList.add('active');
  if (page === 'pemasukan') {
    document.getElementById('subPemasukan').classList.add('active');
    document.getElementById('navInputData').classList.add('open');
    document.getElementById('menuInputData').classList.add('open');
  }
  if (page === 'pengeluaran') {
    document.getElementById('subPengeluaran').classList.add('active');
    document.getElementById('navInputData').classList.add('open');
    document.getElementById('menuInputData').classList.add('open');
  }
  if (page === 'laporan') document.getElementById('navLaporan').classList.add('active');
}

function showPage(page) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.getElementById('page' + page.charAt(0).toUpperCase() + page.slice(1)).classList.add('active');
  setActiveNav(page);
  if (page === 'laporan') renderLaporan();
}

function toggleForm(type) {
  state.formOpen[type] = !state.formOpen[type];
  const row = document.getElementById('formRow' + (type === 'pemasukan' ? 'Pemasukan' : 'Pengeluaran'));
  row.classList.toggle('show', state.formOpen[type]);
  if (state.formOpen[type]) {
    const prefix = type === 'pemasukan' ? 'p' : 'e';
    const today = new Date().toISOString().split('T')[0];
    document.getElementById(prefix + 'Tanggal').value = today;
    document.getElementById(prefix + 'Kwitansi').focus();
  }
}

function saveEntry(type) {
  const prefix = type === 'pemasukan' ? 'p' : 'e';
  const tanggal = document.getElementById(prefix + 'Tanggal').value;
  const kwitansi = document.getElementById(prefix + 'Kwitansi').value.trim();
  const uraian = document.getElementById(prefix + 'Uraian').value.trim();
  const nominal = parseFloat(document.getElementById(prefix + 'Nominal').value);

  if (!tanggal || !uraian || isNaN(nominal) || nominal <= 0) {
    showToast('error', 'Harap isi semua field dengan benar!');
    return;
  }

  state[type].push({ tanggal, kwitansi: kwitansi || '-', uraian, nominal });
  state[type].sort((a, b) => a.tanggal.localeCompare(b.tanggal));

  document.getElementById(prefix + 'Kwitansi').value = '';
  document.getElementById(prefix + 'Uraian').value = '';
  document.getElementById(prefix + 'Nominal').value = '';
  state.formOpen[type] = false;
  document.getElementById('formRow' + (type === 'pemasukan' ? 'Pemasukan' : 'Pengeluaran')).classList.remove('show');

  renderTable(type);
  updateStats();
  showToast('success', 'Data berhasil disimpan!');
}

function deleteEntry(type, idx) {
  if (!confirm('Hapus data ini?')) return;
  state[type].splice(idx, 1);
  renderTable(type);
  updateStats();
  showToast('success', 'Data berhasil dihapus.');
}

function renderTable(type) {
  const key = type === 'pemasukan' ? 'Pemasukan' : 'Pengeluaran';
  const tbody = document.getElementById('tbody' + key);
  const noData = document.getElementById('noData' + key);
  const formRow = document.getElementById('formRow' + key);

  Array.from(tbody.querySelectorAll('tr.data-row')).forEach(r => r.remove());

  const data = state[type];
  noData.style.display = data.length === 0 ? '' : 'none';

  let runSaldo = type === 'pengeluaran' ? state.pemasukan.reduce((s, e) => s + e.nominal, 0) : 0;

  data.forEach((entry, idx) => {
    const tr = document.createElement('tr');
    tr.className = 'data-row';
    if (type === 'pemasukan') {
      runSaldo += entry.nominal;
      tr.innerHTML = `
        <td><span class="badge-no">${idx + 1}</span></td>
        <td>${fmtDate(entry.tanggal)}</td>
        <td>${entry.kwitansi}</td>
        <td>${entry.uraian}</td>
        <td class="income-val">${fmt(entry.nominal)}</td>
        <td class="saldo-val">${fmt(runSaldo)}</td>
        <td><button class="action-btn del" onclick="deleteEntry('pemasukan', ${idx})" title="Hapus"><i class="ti ti-trash"></i></button></td>`;
    } else {
      runSaldo -= entry.nominal;
      tr.innerHTML = `
        <td><span class="badge-no">${idx + 1}</span></td>
        <td>${fmtDate(entry.tanggal)}</td>
        <td>${entry.kwitansi}</td>
        <td>${entry.uraian}</td>
        <td class="expense-val">${fmt(entry.nominal)}</td>
        <td class="saldo-val">${fmt(runSaldo)}</td>
        <td><button class="action-btn del" onclick="deleteEntry('pengeluaran', ${idx})" title="Hapus"><i class="ti ti-trash"></i></button></td>`;
    }
    tbody.insertBefore(tr, noData);
  });
}

function renderLaporan() {
  const tbody = document.getElementById('tbodyLaporan');
  const noData = document.getElementById('noDataLaporan');
  const footer = document.getElementById('laporanFooter');
  Array.from(tbody.querySelectorAll('tr.data-row')).forEach(r => r.remove());

  const all = [
    ...state.pemasukan.map(e => ({ ...e, type: 'pemasukan' })),
    ...state.pengeluaran.map(e => ({ ...e, type: 'pengeluaran' }))
  ].sort((a, b) => a.tanggal.localeCompare(b.tanggal));

  noData.style.display = all.length === 0 ? '' : 'none';
  footer.style.display = all.length === 0 ? 'none' : 'flex';

  let saldo = 0, totalIncome = 0, totalExpense = 0;
  all.forEach((entry, idx) => {
    const tr = document.createElement('tr');
    tr.className = 'data-row';
    const isIncome = entry.type === 'pemasukan';
    if (isIncome) { saldo += entry.nominal; totalIncome += entry.nominal; }
    else { saldo -= entry.nominal; totalExpense += entry.nominal; }
    tr.innerHTML = `
      <td><span class="badge-no">${idx + 1}</span></td>
      <td>${fmtDate(entry.tanggal)}</td>
      <td>${entry.kwitansi}</td>
      <td>${entry.uraian}</td>
      <td class="${isIncome ? 'income-val' : ''}">${isIncome ? fmt(entry.nominal) : '-'}</td>
      <td class="${!isIncome ? 'expense-val' : ''}">${!isIncome ? fmt(entry.nominal) : '-'}</td>
      <td class="saldo-val">${fmt(saldo)}</td>`;
    tbody.insertBefore(tr, noData);
  });

  document.getElementById('footerIncome').textContent = fmt(totalIncome);
  document.getElementById('footerExpense').textContent = fmt(totalExpense);
  document.getElementById('footerBalance').textContent = fmt(totalIncome - totalExpense);
}

function updateStats() {
  const totalIncome = state.pemasukan.reduce((s, e) => s + e.nominal, 0);
  const totalExpense = state.pengeluaran.reduce((s, e) => s + e.nominal, 0);
  document.getElementById('statIncome').textContent = fmt(totalIncome);
  document.getElementById('statExpense').textContent = fmt(totalExpense);
  document.getElementById('statBalance').textContent = fmt(totalIncome - totalExpense);
}

function exportCSV(type) {
  if (!currentUser) return;
  let headers, rows;
  if (type === 'pemasukan') {
    headers = ['No,Tanggal,No Kwitansi,Uraian,Pemasukan,Saldo'];
    let saldo = 0;
    rows = state.pemasukan.map((e, i) => { saldo += e.nominal; return `${i+1},${fmtDate(e.tanggal)},${e.kwitansi},${e.uraian},${e.nominal},${saldo}`; });
  } else if (type === 'pengeluaran') {
    headers = ['No,Tanggal,No Kwitansi,Uraian,Pengeluaran,Saldo'];
    let saldo = state.pemasukan.reduce((s, e) => s + e.nominal, 0);
    rows = state.pengeluaran.map((e, i) => { saldo -= e.nominal; return `${i+1},${fmtDate(e.tanggal)},${e.kwitansi},${e.uraian},${e.nominal},${saldo}`; });
  } else {
    headers = ['No,Tanggal,No Kwitansi,Uraian,Pemasukan,Pengeluaran,Saldo'];
    const all = [
      ...state.pemasukan.map(e => ({ ...e, type: 'pemasukan' })),
      ...state.pengeluaran.map(e => ({ ...e, type: 'pengeluaran' }))
    ].sort((a, b) => a.tanggal.localeCompare(b.tanggal));
    let saldo = 0;
    rows = all.map((e, i) => {
      const inc = e.type === 'pemasukan' ? e.nominal : 0;
      const exp = e.type === 'pengeluaran' ? e.nominal : 0;
      saldo += inc - exp;
      return `${i+1},${fmtDate(e.tanggal)},${e.kwitansi},${e.uraian},${inc||''},${exp||''},${saldo}`;
    });
  }
  const csv = [...headers, ...rows].join('\n');
  const blob = new Blob([csv], { type: 'text/csv' });
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = `${type}_mbg_sgw2.csv`;
  a.click();
}

// Set default dates
const today = new Date().toISOString().split('T')[0];
document.getElementById('pTanggal').value = today;
document.getElementById('eTanggal').value = today;

// Focus username on load
document.getElementById('loginUsername').focus();
</script>
</body>
</html>
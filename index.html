<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>โปรแกรมคำนวณสี Flexo — GPMASTERBOX</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500;600;700&family=Noto+Serif+Thai:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root {
  --cream: #FDF8F2;
  --cream-dark: #F5EDE0;
  --orange: #E8813A;
  --orange-light: #F4A661;
  --orange-dark: #C96A25;
  --orange-pale: #FEF3E8;
  --brown: #7A4F2E;
  --brown-light: #A0703F;
  --ink-bg: #EEF4FB;
  --ink-accent: #3B82C4;
  --ink-text: #1E4D7B;
  --tol-bg: #FFF4E8;
  --tol-accent: #E8813A;
  --cost-bg: #EDFAF3;
  --cost-accent: #2E9E62;
  --cost-text: #1A6B41;
  --text-primary: #2C1A0E;
  --text-secondary: #6B4C2F;
  --text-muted: #A0896E;
  --border: #E8D8C4;
  --shadow-sm: 0 2px 8px rgba(122,79,46,.08);
  --shadow-md: 0 6px 24px rgba(122,79,46,.12);
  --shadow-lg: 0 16px 48px rgba(122,79,46,.16);
  --radius: 16px;
  --radius-sm: 10px;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  font-family: 'Sarabun', sans-serif;
  background: var(--cream);
  color: var(--text-primary);
  min-height: 100vh;
  font-size: 15px;
  line-height: 1.6;
}

/* ── BACKGROUND TEXTURE ── */
body::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image:
    radial-gradient(ellipse 80% 50% at 10% -10%, rgba(232,129,58,.12) 0%, transparent 60%),
    radial-gradient(ellipse 60% 40% at 90% 100%, rgba(232,129,58,.08) 0%, transparent 60%);
  pointer-events: none;
  z-index: 0;
}

.container {
  position: relative;
  z-index: 1;
  max-width: 960px;
  margin: 0 auto;
  padding: 2rem 1.25rem 4rem;
}

/* ── HEADER ── */
header {
  text-align: center;
  padding: 2.5rem 1rem 2rem;
  margin-bottom: 2rem;
}

.brand-badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: var(--orange);
  color: #fff;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: .1em;
  padding: 5px 14px;
  border-radius: 40px;
  margin-bottom: 1.25rem;
  text-transform: uppercase;
}

.brand-badge .dot {
  width: 6px; height: 6px;
  background: rgba(255,255,255,.7);
  border-radius: 50%;
  animation: pulse 2s infinite;
}

@keyframes pulse { 0%,100%{opacity:1} 50%{opacity:.4} }

header h1 {
  font-family: 'Noto Serif Thai', serif;
  font-size: clamp(1.8rem, 4vw, 2.6rem);
  font-weight: 700;
  color: var(--text-primary);
  line-height: 1.3;
  margin-bottom: .6rem;
}

header h1 span { color: var(--orange); }

header p {
  color: var(--text-secondary);
  font-size: 15px;
  max-width: 540px;
  margin: 0 auto;
}

/* ── CARDS ── */
.card {
  background: #fff;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  box-shadow: var(--shadow-md);
  padding: 2rem;
  margin-bottom: 1.5rem;
}

.card-title {
  font-family: 'Noto Serif Thai', serif;
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--text-primary);
  margin-bottom: 1.5rem;
  display: flex;
  align-items: center;
  gap: 10px;
}

.card-title .icon {
  width: 34px; height: 34px;
  background: var(--orange-pale);
  border-radius: 9px;
  display: grid;
  place-items: center;
  font-size: 16px;
  flex-shrink: 0;
}

/* ── FORM ── */
.form-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem 1.25rem;
}

@media(max-width:600px) { .form-grid { grid-template-columns: 1fr; } }

.field {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.field label {
  font-size: 13px;
  font-weight: 600;
  color: var(--text-secondary);
  letter-spacing: .02em;
}

.field input {
  border: 1.5px solid var(--border);
  border-radius: var(--radius-sm);
  padding: 10px 14px;
  font-family: 'Sarabun', sans-serif;
  font-size: 15px;
  color: var(--text-primary);
  background: var(--cream);
  transition: border-color .2s, box-shadow .2s, background .2s;
  outline: none;
}

.field input:focus {
  border-color: var(--orange);
  background: #fff;
  box-shadow: 0 0 0 3px rgba(232,129,58,.15);
}

.field input.error { border-color: #E24B4A; background: #FFF5F5; }

.field .hint {
  font-size: 11px;
  color: var(--text-muted);
}

.field .err-msg {
  font-size: 12px;
  color: #C0392B;
  display: none;
}

.field .err-msg.show { display: block; }

/* ── BUTTONS ── */
.btn-row {
  display: flex;
  flex-wrap: wrap;
  gap: .75rem;
  margin-top: 1.75rem;
}

.btn {
  display: inline-flex;
  align-items: center;
  gap: 7px;
  border: none;
  border-radius: var(--radius-sm);
  padding: 11px 22px;
  font-family: 'Sarabun', sans-serif;
  font-size: 14px;
  font-weight: 600;
  cursor: pointer;
  transition: all .18s;
  position: relative;
  overflow: hidden;
}

.btn::after {
  content: '';
  position: absolute;
  inset: 0;
  background: rgba(255,255,255,0);
  transition: background .15s;
}

.btn:hover::after { background: rgba(255,255,255,.12); }
.btn:active { transform: scale(.97); }

.btn-primary {
  background: var(--orange);
  color: #fff;
  box-shadow: 0 4px 14px rgba(232,129,58,.4);
}

.btn-primary:hover { background: var(--orange-dark); box-shadow: 0 6px 18px rgba(232,129,58,.5); }

.btn-secondary {
  background: var(--cream-dark);
  color: var(--brown);
  border: 1.5px solid var(--border);
}

.btn-secondary:hover { background: var(--border); }

.btn-success {
  background: var(--cost-accent);
  color: #fff;
  box-shadow: 0 4px 14px rgba(46,158,98,.35);
}

.btn-success:hover { background: var(--cost-text); }

/* ── RESULT SECTION ── */
#results-section {
  display: none;
  animation: fadeUp .4s ease both;
}

@keyframes fadeUp { from{opacity:0;transform:translateY(16px)} to{opacity:1;transform:none} }

.result-summary {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
  margin-bottom: 1.5rem;
}

@media(max-width:650px) { .result-summary { grid-template-columns: 1fr 1fr; } }
@media(max-width:420px) { .result-summary { grid-template-columns: 1fr; } }

.summary-card {
  border-radius: var(--radius-sm);
  padding: 1.25rem 1rem;
  text-align: center;
  border: 1px solid;
}

.summary-card .sc-label {
  font-size: 12px;
  font-weight: 600;
  letter-spacing: .04em;
  margin-bottom: 6px;
}

.summary-card .sc-val {
  font-size: 1.6rem;
  font-weight: 700;
  line-height: 1.2;
}

.summary-card .sc-unit { font-size: 12px; margin-top: 3px; opacity: .75; }

.sc-ink { background: var(--ink-bg); border-color: #C6DCEF; }
.sc-ink .sc-label { color: var(--ink-text); }
.sc-ink .sc-val { color: var(--ink-accent); }

.sc-tol { background: var(--tol-bg); border-color: #F0CFAA; }
.sc-tol .sc-label { color: #8C4E10; }
.sc-tol .sc-val { color: var(--orange-dark); }

.sc-cost { background: var(--cost-bg); border-color: #A8DFC2; }
.sc-cost .sc-label { color: var(--cost-text); }
.sc-cost .sc-val { color: var(--cost-accent); }

/* ── DETAIL TABLE ── */
.result-detail {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}

@media(max-width:600px) { .result-detail { grid-template-columns: 1fr; } }

.detail-block {
  border-radius: var(--radius-sm);
  padding: 1.25rem;
  border: 1px solid;
}

.detail-block.ink { background: var(--ink-bg); border-color: #C6DCEF; }
.detail-block.tol { background: var(--tol-bg); border-color: #F0CFAA; }
.detail-block.cost { background: var(--cost-bg); border-color: #A8DFC2; }
.detail-block.info { background: var(--cream-dark); border-color: var(--border); }

.detail-block h3 {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: .06em;
  text-transform: uppercase;
  margin-bottom: 12px;
}

.detail-block.ink h3 { color: var(--ink-text); }
.detail-block.tol h3 { color: #8C4E10; }
.detail-block.cost h3 { color: var(--cost-text); }
.detail-block.info h3 { color: var(--text-secondary); }

.detail-row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 6px 0;
  border-bottom: 1px solid rgba(0,0,0,.05);
  font-size: 13.5px;
}

.detail-row:last-child { border-bottom: none; }

.detail-row .dr-label { color: var(--text-secondary); }
.detail-row .dr-val { font-weight: 600; color: var(--text-primary); font-variant-numeric: tabular-nums; }

/* ── TOLERANCE BAR ── */
.tol-visual {
  margin: 12px 0 4px;
  padding: 10px 12px;
  background: rgba(255,255,255,.6);
  border-radius: 8px;
}

.tol-track {
  height: 8px;
  background: rgba(232,129,58,.15);
  border-radius: 4px;
  position: relative;
  margin: 8px 0;
}

.tol-fill {
  height: 100%;
  border-radius: 4px;
  background: linear-gradient(90deg, #F4A661, var(--orange));
  position: absolute;
  left: 8%;
  width: 24%;
  transition: all .5s ease;
}

.tol-labels {
  display: flex;
  justify-content: space-between;
  font-size: 11px;
  color: var(--text-muted);
}

/* ── JOB HISTORY TABLE ── */
.table-wrap {
  overflow-x: auto;
  border-radius: var(--radius-sm);
  border: 1px solid var(--border);
}

table {
  width: 100%;
  border-collapse: collapse;
  font-size: 13.5px;
  min-width: 660px;
}

thead th {
  background: var(--cream-dark);
  padding: 11px 14px;
  text-align: left;
  font-weight: 700;
  font-size: 12px;
  color: var(--text-secondary);
  letter-spacing: .04em;
  border-bottom: 1.5px solid var(--border);
  white-space: nowrap;
}

tbody tr {
  transition: background .15s;
}

tbody tr:nth-child(even) { background: var(--cream); }
tbody tr:hover { background: var(--orange-pale); }

tbody td {
  padding: 10px 14px;
  border-bottom: 1px solid var(--border);
  color: var(--text-primary);
  white-space: nowrap;
}

tbody tr:last-child td { border-bottom: none; }

.delete-btn {
  background: #FEE2E2;
  color: #C0392B;
  border: none;
  border-radius: 6px;
  padding: 5px 11px;
  font-size: 12px;
  font-weight: 600;
  cursor: pointer;
  font-family: 'Sarabun', sans-serif;
  transition: all .15s;
}

.delete-btn:hover { background: #FECACA; }

/* ── EMPTY STATE ── */
.empty-state {
  text-align: center;
  padding: 3rem 1rem;
  color: var(--text-muted);
}

.empty-state .es-icon {
  font-size: 2.5rem;
  margin-bottom: .75rem;
  opacity: .5;
}

.empty-state p { font-size: 14px; }

/* ── DIVIDER ── */
.divider {
  height: 1px;
  background: var(--border);
  margin: 1.75rem 0;
}

/* ── FOOTER ── */
footer {
  text-align: center;
  padding: 1.5rem;
  color: var(--text-muted);
  font-size: 12px;
  position: relative;
  z-index: 1;
}

/* ── TOAST ── */
.toast {
  position: fixed;
  bottom: 2rem;
  right: 1.5rem;
  background: var(--text-primary);
  color: #fff;
  padding: 12px 20px;
  border-radius: 10px;
  font-size: 14px;
  font-weight: 500;
  box-shadow: var(--shadow-lg);
  transform: translateY(80px);
  opacity: 0;
  transition: all .3s cubic-bezier(.34,1.56,.64,1);
  z-index: 1000;
  pointer-events: none;
}

.toast.show { transform: translateY(0); opacity: 1; }

/* ── SCROLLBAR ── */
::-webkit-scrollbar { width: 6px; height: 6px; }
::-webkit-scrollbar-track { background: var(--cream); }
::-webkit-scrollbar-thumb { background: var(--border); border-radius: 10px; }
</style>
</head>
<body>

<div class="container">

  <!-- HEADER -->
  <header>
    <div class="brand-badge"><span class="dot"></span> GPMASTERBOX</div>
    <h1>โปรแกรมคำนวณ<span>สี Flexo</span></h1>
    <p>คำนวณปริมาณและต้นทุนสีพิมพ์ฟล็กโซกราฟีสำหรับการผลิตกล่องลูกฟูก — แม่นยำตามมาตรฐานโรงพิมพ์จริง</p>
  </header>

  <!-- INPUT CARD -->
  <div class="card">
    <div class="card-title">
      <div class="icon">📐</div>
      กรอกข้อมูลการพิมพ์
    </div>

    <div class="form-grid">
      <div class="field">
        <label>กว้าง (นิ้ว)</label>
        <input type="number" id="width" placeholder="เช่น 26" min="0.01" step="0.01">
        <span class="err-msg" id="err-width">กรุณากรอกความกว้างที่มากกว่า 0</span>
      </div>
      <div class="field">
        <label>ยาว (นิ้ว)</label>
        <input type="number" id="length" placeholder="เช่น 30" min="0.01" step="0.01">
        <span class="err-msg" id="err-length">กรุณากรอกความยาวที่มากกว่า 0</span>
      </div>
      <div class="field">
        <label>จำนวนแผ่น</label>
        <input type="number" id="quantity" placeholder="เช่น 5000" min="1" step="1">
        <span class="err-msg" id="err-quantity">กรุณากรอกจำนวนแผ่นที่เป็นจำนวนเต็มมากกว่า 0</span>
      </div>
      <div class="field">
        <label>เปอร์เซ็นต์พื้นที่พิมพ์ (%)</label>
        <input type="number" id="coverage" placeholder="0–100" min="0" max="100" step="1" value="100">
        <span class="hint">ค่าเริ่มต้น = 100% (เต็มพื้นที่)</span>
        <span class="err-msg" id="err-coverage">เปอร์เซ็นต์ต้องอยู่ระหว่าง 0 ถึง 100</span>
      </div>
      <div class="field">
        <label>ราคาสีต่อกิโลกรัม (บาท)</label>
        <input type="number" id="inkPrice" placeholder="เช่น 150" min="0" step="1">
        <span class="err-msg" id="err-inkPrice">ราคาต้องไม่ติดลบ</span>
      </div>
      <div class="field">
        <label>สูญเสียจากการเตรียมเครื่อง (กก.)</label>
        <input type="number" id="setupWaste" placeholder="เช่น 1" min="0" step="0.1" value="0">
        <span class="hint">Setup waste — ค่าเริ่มต้น = 0</span>
        <span class="err-msg" id="err-setupWaste">ค่าต้องไม่ติดลบ</span>
      </div>
      <div class="field">
        <label>สูญเสียจากการล้างเครื่อง (กก.)</label>
        <input type="number" id="cleaningLoss" placeholder="เช่น 0.85" min="0" step="0.1" value="0">
        <span class="hint">Cleaning loss — ค่าเริ่มต้น = 0</span>
        <span class="err-msg" id="err-cleaningLoss">ค่าต้องไม่ติดลบ</span>
      </div>
    </div>

    <div class="btn-row">
      <button class="btn btn-primary" onclick="calculate()">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M9 3H5a2 2 0 0 0-2 2v4m6-6h10a2 2 0 0 1 2 2v4M9 3v18m0 0h10a2 2 0 0 0 2-2V9M9 21H5a2 2 0 0 1-2-2V9m0 0h18"/></svg>
        คำนวณ
      </button>
      <button class="btn btn-secondary" onclick="loadExample()">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
        ใส่ข้อมูลตัวอย่าง
      </button>
      <button class="btn btn-secondary" onclick="resetForm()">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M3 12a9 9 0 1 0 9-9 9.75 9.75 0 0 0-6.74 2.74L3 8"/><path d="M3 3v5h5"/></svg>
        ล้างค่า
      </button>
    </div>
  </div>

  <!-- RESULTS SECTION -->
  <div id="results-section">

    <div class="card">
      <div class="card-title">
        <div class="icon">📊</div>
        ผลการคำนวณ
      </div>

      <!-- 3 SUMMARY CARDS -->
      <div class="result-summary">
        <div class="summary-card sc-ink">
          <div class="sc-label">สีทั้งหมด (หลังหักสูญเสีย)</div>
          <div class="sc-val" id="sum-finalInk">—</div>
          <div class="sc-unit">กิโลกรัม</div>
        </div>
        <div class="summary-card sc-tol">
          <div class="sc-label">ช่วงความคลาดเคลื่อน</div>
          <div class="sc-val" id="sum-range">—</div>
          <div class="sc-unit">กก. (±12%)</div>
        </div>
        <div class="summary-card sc-cost">
          <div class="sc-label">ต้นทุนสีต่อแผ่น</div>
          <div class="sc-val" id="sum-costPerSheet">—</div>
          <div class="sc-unit">บาท/แผ่น</div>
        </div>
      </div>

      <!-- DETAIL BLOCKS -->
      <div class="result-detail">

        <div class="detail-block ink">
          <h3>📘 ข้อมูลการใช้สี</h3>
          <div class="detail-row"><span class="dr-label">พื้นที่แผ่นกระดาษ</span><span class="dr-val" id="res-area">—</span></div>
          <div class="detail-row"><span class="dr-label">สีต่อแผ่น (100%)</span><span class="dr-val" id="res-inkPerSheet">—</span></div>
          <div class="detail-row"><span class="dr-label">สีต่อแผ่น (หลัง coverage)</span><span class="dr-val" id="res-adjInk">—</span></div>
          <div class="detail-row"><span class="dr-label">สีรวม (production)</span><span class="dr-val" id="res-totalInk">—</span></div>
          <div class="detail-row"><span class="dr-label">สียอดรวม (+ waste)</span><span class="dr-val" id="res-finalInk">—</span></div>
        </div>

        <div class="detail-block tol">
          <h3>📙 ช่วงความคลาดเคลื่อน ±12%</h3>
          <div class="tol-visual">
            <div class="tol-track">
              <div class="tol-fill" id="tol-fill"></div>
            </div>
            <div class="tol-labels">
              <span id="tol-min-label">—</span>
              <span>ค่ากลาง</span>
              <span id="tol-max-label">—</span>
            </div>
          </div>
          <div class="detail-row"><span class="dr-label">ปริมาณสีต่ำสุด (−12%)</span><span class="dr-val" id="res-minInk">—</span></div>
          <div class="detail-row"><span class="dr-label">ปริมาณสีสูงสุด (+12%)</span><span class="dr-val" id="res-maxInk">—</span></div>
        </div>

        <div class="detail-block cost">
          <h3>📗 ต้นทุนสี</h3>
          <div class="detail-row"><span class="dr-label">ต้นทุนรวม</span><span class="dr-val" id="res-totalCost">—</span></div>
          <div class="detail-row"><span class="dr-label">ต้นทุนต่ำสุด</span><span class="dr-val" id="res-minCost">—</span></div>
          <div class="detail-row"><span class="dr-label">ต้นทุนสูงสุด</span><span class="dr-val" id="res-maxCost">—</span></div>
          <div class="detail-row"><span class="dr-label">ต้นทุนสีต่อแผ่น</span><span class="dr-val" id="res-costPerSheet">—</span></div>
        </div>

        <div class="detail-block info">
          <h3>📋 ข้อมูลงานพิมพ์</h3>
          <div class="detail-row"><span class="dr-label">ขนาดแผ่น</span><span class="dr-val" id="info-size">—</span></div>
          <div class="detail-row"><span class="dr-label">จำนวนแผ่น</span><span class="dr-val" id="info-qty">—</span></div>
          <div class="detail-row"><span class="dr-label">% พื้นที่พิมพ์</span><span class="dr-val" id="info-cov">—</span></div>
          <div class="detail-row"><span class="dr-label">สูญเสียเตรียมเครื่อง</span><span class="dr-val" id="info-setup">—</span></div>
          <div class="detail-row"><span class="dr-label">สูญเสียล้างเครื่อง</span><span class="dr-val" id="info-clean">—</span></div>
        </div>

      </div>

      <div class="divider"></div>

      <div class="btn-row">
        <button class="btn btn-success" onclick="saveJob()">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M19 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11l5 5v11a2 2 0 0 1-2 2z"/><polyline points="17 21 17 13 7 13 7 21"/><polyline points="7 3 7 8 15 8"/></svg>
          บันทึกผลลงตาราง
        </button>
      </div>
    </div>

  </div>

  <!-- JOB HISTORY -->
  <div class="card">
    <div class="card-title">
      <div class="icon">📋</div>
      ประวัติงานพิมพ์ที่บันทึกไว้
    </div>

    <div id="history-container">
      <div class="empty-state" id="empty-state">
        <div class="es-icon">📂</div>
        <p>ยังไม่มีงานที่บันทึก — คำนวณแล้วกด "บันทึกผลลงตาราง"</p>
      </div>
      <div class="table-wrap" id="table-wrap" style="display:none">
        <table>
          <thead>
            <tr>
              <th>#</th>
              <th>ขนาดกระดาษ (นิ้ว)</th>
              <th>จำนวนแผ่น</th>
              <th>% พื้นที่พิมพ์</th>
              <th>ใช้สีรวม (กก.)</th>
              <th>ต้นทุนรวม (บาท)</th>
              <th>ต้นทุนต่อแผ่น (บาท)</th>
              <th>จัดการ</th>
            </tr>
          </thead>
          <tbody id="job-tbody"></tbody>
        </table>
      </div>
    </div>

  </div>

</div>

<!-- TOAST -->
<div class="toast" id="toast"></div>

<footer>
  GPMASTERBOX — โปรแกรมคำนวณสี Flexo v1.0 &nbsp;|&nbsp; อ้างอิงมาตรฐาน: 27.5×31.1 นิ้ว = 7 กก./1,000 แผ่น
</footer>

<script>
const BASE_AREA = 855.25;
const BASE_INK  = 7;
let jobs = [];
let lastCalc = null;

function r2(v){ return Math.round(v * 100) / 100; }
function fmt(v, d=2){ return Number(v).toLocaleString('th-TH',{minimumFractionDigits:d,maximumFractionDigits:d}); }
function fmtInt(v){ return Math.round(v).toLocaleString('th-TH'); }

function showToast(msg, dur=2500){
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'), dur);
}

function setErr(id, show){
  const inp = document.getElementById(id);
  const err = document.getElementById('err-' + id);
  if(!inp || !err) return;
  inp.classList.toggle('error', show);
  err.classList.toggle('show', show);
}

function clearErr(id){
  const inp = document.getElementById(id);
  const err = document.getElementById('err-' + id);
  if(!inp || !err) return;
  inp.classList.remove('error');
  err.classList.remove('show');
}

function getNum(id){ return parseFloat(document.getElementById(id).value); }
function getStr(id){ return document.getElementById(id).value.trim(); }

function validate(){
  let ok = true;
  ['width','length','quantity','coverage','inkPrice','setupWaste','cleaningLoss'].forEach(clearErr);

  const w   = getNum('width');
  const l   = getNum('length');
  const qty = getNum('quantity');
  const cov = getNum('coverage');
  const prc = getNum('inkPrice');
  const sw  = getNum('setupWaste');
  const cl  = getNum('cleaningLoss');

  if(isNaN(w) || w <= 0)                      { setErr('width',       true); ok=false; }
  if(isNaN(l) || l <= 0)                      { setErr('length',      true); ok=false; }
  if(isNaN(qty) || qty < 1 || !Number.isInteger(qty)) { setErr('quantity',   true); ok=false; }
  if(isNaN(cov) || cov < 0 || cov > 100)      { setErr('coverage',    true); ok=false; }
  if(!isNaN(prc) && prc < 0)                  { setErr('inkPrice',    true); ok=false; }
  if(!isNaN(sw) && sw < 0)                    { setErr('setupWaste',  true); ok=false; }
  if(!isNaN(cl) && cl < 0)                    { setErr('cleaningLoss',true); ok=false; }

  return ok;
}

function calculate(){
  if(!validate()) return;

  const w   = getNum('width');
  const l   = getNum('length');
  const qty = parseInt(document.getElementById('quantity').value, 10);
  const cov = getNum('coverage');
  const prc = isNaN(getNum('inkPrice'))    ? 0 : getNum('inkPrice');
  const sw  = isNaN(getNum('setupWaste')) ? 0 : getNum('setupWaste');
  const cl  = isNaN(getNum('cleaningLoss'))? 0 : getNum('cleaningLoss');

  const area            = r2(w * l);
  const areaRatio       = area / BASE_AREA;
  const inkPerSheet     = r2(BASE_INK * areaRatio);
  const adjInk          = r2(inkPerSheet * (cov / 100));
  const totalInkG       = adjInk * qty;
  const totalInkKg      = r2(totalInkG / 1000);
  const finalInkKg      = r2(totalInkKg + sw + cl);
  const minInkKg        = r2(finalInkKg * 0.88);
  const maxInkKg        = r2(finalInkKg * 1.12);
  const totalCost       = r2(finalInkKg * prc);
  const minCost         = r2(minInkKg * prc);
  const maxCost         = r2(maxInkKg * prc);
  const costPerSheet    = qty > 0 ? r2(totalCost / qty) : 0;

  lastCalc = {w,l,qty,cov,sw,cl,prc,area,inkPerSheet,adjInk,totalInkKg,finalInkKg,minInkKg,maxInkKg,totalCost,minCost,maxCost,costPerSheet};

  // ── Populate summary
  document.getElementById('sum-finalInk').textContent    = fmt(finalInkKg);
  document.getElementById('sum-range').textContent       = fmt(minInkKg) + ' – ' + fmt(maxInkKg);
  document.getElementById('sum-costPerSheet').textContent = fmt(costPerSheet, 4);

  // ── Populate detail — ink
  document.getElementById('res-area').textContent        = fmt(area) + ' ตร.นิ้ว';
  document.getElementById('res-inkPerSheet').textContent = fmt(inkPerSheet, 3) + ' กรัม';
  document.getElementById('res-adjInk').textContent      = fmt(adjInk, 3) + ' กรัม';
  document.getElementById('res-totalInk').textContent    = fmt(totalInkKg) + ' กก.';
  document.getElementById('res-finalInk').textContent    = fmt(finalInkKg) + ' กก.';

  // ── Tolerance
  document.getElementById('res-minInk').textContent      = fmt(minInkKg) + ' กก.';
  document.getElementById('res-maxInk').textContent      = fmt(maxInkKg) + ' กก.';
  document.getElementById('tol-min-label').textContent   = fmt(minInkKg) + ' กก.';
  document.getElementById('tol-max-label').textContent   = fmt(maxInkKg) + ' กก.';

  // ── Cost
  document.getElementById('res-totalCost').textContent   = fmt(totalCost, 2) + ' บาท';
  document.getElementById('res-minCost').textContent     = fmt(minCost, 2) + ' บาท';
  document.getElementById('res-maxCost').textContent     = fmt(maxCost, 2) + ' บาท';
  document.getElementById('res-costPerSheet').textContent= fmt(costPerSheet, 4) + ' บาท';

  // ── Info
  document.getElementById('info-size').textContent  = fmt(w, 1) + ' × ' + fmt(l, 1) + ' นิ้ว';
  document.getElementById('info-qty').textContent   = fmtInt(qty) + ' แผ่น';
  document.getElementById('info-cov').textContent   = fmt(cov, 0) + '%';
  document.getElementById('info-setup').textContent = fmt(sw) + ' กก.';
  document.getElementById('info-clean').textContent = fmt(cl) + ' กก.';

  const section = document.getElementById('results-section');
  section.style.display = 'block';
  section.scrollIntoView({ behavior:'smooth', block:'nearest' });
  showToast('✅ คำนวณสำเร็จ');
}

function saveJob(){
  if(!lastCalc){ showToast('⚠️ กรุณาคำนวณก่อนบันทึก'); return; }
  const c = lastCalc;
  jobs.unshift({
    id: Date.now(),
    size: c.w + ' × ' + c.l,
    qty: c.qty,
    cov: c.cov,
    finalInk: c.finalInkKg,
    totalCost: c.totalCost,
    costPerSheet: c.costPerSheet
  });
  renderTable();
  showToast('💾 บันทึกงานเรียบร้อย');
}

function deleteJob(id){
  jobs = jobs.filter(j=>j.id!==id);
  renderTable();
  showToast('🗑️ ลบรายการแล้ว');
}

function renderTable(){
  const empty = document.getElementById('empty-state');
  const wrap  = document.getElementById('table-wrap');
  const tbody = document.getElementById('job-tbody');

  if(!jobs.length){
    empty.style.display = '';
    wrap.style.display = 'none';
    return;
  }

  empty.style.display = 'none';
  wrap.style.display = '';

  tbody.innerHTML = jobs.map((j, i) => `
    <tr>
      <td>${jobs.length - i}</td>
      <td>${j.size} นิ้ว</td>
      <td>${fmtInt(j.qty)}</td>
      <td>${fmt(j.cov, 0)}%</td>
      <td>${fmt(j.finalInk)} กก.</td>
      <td>${fmt(j.totalCost, 2)} บาท</td>
      <td>${fmt(j.costPerSheet, 4)} บาท</td>
      <td><button class="delete-btn" onclick="deleteJob(${j.id})">ลบ</button></td>
    </tr>
  `).join('');
}

function loadExample(){
  document.getElementById('width').value        = '26';
  document.getElementById('length').value       = '30';
  document.getElementById('quantity').value     = '5000';
  document.getElementById('coverage').value     = '60';
  document.getElementById('inkPrice').value     = '150';
  document.getElementById('setupWaste').value   = '1';
  document.getElementById('cleaningLoss').value = '0.85';
  ['width','length','quantity','coverage','inkPrice','setupWaste','cleaningLoss'].forEach(clearErr);
  showToast('📋 ใส่ข้อมูลตัวอย่างแล้ว');
}

function resetForm(){
  ['width','length','quantity','inkPrice'].forEach(id=>{
    document.getElementById(id).value='';
  });
  document.getElementById('coverage').value      = '100';
  document.getElementById('setupWaste').value    = '0';
  document.getElementById('cleaningLoss').value  = '0';
  ['width','length','quantity','coverage','inkPrice','setupWaste','cleaningLoss'].forEach(clearErr);
  document.getElementById('results-section').style.display = 'none';
  lastCalc = null;
  showToast('🔄 ล้างค่าเรียบร้อย');
}

// ── Allow Enter key to trigger calculate
document.addEventListener('keydown', e => {
  if(e.key === 'Enter') calculate();
});
</script>
</body>
</html>

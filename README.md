<!doctype html>
<html lang="bn">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Today's USA Code Daw — Article</title>
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --accent:#0f4c81; /* anchor / brand */
    --muted:#6b7280;
    --bg:#ffffff;
    --card:#fafafa;
    font-family: 'Inter',system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;
  }
  *{box-sizing:border-box}
  body{margin:0;background:var(--bg);color:#0b1220;line-height:1.6}
  header{position:sticky;top:0;background:white;z-index:30;border-bottom:1px solid #eee}
  .container{max-width:1100px;margin:0 auto;padding:16px}
  .brand{display:flex;gap:12px;align-items:center}
  .logo{font-weight:700;color:var(--accent);font-size:18px}
  nav{margin-left:auto}
  .nav-toggle{display:none}
  /* layout */
  .grid{display:grid;grid-template-columns: 1fr 320px;gap:22px;padding:18px 0}
  article{background:var(--bg);padding:6px 0}
  h1{font-size:22px;margin:8px 0 6px}
  .meta{color:var(--muted);font-size:13px;margin-bottom:12px}
  .hero{width:100%;height:220px;object-fit:cover;border-radius:6px;margin-bottom:12px}
  .content p{margin:12px 0}
  aside.card{background:var(--card);padding:12px;border-radius:8px;border:1px solid #eee}
  .section-title{font-weight:600;margin-bottom:8px}
  /* responsive */
  @media (max-width:900px){
    .grid{grid-template-columns:1fr; padding:12px 0}
    nav{display:none}
    .nav-toggle{display:block;margin-left:auto}
    .hero{height:180px}
  }
  /* small details */
  .socials{display:flex;gap:8px;margin-top:8px}
  .btn{display:inline-block;padding:8px 12px;border-radius:6px;background:var(--accent);color:white;text-decoration:none;font-weight:600}
  .related-list{list-style:none;padding:0;margin:0}
  .related-list li{padding:8px 0;border-bottom:1px dashed #eee;font-size:14px}
</style>
</head>
<body>
<header>
  <div class="container" style="display:flex;align-items:center">
    <div class="brand">
      <div class="logo">Today's USA Code Daw</div>
      <div style="color:var(--muted);font-size:13px;margin-top:3px">Latest tech & code news</div>
    </div>
    <button class="nav-toggle" aria-label="menu">☰</button>
    <nav>
      <a href="#">বাংলাদেশ</a> · <a href="#">আন্তর্জাতিক</a> · <a href="#">টিপস</a>
    </nav>
  </div>
</header>

<main class="container">
  <div class="grid">
    <article>
      <div class="breadcrumb" style="color:var(--muted);font-size:13px">ইন্টারনেশনাল · ৭ অক্টোবর, ২০২৫</div>
      <h1>টেম্পলেট: কীভাবে AI দিয়ে কোড জেনারেট করে ওয়েব অ্যাপ তৈরি করবেন</h1>
      <div class="meta">Today's USA Code Daw — সম্পাদক · ১২ মিনিট আগে</div>
      <img class="hero" src="https://via.placeholder.com/1200x700.png?text=Hero+Image" alt="Hero image">
      <div class="content">
        <p>এই আর্টিকেলে দেখানো হবে কীভাবে আপনি AI টুল ব্যবহার করে দ্রুত ওয়েব অ্যাপ্লিকেশন প্রোটোটাইপ বানাতে পারেন...</p>
        <p><strong>ধাপ ১:</strong> প্রয়োজনীয় টুল ইনস্টল করুন — Node.js, Git, Editor ইত্যাদি।</p>
        <p><img src="https://via.placeholder.com/800x400.png?text=Inline+Image" style="width:100%;border-radius:6px" alt="inline image"></p>
        <p><strong>ধাপ ২:</strong> কোড জেনারেশন — উদাহরণ সহ কোড স্নিপেট দেখুন।</p>
        <p>...আরো লেখা...</p>
      </div>

      <div style="margin-top:18px;display:flex;gap:8px;flex-wrap:wrap">
        <a class="btn" href="#">শেয়ার করুন</a>
        <div class="socials" aria-hidden="true">
          <span style="color:var(--muted)">FB</span>
          <span style="color:var(--muted)">TW</span>
          <span style="color:var(--muted)">WA</span>
        </div>
      </div>
    </article>

    <aside>
      <div class="card">
        <div class="section-title">ক্যাটাগরি</div>
        <ul style="padding:0;margin:0;list-style:none">
          <li style="padding:6px 0">বাংলাদেশ</li>
          <li style="padding:6px 0">আন্তর্জাতিক</li>
          <li style="padding:6px 0">টেক</li>
          <li style="padding:6px 0">শিক্ষা</li>
        </ul>
      </div>

      <div class="card" style="margin-top:12px">
        <div class="section-title">সর্বশেষ খবর</div>
        <div style="font-size:14px;color:var(--muted)">● ডেমো খবর ১</div>
        <div style="font-size:14px;color:var(--muted);margin-top:6px">● ডেমো খবর ২</div>
      </div>

      <div class="card" style="margin-top:12px">
        <div class="section-title">আরও পড়ুন</div>
        <ul class="related-list">
          <li><a href="#">কিভাবে AI ব্লগ লেখে সাহায্য করে</a></li>
          <li><a href="#">সাম্প্রতিক কোডিং টিপস</a></li>
        </ul>
      </div>
    </aside>
  </div>
</main>

<footer style="border-top:1px solid #eee;margin-top:18px;padding:18px 0">
  <div class="container" style="display:flex;justify-content:space-between;align-items:center;gap:12px">
    <div style="color:var(--muted)">© 2025 Today's USA Code Daw</div>
    <div style="color:var(--muted)">Contact: info@tuscodedaw.example</div>
  </div>
</footer>

</body>
</html>

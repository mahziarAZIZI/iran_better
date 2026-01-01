# iran_better
ایران بهتر؛ بستری مستقل برای تحلیل، یادداشت و گفت‌وگوی مسئولانه درباره آینده ایران
<!DOCTYPE html>
<html lang="fa-IR" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>ایران بهتر — گفت‌وگوی مسئولانه و آگاهانه</title>
  <meta name="description" content="ایران بهتر؛ بستری مستقل، حرفه‌ای و قابل اعتماد برای تحلیل، یادداشت و گفت‌وگوی مدنی.">
  <meta name="robots" content="index, follow">
  <meta name="theme-color" content="#020617">
  <meta name="color-scheme" content="dark light">

  <!-- Open Graph -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="ایران بهتر">
  <meta property="og:title" content="ایران بهتر — گفت‌وگوی مسئولانه و آگاهانه">
  <meta property="og:description" content="فضایی برای تفکر، تحلیل و گفت‌وگوی مسئولانه.">
  <meta property="og:image" content="https://iranbetter.ir/images/og-image.jpg">
  <meta property="og:url" content="https://iranbetter.ir/">
  <meta property="og:locale" content="fa_IR">

  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image">

  <!-- Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Schema -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebSite",
    "name": "ایران بهتر",
    "url": "https://iranbetter.ir",
    "inLanguage": "fa-IR"
  }
  </script>

  <style>
    :root {
      --bg:#020617;
      --surface:#020617;
      --surface-secondary:#0f172a;
      --border:#1f2937;
      --text:#f8fafc;
      --muted:#94a3b8;
      --accent:#3b82f6;
      --radius:22px;
      --shadow:0 24px 70px rgba(0,0,0,.45);
      --transition:.3s ease;
    }

    [data-theme="light"]{
      --bg:#f8fafc;
      --surface:#fff;
      --surface-secondary:#f1f5f9;
      --border:#e5e7eb;
      --text:#020617;
      --muted:#475569;
      --shadow:0 24px 70px rgba(0,0,0,.08);
    }

    *{box-sizing:border-box;margin:0;padding:0}

    body{
      font-family:Vazirmatn,system-ui;
      background:var(--bg);
      color:var(--text);
      line-height:1.8;
    }

    header{
      position:sticky;
      top:0;
      background:rgba(2,6,23,.9);
      backdrop-filter:blur(16px);
      border-bottom:1px solid var(--border);
    }

    [data-theme="light"] header{
      background:rgba(255,255,255,.95);
    }

    .nav{
      max-width:1280px;
      margin:auto;
      padding:1rem 1.5rem;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    .brand{
      font-size:1.5rem;
      font-weight:800;
    }

    nav ul{
      display:flex;
      gap:1.5rem;
      list-style:none;
    }

    nav a{
      color:var(--muted);
    }

    nav a[aria-current="page"]{
      color:var(--text);
      font-weight:600;
    }

    main{
      max-width:1280px;
      margin:auto;
      padding:4rem 1.5rem;
    }

    .card{
      background:var(--surface);
      border:1px solid var(--border);
      border-radius:var(--radius);
      padding:3rem;
      box-shadow:var(--shadow);
      margin-bottom:3rem;
    }

    footer{
      text-align:center;
      padding:3rem 1.5rem;
      background:var(--surface-secondary);
      border-top:1px solid var(--border);
      color:var(--muted);
    }

    @media (prefers-reduced-motion: reduce){
      *{animation:none!important;transition:none!important}
    }
  </style>
</head>

<body>

<header>
  <div class="nav">
    <h1 class="brand">🇮🇷 ایران بهتر</h1>
    <nav aria-label="منوی اصلی">
      <ul>
        <li><a href="#about" aria-current="page">درباره</a></li>
        <li><a href="#posts">نوشته‌ها</a></li>
        <li><a href="#contact">تماس</a></li>
      </ul>
    </nav>
    <button id="theme-toggle" type="button" aria-label="تغییر تم">🌙</button>
  </div>
</header>

<main>
  <section id="about" class="card">
    <h2>درباره ما</h2>
    <p>ایران بهتر بستری برای گفت‌وگوی مسئولانه و آینده‌نگر است.</p>
  </section>
</main>

<footer>
  © ۱۴۰۲–۱۴۰۵ — ایران بهتر
</footer>

<script defer>
  const btn=document.getElementById("theme-toggle");
  btn.onclick=()=>{
    const t=document.documentElement.dataset.theme==="light"?"":"light";
    document.documentElement.dataset.theme=t;
    localStorage.setItem("theme",t);
  };
</script>

</body>
</html>

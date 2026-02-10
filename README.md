<!DOCTYPE html><html lang="hi">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Divya Collection - Shahpura</title>
<style>
  :root{--primary:#111;--accent:#eab308;--bg:#f5f5f5;--card:#fff}
  *{box-sizing:border-box}
  body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial;background:var(--bg);color:#111}
  header{background:var(--primary);color:#fff;padding:18px 16px;position:sticky;top:0}
  .container{max-width:1100px;margin:auto;padding:0 16px}
  .brand{font-size:26px;font-weight:800;letter-spacing:.5px}
  nav a{color:#fff;margin-right:14px;text-decoration:none;font-weight:600}
  .hero{display:grid;grid-template-columns:1.2fr .8fr;gap:20px;align-items:center;padding:32px 0}
  .hero h1{font-size:38px;margin:0 0 8px}
  .hero p{margin:0 0 16px;color:#444}
  .btn{display:inline-block;background:var(--accent);color:#000;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700}
  .hero .box{background:linear-gradient(135deg,#222,#555);height:220px;border-radius:18px}
  h2{margin:28px 0 10px}
  .grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
  .card{background:var(--card);border-radius:16px;overflow:hidden;box-shadow:0 6px 16px rgba(0,0,0,.08)}
  .ph{height:150px;background:linear-gradient(135deg,#ddd,#bbb)}
  .card .info{padding:12px}
  .price{font-weight:800}
  .order{margin-top:8px}
  .order a{display:inline-block;background:#22c55e;color:#fff;padding:10px 12px;border-radius:10px;text-decoration:none;font-weight:700}
  .about{background:#fff;border-radius:16px;padding:16px;box-shadow:0 6px 16px rgba(0,0,0,.08)}
  footer{margin-top:28px;background:#111;color:#fff}
  footer .container{padding:18px 16px}
  .small{color:#bbb}
  @media (max-width:900px){.hero{grid-template-columns:1fr}.grid{grid-template-columns:repeat(2,1fr)}}
  @media (max-width:520px){.grid{grid-template-columns:1fr}.hero h1{font-size:30px}}
</style>
</head>
<body>
<header>
  <div class="container" style="display:flex;align-items:center;justify-content:space-between;gap:10px;flex-wrap:wrap">
    <div class="brand">Divya Collection</div>
    <nav>
      <a href="#products">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header><section class="container hero">
  <div>
    <h1>घर बैठे कपड़े ऑर्डर करें</h1>
    <p>शर्ट, पैंट, जीन्स, लोवर्स और टी‑शर्ट्स — बढ़िया क्वालिटी, सही दाम।</p>
    <a class="btn" href="#products">अभी देखें</a>
  </div>
  <div class="box"></div>
</section><section id="products" class="container">
  <h2>हमारे प्रोडक्ट्स</h2>
  <div class="grid">
    <div class="card">
      <div class="ph"></div>
      <div class="info">
        <div><strong>शर्ट</strong></div>
        <div class="price">₹599 से</div>
        <div class="order"><a href="https://wa.me/919981677350?text=मुझे%20शर्ट%20ऑर्डर%20करना%20है">WhatsApp पर ऑर्डर</a></div>
      </div>
    </div>
    <div class="card">
      <div class="ph"></div>
      <div class="info">
        <div><strong>पैंट</strong></div>
        <div class="price">₹799 से</div>
        <div class="order"><a href="https://wa.me/919981677350?text=मुझे%20पैंट%20ऑर्डर%20करना%20है">WhatsApp पर ऑर्डर</a></div>
      </div>
    </div>
    <div class="card">
      <div class="ph"></div>
      <div class="info">
        <div><strong>जीन्स</strong></div>
        <div class="price">₹999 से</div>
        <div class="order"><a href="https://wa.me/919981677350?text=मुझे%20जीन्स%20ऑर्डर%20करना%20है">WhatsApp पर ऑर्डर</a></div>
      </div>
    </div>
    <div class="card">
      <div class="ph"></div>
      <div class="info">
        <div><strong>टी‑शर्ट्स</strong></div>
        <div class="price">₹399 से</div>
        <div class="order"><a href="https://wa.me/919981677350?text=मुझे%20टी-शर्ट%20ऑर्डर%20करना%20है">WhatsApp पर ऑर्डर</a></div>
      </div>
    </div>
    <div class="card">
      <div class="ph"></div>
      <div class="info">
        <div><strong>लोवर्स</strong></div>
        <div class="price">₹499 से</div>
        <div class="order"><a href="https://wa.me/919981677350?text=मुझे%20लोवर्स%20ऑर्डर%20करना%20है">WhatsApp पर ऑर्डर</a></div>
      </div>
    </div>
  </div>
</section><section id="about" class="container" style="margin-top:24px">
  <div class="about">
    <h2>हमारे बारे में</h2>
    <p><strong>Divya Collection, Shahpura</strong> – हम आपके लिए ट्रेंडिंग और क्वालिटी मेन्स वियर लाते हैं।</p>
    <p><strong>पता:</strong> शाहपुरा, डिंडौरी, मध्य प्रदेश</p>
  </div>
</section><section id="contact" class="container" style="margin-top:24px">
  <div class="about">
    <h2>संपर्क</h2>
    <p>ऑर्डर के लिए WhatsApp करें: <strong>+91-9981677350</strong></p>
    <p class="small">(ऊपर के बटन में अपना WhatsApp नंबर डालें — XXXXXXXXXX की जगह)</p>
  </div>
</section><footer>
  <div class="container">
    <div>© <span id="y"></span> Divya Collection • Shahpura, Dindori (MP)</div>
    <div class="small">All Men’s Wear</div>
  </div>
</footer><script>document.getElementById('y').textContent=new Date().getFullYear();</script></body>
</html>
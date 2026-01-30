# kimoto-safety-solutions
Kimoto Safety Solutions website
[1.html](https://github.com/user-attachments/files/24955766/1.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KIMOTO SAFETY SOLUTIONS</title>

<style>
:root{
  --blue:#0B1F33;
  --steel:#1E3A5F;
  --orange:#FF8C1A;
  --light:#F5F7FA;
  --dark:#0F172A;
}

*{margin:0;padding:0;box-sizing:border-box}

body{
  font-family:Inter,Segoe UI,Arial,sans-serif;
  background:var(--light);
  color:var(--dark);
  line-height:1.6;
}

/* HEADER */
header{
  background:var(--blue);
  padding:18px 40px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

header h1{
  color:#fff;
  letter-spacing:2px;
  font-size:20px;
}

nav a{
  color:#fff;
  text-decoration:none;
  margin-left:20px;
  font-weight:500;
}

.cta{
  background:var(--orange);
  color:#000;
  padding:10px 22px;
  border-radius:30px;
  font-weight:700;
}

/* HERO */
.hero{
  background:linear-gradient(135deg,var(--blue),var(--steel));
  color:#fff;
  padding:100px 20px;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:50px;
  align-items:center;
  max-width:1300px;
  margin:auto;
}

.hero h2{
  font-size:42px;
  margin-bottom:16px;
}

.hero p{
  font-size:18px;
  max-width:520px;
}

.hero img{
  width:100%;
  max-width:420px;
  border-radius:24px;
  box-shadow:0 30px 70px rgba(0,0,0,.35);
}

/* SECTIONS */
section{
  max-width:1200px;
  margin:auto;
  padding:80px 20px;
}

section h3{
  text-align:center;
  font-size:32px;
  color:var(--blue);
  margin-bottom:40px;
}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:32px;
}

.card{
  background:#fff;
  border-radius:22px;
  padding:28px;
  box-shadow:0 20px 40px rgba(0,0,0,.08);
}

.card img{
  width:100%;
  border-radius:16px;
  margin-bottom:16px;
}

.card h4{
  color:var(--steel);
  margin-bottom:8px;
}

/* PRODUCTS */
.products .card{
  border-top:6px solid var(--orange);
}

/* WHY */
.why{
  background:linear-gradient(135deg,var(--blue),var(--steel));
  color:#fff;
  border-radius:36px;
}

.why h3{color:#fff}

.why .card{
  background:rgba(255,255,255,.12);
  color:#fff;
  border-left:5px solid var(--orange);
}

/* CONTACT */
.contact{
  text-align:center;
}

/* FOOTER */
footer{
  background:var(--blue);
  color:#fff;
  text-align:center;
  padding:26px;
  font-size:14px;
}

/* RESPONSIVE */
@media(max-width:768px){
  .hero{grid-template-columns:1fr;text-align:center}
  .hero h2{font-size:32px}
}
</style>
</head>

<body>

<header>
  <h1>KIMOTO SAFETY SOLUTIONS</h1>
  <nav>
    <a href="#products">Products</a>
    <a class="cta" href="https://wa.me/254718450756?text=Hello%20KIMOTO%20Safety%20Solutions.%20I%20would%20like%20to%20request%20a%20quotation.">
      REQUEST A QUOTE
    </a>
  </nav>
</header>

<section class="hero">
  <div>
    <h2>KIMOTO SAFETY SOLUTIONS</h2>
    <p>
      Certified PPE and professional branding solutions designed for Kenyan
      industries, institutions, and large-scale projects.
    </p>
    <br>
    <a class="cta" href="https://wa.me/254718450756?text=Hello%20KIMOTO%20Safety%20Solutions.%20I%20would%20like%20to%20request%20a%20quotation.">
      REQUEST A QUOTE
    </a>
  </div>

  <!-- HERO PPE PORTRAIT -->
  <img src="images/kimoto-ppe-portrait.png" alt="KIMOTO Safety Professional in PPE">
</section>

<section>
  <h3>Our Services</h3>
  <div class="grid">
    <div class="card">
      <img src="images/ppe-supply.jpg" alt="">
      <h4>PPE Supply</h4>
      <p>
        Supply of OSHA and KEBS-compliant Personal Protective Equipment
        for construction, manufacturing, logistics, and institutions.
      </p>
    </div>

    <div class="card">
      <img src="images/ppe-branding.jpg" alt="">
      <h4>PPE Branding</h4>
      <p>
        Professional printing and embroidery on helmets, vests,
        overalls, jackets, and workwear.
      </p>
    </div>

    <div class="card">
      <img src="images/bulk-supply.jpg" alt="">
      <h4>Bulk & Project Supply</h4>
      <p>
        Reliable sourcing and timely delivery for tenders,
        NGOs, and large-scale safety projects.
      </p>
    </div>
  </div>
</section>

<section id="products" class="products">
  <h3>Product Categories</h3>
  <div class="grid">
    <div class="card">
      <img src="images/helmets.jpg" alt="">
      <h4>Head Protection</h4>
      <p>Industrial safety helmets and bump caps for impact and falling-object protection.</p>
    </div>

    <div class="card">
      <img src="images/eye-protection.jpg" alt="">
      <h4>Eye & Face Protection</h4>
      <p>Safety glasses, goggles, and face shields for dust, chemicals, and sparks.</p>
    </div>

    <div class="card">
      <img src="images/hearing-protection.jpg" alt="">
      <h4>Hearing Protection</h4>
      <p>Ear plugs and ear muffs designed for high-noise industrial environments.</p>
    </div>

    <div class="card">
      <img src="images/hand-protection.jpg" alt="">
      <h4>Hand Protection</h4>
      <p>Cut-resistant, chemical-resistant, and disposable gloves.</p>
    </div>

    <div class="card">
      <img src="images/body-protection.jpg" alt="">
      <h4>Body Protection</h4>
      <p>Overalls, reflective vests, jackets, and rainwear for industrial use.</p>
    </div>

    <div class="card">
      <img src="images/foot-protection.jpg" alt="">
      <h4>Foot Protection</h4>
      <p>Steel-toe and composite safety boots with anti-slip soles.</p>
    </div>
  </div>
</section>

<section class="why">
  <h3>Why Choose KIMOTO</h3>
  <div class="grid">
    <div class="card">OSHA 2007 & KEBS compliant products</div>
    <div class="card">Premium yet affordable pricing</div>
    <div class="card">PPE supply and branding under one roof</div>
    <div class="card">Reliable local Kenyan support</div>
  </div>
</section>

<section class="contact">
  <h3>Contact Us</h3>
  <p>Email: kimathi.maina@gmail.com</p>
  <p>Phone / WhatsApp: +254 718 450 756</p>
  <br>
  <a class="cta" href="https://wa.me/254718450756?text=Hello%20KIMOTO%20Safety%20Solutions.%20I%20would%20like%20to%20request%20a%20quotation.">
    REQUEST A QUOTE
  </a>
</section>

<footer>
  © 2026 KIMOTO SAFETY SOLUTIONS • Gear Up. Go Home Safe.
</footer>

</body>
</html>
![hand-protection](https://github.com/user-attachments/assets/59feb907-f885-4570-8ab7-d67cb3ae268e)
![foot-protection jpg](https://github.com/user-attachments/assets/31cf8f49-ad5c-4a3f-b46f-0e919f8bff60)
![foot-protection](https://github.com/user-attachments/assets/b9076751-f103-41f2-bd36-2e876e43d932)
![eye-protection](https://github.com/user-attachments/assets/abc53786-dff8-468f-8064-18d449f807d0)
![bulk-supply](https://github.com/user-attachments/assets/bb6ea0f3-167b-4fbf-ae82-f82c5ebd4c9c)
![body-protection](https://github.com/user-attachments/assets/fff748b2-d67d-4d5c-9437-6961581519a6)
![ppe-supply](https://github.com/user-attachments/assets/f75ffc05-95c0-45a0-a314-4c79aa23bb82)
![ppe-branding](https://github.com/user-attachments/assets/ec939c43-3708-4c2e-b32a-999c05680749)
![kimoto-ppe-portrait png](https://github.com/user-attachments/assets/dfd2bc47-fc59-4339-8607-775c30b3c3c5)
![helmets](https://github.com/user-attachments/assets/1eaaa873-7771-46e5-b9e8-e88183dc7260)
![hearing-protection](https://github.com/user-attachments/assets/c33f81b4-7c78-475d-8796-a408dbaceb39)
![head-protection](https://github.com/user-attachments/assets/ae900a5f-8f98-4bf3-a4cc-62438583861c)

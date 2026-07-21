<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Join Now — United Nature Foundation</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,400;0,600;1,500&family=Jost:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
  .join-hero {
    min-height: 640px;
    color: var(--white);
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding-bottom: 60px;
  }
  .join-hero h1 {
    font-size: clamp(2.2rem, 5.4vw, 3.6rem);
    color: var(--white);
    text-transform: uppercase;
    line-height: 1.15;
  }
  .join-hero h1 .amazon { color: rgba(0,0,0,0.55); }
  .join-hero .btns { display: flex; gap: 16px; justify-content: center; margin-top: 30px; flex-wrap: wrap; }
  .join-hero .btn { background: var(--white); color: var(--ink); border-color: var(--white); }
  .join-hero .btn:hover { background: transparent; color: var(--white); }

  .quote-strip { display: grid; grid-template-columns: 1fr 1fr 1fr 1fr; gap: 0; align-items: stretch; }
  .quote-block { padding: 50px 40px; display: flex; flex-direction: column; justify-content: center; }
  .quote-block .mark { font-family: var(--font-display); font-size: 2.4rem; color: var(--teal-900); line-height: 1; }
  .quote-block p { color: var(--teal-900); font-size: 1.05rem; }
  .quote-block .who { font-size: 0.9rem; color: #6b6b60; }
  .quote-strip .ph { aspect-ratio: 1/1; }
  @media (max-width: 900px) { .quote-strip { grid-template-columns: 1fr; } }

  .tier-card {
    border-radius: var(--radius-lg);
    padding: 56px 60px;
    color: var(--white);
    margin: 0 auto 30px;
    max-width: 1200px;
  }
  .tier-card.ranger { background: linear-gradient(120deg, #9fd6a8, #4a7a55 55%, #26402c); }
  .tier-card.corporate { background: linear-gradient(120deg, #6fb7ea, #dfeeff 55%, #bcd9f7); color: var(--teal-900); }
  .tier-card .kicker { letter-spacing: 0.1em; font-size: 0.8rem; text-transform: uppercase; opacity: 0.9; }
  .tier-card h2 { font-size: clamp(2rem, 4vw, 2.8rem); color: inherit; text-transform: uppercase; margin: 10px 0 22px; }
  .tier-card p { max-width: 620px; opacity: 0.95; }
  .tier-card .tags { text-decoration: underline; font-size: 0.9rem; letter-spacing: 0.03em; margin: 18px 0 30px; display:block; }
  .tier-card .price { font-size: 1.3rem; font-weight: 600; }
  .tier-card .price-note { font-size: 0.95rem; opacity: 0.85; }
  .tier-card .btn { margin-top: 24px; }
  .tier-card.ranger .btn { background: var(--white); color: var(--forest-950); border-color: var(--white); }
  .tier-card.corporate .btn { background: var(--teal-900); color: var(--white); border-color: var(--teal-900); }

  .protect-banner {
    position: relative;
    color: var(--white);
    padding: 60px 0;
    display: grid;
    grid-template-columns: 1.2fr 1fr 1fr 1fr;
    align-items: center;
    gap: 20px;
  }
  .protect-banner h2 { color: var(--white); font-size: clamp(1.6rem, 3vw, 2.2rem); line-height: 1.15; }
  .protect-banner h2 em { color: #a9e6ad; font-style: normal; }
  .stat { text-align: center; border-left: 1px solid rgba(255,255,255,0.35); padding-left: 20px; }
  .stat:first-of-type { border-left: none; padding-left: 0; }
  .stat .icon { font-size: 1.4rem; margin-bottom: 8px; }
  .stat .num { font-family: var(--font-display); font-size: 1.7rem; }
  .stat .lbl { font-size: 0.7rem; letter-spacing: 0.05em; opacity: 0.85; }
  @media (max-width: 900px) {
    .protect-banner { grid-template-columns: 1fr; text-align: center; }
    .stat { border-left: none; padding-left: 0; }
  }

  .wildlife-strip { display: grid; grid-template-columns: repeat(4, 1fr); gap: 0; }
  .wildlife-strip .ph { aspect-ratio: 4/5; }
  .wildlife-strip .fact {
    background: var(--cream-200);
    display: flex; align-items: center; padding: 30px;
    font-size: 1rem; color: var(--teal-900);
  }
  @media (max-width: 900px) { .wildlife-strip { grid-template-columns: repeat(2, 1fr); } }
</style>
</head>
<body>

<header class="site-header">
  <div class="container">
    <a href="index.html" class="brand">
      <span class="unf">UNF</span>
      <span class="full">UNITED NATURE</span>
      <span class="tag">FOUNDATION</span>
    </a>
    <button class="nav-toggle" aria-label="Toggle menu" aria-expanded="false">
      <span></span><span></span><span></span>
    </button>
    <nav class="main-nav">
      <a href="our-story.html">Our Story</a>
      <a href="canopy-crew.html">Canopy Crew</a>
      <a href="unf-projects.html">UNF Projects</a>
      <a href="donate.html">Donate</a>
    </nav>
    <div class="header-actions">
      <a href="join-now.html" class="btn btn-primary">Join Now</a>
    </div>
  </div>
</header>

<section class="join-hero ph">
  <div class="ph-label" style="position:absolute; top:0; left:0;">sunrise over rainforest canopy</div>
  <div class="container">
    <h1>Become a<br>Guardian of the<br><span class="amazon">Amazon</span></h1>
    <div class="btns">
      <a href="#ranger" class="btn">Amazon Ranger</a>
      <a href="#corporate" class="btn">Corporate Ranger</a>
    </div>
  </div>
</section>

<section class="quote-strip">
  <div class="quote-block">
    <span class="mark">&ldquo;</span>
    <p>Being a UNF member means knowing I'm part of something bigger - protecting life, cultures an our planets future.</p>
    <span class="who">- Michael, Amazon Ranger Member</span>
  </div>
  <div class="ph"><div class="ph-label">blue morpho butterfly on leaf</div></div>
  <div class="ph"><div class="ph-label">capybara wading in water</div></div>
  <div class="ph"><div class="ph-label">glass frog on leaf</div></div>
</section>

<section class="section" style="padding-bottom:20px;">
  <div class="tier-card ranger" id="ranger">
    <span class="kicker">For Juniors, Families and Gifts</span>
    <h2>Amazon Ranger</h2>
    <p>A one-off into the wild contribution.<br>Join the conservation crew, contribute towards 0.1 acre of land and get a Ranger Welcome Pack - perfect as a gift.</p>
    <span class="tags">JUNIOR FRIENDLY | GIFT OPTION | ONE OFF</span>
    <div class="price">£99.99</div>
    <div class="price-note">one off lifetime ranger</div>
    <a href="donate.html" class="btn">Become a Ranger</a>
  </div>

  <div class="tier-card corporate" id="corporate">
    <span class="kicker">For Businesses</span>
    <h2>Corporate Ranger</h2>
    <p>Protect the rainforest at scale.<br>Sponsor 2 - 100 acres, anchor your ESG story in measurable impact and stand among the businesses defending the Amazon.</p>
    <span class="tags">2-100 ACRES | ANNUAL PARTNERSHIP</span>
    <div class="price">£1000.00</div>
    <div class="price-note">per acre from £2000</div>
    <a href="donate.html" class="btn">Sponsor Acres</a>
  </div>
</section>

<section class="protect-banner ph">
  <div class="ph-label" style="position:absolute; top:0; right:0;">jungle river with jaguar face overlay</div>
  <div>
    <h2>TOGETHER,<br>WE PROTECT<br>WHAT MATTERS <em>MOST</em></h2>
  </div>
  <div class="stat"><div class="icon">🌱</div><div class="num">50,000+</div><div class="lbl">ACRES PROTECTED</div></div>
  <div class="stat"><div class="icon">🐾</div><div class="num">1,500+</div><div class="lbl">SPECIES SAFEGUARDED</div></div>
  <div class="stat"><div class="icon">☁️</div><div class="num">6M+</div><div class="lbl">TONS CO2 STORED</div></div>
</section>

<section class="wildlife-strip">
  <div class="ph"><div class="ph-label">sloth hanging from branch</div></div>
  <div class="ph"><div class="ph-label">capuchin monkey on log</div></div>
  <div class="ph"><div class="ph-label">blue morpho butterfly on leaf</div></div>
  <div class="ph"><div class="ph-label">river dolphin surfacing</div></div>
  <div class="fact">The Amazon Rainforest is home to more than 3 million species of plants and animals, including around 10% of all known wildlife species on Earth.</div>
</section>

<footer class="site-footer">
  <div class="container">
    <div class="footer-signup">
      <h2>Keep In touch</h2>
      <p>Sign up to keep up to date and informed about our continued conservation work in the Amazon and how you can help United Nature Foundation.</p>
      <hr class="footer-rule">
      <form class="newsletter-form">
        <div class="signup-row">
          <input type="email" placeholder="Enter your email" required>
        </div>
        <div class="checkbox-row">
          <input type="checkbox" id="sub"><label for="sub">Yes, subscribe me to your newsletter.</label>
          <button type="submit" class="btn btn-primary" style="margin-left:auto;">Sign Up</button>
        </div>
      </form>
    </div>
    <hr class="footer-rule">
    <div class="footer-links">
      <div>
        <a href="#">Get Involved</a>
        <a href="donate.html">Donate Now</a>
      </div>
      <div>
        <a href="#">Homen De Selva</a>
        <a href="#">UNF HQ</a>
      </div>
      <div>
        <a href="#">Terms &amp; Conditions</a>
        <a href="#">Privacy Policy</a>
        <a href="#">Accessibility Statement</a>
      </div>
    </div>
    <div class="footer-bottom">© 2026 by United Nature Foundation.</div>
  </div>
</footer>

<script src="js/main.js"></script>
</body>
</html>

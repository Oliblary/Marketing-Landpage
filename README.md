<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Oliblary | Start Free with Systeme.io</title>

<style>
* { margin:0; padding:0; box-sizing:border-box; font-family: Arial,sans-serif; }
body { background:#f9f9f9; color:#333; line-height:1.6; }
.container { width:90%; max-width:1200px; margin:0 auto; }

/* HERO */
header {
  min-height: 95vh;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:#fff;
  padding:40px 20px;
  position:relative;
  overflow:hidden;

  background:
    linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.65)),
    url('https://images.pexels.com/photos/4386370/pexels-photo-4386370.jpeg') center/cover no-repeat;
}

.hero-content { max-width:700px; z-index:2; }
header h1 { font-size:3rem; margin-bottom:20px; }
header p { font-size:1.3rem; margin-bottom:25px; }

.cta-btn {
  display:inline-block;
  padding:18px 45px;
  background:#00A0ff;
  color:#fff;
  border-radius:8px;
  text-decoration:none;
  font-weight:bold;
  transition:0.3s;
}
.cta-btn:hover { background:#0080cc; }

.subtext { display:block; margin-top:10px; font-size:0.9rem; opacity:0.8; }

.hero-image { margin-top:40px; z-index:2; }
.hero-image img {
  width:100%;
  max-width:850px;
  border-radius:12px;
  box-shadow:0 25px 60px rgba(0,0,0,0.5);
}

/* FEATURES */
.features {
  display:flex;
  flex-wrap:wrap;
  gap:20px;
  margin:60px 0;
}

.feature {
  flex:1;
  min-width:250px;
  background:#fff;
  padding:30px;
  border-radius:12px;
  text-align:center;
  box-shadow:0 6px 18px rgba(0,0,0,0.12);
}

.feature img { width:70px; margin-bottom:15px; }
.feature h3 { color:#4a90e2; margin-bottom:10px; }

/* BONUS */
.bonus {
  background:#fff3e6;
  padding:40px;
  border-radius:12px;
  margin:50px 0;
  text-align:center;
}

/* TRUST / SOCIAL PROOF */
.trust {
  background:#e6f2ff;
  padding:50px 20px;
  border-radius:12px;
  margin:60px 0;
  text-align:center;
}

.trust h2 {
  margin-bottom:20px;
  color:#222;
}

.trust p {
  max-width:800px;
  margin:0 auto;
  font-size:1.05rem;
}

/* CTA */
.cta {
  background:#ff6f61;
  color:#fff;
  text-align:center;
  padding:60px 20px;
  border-radius:12px;
  margin:60px 0;
}

.cta input {
  padding:16px;
  margin:10px;
  border:none;
  border-radius:6px;
}


<!-- VERIFIED TESTIMONIALS -->
<section class="testimonials">
  <h2>Trusted by Real Users Worldwide</h2>

  <div class="testimonial-grid">

    <!-- CARD 1 -->
    <div class="testimonial-card">
      <div class="review-top">
        <img src="https://images.unsplash.com/photo-1527980965255-d3b416303d12?auto=format&fit=crop&w=200&q=80">
        <div>
          <h4>Daniel M.</h4>
          <span class="role">Beginner Marketer</span>
        </div>
      </div>

      <div class="stars">★★★★★</div>

      <p>
        “Systeme.io completely changed how I run my business. I built my first funnel in one day and started getting results almost immediately.”
      </p>

      <div class="badge">✔ Verified User</div>
    </div>

    <!-- CARD 2 -->
    <div class="testimonial-card">
      <div class="review-top">
        <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=200&q=80">
        <div>
          <h4>Sarah K.</h4>
          <span class="role">Course Creator</span>
        </div>
      </div>

      <div class="stars">★★★★★</div>

      <p>
        “I’m not tech-savvy, but this platform made everything simple. My course and emails are now fully automated.”
      </p>

      <div class="badge">✔ Verified User</div>
    </div>

    <!-- CARD 3 -->
    <div class="testimonial-card">
      <div class="review-top">
        <img src="https://images.unsplash.com/photo-1552374196-c4e7ffc6e126?auto=format&fit=crop&w=200&q=80">
        <div>
          <h4>James R.</h4>
          <span class="role">Digital Entrepreneur</span>
        </div>
      </div>

      <div class="stars">★★★★★</div>

      <p>
        “Switching to Systeme.io simplified everything. Funnels, emails, and product delivery now run automatically.”
      </p>

      <div class="badge">✔ Verified User</div>
    </div>

  </div>
</section>
}

/* FAQ */
.faq {
  background:#fff;
  padding:60px 20px;
  border-radius:12px;
  margin:60px 0;
}

.faq h2 {
  text-align:center;
  margin-bottom:30px;
}

.faq-item {
  margin-bottom:20px;
  padding:20px;
  background:#f7f7f7;
  border-radius:10px;
}

.faq-item h4 {
  color:#4a90e2;
  margin-bottom:8px;
}

/* FOOTER */
footer {
  text-align:center;
  padding:30px;
  background:#333;
  color:#fff;
}

/* MOBILE */
@media(max-width:768px){
  .features { flex-direction:column; }
  header h1 { font-size:2.2rem; }
}
</style>
</head>

<body>

<!-- HERO -->
<header>
  <div class="hero-content">
    <h1>Build Your Online Business with Systeme.io — 100% FREE</h1>
    <p>
      The all-in-one platform to build funnels, automate emails, sell products, and grow your income online.
    </p>

    <a href="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92" class="cta-btn">
      Start Free with Systeme.io
    </a>
    <span class="subtext">No credit card required</span>
  </div>

  <div class="hero-image">
    <img src="https://images.pexels.com/photos/6476589/pexels-photo-6476589.jpeg" alt="Systeme.io dashboard preview">
  </div>
</header>

<div class="container">

<!-- FEATURES -->
<section class="features">

  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/190/190411.png">
    <h3>Sales Funnels</h3>
    <p>Build high-converting funnels with simple drag-and-drop tools.</p>
  </div>

  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/3050/3050650.png">
    <h3>Email Marketing</h3>
    <p>Automate emails and turn leads into customers on autopilot.</p>
  </div>

  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/1040/1040211.png">
    <h3>Online Courses</h3>
    <p>Create and sell courses with automated delivery systems.</p>
  </div>

  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/1170/1170576.png">
    <h3>Digital Products</h3>
    <p>Sell ebooks, downloads, and coaching with built-in checkout.</p>
  </div>

  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/1828/1828919.png">
    <h3>Membership Sites</h3>
    <p>Create exclusive paid communities and content access areas.</p>
  </div>

  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png">
    <h3>Affiliate System</h3>
    <p>Let others promote your products and grow your income faster.</p>
  </div>

</section>

<!-- BONUS -->
<section class="bonus">
  <h2>Why Systeme.io Works</h2>
  <p>
    Most beginners fail because they juggle too many tools.<br><br>
    <strong>Systeme.io replaces everything with one simple system built for speed and simplicity.</strong>
  </p>
</section>

<!-- TRUST / SOCIAL PROOF -->
<section class="trust">
  <h2>Trusted by Thousands of Online Entrepreneurs</h2>
  <p>
    Systeme.io is used globally by beginners and marketers to build businesses without technical stress.
    It combines everything needed to start, grow, and automate online income in one platform.
  </p>
</section>

<!-- CTA -->
<section class="cta">
  <h2>Start Building Your Online Income System Today</h2>

  <form action="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92" target="_blank">
    <input type="email" placeholder="Enter your email" required>
    <input type="submit" value="Start Free Now">
  </form>
</section>

<!-- FAQ -->
<section class="faq">
  <h2>Frequently Asked Questions</h2>

  <div class="faq-item">
    <h4>Is Systeme.io really free?</h4>
    <p>Yes. You can start with a free plan that includes funnels, email marketing, and basic automation.</p>
  </div>

  <div class="faq-item">
    <h4>Do I need technical skills?</h4>
    <p>No. Everything is beginner-friendly with drag-and-drop tools and templates.</p>
  </div>

  <div class="faq-item">
    <h4>Can I make money with it?</h4>
    <p>Yes. You can sell products, courses, and build automated funnels for income generation.</p>
  </div>

</section>

</div>

<footer>
  <p>© 2026 Oliblary</p>
  <p>Affiliate disclosure: We may earn a commission if you sign up.</p>
</footer>

</body>
</html>

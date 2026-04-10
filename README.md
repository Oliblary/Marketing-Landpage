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
  position: relative;
  min-height: 90vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: #fff;
  background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260') center/cover no-repeat;
}
header .hero-content { max-width:700px; animation: fadeInDown 1.5s ease-out; }
header h1 { font-size:3rem; margin-bottom:20px; }
header p { font-size:1.3rem; margin-bottom:30px; }
header a.cta-btn {
  display:inline-block; padding:18px 45px; font-size:1.2rem; background:#00A0ff; color:#fff; border-radius:8px; font-weight:bold; text-decoration:none; transition:0.3s;
}
header a.cta-btn:hover { background:#0080cc; }

@keyframes fadeInDown { from { opacity:0; transform:translateY(-30px);} to { opacity:1; transform:translateY(0);} }

/* FEATURES */
.features { display:flex; flex-wrap:wrap; justify-content:space-between; gap:20px; margin:60px 0; }
.feature { flex:1 1 30%; background:#fff; padding:30px; border-radius:12px; text-align:center; box-shadow:0 6px 18px rgba(0,0,0,0.12); transition:transform 0.4s; }
.feature:hover { transform:translateY(-10px); box-shadow:0 10px 25px rgba(0,0,0,0.18); }
.feature img { width:80px; margin-bottom:20px; }
.feature h3 { color:#4a90e2; margin-bottom:15px; }
.feature p { color:#555; font-size:1rem; }

/* PLAN COMPARISON */
.plans { margin:60px 0; display:flex; flex-wrap:wrap; justify-content:center; gap:20px; }
.plan { background:#fff; flex:1 1 300px; padding:30px; border-radius:12px; text-align:center; box-shadow:0 6px 18px rgba(0,0,0,0.12); transition:transform 0.3s; }
.plan:hover { transform:translateY(-8px); }
.plan h3 { color:#4a90e2; margin-bottom:15px; }
.plan .price { font-size:2rem; font-weight:bold; margin-bottom:20px; }
.plan ul { list-style:none; margin-bottom:20px; color:#555; }
.plan ul li { margin-bottom:12px; }
.plan a { display:inline-block; padding:15px 30px; background:#00A0ff; color:#fff; border-radius:8px; text-decoration:none; font-weight:bold; transition:0.3s; }
.plan a:hover { background:#0080cc; }

/* TESTIMONIALS */
.testimonials { background:#fff; padding:60px 20px; border-radius:12px; box-shadow:0 6px 18px rgba(0,0,0,0.12); margin-bottom:60px; }
.testimonial { text-align:center; margin-bottom:40px; }
.testimonial img { border-radius:50%; width:80px; margin-bottom:15px; }
.testimonial p { font-style:italic; margin-bottom:10px; color:#555; }
.testimonial h4 { color:#4a90e2; }

/* TRUST LOGOS */
.trust { background:#e6f2ff; padding:50px 20px; text-align:center; border-radius:12px; margin-bottom:40px; }
.trust h3 { color:#4a90e2; margin-bottom:30px; }
.trust .logos { display:flex; justify-content:center; flex-wrap:wrap; gap:40px; }
.trust .logos img { height:50px; filter: grayscale(100%); transition:0.3s; }
.trust .logos img:hover { filter:none; }

/* BONUS */
.bonus { background:#fff3e6; padding:40px 20px; border-radius:12px; margin-bottom:50px; box-shadow:0 6px 18px rgba(0,0,0,0.1); }
.bonus h3 { color:#ff6f61; margin-bottom:20px; }
.bonus p { font-size:1.1rem; color:#555; }

/* CTA */
.affiliate-disclaimer { text-align:center; font-size:0.85rem; color:#555; margin-bottom:20px; }
.cta { background:#ff6f61; color:#fff; text-align:center; padding:60px 20px; border-radius:12px; margin-bottom:60px; }
.cta h2 { font-size:2.2rem; margin-bottom:25px; }
.cta form { display:flex; flex-wrap:wrap; justify-content:center; gap:12px; margin-top:20px; }
.cta input[type="email"] { padding:16px; border-radius:6px; border:none; width:300px; max-width:100%; font-size:1rem; }
.cta input[type="submit"] { padding:16px 35px; border-radius:6px; border:none; background:#333; color:#fff; font-weight:bold; cursor:pointer; transition:0.3s; }
.cta input[type="submit"]:hover { background:#555; }

/* FOOTER */
footer { text-align:center; padding:35px 0; background:#333; color:#fff; font-size:0.9rem; }
footer p:last-child { font-size:0.8rem; color:#ccc; margin-top:8px; }

/* MEDIA QUERIES */
@media (max-width:992px){
.features, .plans { flex-direction:column; align-items:center; }
.feature, .plan { flex:1 1 90%; }
header h1 { font-size:2.2rem; }
header p { font-size:1.1rem; }
header a.cta-btn { padding:15px 30px; font-size:1rem; }
}
</style>
</head>
<body>

<!-- HERO -->
<header>
  <div class="hero-content">
    <h1>Start Free & Grow Your Business with Systeme.io</h1>
    <p>All-in-one platform for funnels, email automation, courses, and affiliate management. Test it for free and upgrade as you grow.</p>
    <a href="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92" target="_blank" class="cta-btn">Start Free Today</a>
  </div>
</header>

<div class="container">

<!-- FEATURES -->
<section class="features">
  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/190/190411.png">
    <h3>High-Converting Funnels</h3>
    <p>Create funnels that convert visitors into paying customers fast.</p>
  </div>
  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/3050/3050650.png">
    <h3>Email Automation</h3>
    <p>Automate your marketing to nurture leads and increase revenue.</p>
  </div>
  <div class="feature">
    <img src="https://cdn-icons-png.flaticon.com/512/1040/1040211.png">
    <h3>Sell Courses & Products</h3>
    <p>Monetize your knowledge with courses and digital products.</p>
  </div>
</section>

<!-- PLAN COMPARISON -->
<section class="plans">
  <div class="plan">
    <h3>Free Plan</h3>
    <div class="price">$0/month</div>
    <ul>
      <li>1,000 contacts</li>
      <li>3 funnels</li>
      <li>Email automation basic</li>
      <li>1 membership site</li>
    </ul>
    <a href="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92" target="_blank">Start Free</a>
  </div>
  <div class="plan">
    <h3>Startup Plan</h3>
    <div class="price">$27/month</div>
    <ul>
      <li>10,000 contacts</li>
      <li>10 funnels</li>
      <li>Advanced email automation</li>
      <li>Unlimited membership sites</li>
      <li>Affiliate program access</li>
    </ul>
    <a href="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92" target="_blank">Upgrade Anytime</a>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials">
  <div class="testimonial">
    <img src="https://randomuser.me/api/portraits/men/32.jpg">
    <p>"I started free and within 2 months upgraded to paid. My business automated like never before!"</p>
    <h4>- John D., Entrepreneur</h4>
  </div>
  <div class="testimonial">
    <img src="https://randomuser.me/api/portraits/women/44.jpg">
    <p>"The free plan allowed me to test everything. Upgrading was the best decision for growth!"</p>
    <h4>- Sarah L., Business Owner</h4>
  </div>
</section>

<!-- TRUST LOGOS -->
<section class="trust">
  <h3>Trusted by Entrepreneurs Worldwide</h3>
  <div class="logos">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Forbes_logo.svg">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/CNN_logo.svg">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Inc._Magazine_logo.svg">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/TechCrunch_logo.svg">
  </div>
</section>

<!-- BONUS -->
<section class="bonus">
  <h3>🎁 Limited-Time Bonus</h3>
  <p>Start free via Oliblary today and get the <strong>Ultimate Funnel Builder Guide</strong> to maximize your growth and revenue.</p>
</section>

<!-- AFFILIATE DISCLAIMER ABOVE CTA -->
<p class="affiliate-disclaimer">
  Disclosure: Oliblary is an affiliate of Systeme.io. We may earn a commission if you sign up via our links, at no extra cost to you.
</p>

<!-- CTA -->
<section class="cta">
  <h2>Start Free Today & Upgrade When Ready</h2>
  <form action="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92" method="get" target="_blank">
    <input type="email" name="email" placeholder="Enter your email" required>
    <input type="submit" value="Start Free Now">
  </form>
</section>

</div>

<!-- FOOTER -->
<footer>
  <p>&copy; 2026 Oliblary. All rights reserved.</p>
  <p>Disclosure: Oliblary is an affiliate of Systeme.io. We may earn a commission if you sign up via our links, at no extra cost to you.</p>
</footer>

</body>
</html>

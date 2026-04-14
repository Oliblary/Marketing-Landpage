<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Oliblary | Build Your Online Business with Systeme.io</title>

<style>
:root{
  --primary:#00A0ff;
  --dark:#111;
  --light:#fff;
  --gray:#555;
  --shadow:0 10px 30px rgba(0,0,0,0.12);
}

*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif;}
body{background:#f7f7f7;color:#333;line-height:1.6;}
.container{width:90%;max-width:1100px;margin:auto;}

/* GLOBAL */
section{padding:70px 0;}

/* HERO */
.hero{
  min-height:95vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:#fff;
  padding:40px 20px;
  background:
    linear-gradient(rgba(0,0,0,0.65),rgba(0,0,0,0.65)),
    url('https://images.pexels.com/photos/4386370/pexels-photo-4386370.jpeg') center/cover no-repeat;
  position:relative;
}

.hero h1{font-size:3rem;margin-bottom:20px;}
.hero p{font-size:1.2rem;max-width:700px;margin:auto;margin-bottom:25px;}

.btn{
  display:inline-block;
  padding:16px 40px;
  background:var(--primary);
  color:#fff;
  border-radius:8px;
  text-decoration:none;
  font-weight:bold;
}
.btn:hover{background:#0077cc;}

.subtext{display:block;margin-top:10px;font-size:0.9rem;opacity:0.8;}

/* HERO MOCKUP */
.hero-mockup{
  margin-top:40px;
}
.hero-mockup img{
  width:100%;
  max-width:850px;
  border-radius:12px;
  box-shadow:0 25px 60px rgba(0,0,0,0.5);
}

/* FEATURES */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.card{
  background:#fff;
  padding:25px;
  border-radius:12px;
  box-shadow:var(--shadow);
  text-align:center;
}

.card img{width:60px;margin-bottom:15px;}
.card h3{color:#2c6fff;margin-bottom:10px;}
.card p{color:var(--gray);}

/* IMAGE STRIP */
.showcase img{
  width:100%;
  border-radius:12px;
  box-shadow:var(--shadow);
}

/* TRUST */
.trust{
  background:#eaf4ff;
  text-align:center;
}
.trust h2{margin-bottom:10px;}
.trust p{max-width:700px;margin:auto;color:var(--gray);}
.stats{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:40px;
  margin-top:30px;
}
.stats div h3{color:var(--primary);font-size:1.8rem;}

/* TESTIMONIALS */
.testimonials{
  background:#fff;
  text-align:center;
}
.testimonial{
  max-width:500px;
  margin:20px auto;
  padding:20px;
  box-shadow:var(--shadow);
  border-radius:12px;
}
.testimonial img{
  width:70px;
  border-radius:50%;
  margin-bottom:10px;
}

/* CTA */
.cta{
  background:#ff6f61;
  color:#fff;
  text-align:center;
}
.cta input{
  padding:15px;
  border:none;
  border-radius:6px;
  margin:5px;
}

/* EXIT POPUP */
.popup{
  position:fixed;
  top:0;left:0;
  width:100%;height:100%;
  background:rgba(0,0,0,0.7);
  display:none;
  align-items:center;
  justify-content:center;
}

.popup-content{
  background:#fff;
  padding:30px;
  border-radius:12px;
  text-align:center;
  max-width:400px;
}
.popup-content h2{margin-bottom:10px;}
.popup-content button{
  margin-top:15px;
  padding:12px 25px;
  background:var(--primary);
  border:none;
  color:#fff;
  border-radius:6px;
  cursor:pointer;
}
</style>
</head>

<body>

<!-- HERO -->
<header class="hero">
  <div>
    <h1>Build a Real Online Business with Systeme.io — Start Free Today</h1>
    <p>
      Create funnels, automate emails, and sell digital products using one simple platform designed for beginners and professionals.
    </p>

    <a class="btn" href="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92">
      Start Free Now
    </a>
    <span class="subtext">No credit card required</span>

    <div class="hero-mockup">
      <img src="https://images.pexels.com/photos/6476589/pexels-photo-6476589.jpeg" alt="Systeme.io dashboard">
    </div>
  </div>
</header>

<div class="container">

<!-- FEATURES -->
<section>
<div class="grid">

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/190/190411.png">
<h3>Funnels That Convert</h3>
<p>Build high-performing sales funnels in minutes.</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/3050/3050650.png">
<h3>Email Automation</h3>
<p>Automatically follow up and close more sales.</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/1040/1040211.png">
<h3>Sell Digital Products</h3>
<p>Launch courses and earn online income easily.</p>
</div>

</div>
</section>

<!-- SHOWCASE -->
<section class="showcase">
<img src="https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg">
</section>

<!-- TRUST -->
<section class="trust">
<h2>Trusted by Entrepreneurs Worldwide</h2>
<p>
Thousands use Systeme.io to build automated businesses and generate income online.
</p>

<div class="stats">
<div>
<h3>100K+</h3>
<p>Users</p>
</div>

<div>
<h3>All-in-One</h3>
<p>Platform</p>
</div>

<div>
<h3>Free Plan</h3>
<p>No Credit Card</p>
</div>
</div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials">

<div class="testimonial">
<img src="https://randomuser.me/api/portraits/men/32.jpg">
<p>"I built my first funnel in 2 days. Everything is simple."</p>
<h4>- John D.</h4>
</div>

<div class="testimonial">
<img src="https://randomuser.me/api/portraits/women/44.jpg">
<p>"Systeme.io replaced 3 tools for me. Very powerful."</p>
<h4>- Sarah L.</h4>
</div>

</section>

<!-- CTA -->
<section class="cta">
<h2>Start Free Today — No Credit Card Required</h2>

<form action="https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92">
<input type="email" placeholder="Enter your email" required>
<input type="submit" value="Get Started">
</form>
</section>

</div>

<!-- EXIT POPUP -->
<div class="popup" id="popup">
  <div class="popup-content">
    <h2>Before You Go</h2>
    <p>Start building your online business with Systeme.io for free.</p>
    <button onclick="window.location.href='https://systeme.io/?sa=sa0266558169ffdca98644ff784ec3a16590d5ef92'">
      Start Free
    </button>
  </div>
</div>

<script>
let shown=false;
document.addEventListener("mouseleave", function(e){
  if(e.clientY < 10 && !shown){
    document.getElementById("popup").style.display="flex";
    shown=true;
  }
});
</script>

</body>
</html>

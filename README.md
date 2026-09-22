# Zubotix
zubotixai-site/
│
├── index.html   (main page)
├── style.css    (theme + animations)
└── assets/      (logo, images)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ZubotixAI</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header -->
  <header class="fade-in">
    <img src="assets/zubotix-logo.png" alt="Zubotix Logo" class="logo pulse">
    <h1>ZUBOTIX AI</h1>
    <p>Smart Solutions. Limitless Possibilities.</p>
  </header>

  <!-- Navigation -->
  <nav class="navbar slide-down">
    <a href="#features">Features</a>
    <a href="#plans">Plans</a>
    <a href="#signup">Sign Up</a>
  </nav>

  <!-- Normal Plan -->
  <section id="features" class="fade-up">
    <h2>Normal Plan Features</h2>
    <ul>
      <li>✔ Chat & problem solving</li>
      <li>✔ 7 images/day</li>
      <li>✔ 4 videos/day</li>
      <li>✔ 3 websites/60 days</li>
      <li>✔ 2 apps/month</li>
      <li>✔ Language learning basics</li>
      <li>✔ Courses + certificate</li>
      <li>✔ Day & budget planner</li>
    </ul>
  </section>

  <!-- Premium Plan -->
  <section id="plans" class="fade-up">
    <h2>Premium Plan</h2>
    <ul>
      <li>🚀 Unlimited chat</li>
      <li>🚀 20 images/day</li>
      <li>🚀 15 videos/day</li>
      <li>🚀 10 websites/60 days</li>
      <li>🚀 5 apps/month</li>
      <li>🚀 Advanced language learning</li>
      <li>🚀 Full courses + certificates</li>
      <li>🚀 Priority support</li>
      <li>🚀 Analytics dashboard</li>
    </ul>
    <!-- Razorpay Payment Button -->
    <a href="https://razorpay.kyc.idfy.com/v2/captures?t=tt5kp4bAyabw&redirect_uri=https://easy.razorpay.com/onboarding" 
       class="btn bounce">Buy Premium</a>
  </section>

  <!-- Sign Up -->
  <section id="signup" class="fade-up">
    <h2>Sign Up</h2>
    <form>
      <input type="email" placeholder="Email" required>
      <input type="date" required>
      <select>
        <option>Male</option>
        <option>Female</option>
        <option>Other</option>
      </select>
      <button class="btn glow">Submit</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    © 2026 ZubotixAI | Smart Solution Limitless Possibilities
  </footer>
</body>
</html>
body {
  font-family: 'Poppins', sans-serif;
  margin: 0; padding: 0;
  background: #fdfdfd;
  color: #222;
  scroll-behavior: smooth;
}

header {
  background: linear-gradient(90deg,#4facfe,#8e54e9);
  text-align: center;
  padding: 50px;
  color: #fff;
}

.logo { width: 120px; }

/* Navbar */
.navbar {
  position: sticky; top: 0;
  background: #fff; text-align: center;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}
.navbar a {
  color: #4facfe; margin: 15px;
  text-decoration: none; font-weight: bold;
  transition: color 0.3s ease;
}
.navbar a:hover { color: #8e54e9; }

/* Sections */
section { padding: 40px; text-align: center; }
ul { list-style: none; padding: 0; }
li { margin: 8px 0; }

/* Buttons */
.btn {
  background: #4facfe; color: #fff;
  padding: 12px 25px; border-radius: 30px;
  border: none; cursor: pointer;
  text-decoration: none; font-weight: bold;
  transition: all 0.3s ease;
}
.btn:hover { background: #8e54e9; transform: scale(1.05); }

/* Footer */
footer {
  background: #222; color: #fff;
  text-align: center; padding: 20px;
}

/* Animations */
.fade-in { animation: fadeIn 2s ease; }
.fade-up { animation: fadeUp 2s ease; }
.slide-down { animation: slideDown 1.5s ease; }
.pulse { animation: pulse 2s infinite; }
.bounce:hover { animation: bounce 0.6s; }
.glow:hover { box-shadow: 0 0 15px #8e54e9; }

@keyframes fadeIn { from {opacity:0;} to {opacity:1;} }
@keyframes fadeUp { from {opacity:0; transform:translateY(30px);} to {opacity:1; transform:translateY(0);} }
@keyframes slideDown { from {transform:translateY(-50px); opacity:0;} to {transform:translateY(0); opacity:1;} }
@keyframes pulse { 0% {transform:scale(1);} 50% {transform:scale(1.1);} 100% {transform:scale(1);} }
@keyframes bounce { 0%,100% {transform:translateY(0);} 50% {transform:translateY(-10px);} }

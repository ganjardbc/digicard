<template>
  <div>
    <!-- Header -->
    <header class="header">
      <div class="container">
        <h1 class="logo">DigiCard</h1>
        <nav class="nav">
          <a href="#categories">Categories</a>
          <a href="#features">Features</a>
          <a href="#pricing">Pricing</a>
          <a href="#feedback">Feedback</a>
        </nav>
      </div>
    </header>

    <!-- Banner -->
    <section class="banner">
      <div class="container">
        <h2>Your Digital Identity, Simplified</h2>
        <p>Create, share, and manage your digital cards effortlessly.</p>
        <button>Get Started</button>
      </div>
    </section>

    <!-- Categories -->
    <section id="categories" class="categories">
      <div class="container">
        <h2>Card Categories</h2>
        <div class="grid">
          <div class="card">Business Cards</div>
          <div class="card">Event Invitations</div>
          <div class="card">Membership Cards</div>
          <div class="card">Gift Cards</div>
        </div>
      </div>
    </section>

    <!-- Features -->
    <section id="features" class="features">
      <div class="container">
        <h2>Platform Features</h2>
        <ul>
          <li>Customizable Designs</li>
          <li>QR Code Integration</li>
          <li>Analytics & Tracking</li>
          <li>Easy Sharing</li>
        </ul>
      </div>
    </section>

    <!-- Pricing -->
    <section id="pricing" class="pricing">
      <div class="container">
        <h2>Pricing Plans</h2>
        <div class="plans">
          <div class="plan">
            <h3>Free</h3>
            <p>$0/month</p>
            <ul>
              <li>Basic Templates</li>
              <li>1 Card</li>
              <li>Email Support</li>
            </ul>
          </div>
          <div class="plan">
            <h3>Pro</h3>
            <p>$9.99/month</p>
            <ul>
              <li>All Templates</li>
              <li>Unlimited Cards</li>
              <li>Priority Support</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Feedback -->
    <section id="feedback" class="feedback">
      <div class="container">
        <h2>What Our Users Say</h2>
        <div class="reviews">
          <blockquote>"DigiCard made networking so easy!" — Alex</blockquote>
          <blockquote>"A game-changer for my business cards." — Priya</blockquote>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <p>&copy; 2025 DigiCard. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
// No specific logic needed for static homepage
</script>

<style scoped>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

/* Header */
.header {
  background: #1a1a1a;
  color: #fff;
  padding: 1rem 0;
}
.logo {
  font-size: 1.5rem;
}
.nav {
  display: flex;
  gap: 1rem;
}
.nav a {
  color: white;
  text-decoration: none;
}
.header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* Banner */
.banner {
  background: linear-gradient(120deg, #00bcd4, #3f51b5);
  color: white;
  text-align: center;
  padding: 3rem 1rem;
}
.banner h2 {
  font-size: 2.5rem;
}
.banner button {
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background: white;
  color: #3f51b5;
  border: none;
  cursor: pointer;
}

/* Categories */
.categories {
  padding: 2rem 0;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 1rem;
}
.card {
  background: #f3f3f3;
  padding: 1rem;
  text-align: center;
  border-radius: 8px;
}

/* Features */
.features {
  background: #f9f9f9;
  padding: 2rem 0;
}
.features ul {
  list-style: none;
  padding: 0;
}
.features li {
  padding: 0.5rem 0;
}

/* Pricing */
.pricing {
  padding: 2rem 0;
}
.plans {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.plan {
  background: #e0e0e0;
  padding: 1rem;
  border-radius: 8px;
  text-align: center;
}
.plan ul {
  list-style: none;
  padding: 0;
}
.plan li {
  padding: 0.25rem 0;
}
@media(min-width: 768px) {
  .plans {
    flex-direction: row;
    justify-content: space-around;
  }
}

/* Feedback */
.feedback {
  background: #fff;
  padding: 2rem 0;
}
.reviews blockquote {
  font-style: italic;
  margin: 1rem 0;
}

/* Footer */
.footer {
  background: #1a1a1a;
  color: white;
  text-align: center;
  padding: 1rem 0;
}
</style>
---
layout: home
---

<div class="hero">
  <img src="1702584574588.jpeg" alt="Rahib Amin" class="profile-image">
  <h1>Rahib Amin</h1>
  <h2>Technical Product Manager & Cloud Architect</h2>
</div>

<div class="expertise-areas">
  <div class="expertise-card">
    <h3>🚀 Product Strategy</h3>
    <p>Driving innovation through user-centered product development and strategic roadmap planning</p>
  </div>
  <div class="expertise-card">
    <h3>☁️ Cloud Architecture</h3>
    <p>Designing scalable, secure cloud solutions that power modern enterprises</p>
  </div>
  <div class="expertise-card">
    <h3>🔄 Platform Strategy</h3>
    <p>Enabling digital transformation through comprehensive platform strategies</p>
  </div>
</div>

<style>
:root {
  /* Color System */
  --primary-dark: #1a1c23;
  --surface-dark: #22242c;
  --accent-blue: #60a5fa;
  --accent-purple: #818cf8;
  --text-primary: #f8fafc;
  --text-secondary: #94a3b8;
  
  /* Typography */
  --font-main: -apple-system, BlinkMacSystemFont, 'Inter', 'Segoe UI', Roboto, sans-serif;
  --font-headers: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Inter', sans-serif;
}

body {
  background-color: var(--primary-dark);
  color: var(--text-primary);
  font-family: var(--font-main);
  line-height: 1.6;
}

.hero {
  text-align: center;
  padding: 5rem 2rem;
  background: linear-gradient(135deg, var(--surface-dark) 0%, var(--primary-dark) 100%);
  color: var(--text-primary);
  border-radius: 16px;
  margin: 2rem auto;
  max-width: 1200px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
}

.hero h1 {
  font-family: var(--font-headers);
  font-size: 3rem;
  font-weight: 700;
  margin: 1rem 0;
  background: linear-gradient(135deg, var(--accent-blue), var(--accent-purple));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.hero h2 {
  font-family: var(--font-headers);
  font-size: 1.5rem;
  color: var(--text-secondary);
  font-weight: 500;
}

.profile-image {
  width: 220px;
  height: 220px;
  border-radius: 50%;
  border: 4px solid var(--accent-blue);
  margin-bottom: 2rem;
  box-shadow: 0 0 25px rgba(96, 165, 250, 0.3);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.profile-image:hover {
  transform: scale(1.02);
  box-shadow: 0 0 30px rgba(96, 165, 250, 0.4);
}

.expertise-areas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2rem;
  margin: 3rem auto;
  max-width: 1200px;
  padding: 0 2rem;
}

.expertise-card {
  padding: 2rem;
  border-radius: 12px;
  background: var(--surface-dark);
  color: var(--text-primary);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  border: 1px solid rgba(255, 255, 255, 0.1);
  position: relative;
  overflow: hidden;
}

.expertise-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--accent-blue), var(--accent-purple));
  opacity: 0;
  transition: opacity 0.3s ease;
}

.expertise-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 20px rgba(0, 0, 0, 0.2);
  border-color: rgba(255, 255, 255, 0.2);
}

.expertise-card:hover::before {
  opacity: 1;
}

.expertise-card h3 {
  font-family: var(--font-headers);
  font-size: 1.5rem;
  font-weight: 600;
  color: var(--accent-blue);
  margin-bottom: 1rem;
}

.expertise-card p {
  color: var(--text-secondary);
  font-size: 1.1rem;
  line-height: 1.6;
}

@media (max-width: 768px) {
  .hero h1 {
    font-size: 2.5rem;
  }
  
  .hero h2 {
    font-size: 1.25rem;
  }
  
  .expertise-areas {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
}
</style>

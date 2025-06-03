---
layout: home
---

<div class="hero">
  <div class="hero-background">
    <div class="geometric-shapes"></div>
  </div>
  <div class="hero-content">
    <div class="profile-container">
      <img src="1702584574588.jpeg" alt="Rahib Amin" class="profile-image">
      <div class="profile-glow"></div>
    </div>
    <h1>Rahib Amin</h1>
    <h2>Technical Product Manager & Cloud Architect</h2>
    <div class="social-links">
      <a href="https://github.com/rahibamin" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/rahib-amin" target="_blank">LinkedIn</a>
      <a href="https://twitter.com/rahibamin" target="_blank">Twitter</a>
    </div>
  </div>
</div>

<div class="expertise-areas">
  <div class="expertise-card">
    <div class="card-glow"></div>
    <div class="icon">🚀</div>
    <h3>Product Strategy</h3>
    <p>Driving innovation through user-centered product development and strategic roadmap planning</p>
    <div class="card-footer">
      <span class="learn-more">Learn More →</span>
    </div>
  </div>
  <div class="expertise-card">
    <div class="card-glow"></div>
    <div class="icon">☁️</div>
    <h3>Cloud Architecture</h3>
    <p>Designing scalable, secure cloud solutions that power modern enterprises</p>
    <div class="card-footer">
      <span class="learn-more">Learn More →</span>
    </div>
  </div>
  <div class="expertise-card">
    <div class="card-glow"></div>
    <div class="icon">🔄</div>
    <h3>Platform Strategy</h3>
    <p>Enabling digital transformation through comprehensive platform strategies</p>
    <div class="card-footer">
      <span class="learn-more">Learn More →</span>
    </div>
  </div>
</div>

<style>
:root {
  /* Updated Color System */
  --bg-deep: #0a0c10;
  --bg-surface: #161b22;
  --card-bg: #21262d;
  --accent-primary: #58a6ff;
  --accent-secondary: #bc8cff;
  --text-bright: #ffffff;
  --text-primary: #c9d1d9;
  --text-secondary:rgb(223, 225, 228);
  --border-color: #30363d;
  
  /* Unified Typography */
  --font-main: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;

  /* Gradient Colors */
  --gradient-1: #0ea5e9;
  --gradient-2: #6366f1;
  --gradient-3: #a855f7;

  /* New CSS Variables */
  --card-bg-rgb: 33, 38, 45;
  --gradient-1-rgb: 14, 165, 233;
}

body {
  background: var(--bg-deep);
  color: var(--text-primary);
  font-family: var(--font-main);
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

.page-content {
  background: linear-gradient(
    to bottom,
    var(--bg-deep) 0%,
    var(--bg-surface) 100%
  );
  min-height: 100vh;
  padding: 2rem 0;
}

.hero {
  position: relative;
  text-align: center;
  padding: 6rem 2rem;
  background: var(--card-bg);
  color: var(--text-bright);
  border-radius: 16px;
  margin: 2rem auto;
  max-width: 1200px;
  overflow: hidden;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.4);
  border: 1px solid var(--border-color);
}

.hero-background {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  overflow: hidden;
  opacity: 0.1;
}

.geometric-shapes {
  position: absolute;
  top: -50%;
  left: -50%;
  right: -50%;
  bottom: -50%;
  background: 
    radial-gradient(circle at 20% 20%, var(--gradient-1) 0%, transparent 50%),
    radial-gradient(circle at 80% 80%, var(--gradient-2) 0%, transparent 50%),
    radial-gradient(circle at 50% 50%, var(--gradient-3) 0%, transparent 50%);
  animation: rotate 30s linear infinite;
}

.hero-content {
  position: relative;
  z-index: 1;
}

.profile-container {
  position: relative;
  width: 220px;
  height: 220px;
  margin: 0 auto 2rem;
}

.profile-image {
  position: relative;
  width: 200px;
  height: 200px;
  border-radius: 50%;
  border: 3px solid rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(5px);
  transition: all 0.5s ease;
}

.profile-glow {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 180px;
  height: 180px;
  transform: translate(-50%, -50%);
  border-radius: 50%;
  background: radial-gradient(circle at center, 
    var(--gradient-1) 0%, 
    transparent 70%);
  opacity: 0;
  transition: opacity 0.5s ease;
}

.profile-container:hover .profile-glow {
  opacity: 0.15;
}

.profile-container:hover .profile-image {
  transform: scale(1.05);
  border-color: var(--gradient-1);
}

.hero h1 {
  font-size: 4rem;
  font-weight: 700;
  margin: 1rem 0;
  background: linear-gradient(120deg, 
    var(--gradient-1), 
    var(--gradient-2), 
    var(--gradient-3));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradient 8s ease infinite;
  background-size: 200% auto;
}

.hero h2 {
  font-size: 1.5rem;
  color: var(--text-secondary);
  font-weight: 500;
  opacity: 0.9;
  margin-bottom: 2rem;
}

.social-links {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  margin-top: 2rem;
}

.social-links a {
  color: var(--text-secondary);
  text-decoration: none;
  padding: 0.5rem 1rem;
  border-radius: 6px;
  background: rgba(255, 255, 255, 0.05);
  transition: all 0.3s ease;
}

.social-links a:hover {
  color: var(--text-bright);
  background: rgba(255, 255, 255, 0.1);
  transform: translateY(-2px);
}

.expertise-areas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2rem;
  margin: 4rem auto;
  max-width: 1200px;
  padding: 0 2rem;
  perspective: 1000px;
}

.expertise-card {
  position: relative;
  padding: 2.5rem;
  border-radius: 16px;
  background: linear-gradient(145deg, 
    rgba(var(--card-bg-rgb), 0.9),
    rgba(var(--card-bg-rgb), 0.4));
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  overflow: hidden;
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
  transform-style: preserve-3d;
}

.card-glow {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 100%;
  background: linear-gradient(45deg, 
    var(--gradient-1), 
    var(--gradient-2), 
    var(--gradient-3));
  opacity: 0;
  transition: opacity 0.3s ease;
  filter: blur(20px);
  z-index: 0;
}

.expertise-card:hover {
  transform: translateY(-10px) rotateX(2deg);
  border-color: rgba(255, 255, 255, 0.2);
  box-shadow: 
    0 15px 35px rgba(0, 0, 0, 0.3),
    0 0 30px rgba(var(--gradient-1-rgb), 0.1);
}

.expertise-card:hover .card-glow {
  opacity: 0.1;
}

.icon {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
  position: relative;
  z-index: 1;
  filter: drop-shadow(0 0 10px rgba(var(--gradient-1-rgb), 0.3));
}

.expertise-card h3 {
  font-size: 1.8rem;
  font-weight: 700;
  margin-bottom: 1rem;
  background: linear-gradient(120deg, 
    var(--gradient-1), 
    var(--gradient-2));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  position: relative;
  z-index: 1;
}

.expertise-card p {
  color: var(--text-secondary);
  font-size: 1.1rem;
  line-height: 1.7;
  margin-bottom: 2rem;
  position: relative;
  z-index: 1;
}

.card-footer {
  position: relative;
  z-index: 1;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  padding-top: 1rem;
  margin-top: auto;
}

.learn-more {
  font-size: 0.9rem;
  color: var(--gradient-1);
  text-transform: uppercase;
  letter-spacing: 0.5px;
  font-weight: 500;
  transition: all 0.3s ease;
  cursor: pointer;
}

.learn-more:hover {
  color: var(--gradient-2);
  transform: translateX(5px);
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

@keyframes gradient {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
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
    padding: 0 1rem;
  }
}
</style>

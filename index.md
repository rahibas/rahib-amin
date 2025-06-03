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
  /* Updated Color System */
  --bg-deep: #0a0c10;
  --bg-surface: #161b22;
  --card-bg: #21262d;
  --accent-primary: #58a6ff;
  --accent-secondary: #bc8cff;
  --text-bright: #ffffff;
  --text-primary:rgb(218, 226, 233);
  --text-secondary:rgb(217, 222, 228);
  --border-color: #30363d;
  
  /* Unified Typography */
  --font-main: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
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
  text-align: center;
  padding: 4rem 2rem;
  background: var(--card-bg);
  color: var(--text-bright);
  border-radius: 12px;
  margin: 2rem auto;
  max-width: 1200px;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.3);
  border: 1px solid var(--border-color);
}

.hero h1 {
  font-family: var(--font-main);
  font-size: 3.5rem;
  font-weight: 600;
  margin: 1rem 0;
  color: var(--text-bright);
  letter-spacing: -0.03em;
  background: linear-gradient(120deg, var(--accent-primary), var(--accent-secondary));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 2px 10px rgba(88, 166, 255, 0.2);
}

.hero h2 {
  font-family: var(--font-main);
  font-size: 1.5rem;
  color: var(--text-primary);
  font-weight: 400;
  margin-top: 0.5rem;
}

.profile-image {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  border: 3px solid var(--accent-primary);
  margin-bottom: 2rem;
  box-shadow: 0 0 30px rgba(88, 166, 255, 0.2);
  transition: all 0.3s ease;
}

.profile-image:hover {
  transform: scale(1.03);
  border-color: var(--accent-secondary);
  box-shadow: 0 0 40px rgba(88, 166, 255, 0.3);
}

.expertise-areas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 3rem auto;
  max-width: 1200px;
  padding: 0 2rem;
}

.expertise-card {
  padding: 2rem;
  border-radius: 12px;
  background: var(--card-bg);
  color: var(--text-primary);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
  transition: all 0.3s ease;
  border: 1px solid var(--border-color);
  position: relative;
  overflow: hidden;
}

.expertise-card::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 3px;
  background: linear-gradient(90deg, var(--accent-primary), var(--accent-secondary));
  opacity: 0;
  transition: opacity 0.3s ease;
}

.expertise-card:hover {
  transform: translateY(-4px);
  border-color: var(--accent-primary);
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.3);
}

.expertise-card:hover::after {
  opacity: 1;
}

.expertise-card h3 {
  font-family: var(--font-main);
  font-size: 1.4rem;
  font-weight: 600;
  color: var(--accent-primary);
  margin-bottom: 1rem;
}

.expertise-card p {
  color: var(--text-secondary);
  font-size: 1.1rem;
  line-height: 1.6;
  margin: 0;
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

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
body {
  background-color: #121212;
  color: #e0e0e0;
}

.hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #1e1e1e 0%, #2c3e50 100%);
  color: #ffffff;
  border-radius: 8px;
  margin-bottom: 2rem;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
}

.profile-image {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  border: 4px solid #3498db;
  margin-bottom: 1rem;
  box-shadow: 0 0 20px rgba(52, 152, 219, 0.3);
}

.expertise-areas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.expertise-card {
  padding: 1.5rem;
  border-radius: 8px;
  background: #1e1e1e;
  color: #e0e0e0;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
  transition: transform 0.2s, box-shadow 0.2s;
  border: 1px solid #333;
}

.expertise-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(52, 152, 219, 0.2);
  border-color: #3498db;
}

.expertise-card h3 {
  color: #3498db;
  margin-bottom: 1rem;
}

@media (max-width: 768px) {
  .expertise-areas {
    grid-template-columns: 1fr;
  }
}
</style>

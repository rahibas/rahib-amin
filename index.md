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
.hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #1a1a1a 0%, #2c3e50 100%);
  color: white;
  border-radius: 8px;
  margin-bottom: 2rem;
}

.profile-image {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  border: 4px solid #3498db;
  margin-bottom: 1rem;
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
  background: #f8f9fa;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}

.expertise-card:hover {
  transform: translateY(-5px);
}

@media (max-width: 768px) {
  .expertise-areas {
    grid-template-columns: 1fr;
  }
}
</style>

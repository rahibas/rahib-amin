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
      <a href="https://github.com/rahibas" target="_blank">GitHub</a>
      <a href="https://www.linkedin.com/in/rahib-amin-2aa402149/" target="_blank">LinkedIn</a>
    </div>
  </div>
</div>

<div class="about-section">
  <div class="about-container">
    <h2 class="section-title">About Me</h2>
    <div class="about-content">
      <p class="about-intro">
        As a Lead Consultant at Thoughtworks America's EMPC Service Line, I bring over a decade of experience in large-scale distributed systems and technical product management.
      </p>
      <div class="about-details">
        <p>I position myself at the intersection of Product Management, Architecture, and Platform Strategy, specializing in:</p>
        <ul>
          <li>Translating complex technical visions into actionable product roadmaps</li>
          <li>Building scalable platform solutions within API and event-driven ecosystems</li>
          <li>Implementing AI-driven platform solutions</li>
          <li>Facilitating cross-functional collaboration using Design Thinking approaches</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="expertise-areas">
  <div class="expertise-card">
    <div class="card-glow"></div>
    <div class="icon">
      <img src="https://img.icons8.com/fluency/48/rocket.png" alt="Rocket Icon">
    </div>
    <h3>Enterprise Platform Modernization</h3>
    <p>Transforming technical visions into scalable platform architectures and actionable roadmaps. Specializing in "X as a Product" mindset and developer experience optimization.</p>
    <div class="card-footer">
      <a href="https://www.thoughtworks.com/en-us/what-we-do/enterprise-platform-modernization" target="_blank" class="learn-more">Explore Strategy →</a>
    </div>
  </div>
  
  <div class="expertise-card">
    <div class="card-glow"></div>
    <div class="icon">
      <img src="https://img.icons8.com/fluency/48/cloud.png" alt="Cloud Icon">
    </div>
    <h3>Architecture & Systems</h3>
    <p>Designing robust distributed systems with expertise in microservices, event-driven architecture, and polyglot persistence ecosystems.</p>
    <div class="card-footer">
      <a href="https://www.thoughtworks.com/en-us/insights/topic/architecture" target="_blank" class="learn-more">View Architectures →</a>
    </div>
  </div>
  
  <div class="expertise-card">
    <div class="card-glow"></div>
    <div class="icon">
      <img src="https://img.icons8.com/fluency/48/leadership.png" alt="Leadership Icon">
    </div>
    <h3>Technology Leadership</h3>
    <p>Driving DevSecOps practices, fostering cross-functional collaboration, and aligning technical initiatives with business objectives.</p>
    <div class="card-footer">
      <a href="https://www.thoughtworks.com/en-us/about-us/events/webinars/beyond-the-data--data-leadership-for-transformative-impact-in-20" target="_blank" class="learn-more">Learn About Leadership →</a>
    </div>
  </div>
</div>

<div class="blogs-section">
  <div class="blogs-container">
    <h2 class="section-title">My Blogs</h2>
    <ul class="blogs-list">
      <li>
        <a href="https://medium.com/@amin.rahib/finding-the-sweet-spot-why-strategic-balance-is-crucial-for-platform-roadmaps-d8043bb3ae6d" target="_blank">
          Finding the Sweet Spot: Why Strategic Balance is Crucial for Platform Roadmaps
        </a>
      </li>
      <li>
        <a href="https://www.thoughtworks.com/en-us/insights/blog/apis/design-thinking-apis" target="_blank">
          Design Thinking for APIs
        </a>
      </li>
      <li>
        <a href="https://www.youtube.com/watch?v=KvaufrhtTF4&list=PLDvibOTp3V8-ShFDF7KYepg0YVw2aQfeT&index=22" target="_blank">
          Video: Exploring Platform Strategies
        </a>
      </li>
    </ul>
  </div>
</div>

<div class="speaking-section">
  <div class="speaking-container">
    <h2 class="section-title">Upcoming Speaking Engagements</h2>
    <ul class="speaking-list">
      <li>
        <strong>Event Name:</strong> Example Conference<br>
        <strong>Date:</strong> January 15, 2024<br>
        <strong>Topic:</strong> The Future of Cloud Architectures
      </li>
      <li>
        <strong>Event Name:</strong> Tech Leadership Summit<br>
        <strong>Date:</strong> February 20, 2024<br>
        <strong>Topic:</strong> Driving Innovation with AI
      </li>
    </ul>
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

.about-section {
  margin: 4rem auto;
  max-width: 1200px;
  padding: 0 2rem;
}

.about-container {
  background: var(--card-bg);
  border-radius: 16px;
  padding: 3rem;
  border: 1px solid var(--border-color);
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.4);
  position: relative;
  overflow: hidden;
}

.section-title {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 2rem;
  background: linear-gradient(120deg, var(--gradient-1), var(--gradient-2));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  display: inline-block;
}

.about-content {
  position: relative;
  z-index: 1;
}

.about-intro {
  font-size: 1.2rem;
  color: var(--text-bright);
  margin-bottom: 2rem;
  line-height: 1.8;
}

.about-details {
  color: var(--text-secondary);
}

.about-details p {
  margin-bottom: 1rem;
}

.about-details ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: grid;
  gap: 1rem;
}

.about-details li {
  padding-left: 1.5rem;
  position: relative;
}

.about-details li::before {
  content: "→";
  position: absolute;
  left: 0;
  color: var(--gradient-1);
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

.blogs-section, .speaking-section {
  margin: 4rem auto;
  max-width: 1200px;
  padding: 0 2rem;
}

.blogs-container, .speaking-container {
  background: var(--card-bg);
  border-radius: 16px;
  padding: 3rem;
  border: 1px solid var(--border-color);
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.4);
}

.blogs-list, .speaking-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.blogs-list li, .speaking-list li {
  margin-bottom: 1.5rem;
}

.blogs-list a {
  color: var(--accent-primary);
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

.blogs-list a:hover {
  color: var(--accent-secondary);
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
  
  .about-container {
    padding: 2rem;
  }
  
  .section-title {
    font-size: 2rem;
  }
  
  .about-intro {
    font-size: 1.1rem;
  }
}
</style>

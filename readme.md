<div class="mtflash-readme">
  <div class="readme-container">
    
    <!-- Hero Section -->
    <div class="readme-hero">
      <div class="hero-icon">📁</div>
      <h1 class="hero-title">MTFLASH FIRMWARE</h1>
      <p class="hero-subtitle">No Ads • No Limits • Pure Speed</p>
      <div class="hero-badges">
        <span class="badge online">🟢 Online</span>
        <span class="badge performance">⚡ High Performance</span>
        <span class="badge secure">🔒 Secure</span>
      </div>
    </div>
    
    <!-- Features Section -->
    <div class="readme-features">
      <div class="feature-card">
        <div class="feature-icon">🚀</div>
        <h3 class="feature-title">Lightning Fast</h3>
        <p class="feature-desc">Optimized for maximum performance with zero latency</p>
      </div>
      
      <div class="feature-card">
        <div class="feature-icon">🛡️</div>
        <h3 class="feature-title">Enterprise Security</h3>
        <p class="feature-desc">Military-grade encryption and secure file management</p>
      </div>
      
      <div class="feature-card">
        <div class="feature-icon">🌐</div>
        <h3 class="feature-title">Global CDN</h3>
        <p class="feature-desc">Worldwide content delivery with 99.9% uptime guarantee</p>
      </div>
    </div>
    
    <!-- Stats Section -->
    <div class="readme-stats">
      <div class="stat-item">
        <div class="stat-number">99.9%</div>
        <div class="stat-label">Uptime</div>
      </div>
      <div class="stat-item">
        <div class="stat-number">1000+</div>
        <div class="stat-label">Active Users</div>
      </div>
      <div class="stat-item">
        <div class="stat-number">24/7</div>
        <div class="stat-label">Support</div>
      </div>
      <div class="stat-item">
        <div class="stat-number">5TB+</div>
        <div class="stat-label">Storage</div>
      </div>
    </div>
    
    <!-- Contact Section -->
    <div class="readme-contact">
      <h2 class="contact-title">Get Support</h2>
      <p class="contact-desc">Need help? Our team is here to assist you 24/7</p>
      <div class="contact-buttons">
        <a href="https://zalo.me/0975904043" target="_blank" rel="noopener" class="contact-btn zalo-btn">
          <span class="btn-icon">💬</span>
          <span class="btn-text">Zalo Support</span>
        </a>
        <a href="https://t.me/bunnyVN888" target="_blank" rel="noopener" class="contact-btn telegram-btn">
          <span class="btn-icon">🚀</span>
          <span class="btn-text">Telegram</span>
        </a>
        <a href="mailto:support@mtflash.com" class="contact-btn email-btn">
          <span class="btn-icon">💌</span>
          <span class="btn-text">Email Us</span>
        </a>
      </div>
    </div>
    
  </div>
  
  <!-- Background Elements -->
  <div class="readme-bg">
    <div class="bg-orb orb-1"></div>
    <div class="bg-orb orb-2"></div>
    <div class="bg-orb orb-3"></div>
  </div>
</div>

<style>
/* Professional README Styles - Matching Footer Theme */
.mtflash-readme {
  position: relative;
  background: 
    linear-gradient(135deg, 
      rgba(20, 20, 40, 0.95) 0%,
      rgba(30, 30, 60, 0.85) 25%,
      rgba(40, 20, 60, 0.95) 50%,
      rgba(60, 30, 80, 0.85) 75%,
      rgba(80, 40, 100, 0.95) 100%
    ),
    url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.03'%3E%3Ccircle cx='30' cy='30' r='1.5'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
  padding: 60px 20px;
  font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif;
  overflow: hidden;
  backdrop-filter: blur(25px);
  border-radius: 16px;
  margin: 20px 0;
  box-shadow: 
    0 8px 32px rgba(0, 0, 0, 0.3),
    inset 0 1px 0 rgba(255, 255, 255, 0.08);
  border: 1px solid rgba(255, 255, 255, 0.12);
}

/* Background Orbs */
.readme-bg {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  pointer-events: none;
}

.bg-orb {
  position: absolute;
  border-radius: 50%;
  filter: blur(80px);
  opacity: 0.1;
  animation: floatOrbs 30s linear infinite;
}

.orb-1 {
  width: 200px;
  height: 200px;
  background: #00d4ff;
  top: 10%;
  left: 10%;
  animation-delay: 0s;
}

.orb-2 {
  width: 150px;
  height: 150px;
  background: #b157ff;
  top: 60%;
  right: 20%;
  animation-delay: -10s;
}

.orb-3 {
  width: 180px;
  height: 180px;
  background: #ff6b9d;
  bottom: 20%;
  left: 60%;
  animation-delay: -20s;
}

@keyframes floatOrbs {
  0%, 100% { transform: translateY(0px) rotate(0deg); }
  50% { transform: translateY(-20px) rotate(180deg); }
}

/* Container */
.readme-container {
  position: relative;
  z-index: 10;
  max-width: 1000px;
  margin: 0 auto;
}

/* Hero Section */
.readme-hero {
  text-align: center;
  margin-bottom: 60px;
}

.hero-icon {
  font-size: 64px;
  margin-bottom: 20px;
  filter: drop-shadow(0 0 20px rgba(255, 255, 255, 0.3));
  animation: iconFloat 3s ease-in-out infinite;
}

@keyframes iconFloat {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
}

.hero-title {
  font-size: clamp(32px, 6vw, 48px);
  font-weight: 800;
  color: rgba(255, 255, 255, 0.95);
  margin: 0 0 16px 0;
  letter-spacing: -0.025em;
  text-shadow: 
    0 0 30px rgba(255, 255, 255, 0.2),
    0 2px 4px rgba(0, 0, 0, 0.3);
  position: relative;
}

.hero-title::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(45deg, #00d4ff, #b157ff, #ff6b9d);
  background-size: 200% 200%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  opacity: 0;
  animation: heroGlow 4s ease-in-out infinite;
}

@keyframes heroGlow {
  0%, 100% { opacity: 0; background-position: 0% 50%; }
  50% { opacity: 0.7; background-position: 100% 50%; }
}

.hero-subtitle {
  font-size: 20px;
  color: rgba(255, 255, 255, 0.7);
  margin: 0 0 24px 0;
  font-weight: 400;
  letter-spacing: 0.5px;
}

.hero-badges {
  display: flex;
  gap: 12px;
  justify-content: center;
  flex-wrap: wrap;
}

.badge {
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 14px;
  font-weight: 500;
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid rgba(255, 255, 255, 0.2);
  color: rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(10px);
  transition: all 0.3s ease;
}

.badge:hover {
  background: rgba(255, 255, 255, 0.15);
  transform: translateY(-2px);
}

.badge.online {
  background: linear-gradient(135deg, rgba(34, 197, 94, 0.2), rgba(34, 197, 94, 0.1));
  box-shadow: 0 4px 15px rgba(34, 197, 94, 0.2);
}

.badge.performance {
  background: linear-gradient(135deg, rgba(251, 191, 36, 0.2), rgba(251, 191, 36, 0.1));
  box-shadow: 0 4px 15px rgba(251, 191, 36, 0.2);
}

.badge.secure {
  background: linear-gradient(135deg, rgba(139, 92, 246, 0.2), rgba(139, 92, 246, 0.1));
  box-shadow: 0 4px 15px rgba(139, 92, 246, 0.2);
}

/* Features Section */
.readme-features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 24px;
  margin-bottom: 60px;
}

.feature-card {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 16px;
  padding: 32px 24px;
  backdrop-filter: blur(20px);
  transition: all 0.3s ease;
  text-align: center;
}

.feature-card:hover {
  background: rgba(255, 255, 255, 0.08);
  transform: translateY(-4px);
  box-shadow: 0 12px 32px rgba(0, 0, 0, 0.3);
}

.feature-icon {
  font-size: 48px;
  margin-bottom: 16px;
  filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.2));
}

.feature-title {
  font-size: 20px;
  font-weight: 600;
  color: rgba(255, 255, 255, 0.9);
  margin: 0 0 12px 0;
  letter-spacing: -0.01em;
}

.feature-desc {
  font-size: 15px;
  color: rgba(255, 255, 255, 0.7);
  line-height: 1.6;
  margin: 0;
}

/* Stats Section */
.readme-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 24px;
  margin-bottom: 60px;
  padding: 32px 24px;
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 16px;
  backdrop-filter: blur(20px);
}

.stat-item {
  text-align: center;
}

.stat-number {
  font-size: 28px;
  font-weight: 700;
  color: rgba(255, 255, 255, 0.95);
  display: block;
  margin-bottom: 8px;
  background: linear-gradient(45deg, #00d4ff, #b157ff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.stat-label {
  font-size: 14px;
  color: rgba(255, 255, 255, 0.7);
  font-weight: 400;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

/* Contact Section */
.readme-contact {
  text-align: center;
}

.contact-title {
  font-size: 28px;
  font-weight: 700;
  color: rgba(255, 255, 255, 0.95);
  margin: 0 0 12px 0;
  letter-spacing: -0.02em;
}

.contact-desc {
  font-size: 17px;
  color: rgba(255, 255, 255, 0.7);
  margin: 0 0 32px 0;
  line-height: 1.6;
}

.contact-buttons {
  display: flex;
  gap: 16px;
  justify-content: center;
  flex-wrap: wrap;
}

.contact-btn {
  position: relative;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 14px 24px;
  border-radius: 12px;
  text-decoration: none;
  font-size: 14px;
  font-weight: 600;
  color: rgba(255, 255, 255, 0.9);
  transition: all 0.3s ease;
  overflow: hidden;
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  background: rgba(255, 255, 255, 0.1);
  min-width: 140px;
  justify-content: center;
}

.contact-btn::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.1), transparent);
  transition: all 0.4s ease;
}

.contact-btn:hover::before {
  left: 100%;
}

.contact-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
}

.zalo-btn {
  background: linear-gradient(135deg, rgba(0, 212, 255, 0.2), rgba(0, 150, 255, 0.1));
  box-shadow: 0 4px 15px rgba(0, 212, 255, 0.2);
}

.telegram-btn {
  background: linear-gradient(135deg, rgba(177, 87, 255, 0.2), rgba(150, 50, 255, 0.1));
  box-shadow: 0 4px 15px rgba(177, 87, 255, 0.2);
}

.email-btn {
  background: linear-gradient(135deg, rgba(255, 107, 157, 0.2), rgba(255, 80, 120, 0.1));
  box-shadow: 0 4px 15px rgba(255, 107, 157, 0.2);
}

.btn-icon {
  font-size: 16px;
  transition: all 0.3s ease;
}

.contact-btn:hover .btn-icon {
  transform: scale(1.1);
}

/* Responsive Design */
@media (max-width: 768px) {
  .mtflash-readme {
    padding: 40px 16px;
    margin: 10px 0;
  }
  
  .hero-icon {
    font-size: 48px;
  }
  
  .readme-features {
    grid-template-columns: 1fr;
  }
  
  .readme-stats {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .contact-buttons {
    flex-direction: column;
    max-width: 300px;
    margin: 0 auto;
  }
  
  .contact-btn {
    width: 100%;
  }
}

@media (max-width: 480px) {
  .hero-badges {
    flex-direction: column;
    align-items: center;
  }
  
  .readme-stats {
    grid-template-columns: 1fr;
  }
}

/* Accessibility */
.contact-btn:focus {
  outline: none;
  box-shadow: 
    0 0 0 3px rgba(255, 255, 255, 0.3),
    0 8px 25px rgba(0, 0, 0, 0.2);
}

/* Reduced Motion */
@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
  }
}
</style>
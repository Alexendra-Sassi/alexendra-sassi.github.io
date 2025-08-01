---
layout: about
icon: fas fa-info-circle
order: 5
---

<section class="alexandra-sassi-container">

  <!-- Header -->
  <header class="as-header">
    <div class="as-profile-img">👩‍🎓</div>
    <h1 class="as-title">Alexendra Sassi</h1>
    <p class="as-subtitle">Étudiante en Nutrition • Passionnée par la santé et le bien-être</p>
    <span class="as-badge">🎓 En formation continue</span>
  </header>

  <!-- À propos -->
  <section class="as-section">
    <h2 class="as-section-title">Qui suis-je ?</h2>
    <p class="as-intro-text">
      Bonjour ! Je suis Alexendra Sassi, étudiante passionnée en nutrition basée à Bobo-Dioulasso, Burkina Faso. Ma mission est d'accompagner chaque personne vers une meilleure santé grâce à une alimentation équilibrée.
    </p>
  </section>

  <!-- Services -->
  <section class="as-section">
    <h2 class="as-section-title">Mes Services</h2>
    <div class="as-services-grid">

<article class="as-service-card as-blue-card">
        <div class="as-service-icon">🥗</div>
        <h3>Conseils Nutritionnels</h3>
        <p>Accompagnement nutritionnel pour vous aider à adopter de meilleures habitudes alimentaires.</p>
        <ul class="as-feature-list">
          <li>Analyse de vos habitudes alimentaires</li>
          <li>Conseils personnalisés</li>
          <li>Suivi et motivation</li>
        </ul>
      </article>

  <article class="as-service-card as-green-card">
        <div class="as-service-icon">📋</div>
        <h3>Suggestions de Menus</h3>
        <p>Création de suggestions de menus équilibrés et variés adaptés à vos besoins.</p>
        <ul class="as-feature-list">
          <li>Menus équilibrés</li>
          <li>Listes de courses</li>
          <li>Recettes simples et saines</li>
        </ul>
      </article>

  <article class="as-service-card as-purple-card">
        <div class="as-service-icon">👶</div>
        <h3>Conseils Nutrition Familiale</h3>
        <p>Conseils nutritionnels de base pour la famille.</p>
        <ul class="as-feature-list">
          <li>Nutrition pédiatrique</li>
          <li>Grossesse et allaitement</li>
          <li>Nutrition des seniors</li>
        </ul>
      </article>

  </div>
  </section>

  <!-- Newsletter -->
  <section class="as-newsletter">
    <h3 class="as-newsletter-title">Conseils exclusifs par email</h3>
    <p class="as-newsletter-text">Recevez chaque mois des menus équilibrés et des astuces nutritionnelles.</p>
    <form class="as-newsletter-form">
      <label for="newsletter-email" class="sr-only">Votre email</label>
      <input id="newsletter-email" name="email" type="email" placeholder="Votre email" required class="as-newsletter-input">
      <button type="submit" class="as-newsletter-button">📩 S'inscrire</button>
    </form>
  </section>

  <!-- Contact -->
  <section class="as-contact-section">
    <div class="as-contact-grid">
<div class="as-contact-info">
        <h3 class="as-contact-title">Informations de Contact</h3>

  <div class="as-contact-item">
          <div class="as-contact-icon">📧</div>
          <div class="as-contact-content">
            <strong>Email</strong><br>
            <a href="mailto:exemple@exemple.com" class="as-contact-link">exemple@exemple.com</a>
          </div>
        </div>

  <div class="as-contact-item">
          <div class="as-contact-icon">📱</div>
          <div class="as-contact-content">
            <strong>Téléphone</strong><br>
            <a href="tel:+22604454323" class="as-contact-link">+226 04 45 43 23</a>
          </div>
        </div>

<div class="as-contact-item">
          <div class="as-contact-icon">📍</div>
          <div class="as-contact-content">
            <strong>Localisation</strong><br>
            Bobo-Dioulasso, Burkina Faso
          </div>
        </div>

  <div class="as-contact-item">
          <div class="as-contact-icon">🕒</div>
          <div class="as-contact-content">
            <strong>Disponibilité</strong><br>
            Lun - Ven : 9H - 17H<br>
            Sam : 9H - 12H
          </div>
        </div>
      </div>

<div class="as-contact-form">
  <h3 class="as-form-title">Envoyez-moi un message</h3>
  <form class="as-form" id="contact-form">
    <div class="as-form-row">
      <div class="as-form-group">
        <label for="prenom" class="sr-only">Prénom</label>
        <input type="text" id="prenom" name="Prénom" placeholder="Prénom *" required class="as-form-input">
      </div>
      <div class="as-form-group">
        <label for="nom" class="sr-only">Nom</label>
        <input type="text" id="nom" name="Nom" placeholder="Nom *" required class="as-form-input">
      </div>
    </div>
    <div class="as-form-group">
      <label for="email" class="sr-only">Email</label>
      <input type="email" id="email" name="Email" placeholder="Votre email *" required class="as-form-input">
    </div>
    <div class="as-form-group">
      <label for="service" class="sr-only">Service</label>
      <select id="service" name="Service" class="as-form-select" required>
        <option disabled selected>Sélectionnez un service</option>
        <option>Conseils Nutritionnels</option>
        <option>Suggestions de Menus</option>
        <option>Conseils Nutrition Familiale</option>
        <option>Autre demande</option>
      </select>
    </div>
    <div class="as-form-group">
      <label for="message" class="sr-only">Message</label>
      <textarea id="message" name="Message" placeholder="Décrivez votre demande..." class="as-form-textarea"></textarea>
    </div>
    <button type="submit" class="as-submit-button">📨 Envoyer le message</button>
  </form>

  <!-- Message de confirmation -->
  <div id="success-message" style="display: none; margin-top: 10px; color: green;">✅ Message envoyé avec succès !</div>
</div>
 
<style>
:root {
  --primary: #3b82f6;
  --primary-dark: #2563eb;
  --green: #10b981;
  --purple: #8b5cf6;
  --text-dark: #0f172a;
  --text-muted: #64748b;
  --bg-light: #f8fafc;
  --border: #e2e8f0;
  --font: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

/* Reset */
.alexandra-sassi-container * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: var(--font);
}

.alexandra-sassi-container {
  max-width: 1200px;
  margin: 20px auto;
  padding: 40px;
  background: linear-gradient(135deg, #ffffff 0%, #f8fafc 100%);
  border-radius: 20px;
  box-shadow: 0 20px 60px rgba(0,0,0,0.1), 0 8px 25px rgba(0,0,0,0.08);
  color: var(--text-dark);
  line-height: 1.7;
  position: relative;
  overflow: hidden;
}

.alexandra-sassi-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--primary), var(--green), var(--purple));
  animation: gradientShift 6s ease-in-out infinite;
}

@keyframes gradientShift {
  0%, 100% { background: linear-gradient(90deg, var(--primary), var(--green), var(--purple)); }
  33% { background: linear-gradient(90deg, var(--green), var(--purple), var(--primary)); }
  66% { background: linear-gradient(90deg, var(--purple), var(--primary), var(--green)); }
}

/* Header */
.as-header {
  text-align: center;
  margin-bottom: 30px;
  animation: fadeInUp 0.8s ease-out;
}
.as-profile-img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--primary) 0%, var(--purple) 100%);
  margin: 0 auto 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2.5rem;
  color: white;
  position: relative;
  animation: pulse 2s infinite;
  box-shadow: 0 8px 25px rgba(59, 130, 246, 0.3);
}

.as-profile-img::after {
  display: none;
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.05); }
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}

.as-title {
  font-size: 2.5rem;
  font-weight: 700;
  background: linear-gradient(135deg, var(--primary), var(--purple));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: fadeInUp 0.8s ease-out 0.2s backwards;
}
.as-subtitle {
  font-size: 1.1rem;
  color: var(--text-muted);
  margin-bottom: 16px;
  animation: fadeInUp 0.8s ease-out 0.4s backwards;
}
.as-badge {
  padding: 8px 20px;
  background: linear-gradient(135deg, #dbeafe, #e0e7ff);
  color: var(--primary);
  border-radius: 25px;
  font-size: 0.9rem;
  font-weight: 500;
  display: inline-block;
  border: 1px solid rgba(59, 130, 246, 0.2);
  animation: fadeInUp 0.8s ease-out 0.6s backwards;
  position: relative;
  overflow: hidden;
}

.as-badge::before {
  content: '';
  position: absolute;
  top: 0; left: -100%;
  width: 100%; height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.4), transparent);
  animation: shimmer 3s infinite;
}

@keyframes shimmer {
  to { left: 100%; }
}

/* Sections */
.as-section {
  margin-bottom: 40px;
  animation: fadeInUp 0.8s ease-out;
}
.as-section-title {
  font-size: 1.8rem;
  font-weight: 700;
  margin-bottom: 20px;
  position: relative;
  padding-left: 15px;
}

.as-section-title::before {
  content: '';
  position: absolute;
  left: 0; top: 50%;
  width: 4px; height: 20px;
  background: linear-gradient(135deg, var(--primary), var(--green));
  border-radius: 2px;
  transform: translateY(-50%);
}

.as-intro-text {
  font-size: 1.1rem;
  color: #475569;
  padding: 20px;
  background: linear-gradient(135deg, #f8fafc, #f1f5f9);
  border-radius: 12px;
  border-left: 4px solid var(--primary);
  position: relative;
}

/* Services */
.as-services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
}
.as-service-card {
  background: white;
  border: 1px solid var(--border);
  border-radius: 16px;
  padding: 24px;
  position: relative;
  transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
  overflow: hidden;
}

.as-service-card::after {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background: linear-gradient(135deg, transparent, rgba(255,255,255,0.1));
  opacity: 0;
  transition: opacity 0.3s;
}

.as-service-card:hover {
  border-color: transparent;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1), 0 10px 20px rgba(0, 0, 0, 0.05);
  transform: translateY(-8px) scale(1.02);
}

.as-service-card:hover::after {
  opacity: 1;
}

.as-service-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 4px;
  border-radius: 16px 16px 0 0;
  animation: pulse-border 2s infinite;
}
.as-blue-card::before { background: linear-gradient(90deg, var(--primary), #60a5fa); }
.as-green-card::before { background: linear-gradient(90deg, var(--green), #34d399); }
.as-purple-card::before { background: linear-gradient(90deg, var(--purple), #a78bfa); }

@keyframes pulse-border {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.7; }
}

.as-service-icon {
  width: 56px;
  height: 56px;
  border-radius: 16px;
  font-size: 24px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 16px;
  position: relative;
  transition: transform 0.3s;
}

.as-service-card:hover .as-service-icon {
  transform: scale(1.1) rotate(5deg);
}

.as-blue-card .as-service-icon { 
  background: linear-gradient(135deg, var(--primary), #60a5fa);
  box-shadow: 0 8px 20px rgba(59, 130, 246, 0.3);
}
.as-green-card .as-service-icon { 
  background: linear-gradient(135deg, var(--green), #34d399);
  box-shadow: 0 8px 20px rgba(16, 185, 129, 0.3);
}
.as-purple-card .as-service-icon { 
  background: linear-gradient(135deg, var(--purple), #a78bfa);
  box-shadow: 0 8px 20px rgba(139, 92, 246, 0.3);
}

.as-feature-list {
  list-style: none;
}
.as-feature-list li {
  display: flex;
  align-items: center;
  color: #475569;
  font-size: 0.9rem;
  margin-bottom: 8px;
  opacity: 0;
  animation: slideInLeft 0.6s ease-out forwards;
}

.as-feature-list li:nth-child(1) { animation-delay: 0.1s; }
.as-feature-list li:nth-child(2) { animation-delay: 0.2s; }
.as-feature-list li:nth-child(3) { animation-delay: 0.3s; }

@keyframes slideInLeft {
  from { opacity: 0; transform: translateX(-20px); }
  to { opacity: 1; transform: translateX(0); }
}

.as-feature-list li::before {
  content: '✓';
  color: var(--green);
  font-weight: 600;
  margin-right: 8px;
  background: rgba(16, 185, 129, 0.1);
  width: 20px; height: 20px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 12px;
}

/* Newsletter */
.as-newsletter {
  background: linear-gradient(135deg, var(--bg-light), #e0e7ff);
  border: 1px solid rgba(59, 130, 246, 0.2);
  border-radius: 16px;
  padding: 30px;
  text-align: center;
  margin-bottom: 30px;
  position: relative;
  overflow: hidden;
}

.as-newsletter::before {
  content: '';
  position: absolute;
  top: -50%; left: -50%;
  width: 200%; height: 200%;
  background: conic-gradient(transparent, rgba(59, 130, 246, 0.05), transparent);
  animation: rotate 10s linear infinite;
}

.as-newsletter > * {
  position: relative;
  z-index: 1;
}

.as-newsletter-title {
  font-size: 1.5rem;
  margin-bottom: 15px;
  background: linear-gradient(135deg, var(--primary), var(--purple));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.as-newsletter-text {
  color: var(--text-muted);
  margin-bottom: 20px;
}
.as-newsletter-form {
  display: flex;
  max-width: 500px;
  margin: 0 auto;
  gap: 8px;
}
.as-newsletter-input {
  flex: 1;
  padding: 12px 16px;
  border: 2px solid transparent;
  border-radius: 10px;
  font-family: inherit;
  background: white;
  transition: all 0.3s;
}

.as-newsletter-input:focus {
  outline: none;
  border-color: var(--primary);
  box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.1);
}

.as-newsletter-button {
  padding: 12px 24px;
  background: linear-gradient(135deg, var(--primary), var(--primary-dark));
  color: white;
  border: none;
  border-radius: 10px;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s;
  position: relative;
  overflow: hidden;
}

.as-newsletter-button::before {
  content: '';
  position: absolute;
  top: 0; left: -100%;
  width: 100%; height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
  transition: left 0.5s;
}

.as-newsletter-button:hover::before {
  left: 100%;
}

.as-newsletter-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(59, 130, 246, 0.3);
}

/* Contact */
.as-contact-section {
  background: linear-gradient(135deg, var(--bg-light), #f1f5f9);
  border-radius: 20px;
  padding: 30px;
  position: relative;
}
.as-contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
}
.as-contact-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 16px;
  padding: 16px;
  background: white;
  border-radius: 12px;
  border: 1px solid var(--border);
  transition: all 0.3s;
  position: relative;
  overflow: hidden;
}

.as-contact-item::before {
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 4px; height: 100%;
  background: linear-gradient(135deg, var(--primary), var(--green));
  transform: scaleY(0);
  transition: transform 0.3s;
}

.as-contact-item:hover::before {
  transform: scaleY(1);
}

.as-contact-item:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
}

.as-contact-icon {
  margin-right: 12px;
  font-size: 20px;
  color: var(--primary);
  background: rgba(59, 130, 246, 0.1);
  width: 40px; height: 40px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}
.as-contact-content strong {
  color: var(--text-dark);
}

/* Formulaires */
.as-form-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}
.as-form-group {
  margin-bottom: 16px;
}
.as-form-input, .as-form-select, .as-form-textarea {
  width: 100%;
  padding: 12px 16px;
  border: 2px solid #e2e8f0;
  border-radius: 10px;
  font-family: inherit;
  transition: all 0.3s;
  background: white;
}

.as-form-input:focus, .as-form-select:focus, .as-form-textarea:focus {
  outline: none;
  border-color: var(--primary);
  box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.1);
  transform: translateY(-1px);
}

.as-form-textarea {
  height: 100px;
  resize: vertical;
}
.as-submit-button {
  width: 100%;
  padding: 14px;
  background: linear-gradient(135deg, var(--primary), var(--primary-dark));
  color: white;
  border: none;
  border-radius: 10px;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s;
  position: relative;
  overflow: hidden;
  font-size: 1rem;
}

.as-submit-button::before {
  content: '';
  position: absolute;
  top: 0; left: -100%;
  width: 100%; height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
  transition: left 0.5s;
}

.as-submit-button:hover::before {
  left: 100%;
}

.as-submit-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 25px rgba(59, 130, 246, 0.3);
}

/* Responsive */
@media (max-width: 768px) {
  .alexandra-sassi-container {
    padding: 20px;
    margin: 10px;
  }
  .as-contact-grid,
  .as-form-row,
  .as-services-grid,
  .as-newsletter-form {
    grid-template-columns: 1fr;
    flex-direction: column;
  }
  .as-newsletter-input,
  .as-newsletter-button {
    width: 100%;
  }
  .as-title {
    font-size: 2rem;
  }
}

/* Visually hidden (for labels) */
.sr-only {
  position: absolute;
  left: -9999px;
  top: auto;
  width: 1px;
  height: 1px;
  overflow: hidden;
}

</style>

<script>
  const form = document.getElementById('contact-form');
const successMessage = document.getElementById('success-message');

form.addEventListener('submit', async function (e) {
  e.preventDefault();
  
  try {
    const formData = new FormData(form);
    const response = await fetch("https://formsubmit.co/ajax/katchao878@gmail.com", {
      method: "POST",
      headers: { 
        'Content-Type': 'application/json',
        'Accept': 'application/json'
      },
      body: JSON.stringify(Object.fromEntries(formData))
    });
    
    if (response.ok) {
      successMessage.style.display = 'block';
      form.reset();
      setTimeout(() => {
        successMessage.style.display = 'none';
      }, 2500);
    } else {
      alert("❌ Une erreur s'est produite. Code: " + response.status);
    }
  } catch (error) {
    alert("❌ Erreur réseau : " + error.message);
    console.error(error);
  }
});
</script>
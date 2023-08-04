<template>
  <div id="app">
    <div class="container">
      <div class="title-container">
        <h1 class="title">Construisez votre offre</h1>
        <p class="subtitle">Une tarification simple et clair où vous ne payez que ce dont vous avez besoin 😎</p>
      </div>

      <section class="step">
        <span class="step-number">
          1
        </span>
        <div class="step-content">
          <h2 class="step-title">
            Choisissez les réseaux que vous souhaitez connecter
          </h2>

          <div class="step-card-container">
            <button class="step-card selected">
              <i class="ri-facebook-fill"></i> Facebook <span>Pages</span>
            </button>
            <button class="step-card selected">
              <i class="ri-facebook-fill"></i> Facebook <span>Groupes</span>
            </button>
            <button class="step-card selected">
              <i class="ri-twitter-fill"></i> Twitter
            </button>
            <button class="step-card selected">
              <i class="ri-telegram-fill"></i> Telegram
            </button>
            <button class="step-card selected">
              <i class="ri-linkedin-fill"></i> LinkedIn
            </button>
            <button class="step-card">
              <i class="ri-instagram-fill"></i> Instagram <span>Post</span>
            </button>
            <button class="step-card">
              <i class="ri-instagram-fill"></i> Instagram <span>Stories</span>
            </button>
            <button class="step-card">
              <i class="ri-pinterest-fill"></i> Pinterest
            </button>
            <button class="step-card">
              <i class="ri-youtube-fill"></i> Youtube
            </button>
            <button class="step-card">
              <i class="ri-google-fill"></i> Google My Business
            </button>
          </div>
        </div>
      </section>

      <section class="step">
        <span class="step-number">
          2
        </span>
        <div class="step-content">
          <h2 class="step-title">
            Configurez vos sources
          </h2>

          <div class="step-size-row">
            <div class="step-size-group">
              <span class="step-size-label">
                Nombre de RS
              </span>
              <div class="step-size-input-container">
                <button class="step-size-input-button">
                  -
                </button>
                <div class="step-size-input-data">
                  <span class="step-size-input-value" contenteditable="true">
                    1
                  </span>
                  <span class="step-size-input-unit">
                    RS
                  </span>
                </div>
                <button class="step-size-input-button">
                  +
                </button>
              </div>
            </div>

            <div class="step-size-group">
              <span class="step-size-label">
                Nombre de flux RSS/XML
              </span>
              <div class="step-size-input-container">
                <button class="step-size-input-button">
                  -
                </button>
                <div class="step-size-input-data">
                  <span class="step-size-input-value" contenteditable="true">
                    1
                  </span>
                  <span class="step-size-input-unit">
                    flux
                  </span>
                </div>
                <button class="step-size-input-button">
                  +
                </button>
              </div>
            </div>
          </div>
        </div>
      </section>
      
      <section class="step">
        <span class="step-number">
          3
        </span>
        <div class="step-content">
          <h2 class="step-title">
            Définissez vos propres limites
          </h2>

          <div class="step-size-row">
            <div class="step-size-group">
              <span class="step-size-label">
                Fréquence de mise à jour des flux
              </span>
              <div class="step-size-input-container">
                <button class="step-size-input-button">
                  -
                </button>
                <div class="step-size-input-data">
                  <span class="step-size-input-value" contenteditable="true">
                    5
                  </span>
                  <span class="step-size-input-unit">
                    min
                  </span>
                </div>
                <button class="step-size-input-button">
                  +
                </button>
              </div>
            </div>

            <div class="step-size-group">
              <span class="step-size-label">
                Limitation des posts
              </span>
              <div class="step-size-input-container">
                <button class="step-size-input-button">
                  -
                </button>
                <div class="step-size-input-data">
                  <span class="step-size-input-value" contenteditable="true">
                    3
                  </span>
                  <span class="step-size-input-unit">
                    par jour
                  </span>
                </div>
                <button class="step-size-input-button">
                  +
                </button>
              </div>
            </div>
          </div>

          <div class="step-size-row">
            <div class="step-size-group">
              <span class="step-size-label">
                Nombre d'utilisateurs
              </span>
              <div class="step-size-input-container">
                <button class="step-size-input-button">
                  -
                </button>
                <div class="step-size-input-data">
                  <span class="step-size-input-value" contenteditable="true">
                    1
                  </span>
                  <span class="step-size-input-unit">
                    pers.
                  </span>
                </div>
                <button class="step-size-input-button">
                  +
                </button>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="step">
        <span class="step-number">
          4
        </span>
        <div class="step-content">
          <h2 class="step-title">
            En bonus...
          </h2>

          <ul class="step-features">
            <li><i class="ri-check-fill"></i> Connections aux réseaux sociaux Facebook Pages, Facebook Groupes, Twitter, Telegram et LinkedIn offerts</li>
            <li><i class="ri-check-fill"></i> Mentions et hashtags automatiques</li>
            <li><i class="ri-check-fill"></i> Posts automatiques</li>
            <li><i class="ri-check-fill"></i> Blacklist de mots</li>
          </ul>
        </div>
      </section>

      <section class="step">
        <span class="step-number">
          5
        </span>
        <div class="step-content">
          <h2 class="step-title">
            Estimation du coût
          </h2>

          <div class="step-summary-row">
            <table class="step-summary">
              <thead>
                <tr>
                  <th class="step-summary-label">
                    <i class="ri-calculator-fill"></i> Estimation du coût
                  </th>
                  <th class="step-summary-value">
                    <select>
                      <option value="monthly">Mensuel</option>
                      <option value="yearly">Annuel</option>
                    </select>
                  </th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="step-summary-value">
                    <div class="step-summary-value-container">
                      <span class="step-summary-value-data">
                      Nombre de RS
                      </span>
                      <span class="step-summary-value-unit">
                        1 RS
                      </span>
                    </div>
                  </td>
                  <td class="step-summary-value">
                    0.00€
                  </td>
                </tr>
              </tbody>
            </table>
          </div>

          <button class="step-summary-button">
            Sauvegarder et payer
          </button>
        </div>
      </section>
    </div>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
  @import url("https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css");
  @import url("~/assets/css/reset.css");
  @import url("~/assets/css/main.css");
</style>
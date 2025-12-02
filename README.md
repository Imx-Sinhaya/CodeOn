This site can’t be reached
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Hosting — Game Hosting, VPS & Dedicated Servers</title>
  <meta name="description" content="Premium game hosting, VPS & dedicated servers. High-performance, DDoS protection, and 24/7 support." />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="assets/css/styles.css" />
</head>
<body>
  <!-- Top notice (optional) -->
  <div class="topbar">
    <div class="container">
      <span class="topbar-text">Limited-time promo: 50% off first month on Game Hosting</span>
      <a href="#pricing" class="topbar-link">View deals</a>
    </div>
  </div>

  <!-- Header -->
  <header class="site-header">
    <div class="container header-inner">
      <a href="#" class="brand" aria-label="Home">
        <img src="assets/img/logo.svg" alt="Your Hosting" class="brand-logo" />
        <span class="brand-name">Your Hosting</span>
      </a>

      <nav class="nav">
        <button class="nav-toggle" aria-label="Toggle menu">
          <span class="bar"></span><span class="bar"></span><span class="bar"></span>
        </button>
        <ul class="nav-list" role="menu">
          <li role="none"><a role="menuitem" href="#games">Games</a></li>
          <li role="none"><a role="menuitem" href="#vps">VPS</a></li>
          <li role="none"><a role="menuitem" href="#v2ray">V2Ray</a></li>
          <li role="none"><a role="menuitem" href="#web">Web Hosting</a></li>
          <li role="none"><a role="menuitem" href="#features">Features</a></li>
          <li role="none"><a role="menuitem" href="#status" class="status-pill"><span class="status-dot"></span><span class="status-text">Status</span></a></li>
          <li role="none"><a role="menuitem" href="#client" class="btn btn-outline">Client Space</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero" id="home">
    <div class="container hero-inner">
      <div class="hero-copy">
        <h1>High-performance game hosting that just works</h1>
        <p class="sub">Instant setup, low latency worldwide, and 24/7 support. Launch your Minecraft, Rust, ARK, and more in minutes.</p>
        <div class="hero-actions">
          <a href="#pricing" class="btn btn-primary">Get started</a>
          <a href="#features" class="btn btn-ghost">Explore features</a>
        </div>
        <ul class="hero-bullets">
          <li><strong>Instant deploy:</strong> Spin up servers in under 60 seconds</li>
          <li><strong>Protection:</strong> Enterprise-grade DDoS mitigation</li>
          <li><strong>Uptime:</strong> 99.9% SLA with proactive monitoring</li>
          <li><strong>Support:</strong> Real humans, 24/7</li>
        </ul>
      </div>
      <div class="hero-visual">
        <div class="panel-preview" aria-hidden="true">
          <div class="panel-header">
            <div class="dot red"></div>
            <div class="dot yellow"></div>
            <div class="dot green"></div>
            <span>Control Panel</span>
          </div>
          <div class="panel-body">
            <div class="stat">
              <span class="label">CPU</span>
              <div class="bar"><span style="width: 28%;"></span></div>
            </div>
            <div class="stat">
              <span class="label">RAM</span>
              <div class="bar"><span style="width: 63%;"></span></div>
            </div>
            <div class="stat">
              <span class="label">Network</span>
              <div class="bar"><span style="width: 47%;"></span></div>
            </div>
            <div class="tags">
              <span class="tag">1-click Mods</span>
              <span class="tag">Backups</span>
              <span class="tag">Analytics</span>
              <span class="tag">SSH</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Category cards -->
  <section class="categories" id="games">
    <div class="container">
      <h2>Choose your platform</h2>
      <p class="sub">Game Hosting, VPS, Dedicated Servers, and Managed Web Hosting.</p>
      <div class="card-grid">
        <article class="card">
          <div class="card-top">
            <h3>Game Hosting</h3>
            <p>Optimized CPUs, mod managers, instant setup for top titles.</p>
          </div>
          <ul class="ticklist">
            <li>Global locations</li>
            <li>DDoS protection</li>
            <li>1-click mods & plugins</li>
          </ul>
          <a class="btn btn-primary" href="#pricing">View plans</a>
        </article>

        <article class="card" id="cloud">
          <div class="card-top">
            <h3>Cloud VPS</h3>
            <p>Scalable virtual machines with root access and snapshots.</p>
          </div>
          <ul class="ticklist">
            <li>Flexible resources</li>
            <li>NVMe storage</li>
            <li>Snapshots & backups</li>
          </ul>
          <a class="btn btn-primary" href="#pricing">View plans</a>
        </article>

        <article class="card" id="dedicated">
          <div class="card-top">
            <h3>Dedicated</h3>
            <p>Bare-metal power, custom configs, priority support.</p>
          </div>
          <ul class="ticklist">
            <li>Latest-gen CPUs</li>
            <li>Custom network</li>
            <li>24/7 monitoring</li>
          </ul>
          <a class="btn btn-primary" href="#pricing">View plans</a>
        </article>

        <article class="card" id="web">
          <div class="card-top">
            <h3>Web Hosting</h3>
            <p>Managed sites with SSL, mail, databases, and staging.</p>
          </div>
          <ul class="ticklist">
            <li>Free SSL</li>
            <li>Daily backups</li>
            <li>One-click deploy</li>
          </ul>
          <a class="btn btn-primary" href="#pricing">View plans</a>
        </article>
      </div>
    </div>
  </section>

  <!-- Feature highlights -->
  <section class="features" id="features">
    <div class="container">
      <h2>Built for reliability and speed</h2>
      <div class="feature-grid">
        <article class="feature">
          <h3>Latest-gen processors</h3>
          <p>High clocks and modern architectures for consistent performance.</p>
        </article>
        <article class="feature">
          <h3>Optimized network</h3>
          <p>Low-latency routes with smart anycast and peering.</p>
        </article>
        <article class="feature">
          <h3>Multi-layer security</h3>
          <p>Active detection, isolation, and DDoS mitigation.</p>
        </article>
        <article class="feature">
          <h3>Powerful panel</h3>
          <p>Backups, analytics, mod/plugin managers, and SSH.</p>
        </article>
        <article class="feature">
          <h3>Flexible scaling</h3>
          <p>Adjust CPU, RAM, storage as your servers grow.</p>
        </article>
        <article class="feature">
          <h3>Global locations</h3>
          <p>Choose regions for best ping to your players.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- Pricing -->
  <section class="pricing" id="pricing">
    <div class="container">
      <h2>Simple, transparent pricing</h2>
      <p class="sub">No hidden fees. Upgrade or downgrade anytime.</p>
      <div class="price-grid">
        <article class="price-card">
          <header>
            <h3>Minecraft Starter</h3>
            <p class="price"><span class="currency">USD</span> 3.99<span class="period">/mo</span></p>
          </header>
          <ul class="features-list">
            <li>2 GB RAM</li>
            <li>2 vCPU</li>
            <li>NVMe storage</li>
            <li>1-click mods</li>
          </ul>
          <a class="btn btn-primary" href="#checkout">Select</a>
        </article>

        <article class="price-card">
          <header>
            <h3>VPS S-1</h3>
            <p class="price"><span class="currency">USD</span> 6.99<span class="period">/mo</span></p>
          </header>
          <ul class="features-list">
            <li>2 vCPU</li>
            <li>4 GB RAM</li>
            <li>40 GB NVMe</li>
            <li>Snapshots</li>
          </ul>
          <a class="btn btn-primary" href="#checkout">Select</a>
        </article>

        <article class="price-card">
          <header>
            <h3>Dedicated E3</h3>
            <p class="price"><span class="currency">USD</span> 49<span class="period">/mo</span></p>
          </header>
          <ul class="features-list">
            <li>4c/8t CPU</li>
            <li>32 GB RAM</li>
            <li>480 GB SSD</li>
            <li>Unmetered bandwidth</li>
          </ul>
          <a class="btn btn-primary" href="#checkout">Select</a>
        </article>

        <article class="price-card">
          <header>
            <h3>Web Basic</h3>
            <p class="price"><span class="currency">USD</span> 2.99<span class="period">/mo</span></p>
          </header>
          <ul class="features-list">
            <li>1 website</li>
            <li>Free SSL</li>
            <li>Daily backups</li>
            <li>Mail & DB</li>
          </ul>
          <a class="btn btn-primary" href="#checkout">Select</a>
        </article>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="faq" id="faq">
    <div class="container">
      <h2>Frequently asked questions</h2>
      <div class="faq-list">
        <details>
          <summary>How fast is deployment?</summary>
          <p>Most servers are ready within a minute. Larger setups may take a few more.</p>
        </details>
        <details>
          <summary>Do you offer 24/7 support?</summary>
          <p>Yes—live chat and tickets around the clock with technical specialists.</p>
        </details>
        <details>
          <summary>Can I migrate from another host?</summary>
          <p>We’ll help with panel-to-panel migrations and data imports.</p>
        </details>
        <details>
          <summary>What payment methods do you accept?</summary>
          <p>Cards, PayPal, and select local methods depending on region.</p>
        </details>
        <details>
          <summary>Is DDoS protection included?</summary>
          <p>Yes, multi-layer protection is included for all services.</p>
        </details>
      </div>
    </div>
  </section>

  <!-- Community CTA -->
  <section class="discord" id="status">
    <div class="container discord-inner">
      <div class="discord-copy">
        <h2>Join our community</h2>
        <p>Get updates, tips, and instant support from staff and users.</p>
        <a class="btn btn-outline" href="#" aria-label="Join Discord">Join Discord</a>
      </div>
      <div class="discord-status">
        <span class="status-dot"></span>
        <span class="status-label">All services operational</span>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="site-footer">
    <div class="container footer-inner">
      <div class="footer-brand">
        <img src="assets/img/logo.svg" alt="Your Hosting" class="brand-logo" />
        <span class="brand-name">Your Hosting</span>
      </div>
      <nav class="footer-nav">
        <a href="#legal">Legal</a>
        <a href="#client">Client Space</a>
        <a href="#web">Web Hosting</a>
      </nav>
      <p class="small">© 2025 Your Company. Replace names, copy, and assets with your brand.</p>
    </div>
  </footer>

  <script src="assets/js/script.js"></script>
</body>
</html>

<template>
  <div class="site-wrapper">
    <nav class="navbar">
      <div class="nav-container">
        <span class="logo">ZEXOLVER</span>
        <div class="links">
          <a href="#home">Home</a>
          <a href="#services">Services</a>
          <a href="/info/">Server Status</a>
        </div>
      </div>
    </nav>

    <header id="home" class="section hero">
      <div class="badge">SYSTEMS ONLINE (v6)</div>
      <h1>Sovereign Infrastructure</h1>
      <p class="subtitle">High-performance hosting powered by Rust & IPv6</p>
      <a href="#services" class="btn-primary">Explore Services</a>
    </header>

    <section id="services" class="section services">
      <h2>Hosted Services</h2>
      <div class="grid">
        <div class="card">
          <h3>Code Forge</h3>
          <p>Self-hosted Git instances for private development.</p>
          <span class="status">Planned</span>
        </div>
        <div class="card">
          <h3>Matrix Node</h3>
          <p>Secure, decentralized communication (Coming Soon).</p>
          <span class="status-pending">Planned</span>
        </div>
        <div class="card">
          <h3>File Storage</h3>
          <p>WebDAV and Miniserve high-speed access.</p>
          <span class="status">Planned</span>
        </div>
      </div>
    </section>

    <footer class="section about">
      <h2>Why IPv6?</h2>
      <p>By moving to an IPv6-only architecture, we eliminate the need for NAT, reduce latency, and embrace the future of the internet. This server is built on a custom Rust-based proxy stack for maximum security.</p>
      <p class="footer-note">&copy; 2026 Zexolver Main Server</p>
    </footer>
  </div>
</template>

<style>
/* Global resets for smooth scrolling */
html { scroll-behavior: smooth; }
body { margin: 0; font-family: 'Inter', sans-serif; background: #0f172a; color: #f8fafc; }

.section { padding: 80px 20px; max-width: 1000px; margin: 0 auto; text-align: center; }

/* Navbar */
.navbar { position: sticky; top: 0; background: rgba(15, 23, 42, 0.9); backdrop-filter: blur(10px); border-bottom: 1px solid #1e293b; z-index: 100; padding: 15px 0; }
.nav-container { display: flex; justify-content: space-between; align-items: center; max-width: 1000px; margin: 0 auto; padding: 0 20px; }
.logo { font-weight: 800; color: #38bdf8; letter-spacing: 1px; }
.links a { margin-left: 20px; text-decoration: none; color: #94a3b8; transition: color 0.3s; }
.links a:hover { color: #38bdf8; }

/* Hero */
.hero { min-height: 80vh; display: flex; flex-direction: column; justify-content: center; }
h1 { font-size: 3.5rem; margin: 10px 0; color: #f8fafc; }
.badge { background: #065f46; color: #34d399; display: inline-block; padding: 5px 15px; border-radius: 20px; font-size: 0.8rem; font-weight: bold; }
.btn-primary { background: #38bdf8; color: #0f172a; padding: 12px 30px; border-radius: 8px; text-decoration: none; font-weight: bold; margin-top: 20px; display: inline-block; }

/* Grid */
.grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; margin-top: 40px; }
.card { background: #1e293b; border: 1px solid #334155; padding: 30px; border-radius: 12px; text-align: left; }
.card h3 { margin-top: 0; color: #38bdf8; }
.status { color: #34d399; font-size: 0.8rem; font-weight: bold; text-transform: uppercase; }
.status-pending { color: #94a3b8; font-size: 0.8rem; font-weight: bold; text-transform: uppercase; }

.about { border-top: 1px solid #1e293b; color: #94a3b8; }
</style>

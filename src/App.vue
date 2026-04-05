<template>
  <div class="dashboard">
    <div class="badge">SYSTEMS ONLINE (v6)</div>
    <h1>Zexolver's Dashboard</h1>
    <p class="subtitle">Vue + Farm + Rust Infrastructure</p>
    
    <div class="nav-links">
      <a href="/info/" class="btn">View Server Status List</a>
    </div>

    <div class="stats-grid">
      <div class="stat-card">
        <h3>Network</h3>
        <p>IPv6 Only (Encrypted)</p>
      </div>
      <div class="stat-card">
        <h3>Storage</h3>
        <p>RAID Array Linked</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.dashboard { text-align: center; color: #f8fafc; padding: 40px; }
.badge { display: inline-block; background: #065f46; color: #34d399; padding: 5px 15px; border-radius: 20px; font-weight: bold; margin-bottom: 15px; }
h1 { color: #38bdf8; font-size: 3rem; margin: 0; }
.subtitle { color: #94a3b8; margin-bottom: 30px; }
.btn { background: #38bdf8; color: #0f172a; padding: 12px 24px; text-decoration: none; border-radius: 8px; font-weight: bold; }
.stats-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; max-width: 500px; margin: 40px auto; }
.stat-card { background: #1e293b; border: 1px solid #334155; padding: 20px; border-radius: 12px; }
</style>

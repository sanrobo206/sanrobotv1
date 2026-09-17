---
layout: home
title: SanSCARA - Technical Analysis
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap');

  body {
    background-color: #f8fafc;
    background-image: radial-gradient(at 0% 0%, hsla(210,100%,93%,1) 0, transparent 50%),
                      radial-gradient(at 50% 0%, hsla(220,100%,95%,1) 0, transparent 50%),
                      radial-gradient(at 100% 0%, hsla(210,100%,93%,1) 0, transparent 50%);
    min-height: 100vh;
    margin: 0;
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(32px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .animate-section {
    animation: fadeInUp 1s cubic-bezier(0.22, 1, 0.36, 1) forwards;
    opacity: 0;
  }

  .technical-card {
    background: rgba(255, 255, 255, 0.86);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.6);
    border-radius: 32px;
    padding: 70px 60px;
    box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.08);
  }

  .hero-image {
    max-width: 760px;
    margin: 0 auto 60px;
    padding: 15px;
    background: #ffffff;
    border-radius: 24px;
    box-shadow: inset 0 2px 4px rgba(0,0,0,0.05), 0 20px 40px rgba(0,0,0,0.08);
  }

  .hero-image img {
    width: 100%;
    display: block;
    border-radius: 16px;
  }

  .technical-card h2 {
    color: #1e293b !important;
    font-size: 2rem !important;
    margin: 50px 0 18px;
    padding-left: 16px;
    border-left: 5px solid #2563eb;
  }

  .technical-card p {
    color: #475569 !important;
    font-size: 1.15rem;
    line-height: 1.85;
  }

  .spec-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 18px;
    margin: 28px 0;
  }

  .spec-item {
    background: #eff6ff;
    border: 1px solid #dbeafe;
    border-radius: 18px;
    padding: 24px;
  }

  .spec-item strong {
    display: block;
    color: #1e40af;
    font-size: 0.85rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    margin-bottom: 8px;
  }

  .spec-item span {
    color: #334155;
    font-size: 1.05rem;
    line-height: 1.55;
  }

  .cta-button {
    display: inline-block;
    padding: 18px 42px;
    background: #2563eb;
    color: #ffffff !important;
    text-decoration: none;
    border-radius: 100px;
    font-weight: 700;
    letter-spacing: 1px;
    text-transform: uppercase;
    transition: all 0.3s ease;
    box-shadow: 0 10px 25px rgba(37, 99, 235, 0.2);
  }

  .cta-button:hover {
    background: #1e40af;
    transform: translateY(-2px);
    box-shadow: 0 15px 30px rgba(37, 99, 235, 0.3);
  }

  @media (max-width: 700px) {
    .technical-card { padding: 42px 22px; }
    .spec-grid { grid-template-columns: 1fr; }
    .page-title { font-size: 3rem !important; }
  }
</style>

<main style="max-width: 1100px; margin: 0 auto; padding: 100px 24px; box-sizing: border-box;">
  <header class="animate-section" style="text-align: center; margin-bottom: 70px;">
    <h1 class="page-title" style="font-size: 5rem; font-weight: 800; color: #0f172a; margin-bottom: 18px; letter-spacing: -0.05em;">
      San<span style="color: #2563eb;">SCARA</span>
    </h1>
    <p style="font-size: 1rem; color: #64748b; font-weight: 700; letter-spacing: 4px; text-transform: uppercase;">Industrial Robotic System</p>
  </header>

  <article class="technical-card animate-section">
    <div class="hero-image">
      <img src="{{ '/sanscara.jpg' | relative_url }}" alt="SanSCARA CNC-machined aluminum robotic system">
    </div>

    <h2>Project Overview</h2>
    <p>
      SanSCARA is an industrial-quality SCARA platform built around a rigid, CNC-machined aluminum structure. The system combines two rotary SCARA links with dedicated Y-axis and Z-axis linear rails, extending its working envelope while preserving controlled, repeatable motion.
    </p>

    <div class="spec-grid">
      <div class="spec-item">
        <strong>Construction</strong>
        <span>CNC-machined aluminum structure</span>
      </div>
      <div class="spec-item">
        <strong>Linear Motion</strong>
        <span>Dedicated Y-axis and Z-axis rails</span>
      </div>
      <div class="spec-item">
        <strong>Primary Joint 1</strong>
        <span>Robstride 00 motor</span>
      </div>
      <div class="spec-item">
        <strong>Primary Joint 2</strong>
        <span>Robstride 05 motor</span>
      </div>
      <div class="spec-item">
        <strong>Wrist</strong>
        <span>Feetech STS3250 servos for roll, yaw, and pitch</span>
      </div>
      <div class="spec-item">
        <strong>Gripper</strong>
        <span>Feetech STS3250-driven rack-and-pinion mechanism</span>
      </div>
    </div>

    <h2>Rigid SCARA Joint Architecture</h2>
    <p>
      The first and second SCARA links each use two conical bearings. The bearings are preloaded to remove mechanical play, increase joint stiffness, and maintain a rigid connection through both links. This bearing arrangement supports the industrial-quality mechanical design and reduces unwanted movement at the end effector.
    </p>

    <h2>Primary Joint Actuation</h2>
    <p>
      The first rotary joint is driven by a Robstride 00 motor, while the second is driven by a Robstride 05. These motors actuate the two main links of the SCARA mechanism. The rigid aluminum links and preloaded bearing assemblies provide a stable mechanical foundation for their motion.
    </p>

    <h2>Y and Z Linear Motion</h2>
    <p>
      SanSCARA incorporates both a Y rail and a Z rail. The Y-axis rail translates the robot assembly along the base, while the vertical Z-axis rail changes the operating height. Closed-loop stepper drivers provide monitored linear-axis actuation, combining stepper positioning with feedback for dependable motion control.
    </p>

    <h2>Roll-Yaw-Pitch Wrist</h2>
    <p>
      At the end of the SCARA links, a three-axis wrist provides roll, yaw, and pitch motion. Feetech STS3250 servos actuate these final orientation axes, allowing the end effector to approach a target from multiple angles instead of remaining limited to a fixed tool orientation.
    </p>

    <h2>Rack-and-Pinion Gripper</h2>
    <p>
      The end effector uses a rack-and-pinion gripper powered by a Feetech STS3250 servo. The mechanism converts the servo's rotary output into coordinated linear jaw motion for controlled opening and closing.
    </p>

    <h2>System Summary</h2>
    <p>
      CNC-machined aluminum, preloaded conical bearings, Robstride joint motors, closed-loop stepper-driven linear axes, and Feetech wrist and gripper actuation work together as one rigid industrial robotic platform. SanSCARA combines an expanded linear work envelope with SCARA speed and a multi-axis wrist for flexible manipulation.
    </p>

    <div style="text-align: center; margin-top: 60px;">
      <a href="{{ '/' | relative_url }}" class="cta-button">Return to Project Hub</a>
    </div>
  </article>

  <footer style="margin-top: 80px; text-align: center; color: #94a3b8; font-size: 0.9rem; padding-bottom: 40px; letter-spacing: 2px;">
    &copy; 2026 DESIGNED BY <span style="font-weight: 800; color: #1e293b;">SANATAN SINHA</span>
  </footer>
</main>

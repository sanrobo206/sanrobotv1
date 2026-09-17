---
layout: home
title: SanRobot — Advanced Robotic Systems
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

  :root {
    --ink: #0b1220;
    --muted: #526174;
    --line: #d9e0e8;
    --surface: #ffffff;
    --canvas: #f3f6f9;
    --accent: #1769e0;
    --accent-dark: #0f4fab;
  }

  * {
    box-sizing: border-box;
  }

  html {
    scroll-behavior: smooth;
  }

  body {
    background:
      linear-gradient(180deg, rgba(23, 105, 224, 0.06) 0, transparent 420px),
      var(--canvas);
    color: var(--ink);
    min-height: 100vh;
    margin: 0;
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    -webkit-font-smoothing: antialiased;
  }

  body > .wrapper {
    width: 100%;
    max-width: none;
    margin: 0;
  }

  body > .wrapper > header,
  body > .wrapper > footer {
    display: none;
  }

  body > .wrapper > section {
    float: none;
    width: 100%;
    padding: 0;
  }

  .site-nav {
    position: sticky;
    top: 0;
    z-index: 100;
    background: rgba(255, 255, 255, 0.92);
    border-bottom: 1px solid rgba(217, 224, 232, 0.9);
    backdrop-filter: blur(18px);
  }

  .nav-inner {
    max-width: 1200px;
    height: 72px;
    margin: 0 auto;
    padding: 0 28px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .brand {
    color: var(--ink) !important;
    text-decoration: none;
    font-size: 1.25rem;
    font-weight: 800;
    letter-spacing: -0.04em;
  }

  .brand-mark {
    color: var(--accent);
  }

  .nav-links {
    display: flex;
    gap: 28px;
  }

  .nav-links a {
    color: #344256 !important;
    text-decoration: none;
    font-size: 0.84rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .nav-links a:hover {
    color: var(--accent) !important;
  }

  .site-shell {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 28px 72px;
  }

  .site-hero {
    min-height: 440px;
    padding: 112px 0 88px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    border-bottom: 1px solid var(--line);
  }

  .hero-kicker {
    margin: 0 0 18px;
    color: var(--accent);
    font-size: 0.78rem;
    font-weight: 800;
    letter-spacing: 0.18em;
    text-transform: uppercase;
  }

  .site-hero h1 {
    max-width: 900px;
    margin: 0;
    color: var(--ink);
    font-size: clamp(4.5rem, 10vw, 8rem);
    font-weight: 800;
    line-height: 0.92;
    letter-spacing: -0.075em;
  }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .animate-section {
    animation: fadeInUp 0.7s cubic-bezier(0.22, 1, 0.36, 1) forwards;
    opacity: 0;
  }

  .delay-1 { animation-delay: 0.05s; }
  .delay-2 { animation-delay: 0.1s; }
  .delay-3 { animation-delay: 0.15s; }
  .delay-4 { animation-delay: 0.2s; }
  .delay-5 { animation-delay: 0.25s; }
  .delay-6 { animation-delay: 0.3s; }
  .delay-7 { animation-delay: 0.35s; }

  .project-card {
    display: grid;
    grid-template-columns: minmax(0, 1.2fr) minmax(300px, 0.8fr);
    gap: 34px 48px;
    align-items: center;
    margin: 32px 0;
    padding: 42px;
    background: var(--surface);
    border: 1px solid var(--line);
    border-radius: 20px;
    box-shadow: 0 12px 35px rgba(12, 28, 50, 0.06);
    transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
  }

  .project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 20px 48px rgba(12, 28, 50, 0.1);
    border-color: #b9c8d9;
  }

  .project-card h2 {
    grid-column: 1 / -1;
    margin: 0 !important;
    padding-bottom: 22px;
    color: var(--ink) !important;
    border-bottom: 1px solid var(--line);
    font-size: clamp(2rem, 4vw, 3.15rem) !important;
    font-weight: 750;
    line-height: 1.05;
    letter-spacing: -0.055em;
    text-align: left !important;
  }
  
  .project-description {
    color: var(--muted) !important;
    font-size: 1.05rem;
    line-height: 1.75;
    max-width: none;
    margin: 0;
  }

  .project-description b {
    color: #17243a;
  }

  .cta-button {
    display: inline-block;
    padding: 14px 24px;
    background: var(--ink);
    color: #ffffff !important;
    text-decoration: none;
    border-radius: 8px;
    font-weight: 700;
    font-size: 0.76rem;
    letter-spacing: 0.09em;
    text-transform: uppercase;
    transition: background 0.2s ease, transform 0.2s ease;
    box-shadow: none;
  }

  .cta-button:hover {
    background: var(--accent);
    transform: translateY(-2px);
  }

  .image-container {
    width: 100%;
    max-width: none !important;
    margin: 0 !important;
    padding: 0;
    overflow: hidden;
    background: #e8edf2;
    border: 1px solid #dde4eb;
    border-radius: 12px;
    box-shadow: none;
  }

  .image-container img {
    width: 100%;
    max-height: 620px;
    object-fit: contain;
    border-radius: 0;
    display: block;
  }

  .about-section {
    margin-top: 88px;
    padding: 64px;
    display: grid;
    grid-template-columns: minmax(230px, 0.7fr) minmax(0, 1.3fr);
    gap: 64px;
    color: #ffffff;
    background: var(--ink);
    border-radius: 20px;
  }

  .about-section h2 {
    margin: 0;
    color: #ffffff !important;
    font-size: clamp(2rem, 4vw, 3.25rem) !important;
    line-height: 1.08;
    letter-spacing: -0.05em;
  }

  .about-section p {
    margin: 0;
    color: #c2cedd;
    font-size: 1.12rem;
    line-height: 1.8;
  }

  .site-footer {
    margin-top: 52px;
    padding: 30px 0 12px;
    display: flex;
    justify-content: space-between;
    color: #75849a;
    border-top: 1px solid var(--line);
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
  }

  @media (max-width: 800px) {
    .site-nav {
      position: relative;
    }

    .site-hero {
      min-height: 360px;
      padding: 76px 0 64px;
    }

    .project-card {
      grid-template-columns: 1fr;
      gap: 26px;
      padding: 26px;
    }

    .about-section {
      grid-template-columns: 1fr;
      gap: 24px;
      padding: 42px 28px;
    }
  }

  @media (max-width: 520px) {
    .nav-inner,
    .site-shell {
      padding-left: 18px;
      padding-right: 18px;
    }

    .nav-links {
      gap: 16px;
    }

    .project-card {
      margin: 20px 0;
      padding: 20px;
      border-radius: 14px;
    }

    .site-footer {
      display: block;
      line-height: 1.8;
    }
  }

  @media (prefers-reduced-motion: reduce) {
    html { scroll-behavior: auto; }
    .animate-section {
      animation: none;
      opacity: 1;
    }
    .project-card,
    .cta-button {
      transition: none;
    }
  }
</style>

<nav class="site-nav" aria-label="Primary navigation">
  <div class="nav-inner">
    <a class="brand" href="{{ '/' | relative_url }}">San<span class="brand-mark">Robot</span></a>
    <div class="nav-links">
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
    </div>
  </div>
</nav>

<div class="site-shell">
  <header class="site-hero animate-section">
    <p class="hero-kicker">Advanced Robotic Systems</p>
    <h1>SanRobot</h1>
  </header>

  <!-- Project 1: SanSCARA -->
  <div id="projects" class="animate-section delay-1">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">SanSCARA</h2>
      <div class="image-container" style="max-width: 720px; margin-left: auto; margin-right: auto;">
        <img src="{{ '/sanscara.jpg' | relative_url }}" alt="SanSCARA industrial aluminum robotic system">
      </div>
      <div class="project-description">
        SanSCARA is a unique hybrid, industrial-quality <b>7-axis SCARA robot</b>. Its aluminum components are CNC machined for rigidity and precision. It delivers <b>0.05 mm repeatability</b> and extends the traditional SCARA architecture with a roll-yaw-pitch wrist at the end, enabling flexible tool orientation across a broad working envelope.
      </div>
    </section>
  </div>

  <!-- Project 2: SR2i -->
  <div class="animate-section delay-2">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">SR2i</h2>
      <div class="image-container" style="max-width: 900px; margin-left: auto; margin-right: auto;">
        <img src="{{ '/sr2i.jpg' | relative_url }}" alt="SR2i lightweight industrial 7-axis robotic arm">
      </div>
      <div class="project-description">
        SR2i is a lightweight, industrial <b>7-axis robotic arm</b> constructed from carbon fiber and aluminum. Precision ball bearings support smooth, rigid joint motion, while its high-performance mechanical design achieves <b>0.1 mm repeatability</b> for accurate and versatile manipulation.
      </div>
    </section>
  </div>

  <!-- Project 3: sGripper Ultra-Lightweight -->
  <div class="animate-section delay-3">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">sGripper Ultra-Lightweight</h2>
      <div class="image-container" style="max-width: 900px; margin-left: auto; margin-right: auto;">
        <img src="{{ '/sgripper-ultralight.jpg' | relative_url }}" alt="sGripper Ultra-Lightweight rack-and-pinion gripper">
      </div>
      <div class="project-description">
        An ultra-lightweight <b>rack-and-pinion gripper</b> that uses carbon-fiber guides and a lightweight carriage. A miniature ball bearing keeps each rack firmly engaged with the pinion, preventing it from twisting or lifting away during operation. At just <b>150 grams including the motor</b>, it is significantly lighter than other grippers of comparable quality while retaining a precise, rigid mechanism.
      </div>
    </section>
  </div>

  <!-- Project 4: sROBOT v.1 -->
  <div class="animate-section delay-4">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">sROBOT v.1</h2>
      <div class="image-container">
        <img src="Screenshot from 2026-02-20 13-59-47.jpeg" alt="sROBOT v.1">
      </div>
      <div class="project-description">
        The <b>srobotv1</b> is an advanced 7-axis robotic manipulator engineered for maximum stability and dexterity. By integrating <b>bearings throughout the entire assembly</b>, I eliminated the 1-degree base deflection that typically results in massive precision errors at the gripper.
        <div style="text-align: center; margin-top: 50px;">
          <a href="https://sanrobo206.github.io/srobotv1/" class="cta-button">EXPLORE TECHNICAL ANALYSIS</a>
        </div>
      </div>
    </section>
  </div>

  <!-- Project 5: Mobile Fire Detection -->
  <div class="animate-section delay-5">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">Fire Detection Rover</h2>
      <div class="image-container">
        <img src="rover-cad.jpeg" alt="Mobile Fire Detection System Rover">
      </div>
      <div class="project-description">
        An autonomous safety solution designed for rapid response in high-risk environments. This project integrates <b>multi-sensor data fusion</b> to identify heat signatures and smoke patterns in real-time, providing a mobile shield against industrial hazards.
        <div style="text-align: center; margin-top: 50px;">
          <a href="https://sanrobo206.github.io/mfds/" class="cta-button">EXPLORE TECHNICAL ANALYSIS</a>
        </div>
      </div>
    </section>
  </div>

  <!-- Project 6: sHUMANOID v.1 -->
  <div class="animate-section delay-6">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">sHUMANOID v.1</h2>
      <div class="image-container">
        <img src="humanoidscreenshot(1).png" alt="sHUMANOID v.1">
      </div>
      <div class="project-description">
        A mobile humanoid platform engineered for complex manipulation. Built with a robust <b>extruded aluminum</b> frame, the robot features a <b>mecanum wheel base</b> for omnidirectional movement, blending industrial strength with fluid agility.
        <div style="text-align: center; margin-top: 50px;">
          <a href="https://sanrobo206.github.io/shumanoidv1" class="cta-button">DIVE DEEPER</a>
        </div>
      </div>
    </section>
  </div>

  <!-- Project 7: sGRIPPER v.1 -->
  <div class="animate-section delay-7">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">sGRIPPER v.1</h2>
      <div class="image-container" style="max-width: 800px; margin-left: auto; margin-right: auto;">
        <img src="IMG_6587-removebg-preview.png" alt="sGRIPPER v.1">
      </div>
      <div class="project-description">
        A high-precision end-effector featuring an industrial <b>MGN 7 linear rail</b> and a custom <b>cam-based actuation</b> mechanism. This architecture provides perfect parallel finger movement and high mechanical advantage.
        <div style="text-align: center; margin-top: 50px;">
          <a href="https://sanrobo206.github.io/sgripperv1" class="cta-button">EXPLORE MORE INSIDE THE PROJECT</a>
        </div>
      </div>
    </section>
  </div>

  <section id="about" class="about-section animate-section">
    <h2>About Sanatan Sinha</h2>
    <p>Sanatan Sinha is the engineer and creator behind SanRobot. His work focuses on developing precise, lightweight robotic systems through practical mechanical design, advanced materials, and iterative prototyping.</p>
  </section>

  <footer class="site-footer animate-section">
    <span>&copy; 2026 Designed by Sanatan Sinha</span>
  </footer>

</div>

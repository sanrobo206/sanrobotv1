---
layout: home
title: Sanatan - Projects
---

<style>
  /* Professional Fade-In Animation */
  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .animate-section {
    animation: fadeInUp 1s ease-out forwards;
    opacity: 0;
  }

  .delay-1 { animation-delay: 0.2s; }
  .delay-2 { animation-delay: 0.4s; }

  /* Premium Website Background */
  body {
    background: linear-gradient(135deg, #fdfbfb 0%, #ebedee 100%);
    min-height: 100vh;
    margin: 0;
  }

  /* Glassmorphism Project Cards */
  .project-card {
    background: rgba(255, 255, 255, 0.8);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.5);
    border-radius: 24px;
    padding: 50px;
    box-shadow: 0 20px 40px rgba(0,0,0,0.06);
    transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1);
  }

  .project-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 30px 60px rgba(0,0,0,0.12);
  }

  /* Premium Button Styling */
  .cta-button {
    display: inline-block;
    padding: 18px 40px;
    background: #000000;
    color: #ffffff !important;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 700;
    font-size: 1.1rem;
    transition: 0.3s;
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
  }

  .cta-button:hover {
    background: #333;
    transform: scale(1.05);
    box-shadow: 0 12px 25px rgba(0,0,0,0.2);
  }
</style>

<div style="width: 100%; margin: 0; padding: 100px 20px; font-family: 'Google Sans', -apple-system, sans-serif; box-sizing: border-box;">

  <!-- Website Header -->
  <header class="animate-section" style="text-align: center; margin-bottom: 100px;">
    <h1 style="font-size: 4.5rem; font-weight: 800; color: #111; margin-bottom: 10px; letter-spacing: -0.06em;">
      Sanatan <span style="color: #666;">-</span> Projects
    </h1>
    <p style="font-size: 1.6rem; color: #888; font-weight: 400; letter-spacing: 1px;">BY SANATAN SINHA</p>
  </header>

  <!-- Project 1 Section -->
  <div class="animate-section delay-1" style="max-width: 1100px; margin: 0 auto 100px auto;">
    <section class="project-card">
      <h2 style="font-size: 2.8rem; font-weight: 700; color: #000; margin-bottom: 40px; text-align: center; letter-spacing: -0.02em;">srobotv1</h2>
      
      <!-- Using the JPEG version of your screenshot -->
      <div style="text-align: center; margin-bottom: 45px;">
        <img src="Screenshot from 2026-02-20 13-59-47.jpeg" alt="srobotv1 Robot Arm" style="width: 100%; max-width: 950px; border-radius: 16px; box-shadow: 0 15px 45px rgba(0,0,0,0.1);">
      </div>

      <div style="font-size: 1.25rem; color: #444; text-align: justify; padding: 0 5%; line-height: 1.8;">
        The <b>srobotv1</b> is an advanced 7-axis robotic manipulator engineered for maximum stability and dexterity. By integrating <b>bearings throughout the entire assembly</b>, I eliminated the 1-degree base deflection that typically results in massive precision errors at the gripper. 
        <br><br>
        Utilizing a unique <b>seven-axis</b> configuration, the srobotv1 achieves superior reach and maneuverability compared to standard 6-axis arms.
        <br><br>
        <div style="text-align: center; margin-top: 40px;">
          <a href="https://sanrobo206.github.io" class="cta-button">EXPLORE TECHNICAL ANALYSIS</a>
        </div>
      </div>
    </section>
  </div>

  <!-- Project 2 Section (Placeholder) -->
  <div class="animate-section delay-2" style="max-width: 1100px; margin: 0 auto 100px auto;">
    <section class="project-card" style="text-align: center; padding: 60px;">
      <h2 style="font-size: 2.2rem; font-weight: 700; color: #000; margin-bottom: 20px;">Project 2: robot</h2>
      <p style="font-size: 1.2rem; color: #777;">Advanced autonomous systems and navigation research.</p>
    </section>
  </div>

  <!-- Footer -->
  <footer class="animate-section" style="margin-top: 150px; text-align: center; color: #aaa; font-size: 1rem; padding-bottom: 60px; text-transform: uppercase; letter-spacing: 3px;">
    Created by <span style="font-weight: 700; color: #111;">Sanatan Sinha</span>
  </footer>

</div>

---
layout: home
title: Sanatan - Projects
---

<style>
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
  .delay-3 { animation-delay: 0.6s; }

  body {
    background: linear-gradient(135deg, #fdfbfb 0%, #ebedee 100%);
    min-height: 100vh;
    margin: 0;
  }

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

  .cta-button {
    display: inline-block;
    padding: 18px 40px;
    background: #000000;
    color: #ffffff !important;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 700;
    font-size: 1.1rem;
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
  }

  .cta-button:hover {
    background: #333;
    transform: scale(1.05);
  }
</style>

<div style="width: 100%; margin: 0; padding: 100px 20px; font-family: 'Google Sans', -apple-system, sans-serif; box-sizing: border-box;">

  <header class="animate-section" style="text-align: center; margin-bottom: 100px;">
    <h1 style="font-size: 4.5rem; font-weight: 800; color: #111; margin-bottom: 10px; letter-spacing: -0.06em;">
      Sanatan <span style="color: #666;">-</span> Projects
    </h1>
    <p style="font-size: 1.6rem; color: #888; font-weight: 400; letter-spacing: 1px;">BY SANATAN SINHA</p>
  </header>

  <!-- Project 1 Section -->
  <div class="animate-section delay-1" style="max-width: 1100px; margin: 0 auto 100px auto;">
    <section class="project-card">
      <h2 style="font-size: 2.8rem; font-weight: 700; color: #000; margin-bottom: 40px; text-align: center;">srobotv1</h2>
      <div style="text-align: center; margin-bottom: 45px;">
        <img src="Screenshot from 2026-02-20 13-59-47.jpeg" alt="srobotv1" style="width: 100%; max-width: 950px; border-radius: 16px; box-shadow: 0 15px 45px rgba(0,0,0,0.1);">
      </div>
      <div style="font-size: 1.25rem; color: #444; text-align: justify; padding: 0 5%; line-height: 1.8;">
        The <b>srobotv1</b> is an advanced 7-axis robotic manipulator engineered for maximum stability and dexterity. By integrating <b>bearings throughout the entire assembly</b>, I eliminated the 1-degree base deflection that typically results in massive precision errors at the gripper.
        <br><br>
        <div style="text-align: center; margin-top: 40px;">
          <a href="https://sanrobo206.github.io/srobotv1/" class="cta-button">EXPLORE TECHNICAL ANALYSIS</a>
        </div>
      </div>
    </section>
  </div>

  <!-- Project 2 Section -->
  <div class="animate-section delay-2" style="max-width: 1100px; margin: 0 auto 100px auto;">
    <section class="project-card">
      <h2 style="font-size: 2.8rem; font-weight: 700; color: #000; margin-bottom: 40px; text-align: center;">Mobile Fire Detection System</h2>
      <div style="text-align: center; margin-bottom: 45px;">
        <img src="rover-cad.jpeg" alt="Mobile Fire Detection System Rover" style="width: 100%; max-width: 950px; border-radius: 16px; box-shadow: 0 15px 45px rgba(0,0,0,0.1);">
      </div>
      <div style="font-size: 1.25rem; color: #444; text-align: justify; padding: 0 5%; line-height: 1.8;">
        The <b>Mobile Fire Detection System</b> is an autonomous safety solution designed for rapid response in high-risk environments. This project integrates multi-sensor data fusion to identify heat signatures and smoke patterns in real-time.
        <br><br>
        <div style="text-align: center; margin-top: 40px;">
          <a href="https://sanrobo206.github.io/mfds/" class="cta-button">EXPLORE TECHNICAL ANALYSIS</a>
        </div>
      </div>
    </section>
  </div>

  <!-- Project 3 Section -->
  <div class="animate-section delay-3" style="max-width: 1100px; margin: 0 auto 100px auto;">
    <section class="project-card">
      <h2 style="font-size: 2.8rem; font-weight: 700; color: #000; margin-bottom: 40px; text-align: center;">sHUMANOID v.1</h2>
      <div style="text-align: center; margin-bottom: 45px;">
        <img src="humanoid.png" alt="sHUMANOID v.1" style="width: 100%; max-width: 950px; height: 500px; object-fit: cover; object-position: 50% 100%; border-radius: 16px; box-shadow: 0 15px 45px rgba(0,0,0,0.1);">
      </div>
      <div style="font-size: 1.25rem; color: #444; text-align: justify; padding: 0 5%; line-height: 1.8;">
        The <b>sHUMANOID v.1</b> is a mobile humanoid platform engineered for complex manipulation and high-mobility navigation. Built entirely from a robust <b>extruded aluminum</b> frame, the robot features a <b>mecanum wheel</b> base for omnidirectional movement. 
        <br><br>
        For high-dexterity interaction, the system utilizes a <b>bimanual setup</b> incorporating two <b>sROBOT v.1</b> robotic arms, allowing for coordinated dual-arm tasks and advanced research into mobile manipulation.
        <br><br>
        <div style="text-align: center; margin-top: 40px;">
          <a href="https://sanrobo206.github.io/shumanoidv1/" class="cta-button">DIVE DEEPER</a>
        </div>
      </div>
    </section>
  </div>

  <footer class="animate-section" style="margin-top: 150px; text-align: center; color: #aaa; font-size: 1rem; padding-bottom: 60px; text-transform: uppercase; letter-spacing: 3px;">
    Created by <span style="font-weight: 700; color: #111;">Sanatan Sinha</span>
  </footer>

</div>

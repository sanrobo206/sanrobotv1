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
    animation: fadeInUp 0.8s ease-out forwards;
    opacity: 0;
  }

  /* Delay for staggered effect */
  .delay-1 { animation-delay: 0.2s; }
  .delay-2 { animation-delay: 0.4s; }
  .delay-3 { animation-delay: 0.6s; }

  body {
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    min-height: 100vh;
  }

  .project-card {
    background: rgba(255, 255, 255, 0.9);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 20px;
    padding: 40px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.05);
    transition: transform 0.3s ease;
  }

  .project-card:hover {
    transform: translateY(-5px);
  }
</style>

<div style="width: 100%; margin: 0; padding: 80px 20px; font-family: 'Google Sans', -apple-system, sans-serif; box-sizing: border-box;">

  <!-- Header -->
  <header class="animate-section" style="text-align: center; margin-bottom: 80px;">
    <h1 style="font-size: 4rem; font-weight: 800; color: #1a1a1a; margin-bottom: 10px; letter-spacing: -0.05em;">
      Sanatan <span style="color: #007bff;">-</span> Projects
    </h1>
    <p style="font-size: 1.5rem; color: #555; font-weight: 400;">by Sanatan Sinha</p>
  </header>

  <!-- Project 1 Section -->
  <div class="animate-section delay-1" style="max-width: 1100px; margin: 0 auto 100px auto;">
    <section class="project-card">
      <h2 style="font-size: 2.5rem; font-weight: 700; color: #1a1a1a; margin-bottom: 30px; text-align: center;">Project 1: srobotv1</h2>
      
      <div style="text-align: center; margin-bottom: 40px;">
        <img src="Screenshot from 2026-02-20 13-59-47.png" alt="srobotv1" style="width: 100%; max-width: 900px; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.1);">
      </div>

      <div style="font-size: 1.2rem; color: #444; text-align: justify; padding: 0 5%; line-height: 1.8;">
        The <b>srobotv1</b> is an advanced 7-axis robotic manipulator designed for high-precision tasks. A critical engineering challenge addressed in this design is the stability of the robot's base; even a minor 1-degree shift at the foundation translates into significant, amplified movement at the gripper. To eliminate this mechanical play and ensure precision, I integrated <b>bearings throughout the entire assembly</b>.
        <br><br>
        Furthermore, by utilizing a <b>seven-axis</b> configuration rather than the industry-standard six, the srobotv1 achieves superior reach and dexterity.
        <br><br>
        <div style="text-align: center; margin-top: 30px;">
          <a href="https://sanrobo206.github.io" style="display: inline-block; padding: 15px 35px; background: #1a1a1a; color: #fff; text-decoration: none; border-radius: 50px; font-weight: 600; transition: 0.3s; box-shadow: 0 5px 15px rgba(0,0,0,0.2);">View Full Technical Analysis</a>
        </div>
      </div>
    </section>
  </div>

  <!-- Project 2 Section -->
  <div class="animate-section delay-2" style="max-width: 1100px; margin: 0 auto 100px auto;">
    <section class="project-card">
      <h2 style="font-size: 2.5rem; font-weight: 700; color: #1a1a1a; margin-bottom: 25px; text-align: center;">Project 2: robot</h2>
      <div style="font-size: 1.2rem; color: #444; text-align: center;">
        Next-generation robotics research focused on autonomous navigation and control.
      </div>
    </section>
  </div>

  <!-- Footer -->
  <footer class="animate-section delay-3" style="margin-top: 150px; text-align: center; color: #666; font-size: 1.1rem; padding-bottom: 50px;">
    Created by <span style="font-weight: 700; color: #1a1a1a;">Sanatan Sinha</span>
  </footer>

</div>

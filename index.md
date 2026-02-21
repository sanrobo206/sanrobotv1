---
layout: home
title: Sanatan - Projects
---

<style>
  @import url('https://fonts.googleapis.com');

  body {
    background-color: #f8fafc;
    background-image: radial-gradient(at 0% 0%, hsla(210,100%,93%,1) 0, transparent 50%), 
                      radial-gradient(at 50% 0%, hsla(220,100%,95%,1) 0, transparent 50%), 
                      radial-gradient(at 100% 0%, hsla(210,100%,93%,1) 0, transparent 50%);
    min-height: 100vh;
    margin: 0;
    font-family: 'Inter', -apple-system, sans-serif;
  }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(40px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .animate-section {
    animation: fadeInUp 1.2s cubic-bezier(0.22, 1, 0.36, 1) forwards;
    opacity: 0;
  }

  .delay-1 { animation-delay: 0.1s; }
  .delay-2 { animation-delay: 0.3s; }
  .delay-3 { animation-delay: 0.5s; }
  .delay-4 { animation-delay: 0.7s; }

  .project-card {
    background: rgba(255, 255, 255, 0.8);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.5);
    border-radius: 32px;
    padding: 80px 60px;
    box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.05);
    transition: all 0.5s ease;
    margin-bottom: 80px;
  }

  .project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 40px 80px -15px rgba(37, 99, 235, 0.1);
    border-color: rgba(37, 99, 235, 0.3);
  }

  .project-card h2 { 
    color: #1e293b !important; 
    font-size: 3.5rem !important; 
    letter-spacing: -0.04em;
  }
  
  .project-description { 
    color: #475569 !important; 
    font-size: 1.35rem; 
    line-height: 1.8; 
    max-width: 900px;
    margin: 0 auto;
  }

  .cta-button {
    display: inline-block;
    padding: 20px 45px;
    background: #2563eb;
    color: #ffffff !important;
    text-decoration: none;
    border-radius: 100px;
    font-weight: 700;
    font-size: 1rem;
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

  .image-container {
    background: #ffffff;
    padding: 15px;
    border-radius: 24px;
    margin-bottom: 60px;
    box-shadow: inset 0 2px 4px rgba(0,0,0,0.05), 0 20px 40px rgba(0,0,0,0.05);
  }

  .image-container img {
    width: 100%;
    border-radius: 16px;
    display: block;
  }
</style>

<div style="max-width: 1200px; margin: 0 auto; padding: 120px 24px; box-sizing: border-box;">

  <header class="animate-section" style="text-align: center; margin-bottom: 120px;">
    <h1 style="font-size: 5rem; font-weight: 800; color: #0f172a; margin-bottom: 20px; letter-spacing: -0.05em;">
      Sanatan <span style="color: #2563eb;">—</span> Projects
    </h1>
    <p style="font-size: 1.2rem; color: #64748b; font-weight: 600; letter-spacing: 4px; text-transform: uppercase;">Engineering Portfolio</p>
  </header>

  <!-- Project 1: srobotv1 -->
  <div class="animate-section delay-1">
    <section class="project-card">
      <h2 style="text-align: center; margin-bottom: 50px;">srobotv1</h2>
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

  <!-- Project 2: Mobile Fire Detection -->
  <div class="animate-section delay-2">
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

  <!-- Project 3: sHUMANOID v.1 -->
  <div class="animate-section delay-3">
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

  <!-- Project 4: sGRIPPER v.1 -->
  <div class="animate-section delay-4">
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

  <footer class="animate-section" style="margin-top: 100px; text-align: center; color: #94a3b8; font-size: 0.9rem; padding-bottom: 80px; letter-spacing: 2px;">
    &copy; 2026 DESIGNED BY <span style="font-weight: 800; color: #1e293b;">SANATAN SINHA</span>
  </footer>

</div>

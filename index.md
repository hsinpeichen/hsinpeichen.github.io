---
layout: default
title: Home
---

<style>
  .wrapper {
    max-width: 1000px !important;
    margin: 0 auto !important;
    padding: 0 20px !important;
    float: none !important;
    display: block !important;
  }

  section {
    width: 100% !important;
    max-width: 100% !important;
    margin: 0 !important;
    padding: 20px 0 !important;
    float: none !important;
    flex: 1;
  }
  .header-nav {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    background: rgba(255, 255, 255, 0.8); 
    backdrop-filter: blur(10px);
    padding: 15px 0;
    margin-bottom: 20px;
    border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    width: 100%;
  }

  .header-nav a {
    margin: 0px 15px;
    text-decoration: none;
    color: #bf5700;
    font-weight: bold;
    font-size: 1.2em;
  }
  .header-nav a:hover {
  color: #ffcc00 !important;
  }

  header {
    background: linear-gradient(rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), url('photos/website-bg.webp') !important;
    background-size: cover !important;
    background-position: bottom !important;
    padding: 60px 0 !important;
    text-align: center !important;
    width: 100vw !important;
    position: relative !important;
    left: 50% !important;
    transform: translateX(-50%) !important;
    margin: 0 0 20px 0 !important;
    float: none !important;
  }

  header ul, header p.view, header .buttons {
    display: none !important;
  }

  header h1 {
    margin: 0 !important;
    width: 100% !important;
  }

  header h1 a {
    color: #ffffff !important;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
    font-size: 1.5em !important;
    font-weight: bold !important;
    pointer-events: none !important;
  }

  header p {
    color: #eeeeee !important;
    font-size: 1.1em !important;
    margin: 15px 0 0 0 !important;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.8);
  }

  .profile-container {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    gap: 40px;
    margin: 0 auto;
    max-width: 950px;
    width: 100%;
  }
  
  .profile-image-wrapper {
    flex: 3;
    display: flex;
    justify-content: center;
  }

  .profile-image {
    width: 100%;
    max-width: 220px;
    height: auto;
    aspect-ratio: 1 / 1;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }

  .profile-text {
    flex: 7;
    font-size: 1.0em;
    line-height: 1.6;
    color: #333;
    text-align: justify !important;
    text-justify: inter-word;
    max-width: 800px;
  }

  .back-to-top {
    position: fixed;
    bottom: 30px;
    right: 30px;
    width: 50px;
    height: 50px;
    background-color: #bf5700;
    color: white !important;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 24px;
    z-index: 9999;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s, background-color 0.3s;
  }

  .back-to-top:hover {
    background-color: #8c4000;
    transform: translateY(-5px);
  }

  html {
    scroll-behavior: smooth;
  }

  @media screen and (max-width: 768px) {
    .back-to-top {
      bottom: 20px;
      right: 20px;
      width: 40px;
      height: 40px;
      font-size: 18px;
    }
  }

footer {
    position: relative !important;
    width: 100% !important;
    text-align: center !important;
    padding: 0 !important;
    margin-top: 80px !important;
    margin-bottom: 20px !important;
    clear: both !important;
    font-size: 0.85em !important;
    color: #999 !important;
    line-height: 1.5 !important;
  }

  footer p {
    margin: 0 0 5px 0 !important; 
    padding: 0 !important;
  }

  footer a {
    color: #999 !important;
    text-decoration: underline;
  }

  footer a:hover {
    color: #bf5700 !important;
  }

  footer p small {
    display: inline-block !important;
    margin-top: 5px !important;
    color: #999 !important;
    font-size: 1em !important;
  }
</style>

<div class="header-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/cv">CV</a>
  <a href="/outreach">Outreach</a>
</div>

<div class="profile-container">
  <img src="photos/avatar.webp" loading="lazy" alt="Hsin-Pei Chen" class="profile-image">
  
  <div class="profile-text">
    <p>I am a graduate student in the <strong>Department of Astronomy at The University of Texas at Austin, working with Dr. Stella Offner.</strong> My work focuses on how stars form and evolve in the Universe.</p>

    <p>I hold a M.S. degree from <strong>Institute of Astronomy, National Tsing Hua University</strong>, Taiwan, where I conducted astrophysical simulations of supernovae. At UT, my <strong>current project investigates the role of cosmic rays in star-forming clouds using STARFORGE simulations.</strong></p>

    <p>I was born and raised in Kaohsiung, a beautiful city in Southern Taiwan. And so was my dog, <a href="https://www.instagram.com/mumu_dog_0910/" style="font-weight: bold; color: #bf5700;">Mumu</a>! We moved to Austin together in the summer of 2024.</p>
    
    <div style="margin-top: 30px;">
        <a href="https://github.com/hsinpeichen" target="_blank" style="margin-right: 20px; color: #bf5700; text-decoration: none; font-weight: bold;">GitHub Profile</a>
        <a href="mailto:hpchen@utexas.edu" target="_blank" style="margin-right: 20px; color: #bf5700; text-decoration: none; font-weight: bold;">Email Me</a>
        <a href="https://www.name-coach.com/hsin-pei-chen-74e4f5c1-32b1-4295-a372-db0a15b96573" target="_blank" style="color: #bf5700; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 5px;">
        <span style="font-size: 1.2em;">🔊</span> My Name
        </a>
    </div>
  </div>
</div>

<footer>
  <p>© 2026 Hsin-Pei Chen | Last updated: Feb 2026</p>
  <p style="font-size: 0.8em; color: #999;">
    All content is licensed under <a href="https://creativecommons.org/licenses/by/4.0/" target="_blank">CC BY 4.0</a> unless otherwise noted.
  </p>
</footer>

<a href="#" class="back-to-top" title="Back to Top">↑</a>
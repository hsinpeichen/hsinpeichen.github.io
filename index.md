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
  }

  section {
    width: 100% !important;
    max-width: 100% !important;
    margin: 0 !important;
    padding: 20px 0 !important;
    float: none !important;
  }

  header {
    background: linear-gradient(rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), url('photos/website-bg.jpeg') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 4.5px 0 !important;
    margin: 0 0 25px 0 !important;
    text-align: center !important;
    
    width: 100vw !important;
    position: relative !important;
    left: 50% !important;
    transform: translateX(-50%) !important;
    margin: 0 0 40px 0 !important;
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
    font-size: 2.2em !important;
    font-weight: bold !important;
    pointer-events: none !important;
  }

  header p {
    color: #eeeeee !important;
    font-size: 1.1em !important;
    margin: 15px 0 0 0 !important;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.8);
  }

  .header-nav {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 15px 0;
    margin-bottom: 20px;
    border-bottom: 1px solid #eee;
    width: 100%;
  }

  .header-nav a {
    margin: 10px 20px;
    text-decoration: none;
    color: #bf5700;
    font-weight: bold;
    font-size: 1.2em;
  }

  .profile-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 20px;
    width: 100%;
  }

  .profile-image {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid #fff;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }

  .profile-text {
    font-size: 1.1em;
    line-height: 1.6;
    color: #333;
    text-align: left;
    max-width: 800px;
  }

  .profile-text strong {
    color: #bf5700;
  }
</style>

<div class="header-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/cv">CV</a>
  <a href="/outreach">Outreach</a>
</div>

<div class="profile-container">
  <img src="photos/avatar.jpg" alt="Hsin-Pei Chen" class="profile-image">
  
  <div class="profile-text">
    <p>I am a graduate student in the <strong>Department of Astronomy at The University of Texas at Austin, working with Dr. Stella Offner</strong>. My work focuses on how stars form and evolve in the Universe.</p>

    <p>I hold a M.S. degree from <strong>Institute of Astronomy, National Tsing Hua University</strong>, Taiwan, where I conducted astrophysical simulations of supernovae. As at UT, <strong>my current project investigates the role of cosmic rays in star-forming clouds using STARFORGE simulations.</strong></p>

    <p>I was born and raised in Kaohsiung, a beautiful city in Southern Taiwan. And so was my dog, Mumu! We moved to Austin together in the summer of 2024.</p>
    
    <div style="margin-top: 30px;">
        <a href="https://github.com/hsinpeichen" style="margin-right: 20px; color: #bf5700; text-decoration: none; font-weight: bold;">GitHub Profile</a>
        <a href="mailto:hpchen@utexas.edu" style="color: #bf5700; text-decoration: none; font-weight: bold;">Email Me</a>
        <a href="https://www.name-coach.com/hsin-pei-chen-74e4f5c1-32b1-4295-a372-db0a15b96573" target="_blank" style="color: #bf5700; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 5px;">
        <span style="font-size: 1.2em;">🔊</span> My Name
        </a>
    </div>
  </div>
</div>
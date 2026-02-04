---
layout: default
title: Home
---

<style>
  header ul, 
  header .github-button, 
  header .view, 
  header .buttons {
    display: none !important;
    visibility: hidden !important;
    height: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  
  header h1 a {
    pointer-events: none !important;
    cursor: default !important;
    color: #ffffff !important; 
    text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
    text-decoration: none !important;
    font-weight: bold;
    font-size: 1.8em !important;
    line-height: 1.2 !important;
    display: block;
  }

  header {
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('photos/website-bg.jpeg') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 60px 20px !important;
    text-align: center;
    width: 100vw !important;
    position: relative !important;
    left: 50% !important;
    transform: translateX(-50%) !important;
    margin: 0 !important;
    box-sizing: border-box;
  }

  header p {
    color: #eeeeee !important;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.8);
    font-size: 1.1em !important;
    margin-top: 10px !important;
    margin-bottom: 0 !important;
    font-weight: 300;
  }

  .header-nav {
    display: flex;
    justify-content: center;
    padding: 30px 0;
    margin-bottom: 30px;
    border-bottom: 1px solid #eee;
  }
  .header-nav a {
    margin: 0 20px;
    text-decoration: none;
    color: #bf5700;
    font-weight: bold;
    font-size: 1.2em;
  }

  .profile-container {
    max-width: 900px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 30px;
  }
  .profile-image {
    width: 280px;
    height: 280px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }
  .profile-text {
    font-size: 1.25em;
    line-height: 1.8;
    color: #333;
    text-align: left;
  }

  .profile-text strong {
    color: #bf5700;
  }

  .contact-links {
    margin-top: 30px;
    display: flex;
    justify-content: center;
    gap: 30px;
  }
  .contact-links a {
    font-size: 1.1em;
    padding: 8px 20px;
    border: 1px solid #bf5700;
    border-radius: 5px;
    transition: 0.3s;
  }
  .contact-links a:hover {
    background-color: #bf5700;
    color: white !important;
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
        <a href="https://www.name-coach.com/hsin-pei-chen-74e4f5c1-32b1-4295-a372-db0a15b96573" target="_blank" style="color: #bf5700; text-decoration: none; font-weight: bold; display: flex; align-items: center; gap: 5px;">
        <span style="font-size: 1.2em;">🔊</span> My Name
        </a>
    </div>
  </div>
</div>
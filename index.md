---
layout: default
title: Home
---

<style>
  /* 1. 頂部區域設定：白底、黑標題、灰副標 */
  header {
    background: #ffffff !important;
    border-bottom: 1px solid #eee;
    padding: 30px 0 !important;
  }
  header h1 a {
    color: #000000 !important; /* 名字黑色 */
    text-decoration: none !important;
    font-weight: bold;
  }
  header p {
    color: #666666 !important; /* 副標題灰色 */
    font-size: 1.1em;
  }

  /* 2. 導覽列樣式 */
  .header-nav {
    text-align: center;
    padding: 20px 0;
    margin-bottom: 20px;
  }
  .header-nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #bf5700; /* 保持 UT 橘作為點綴色 */
    font-weight: 500;
  }
  
  /* 3. 個人簡介佈局 */
  .profile-container {
    display: flex;
    align-items: flex-start;
    gap: 40px;
    flex-wrap: wrap;
  }
  .profile-image {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    object-fit: cover;
    border: 1px solid #eee;
  }
  .profile-text {
    flex: 1;
    min-width: 300px;
    line-height: 1.7;
    color: #333;
  }
</style>

<div class="header-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/cv">CV</a>
  <a href="/outreach">Outreach</a>
</div>

<div class="profile-container">
  <img src="avatar.jpg" alt="Hsin-Pei Chen" class="profile-image">
  
  <div class="profile-text">
    <p>I am a graduate student in the <strong>Department of Astronomy at The University of Texas at Austin</strong>. My work focuses on how stars form and evolve in the Universe.</p>

    <p>I hold a M.S. degree from <strong>Institute of Astronomy, National Tsing Hua University</strong>, Taiwan, where I conducted astrophysical simulations of supernovae. I am <strong>currently a Graduate Research Assistant at UT in Dr. Stella Offner's research group</strong>. My current project <strong>investigates the role of cosmic rays in star-forming clouds using STARFORGE simulations.</strong></p>

    <p>I was born and raised in <strong>Kaohsiung</strong>, a beautiful city in Southern Taiwan. And so was my dog, <strong>Mumu</strong>! We moved to Austin together in the summer of 2024.</p>
    
    <div style="margin-top: 30px;">
        <a href="https://github.com/hsinpeichen" style="margin-right: 20px; color: #bf5700; text-decoration: none; font-weight: bold;">GitHub Profile</a>
        <a href="mailto:hpchen@utexas.edu" style="color: #bf5700; text-decoration: none; font-weight: bold;">Email Me</a>
        <a href="https://www.name-coach.com/hsin-pei-chen-74e4f5c1-32b1-4295-a372-db0a15b96573" target="_blank" style="color: #bf5700; text-decoration: none; font-weight: bold; display: flex; align-items: center; gap: 5px;">
        <span style="font-size: 1.2em;">🔊</span> My Name
        </a>
    </div>
  </div>
</div>
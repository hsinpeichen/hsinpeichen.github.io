---
layout: default
title: Home
---

<style>
  /* 1. 設定頂部橫幅背景為 UT 橘色，並確保文字為白色 */
  header {
    background-color: #bf5700 !important;
    padding: 20px 0;
  }
  header h1 a {
    color: #ffffff !important;
    font-weight: bold;
    text-decoration: none;
  }
  header p {
    color: #f8f8f8 !important;
  }

  /* 2. 導覽列樣式微調 */
  .header-nav {
    text-align: center;
    border-bottom: 1px solid #eee;
    padding-bottom: 15px;
    margin-bottom: 30px;
  }
  .header-nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #bf5700;
    font-weight: 500;
  }
  
  /* 3. 個人簡介區塊佈局 */
  .profile-container {
    display: flex;
    align-items: flex-start;
    gap: 40px;
    margin-top: 20px;
    flex-wrap: wrap;
  }
  .profile-image {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #eee;
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

    <p>I hold a M.S. degree from <strong>Institute of Astronomy, National Tsing Hua University</strong>, Taiwan, where I conducted astrophysical simulations of supernovae. I am <strong>currently a Graduate Research Assistant at UT in Dr. Stella Offner's research group. My current project investigates the role of cosmic rays in star-forming clouds using STARFORGE simulations.</strong></p>

    <p>I was born and raised in <strong>Kaohsiung</strong>, a beautiful city in Southern Taiwan. And so was my dog, <strong>Mumu</strong>! We moved to Austin together in the summer of 2024.</p>
    
    <div style="margin-top: 30px;">
        <a href="https://github.com/hsinpeichen" style="margin-right: 20px; color: #bf5700; text-decoration: none; font-weight: bold;">GitHub Profile</a>
        <a href="mailto:hpchen@utexas.edu" style="color: #bf5700; text-decoration: none; font-weight: bold;">Email Me</a>
    </div>
  </div>
</div>
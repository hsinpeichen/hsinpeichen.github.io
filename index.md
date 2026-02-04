---
layout: default
title: Home
---

<style>
  /* 1. 修正整體容器：強制消除主題的側邊欄留白 */
  .wrapper {
    max-width: 1000px !important; /* 增加一點寬度讓電腦版更大氣 */
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

  /* 2. 修正 Header：確保全寬且文字置中 */
  header {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('photos/website-bg.jpeg') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 80px 0 !important; /* 增加上下間距 */
    text-align: center !important;
    
    /* 強制跳出容器達到全螢幕寬度 */
    width: 100vw !important;
    position: relative !important;
    left: 50% !important;
    transform: translateX(-50%) !important;
    margin: 0 0 40px 0 !important;
    float: none !important;
  }

  /* 隱藏主題原本在左側的物件 */
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
    font-size: 2.8em !important; /* 增大標題 */
    font-weight: bold !important;
    pointer-events: none !important;
  }

  header p {
    color: #eeeeee !important;
    font-size: 1.3em !important;
    margin: 15px 0 0 0 !important;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.8);
  }

  /* 3. 導覽列：確保在正中間 */
  .header-nav {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px 0;
    margin-bottom: 40px;
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

  /* 4. 個人介紹區塊：居中排版 */
  .profile-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 30px;
    width: 100%;
  }

  .profile-image {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid #fff;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }

  .profile-text {
    font-size: 1.2em;
    line-height: 1.8;
    color: #333;
    text-align: left; /* 長文左對齊，但區塊本身居中 */
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
    <p>(test) I am a graduate student in the <strong>Department of Astronomy at The University of Texas at Austin, working with Dr. Stella Offner</strong>. My work focuses on how stars form and evolve in the Universe.</p>

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
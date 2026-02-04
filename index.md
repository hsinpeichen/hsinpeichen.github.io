---
layout: default
title: Home
---

<style>
  /* 讓最上方的標題文字變成白色 (背景是橘色時較清晰) */
  header h1 a { color: #ffffff !important; }
  header p { color: #eeeeee !important; }

  /* 調整頁面主標題（你的名字）為黑色 */
  .main-title {
    color: #000000;
    text-align: center;
    margin-top: 0;
    font-size: 2.2em;
  }

  .header-nav {
    text-align: center;
    border-bottom: 1px solid #eee;
    padding-bottom: 20px;
    margin-bottom: 30px;
  }
  .header-nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #bf5700; /* 導覽連結用 UT 橘 */
    font-weight: 500;
  }
  
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
    line-height: 1.6;
  }
</style>

<div class="header-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/cv">CV</a>
  <a href="/outreach">Outreach</a>
  <h1 class="main-title">Hsin-Pei Chen (陳昕霈)</h1>
</div>

<div class="profile-container">
  <img src="avatar.jpg" alt="Hsin-Pei Chen" class="profile-image">
  
  <div class="profile-text">
    <p>I am a graduate student in the <strong>Department of Astronomy at The University of Texas at Austin</strong>. My work focuses on how stars form and evolve in the Universe.</p>

    <p>I hold a M.S. degree from <strong>Institute of Astronomy, National Tsing Hua University</strong>, Taiwan, where I conducted astrophysical simulations of supernovae. I am currently a Graduate Research Assistant at UT in Dr. Stella Offner's research group. My current project investigates the role of cosmic rays in star-forming clouds using STARFORGE simulations.</p>

    <p>I was born and raised in <strong>Kaohsiung</strong>, a beautiful city in Southern Taiwan. And so was my dog, <strong>Mumu</strong>! We moved to Austin together in the summer of 2024.</p>
    
    <div style="margin-top: 30px;">
        <a href="https://github.com/hsinpeichen" style="margin-right: 20px; color: #333;">GitHub</a>
        <a href="mailto:hpchen@utexas.edu" style="color: #333;">Email</a>
    </div>
  </div>
</div>
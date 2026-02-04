---
layout: default
title: Home
---

<style>
  /* 1. 修正 Header 背景：全寬延伸但限制內容 */
  header {
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('photos/website-bg.jpg') !important;
    background-size: cover !important;
    background-position: center !important;
    padding: 60px 20px !important; /* 增加左右內距 */
    text-align: center;
    
    /* 讓背景圖跳出容器邊界 */
    width: 100vw !important;
    position: relative !important;
    left: 50% !important;
    transform: translateX(-50%) !important;
    margin: 0 !important;
    box-sizing: border-box;
  }
  
  /* 徹底移除頂端 GitHub 按鈕 */
  header ul {
    display: none !important;
  }

  /* 2. 修正標題字體：設定更穩定的尺寸 */
  header h1 {
    margin: 0 auto !important;
    max-width: 800px;
  }

  header h1 a {
    color: #ffffff !important; 
    text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
    text-decoration: none !important;
    font-weight: bold;
    font-size: 1.8em !important; /* 調降字體大小 */
    line-height: 1.2 !important;
    display: block;
  }
  
  header p {
    color: #eeeeee !important;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.8);
    font-size: 1.1em !important; /* 調降副標題字體 */
    margin-top: 10px !important;
    margin-bottom: 0 !important;
    font-weight: 300;
  }

  /* 3. 導覽列與內文 (維持原樣) */
  .header-nav {
    text-align: center;
    padding: 20px 0;
    margin-bottom: 20px;
    border-bottom: 1px solid #eee;
  }
  .header-nav a {
    margin: 0 10px;
    text-decoration: none;
    color: #bf5700;
    font-weight: 500;
    font-size: 0.95em;
  }
  
  .profile-container {
    display: flex;
    align-items: flex-start;
    gap: 40px;
    flex-wrap: wrap;
    margin-top: 20px;
  }
  .profile-image {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
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
  <img src="photos/avatar.jpg" alt="Hsin-Pei Chen" class="profile-image">
  
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
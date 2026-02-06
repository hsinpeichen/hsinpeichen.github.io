---
layout: default
title: CV
---

<style>
  .wrapper footer {
    display: none !important;
    visibility: hidden !important;
    height: 0 !important;
    padding: 0 !important;
    margin: 0 !important;
  }

  .wrapper {
    max-width: 1000px !important;
    margin: 0 auto !important;
    padding: 0 20px !important;
    float: none !important;
    display: block !important;
    min-height: 0 !important;
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

  .cv-section {
    display: flex;
    gap: 40px;
    margin-top: 40px;
    flex-wrap: wrap;
  }
  
  .cv-sidebar {
    flex: 1;
    min-width: 150px;
    font-size: 1.5em;
    font-weight: bold;
    color: #333;
  }
  .cv-content {
    flex: 4;
    min-width: 300px;
  }

  .pdf-container {
    position: relative;
    width: 100%;
    height: 800px;
    border: 1px solid #ddd;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  .pdf-iframe {
    width: 100%;
    height: 100%;
    border: none;
  }

  .download-btn {
    display: block;
    width: fit-content;
    margin-bottom: 20px;
    padding: 10px 20px;
    background-color: #bf5700;
    color: white !important;
    text-decoration: none !important;
    border-radius: 5px;
    font-weight: bold;
  }

  .custom-footer {
    display: block !important;
    width: 100% !important;
    text-align: center !important;
    padding: 40px 0 !important;
    margin-top: 60px !important;
    margin-bottom: 20px !important;
    clear: both !important;
    font-size: 0.85em !important;
    color: #999 !important;
    line-height: 1.8;
    border-top: 1px solid #eee;
  }

  .custom-footer p {
    text-align: center !important;
    margin: 5px 0 !important;
  }

  .custom-footer a {
    color: #777 !important;
    text-decoration: underline;
  }
</style>

<div class="header-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/cv">CV</a>
  <a href="/outreach">Outreach</a>
</div>

<header>
  <h1><a href="/">Hsin-Pei Chen</a></h1>
  <p>PhD Student in Astrophysics at UT Austin</p>
</header>

<div class="cv-section">
  <div class="cv-sidebar">
    CV
  </div>

  <div class="cv-content">
    
    <a href="files/CV_HPC.pdf" class="download-btn" target="_blank">Download Full CV (PDF)</a>

    <div class="pdf-container">
      <iframe 
        src="files/CV_HPC.pdf#toolbar=0" 
        class="pdf-iframe">
      </iframe>
    </div>
  </div>
</div>

<div class="custom-footer">
  <p>© 2026 Hsin-Pei Chen | Last updated: {{ site.time | date: "%B %Y" }}</p>
  
  <p class="footer-contact">
    <a href="mailto:hpchen@utexas.edu">Email</a> | 
    <a href="https://github.com/hsinpeichen" target="_blank">GitHub</a> | 
    <a href="https://scixplorer.org/public-libraries/7K4rh0uVRXaVBYfpganPeQ" target="_blank">Publications</a>
  </p>

  <p style="font-size: 0.9em;">
    All content is licensed under <a href="https://creativecommons.org/licenses/by/4.0/" target="_blank">CC BY 4.0</a> unless otherwise noted.
  </p>

  <p style="font-size: 0.8em; margin-top: 15px; color: #bbb;">
    Hosted on GitHub Pages — Theme by <a href="https://github.com/orderedlist" target="_blank" style="color: #bbb;">orderedlist</a>
  </p>
</div>

<a href="#" class="back-to-top" title="Back to Top">↑</a>
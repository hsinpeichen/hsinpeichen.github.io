---
layout: default
title: CV
---

<style>
  .wrapper {
    max-width: 1000px !important;
    margin: 0 auto !important;
    padding: 0 20px !important;
    float: none !important;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
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
    position: absolute;
    top: 10px;
    left: 0;
    right: 0;
    z-index: 10;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 10px 0;
    margin-bottom: 20px;
    border-bottom: none;
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

  footer {
  position: relative !important;
  bottom: auto !important;
  left: auto !important;
  width: 100% !important;
  text-align: center !important;
  padding: 40px 0 !important;
  margin-top: 50px !important;
  clear: both !important;
  }
</style>

<div class="header-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/cv">CV</a>
  <a href="/outreach">Outreach</a>
</div>

<div class="cv-section">
  <div class="cv-sidebar">
    CV
  </div>

  <div class="cv-content">
    
    <a href="files/CV_HPC_02042026.pdf" class="download-btn" target="_blank">Download Full CV (PDF)</a>

    <div class="pdf-container">
      <iframe 
        src="files/CV_HPC_02042026.pdf#toolbar=0" 
        class="pdf-iframe">
      </iframe>
    </div>
    
  </div>
</div>
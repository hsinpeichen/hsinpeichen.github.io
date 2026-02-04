---
layout: default
title: CV
---

<style>
  /* 頂部導覽樣式 (保持全站一致) */
  .header-nav {
    text-align: center;
    padding: 20px 0;
    margin-bottom: 20px;
    border-bottom: 1px solid #eee;
  }
  .header-nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #bf5700;
    font-weight: 500;
  }

  /* CV 頁面佈局 */
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

  /* PDF 嵌入容器樣式 */
  .pdf-container {
    position: relative;
    width: 100%;
    height: 800px; /* 您可以調整高度以符合您的 CV 長度 */
    border: 1px solid #ddd;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  .pdf-iframe {
    width: 100%;
    height: 100%;
    border: none;
  }
  
  /* 提供行動裝置下載的按鈕 (手機有時無法直接顯示內嵌 PDF) */
  .download-btn {
    display: block;
    width: fit-content;
    margin: 20px 0;
    padding: 10px 20px;
    background-color: #bf5700;
    color: white !important;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
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
---
layout: default
title: CV
---

<style>
/* --- 1. 頂部全寬 Header 樣式 (與首頁同步) --- /
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

/ 徹底隱藏 GitHub 按鈕與連結 /
header ul, header .github-button, header .view, header .buttons {
display: none !important;
visibility: hidden !important;
height: 0 !important;
}

/ 標題與副標題樣式 /
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

header p {
color: #eeeeee !important;
text-shadow: 1px 1px 3px rgba(0,0,0,0.8);
font-size: 1.1em !important;
margin-top: 10px !important;
font-weight: 300;
}

/ --- 2. 導覽列與 CV 內容樣式 --- /
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

/ CV 頁面佈局 /
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

/ PDF 嵌入容器樣式 /
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

/ 提供行動裝置下載的按鈕 */
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
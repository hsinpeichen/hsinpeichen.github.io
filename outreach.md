---
layout: default
title: Outreach
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

  .outreach-section {
    display: flex;
    gap: 40px;
    margin-top: 40px;
    flex-wrap: wrap;
  }

  .outreach-sidebar {
    flex: 1;
    min-width: 150px;
    font-size: 1.5em;
    font-weight: bold;
    color: #333;
  }

  .outreach-content {
    flex: 4;
    min-width: 300px;
  }

  .outreach-content p {
    text-align: justify !important;
    text-justify: inter-word;
    hyphens: auto;
  }

  .image-gallery {
    display: flex;
    flex-direction: row;
    gap: 15px;
    margin: 20px 0;
  }
  
  .gallery-item {
    flex: 1;
    max-width: calc(33.33% - 10px);
  }
  
  .gallery-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
    border: 1px solid #ddd;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }

  .blog-image {
    width: 100%;
    max-width: 500px;
    height: auto;
    display: block;
    margin: 20px auto;
    border-radius: 4px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
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
    .image-gallery {
      flex-direction: column !important;
    }
    .gallery-item {
      max-width: 100%;
    }
  }

  .custom-footer {
    display: block !important;
    width: 100% !important;
    text-align: center !important;
    padding: 40px 0 !important;
    margin-top: 40px !important;
    margin-bottom: 20px !important;
    clear: both !important;
    font-size: 0.85em !important;
    color: #999 !important;
    line-height: 1.8;
    border-top: 1px solid #eee;
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

<div class="outreach-section">
  <div class="outreach-sidebar">
    Outreach
  </div>

  <div class="outreach-content">
    <p>In addition to my academic pursuits, I have dedicated time to amateur astronomy clubs and activities in Taiwan, with the aim of sharing the wonders of the Universe with college students and the broader public.</p>
    
    <hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

    <h3>Astronomy Club Activities (2017-2020)</h3>

    <img src="photos/outreach-nknuastrclub.webp" loading="lazy" alt="NKNU astro club" class="blog-image">

    <p>
      I initiated the Astronomy Club at NKNU during my undergraduate years, recruited instructors and instrumental aids, and designed courses for astronomy and observation techniques. I also led the teaching segment at the NTHU StarKids Astronomy Camp, designed for high school students who are passionate about astronomy.
    </p>

    <hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

    <h3>Astronomy Club Union of Universities in Taiwan (2020-2024)</h3>

    <img src="photos/outreach-starkids.webp" loading="lazy" alt="Starkids Camp" class="blog-image">

    <p>
      During 2020-2022, I served as one of the directors at the Astronomy Club Union of Universities in Taiwan (ACUUT), an organization dedicated to supporting university astronomy clubs in Taiwan. Especially, during the solar eclipse in June 2020, I coordinated the national live-streaming program of ACUUT in collaboration with the Central Weather Bureau in Taiwan, ultimately attracting around 290,000 viewers. Through these experiences, I have acquired valuable skills in project organization, team leadership, and effective collaboration.
    </p>

    <hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

    <h3>Astronomy Club Union of Universities in Taiwan (2020-2024)</h3>

    <div class="image-gallery">
      <div class="gallery-item">
        <img src="photos/outreach-acuut1.webp" loading="lazy" alt="ACUUT Event 1">
      </div>
      <div class="gallery-item">
        <img src="photos/outreach-acuut2.webp" loading="lazy" alt="ACUUT Event 2">
      </div>
      <div class="gallery-item">
        <img src="photos/outreach-acuut3.webp" loading="lazy" alt="ACUUT Event 3">
      </div>
    </div>

    <p>
      During 2020-2022, I served as one of the directors at the Astronomy Club Union of Universities in Taiwan (ACUUT), an organization dedicated to supporting university astronomy clubs in Taiwan. Especially, during the solar eclipse in June 2020, I coordinated the national live-streaming program of ACUUT in collaboration with the Central Weather Bureau in Taiwan, ultimately attracting around 290,000 viewers. Through these experiences, I have acquired valuable skills in project organization, team leadership, and effective collaboration.
    </p>

    <hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

    <h3>Astronomy for the Public in Austin (2024-Current)</h3>

    <img src="photos/outreach-aotatx.webp" loading="lazy" alt="AoT in Austin" class="blog-image">

    <p>
      As an international student who left my home country at the age of 26, I am currently learning to engage with the local community in Austin, TX by regularly attending Astronomy on Tap ATX events. My goal is to give at least one public talk before I graduate in 2029. Hopefully more!
    </p>
  </div>
</div>

<div class="custom-footer">
  <p>© 2026 Hsin-Pei Chen | Last updated: {{ site.time | date: "%B %d, %Y" }}</p>
  
  <p class="footer-contact">
    <a href="mailto:hpchen@utexas.edu">Email</a> | 
    <a href="https://github.com/hsinpeichen" target="_blank">GitHub</a> | 
    <a href="https://scixplorer.org/public-libraries/7K4rh0uVRXaVBYfpganPeQ" target="_blank">Publications</a>
  </p>

  <p style="font-size: 0.9em;">
    All content is licensed under <a href="https://creativecommons.org/licenses/by/4.0/" target="_blank">CC BY 4.0</a> unless otherwise noted.
  </p>
</div>

<a href="#" class="back-to-top" title="Back to Top">↑</a>
---
layout: default
title: Research
---

<style>
  /* 頂部導覽與標題樣式 (與首頁保持一致) */
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

  /* 研究專案的佈局 */
  .research-section {
    display: flex;
    gap: 40px;
    margin-top: 40px;
    flex-wrap: wrap;
  }
  .research-sidebar {
    flex: 1;
    min-width: 200px;
    font-size: 1.5em;
    font-weight: bold;
    color: #333;
  }
  .research-content {
    flex: 3;
    min-width: 300px;
  }
  .project-image {
    width: 100%;
    max-width: 600px;
    height: auto;
    margin-bottom: 15px;
    border-radius: 4px;
  }
  .image-credit {
    font-size: 0.85em;
    color: #666;
    font-style: italic;
    margin-bottom: 20px;
  }
  /* 醒目的按鈕樣式 */
  .paper-btn {
    display: inline-block;
    margin: 15px 0;
    padding: 10px 20px;
    background-color: #bf5700; /* UT 橘 */
    color: white !important;
    text-decoration: none !important;
    border-radius: 5px;
    font-weight: bold;
    font-size: 0.9em;
    transition: background-color 0.3s;
  }
  .paper-btn:hover {
    background-color: #9d4700; /* 滑鼠游標懸停時變深 */
  }
</style>

<div class="header-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/cv">CV</a>
  <a href="/outreach">Outreach</a>
</div>

<div class="research-section">
  <div class="research-sidebar">
    Research Overview
  </div>

  <div class="research-content">
    
    <h3>Master's Thesis: Exploring the Observability of Surviving Companions of Stripped-envelope Supernovae</h3>

    <img src="photos/research-sn.jpg" alt="Supernova Research" class="project-image">
    <p class="image-credit">Image credit: NASA, ESA, Leah Hustak (STScI)</p>

    <p>
      In 2020, I began my Master’s studies at NTHU, under the guidance of Dr. Kuo-Chuan Pan. My Master's thesis focused on simulating the surviving companions of stripped-envelope supernovae (SNe). Through hydrodynamics simulations of the SN impact on the companion and the evolutionary paths of the surviving companion, we uncovered that the surviving companion becomes temporarily brighter and redder, enhancing the chances of detection. By applying observational constraints from SN 2020oi, we further predicted that the possible surviving companion could be observed by Hubble Space Telescope (HST) and James Webb Space Telescope (JWST) 10 years after the explosion. This project was published in the Astrophysical Journal (Chen, Rau, & Pan, 2023) and featured in the <a href="https://aasnova.org/2023/07/19/wanted-surviving-companions-of-stripped-envelope-supernovae/" style="color: #bf5700; font-weight: bold;">AASNova</a> website in July 2023.
    </p>

    <a href="https://iopscience.iop.org/article/10.3847/1538-4357/acc9af" class="paper-btn" target="_blank"> View Paper
    </a>

    <hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

    <h3>Research Assistant Project at NCTS: Type Ia Supernova Progenitors and Surviving Companions within the Symbiotic Channel</h3>

    <div style="max-width: 600px; margin: 30px 0; border: 1px solid #ddd; padding: 10px; background-color: #f9f9f9;">
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
        <iframe 
        src="https://www.youtube.com/embed/QSmuqBiAQ4c" 
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
        </iframe>
    </div>
    <p style="margin: 10px 0 0 0; font-size: 0.9em; font-style: italic; color: #333; border-top: 1px solid #eee; padding-top: 10px;">
        NASA video (1:20) explaining the single-degenerate scenario of Type Ia supernovae.
    </p>
    </div>

    <p>
      After graduating in February 2023, I continued working as a Research Assistant at the National Center for Theoretical Science in Taiwan under the mentorship of Professor Pan. I embarked on my next project, exploring the systematic study of surviving companions in the symbiotic channel of type Ia supernovae. Our research revealed that the evolved companions could maintain their luminosity from before the SN explosion or transform into hot, bright dwarves. We have submitted the paper to ApJ, and it is currently under revision. Through these projects of simulations of supernovae, I have received solid training in conducting simulations using stellar evolution code MESA and hydrodynamics simulation code FLASH, and also have enhanced my abilities in problem solving, literature review, and scientific writing.
    </p>

    <a href="https://iopscience.iop.org/article/10.3847/1538-4357/adeb71" class="paper-btn" target="_blank"> View Paper
    </a>

    <hr style="margin: 40px 0; border: 0; border-top: 1px solid #eee;">

    <h3>Current Project at UT: Synthetic Observations of Cosmic Ray Tracers with STARFORGE Simulations</h3>

    <img src="photos/research-starforge.jpg" alt="A snapshot of STARFORGE simulation." class="project-image">
    <p class="image-credit">Image credit: Northwestern University/UT Austin</p>

    <p>
      Currently at UT Austin, as a member of Dr. Stella Offner's research group, my first two years of graduate study are dedicated to investigating the effects of cosmic rays in star-forming regions. Cosmic rays are a significant factor influencing various aspects of star formation, including chemical abundances, gas temperature, and star formation efficiencies. In this project, I will use numerical simulation data from STARFORGE (Fitz Axen et al. 2024) to examine how cosmic rays affect chemistry of star-forming clouds. My goal is to produce synthetic observations of cosmic ray tracers and to evaluate the accuracy of the CRIRs derived in molecular cloud observations.
    </p>

  </div>
</div>
---
layout: about
title: about
permalink: /
subtitle: >-
  Postdoctoral researcher at <a href='https://portal.research.lu.se/en/persons/leonardo-oliveira/'>Lund University</a> and <a href='https://www.maxiv.lu.se/beamlines-accelerators/beamlines/nanomax/staff/'>MAX IV Laboratory, NanoMAX beamline</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Synchrotron Radiation Research</p>
    <p>Department of Physics, Lund University</p>
    <p>NanoMAX beamline</p>
    <p>MAX IV Synchrotron</p>
    <p>Lund, Sweden</p>

selected_papers: false # shown at the end of the text below instead, with a capitalised heading
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # turn on and add files to _news/ to show a news list

latest_posts:
  enabled: false
---

I am an X-ray diffraction and imaging scientist linking **structure, processing and properties** in advanced materials.

My core methods are strain and tilt mapping by **dark-field X-ray microscopy (DFXM)** and **scanning nano-diffraction (nano-XRD)**, together with **Rietveld and Le Bail refinement**, **texture analysis** and **in situ diffraction**. As a postdoc at the NanoMAX beamline at MAX IV, I run in situ experiments with users, assess their feasibility, and develop Python tools for processing data during beamtime.

My research focuses on how local structure, strain and residual stress govern functionality in ferroelectrics, antiferroelectrics and other electromechanical materials, from ceramics to thin films: lead-free dielectric ceramics for energy storage, Hf<sub>0.5</sub>Zr<sub>0.5</sub>O<sub>2</sub> device stacks and InGaN nanoLEDs.

I did my PhD in Physics at the Technical University of Denmark (DTU), where I [quantified heterogeneity in lead-free dielectric ceramics for energy storage using synchrotron X-rays](https://orbit.dtu.dk/en/publications/quantifying-heterogeneity-in-lead-free-dielectric-ceramics-for-en/).

## Highlights

- **[ESRF Highlight of the Year 2024](https://www.esrf.fr/files/live/sites/www/files/ExternalFiles/Communication/Highlights/2024/index.html#/page/70)**: my residual-stress work on antiferroelectric NaNbO<sub>3</sub> was selected as the flagship result of the ID06-HXM beamline.
- **Winner, Machine Learning for Microscopy Hackathon 2** (2026), for an ML denoising workflow for diffraction microscopy data.
- **Editor's HOT paper** in _J. Mater. Chem. C_ (2023) and a **journal cover** in _CrystEngComm_ (2019).
- 17 peer-reviewed papers, h-index 10, reviewer for _Journal of Applied Crystallography_ and _Applied Physics Letters_.

## In the media

<style>
  .link-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1rem; margin: 1rem 0 2rem; }
  .link-card { display: flex; flex-direction: column; border: 1px solid var(--global-divider-color); border-radius: 8px; overflow: hidden; color: var(--global-text-color) !important; background: var(--global-card-bg-color); text-decoration: none !important; transition: border-color 0.2s; }
  .link-card:hover { border-color: var(--global-theme-color); }
  .link-card img { width: 100%; height: 160px; object-fit: cover; display: block; margin: 0; }
  .link-card img.lc-missing { visibility: hidden; background: var(--global-divider-color); }
  .link-card .lc-body { padding: 0.75rem 1rem 1rem; }
  .link-card .lc-source { font-size: 0.8rem; color: var(--global-text-color-light); margin-bottom: 0.25rem; }
  .link-card .lc-title { font-weight: 600; line-height: 1.3; margin-bottom: 0.4rem; }
  .link-card .lc-desc { font-size: 0.85rem; color: var(--global-text-color-light); line-height: 1.4; }
</style>

<div class="link-cards">
<a class="link-card" href="https://www.maxiv.lu.se/article/beamline-collaborations-through-max-ivs-shared-postdocs-leonardo-oliveira/" target="_blank" rel="noopener">
<img src="https://www.maxiv.lu.se/wp-content/uploads/2026/02/Adobe-Express-file.jpg" alt="Leonardo Oliveira at the NanoMAX beamline" loading="lazy" style="object-position: center 30%;" onerror="this.classList.add('lc-missing')">
<div class="lc-body">
<div class="lc-source">MAX IV · Interview · Feb 2026</div>
<div class="lc-title">Beamline collaborations through MAX IV's shared postdocs: Leonardo Oliveira</div>
<div class="lc-desc">How I divide my time between a university research group at Lund University and the NanoMAX beamline.</div>
</div>
</a>
<a class="link-card" href="https://www.esrf.fr/files/live/sites/www/files/ExternalFiles/Communication/Highlights/2024/index.html#/page/70" target="_blank" rel="noopener">
<img src="https://toolbox.fluidbook.com/services/socialimage/nL0NkJx7/1738163273" alt="Cover of ESRF Highlights 2024" loading="lazy" onerror="this.classList.add('lc-missing')">
<div class="lc-body">
<div class="lc-source">ESRF · Highlights 2024 · p. 70</div>
<div class="lc-title">ESRF Highlights 2024: residual stress in antiferroelectric NaNbO<sub>3</sub></div>
<div class="lc-desc">My dark-field X-ray microscopy work on NaNbO<sub>3</sub> ceramics, selected as the highlight from the ID06-HXM beamline.</div>
</div>
</a>
</div>

<h2 class="mt-4"><a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a></h2>

<div class="selected-publications">
{% include selected_papers.liquid %}
</div>

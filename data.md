---
title: Data
permalink: /data/
feature_text: |
  <p style="color: white; font-size: clamp(9px, 2vw, 12px); text-shadow: 2px 2px 4px black;">Facing climate change challenges with scientific knowledge and practical solutions</p>
feature_image: "/assets/atmospheric_river_satellite.png"
excerpt: "Open data from the Climate and Weather Extremes Lab, including the Northern Hemisphere Atmospheric River Database."
---

<div class="lab-page">

<h2 class="section-title">Northern Hemisphere Atmospheric River Database</h2>

<p>We openly share a long-term, high-resolution catalog of atmospheric rivers (ARs) over the Northern Hemisphere, identified with the <strong>Pan&ndash;Lu algorithm</strong>. The database provides <strong>6-hourly</strong> AR fields on a <strong>1&deg;&times;1&deg;</strong> grid spanning <strong>1950&ndash;2022</strong>. Each time step is stored as a binary (0/1) field in NetCDF, where <strong>1</strong> indicates an AR is present at that grid cell and <strong>0</strong> indicates absence. This format makes it straightforward to compute AR frequency, long-term trends, landfall statistics, and composites. The database was released together with our <em>npj Climate and Atmospheric Science</em> (2025) paper on contrasting historical AR trends across the Northern Hemisphere.</p>

<ul class="data-specs">
  <li><strong>Coverage:</strong> Northern Hemisphere</li>
  <li><strong>Period:</strong> 1950&ndash;2022</li>
  <li><strong>Spatial resolution:</strong> 1&deg; &times; 1&deg;</li>
  <li><strong>Temporal resolution:</strong> 6-hourly</li>
  <li><strong>Format:</strong> NetCDF, binary AR mask (1 = AR present, 0 = absent)</li>
  <li><strong>Method:</strong> Pan&ndash;Lu atmospheric river identification algorithm</li>
</ul>

<p>
  <a class="btn" href="https://github.com/panmengxin/AR_database" target="_blank">Download on GitHub</a>
  <a class="btn btn--ghost" href="https://doi.org/10.1038/s41612-025-01191-w" target="_blank">Read the paper</a>
</p>

<h2 class="section-title">How to cite</h2>

<p>If you use this database, please cite:</p>

<p>Pan, M., Hu, S., Zaitchik, B.F. &amp; Pan, W.K. (2025). <em>Contrasting historical trends of atmospheric rivers in the Northern Hemisphere.</em> npj Climate and Atmospheric Science, 8, 307. <a href="https://doi.org/10.1038/s41612-025-01191-w" target="_blank">https://doi.org/10.1038/s41612-025-01191-w</a></p>

<h2 class="section-title">Related references</h2>

<ul class="publication-list">
  <li><strong>Pan, M.</strong> &amp; Lu, M. (2019). <em>A novel atmospheric river identification algorithm.</em> Water Resources Research, 55, 6069&ndash;6087. <a href="https://doi.org/10.1029/2018WR024407" target="_blank">[Link]</a></li>
  <li><strong>Pan, M.</strong> &amp; Lu, M. (2020). <em>East Asia atmospheric river catalog: annual cycle, transition mechanism, and precipitation.</em> Geophysical Research Letters, 47(15), e2020GL089477. <a href="https://doi.org/10.1029/2020GL089477" target="_blank">[Link]</a></li>
  <li><strong>Pan, M.</strong>, Lu, M. &amp; Lall, U. (2024). <em>Diversity of cross-Pacific atmospheric river main routes.</em> Communications Earth &amp; Environment, 5, 378. <a href="https://doi.org/10.1038/s43247-024-01552-y" target="_blank">[Link]</a></li>
</ul>

</div>

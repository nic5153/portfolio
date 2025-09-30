---
layout: page
title: "Research"
permalink: /research/
---

# Research

# Mysterious Modulations

Cataclysmic Variable (CV) systems exhibit complex accretion phenomena, including dramatic outbursts and changes in disk dynamics. **AT 2019muu** is a CV superoutburst located at **RA 19:27:29.810** and **DEC +33:03:05.22** that has been observed by the *Transiting Exoplanet Survey Satellite (TESS)*.  

This system exhibits a strong **beat frequency** visible within its light curve, with periodogram results indicating two frequencies at **4.97** and **5.48 cycles per day**.  

Two nearby targets were identified as potential blending sources; one is likely a **δ-Scuti pulsator** that undergoes a strong modulation. Further analysis is underway to confirm the nature of this blending.

# What is a CV?

Cataclysmic variable (CV) systems are close binary star systems where a **white dwarf** accretes material from a companion star. As the material from the companion star is accreted, it flows toward the white dwarf, forming an **accretion disk** of superheated gas around it.  

The intense gravitational interactions and heating within the disk cause it to brighten significantly. When the accretion rate surpasses a critical threshold, it can lead to dramatic **outbursts**, a characteristic feature of dwarf novae (a subclass of CVs). These outbursts occur due to **thermal instabilities** in the disk.  

The orbital periods of CV systems are typically short,  often ranging from a few hours to less than a day due to the compact nature of the binary. Variations like **superhumps**, which are created by the precession of the accretion disk as it and the white dwarf orbits the donor star, can provide insights into the system’s dynamics.

# Methods

<div style="margin:1rem 0;">
  <iframe src="{{ '/files/light_curve_AT2019muu.html' | relative_url }}" 
          width="100%" height="500" style="border:0;">
  </iframe>
</div>

Our investigation of AT 2019muu began not at the telescope, but with data from the **Transiting Exoplanet Survey Satellite (TESS)**. Our original task was to organize and classify light curves in search of superoutbursting cataclysmic variables. 

During this process, the light curve of AT 2019muu was flagged due to the presence of a **significant beat frequency** clearly visible in the data. To quantify this variability, we performed Fourier analysis, producing a **Lomb–Scargle periodogram** that revealed two distinct peaks at **4.97** and **5.48 cycles per day**.  

These periods were further validated by generating **phase-folded light curves**, which confirmed the detected signals.

# What is a beat frequency?

When two signals of similar frequencies interfere with each other, a resulting pattern of constructive and destructive interference is created. Over certain timescales, these patterns appear in a "beating" visual, shown in the plot below.

<div style="margin:1rem 0;">
  <iframe src="{{ '/files/optimized_animated_beat_frequency_visualization.html' | relative_url }}" 
          width="100%" height="500" style="border:0;">
  </iframe>
</div>


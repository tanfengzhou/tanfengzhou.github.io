---
title: "Research"
permalink: /research/
author_profile: true
---

## Research themes

<h3 id="marine-geophysics" style="padding-top:110px; margin-top:-110px;">
  1) Marine geophysics
</h3>

**Overview:**  
I investigate the physical controls that govern segmentation and earthquake behavior at oceanic transform faults, with a focus on the Gofar transform fault on the East Pacific Rise.

My research on westernmost Gofar (G3) shows that earthquake faulting styles vary systematically between rupture zones and creeping barriers. These variations indicate that the barriers are mechanically weak, likely reflecting elevated pore-fluid pressure. My work on easternmost Gofar (G1) investigates how fault-zone structure and fluid conditions jointly modulate along-strike segmentation.

Together, these studies connect detailed observations of small earthquakes to the physical conditions that allow some segments to host recurring large earthquakes while others accommodate creep and inhibit rupture propagation.

<figure>
  <img src="/images/projects/marine-geophysics/gofarG3focal.png"
       alt="AI workflow for earthquake detection and source characterization"
       style="max-width:100%; height:auto;">
  <figcaption><em>Figure 1.</em> Focal mechanisms on Gofar G3 branch. Non-strike-slip events are common on the oceanic transform fault, while certain faulting types prefer different segments. Kilometer scale normal faulting structures perpendicular to the transform fault are identified. Stress inversion shows the maximum and minimum stress are horizontal and ~45 degrees from the transform fault.</figcaption>
</figure>

**Selected publications:**  
- **Tan, F.**, Fan, W., Shearer, P. M., Behn, M. D., & McGuire, J. J. (2026). *Focal mechanism variations reveal mechanical controls on segmentation at oceanic transform faults.* **Nature Communications**, 17, 9836.
  [Article](https://www.nature.com/articles/s41467-026-76407-5) ·
  [PDF](https://www.nature.com/articles/s41467-026-76407-5.pdf)
- **Tan, F.**, Fan, W., Shearer, P. M., McGuire, J. J., Behn, M. D., Warren, J. M., Liu, Y., Collins, J. A., & Boettcher, M. S. *Structure and fluid conditions modulate along-strike segmentation of the easternmost Gofar oceanic transform fault.* Under review at **Journal of Geophysical Research: Solid Earth**.

**Selected presentations:**
- **<u>Tan, F.</u>**, Fan, W., Shearer, P., McGuire, J., Behn, M., Warren, J., Liu, Y., Collins, J., & Boettcher, M. (2026). *Fault-zone structure and fluid conditions associated with along-strike segmentation at the Gofar transform fault, East Pacific Rise.* American Geophysical Union (**AGU**) Fall Meeting, **oral presentation** (T51A-05).
  [Abstract](https://studio.m-anage.com/agu/agu26/meetingapp.cgi/Paper/2077998)

---

<h3 id="ai-and-seismological-methods" style="padding-top:110px; margin-top:-110px;">
  2) AI and seismological methods
</h3>

**Overview:**  
I develop modern seismological and AI-based methods to study seismic signals. One of the key contributions is the Source Untangler Guided by Artificial intelligence image Recognition (SUGAR). SUGAR introduces a computer-vision framing of seismic source detection: it turns the detection/location into a 3-D image segmentation problem, rather than relying only on traditional pick-and-associate workflows. By integrating waveform stacking and 3-D computer vision, SUGAR is robust when events overlap strongly in space and time. In synthetic and real-data tests, the workflow is reported to characterize intense, complex sequences in near real time, outperforming both commonly used AI/non-AI approaches and skilled analyst workflows in these challenging scenarios. 

<figure>
  <img src="/images/projects/ai-seismology/SUGAR-example.jpg"
       alt="AI workflow for earthquake detection and source characterization"
       style="max-width:90%; height:auto;">
  <figcaption><em>Figure 2.</em> Example of SUGAR detections. Top: SUGAR detects and correctly locates 7 earthquakes out of 8 within the one-minute seismogram, while an analyst only identified the biggest one. Bottom: The computer vision model in SUGAR identifies 3 almost concurrent earthquakes (right) from the brightness video obtained by waveform stacking (left).</figcaption>
</figure>

**Selected publications:**  
- **Tan, F.**, Kao, H., Yi, K. M., Nissen, E., Goerzen, C., Hutchinson, J., Gao, D., & Farahbod, A. (2024).
  *Next generation source detection by computer vision: untangling the complexity of the 2016 Kaikōura earthquake sequence.*
  **Journal of Geophysical Research: Solid Earth**, 129, e2024JB028735.
  [Article](https://doi.org/10.1029/2024JB028735) ·
  [PDF](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2024JB028735) ·
  [Code](https://github.com/tanfengzhou/SUGAR_kaikoura)
- **Tan, F.**, Kao, H., Nissen, E., & Eaton, D. (2019). *Seismicity-Scanning based on Navigated Automatic Phase-picking.* **Journal of Geophysical Research: Solid Earth**, 124, 3802–3818.
  [Article](https://doi.org/10.1029/2018JB017050) ·
  [PDF](https://web.uvic.ca/~enissen/papers/Tan-etal-2019-JGR.pdf)

**Selected presentations:**
- **<u>Tan, F.</u>**, Kao, H., Yi, K. M., Goerzen, C., Hutchinson, J., Gao, D., Farahbod, A., & Nissen, E. (2022). *Source Untangler Guided by Artificial Intelligence Image Recognition (SUGAR).* **AGU** Fall Meeting, **oral presentation** (S52A-03).

---

<h3 id="major-earthquakes" style="padding-top:110px; margin-top:-110px;">
  3) Major earthquakes
</h3>

**Overview:**  
I use seismology and multidisciplinary collaborations to study major earthquakes worldwide, with a focus on earthquake physics. Recent studies include the 2025 Mw 8.8 Kamchatka earthquake and the 2025 Mw 7.8 Myanmar earthquake.

The study of the 2025 Kamchatka earthquake reveals that its rupture initially progressed slowly within the rough Kruzenstern Fracture Zone and nearly stopped after approximately 50 seconds. It then propagated into a smoother neighboring segment, where much larger slip occurred. This work shows how a rough fracture zone can provide a gateway to a giant earthquake when connected to a neighboring segment sufficiently stressed to sustain rupture. These findings highlight the importance of interactions between heterogeneous fault segments in assessing earthquake and tsunami hazards.

<!-- Add images under /images/projects/environmental-seismology/ -->
<!-- Example:
<img src="/images/projects/environmental-seismology/greenland.png" alt="Study area / Greenland" width="750">
<br>
<img src="/images/projects/environmental-seismology/detections.png" alt="Detections figure" width="750">
-->

**Selected publications:**  
- Luo, H.<sup>†</sup>, **Tan, F.**<sup>†</sup>, Ma, Z., Chen, K., Zhang, J., Wang, X., Xu, S., Carvajal, M., Xu, H., Yun, S., & Chen, L. *Rough fracture zone as a gateway to the 2025 Mw 8.8 Kamchatka earthquake.* **Science**. In press. †Co-first authors (equal contribution).
- Ulrich, T., Zou, X., Marchandon, M., Schliwa, N., **Tan, F.**, Gabriel, A., Fan, W., Shearer, P., Thant, M., Tin, T. Z. H., Lindsey, E. O., & Fialko, Y. (2026). *On predictability of slip, rupture geometry, and speed of the 2025 M7.8 Mandalay, Myanmar, earthquake.* **Nature Communications**, 17, 10173.
  [Article](https://www.nature.com/articles/s41467-026-77203-x) ·
  [PDF](https://www.nature.com/articles/s41467-026-77203-x.pdf)

**Selected presentations:**
- Luo, H., **<u>Tan, F.</u>**, Ma, Z., Chen, K., Zhang, J., Wang, X., Xu, S., Carvajal, M., Xu, H., Yun, S., & Chen, L. (2026). *Rough fracture zone fostered the occurrence of the 2025 Mw 8.8 Kamchatka earthquake.* **AGU** Fall Meeting, **oral presentation** (T11A-08).
  [Abstract](https://studio.m-anage.com/agu/agu26/meetingapp.cgi/Paper/2073828)

---

<h3 id="environmental-seismology" style="padding-top:110px; margin-top:-110px;">
  4) Environmental seismology
</h3>

**Overview:**  
I am interested in how seismic observations can be used to study environmental processes, including cryosphere-related signals and other non-tectonic sources. This theme focuses on extracting weak environmental seismic signals from continuous data, combining detection, location and machine learning workflows to identify events and connect them to environmental drivers. The broader goal is to use seismology as a continuous tool for monitoring environmental phenomena. 

<!-- Add images under /images/projects/environmental-seismology/ -->
<!-- Example:
<img src="/images/projects/environmental-seismology/greenland.png" alt="Study area / Greenland" width="750">
<br>
<img src="/images/projects/environmental-seismology/detections.png" alt="Detections figure" width="750">
-->

**Selected publications:**  
- **Tan, F.**, Fan, W., & Shearer, P. M. *Greenland glacial earthquakes from 2010 to 2021.* Under review at **Geophysical Research Letters**.

**Selected presentations:**
- **<u>Tan, F.</u>**, Fan, W., & Shearer, P. (2026). *Searching for glacier-related seismic events in Greenland with waveform similarity and machine learning.* Seismological Society of America (**SSA**) Annual Meeting, **oral presentation**.
- **<u>Tan, F.</u>**, Fan, W., & Shearer, P. (2026). *Greenland glacial earthquake activity from 2010 to 2021 revealed by AI-assisted detection.* **AGU** Fall Meeting, poster.

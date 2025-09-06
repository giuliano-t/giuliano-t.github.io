# Research in Structural Dynamics

## Discovering Hidden Dynamic Couplings in Aero-Engines

My PhD at **Imperial College London (Rolls-Royce UTC)** expanded the current knowledge on hidden vibration interactions in aero-engine rotors, which are likely to affect newer generation designs.  
By combining advanced modelling with a custom-built test rig, I demonstrated that the long-standing assumption of independent shaft, disc, and blade dynamics breaks down under modern architectures.  
These findings imply that **new design requirements** are needed to safeguard the structural integrity and reliability of future ultra-efficient engines.

---

## Research Summary

Next-generation aero-engines rely on shorter, stiffer shafts carrying longer, more flexible blades.  These designs improve aerodynamic efficiency and reduce noise — but they also create **hidden vibration risks**.  

This raised a key question: could vibrations in different parts of the rotor, once thought independent, actually interact in unexpected ways?

In my research I uncovered and validated entirely new families of coupled shaft-disc-blades modes. Using advanced finite element models, I showed that asymmetric bearing supports can cause shaft bending and axial motions to merge into new “hybrid” modes. Extending the analysis to bladed discs showed that torsional, lateral, and axial vibrations can also combine into unique, fully coupled behaviours.

<div style="text-align: center; margin: 2em 0;">
  <video width="600" controls>
    <source src="/assets/videos/IMAC_Mode_6_NR.mp4" type="video/mp4">
    Your browser can’t play this video. <a href="/assets/videos/IMAC_Mode_6_NR.mp4">Download it here.</a>
  </video>
  <p style="font-size: 0.9em; color: #555; margin-top: 0.5em;">
    <strong>Figure 1.</strong> Shaft Bending to Disc 0ND Coupled Mode.
  </p>
</div>

<div style="text-align: center; margin: 2em 0;">
  <video width="600" controls>
    <source src="/assets/videos/Blades_290.mp4" type="video/mp4">
    Your browser can’t play this video. <a href="/assets/videos/Blades_290.mp4">Download it here.</a>
  </video>
  <p style="font-size: 0.9em; color: #555; margin-top: 0.5em;">
    <strong>Figure 2.</strong> Blade 0ND Bending to Shaft Torsional-Axial-Bending fully Coupled Mode.
  </p>
</div>



To validate the predictions, I adapted the existing **ARES rig** facility by designing, commissioning, and installing a new asymmetric support structure. This bespoke setup allowed us to deliberately trigger the predicted couplings on a real rotating system. Experiments confirmed the predictions and even revealed additional vibrational couplings when a disc is mistuned.

<div style="text-align: center; margin: 2em 0;">
  <img src="/assets/images/ARES_OLD_CAD_3_page-0001.jpg" alt="ARES CAD model" width="600">
  <p style="font-size: 0.9em; color: #555; margin-top: 0.5em;">
    <strong>Figure 3.</strong> Pre-existing ARES rig
  </p>
</div>

<div style="text-align: center; margin: 2em 0;">
  <img src="/assets/images/Assembly_Cool_Picture2_page-0001.jpg" alt="ARES assembled rig" width="600">
  <p style="font-size: 0.9em; color: #555; margin-top: 0.5em;">
    <strong>Figure 4.</strong> Asymmetric bearing support assembly added for experimental validation
  </p>
</div>


---
### My Approach to Research

Placeholder

### Methods & Tools:

- **FEM**: Abaqus (with Python scripting), fully self-developed models in Matlab
- **CAD**: Solid Works
- **Data Acquisition**: SignalCalc, LabView
- **Experimental Techniques**: Hammer tests, Shaker tests, Unbalance tests
- **Programming Languages** for pre and post-processing: Matlab, Python

---

## Publications

- **Study of coupling between shaft bending and disc zero nodal diameter modes in a flexible shaft-disc assembly**  
  *Journal of Sound and Vibration, 2020*  
  [DOI](https://doi.org/10.1016/j.jsv.2020.115362)

- **Cross-disc coupling in a flexible shaft–disc assembly in presence of asymmetric axial–radial bearing supports**  
  *Journal of Sound and Vibration, 2022*  
  [DOI](https://doi.org/10.1016/j.jsv.2022.116826)

- **Shaft Bending to Zero Nodal Diameter Disc Coupling Effects in Rotating Structures Due to Asymmetric Bearing Supports**  
  *Conference Proceedings of the Society for Experimental Mechanics Series (IMAC), 2020*  
  [Springer Link](https://link.springer.com/chapter/10.1007/978-3-030-47717-2_38)

- **Coupling between axial, lateral and torsional vibration modes of a flexible shaft with flexible staggered blades**  
  *Proceedings of the International Conference on Vibrations in Rotating Machinery (VIRM), 2020*  
  [Taylor & Francis Link](https://www.taylorfrancis.com/chapters/oa-edit/10.1201/9781003132639-21/coupling-axial-lateral-torsional-vibration-modes-flexible-shaft-flexible-staggered-blades-tuzzi-schwingshackl-green)

- **Investigation on coupling between disc umbrella mode and shaft bending modes in a rotating shaft-disc assembly**  
  *Journal of Physics: Conference Series, 2019*  
  [IOP Link](https://iopscience.iop.org/issue/1742-6596/1264/1)

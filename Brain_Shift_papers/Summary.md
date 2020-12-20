# Summary of Papers

---

## Brief Summary of what have been read so far.

---

### 1. The first evaluation of brain shift during functional neurosurgery by deformation field analysis (2005)

- [Short Case Report] to demonstrate how important it is to plant the electrodes accurately (2mm) in case of advanced Parkinson’s disease. 

- With functional neurosurgery even minimal brain shift in the region of the STN cannot be neglected.
- The accuracy of **static** image guided devices decreases with the length of surgery owing to intraoperative brain shift[1]
- Methods for quantifying this brain movement (teleradiography, pointer based measurement of brain shift, **intraoperative ultrasound**) do exist, but are **not suitable** for evaluating the shift from the surface to the middle of the brain during functional neurosurgery. 
- Only intraoperative CT or MRI can give detailed information on intraoperative shift that can be used to modify the planned trajectories. This requires that one of these examinations is repeated during surgery, with the patient still fixed in the stereotactic frame. 
- Up to now, illustrative models for shift measurement in the brain, especially in the basal ganglia, have not been established.
- the brain shift as a **dynamic error** occurring during functional neurosurgery.
- Brain shift as a reason for ‘‘dynamic error’’ is caused by loss of cerebrospinal fluid (CSF), the inherent qualities of the brain, failure to reclose the burr hole, the time consuming procedures of multichannel microelectrode recording and stimulation testing, and by the procedure itself, which favours further CSF derangement. 
- **Deformation field analysis** has proved to be a reliable method for analysing intraoperative brain shift. Up to now no other study has demonstrated this phenomenon with such accuracy.

---

### 2. Intraoperative Compensation for Brain Shift (2001)

- Tumor removal, brain swelling, the use of brain retractors, and cerebrospinal-fluid drainage all result in an intraoperative brain deformation that is known as brain shift. Thus, neuronavigation systems relying on preoperative image data have a decreasing accuracy during the surgical procedure.
- Navigation systems have been used to measure the extent of brain shift, relying on pointer-based [2,3], mechanical arm-based [4], or autofocus/laser-based techniques [5].
- The suspicious area was **segmented** and the approach was planned. 
- Then, **registration** with these markers completed the navigational update. As an estimate of the accuracy of the updated neuronavigation the mean registration error, a technical measure calculated by the navigation software using the fiducial coordinates (root mean square error) was documented.
- The accuracy was checked by repeated landmark verifications; that is, it was verified whether the position of fiducial or anatomic landmarks that could be easily identified with the
autofocus pointer of the microscope was depicted correctly by the MR image data.
- intraoperative ultrasound has the advantage of being a real-time modality. Ultrasound data may provide information on how to modify high-quality preoperative MR image data to represent the real intraoperative situation, thus compensating for the effects of brain shift. 
- This approach relies on the non-linear registration of intraoperative ultrasound data with preoperative MR volume data. 
- The MR data are modified by using a mathematical model describing the movement of the brain during surgery [6,7,8].
- Instead of using ultrasound images to adapt preoperative image data, so-called sparse data (i.e., measured movements of some known landmarks) are used in mathematical models that try to predict the deformation of the brain [8,9]

---

### 3. Brain Shift Correction Based on a Boundary Element Biomechanical Model with Different Material Properties (2003)

- Depends on Biomechanical Model

---

### 4. Intraoperative Segmentation and Nonrigid Registration for Image Guided Therapy (2000)

- The Paper is so old.

---

### 5. Knowledge modeling in image-guided neurosurgery: application in understanding intraoperative brain shift (2007)

- During an image-guided neurosurgery procedure, the first main deformation (also called brain shift) occurs while opening the dura matter and the arachnoid.
- Deformations are different according to the timing of the surgical procedure and to the surgical action being performed.
- the objective is to succeed in registering preoperative images regarding the deformations.
- This can be achieved by using intraoperative imaging and/or  biomechanical models
- Technical difficulties such as the limited intraoperative MRI spatial resolution and the poor temporal resolution of registration algorithms
- TBC

---

### 6. Framework and Bio-Mechanical Model for a Per-Operative Image-Guided Neuronavigator Including ‘Brain-Shift’ Compensation(TIMC 2006)

- Hastreiter et al. [10] observed a **great variability of the brain-shift** ranging up to 24 mm for cortical displacement and exceeding 3 mm for the deep tumor margin.
- Nabavi et al. [11] state that the **continuous dynamic brain-shift process evolves differently in distinct brain regions**, with a surface shift that occurs throughout surgery (caused by gravity) and with a subsurface shift that mainly occurs during resection (because of the collapse of the resection cavity and the intraparenchymal changes).
- Arguing against the exorbitant cost of the intraoperative MRI imaging devices, some authors have proposed to **couple the biomechanical model of the brain with low-cost readily available intraoperative data** [12] such as **laser-range scanner** systems [13], [14] or **intraoperative ultrasound** [15].
- The **goal** of the intervention is to **minimize the injury** while **maximizing resection**.
- **Design Considerations**:
    1. Finite element biomechanical model of the brain driven by  anatomical landmarks.
    2. The deformation is applied to operating room-registered preoperative patient data.
    3. The deformation occurs throughout the intervention and needs to be monitored as often as possible.
    4. The deformation is due to multiple factors, some of which are hard to monitor :
        - Tissue inflamation and CSF leakage.(hard to monitor)
        - Gravity.
        - Tissue resection.
        - Cyst drainage.
        - Deep structures displacements.
- **Design:** low-cost imaging techniques (localised 2.5D echography) for **deep structures displacements**, and Miga et al. in [14] solution could track **cortical displacements**.
- Brain tissue has a visco-elastic, non-linear behaviour which yields equations difficult to integrate in real-time[16].
- The 3D finite elements code needs to be tested on phantom or patient data.
- Many clinical issues remain unresolved:
  - The definition of the **reference structures** used to ‘pilot’ the model.
  - The **intraoperative identification** within the echographic planes.

---

### 7. Model-driven brain shift compensation (MIA 2002)

---

### 8. A comprehensive model-assisted brain shift correction approach in image-guided neurosurgery: a case study in brain swelling and subsequent sag after craniotomy (Vanderbilt 2019)

BioMechanical Model.

---

### 9. Intraoperative Brain Shift Compensation: Accounting for Dural Septa (IEEE 2011)

---

### 10. Functional neuronavigation combined with intra-operative 3D ultrasound: Initial experiences during surgical resections close to eloquent brain areas and future directions in automatic brain shift compensation of preoperative data (2007)

---

### 11. A Feature-Driven Active Framework for Ultrasound-Based Brain Shift Compensation (Harvard 2018)

---

### 12. Clinical evaluation of a model-updated image-guidance approach to brain shift compensation: experience in 16 cases (2016)

---

### 13. Brain Shift Estimation in Image-Guided Neurosurgery Using 3-D Ultrasound (IEEE 2005)

---

### 14. An atlas-based method to compensate for brain shift: Preliminary results (MIA 2007)

---

### 15. Intraoperative Imaging Modalities and Compensation for Brain Shift in Tumor Resection Surgery (2017)

---

### 16. Estimation of Intraoperative Brain Deformation (2012)

---

### 17. Brain Shift in Neuronavigation of brain tumours: A Review (MIA 2016)

---

### 18. Strategies for brain shift evaluation (MIA 2004)

---

### 19. Brain-shift compensation using intraoperative ultrasound and constraint-based biomechanical simulation (MIA 2017)

---

### 20. Stereopsis-Guided Brain Shift Compensation (IEEE 2005)

---

### 21. Thesis in French (Just Use Figures 2008)

---

### 22. Brain-shift compensation using intraoperative ultrasound and constraint-based biomechanical simulation (TIMC 2017)

---

### 23. Intraoperative image updating for brain shift following dural opening (2007)

---

### 24. Stereopsis-Guided Brain Shift Compensation (PhD Thesis 2004)

---

### 25. Resolve Intraoperative Brain Shift as Imitation Game (Confrence paper 2018)

---

### 26. Automatic ultrasound–MRI registration for neurosurgery using the 2D and 3D LC2 Metric (MIA 2014)

---

## Useful Videos

1. [3D UltraSound MRI Brain-shift video](https://www.youtube.com/watch?v=gU2yvMjnxhw)
2. [2D UltraSound MRI Brain-shift video](https://www.youtube.com/watch?v=4P1vUrSMRJg)

--- 

## References

[1]: Nimsky C, Ganslandt O, Cerny S, et al. Quantification of, visualization of, and compensation for brain shift using intraoperative magnetic resonance imaging. Neurosurgery 2000;47:1070–80.
[2]: Dorward NL, Alberti O, Velani B, Gerritsen FA, Harkness WF, Kitchen ND, Thomas DG. Postimaging brain distortion: magnitude, correlates, and impact on neuronavigation. J Neurosurg 1998;88:656–62.
[3]: Hill DLG, Maurer CR, Maciunas RJ, Barwise JA, Fitzpatrick JM, Wang MY. Measurement of intraoperative brain surface deformation under a craniotomy. Neurosurgery 1998;43:514–28.
[4]: Skrinjar O, Duncan J. Real time 3D brain shift compensation. In: Kuba A, Samal M, Todd-Pokropek A, eds. Information Processing in Medical Imaging. Berlin: Springer, 1999:42–55. 
[5]: Roberts DW, Hartov A, Kennedy FE, Miga MI, Paulsen KD. Intraoperative brain shift and deformation: a quantitative analysis of cortical displacement in 28 cases. Neurosurgery 1998;43:749–60.
[6]: Gobbi DG, Comeau RM, Peters TM. Ultrasound/MRI overlay with image warping for neurosurgery. In: Delp SL, DiGioia AM, Jaramaz B, eds. Medical Image Computing and Computer-Assisted Intervention— MICCAI 2000. Berlin: Springer, 2000:106–14.
[7]: King AP, Blackall JM, Penney GP, Edwards PJ, Hill DL, Hawkes DJ. Bayesian estimation of intra-operative deformation for image-guided surgery using 3-D ultrasound. In: Delp SL, DiGioia AM, Jaramaz B, eds. Medical Image Computing and Computer-Assisted Intervention—MICCAI 2000. Berlin: Springer, 2000: 588–97
[8]: Roberts DW, Miga MI, Hartov A, Eisner S, Lemery JM, Kennedy FE, Paulsen KD. Intraoperatively updated neuroimaging using brain modeling and sparse data. Neurosurgery 1999;45:1199–207.
[9]: Miga MI, Staubert A, Paulsen KD, Kennedy FE, Tronnier VM, Roberts DW, Hartov A, Platenik LA, Lunn KE. Model-updated image-guided neurosurgery: preliminary analysis using intraoperative MR. In: Delp SL, DiGioia AM, Jaramaz B, eds. Medical Image Computing and Computer-Assisted Intervention—MICCAI 2000. Berlin: Springer, 2000:115–24.
[10]: Hastreiter P, Rezk-Salama C, Soza G, Bauer M, Greiner G, Fahlbusch R, Ganslandt O, and Nimsky C. Strategies for brain shift evaluation. Medical Image Analysis, 8:447–464, 2004.
[11]: Nabavi A, Black P, Gering D, Westin C, Mehta V, Pergolizzi R, Ferrant M, Warfield S, Hata N, Schwartz R, Wells III W, Kikinis R, and Jolesz F.
Serial intraoperative magnetic resonance imaging of brain shift. Neurosurgery, 48(4):787–797, 2001.
[12]: Miga M I, Sinha T K, and Cash D M. Techniques to correct for soft tissue deformations during image-guided brain surgery. Payan Y., editor. Biomechanics Applied to Computer Assisted Surgery. Research Signpost Publisher, ISBN 81-308-0031-4, pages 153–176, 2005.
[13]: Audette M A, Siddiqi K, Ferrie F P, , and Peters T M. An integrated range-sensing, segmentation and registration framework for the  characterization of intra-surgical brain deformations in image-guided surgery. Computer Vision and Image Understanding, 89:226–251, 2003.
[14]: Miga M I, Sinha T K, Cash D M, Galloway R L, and Weil R J. Cortical surface registration for image-guided neurosurgery using laser-range scanning. IEEE Transactions on Medical Imaging, 22(8):973–985, 2003.
[15]: Comeau R M, Sadikot A F, Fenster A, and Peters T M. Intraoperative ultrasound for guidance and tissue shift correction in image-guided neurosurgery. Medical Physics, 27:787–800, 2000.
[16]: K Miller. Biomechanics of brain for computer integrated surgery. Warsaw University of Technology Publishing House, 2002.

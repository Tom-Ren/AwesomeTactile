# <center> `AwesomeTactile`
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Reviews, projects,  hardwares, groups, and papers collection of Tactile:love_you_gesture:

## Overview

---
`TL;DR`<br>
:telescope: [Reviews](#i-reviews)<br>
:rocket: [Projects](#ii-projects)<br>
:robot: [Hardwares](#iii-hardwares)<br>
:classical_building: [Groups](#iv-groups)<br>
:bookmark_tabs: [Papers](#v-research-papers)<br>
---


## I. Reviews
` This part collectes reviews of tactile research, from biological theoories to technical implementations. `
### ① Theoritical Basis
1. (Nature Reviews Neuroscience) **Coding and use of tactile signals from the fingertips in object manipulation tasks.** [[paper](https://www.nature.com/articles/nrn2621)]
- ```This paper provides the basis tactile and control mechanisim of finger manipulation tasks. It describles the tactile infomation and encoding process (statistics and timing spikes), as well as the multimodal representations.```<br>
<img width="430" alt="touch" src="https://user-images.githubusercontent.com/22866605/204191542-be282585-e2b8-4206-a48f-773f3f2fd9c8.png"><img width="370" alt="manipulate" src="https://user-images.githubusercontent.com/22866605/204192539-a93ff943-f264-4480-b0d9-f00f93f43e5a.png"><img width="800" alt="signle" src="https://user-images.githubusercontent.com/22866605/204191443-d1310c93-5afe-4ae2-9fc1-478b04438c14.png">

2. (Science Robotics) **Neuro-inspired electronic skin for robots.** [[paper](https://www.science.org/doi/10.1126/scirobotics.abl7344)]
- ```This paper reviews exsisting touch schemes, sensors, algorithms, as well as e-skin for robot. Besides, neural-like sensing, data processing and the integration chips are introduces to provide advance touch information for robotic interaction and applications.```<br>
<img width="460" alt="review" src="https://user-images.githubusercontent.com/22866605/204193276-e31c3aa2-f4a5-4568-bb6a-355b02155e2f.png"><img width="340" alt="sensor" src="https://user-images.githubusercontent.com/22866605/204194063-ce8d255e-1117-4bcf-b9f2-e77669e6ee14.png">
<img width="380" alt="devices" src="https://user-images.githubusercontent.com/22866605/204194167-5e300835-8774-4f16-9a63-1c1841795271.png"><img width="420" alt="algo" src="https://user-images.githubusercontent.com/22866605/204194622-3229a786-764e-45a8-9200-a2d0c48f8031.png">
  
3. (Science Robotics) **Electronic skins and machine learning for intelligent soft robots**[[paper](https://www.science.org/doi/full/10.1126/scirobotics.aaz9239)]
- ```This paper reviews the e-skin (multimodalities, sensor array, sensor fusion) and machine learning algos for soft robot.```<br>
  <img width="305" alt="trend" src="https://user-images.githubusercontent.com/22866605/204198392-50cce900-8969-48af-97a8-97e48619eae6.png"><img width="495" alt="devicarrayes" src="https://user-images.githubusercontent.com/22866605/204198409-5b4b5b79-783f-4bac-b4b1-79a96e6ff141.png">
  <img width="800" alt="ml-algo" src="https://user-images.githubusercontent.com/22866605/204198438-d46ec9a1-8ebd-48a6-9cd0-fda9070d88dd.png">
<br>

### ② Technical pipeline
  1. (IEEE Sensors Journal) Hardware Technology of Vision-Based Tactile Sensor: A Review** [[paper](https://ieeexplore.ieee.org/document/9911183)]
  - ```This paper concludes vision-based tactile sensor (VBTS), which consists of a contact module, an illumination module, and a camera module and their preparation process and complete manufacturing scheme. Details are presented, and future outlook are discussed.```<br>
  <img width="400" alt="vbts" src="https://user-images.githubusercontent.com/22866605/204210884-ee164b17-bda6-487b-a5b4-bf0f86cc7e04.png"><img width="400" alt="principle" src="https://user-images.githubusercontent.com/22866605/204212351-8bcbdfb3-2925-49b7-b774-add8e8f83453.png">

<br>


---
<br><br>
## II. Projects
`Various tactile sensors are developed in recent years, this part concluded these project to provide technical details for reproduction. Based on the sensor mechanism, they are divide as Gel (vision based), electric (pressure sensitive), and other physical principles (optics, thermal, mechanical, *et al.*)`
<br>

### ① Gel Serials
- [GelSight](https://people.csail.mit.edu/kimo/gelsight/): `The first gel based sensors to detect surface details`. :bookmark_tabs: [[paper3](https://pubmed.ncbi.nlm.nih.gov/29186053/)] [[paper2](https://people.csail.mit.edu/kimo/publications/microgeometry/microgeometry.pdf)]  [[paper1](https://people.csail.mit.edu/kimo/publications/retrographic/sensor.pdf)]   :mortar_board: [[Kimo](https://people.csail.mit.edu/kimo/)]  [[Adelson](http://persci.mit.edu/people/adelson)]
  <img width="800" alt="RetrographicSensing" src="https://user-images.githubusercontent.com/22866605/204216823-c2682f90-865c-4100-a7b8-161cb54363b3.png">
  <img width="800" alt="MicrogeometryCapture" src="https://user-images.githubusercontent.com/22866605/204216969-d36de41e-51f1-44e6-abd5-6ffae497ee2d.png">
  <br>
  
- [GelSight Wedge](http://gelsight.csail.mit.edu/wedge/): `GelSight Wedge sensor, which is optimized to have a compact shape for robot fingers, which can achieve high-resolution 3D reconstruction.` :bookmark_tabs: [[paper](http://gelsight.csail.mit.edu/wedge/ICRA2021_Wedge.pdf)(ICRA21)]  :mortar_board:  [[ShaoXiong Wang](http://shaoxiongwang.com/)] [[MARS lab](https://www.purduemars.com/)]<br>
  <img width="425" alt="Wedge" src="https://user-images.githubusercontent.com/22866605/204221118-577cb2ca-9bf9-4613-99ac-469a5d371a0e.png">
  <img width="375" alt="mechanical" src="https://user-images.githubusercontent.com/22866605/204254694-c41c7768-b809-4825-ba45-3d6122ffb036.png">
  <br>
  
- [GelSlim](https://mcubelab.github.io/gelslim/): `A popular open-source compact tactile-sensing Finger with measurement of shape, force and slip.`   :bookmark_tabs: [[paper](https://arxiv.org/pdf/2103.12269.pdf)] [[sight](https://arxiv.org/pdf/1708.00922.pdf)]  [[1.0](https://arxiv.org/pdf/1803.00628.pdf)] [[2.0](https://arxiv.org/pdf/1810.04621.pdf)] [[MPalm](https://arxiv.org/abs/1909.05426)]  :mortar_board:[[Alberto](http://meche.mit.edu/people/faculty/ALBERTOR@MIT.EDU)]  [[SiYuan Dong](https://sites.google.com/site/siyuandong000/)] [[Ian H Taylor](https://ianhtaylor.net/)]    :inbox_tray: [[resource](https://github.com/mcubelab/gelslim)]  [[1.0](https://mcube.mit.edu/research/gelslim.html)] [[30](https://ianhtaylor.net/gelslim-30)]<br>
  <img width="460" alt="family" src="https://user-images.githubusercontent.com/22866605/204275215-a13f7978-6963-4a5e-8edf-386a07161c16.png">
  <img width="340" alt="work" src="https://user-images.githubusercontent.com/22866605/204276884-aa38264d-d5b0-483e-a7c2-44d5b440a7a9.png">
  <img width="800" alt="assemble" src="https://user-images.githubusercontent.com/22866605/204276931-23aeff25-cbc3-4939-8246-5b91f3796cf5.png">
  <br>
  
  
- [Digit](https://digit.ml/): `An easy-to-use, reliable, low-cost, compact, high-resolution, tactile sensor designed for robotic in-hand manipulation.` :bookmark_tabs: [[paper](https://arxiv.org/abs/2005.14679)]  :octocat:  [[resource](https://github.com/facebookresearch/digit-design)]<br>
  <img width="455" alt="digit" src="https://user-images.githubusercontent.com/22866605/204284785-a6ac14b1-d879-4769-99f9-d042792b950e.png">
  <img width="345" alt="Allegro" src="https://user-images.githubusercontent.com/22866605/204285332-0ee7b1e8-3e02-4a7e-8add-e7062394208f.png">
  <br>
  
  
  
- [PyTouch](https://github.com/facebookresearch/PyTouch): `A machine learning tools for tactile info (with digit).`  :bookmark_tabs: [[paper](https://arxiv.org/abs/2105.12791)]
  <img width="800" alt="touch" src="https://user-images.githubusercontent.com/22866605/204287038-97d11995-4aa8-4a2b-b91a-13793f88c3a3.png">
  <br>

  
- [Tacto](https://github.com/facebookresearch/tacto): `A simulation environment for vision based tactile sensors.`  :bookmark_tabs: [[paper](https://arxiv.org/abs/2012.08456)]  📪[[community](https://www.touch-sensing.org/)]
  <img width="800" alt="tacto" src="https://user-images.githubusercontent.com/22866605/204286568-53396b4e-95a5-4e28-83c6-3a2c71196ff6.png">
  <br>


- [TacTip](https://www.bristolroboticslab.com/tactile-robotics): `3D printed open-source tactile sensors family.They adopt biomimetic design to record deformation when sensor touch object, with an substituting papillae and internal pins on the inside of its skin. Tracking pins can provide shape deformation (and force various) infomation.` 📑 [[paper](https://www.liebertpub.com/doi/full/10.1089/soro.2017.0052)]  [[ieee papers](https://ieeexplore.ieee.org/author/37399610200)]   🎓[[Nathan Lepora](https://lepora.com/)] [[Qiang Li](https://sites.google.com/site/qiangliresearch/qiang-li-s-homepage)] :octocat: [[OpenTacTip](https://softroboticstoolkit.com/tactip)]  📚 [[tutorial](https://sites.google.com/view/tactile-servoing/home)]  [[review18](https://ieeexplore.ieee.org/document/8453829)]   [[review21](https://ieeexplore.ieee.org/document/9499032) [arxiv](https://arxiv.org/abs/2105.14455)]<br>
  <img width="445" alt="tacto" src="https://user-images.githubusercontent.com/22866605/204427259-2df22498-c54f-4b78-9505-c2ab9a8ac419.png"><img width="355" alt="tacto" src="https://user-images.githubusercontent.com/22866605/204427397-8efee587-ef6c-4c0c-bb2c-157b38c96b41.png">

  
<br>  
  
### ② Elec Serials
  - [Tactile glove](https://www.nature.com/articles/s41586-019-1234-z): `is a low-cost, scalable tactile glove which contains 548 force sensors and can recognize 26 general objects.` 📑[[paper](https://www.nature.com/articles/s41586-019-1234-z)] [[intro](https://www.nature.com/articles/s41928-019-0268-4)]     :octocat:[[project](http://stag.csail.mit.edu/)]    🎓[[Subramanian Sundaram](https://subras.github.io/)] 
  <img width="800" alt="Tactile glove" src="https://user-images.githubusercontent.com/22866605/208057284-56b84c0c-5db0-4c24-b270-fa2e747bd244.png">
  <br>
  
  - [Italy Tactile Reseach](https://r8.ieee.org/italy-sensors/tactile-sensors/): `The Italian community working is the tactile sensing field, the areas of interest span e.g. human physiology, neuroscience, material science, electronics, robotics, bioengineering.` 🎓[[Maurizio Valle ](https://www.researchgate.net/profile/Maurizio-Valle)]
  <img width="600" alt="Tactile hand" src="https://user-images.githubusercontent.com/22866605/208052864-0986a22a-aab8-4153-b9d3-56bb98e58327.png">
  <br>
  
<br>

### ③ Physical Serials
  3.
  2. 
  1. 


---
<br><br>
## III. Hardwares
```Tactile sensors are developed and commercialized in robotics, metrology and related percepetion. This part will introduce existing sensors and equipements which are public avaliable and purchaseable, that give us a reference for next generation tactile sensors development.```<br>
  
  
### ① [GelSight, Inc.](https://www.gelsight.com/)
GelSight, Inc. is the commercialization organization of [GelSight](https://people.csail.mit.edu/kimo/gelsight/) research, they two tactile products, mesurement focused GelSight [Mobile](https://www.gelsight.com/solutions/surface-metrology-mobile/) (with micrometer accuracy) and robotics focused GelSight [Mini](https://www.gelsight.com/gelsightmini/) (with 25fps velocity).   :computer:[Code](https://github.com/gelsightinc) and  :clapper:[Video](https://www.youtube.com/@GelSight) introduction are availiable.<br>
  <img width="800" alt="图片" src="https://user-images.githubusercontent.com/22866605/208018443-a0cc7b36-f760-4e9f-a7b4-ca15f3ab8b86.png">
  <img width="800" alt="图片" src="https://user-images.githubusercontent.com/22866605/208018258-7e37e6d1-6cfe-453f-a027-ef7d1fa56769.png">
<br><br>

### ② [SynTouch, Inc.](https://syntouchinc.com/)
  `SynTouch, Inc, is a touch sensor company with various **force** and touch sensors production. They begin from the research in Department of Biomedical Engineering at the University of Southern California. They have multiple [touch sensors](https://syntouchinc.com/robotics/), BioTac, BioTac SP and NumaTac; haptics model and touch dataset. The BioTac has a rigid core surrounded by an elastic liquid-filled skin as human fingertip, with force, vibration, and temperature sensing abilities. Furthermore, NomaTac eliminates insensitive dead spots and vulnerable edges and absorbs the energy of collisions, improves durability.` 📋 [Annal Report](https://www.sec.gov/Archives/edgar/data/1728560/000172856019000002/FormC1.pdf) and 📄 [Brochure](https://syntouchinc.com/wp-content/uploads/2017/01/BioTac-Brochure.pdf), 🗂 [resource](https://syntouchinc.com/resources/)<br>
  <img height="200" alt="BioTac" src="https://user-images.githubusercontent.com/22866605/208024133-3d2ebc43-c846-46db-8539-ed0c2c510220.png">
  <img height="200" alt="BioTac SP" src="https://user-images.githubusercontent.com/22866605/208024150-adc01349-3ddf-4c97-870c-f01fe3d36320.png">
  <img height="200" alt="Numa" src="https://user-images.githubusercontent.com/22866605/208024303-2261453b-78d3-465b-ae20-321f72e8c8f7.png">
<br><br>
  

### ③ [TekScan](https://www.tekscan.com/tactile-pressure-sensors)
  `This serial are ultra thin, flexible pressure sensors by film printed circuit with high resolution.`  📦[Products](https://www.tekscan.com/tactile-pressure-sensors)
  <img height="200" alt="sample" src="https://user-images.githubusercontent.com/22866605/208051820-498d9273-4237-4eca-8564-fbb9b0b71a89.png">
  <img height="200" alt="princeple" src="https://user-images.githubusercontent.com/22866605/208051875-568c3690-bff6-46e0-a48e-7bfab58beced.png">
<br><br>
  
### ④ [Touchance](http://touchence.jp/en/products/)
  `Touchace produce various displacement, (6D) force, texture, and tactile sensors.`
  <img width="800" alt="Touchance" src="https://user-images.githubusercontent.com/22866605/208054976-d1376142-6860-4deb-9921-e59c56f5159e.png">

  
### ⑤ [Weiss](http://www.eu-robotics-sme.org/weiss-robotics-gmbh-co-kg/)
  `The WTS series includes a range of intelligent tactile sensor modules with integrated signal processor, with highly sensitive sensor matrix that allows a precise detection of very light contact forces.`
  <img width="800" alt="WTS" src="https://user-images.githubusercontent.com/22866605/208060385-661b8815-38e1-4d51-9043-b85699e11ee2.png">





  
  

---
<br><br>
## IV. Groups
balbabalb



---
<br><br>
## V. Research Papers
> new papers will be added on the top

  
  + (Science Advances) **Ultraflexible organic photonic skin.** [[paper](https://www.science.org/doi/full/10.1126/sciadv.1501856)]<br>
    - `This paper`
  + (Science) **A skin-inspired organic digital mechanoreceptor.** [[paper](https://www.science.org/doi/full/10.1126/science.aaa9306)]
    - `This paper`
  + 🌟 (Science Robotics) **A neuro-inspired artificial peripheral nervous system for scalable electronic skins**
  
  
  

  
  
[^_^]: Todo: https://sferrazza.cc/   https://raffaello.name  https://www.frontiersin.org/articles/10.3389/fphys.2020.611596/full https://www.mdpi.com/2079-6374/4/4/422 https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4724612/   https://www.mdpi.com/2079-4983/6/2/204/htm     Novel Tactile Sensor Technology and Smart TactileSensing Systems: A Review   https://www.engineering.columbia.edu/faculty/matei-ciocarlie   resource: https://techxplore.com/search/?search=tactile
[^_^]: # 「」『』▍▏▷ ◁ ▶ ◀ △▽▲▼➥ 和 → 还有 ˉˉ↴ 以及 ➨ ☛ ☑ 和 ✔ ✘✄ ❐ ✚ ☷ ① ② ③ ④ ⑤ ⑥ ⑦ ⑧ ⑨ ⑩
[^_^]: https://www.nature.com/search?q=tactile%20&%20review&journal=ncomms,%20nature,%20neuro&date_range=last_5_years&order=relevance

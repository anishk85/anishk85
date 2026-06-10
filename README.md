<!-- ════════════════════════════════════════════════════════════════ -->
<!--                  ANIMATED HEADER  (capsule render)                -->
<!-- ════════════════════════════════════════════════════════════════ -->

<a href="https://github.com/anishk85">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,50:00C2FF,100:00FFC6&height=220&section=header&text=Anish%20Kumar&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Robotics%20%E2%80%A2%20AI%2FML%20%E2%80%A2%20Autonomous%20Systems&descAlignY=58&descSize=18" alt="header"/>
</a>

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                     TYPING ANIMATION (typing svg)                 -->
<!-- ════════════════════════════════════════════════════════════════ -->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00C2FF&center=true&vCenter=true&width=800&lines=GSoC+2026+Contributor+%40+JdeRobot+%7C+ROS2+%2B+Aerostack2;Bronze+%C2%B7+Inter+IIT+Tech+Meet+14.0+%7C+Autonomous+Warehouse+Robot;MRI%E2%86%92sCT%3A+Mamba+%7C+Diffusion+%7C+GAN+%E2%80%94+8+architectures;ROS2+%C2%B7+Nav2+%C2%B7+Gazebo+Harmonic+%C2%B7+PyTorch+%C2%B7+Aerostack2)](https://github.com/anishk85)

<!-- profile views + followers + gsoc badge -->
<img src="https://komarev.com/ghpvc/?username=anishk85&label=Profile%20Views&color=6c63ff&style=for-the-badge" alt="profile views"/>
<a href="https://github.com/anishk85?tab=followers">
  <img src="https://img.shields.io/github/followers/anishk85?label=Followers&style=for-the-badge&color=00c2ff&logo=github" alt="followers"/>
</a>
<img src="https://img.shields.io/badge/GSoC_2026-Contributor-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="gsoc 2026"/>
<img src="https://img.shields.io/badge/%F0%9F%A5%89_Inter_IIT_Tech_Meet_14.0-Bronze-CD7F32?style=for-the-badge" alt="bronze inter iit"/>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,50:00C2FF,100:00FFC6&height=2" />

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                            ABOUT ME                               -->
<!-- ════════════════════════════════════════════════════════════════ -->

## About Me

<table border="0" cellspacing="0" cellpadding="0">
<tr>
<td width="58%" valign="top">

**IIT Mandi undergrad** at the intersection of classical robotics and deep learning. I build systems that navigate, perceive, and act — on real hardware and in simulation.

Currently extending JdeRobot's multi-agent framework for drone simulations as a **GSoC 2026 Contributor**, and doing navigation + arm control for **Team Deimos'** custom-built Mars rover.

</td>
<td width="4%"></td>
<td width="38%" valign="top">

```
GSoC 2026   JdeRobot / TheRoboticsClub
Award       Bronze · Inter IIT Tech Meet 14.0
Team        Team Deimos — Mars Rover (IIT Mandi)
Research    MRI→sCT · 8 DL architectures
Now         drone cat-mouse in Gazebo Harmonic
Stack       ROS2 · PyTorch · Nav2 · Aerostack2
```

</td>
</tr>
</table>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFC6,50:00C2FF,100:6C63FF&height=2" />

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                       FEATURED PROJECTS                           -->
<!-- ════════════════════════════════════════════════════════════════ -->

## 📌 &nbsp; Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Visual-Guided-Navigation](https://github.com/anishk85/Visual-Guided-Navigation)
> **Zero-shot vision-language navigation** on TurtleBot3 in Gazebo Harmonic. Robot navigates to natural-language or voice object goals in unseen maps — no pre-built map, no hand-coded waypoints. Gemini 2.5 Flash parses instructions into a goal stack; YOLOv8x-World + MobileSAM + CLIP perception; two-layer DualMap promotes objects seen across ≥3 keyframes to a global A\* nav graph. Includes optional TD3 RL navigator and Next.js + rosbridge GUI.

`Python` &nbsp;`ROS2` &nbsp;`Gazebo` &nbsp;`Gemini 2.5` &nbsp;`YOLOv8` &nbsp;`CLIP` &nbsp;`Nav2` &nbsp;`SLAM` &nbsp;`TD3`

</td>
<td width="50%" valign="top">

### [WareHouse-Inventory-Management](https://github.com/anishk85/WareHouse-Inventory-Management-)
> 🥉 **Bronze Medal — Inter IIT Tech Meet 14.0.** Autonomous 4WD mecanum warehouse robot: navigates shelves, scans QR inventory tags, logs to cloud. Custom ros2\_control C++ hardware interface; Cartographer SLAM; Nav2 with MPPI controller (DWB failed on mecanum); CLAHE→ZBar QR pipeline; optical-flow lift safety. Whole stack Docker-ported to a Pi 4 in 5 hours after a power fault destroyed the Pi 5 the night before the demo.

`C++` &nbsp;`Python` &nbsp;`ROS2` &nbsp;`Nav2` &nbsp;`MPPI` &nbsp;`Docker` &nbsp;`Next.js` &nbsp;`PostgreSQL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [MRI-TO-SCT-mamba-diffusion-gans](https://github.com/anishk85/MRI-TO-SCT-mamba-diffusion-gans-)
> Benchmark of **8 deep learning architectures** for synthetic CT generation from brain MRI, targeting MRI-only radiation treatment planning. Covers Mamba regression (TriPlane, TriAxial, U-Mamba, SegMamba), diffusion models (Hybrid Diffusion, Diffusion UMamba), and GANs (Pix2Pix, UNIT). Best image quality: **TriPlane Mamba** (SSIM 0.856, PSNR 25.79 dB). Best dosimetric fidelity: **U-Mamba** (Gamma 1%/1mm = 93.3%, clinical threshold passed).

`Python` &nbsp;`PyTorch` &nbsp;`Mamba SSM` &nbsp;`DDPM` &nbsp;`GAN` &nbsp;`Medical Imaging`

</td>
<td width="50%" valign="top">

### [GSoC 2026 — Drone Cat-Mouse Chase](https://github.com/anishk85/gsoc2026-Anish_Kumar)
> **Google Summer of Code 2026 @ JdeRobot / TheRoboticsClub.** Extended JdeRobot's RoboticsApplicationManager (RAM) with multi-process / multi-agent support so N peer agents share one Play/Stop lifecycle via Linux process signals + Gazebo pause sync. Demonstrated as a two-drone pursuit-evasion exercise on ROS2 Humble + Gazebo Harmonic + Aerostack2, where the "cat" drone chases a pre-programmed "mouse" drone.

`Python` &nbsp;`ROS2` &nbsp;`Gazebo` &nbsp;`Aerostack2` &nbsp;`GSoC 2026`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Team Deimos — Mars Rover (IIT Mandi)
> Custom-built Mars rover designed and fabricated by **Team Deimos**, Jetson Nano onboard. Software: ROS2, Nav2, MoveIt2, FastSAM scene understanding, EKF multi-sensor fusion (GPS + IMU + wheel + visual odometry), STVL 3D costmaps, elevation mapping, ROSBridge web dashboard, Docker. Stack developed on a Clearpath Husky + Kinova 7-DOF arm dev rig before rover deployment.

`C++` &nbsp;`Python` &nbsp;`ROS2` &nbsp;`MoveIt2` &nbsp;`EKF` &nbsp;`Nav2` &nbsp;`FastSAM` &nbsp;`Docker`

</td>
<td width="50%" valign="top">

### [yolo-keyboard-key-detection](https://github.com/anishk85/yolo-keyboard-key-detection)
> Real-time **keyboard key detection** powered by a custom-trained **YOLO** model.

`Python` &nbsp;`YOLO` &nbsp;`Computer Vision`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [researchAI](https://github.com/anishk85/researchAI)
> Experiments and research tooling exploring **AI/ML** ideas and pipelines.

`Python` &nbsp;`Machine Learning`

</td>
<td width="50%" valign="top">

### [CodeMind](https://github.com/anishk85/CodeMind)
> An interactive **JavaScript** project blending logic and coding challenges.

`JavaScript`

</td>
</tr>
</table>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,50:00C2FF,100:00FFC6&height=2" />

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                        GITHUB STATS                               -->
<!-- ════════════════════════════════════════════════════════════════ -->

## 📊 &nbsp; GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=anishk85&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00C2FF&icon_color=6C63FF&text_color=c9d1d9" alt="stats"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anishk85&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00C2FF&text_color=c9d1d9&langs_count=8" alt="top langs"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=anishk85&theme=tokyonight&hide_border=true&background=0D1117&ring=00C2FF&fire=6C63FF&currStreakLabel=00C2FF" alt="streak"/>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFC6,50:00C2FF,100:6C63FF&height=2" />

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                      ACTIVITY GRAPH                               -->
<!-- ════════════════════════════════════════════════════════════════ -->

## 📈 &nbsp; Contribution Graph

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=anishk85&theme=tokyo-night&bg_color=0D1117&color=00C2FF&line=6C63FF&point=00FFC6&hide_border=true&area=true" alt="activity graph"/>

<br/>

<img src="https://ghchart.rshah.org/00C2FF/anishk85" width="100%" alt="contribution chart"/>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,50:00C2FF,100:00FFC6&height=2" />

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                         CONNECT                                   -->
<!-- ════════════════════════════════════════════════════════════════ -->

## 🌐 &nbsp; Connect With Me

<div align="center">

<a href="https://github.com/anishk85">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github"/>
</a>
<a href="#">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
</a>
<a href="mailto:anishkumar59085@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/>
</a>
<a href="https://theroboticsclub.github.io/gsoc2026-Anish_Kumar">
  <img src="https://img.shields.io/badge/GSoC_Blog-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="gsoc blog"/>
</a>

</div>

<br/>

<div align="center">


⭐️ From [anishk85](https://github.com/anishk85)

</div>

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                     ANIMATED FOOTER                               -->
<!-- ════════════════════════════════════════════════════════════════ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFC6,50:00C2FF,100:6C63FF&height=120&section=footer" alt="footer"/>

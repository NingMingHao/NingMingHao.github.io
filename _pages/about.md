---
permalink: /
title: "Minghao Ning"
excerpt: "PhD candidate at the University of Waterloo working on robust autonomous mobility: multi-sensor perception, motion planning, and cooperative perception."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="mn-hero">
  <img src="/images/research/coinfra-wide.jpg" alt="CoInfra cooperative infrastructure perception: globally fused vehicle and pedestrian tracks across a real traffic site.">
  <div class="mn-hero__caption">
    <p class="mn-hero__title">From onboard geometry-aware planning to cooperative infrastructure sensing</p>
    <p class="mn-hero__sub">Building perception, planning, and control that stay reliable in adverse weather, dense traffic, and crowded indoor spaces.</p>
  </div>
</div>

I am a PhD student in the Department of Mechanical and Mechatronics Engineering at the University of Waterloo, advised by Professor [Amir Khajepour](https://uwaterloo.ca/mechanical-mechatronics-engineering/profile/akhajepo) and co-supervised by Professor [Ehsan Hashemi](https://apps.ualberta.ca/directory/person/ehashemi) at the University of Alberta. 
My research focuses on autonomous driving systems, with an emphasis on multi-sensor fusion, perception, motion planning, control, and cooperative perception for real-world mobility platforms. 
I led the [perception development](https://github.com/NingMingHao/Yolov8TensorrtRos) for the second generation of the [WATonoBus](https://uwaterloo.ca/watonobus/) autonomous shuttle project and led the transition to its third generation (Autoware-based platform).
I also led the development of [CoInfra](https://github.com/NingMingHao/CoInfra), a cooperative infrastructure perception system for connected and automated mobility.
My work aims to improve the reliability and safety of autonomous mobility systems in adverse weather, dense traffic, and complex indoor and outdoor environments.

<a id="research"></a>

Research
======

My research traces a single research trajectory: it begins with robust, real-time perception and motion planning on a single vehicle, and culminates in large-scale cooperative perception powered by infrastructure sensor networks for both outdoor driving and indoor robot mobility. The recurring theme is that safe autonomy needs representations that are *geometry-aware* (useful even when object classes are unknown), *delay-aware* (trustworthy under real network latency), and *deployment-aware* (validated on real hardware in real conditions).

<div class="mn-cards">

  <div class="mn-card">
    <a class="mn-card__media" href="/publication/point-cloud-potential-field">
      <img src="/images/research/motion-planning.jpg" alt="Potential field generated directly from a LiDAR point cloud and used inside an MPC planner.">
    </a>
    <div class="mn-card__body">
      <h3 class="mn-card__title">Drivable space based motion planning MPC</h3>
      <p class="mn-card__text">A potential field is built directly from raw LiDAR point clouds and integrated into a model predictive control planner. By reasoning over the drivable corridor rather than object lists, the planner stays robust to irregular and out-of-distribution obstacles while remaining real-time and dynamically feasible.</p>
      <p class="mn-card__links"><a href="/publication/point-cloud-potential-field">Paper (IEEE&nbsp;TVT)</a></p>
    </div>
  </div>

  <div class="mn-card">
    <a class="mn-card__media" href="/publication/safe-drivable-space-fusion">
      <img src="/images/research/drivable-space.jpg" alt="LiDAR-camera-HD map fusion for safe drivable space under adverse weather.">
    </a>
    <div class="mn-card__body">
      <h3 class="mn-card__title">All-weather drivable-space perception</h3>
      <p class="mn-card__text">A LiDAR&ndash;camera&ndash;HD&nbsp;map fusion pipeline combines adaptive ground removal, weather-aware clustering, and uncertainty-tolerant association to estimate safe free space. Validated on a full-scale autonomous shuttle during real Canadian winter operation.</p>
      <p class="mn-card__links"><a href="/publication/safe-drivable-space-fusion">Paper (IEEE&nbsp;ITSC)</a></p>
    </div>
  </div>

  <div class="mn-card">
    <a class="mn-card__media" href="/publication/coinfra">
      <img src="/images/research/coinfra.jpg" alt="CoInfra outdoor cooperative infrastructure perception with globally fused object tracks.">
    </a>
    <div class="mn-card__body">
      <h3 class="mn-card__title">CoInfra cooperative infrastructure perception</h3>
      <p class="mn-card__text">A globally synchronized, delay-aware perception platform built from 14 roadside sensor nodes with cameras, LiDAR, edge computing, and 5G. It supports low-latency cloud fusion and 3D tracking, and ships with a public adverse-weather dataset for multi-agent perception research.</p>
      <p class="mn-card__links"><a href="/publication/coinfra">Paper</a> <a href="https://github.com/NingMingHao/CoInfra">Code &amp; dataset</a></p>
    </div>
  </div>

  <div class="mn-card">
    <a class="mn-card__media" href="/publication/indoor-cooperative-perception">
      <img src="/images/research/indoor.jpg" alt="Indoor cooperative perception driving an MPC-controlled medical-bed robot among obstacles.">
    </a>
    <div class="mn-card__body">
      <h3 class="mn-card__title">Indoor cooperative perception &amp; closed-loop MPC</h3>
      <p class="mn-card__text">Ceiling-mounted sensor nodes provide uncertainty-aware 3D human pose estimation and delay-aware tracking, overcoming occlusion in crowded spaces. The perception output closes the loop with the MPC planner on a real medical-bed robot platform.</p>
      <p class="mn-card__links"><a href="/publication/indoor-cooperative-perception">Paper (IEEE&nbsp;ITSC)</a></p>
    </div>
  </div>

</div>

Selected project highlights
======

<ul class="mn-projects">
  <li><span class="mn-projects__name">WATonoBus &mdash; Waterloo all-weather autonomous shuttle.</span> Led second-generation perception development and the transition to a third-generation Autoware-based stack, contributing to decision making, safety monitoring, and motion planning/control on a field-tested platform.</li>
  <li><span class="mn-projects__name">CoInfra cooperative infrastructure perception.</span> Designed and deployed a 14-node roadside perception network with cloud-side fusion, delay-aware synchronization, and a large-scale public dataset with diverse adverse-weather coverage.</li>
  <li><span class="mn-projects__name">5G vehicle-to-infrastructure mobility.</span> Built solar-powered infrastructure sensor nodes with cameras, LiDAR, and Jetson edge computers for real-time fusion, global planning, and remote over-the-air management.</li>
  <li><span class="mn-projects__name">Indoor cooperative perception for robot mobility.</span> Developed delay-aware cooperative perception and 3D human pose estimation for safe robot navigation in dynamic, crowded indoor environments.</li>
</ul>

Recent publications
======

* "CoInfra: A Large-Scale Cooperative Infrastructure Perception System and Dataset in Adverse Weather," *arXiv*, 2025. [[paper]](/publication/coinfra)
* "A Novel Motion Planning for Autonomous Vehicles Using Point Cloud Based Potential Field," *IEEE Transactions on Vehicular Technology*, 2024. [[paper]](/publication/point-cloud-potential-field)
* "An Efficient Approach to Generate Safe Drivable Space by LiDAR-Camera-HDmap Fusion," *IEEE ITSC*, 2024. [[paper]](/publication/safe-drivable-space-fusion)
* "Enhancing Indoor Mobility with Connected Sensor Nodes: A Real-Time, Delay-Aware Cooperative Perception Approach," *IEEE ITSC*, 2024. [[paper]](/publication/indoor-cooperative-perception)

See the [Publications](/publications/) page and my [Google Scholar profile](https://scholar.google.com/citations?user=ViXAd2YAAAAJ&hl=en) for the full list.

Contact
======

Email: [minghao.ning@uwaterloo.ca](mailto:minghao.ning@uwaterloo.ca) &middot; [GitHub](https://github.com/NingMingHao) &middot; [Google Scholar](https://scholar.google.com/citations?user=ViXAd2YAAAAJ&hl=en)

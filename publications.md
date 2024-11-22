---
layout: page
title: Publications
---
You can also browse my [Google Scholar profile](https://scholar.google.com/citations?user=x7ilUIsAAAAJ&hl=en&oi=ao).

I have collaborated with researchers from following institutes.
- ###### Vienna University of Technology, Vienna, Austria
- ###### Technical University of Madrid, Madrid, Spain
- ###### University of Melbourne, Victoria, Australia

<hr>
<div class="distribution-map">
    <img src="/assets/img/map.png" alt="" />
    
    <!-- Austria-->
    <button class="map-point" style="top:38%;left:52%">
        <div class="content">
            <div class="institute-logo">
              <img src="/assets/img/tu-wien-logo.svg" alt="">
            </div>
        </div>
    </button>

    <!-- Spain-->
    <button class="map-point" style="top:42%;left:46%">
        <div class="content">
            <div class="institute-logo">
              <img src="/assets/img/upm-logo.jpg" alt="" style="width: 180%">
            </div>
        </div>
    </button>

    <!-- Australia-->
    <button class="map-point" style="top:80%;left: 83.5%">
        <div class="content">
            <div class="institute-logo">
              <img src="/assets/img/unimelb-logo.svg" alt="" style="width: 60%">
            </div>
        </div>
    </button>
</div>
<style>
  .img-point {
    height: 50%;
    width: 50%;
  }
  .outer {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .distribution-map {
    position: relative;
    width: 100%;
    padding: 20px;
    box-sizing: border-box;
    margin: 0 auto;
  }
  .institute-logo {
    position: relative;
    width: 100%;
    padding: 40px;
    box-sizing: border-box;
    margin: 5px auto;
  }
  .distribution-map > img {
    width: 100%;
    position: relative;
    margin: 0;
    padding: 0;
  }
  .distribution-map .map-point {
    cursor: pointer;
    outline: none;
    z-index: 0;
    position: absolute;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    filter: progid:DXImageTransform.Microsoft.Alpha(Opacity=80);
    opacity: 0.8;
    transform: translate(-50%, -50%);
    -moz-transition: opacity 0.25s ease-in-out 0.25s, width 0.25s ease-in-out 0.25s, height 0.25s ease-in-out 0.25s, z-index 0.25s ease-in-out 0.25s;
    -o-transition: opacity 0.25s ease-in-out 0.25s, width 0.25s ease-in-out 0.25s, height 0.25s ease-in-out 0.25s, z-index 0.25s ease-in-out 0.25s;
    -webkit-transition: opacity 0.25s ease-in-out, width 0.25s ease-in-out, height 0.25s ease-in-out, z-index 0.25s ease-in-out;
    -webkit-transition-delay: 0.25s, 0.25s, 0.25s, 0.25s;
    transition: opacity 0.25s ease-in-out 0.25s, width 0.25s ease-in-out 0.25s, height 0.25s ease-in-out 0.25s, z-index 0.25s ease-in-out 0.25s;
    background: rgb(255,255,255);
    border: 8px solid #000000;
  }
  .distribution-map .map-point .content {
    filter: progid:DXImageTransform.Microsoft.Alpha(Opacity=0);
    opacity: 0;
    transition: opacity 0.25s ease-in-out;
    width: 100%;
    height: 100%;
    left: 50%;
    transform: translateX(-50%);
    overflow: overlay;
  }
  .distribution-map .map-point:active, .distribution-map .map-point:focus {
    margin: 0;
    padding: 0;
    filter: progid:DXImageTransform.Microsoft.Alpha(enabled=false);
    opacity: 1;
    width: 300px;
    height: 220px;
    color: #e5e5e5;
    z-index: 1;
    transition: opacity 0.25s ease-in-out, width 0.25s ease-in-out, height 0.25s ease-in-out;
  }
  .distribution-map .map-point:active .content, .distribution-map .map-point:focus .content {
    filter: progid:DXImageTransform.Microsoft.Alpha(enabled=false);
    opacity: 1;
    -moz-transition: opacity 0.25s ease-in-out 0.25s, height 0.25s ease-in-out, overflow 0.25s ease-in-out;
    -o-transition: opacity 0.25s ease-in-out 0.25s, height 0.25s ease-in-out, overflow 0.25s ease-in-out;
    -webkit-transition: opacity 0.25s ease-in-out, height 0.25s ease-in-out, overflow 0.25s ease-in-out;
    -webkit-transition-delay: 0.25s, 0s, 0s;
    transition: opacity 0.25s ease-in-out 0.25s, height 0.25s ease-in-out, overflow 0.25s ease-in-out;
    overflow: hidden;
  }
  .distribution-map .map-point:active .content a:hover, .distribution-map .map-point:active .content a:active, .distribution-map .map-point:focus .content a:hover, .distribution-map .map-point:focus .content a:active {
    color: #afe1fa;
  }
    .description {
    max-width: 600px;
    margin: 0 auto;
    color: rgba(229, 229, 229, 0.7);
  }
  
  div, img, footer {
    position: relative;
    box-sizing: border-box;
  }
</style>
<hr>

- **2024**
    <div class="card padded-div">
        <code style="font-size: 0.8em; color: black; background-color: white; font-family: sans-serif">
            <strong>T. B. Hewage</strong>, S. Ilager, M. A. Rodriguez, and R. Buyya, "A Framework for Carbon-aware Real-Time Workload Management in Clouds using Renewables-driven Cores"
        </code>
        <div class="padded-div">
            <span class="artifact paper"><a href="https://arxiv.org/abs/2411.07628">Paper</a></span>
            <span class="artifact paper"><a href="https://github.com/tharindu-b-hewage/openstack-gc">Code</a></span>
            <span class="label venue">Arxiv pre-print</span>
            <span class="label year">2024</span>
        </div>
    </div>

- **2023**
    <div class="card padded-div">
        <code style="font-size: 0.8em; color: black; background-color: white; font-family: sans-serif">
            <strong>T. B. Hewage</strong>, S. Ilager, M. A. Rodriguez, P. Arroba and R. Buyya, "DEMOTS: A Decentralized Task Scheduling Algorithm for Micro-Clouds with Dynamic Power-Budgets"
        </code>
        <div class="padded-div">
            <span class="artifact paper"><a href="https://ieeexplore.ieee.org/document/10255015">Paper</a></span>
            <span class="label venue">IEEE 16th International Conference on Cloud Computing (CLOUD)</span>
            <span class="label year">2023</span>
            <span class="label location">Chicago, IL, USA</span>
        </div>
    </div>
    <div class="card padded-div">
        <code style="font-size: 0.8em; color: black; background-color: white; font-family: sans-serif">
            <strong>T. B. Hewage</strong>, S. Ilager, M. A. Rodriguez, and R. Buyya, "CloudSim express: A novel framework for rapid low code simulation of cloud computing environments"
        </code>
        <div class="padded-div">
            <span class="artifact paper"><a href="https://onlinelibrary.wiley.com/doi/10.1002/spe.3290">Paper</a></span>
            <span class="artifact paper"><a href="https://github.com/Cloudslab/cloudsim-express">Code</a></span>
            <span class="label venue">Software: Practice and Experience</span>
            <span class="label year">2023</span>
            <span class="label location">Vol.: 54, Issue: 3</span>
        </div>
    </div>

<style>
    .label {
        color: white;
        padding: 8px;
        background: inherit;
        font-family: monospace;
        font-size: 0.6em;
        border-radius: 20px;
    }
    .artifact {
        color: blue;
        padding: 8px;
        padding-left: 10px;
        padding-right: 10px;
        font-family: monospace;
        font-size: 0.6em;
        font-weight: bold;
        outline: black solid 0.1em;
    }
    .artifact:hover {
      font-size: 0.8em;
      outline-width: 0.2em;  
      background-color:white;
      transition: 0.1s;
    }
    .venue {background-color: rgba(6,23,114,0.89);} /* Green */
    .year {background-color: rgba(6,23,114,0.89);} /* Blue */
    .location {background-color: rgba(6,23,114,0.89);} /* Blue */
    .paper {background-color: khaki;} /* Blue */
    .code {background-color: lightseagreen;} /* Blue */

    .card {
      box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
      transition: 2s;
      border-radius: 5px; /* 5px rounded corners */
      text-align: justify;
    }
    /* On mouse-over, add a deeper shadow */
    .card:hover {
      box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
    }
    .padded-div {
      padding: 10px;
    }
    .parent-div {
      display: flex;
      flex-wrap: wrap;
      /* for horizontal aligning of child divs */
      justify-content: center;
      /* for vertical aligning */
      align-items: center;
    }
    
    .child-div {
      width: /* yoursize for each div */
      ;
    }
</style>

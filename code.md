---
layout: page
title: CODE
---
<div class="v-line">
    <div class="entry card">
        <div class="make-center"><strong><a href="https://github.com/crunchycookie/core-power-mgt">Openstack-GC: Carbon-aware computing for Real-time VMs with Openstack</a></strong></div>
        <div class="typewriter">
            <p>
                A framework to harness intermittent Renewable energy for real-time VMs in cloud datacenters, designed to be used with commodity hardware.
            </p>
        </div>
    </div>
    <div class="entry card">
        <div class="make-center"><strong><a href="https://github.com/crunchycookie/core-power-mgt">A CPU Core Power Management Service</a></strong></div>
        <div class="typewriter">
            <p>
                A Golang service wrapping the Intel Power Optimization Library to manage per-core power features of intel processors. It enables integration
                of hardware power management with the cloud orchestration layer.
            </p>
        </div>
    </div>
    <div class="entry card">
        <div class="make-center"><strong><a href="https://github.com/crunchycookie/orion">Orion: A distributed computing framework</a></strong></div>
        <div class="typewriter">
            <p>
                Orion is an API-driven, java-based distributed computing framework. It provides task submissions through
                REST-apis, executes using a worker pool, and provides a monitoring app to track task status. Have a look
                at the <a href="https://towardsdatascience.com/lets-build-a-simple-distributed-computing-system-for-modern-cloud-part-one-e2b745126211">Orion article published in Towards Data Science</a>.
            </p>
        </div>
    </div>
    <div class="entry card">
        <div class="make-center"><strong><a href="https://github.com/tharindu-b-hewage/deep-video-activity-recognition">Real-time detection of activities in a video feed</a></strong></div>
        <div class="typewriter">
            <p>
                A system written in Python that uses a deep 3D convolutional model to classify actions in the video feed.
            </p>
        </div>
    </div>
    <div class="entry card">
        <div class="make-center"><strong><a href="https://github.com/tharindu-b-hewage/deep-video-detection-pizza">Real-time content-detection for satellite video streams</a></strong></div>
        <div class="typewriter">
            <p>
                A system written in C++ that consumes a satellite video stream, which leverage inferring of a stacked
                multi-samples through a deep neural network to detect targeted content. Image processing is handled via
                OpenCV and model is trained and server via Caffe.
            </p>
        </div>
    </div>
</div>

<style>
    .entry {
        display: grid;
        row-gap: 2px;
        grid-template-rows: 0.3em 1fr;
        padding: 5px;
    }
    .v-line {
         border-left: thick solid rgba(0,0,0,0.25);
         margin-bottom: 30px; 
    }
    .card {
        outline: black;
        left: 10px;
        padding-left: 5px;
    }
    .img {
        width:100%;
        height:100%;
        object-fit:contain;
    }
    .make-center {
        text-align: left;
    }
    .typewriter {
        font-family: monospace;
        font-size: 0.8em;
        text-align: justify;
    }
</style>
---
layout: page
title: Course Videos
permalink: /videos/
---

# SYDE 312 Course Videos

Welcome to the video repository for SYDE 312. Here you'll find recordings of all course lectures and tutorials.

## How to Use This Page

- Videos are organized chronologically
- Click on any video to start watching
- You can use the video controls to adjust playback speed, quality, and volume

## Local Video Recordings

<div class="video-entry">
  <h3>Team 2Blue1Brown - Presentation</h3>
  <video width="100%" controls>
    <source src="{{ site.baseurl }}/assets/videos/2blue1brown.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div class="video-entry">
  <h3>Team 2Blue1Brown - Q&A</h3>
  <video width="100%" controls>
    <source src="{{ site.baseurl }}/assets/videos/2blue-1brown-qa.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div class="video-entry">
  <h3>Team Span Fans - Q&A</h3>
  <video width="100%" controls>
    <source src="{{ site.baseurl }}/assets/videos/span-fans-qa.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

## YouTube Videos

<div class="video-entry">
  <h3>Team Span Fans - Presentation</h3>
  <div class="video-container">
    <iframe width="100%" height="480" src="https://www.youtube.com/embed/6arxFCaueWc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>

<div class="video-entry">
  <h3>Team Eigenforce - Presentation + Q&A</h3>
  <div class="video-container">
    <iframe width="100%" height="480" src="https://www.youtube.com/embed/xetDZBtKv6g" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>

<style>
.video-entry {
  margin-bottom: 2em;
  padding: 1em;
  border-radius: 8px;
  background-color: #f8f9fa;
}

.video-entry h3 {
  margin-bottom: 0.5em;
}

video {
  max-width: 100%;
  margin-top: 0.5em;
  border-radius: 4px;
}

.video-container {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 aspect ratio */
  height: 0;
  overflow: hidden;
  margin-top: 0.5em;
  border-radius: 4px;
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border-radius: 4px;
}
</style> 
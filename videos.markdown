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

## Video List

{% for video in site.static_files %}
  {% if video.path contains 'assets/videos' %}
    <div class="video-entry">
      <h3>{{ video.basename }}</h3>
      <video width="100%" controls>
        <source src="{{ site.baseurl }}/assets/videos/{{ video.basename }}.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  {% endif %}
{% endfor %}

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
</style> 
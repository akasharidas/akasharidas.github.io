---
layout: page
title: Projects
permalink: /projects/
description:
nav: true
nav_order: 1
---

<h2>AI Art</h2>
Some artwork I(?) created with generative AI tools like <a href="https://github.com/alembics/disco-diffusion">Disco Diffusion</a> and <a href="https://github.com/mikaelalafriz/lucid-sonic-dreams">Lucid Sonic Dreams</a> plus Photoshop. Work in progress...
<br>
<br>

<div class="card mt-3">
<div style="margin-top:3%; margin-left:3%; margin-right:3%">
    <figure>
      <img class="img-fluid z-depth-1 rounded" src="{{site.baseurl}}/assets/img/cafe_upscaled.png">
      <figcaption>Mystical coffee shop</figcaption>
    </figure>
</div>
</div>
<br>

<div class="card mt-3">
<div style="margin-top:3%; margin-left:3%; margin-right:3%">
    <figure>
      <img class="img-fluid z-depth-1 rounded" src="{{site.baseurl}}/assets/img/arabia_upscaled.png">
      <figcaption>Ancient arabian city surrounded by desert and mountains</figcaption>
    </figure>
</div>
</div>
<br>

<div class="card mt-3">
<div style="margin-top:3%; margin-left:3%; margin-right:3%">
    <figure>
      <img class="img-fluid z-depth-1 rounded" src="{{site.baseurl}}/assets/img/toronto_upscaled.png">
      <figcaption>The Toronto skyline in a chillwave/futuresynth style</figcaption>
    </figure>
</div>
</div>
<br>

<div class="card mt-3">
<div style="margin-top:3%; margin-left:3%; margin-right:3%">
    <figure>
      <center>
        <video class="img-fluid z-depth-1 rounded" id="videoElement" autoplay="autoplay" loop=true muted width="50%" >
          <source src="{{site.baseurl}}/assets/vid/to_the_moon.mp4" type="video/mp4">
        </video>
      </center>
      <figcaption>Psychedelic visuals synchronized with music, made by making audio-driven pertubations to the latent space of a pretrained StyleGAN</figcaption>
    </figure>
</div>
</div>
<br>

<script type="text/javascript">
    (function(window) {
        function setupVideo()
        {
            var v = document.getElementById('videoElement');
            v.addEventListener('mouseover', function() { this.controls = true; }, false);
            v.addEventListener('mouseout', function() { this.controls = false; }, false);
        }

        window.addEventListener('load', setupVideo, false);
    })(window);
</script>


<!-- ----------------------------------------------------------------------------- -->
<br>
<hr>
<br>
<!-- ----------------------------------------------------------------------------- -->

<h2>I did \(x\) to learn \(y\)...</h2>
<p>According to the <a href="https://towardsdatascience.com/want-a-data-science-job-use-the-weekend-project-principle-to-get-it-a86ba2da514f">Weekend Project Principle</a>, a great way to build a broad skillset is to work on small-scale self-defined projects related to one's interests, usually over short timeframes such as a weekend. In my spare time, I enjoy tinkering with new tools and technologies, and aim to build a minimal working prototype \(x\) with the goal of learning \(y\).</p>
<br>


<div class="card mt-3">
<div class="p-3">
<div>
  <div class="row">
  <div class="col-sm-4">
    <video class="img-fluid z-depth-1 rounded" autoplay="autoplay" loop=true muted>
      <source src="{{site.baseurl}}/assets/vid/gravity.mp4" type="video/mp4">
    </video>
  </div>
  <div class="col-sm-8">
    I wrote a 2D Newtonian gravity simulator, to learn basic numerical simulation and how to use JIT compilation to speed up Python code.
  </div>
</div>
</div>
</div>
</div>
<br>


<div class="card mt-3">
<div class="p-3">
<div>
  <div class="row">
  <div class="col-sm-4">
    <img class="img-fluid z-depth-1 rounded" src="{{site.baseurl}}/assets/img/bar_chart.png">
  </div>
  <div class="col-sm-8">
    I recreated some of the plots on <a href="https://www.datawrapper.de/">datawrapper.de</a>, to learn what it takes to make professional publication-quality charts using everyday open-source plotting tools in Python.
  </div>
</div>
</div>
</div>
</div>
<br>


<div class="card mt-3">
<div class="p-3">
<div>
  <div class="row">
  <div class="col-sm-4">
    <img class="img-fluid z-depth-1 rounded" src="{{site.baseurl}}/assets/img/simple_scene.png">
  </div>
  <div class="col-sm-8">
    I followed the <a href="https://raytracing.github.io/books/RayTracingInOneWeekend.html">Ray Tracing in One Weekend book</a>, to learn the basics of ray-traced rendering and pick up C++.
  </div>
</div>
</div>
</div>
</div>
<br>





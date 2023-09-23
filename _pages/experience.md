---
layout: page
permalink: /experience/
title: Experience
description:
nav: true
nav_order: 1
years: [2022, 2021]
---

<div class="card mt-3">
<div class="p-3">
<h2>Education</h2>
<div class="publications">
    <h2 class="year">2022 - 2023</h2>
    <b>University of Toronto 🇨🇦</b> <br>
    MSc. in Applied Computing (Concentration: Artificial Intelligence) <br>
    <b>GPA</b>: 4.0 / 4.0  

    <h2 class="year">2017 - 2022</h2>
    <b>Indian Institute of Technology Madras 🇮🇳</b> <br>
    Interdisciplinary Dual Degree in Aerospace Engineering and Data Science <br>
    <b>CGPA</b>: 9.26 / 10.00, 
    <a href="{{site.baseurl}}/assets/pdf/DDP.pdf" style="border: 1px solid black; padding: 5px 20px;" class="btn btn-sm z-depth-1" role="button">Thesis</a>

</div>
</div>
</div>
<br>


<div class="card mt-3">
<div class="p-3">
<h2>Experience</h2>
<div class="publications">
    <h2 class="year">May 2023 - Dec 2023</h2>
    <b>Advanced Micro Devices (AMD) 📱🎮</b> <br>
    Applied Research Intern, Machine Learning and 3D Computer Vision<br>
        <small>
        <ul>
            <li>Built an automatic system to produce high-fidelity animatable 3D human avatars from a consumer laptop webcam. </li>
            <li>Developed a novel method based on GANs for photorealistic texture synthesis, 3D morphable models, landmark detection, face recognition embeddings and differentiable rendering in PyTorch3D. </li>
            <li>Achieved ~45% higher perceptual quality and ~25% better lighting symmetry compared to existing literature when applied to low-quality webcams, while also satisfying latency constraints for edge devices. </li>
        </ul>
        </small>

    <h2 class="year">Jul 2020 - Jul 2022</h2>
    <b>Indian Institute of Technology Madras 🦌</b> <br>
    Student Researcher, Deep Learning for Fluid Mechanics and CFD<br>
        <small>
        <ul>
            <li>Worked on developing fast and accurate AI algorithms for fluid simulations. </li>
            <li>Trained a ConvNet with physics-based components to correct errors in low-precision simulations. </li>
            <li>Published two first-author research papers and presented at a conference. </li>
            <li>Demonstrated improved computational efficiency and ~45% error reduction: [<a href="https://www.sciencedirect.com/science/article/pii/S2666352X22000243">Paper</a>] </li>
        </ul>
        </small>

    <h2 class="year">Summer 2021</h2>
    <b>Anheuser-Busch InBev 🍺</b> <br>
    Data Scientist Intern<br>
        <small>
        <ul>
            <li>Interned in the marketing analytics team at the <a href="https://www.ab-inbev.com/our-brands/">world's largest beer company</a>.</li>
            <li>Improved data-driven allocation of marketing resources across global markets and brands, resulting in an estimated 7% increase in marketing net revenue. </li>
            <li>Automated the team's data processing pipeline using Python (previously done manually in Excel). </li>
            <li>Received a job offer for showing excellent performance. </li>
        </ul>
        </small>

    <h2 class="year">Summer 2020</h2>
    <b>unMazer.ai 📈</b> <br>
    Intern, Computer Vision and Product Development<br>
        <small>
        <ul>
            <li>Event detection using a custom CNN+LSTM network and object detection using YOLOv4 in CCTV road footage. </li>
            <li>Built a procotoring tool to detect cheating in online exams using eye tracking models and OpenCV. </li>
            <li>Instrumental in building three AI-based minimum viable products (MVPs) during the company’s initial phase. </li>
            <li>Blog post:  <a href="https://medium.com/calam-in/leveraging-ai-to-reduce-road-fatalities-a10eec2e505c"> [Leveraging AI to Reduce Road Fatalities]</a> </li>
        </ul>
        </small>


    <h2 class="year">Winter 2018</h2>
    <b>The ePlane Company  🛩️</b> <br>
    Design Intern<br>
        <small>
        <ul>
            <li>Worked at an <a href="https://timesofindia.indiatimes.com/city/chennai/coming-soon-from-iit-madras-stable-flying-taxis/articleshow/82058951.cms">IIT Madras incubated start-up</a> building all-electric aircraft. </li>
            <li>Worked on the design and aerodynamic analysis of an electric VTOL aircraft prototype using CFD. </li>
        </ul>
        </small>

        
</div>
</div>
</div>
<br>


<div class="card mt-3">
<div class="p-3">
<h2>Research Publications</h2>

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
</div>
</div>
<br>


<div class="card mt-3">
<div class="p-3">
<h2>Teaching</h2>
<div class="publications">
    <h2 class="year">Fall 2022 and Winter 2022</h2>
    <b>Introduction to Computer Programming</b>, University of Toronto <br>
    Teaching Assistant <br>

    <h2 class="year">Fall 2021</h2>
    <b>Machine Intelligence and Brain Research</b>, <a href="https://ccbr.iitmadras.in/">Center for Computational Brain Research</a><br>
    Teaching Assistant <br>
    Topics: Neuroscience, Vision, Audition, Natural Language, Reinforcement Learning

    <h2 class="year">Fall 2021</h2>
    <b>Propulsion 1</b>, Undergrad course at IIT Madras <br>
    Head Teaching Assistant <br>

    
</div>
</div>
</div>
<br>


<div class="card mt-3">
<div class="p-3">
<h2>Miscellaneous Achievements</h2>
<div class="publications">
    <h2 class="year">Jan 2018</h2>
    <b>Guest of the Prime Minister at the Republic Day Parade</b><br>
    Awarded for achieving a top 3 score in the national higher secondary exam <br>

    <h2 class="year">May 2017</h2>
    <b>Joint Entrance Examination</b> <br>
    Ranked in the top 0.2% (amongst 1,200,000 candidates) in India’s toughest engineering entrance exam <br>

    
</div>
</div>
</div>
<br>
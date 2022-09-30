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
    <h2 class="year">2022 - present</h2>
    <b>University of Toronto 🇨🇦</b> <br>
    MSc. in Applied Computing (Concentration: Artificial Intelligence) <br>
    <!-- <b>CGPA</b>: 9.27 / 10.00   -->

    <h2 class="year">2017 - 2022</h2>
    <b>Indian Institute of Technology Madras 🇮🇳</b> <br>
    Interdisciplinary Dual Degree in Aerospace Engineering and Data Science <br>
    <b>CGPA</b>: 9.26 / 10.00  

</div>
</div>
</div>
<br>



<div class="card mt-3">
<div class="p-3">
<h2>Research</h2>

While at IIT Madras, I worked extensively with <a href="https://home.iitm.ac.in/nrv/">Prof. Nagabhushana Rao Vadlamani</a> and <a href="https://yukiminamoto.com/">Prof. Yuki Minamoto</a> on machine learning for fluid mechanics and computational fluid dynamics (CFD). 

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
<h2>Internships</h2>
<div class="publications">
    <h2 class="year">Summer 2021</h2>
    <b>Anheuser-Busch InBev 🍺🍻</b> <br>
    Data Scientist <br>
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
    Data Scientist and Web Developer<br>
        <small>
        <ul>
            <li>Built a deep learning based tool to analyze, detect and flag various features in CCTV footage of road traffic. </li>
            <li>Contributed significantly towards building three company products in their early stage. </li>
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
<h2>Teaching</h2>
<div class="publications">
    <h2 class="year">Fall 2022</h2>
    <b>Introduction to Computer Programming</b>, Undergrad course at University of Toronto <br>
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
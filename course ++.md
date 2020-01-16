---
layout: page
title: Course ++
permalink: /Coursepp/
---

<div style="width:100%; float: left">
    <div class="Course-plusplus-gallary">
        <h2>Courses from different Universities</h2>
        {% for resource in site.data.coursepp.Courses from different Universities %}
        <div class="Coursepp-materual--image-cover-container">
            <img src="{{ resource.pic | prepend: site.baseurl }}" class="Course-pp--image-cover">
            <p><a href="{{resource.address}}">{{resource.name}}</a></p>
        </div>
        {% endfor %}
<br><br><br><br><br><br><br><br><br><br><br><br>

<!-- <center><h1>MIT Computer Systems Security</h1></center>
<h3><bold>Lecture 1:</bold> Introduction, Threat Models</h3> -->
<!-- <iframe src="" height=325 width=545 frameborder=0></iframe> -->

<!-- <video width="400" controls>
        <source src="https://www.youtube.com/v/GqmQg-cszw4" type="video/mp4">
        Your browser does not support HTML5 video.
      </video> -->

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/GqmQg-cszw4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<!-- <div style="width: 100%;">    <div style="width: 100%; padding-top: 56.25%; position: relative;">        <iframe style="position: absolute; width: 100%; height: 100%; top: 0; right: 0; border: none" src="https://www.dideo.ir/pre_embed/v/yt/GqmQg-cszw4"                allowFullScreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  allow="accelerometer; gyroscope; picture-in-picture; autoplay; fullscreen; encrypted-media" frameborder="0"></iframe></div></div> -->
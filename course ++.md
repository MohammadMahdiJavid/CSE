---
layout: page
title: Course ++
permalink: /Coursepp/
---

<div style="width:100%; float: left">
    <div class="Course-plusplus-gallary">
        <h2>Courses from different Universities</h2>
        {% for resource in site.data.coursepp.Universities %}
        <div class="Coursepp--image-cover-container">
            <img src="{{ resource.pic | prepend: site.baseurl }}" class="Course-pp--image-cover">
            <p text-align:center><a href="{{resource.address}}">{{resource.name}}</a></p>
        </div>
        {% endfor %}
<br><br><br><br><br><br><br><br><br><br><br><br>

<br><br><br>
<table>
  <tr>
    <td>Cryptographic libraries:</td>
    <td><a href="https://github.com/google/tink">1- tink by Google</a></td>
    <td><a href="http://www.gnupg.org/gpgme.html">2- GPGME by GnuPG</a></td>
    <td><a href="http://www.openssl.org/">3- OpenSSL</a></td>
    <td><a href="http://nacl.cace-project.eu/">4- NaCl: Networking and Cryptography library by Tanja Lange and Daniel J. Bernstein.</a></td>
  </tr>
</table>

<!-- <center><h1>MIT Computer Systems Security</h1></center>
<h3><bold>Lecture 1:</bold> Introduction, Threat Models</h3> -->
<!-- <iframe src="" height=325 width=545 frameborder=0></iframe> -->

<!-- <video width="400" controls>
        <source src="https://www.youtube.com/v/GqmQg-cszw4" type="video/mp4">
        Your browser does not support HTML5 video.
      </video> -->

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/GqmQg-cszw4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<!-- <div style="width: 100%;">    <div style="width: 100%; padding-top: 56.25%; position: relative;">        <iframe style="position: absolute; width: 100%; height: 100%; top: 0; right: 0; border: none" src="https://www.dideo.ir/pre_embed/v/yt/GqmQg-cszw4"                allowFullScreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  allow="accelerometer; gyroscope; picture-in-picture; autoplay; fullscreen; encrypted-media" frameborder="0"></iframe></div></div> -->
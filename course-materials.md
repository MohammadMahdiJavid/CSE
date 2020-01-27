---
layout: page
title: Course Materials
permalink: /course-materials/
---












<div style="width:100%; float: left">
    <div class="Course-material-pic-gallary">
        <h2>    Main Books</h2>
        {% for resource in site.data.course-material.main_resources %}
        <div class="Course-materual--image-cover-container">
            <img src="{{ resource.pic | prepend: site.baseurl }}" class="Course-material--image-cover">
            <p><a href="{{resource.address}}">{{resource.name}}</a></p>
        </div>
        {% endfor %}
<br><br><br><br><br><br><br><br><br><br><br><br>
        <h2>MIT Reference materials</h2>
        {% for resource in site.data.course-material.MIT_Reference materials %}
        <div class="Course-materual--image-cover-container">
            <img src="{{ resource.pic | prepend: site.baseurl }}" class="Course-material--image-cover">
            <p><a href="{{resource.address}}">{{resource.name}}</a></p>
        </div>
        {% endfor %}
<br><br><br><br><br><br><br><br><br><br><br><br><br>
    </div>
</div>


















































































<!-- 


<p><big><big><big>Network security Books:</big></big></big></p>

<br>


<p><big><font color="red"> 1- Cryptography and Network Security: Principles and Practice Books by William Stallings </font><big>
<br><br>

<a href="https://github.com/mahdi-javid/computer-systems-security/raw/master/download/7th%20Edition-cryptography%20and%20network%20security%20stallings.pdf">
<img border="0" alt="Cryptography and Network Security: Principles and Practice (7th Edition) by William Stallings" src="https://github.com/mahdi-javid/computer-systems-security/blob/master/download/Cryptography%20and%20Network%20Security%20Principles%20and%20Practice%20(7th%20Edition)%20by%20William%20Stallings.jpg?raw=true" width="180" height="250" hspace="50">
</a>

Cryptography and Network Security: Principles and Practice (6th Edition) by William Stallings 
<a  href="https://github.com/mahdi-javid/computer-systems-security/raw/master/download/(DR.zeinab%20Movahedi)%5BWilliam_Stallings%5D_Cryptography_and_Network_Security.pdf">
<img border="0" alt="Cryptography and Network Security: Principles and Practice (6th Edition) by William Stallings" src="https://github.com/mahdi-javid/computer-systems-security/blob/master/download/Cryptography%20and%20Network%20Security%20Principles%20and%20Practice%20(6th%20Edition)%20by%20William%20Stallings.jpg?raw=true" width="180" height="250" hspace="50">
</a>


<a  href="https://github.com/mahdi-javid/computer-systems-security/raw/master/download/(DR.zeinab%20Movahedi)%20Cryptography%20and%20Network%20Security%20Principles%20and%20Practice%20Fifth%20Edition%20by%20William%20Stallings.pdf">
<img border="0" alt="Cryptography and Network Security Principles and Practice (5th Edition) by William Stallings" src="https://github.com/mahdi-javid/computer-systems-security/blob/master/download/Cryptography%20and%20Network%20Security%20Principles%20and%20Practice%20(5th%20Edition)%20by%20William%20Stallings.jpg?raw=true" width="180" height="250" hspace="50">
</a>


<br><br><br><br>
<p hspace="50"><font color="red">2- Network Security Essentials: Applications and Standards Books by William Stallings</font><br></p>
<a  href="https://github.com/mahdi-javid/computer-systems-security/raw/master/download/(DR.zeinab%20Movahedi)%5BWilliam_Stallings%5D_Network_Security_Essentials__A.pdf">
<img border="0" alt="Network Security Essentials: Applications and Standards (4thEdition) by William Stallings" src="https://github.com/mahdi-javid/computer-systems-security/blob/master/download/Network%20Security%20Essentials%20Applications%20and%20Standards%20(4thEdition)%20by%20William%20Stallings.jpg?raw=true" width="180" height="250" hspace="50">
</a>




<br><br><br><br>
<p hspace="50"><font color="red">3- Computer Networking: A Top-Down Approach Book by Jim Kurose</font><br></p>
<a  href="https://github.com/mahdi-javid/computer-systems-security/raw/master/download/fqo47.Computer.Networking.A.TopDown.Approach.6th.Edition.pdf">
<img border="0" alt="Computer Networking: A Top-Down Approach Book by Jim Kurose" src="https://github.com/mahdi-javid/computer-systems-security/blob/master/download/computernetworkingatop-downapproach6thedition-1-638.jpg?raw=true" width="180" height="250" hspace="50">
</a>



<br><br>

-->
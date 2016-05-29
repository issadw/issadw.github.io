---
layout: post
title: Introduction
---

<i class="fa fa-home fa-lg"></i><b> Location:</b> Hanoi University of Science and Technology (HUST), Hanoi.

<i class="fa fa-clock-o fa-lg"></i><b> Time:</b>  4-5 August 2016

<i class="fa fa-newspaper-o fa-lg"></i><b> Content:</b> IoT  Systems, Services and Analytics for Developing Worlds

<hr>
<div class="w3-content" style="max-width:1000px;position:relative; display: block; margin-left: auto; margin-right: auto; text-align: center">

<div class="w3-display-container mySlides">
  <img src="http://script.tugo.com.vn/wp-content/uploads/H%C3%80-N%E1%BB%98I-1.jpg" style="width:100%">
  <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black">
    Ha Noi, VietNam
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="https://fbcdn-sphotos-b-a.akamaihd.net/hphotos-ak-xtp1/v/t1.0-9/11892176_594642940673733_3747139679302136741_n.jpg?oh=df3a4dc33dc406420eb2dc3a1b9bd61f&oe=57E3CD96&__gda__=1473659808_f9babe3516bf1d0b613b91d44e5b9454" style="width:100%">
  <div class="w3-display-bottomright w3-large w3-container w3-padding-16 w3-black">
    Hanoi University of Science and Technology
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="https://scontent-sjc2-1.xx.fbcdn.net/v/t1.0-9/11406960_570955123042515_678234339582409481_n.jpg?oh=8d3b0e22b26263e42920111e33fab3c5&oe=57E2FD47" style="width:100%">
  <div class="w3-display-bottomright w3-large w3-container w3-padding-16 w3-black">
    Hanoi University of Science and Technology
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="http://lumi.vn/Cms_Data/Contents/Lumi/Media/Images/Internet-of-thing.png" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-black">
    Internet of Things 01
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="http://lumi.vn/Cms_Data/Contents/Lumi/Media/Images/Internet-of-thing.png" style="width:100%">
  <div class="w3-display-topright w3-large w3-container w3-padding-16 w3-black">
    Internet of Things 02
  </div>
</div>

<a class="w3-btn-floating w3-hover-dark-grey" style="position:absolute;top:45%;left:0" onclick="plusDivs(-1)">❮</a>
<a class="w3-btn-floating w3-hover-dark-grey" style="position:absolute;top:45%;right:0" onclick="plusDivs(1)">❯</a>

</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>
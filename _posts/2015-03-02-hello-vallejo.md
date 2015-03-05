---
layout:  post
title:   "Code Across"
date:    2015-03-02 00:00:00
preview-image: http://placekitten.com/g/220/220
snippet: What we learned and saw at CodeAcross.
home-image: http://placekitten.com/g/640/320
has_carousel: true
---

<img class="home-img" src="{{ page.home-image | prepend: site.baseurl }}">

This is the descriptive narrative of the event.

<h2>What We Did.</h2>

This is the descriptive narrative of the exercises people did. Some general photos of the event below.

<div class="image-container">
  <span><img class="img-cont-image" src="http://placekitten.com/g/240/240"></span>
  <span><img class="img-cont-image" src="http://placekitten.com/g/240/240"></span>
</div>

<br/>

<h2>Where Do You Stand?</h2>

<div><img class="carousel-image" src="http://placekitten.com/g/640/320"></div>

<br/>

<h2>What If...?</h2>

<div class="carousel">
  <div><img class="carousel-image" src="http://placekitten.com/g/360/320"></div>
  <div><img class="carousel-image" src="http://placekitten.com/g/360/360"></div>
  <div><img class="carousel-image" src="http://placekitten.com/g/360/310"></div>
  <div><img class="carousel-image" src="http://placekitten.com/g/360/390"></div>
</div>

<script>
$(document).ready(function(){
  $('.carousel').slick({
    slidesToShow: 1,
    dots: true,
    accessibility: true
  });
});
</script>

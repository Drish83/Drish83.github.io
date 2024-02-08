---
title: "Digital Presenter"
excerpt: "Web Application to make your own digital avatar presenter in some minutes!<br/><img src='/images/SMC_2.png'>"
collection: portfolio
---

## Objective
Nowadays, it is hard to be present at everywhere. To solve this we wanted to create an application to allow individuals to create an digital presetner of themselves but just providing their script and image. 

## Accomplishments 
* Implemented Bark TTS model to convert script to audio with multilanguage capability. 
* Implemented FOMM to convert image to video
* Implement Wav2Lip for lip syncing
* Implemented GFPGAN to improve the video quality. 
* Used Gradio to make a simple web interface 
* Ran experiments to check the trade off between the quality of video and the computation time

## Results

Got an A+ for the project


<div class="slider">
  <img src="/images/SMC_1.jpg" style="width:100%">
  <img src="/images/SMC_2.png" style="width:100%">
  <!-- Add as many images as you need -->
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("slider");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  slides[slideIndex-1].style.display = "block";  
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>
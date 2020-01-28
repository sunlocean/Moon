---
layout: page
title: Wir
tags: [moon]
date:2019-05-29
comments: false
---
    
<!--<center><a href="http://taylantatli.github.io/Moon"><b>Moon</b></a> is a minimal, one column jekyll theme.</center>-->

## Sun L'Ocean
Wir sind Sun L’Ocean e.V. ein kleines Projekt mit großen Zielen. Wir möchten mit einfachen Mitteln dafür sorgen, dass nicht nur du die Sommertage am Strand genießt und mit schützender Sonnencreme versorgt bist sondern auch, dass das Meer dabei den geringst möglichen Schaden nimmt.

## Kontakt
Erreichen kannst du uns bei <a href="https://www.instagram.com/sun_locean/"><b>Instagram</b></a> und <a href="https://www.facebook.com/Sun-LOcean-236116057317752/"><b>Facebook</b></a>, denn wir sind natürlich am Puls der Zeit. 
Wir freuen uns aber auch über eine Email an teamsunlocean@gmail.com und im Impressum findest du eine Adresse für deine Brieftaube.

<a href="https://sunlocean.github.io/Impressum"><b>Impressum</b></a> 
<a href="https://sunlocean.github.io/Datenschutz"><b>Datenschutz</b></a>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Jan 28, 2021 15:45:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

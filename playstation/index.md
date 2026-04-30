---
layout: default
title: PlayStation
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">PlayStation</span>
</nav>

# PlayStation

<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/PS1.png' | relative_url }}"
         alt="The PlayStation"
         class="box-art">
    <figcaption id="box-art-caption">The PlayStation</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/PS1.png' | relative_url }}",
      caption: "The PlayStation",
      alt: "The PlayStation"
    },
    {
      src: "{{ '/assets/images/misc/PSOne.png' | relative_url }}",
      caption: "The PS One",
      alt: "The PS One"
    }
  ];
  let currentBoxArt = 0;
  function changeBoxArt(direction) {
    currentBoxArt += direction;
    if (currentBoxArt < 0) {
      currentBoxArt = boxArts.length - 1;
    }
    if (currentBoxArt >= boxArts.length) {
      currentBoxArt = 0;
    }
    document.getElementById("box-art-image").src = boxArts[currentBoxArt].src;
    document.getElementById("box-art-image").alt = boxArts[currentBoxArt].alt;
    document.getElementById("box-art-caption").textContent = boxArts[currentBoxArt].caption;
  }
</script>


Released: 3/Dec/1994(JP) , 9/Sep/1995(NA) , 29/Sep/1995(EU)

---

## My Thoughts On The PlayStation

The PlayStation to me and many others are one of the greatest consoles and the one that started a long legacy for sony, whether you like more chill platformers like Crash Bandicoot or Spyro The Dragon, or more survival based Tomb Raider  or Resident Evil the original playStation had it all with a fair share of jankiness too. This console was a big part of my childhood playing Crash Bandicoot and Resident Evil more often than not so I feel obliged to say I love it.

---

This is where you will find all the Playstation games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/playstation/cb1/' | relative_url }}">
  Crash Bandicoot
</a>

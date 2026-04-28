---
layout: default
title: Nintendo 64
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">Nintendo 64</span>
</nav>

# Nintendo 64


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/N64.png' | relative_url }}"
         alt="PAL/JP/NA Nintendo 64"
         class="box-art">
    <figcaption id="box-art-caption">PAL/JP/NA Nintendo64</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/N64.png' | relative_url }}",
      caption: "PAL/JP/NA Nintendo 64",
      alt: "PAL/JP/NA Nintendo 64"
    },
    {
      src: "{{ '/assets/images/misc/N64DD.png' | relative_url }}",
      caption: "Nintendo 64 With Disk Drive Attachment",
      alt: "Nintendo 64 With Disk Drive Attachment"
    },
    {
      src: "{{ '/assets/images/misc/N64IQUE.png' | relative_url }}",
      caption: "The iQue Player (N64 In Mainland China)",
      alt: "The iQue Player (N64 In Mainland China)"
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


Released: 23/June/1996(JP) , 29/Sep/1996(NA) , 1/March/1997(EU)


---

## My Thoughts On The Nintendo 64

My family when I was young was very big on Playstation compared to Nintendo so I never really grew up with this console which led me to buy my own when I was around 20. Since then with a mix of physical games and mods i've played a lot of games on the console wether it be the greats such as Mario 64 or Zelda Ocarina of Time or something witha more cult following like Donkey Kong 64 or Banjo-Kazooie. The N64 is easily one of my favourite consoles in recent time.

---

This is where you will find all the Nintendo 64 games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  The Legend Of Zelda: Ocarina Of Time
</a>

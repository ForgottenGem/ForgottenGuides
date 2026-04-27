---
layout: default
title: Ocarina of Time
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <a href="{{ '/n64/' | relative_url }}">Nintendo 64</a>
  <span>/</span>
  <span class="current">Ocarina of Time</span>
</nav>

# The Legend Of Zelda: Ocarina Of Time


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/ootn64/ZOOtN64PalCover.jpg' | relative_url }}"
         alt="PAL Box Art"
         class="box-art">
    <figcaption id="box-art-caption">PAL Box Art</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/ootn64/ZOOtN64PalCover.jpg' | relative_url }}",
      caption: "PAL Box Art",
      alt: "PAL Box Art"
    },
    {
      src: "{{ '/assets/images/ootn64/ZOOtN64NTSCCover.jpg' | relative_url }}",
      caption: "NTSC Box Art",
      alt: "NTSC Box Art"
    },
    {
      src: "{{ '/assets/images/ootn64/ZOOtN64JapanCover.jpg' | relative_url }}",
      caption: "Japan Box Art",
      alt: "Japan Box Art"
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


Released: 21/Nov/1998(JP) , 23/Nov/1998(NA) , 11/Dec/1998(EU)

Genre: 

Developer: 

My Ratings: Fun 7/10 , Difficulty 5/10

---

## My Thoughts

Blah Blah

---

## Guides

<a class="button-link" href="{{ '/n64/oot/100-percent-guideoot' | relative_url }}">
  100% Completion Guide
</a>

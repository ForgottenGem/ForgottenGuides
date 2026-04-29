---
layout: default
title: NES / Famicom
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">NES / Famicom</span>
</nav>

# NES / Famicom


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/NES.png' | relative_url }}"
         alt="The Nintendo Entertainment System"
         class="box-art">
    <figcaption id="box-art-caption">The Nintendo Entertainment System</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/NES.png' | relative_url }}",
      caption: "The Nintendo Entertainment System",
      alt: "The Nintendo Entertainment System"
    },
    {
      src: "{{ '/assets/images/misc/Famicom.png' | relative_url }}",
      caption: "The Famicom (Japan's NES Version)",
      alt: "The Famicom (Japan's NES Version)"
    },
    {
      src: "{{ '/assets/images/misc/FamicomDiskSystem.png' | relative_url }}",
      caption: "The Famicom With Disk System Attachment",
      alt: "The Famicom With Disk System Attachment"
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


Released: 15/July/1983(JP) , 18/Oct/1985(NA) , 1/Sep/1986(EU)


---

## My Thoughts On The Nintendo Entertainment System

I actually have never owned an NES for long even though I have a few games for it such as the original Super Mario Bros. I owned one for about a week that I bought off of ebay and kept trying my hardest to get it working but couldn't so I ended up returning it the next week or so, but the games overall I find them pretty fun but they definitely show their age but the first Mario and Zelda game hit different.

---

This is where you will find all the NES/Famicom games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>





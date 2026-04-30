---
layout: default
title: GameCube
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">Snes / Super Famicom</span>
</nav>

# Snes / Super Famicom


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/SNESPAL.png' | relative_url }}"
         alt="The Pal Super Nintendo Entertainment System"
         class="box-art">
    <figcaption id="box-art-caption">The Pal Super Nintendo Entertainment System</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/SNESPAL.png' | relative_url }}",
      caption: "The Pal Super Nintendo Entertainment System",
      alt: "The Pal Super Nintendo Entertainment System"
    },
    {
      src: "{{ '/assets/images/misc/SNESNTSC.png' | relative_url }}",
      caption: "The NTSC Super Nintendo Entertainment System",
      alt: "The NTSC Super Nintendo Entertainment System"
    },
    {
      src: "{{ '/assets/images/misc/SNESSatellaview.png' | relative_url }}",
      caption: "The Super Famicom With Satellaview Attachment",
      alt: "The Super Famicom With Satellaview Attachment"
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

## My Thoughts On The Super Nintendo Entertainment System

The Snes I feel like was a big development for all series involved especially big for Zelda and Mario, each getting new games for the system such as Mario World and Zelda: A Link To The Past both being major games for their respective series and are beloved by many including myself. The Satellaview attachment in Japan has a rather interesting set of games for it specifically such as BS Zelda no Densetsu, which is close to an enhanced remake of the original Zelda with a Map 2 version also, and another BS Zelda no Densetsu: Inishie no Sekiban , or translated to BS The Legend of Zelda: Ancient Stone Tablets is a game similar to A Link To The Past set six years after the events of that game apparently.

---

This is where you will find all the SNES / Super Famicom games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>







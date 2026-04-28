---
layout: default
title: Nintendo DS
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">Nintendo DS</span>
</nav>

# Nintendo DS


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/DSOG.png' | relative_url }}"
         alt="The Original Nintendo DS"
         class="box-art">
    <figcaption id="box-art-caption">The Original Nintendo DS</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/DSOG.png' | relative_url }}",
      caption: "The Original Nintendo DS",
      alt: "The Original Nintendo DS"
    },
    {
      src: "{{ '/assets/images/misc/NintendoDS.png' | relative_url }}",
      caption: "The Nintendo DS Lite",
      alt: "The Nintendo DS Lite"
    },
    {
      src: "{{ '/assets/images/misc/DSI.png' | relative_url }}",
      caption: "The Nintendo DSI",
      alt: "The Nintendo DSI"
    },
    {
      src: "{{ '/assets/images/misc/DSIXL.png' | relative_url }}",
      caption: "The Nintendo DSI XL",
      alt: "The Nintendo DSI XL"
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


Released: 2/Dec/2004(JP) , 21/Nov/2004(NA) , 11/March/2005(EU)


---

## My Thoughts On The DS

I never actually owned many models of the DS when I was younger, the original DS I have yet to get my hands on to this day. I had a black DS lite that I used constantly as a kid that I have since shell swapped the crusty half broken shell with a nice semi transparent purple one. I played way too much of Mario 64 DS and Bowser's Inside Story when I was younger even doing challenge runs of the latter and recording very very bad speedruns just on my phone when are long gone now. I feel like the DS was a lot of peoples childhood handheld.

---

This is where you will find all the DS games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>



---
layout: default
title: 3DS/2DS Family
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">3DS/2DS Family</span>
</nav>

# 3DS / 2DS


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/Nintendo3DS.png' | relative_url }}"
         alt="The Original Nintendo 3DS"
         class="box-art">
    <figcaption id="box-art-caption">The Original Nintendo 3DS</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/Nintendo3DS.png' | relative_url }}",
      caption: "The Original Nintendo 3DS",
      alt: "The Original Nintendo 3DS"
    },
    {
      src: "{{ '/assets/images/misc/New3DS.png' | relative_url }}",
      caption: "The New Nintendo 3DS",
      alt: "The New Nintendo 3DS"
    },
    {
      src: "{{ '/assets/images/misc/2DS.png' | relative_url }}",
      caption: "The Nintendo 2DS",
      alt: "The Nintendo 2DS"
    },
    {
      src: "{{ '/assets/images/misc/New2dsXL.png' | relative_url }}",
      caption: "The New Nintendo 2DS XL",
      alt: "The New Nintendo 2DS XL"
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


Released: 26/Feb/2011(JP) , 27/March/2011(NA) , 25/March/2011(EU)


---

## My Thoughts On The 3DS Line

For the better part of my teen years I played so many games on my original 3DS and it always was a blast with the eshop virtual console games and DS games being supported as well as the amazing library of games that the 3DS released over it's life cycle. Big games for me was Kid Icarus Uprising , Zelda A Link Between Worlds, and Pokemon Ultra Moon. I always enjoyed my time with this console and as of right now it is the definitive Nintendo Handheld to me.

---

This is where you will find all the 3DS Family of games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>


---
layout: default
title: Game Boy Advance
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">Game Boy Advance</span>
</nav>

# Game Boy Advance


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/GameBoyAdvance.png' | relative_url }}"
         alt="The Original Game Boy Advance"
         class="box-art">
    <figcaption id="box-art-caption">The Original Game Boy Advance</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/GameBoyAdvance.png' | relative_url }}",
      caption: "The Original Game Boy Advance",
      alt: "The Original Game Boy Advance"
    },
    {
      src: "{{ '/assets/images/misc/GBASP.png' | relative_url }}",
      caption: "The Game Boy Advance SP",
      alt: "The Game Boy Advance SP"
    },
    {
      src: "{{ '/assets/images/misc/GBMicro.png' | relative_url }}",
      caption: "The Game Boy Micro",
      alt: "The Game Boy Micro"
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


Released: 21/March/2001(JP) , 11/June/2001(NA) , 22/June/2001(EU)


---

## My Thoughts On The Game Boy Advance

I bought my Game Boy Advance at a convention like 4 years ago when I was around 19, I hadn't remembered that backlit screens weren't always a thing so I got quite a surprise when I turned it on and remembered. But it was still great to play games such as the GBA Crash Bandicoot games or Zelda: Minish Cap. I then later got my GBA SP at the Irish Gaming Market up in dublin and it's the definitive way to play the GB, GBC, and GBA line of games.

---

This is where you will find all the GBA games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>




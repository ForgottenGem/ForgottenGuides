---
layout: default
title: PlayStation 5
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">PlayStation 5</span>
</nav>

# PlayStation 5


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/PS5.png' | relative_url }}"
         alt="The PlayStation 5 Standard Edition"
         class="box-art">
    <figcaption id="box-art-caption">The PlayStation 5 Standard Edition</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/PS5.png' | relative_url }}",
      caption: "The PlayStation 5 Standard Edition",
      alt: "The PlayStation 5 Standard Edition"
    },
    {
      src: "{{ '/assets/images/misc/PS5Slim.png' | relative_url }}",
      caption: "The PlayStation 5 Slim Edition",
      alt: "The PlayStation 5 Slim Edition"
    },
    {
      src: "{{ '/assets/images/misc/PS5Pro.png' | relative_url }}",
      caption: "The PlayStation 5 Pro Edition",
      alt: "The PlayStation 5 Pro Edition"
    },
    {
      src: "{{ '/assets/images/misc/PSVR2.png' | relative_url }}",
      caption: "The PlayStation 5 VR Headset",
      alt: "The PlayStation 5 VR Headset"
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


Released: 19/Nov/2020(World-Wide)


---

## My Thoughts On The PlayStation 5

The PlayStation 5 is the culmination of all sony has worked on, it is one of the best feeling consoles I have every played and trust me i've played a lot of them. The PS5 systems came pre-installed with a game called Astro's Playroom, I remember the day I first played the PS5 I was being home schooled for my final year as it was during the covid 19 pandemic. I booted up Astro's Playroom on a break and when I tell you I fell in love you have no idea how much I love this little robot. Then later they released Astro Bot a standalone astro bot game and it is just so fun. Along with games like Deathloop and Resident Evil remakes and 9 it has made the PS5 a beloved console of mine.

---

This is where you will find all the PlayStation 5 games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>









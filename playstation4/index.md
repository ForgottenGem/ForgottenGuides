---
layout: default
title: PlayStation 4
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">PlayStation 4</span>
</nav>

# PlayStation 4


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/PS4.png' | relative_url }}"
         alt="The PlayStation 4 Standard Edition"
         class="box-art">
    <figcaption id="box-art-caption">The PlayStation 4 Standard Edition</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/PS4.png' | relative_url }}",
      caption: "The PlayStation 4 Standard Edition",
      alt: "The PlayStation 4 Standard Edition"
    },
    {
      src: "{{ '/assets/images/misc/PS4Slim.png' | relative_url }}",
      caption: "The PlayStation 4 Slim Edition",
      alt: "The PlayStation 4 Slim Edition"
    },
    {
      src: "{{ '/assets/images/misc/PS4Pro.png' | relative_url }}",
      caption: "The PlayStation 4 Pro Edition",
      alt: "The PlayStation 4 Pro Edition"
    },
    {
      src: "{{ '/assets/images/misc/PSVR.png' | relative_url }}",
      caption: "The PlayStation 4 VR Headset",
      alt: "The PlayStation 4 VR Headset"
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


Released: 22/Feb/2014(JP) , 15/Nov/2013(NA) , 29/Nov/2013(EU)


---

## My Thoughts On The PlayStation 4

The PlayStation 4 was such an amazing console for me whether it's because of the later Skylanders games, Crash Bandicoot remakes or Bloodborne which is one of the most amazing games of all time and I will fight for this, The PS4 was just such a leap up from the PS3 for me atleast and had so many good games like PvZ Garden Warfare 2. The amount of times i've played each of these is countless and I thoroughly enjoyed my time with the PS4. It was also the first PlayStation console to have VR capabilities with a few good highlights such as Astro Bot : Rescue Mission, PS VR Worlds, Farpoint.

---

This is where you will find all the PlayStation 4 games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>








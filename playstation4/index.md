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


Released: 11/Nov/2006(JP) , 17/Nov/2006(NA) , 23/March/2007(EU)


---

## My Thoughts On The PlayStation 3

PlayStation released their third console and was very very expensive at launch costing about $600 in 2006 which made it a bit of a loss as it also cost Sony a lot to manufacture. That being said their ae some great series that began on the PS3 such as the Assassin's Creed series, Prototype series, and Little Big Planet all being major parts of my PlayStation experience when I was more towards my teen years but overall still not one of my favourite consoles as besides thos amazing new series starting there wasn't too much special about the PS3.

---

This is where you will find all the PlayStation 3 games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>








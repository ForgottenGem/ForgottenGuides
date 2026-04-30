---
layout: default
title: Nintendo Switch
---

<nav class="breadcrumbs" aria-label="Breadcrumb">
  <span class="current">Nintendo Switch</span>
</nav>

# Nintendo Switch


<div class="box-art-carousel">
  <button class="carousel-btn" onclick="changeBoxArt(-1)">‹</button>
  <figure class="image-block">
    <img id="box-art-image"
         src="{{ '/assets/images/misc/SwitchOG.png' | relative_url }}"
         alt="The Nintendo Switch"
         class="box-art">
    <figcaption id="box-art-caption">The Nintendo Switch</figcaption>
  </figure>
  <button class="carousel-btn" onclick="changeBoxArt(1)">›</button>
</div>
<script>
  const boxArts = [
    {
      src: "{{ '/assets/images/misc/SwitchOG.png' | relative_url }}",
      caption: "The Nintendo Switch",
      alt: "The Nintendo Switch"
    },
    {
      src: "{{ '/assets/images/misc/Switch.png' | relative_url }}",
      caption: "The Nintendo Switch OLED",
      alt: "The Nintendo Switch OLED"
    },
    {
      src: "{{ '/assets/images/misc/Switch Lite.png' | relative_url }}",
      caption: "The Nintendo Switch Lite",
      alt: "The Nintendo Switch Lite"
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


Released: 3/March/2017(World-Wide)


---

## My Thoughts On The Nintendo Switch

There are so many things I can say about this console but none of it would do it justice. I remember sitting in the back of the car like with the Switch box in hand and the like giant collector's edition Zelda Breath of The Wild box and was like reading the back of the box over and over and over on the way home just way too excited to get it set up. The time that followed the hundreds of hours playing so many amazing games like the aforementioned Zelda game or Super Mario Odyssey, all the Wii U remakes were greatly appreciated too! I actually for some reason really liked the game Arms when it first released and still do like it to this day!

---

This is where you will find all the Nintendo Switch games I have currently made guides for.

---

## Games

<a class="button-link" href="{{ '/n64/oot/' | relative_url }}">
  temp
</a>


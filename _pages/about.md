---
layout: about
id: about
permalink: /about-light-and-free/
title: About Light & Free
nav: true
nav-order: 3

banner:
  title: About <br>Light & Free

intro: Delicious Greek-style yoghurt with eight scrumptious flavours to choose from. Find the flavour for you, each inspired by around-the-world adventures. 0% fat 0% added sugar 100% delicious.

flavours:

  - id: blueberry
    title: Blueberry Burst
    description: Play to win hearts with this mouth watering taste sensation. Enjoy the fab fruity zing of Light & Free Blueberry!
    link: http://www.lightandfree.com/product/four-pack-blueberry

  - id: vanilla
    title: Vanilla
    description: Smooth as silk, a timeless classic! Enjoy the laid-back taste of Light & Free Vanilla!
    link: http://www.lightandfree.com/product/four-pack-vanilla

  - id: peach
    title: Peach Passion Fruit
    description: Wakey wakey, let your senses shine with this taste of the tropics. Enjoy the exciting fruit combination of Light & Free Peach Passion Fruit!
    link: http://www.lightandfree.com/product/four-pack-peach-passion-fruit

  - id: lemon
    title: Lemon
    description: Its zesty style will awaken your senses. Enjoy the refreshing taste of Light & Free Lemon!
    link: http://www.lightandfree.com/product/four-pack-lemon

  - id: cherry
    title: Cherry Charmer
    description: Take a ride on the luscious side. Enjoy the sunkissed taste of Light & Free Cherry!
    link: http://www.lightandfree.com/product/four-pack-cherry

  - id: strawberry
    title: Strawberry
    description: Great taste, great style, you’re simply made for each other. Enjoy the irresistible taste of Light & Free Strawberry!
    link: http://www.lightandfree.com/product/four-pack-strawberry

  - id: coconut
    title: Coconut
    description: Its coconut bits will tingle your taste buds. Enjoy the fresh taste of Light & Free Coconut!
    link: http://www.lightandfree.com/product/four-pack-coconut

  - id: raspberry
    title: Raspberry Razzle
    description: Enjoy the delicious taste of Light* & Free Raspberry!
    link: http://www.lightandfree.com/product/four-pack-raspberry
---

<div class="container">
  <div>
    <div class="row row--6-6 row--xxl-4-4-4">
      <div class="col">
        <div class="col__content-spacing">
          {% include content/flavour.html id="strawberry" %}
          {% include content/flavour.html id="vanilla" %}
          {% include content/flavour-image.html id="peach" ratio="1-1" %}
          {% include content/flavour.html id="raspberry" %}
          {% include content/flavour-image.html id="cherry" ratio="2-3" %}
        </div>
      </div>
      <div class="col">
        <div class="col__content-spacing">
          {% include content/flavour-image.html id="blueberry" ratio="1-1" %}
          {% include content/flavour-image.html id="coconut" ratio="2-3" %}
          {% include content/flavour.html id="blueberry" %}
          {% include content/flavour-image.html id="strawberry" ratio="1-1" %}
          {% include content/flavour.html id="lemon" %}
        </div>
      </div>
      <div class="col">
        <div class="col__content-spacing">
          {% include content/flavour.html id="peach" %}
          {% include content/flavour.html id="cherry" %}
          {% include content/flavour-image.html id="lemon" ratio="2-3" %}
          {% include content/flavour.html id="coconut" %}
          {% include content/flavour-image.html id="vanilla" ratio="1-1" %}
        </div>
      </div>
    </div>
  </div>
  <div class="space--xxxxl"></div>
</div>
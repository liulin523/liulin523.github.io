---
layout: page
title: Photos
permalink: /photos/
description: Field photos
nav: true
nav_order: 7
---
## Snow monitoring site in Qilian Mountain, Qinghai, 2018
By Jiahua Zhang
<div id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000">
  <ol class="carousel-indicators">
    <li data-target="#carousel" data-slide-to="0" class="active"></li>
    <li data-target="#carousel" data-slide-to="1"></li>
    <li data-target="#carousel" data-slide-to="2"></li>
  </ol>
  
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block" src="/assets/img/field/Jiahua1.jpg" alt="Slide 1" style="width:50%; margin:0 auto;">
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/Jiahua2.jpg" alt="Slide 2" style="width:50%; margin:0 auto;">    
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/Jiahua3.jpg" alt="Slide 3" style="width:50%; margin:0 auto;">
    </div>
  </div>
  
  <a class="carousel-control-prev" href="#carousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

## Rock glaciers in the European Alps, 2018
By Yan Hu
<div id="carouselAlps" class="carousel slide" data-ride="carousel" data-interval="5000">
  <ol class="carousel-indicators">
    <li data-target="#carouselAlps" data-slide-to="0" class="active"></li>
    <li data-target="#carouselAlps" data-slide-to="1"></li>
    <li data-target="#carouselAlps" data-slide-to="2"></li>
  </ol>
  
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block" src="/assets/img/field/yan_alps1.jpg" alt="Alps Rock Glacier 1" style="width:50%; margin:0 auto;">
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/yan_alps2.jpg" alt="Alps Rock Glacier 2" style="width:50%; margin:0 auto;">
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/yan_alps3.jpg" alt="Alps Rock Glacier 3" style="width:50%; margin:0 auto;">
    </div>
  </div>
  
  <a class="carousel-control-prev" href="#carouselAlps" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselAlps" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

## Field Photos on the Tibetan Plateau, 2017-2018
By Lingcao Huang
<div id="carouselTibet" class="carousel slide" data-ride="carousel" data-interval="5000">
  <ol class="carousel-indicators">
    <li data-target="#carouselTibet" data-slide-to="0" class="active"></li>
    <li data-target="#carouselTibet" data-slide-to="1"></li>
    <li data-target="#carouselTibet" data-slide-to="2"></li>
    <li data-target="#carouselTibet" data-slide-to="3"></li>
    <li data-target="#carouselTibet" data-slide-to="4"></li>
  </ol>
  
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block" src="/assets/img/field/lingcao_thaw_slump2_beiluhe.jpg" alt="Tibetan Plateau 1" style="width:50%; margin:0 auto;">
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/lingcao_thaw_slump1_beiluhe.jpg" alt="Tibetan Plateau 2" style="width:50%; margin:0 auto;">
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/lingcao_thermal_erosion_gully_eboling.jpg" alt="Tibetan Plateau 3" style="width:50%; margin:0 auto;">
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/lingcao_sinkhole_eobling.jpg" alt="Tibetan Plateau 4" style="width:50%; margin:0 auto;">
    </div>
    <div class="carousel-item">
      <img class="d-block" src="/assets/img/field/lingcao_Hummocks2_maxianshan.jpg" alt="Tibetan Plateau 5" style="width:50%; margin:0 auto;">
    </div>
  </div>
  
  <a class="carousel-control-prev" href="#carouselTibet" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselTibet" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

## Old photos
(Right-click 'view image' to see a larger image)
<div class="row">
{% for pic in site.data.field_pictures %}
  <div class="col-sm-3 clearfix">
    <img src="/assets/img/field/{{ pic.image }}" class="img-responsive" width="50%" style="float: left" alt="{{ pic.description | default: 'Field photo' }}"/>
  </div>
  {% assign loopindex = forloop.index | modulo: 4 %}
  {% if loopindex == 0 or forloop.last %}
    </div>{% unless forloop.last %}<div class="row">{% endunless %}
  {% endif %}
{% endfor %}

<p>&nbsp;</p>

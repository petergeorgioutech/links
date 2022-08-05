<template lang="html">
  <div class="sub-wrapper">

    <header class="sub-header">
      <nuxt-link to="/" class="back-button" :style="backIcon"></nuxt-link>
      <div class="mini-profile">
        <span class="profile-handle">@peterpandev</span>
        <div class="mini-profile-image" :style="profileImage"></div>
      </div>
    </header>

    <h1 class="title-underlined mb-4">My Setup Gear</h1>
    <p>I have been working hard to create the dream setup which will help boost my productivity and help me achieve my goals as a web developer. I am constantly improving my setup and every product you see has it's purpose. Please find a list below of the items I use within my setup along with a purchase link. Some of the links are affiliate links which help support me as a content creator.</p>
    <p>Feel free to <a href="/get-in-touch">get in touch</a> if you have any further questions related to the setup.</p>
    <img src="~/assets/img/setup.jpg" class="img-fluid mb-3"/>

    <div class="container d-flex flex-column min-vh-70">
      <div class="row content-wrapper">
        <div class="col-12 py-1 links">
          <div class="link">
            <span class="link-image fill-image" :style="deskpadImage"></span>
            <span class="link-text">
              Desk Pad
            </span>
            <a href="https://shop.minimaldesksetups.com/products/desk-pad?sca_ref=1578836.V3jOBkjkyk" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="nuphyImage2"></span>
            <span class="link-text">
              Nuphy Air60
            </span>
            <a href="https://nuphy.com/products/air60?sca_ref=1358258.uq17yCXeKi" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="nuphyImage"></span>
            <span class="link-text">
              Nuphy Air75
            </span>
            <a href="https://nuphy.com/products/air75?sca_ref=1358258.uq17yCXeKi" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="ergochairImage"></span>
            <span class="link-text">
              ErgoChair Pro
            </span>
            <a href="https://www.autonomous.ai/office-chairs/ergonomic-chair?utm_source=pr&utm_medium=influencer&utm_campaign=growth&utm_content=Instagram&utm_term=22PETER" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="macbookImage"></span>
            <span class="link-text">
              16" Macbook Pro M1 Max
            </span>
            <a href="https://www.apple.com/shop/buy-mac/macbook-pro/16-inch-space-gray-10-core-cpu-32-core-gpu-1tb#" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="xreartImage"></span>
            <span class="link-text">
              Xreart iPhone 5S Frame
            </span>
            <a href="https://xreart.com/?ref=0ck56cul3q" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="smartdeskproImage"></span>
            <span class="link-text">
              SmartDesk Pro
            </span>
            <a href="https://rb.gy/keomlb" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="lg49Image"></span>
            <span class="link-text">
              LG 49WL95C-W
            </span>
            <a href="https://www.lg.com/us/monitors/lg-49WL95C-W-ultrawide-monitor" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="lg27Image"></span>
            <span class="link-text">
              LG 27UK850-W
            </span>
            <a href="https://www.lg.com/us/monitors/lg-27UK850-W-4k-uhd-led-monitor" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="ergearImage"></span>
            <span class="link-text">
              ErGear Monitor Mount
            </span>
            <a href="https://www.amazon.co.uk/ErGear-Ultrawide-Innovative-Counterbalance-Technology-black/dp/B08BYJL63R" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="secretlabImage"></span>
            <span class="link-text">
              SecretLab Titan 2020
            </span>
            <a href="https://secretlab.eu/collections/titan-series#titan_2020_softweave-charcoal_blue" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="nanoleafImage"></span>
            <span class="link-text">
              Nanoleaf Shapes
            </span>
            <a href="https://nanoleaf.me/en-EU/products/nanoleaf-shapes/" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="goveeImage"></span>
            <span class="link-text">
              Govee Glide Wall Light
            </span>
            <a href="https://us.govee.com/products/govee-glide-wall-light" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="grovemadeImage"></span>
            <span class="link-text">
              Grovemade Desk Shelf
            </span>
            <a href="https://grovemade.com/desk-shelf-system/" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          
          <div class="link">
            <span class="link-image fill-image" :style="deltahubImage"></span>
            <span class="link-text">
              Deltahub Carpio 2.0
            </span>
            <a href="https://deltahub.io/products/carpio-2" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="benqImage"></span>
            <span class="link-text">
              BenQ Screenbar Plus
            </span>
            <a href="https://www.benq.com/en-us/lamps/computer-desklamp/screenbar-plus.html" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="grid4sImage"></span>
            <span class="link-text">
              GRID&reg; 4S
            </span>
            <a href="https://gridstudio.cc/products/grid%C2%AE4s" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="logitechImage"></span>
            <span class="link-text">
              Logitech C920
            </span>
            <a href="https://www.amazon.com/Logitech-Widescreen-Calling-Recording-Desktop/dp/B006JH8T3S" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="caldigitImage"></span>
            <span class="link-text">
              Caldigit TS3 Plus
            </span>
            <a href="https://www.caldigit.com/ts3-plus/" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="sonyImage"></span>
            <span class="link-text">
              Sony WH-1000XM4
            </span>
            <a href="https://electronics.sony.com/audio/headphones/headband/p/wh1000xm4-b" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="divoomImage"></span>
            <span class="link-text">
              Divoom Ditoo Plus
            </span>
            <a href="https://www.divoom.com/products/divoom-ditooplus" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="mercedesImage"></span>
            <span class="link-text">
              Mercedes A Class AMG
            </span>
            <a href="https://www.kunzmann.de/shop/en/accessory/model-cars/1-18-model-car-mercedes-benz-a-class-compactsedan-digital-white.htm" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="mazdaImage"></span>
            <span class="link-text">
              Mazda RX8
            </span>
            <a href="https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2322090.m570.l1313&_nkw=MAZDA+Rx8+Orange-red+2003+Diecast+Model+Car&_sacat=0" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="hustlerangeImage"></span>
            <span class="link-text">
              Hustlerange Poster
            </span>
            <a href="https://hustlerange.com/discount/PETER20" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>

        </div>
      </div>
    </div>


  </div>
</template>

<script>
import profile from "assets/img/profile.jpg";
import back from "assets/img/icons/back.svg";
import orbitkey from "assets/img/brands/orbitkey.svg";
import feelzing from "assets/img/brands/feelzing.jpg";
import smartdeskpro from "assets/img/brands/smartdeskpro.jpg";
import lg49 from "assets/img/setup/lg49.jpg";
import lg27 from "assets/img/setup/lg27.jpg";
import secretlab from "assets/img/setup/secretlab.jpg";
import nanoleaf from "assets/img/setup/nanoleaf.jpg";
import grovemade from "assets/img/setup/grovemade.jpg";
import deskpad from "assets/img/setup/deskpad.jpg";
import deltahub from "assets/img/setup/deltahub.jpg";
import benq from "assets/img/setup/benq.jpg";
import nuphy from "assets/img/setup/nuphy.jpg";
import nuphy2 from "assets/img/setup/nuphy-air60.jpg";
import macbook from "assets/img/setup/macbook.jpg";
import govee from "assets/img/setup/govee.jpg";
import logitech from "assets/img/setup/logitech.jpg";
import sony from "assets/img/setup/sony.jpg";
import ergear from "assets/img/setup/ergear.jpg";
import grid4s from "assets/img/setup/grid4s.jpg";
import mercedes from "assets/img/setup/mercedes.jpg";
import mazda from "assets/img/setup/mazda.jpg";
import divoom from "assets/img/setup/divoom.jpg";
import caldigit from "assets/img/setup/caldigit.jpg";
import hustlerange from "assets/img/setup/hustlerange.jpg";
import xreart from "assets/img/setup/xreart.jpg";
import ergochair from "assets/img/setup/ergochair.jpg";

export default {
  // transition: {
  //   name: "SlideLeft",
  //   mode: "out-in"
  // },
  layout: 'default',
  data() {
    return {
      placeholderImage: { backgroundImage: `url(https://via.placeholder.com/150x160?text=Image)` },
      profileImage: { backgroundImage: `url(${profile})` },
      backIcon: { backgroundImage: `url(${back})` },
      orbitkeyImage: { backgroundImage: `url(${orbitkey})` },
      feelzingImage: { backgroundImage: `url(${feelzing})` },
      smartdeskproImage: { backgroundImage: `url(${smartdeskpro})` },
      lg49Image: { backgroundImage: `url(${lg49})` },
      lg27Image: { backgroundImage: `url(${lg27})` },
      secretlabImage: { backgroundImage: `url(${secretlab})` },
      nanoleafImage: { backgroundImage: `url(${nanoleaf})` },
      grovemadeImage: { backgroundImage: `url(${grovemade})` },
      deskpadImage: { backgroundImage: `url(${deskpad})` },
      deltahubImage: { backgroundImage: `url(${deltahub})` },
      benqImage: { backgroundImage: `url(${benq})` },
      nuphyImage: { backgroundImage: `url(${nuphy})` },
      nuphyImage2: { backgroundImage: `url(${nuphy2})` },
      macbookImage: { backgroundImage: `url(${macbook})` },
      goveeImage: { backgroundImage: `url(${govee})` },
      logitechImage: { backgroundImage: `url(${logitech})` },
      sonyImage: { backgroundImage: `url(${sony})` },
      ergearImage: { backgroundImage: `url(${ergear})` },
      grid4sImage: { backgroundImage: `url(${grid4s})` },
      mercedesImage: { backgroundImage: `url(${mercedes})` },
      mazdaImage: { backgroundImage: `url(${mazda})` },
      divoomImage: { backgroundImage: `url(${divoom})` },
      caldigitImage: { backgroundImage: `url(${caldigit})` },
      hustlerangeImage: { backgroundImage: `url(${hustlerange})` },
      xreartImage: { backgroundImage: `url(${xreart})` },
      ergochairImage: { backgroundImage: `url(${ergochair})` },
    };
  }
};
</script>

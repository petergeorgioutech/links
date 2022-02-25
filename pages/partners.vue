<template lang="html">
  <div class="sub-wrapper">

    <header class="sub-header">
      <nuxt-link to="/" class="back-button" :style="backIcon"></nuxt-link>
      <div class="mini-profile">
        <span class="profile-handle">@peterpandev</span>
        <div class="mini-profile-image" :style="profileImage"></div>
      </div>
    </header>

    <h1 class="title-underlined mb-4">Brand Partners</h1>
    <p>I've partnered up with some amazing brands who offer products that I use daily within my workspace and day to day life. Help support me by using the links below to purchase your products.</p>

    <div class="container d-flex flex-column min-vh-70">
      <div class="row content-wrapper">
        <div class="col-12 py-1 links">
          <div class="link">
            <span class="link-image fill-image" :style="autonomousImage"></span>
            <span class="link-text">
              SmartDesk Pro
            </span>
            <a href="https://rb.gy/keomlb" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="mindesksetupImage"></span>
            <span class="link-text">
              Minimal Desk Setups
            </span>
            <a href="https://shop.minimaldesksetups.com/products/desk-pad?sca_ref=1578836.V3jOBkjkyk" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="xreartImage"></span>
            <span class="link-text">
              Xreart Frames
            </span>
            <a href="https://xreart.com/?ref=0ck56cul3q" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="orbitkeyImage"></span>
            <span class="link-text">
              Clever Organisation
            </span>
            <a href="https://bit.ly/32K5vNv" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="feelzingImage"></span>
            <span class="link-text">
              Feelzing Energy Patches
            </span>
            <a href="https://feelzing.com/0ck56cul3q" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
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
import autonomous from "assets/img/brands/autonomous.jpg";
import mindesksetup from "assets/img/brands/mindesksetup.webp";
import xreart from "assets/img/setup/xreart.jpg";

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
      autonomousImage: { backgroundImage: `url(${autonomous})` },
      mindesksetupImage: { backgroundImage: `url(${mindesksetup})` },
      xreartImage: { backgroundImage: `url(${xreart})` },
    };
  }
};
</script>

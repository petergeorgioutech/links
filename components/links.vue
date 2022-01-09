<template lang="html">
  <div>
    <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PNK4H79"
    height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
    <div class="container px-0 main-wrapper">
      <div class="row"><div class="col cover"><div class="placeholder"></div></div></div>
      <div class="container d-flex flex-column min-vh-70">
        <div class="row avi">
          <div class="col">
            <div class="text-center avatar rounded-circle"><div class="rounded-circle" :style="profileImage"></div>
            </div>
          </div>
        </div>
        <div class="row justify-content-center mb-1">
          <div class="col-10 text-center py-2">
            <h1 class="username">Peter Georgiou</h1>
            <p class="description">Frontend Web Developer <span class="small-type">@peterpandev</span></p>
            <a href="mailto:hello@petergeorgiou.tech" class="status accepting">
              Accepting <span class="project_type">Freelance Projects</span>
            </a>
          </div>
        </div>
        <div class="row mb-1 featured-items">
          <nuxt-link to="/setup" class="featured-item" :style="setupImage">
            <span class="featured-title">My Setup Gear</span>
          </nuxt-link>
          <a href="https://vscodethemes.com/e/morgan-codes.morgan-codes-vscode-theme" target="_blank" class="featured-item" :style="vsCodeImage">
            <span class="featured-title">VS Code Theme</span>
          </a>
          <nuxt-link to="/" class="featured-item" :style="placeholderImage">
            <span class="featured-title">Placeholder</span>
          </nuxt-link>
          <nuxt-link to="/" class="featured-item" :style="placeholderImage">
            <span class="featured-title">Placeholder</span>
          </nuxt-link>
        </div>
        <div class="row content-wrapper">
          <div class="col-10 offset-1 links">
            <nuxt-link to="/promotions" class="link">
              <span class="link-image" :style="couponImage" style="background-size:70%;background-position:center center;"></span>
              <span class="link-text">Discount Codes</span>
              <span class="arrow"></span>
            </nuxt-link>
          </div>
          <div class="col-10 offset-1 links">
            <nuxt-link to="/partners" class="link">
              <span class="link-image" :style="partnersImage" style="background-size:contain;background-position:center center;"></span>
              <span class="link-text">Brand Partners</span>
              <span class="arrow"></span>
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import profile from "assets/img/profile.jpg";
import setup from "assets/img/setup.jpg";
import vscode from "assets/img/vscode.png";
import coupon from "assets/img/icons/coupon.png";
import orbitkey from "assets/img/brands/orbitkey.svg";
import partners from "assets/img/partners.svg";
export default {
  data() {
    return {
      placeholderImage: { backgroundImage: `url(https://via.placeholder.com/150x160?text=Image)` },
      profileImage: { backgroundImage: `url(${profile})` },
      setupImage: { backgroundImage: `url(${setup})` },
      vsCodeImage: { backgroundImage: `url(${vscode})` },
      orbitkeyImage: { backgroundImage: `url(${orbitkey})` },
      partnersImage: { backgroundImage: `url(${partners})` },
      couponImage: { backgroundImage: `url(${coupon})` },
    };
  },
  methods: {
  }
};
</script>

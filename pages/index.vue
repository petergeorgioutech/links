<template>
  <div>
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
            <ul class="socials-wrapper">
              <li><a href="//instagram.com/peterpandev" target="blank" :style="instagramImage"><span class="icon-instagram"></span></a></li>
              <li><a href="//links.petergeorgiou.tech/youtube" target="blank" :style="youtubeImage"><span class="icon-youtube"></span></a></li>
            </ul>
            <a href="mailto:hello@petergeorgiou.tech" class="status accepting">
              Accepting <span class="project_type">Freelance Projects</span>
            </a>
          </div>
        </div>
        <div class="row mb-3 featured-items">
          <a href="http://www.quadlockcase.net/mag" target="_blank" class="featured-item" :style="quadlockImage">
            <span class="featured-title">Quad Lock MAG&trade;</span>
          </a>
          <a href="https://bit.ly/3vkoiKA" target="_blank" class="featured-item" :style="galaxyImage">
            <span class="featured-title">Hack the galaxy</span>
          </a>
          <a href="https://academy.zerotomastery.io/p/complete-web-developer-zero-to-mastery?affcode=441520_wmgpaqt4" target="_blank" class="featured-item" :style="ztmImage">
            <span class="featured-title">Zero To Mastery</span>
          </a>
          <nuxt-link to="/setup" class="featured-item" :style="setupImage">
            <span class="featured-title">My Setup Gear</span>
          </nuxt-link>
          <a href="https://vscodethemes.com/e/morgan-codes.morgan-codes-vscode-theme" target="_blank" class="featured-item" :style="vsCodeImage">
            <span class="featured-title">VS Code Theme</span>
          </a>
          <nuxt-link to="/get-in-touch" class="featured-item" :style="profile1Image">
            <span class="featured-title">Get In Touch</span>
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
import profile1 from "assets/img/profile1.jpg";
import setup from "assets/img/setup.jpg";
import vscode from "assets/img/vscode.png";
import coupon from "assets/img/icons/coupon.png";
import orbitkey from "assets/img/brands/orbitkey.svg";
import partners from "assets/img/partners.svg";
import ztm from "assets/img/ztm.jpg";
import galaxy from "assets/img/galaxy.jpg";
import instagram from "assets/img/instagram.png";
import youtube from "assets/img/youtube.png";
import quadlock from "assets/img/brands/quadlock.jpg";

export default {
  layout: 'default',
  data() {
    return {
      placeholderImage: { backgroundImage: `url(https://via.placeholder.com/150x160?text=Image)` },
      profileImage: { backgroundImage: `url(${profile})` },
      profile1Image: { backgroundImage: `url(${profile1})` },
      setupImage: { backgroundImage: `url(${setup})` },
      vsCodeImage: { backgroundImage: `url(${vscode})` },
      orbitkeyImage: { backgroundImage: `url(${orbitkey})` },
      partnersImage: { backgroundImage: `url(${partners})` },
      couponImage: { backgroundImage: `url(${coupon})` },
      ztmImage: { backgroundImage: `url(${ztm})` },
      galaxyImage: { backgroundImage: `url(${galaxy})` },
      instagramImage: { backgroundImage: `url(${instagram})` },
      youtubeImage: { backgroundImage: `url(${youtube})` },
      quadlockImage: { backgroundImage: `url(${quadlock})` },
    };
  }
};
</script>
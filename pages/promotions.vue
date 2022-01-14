<template lang="html">
  <div class="sub-wrapper">

    <header class="sub-header">
      <nuxt-link to="/" class="back-button" :style="backIcon"></nuxt-link>
      <div class="mini-profile">
        <span class="profile-handle">@peterpandev</span>
        <div class="mini-profile-image" :style="profileImage"></div>
      </div>
    </header>

    <h1 class="title-underlined mb-4">Discount Codes</h1>
    <p>The code for each brand will be copied automatically when selected. Paste the code in the checkout to receive your discount.</p>

    <div class="container d-flex flex-column min-vh-70">
      <div class="row content-wrapper">
        <div class="col-12 py-1 links">
          <div class="link" data-code="peter20">
            <span class="link-image fill-image" :style="smartdeskproImage"></span>
            <span class="link-text">
              Autonomous SmartDesk Pro <br>
              <span class="link-description">Get 4% Off</span>
            </span>
            <button class="copy-code" :style="copyImage" @click="copy" data-code="22PETER"></button>
            <a href="https://rb.gy/keomlb" target="_blank" class="btn btn-primary web-btn d-none">Shop Now</a>
          </div>
          <div class="link" data-code="peter20">
            <span class="link-image fill-image" :style="feelzingImage"></span>
            <span class="link-text">
              Feelzing Energy Patches <br>
              <span class="link-description">Get 15% Off</span>
            </span>
            <button class="copy-code" :style="copyImage" @click="copy" data-code="PETERPANDEV"></button>
            <a href="https://feelzing.com/0ck56cul3q" target="_blank" class="btn btn-primary web-btn d-none">Shop Now</a>
          </div>
          <div class="link" data-code="peter20">
            <span class="link-image fill-image" :style="hustlerangeImage"></span>
            <span class="link-text">
              Hustlerange Posters <br>
              <span class="link-description">Get 20% Off</span>
            </span>
            <button class="copy-code" :style="copyImage" @click="copy" data-code="PETER20"></button>
            <a href="https://hustlerange.com/discount/PETER20" target="_blank" class="btn btn-primary web-btn d-none">Shop Now</a>
          </div>
        </div>
      </div>
    </div>


  </div>
</template>

<script>
import profile from "assets/img/profile.jpg";
import back from "assets/img/icons/back.svg";
import copy from "assets/img/icons/copy.svg";
import feelzing from "assets/img/brands/feelzing.jpg";
import smartdeskpro from "assets/img/brands/smartdeskpro.jpg";
import hustlerange from "assets/img/setup/hustlerange.jpg";

export default {
  layout: 'default',
  // transition: {
  //   name: "SlideLeft",
  //   mode: "out-in"
  // },
  methods: {
    copy: function(e) {
      $(".copy-code").removeClass("d-none");
      $(".web-btn").addClass("d-none");
      var code = e.currentTarget.getAttribute('data-code');
      console.log(code);
      navigator.clipboard.writeText(code);
      e.currentTarget.classList.add("d-none");
      e.currentTarget.nextElementSibling.classList.remove("d-none");
      // $('#codeCopied').addClass('test');
    }
  },
  data() {
    return {
      placeholderImage: { backgroundImage: `url(https://via.placeholder.com/150x160?text=Image)` },
      profileImage: { backgroundImage: `url(${profile})` },
      backIcon: { backgroundImage: `url(${back})` },
      copyImage: { backgroundImage: `url(${copy})` },
      feelzingImage: { backgroundImage: `url(${feelzing})` },
      smartdeskproImage: { backgroundImage: `url(${smartdeskpro})` },
      hustlerangeImage: { backgroundImage: `url(${hustlerange})` },
    };
  }
};
</script>

<template lang="html">
  <div class="sub-wrapper">

    <header class="sub-header">
      <nuxt-link to="/" class="back-button" :style="backIcon"></nuxt-link>
      <div class="mini-profile">
        <span class="profile-handle">@peterpandev</span>
        <div class="mini-profile-image" :style="profileImage"></div>
      </div>
    </header>
    <h1 class="title-underlined mb-4">General Enquiries</h1>
    <p>Please feel free to email any questions you may have to <a href="mailto:hello@petergeorgiou.tech">hello@petergeorgiou.tech</a> and i'll get back to you as soon as I can.</p>
    <h1 class="title-underlined mb-4">For Collaborations</h1>
    <p>I'm always on the lookout for new products in the market. Get in touch with me by emailing your request to <a href="mailto:partners@petergeorgiou.tech?subject=Collaboration Request">partners@petergeorgiou.tech</a> and we can kick off our collaboraton in style.</p>
  </div>
</template>

<script>
import profile from "assets/img/profile.jpg";
import back from "assets/img/icons/back.svg";

export default {
  // transition: {
  //   name: "SlideLeft",
  //   mode: "out-in"
  // },
  layout: 'default',
  data() {
    return {
      profileImage: { backgroundImage: `url(${profile})` },
      backIcon: { backgroundImage: `url(${back})` }
    };
  }
};
</script>

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
            <span class="link-image fill-image" :style="sihooImage"></span>
            <span class="link-text">
              Sihoo V1 Ergo Chair
            </span>
            <a href="https://www.amazon.com/dp/B0982RGW5Z?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B0982RGW5Z&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="macbookImage"></span>
            <span class="link-text">
              16" Macbook Pro M1 Max
            </span>
            <a href="https://www.apple.com/shop/buy-mac/macbook-pro/16-inch-space-gray-10-core-cpu-32-core-gpu-1tb#" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="deskImage"></span>
            <span class="link-text">
              IKEA Pinnarp Worktop
            </span>
            <a href="https://www.ikea.com/us/en/p/pinnarp-countertop-walnut-veneer-20467479/#content" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="standingdeskImage"></span>
            <span class="link-text">
              Standing Desk
            </span>
            <a href="https://www.autonomous.ai/standing-desks/smartdesk-2-business?utm_source=pr&utm_medium=influencer&utm_campaign=growth&utm_content=TikTok&utm_term=22PETER" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="ultrawideImage"></span>
            <span class="link-text">
              LG 49" Ultrawide
            </span>
            <a href="https://www.amazon.com/dp/B09QD21693?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09QD21693&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="dualupImage"></span>
            <span class="link-text">
              LG Dual Up
            </span>
            <a href="https://www.amazon.com/dp/B09XTD5C7H?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09XTD5C7H&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="uperfectImage"></span>
            <span class="link-text">
              UPerfect O Portable Monitor
            </span>
            <a href="https://www.uperfectmonitor.com/products/oled-portable-monitor-4k-uperfect-o" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="ergearImage"></span>
            <span class="link-text">
              ErGear Monitor Mount
            </span>
            <a href="https://www.amazon.com/dp/B098JT9SFR?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B098JT9SFR&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="keyboardImage"></span>
            <span class="link-text">
              Yunzii Y275 Keyboard
            </span>
            <a href="https://www.yunzii.com/products/yunzii-yz75-wireless-mechanical-keyboard" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="gridstudioImage"></span>
            <span class="link-text">
              iPhone Frames
            </span>
            <a href="https://gridstudio.cc/products/grid®4s?source_type=sales_plugin_af&slt=sales_plugin_af&referral_code=JW7VNR69SBB7" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="goveeglideImage"></span>
            <span class="link-text">
              Govee Glide Wall Lights
            </span>
            <a href="https://www.amazon.com/dp/B091L21GZK?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B091L21GZK&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="goveehexImage"></span>
            <span class="link-text">
              Govee Glide Hexa Wall Lights
            </span>
            <a href="https://www.amazon.com/dp/B09FK1GSXY?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09FK1GSXY&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="grovemadeImage"></span>
            <span class="link-text">
              Grovemade Desk Shelf
            </span>
            <a href="https://grovemade.com/desk-shelf-system/" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="harmanImage"></span>
            <span class="link-text">
              Aura Studio 3
            </span>
            <a href="https://www.amazon.com/dp/B08F8292BT?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B08F8292BT&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="lametricImage"></span>
            <span class="link-text">
              Lametric TIME
            </span>
            <a href="https://store.lametric.com/products/lametric?variant=34703088974" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="deltahubImage"></span>
            <span class="link-text">
              Deltahub Carpio 2.0
            </span>
            <a href="https://www.amazon.com/dp/B098P8XPTX?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B098P8XPTX&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="benqImage"></span>
            <span class="link-text">
              BenQ Screenbar Halo
            </span>
            <a href="https://www.amazon.com/dp/B08WT889V3?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B08WT889V3&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="loupedeckImage"></span>
            <span class="link-text">
              Loupedeck Live
            </span>
            <a href="https://www.amazon.com/dp/B08F7RJYZV?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B08F7RJYZV&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="benqImage"></span>
            <span class="link-text">
              Logitech C920
            </span>
            <a href="https://www.amazon.com/dp/B006JH8T3S?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B006JH8T3S&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="mxmasterImage"></span>
            <span class="link-text">
              Logitech MX Master 3
            </span>
            <a href="https://www.amazon.com/dp/B07XC2FWD1?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B07XC2FWD1&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="neonbeachImage"></span>
            <span class="link-text">
              Neon Beach LED Sign
            </span>
            <a href="https://bit.ly/3U95RU6" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="pegboardImage"></span>
            <span class="link-text">
              IKEA Skadis Pegboards
            </span>
            <a href="https://www.amazon.com/dp/B07NQ1M73V?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B07NQ1M73V&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="quadlockImage"></span>
            <span class="link-text">
              Quadlock MAG Charger
            </span>
            <a href="https://www.amazon.com/dp/B0BHV1LD44?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B0BHV1LD44&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="caldigitImage"></span>
            <span class="link-text">
              Caldigit TS3 Plus
            </span>
            <a href="https://www.amazon.com/dp/B08F7CR49N?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B08F7CR49N&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="sonyImage"></span>
            <span class="link-text">
              Sony WH-1000XM4
            </span>
            <a href="https://www.amazon.com/dp/B0863TXGM3?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B0863TXGM3&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          
          <div class="link">
            <span class="link-image fill-image" :style="mercedesImage"></span>
            <span class="link-text">
              Mercedes A Class AMG
            </span>
            <a href="https://www.kunzmann.de/shop/en/accessory/model-cars/1-18-model-car-mercedes-benz-a-class-compactsedan-digital-white.htm" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          
          
          
          <div class="link">
            <span class="link-image fill-image" :style="fifineImage"></span>
            <span class="link-text">
              Fifine K658
            </span>
            <a href="https://www.amazon.com/dp/B09BNMJM2C?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09BNMJM2C&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          
          

        </div>
      </div>
    </div>


  </div>
</template>

<script>
import profile from "assets/img/profile.jpg";
import back from "assets/img/icons/back.svg";
import benq from "assets/img/setup23/benq.png";
import caldigit from "assets/img/setup23/caldigit.png";
import deltahub from "assets/img/setup23/deltahub.png";
import desk from "assets/img/setup23/desk.png";
import deskpad from "assets/img/setup23/deskpad.png";
import dualup from "assets/img/setup23/dualup.png";
import ergear from "assets/img/setup23/ergear.png";
import fifine from "assets/img/setup23/fifine.png";
import goveeglide from "assets/img/setup23/goveeglide.png";
import goveehex from "assets/img/setup23/goveehex.png";
import gridstudio from "assets/img/setup23/gridstudio.png";
import grovemade from "assets/img/setup23/grovemade.png";
import harman from "assets/img/setup23/harman.png";
import keyboard from "assets/img/setup23/keyboard.png";
import lametric from "assets/img/setup23/lametric.png";
import loupedeck from "assets/img/setup23/loupedeck.png";
import macbook from "assets/img/setup23/macbook.png";
import mercedes from "assets/img/setup23/mercedes.png";
import mxmaster from "assets/img/setup23/mxmaster.png";
import neonbeach from "assets/img/setup23/neonbeach.png";
import pegboard from "assets/img/setup23/pegboard.png";
import quadlock from "assets/img/setup23/quadlock.png";
import sihoo from "assets/img/setup23/sihoo.png";
import sony from "assets/img/setup23/sony.png";
import standingdesk from "assets/img/setup23/standingdesk.png";
import ultrawide from "assets/img/setup23/ultrawide.png";
import uperfect from "assets/img/setup23/uperfect.png";

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
      benqImage: { backgroundImage: `url(${benq})` },
      caldigitImage: { backgroundImage: `url(${caldigit})` },
      deltahubImage: { backgroundImage: `url(${deltahub})` },
      deskImage: { backgroundImage: `url(${desk})` },
      deskpadImage: { backgroundImage: `url(${deskpad})` },
      dualupImage: { backgroundImage: `url(${dualup})` },
      ergearImage: { backgroundImage: `url(${ergear})` },
      fifineImage: { backgroundImage: `url(${fifine})` },
      goveeglideImage: { backgroundImage: `url(${goveeglide})` },
      goveehexImage: { backgroundImage: `url(${goveehex})` },
      gridstudioImage: { backgroundImage: `url(${gridstudio})` },
      grovemadeImage: { backgroundImage: `url(${grovemade})` },
      harmanImage: { backgroundImage: `url(${harman})` },
      keyboardImage: { backgroundImage: `url(${keyboard})` },
      lametricImage: { backgroundImage: `url(${lametric})` },
      loupedeckImage: { backgroundImage: `url(${loupedeck})` },
      macbookImage: { backgroundImage: `url(${macbook})` },
      mercedesImage: { backgroundImage: `url(${mercedes})` },
      mxmasterImage: { backgroundImage: `url(${mxmaster})` },
      neonbeachImage: { backgroundImage: `url(${neonbeach})` },
      pegboardImage: { backgroundImage: `url(${pegboard})` },
      quadlockImage: { backgroundImage: `url(${quadlock})` },
      sihooImage: { backgroundImage: `url(${sihoo})` },
      sonyImage: { backgroundImage: `url(${sony})` },
      standingdeskImage: { backgroundImage: `url(${standingdesk})` },
      ultrawideImage: { backgroundImage: `url(${ultrawide})` },
      uperfectImage: { backgroundImage: `url(${uperfect})` },
      
    };
  }
};
</script>

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
              Desk Pad <br> <small><em>by Deltahub</em></small>
            </span>
            <a href="https://deltahub.io/collections/all-products?ref=peter" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="deltahubImage"></span>
            <span class="link-text">
              Wrist Rests Carpio 2.0 <br> <small><em>by Deltahub</em></small>
            </span>
            <a href="https://deltahub.io/collections/all-products?ref=peter" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="standingdeskImage"></span>
            <span class="link-text">
              Standing Desk by Dokk Store <br> <small><em>Solid wood, live edge - 180cm x 90cm</em></small>
            </span>
            <a href="https://dokk.store/?ref=h6ow9bjv" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="riserImage"></span>
            <span class="link-text">
              Laptop Riser by Dokk Store
            </span>
            <a href="https://dokk.store/?ref=h6ow9bjv" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="shelfImage"></span>
            <span class="link-text">
              Desk Shelf by Dokk Store
            </span>
            <a href="https://dokk.store/?ref=h6ow9bjv" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="keyboardImage"></span>
            <span class="link-text">
              MX Mechanical Mini (Grey) <br> <small><em>Keyboard by Logitech</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B09LK73VHG?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09LK73VHG&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ofs_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="sihooImage"></span>
            <span class="link-text">
              Ergonomic Chair<br> <small><em>V1 by Sihoo</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B0982RGW5Z?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B0982RGW5Z&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="nanoleafImage"></span>
            <span class="link-text">
              Wall lights by Nanoleaf <br> <small><em>Lines + Matte Black covers</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B09LWVWN8M?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09LWVWN8M&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ofs_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="macbookImage"></span>
            <span class="link-text">
              16" Macbook Pro M1 Max <br> <small><em>32GB RAM, 1TB Storage</em></small>
            </span>
            <a href="https://www.apple.com/shop/buy-mac/macbook-pro/16-inch-space-gray-10-core-cpu-32-core-gpu-1tb#" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="ultrawideImage"></span>
            <span class="link-text">
              49" Ultrawide Monitor by LG <br> <small><em>LG 49WL95C-WY (5120 x 1440)</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B09QD21693?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09QD21693&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="uperfectImage"></span>
            <span class="link-text">
              Portable Monitor (UPerfect 0)<br> <small><em>by UPERFECTMONITOR</em></small>
            </span>
            <a href="https://www.uperfectmonitor.com/products/oled-portable-monitor-4k-uperfect-o" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="gridstudioImage"></span>
            <span class="link-text">
              iPhone Frames <br> <small><em>by GridStudio</em></small>
            </span>
            <a href="https://gridstudio.cc/products/grid®4s?source_type=sales_plugin_af&slt=sales_plugin_af&referral_code=JW7VNR69SBB7" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="benqImage"></span>
            <span class="link-text">
              Screenbar Halo <br> <small><em>by BenQ</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B08WT889V3?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B08WT889V3&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="loupedeckImage"></span>
            <span class="link-text">
              Console by Loupedeck <br> <small><em>Loupedeck Live</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B08F7RJYZV?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B08F7RJYZV&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="mxmasterImage"></span>
            <span class="link-text">
              MX Master 3S <br> <small><em>Mouse by Logitech</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B0BS9VVQPD?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B0BS9VVQPD&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ofs_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="pegboardImage"></span>
            <span class="link-text">
              Pegboards from IKEA <br> <small><em>SKADIS</em></small>
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
              Caldigit TS4 Plus
            </span>
            <a href="https://www.amazon.com/dp/B09GK8LBWS?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09GK8LBWS&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ofs_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
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
              Microphone K658 by Fifine
            </span>
            <a href="https://www.amazon.com/dp/B09BNMJM2C?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B09BNMJM2C&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ons_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="ergotronImage"></span>
            <span class="link-text">
              Ergotron HX Monitor Arm
            </span>
            <a href="https://www.amazon.com/dp/B0959D7XDM?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B0959D7XDM&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ofs_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          
          <div class="link">
            <span class="link-image fill-image" :style="webcamImage"></span>
            <span class="link-text">
              360° Webcam <br> <small><em>Link by Insta360</em></small>
            </span>
            <a href="https://www.insta360.com/sal/link?insrc=INRWVK2" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          <div class="link">
            <span class="link-image fill-image" :style="rodeImage"></span>
            <span class="link-text">
              PSA1+ Studio boom arm  <br> <small><em>by Rodemic</em></small>
            </span>
            <a href="https://www.amazon.com/dp/B001D7UYBO?linkCode=ssc&tag=onamzpanayi0a-20&creativeASIN=B001D7UYBO&asc_item-id=amzn1.ideas.1YNZ82Q9EWNWS&ref_=aip_sf_list_spv_ofs_mixed_d_asin" target="_blank" class="btn btn-primary web-btn">Shop Now</a>
          </div>
          
          

        </div>
      </div>
    </div>


  </div>
</template>

<script>
import profile from "assets/img/profile.jpg";
import back from "assets/img/icons/back.svg";
import benq from "assets/img/setup23/benq.jpg";
import caldigit from "assets/img/setup23/caldigit.jpg";
import deltahub from "assets/img/setup23/deltahub.jpg";
import deskpad from "assets/img/setup23/deskpad.jpg";
import fifine from "assets/img/setup23/fifine.jpg";
import gridstudio from "assets/img/setup23/gridstudio.jpg";
import loupedeck from "assets/img/setup23/loupedeck.jpg";
import macbook from "assets/img/setup23/macbook.jpg";
import mercedes from "assets/img/setup23/mercedes.jpg";
import mxmaster from "assets/img/setup23/mxmaster.jpg";
import pegboard from "assets/img/setup23/pegboard.jpg";
import quadlock from "assets/img/setup23/quadlock.jpg";
import sihoo from "assets/img/setup23/sihoo.jpg";
import sony from "assets/img/setup23/sony.jpg";
import standingdesk from "assets/img/setup23/standingdesk.jpg";
import ultrawide from "assets/img/setup23/ultrawide.jpg";
import uperfect from "assets/img/setup23/uperfect.jpg";
import nanoleaf from "assets/img/setup23/nanoleaf.jpg";
import ergotron from "assets/img/setup23/ergotron.jpg";
import riser from "assets/img/setup23/dokkriser.jpg";
import shelf from "assets/img/setup23/shelf.jpg";
import keyboard from "assets/img/setup23/keyboard.jpg";
import webcam from "assets/img/setup23/webcam.jpg";
import rode from "assets/img/setup23/rodeboom.jpg";

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
      deskpadImage: { backgroundImage: `url(${deskpad})` },
      fifineImage: { backgroundImage: `url(${fifine})` },
      gridstudioImage: { backgroundImage: `url(${gridstudio})` },
      keyboardImage: { backgroundImage: `url(${keyboard})` },
      loupedeckImage: { backgroundImage: `url(${loupedeck})` },
      macbookImage: { backgroundImage: `url(${macbook})` },
      mercedesImage: { backgroundImage: `url(${mercedes})` },
      mxmasterImage: { backgroundImage: `url(${mxmaster})` },
      pegboardImage: { backgroundImage: `url(${pegboard})` },
      quadlockImage: { backgroundImage: `url(${quadlock})` },
      sihooImage: { backgroundImage: `url(${sihoo})` },
      sonyImage: { backgroundImage: `url(${sony})` },
      standingdeskImage: { backgroundImage: `url(${standingdesk})` },
      ultrawideImage: { backgroundImage: `url(${ultrawide})` },
      uperfectImage: { backgroundImage: `url(${uperfect})` },
      nanoleafImage: { backgroundImage: `url(${nanoleaf})` },
      ergotronImage: { backgroundImage: `url(${ergotron})` },
      riserImage: { backgroundImage: `url(${riser})` },
      shelfImage: { backgroundImage: `url(${shelf})` },
      keyboardImage: { backgroundImage: `url(${keyboard})` },
      webcamImage: { backgroundImage: `url(${webcam})` },
      rodeImage: { backgroundImage: `url(${rode})` },
    };
  }
};
</script>

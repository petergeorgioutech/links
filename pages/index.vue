<template>
  <div>
    <div class="container px-0 main-wrapper">
      <div class="row">
        <div class="col cover">
          <div class="placeholder"></div>
        </div>
      </div>
      <div class="container d-flex flex-column min-vh-70">
        <div class="row avi">
          <div class="col">
            <div class="text-center avatar rounded-circle">
              <div class="rounded-circle" :style="profileImage"></div>
            </div>
          </div>
        </div>
        <div class="row justify-content-center mb-1">
          <div class="col-10 text-center py-2">
            <h1 class="username">Peter Georgiou</h1>
            <p class="description">Frontend Web Developer | Content Creator <span class="small-type">@peterpandev</span>
            </p>
            <ul class="socials-wrapper">
              <li><a href="//instagram.com/peterpandev" target="blank" :style="instagramImage"><span
                    class="icon-instagram"></span></a></li>
              <li><a href="https://www.tiktok.com/@peterpandeveloper" target="blank" :style="tiktokImage"><span
                    class="icon-tiktok"></span></a></li>
              <li><a href="//links.petergeorgiou.tech/youtube" target="blank" :style="youtubeImage"><span
                    class="icon-youtube"></span></a></li>
              <li><a href="//www.amazon.com/shop/peterpandev/list/1YNZ82Q9EWNWS?ref_=aip_sf_list_spv_ofs_mixed_d"
                  target="blank" :style="amazonImage"><span class="icon-amazon"></span></a></li>
              <li><a href="mailto:hello@petergeorgiou.tech" target="blank" :style="emailImage"><span
                    class="icon-email"></span></a></li>
            </ul>
            <!-- <a href="mailto:peter@petergeorgiou.tech" class="status accepting">
              Accepting <span class="project_type">Brand Collaborations</span>
            </a> -->
          </div>

          <div class="col-12 text-center mt-2 mb-4">
            <div class="embed-responsive embed-responsive-16by9">
              <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/XyWENE4JfdI?si=MyijmQcYMAHru3MG"
                allowfullscreen></iframe>
            </div>
          </div>

          <!-- <div class="col-12 text-center mt-2 mb-4">
            <div class="embed-responsive embed-responsive-16by9">
              <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/CzYe6oh96mw" allowfullscreen></iframe>
            </div>
          </div> -->

          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://www.insta360.com/sal/go-3?insrc=INRWVK2" target="_blank">
                <span class="image" :style="go3Feature"></span>
                <span class="content">
                  <span class="featured-title"><b>Insta360 GO 3</b> <br> <b>BLACK FRIDAY</b><br> <small>Free t-shirt,
                      carry case and 5% off to the first 20 orders</small></span>
                  <span class="featured-button btn btn-primary btn-sm">GET OFFER</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->

          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://brandstore.rode.com/products/podcaster-bundle-white-collection?sca_ref=4474187.QDKA4sS45d" target="_blank">
                <span class="image" :style="rodeFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>RODE</b> <b>LIMITED EDITION</b><br> <small>WHITE BUNDLE</small></span>
                  <span class="featured-button btn btn-primary btn-sm">GET OFFER</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->

          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://shop.minimaldesksetups.com/products/task-time-bundle?sca_ref=1578836.V3jOBkjkyk&utm_source=affiliate&utm_medium=1578836&utm_campaign=panayiotis-georgiou" target="_blank">
                <span class="image" :style="mdsFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>TASK & TIME by MDS</b></span>
                  <span class="featured-button btn btn-primary btn-sm">SHOP NOW</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->

          <!-- <div class="col-12 text-center mt-2 mb-4">
            <div class="embed-responsive embed-responsive-16by9">
              <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/HPuFyrSX0W8?si=d9_qCANKx2oP8mBm"
                allowfullscreen></iframe>
            </div>
          </div> -->
          
          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://shop.minimaldesksetups.com/products/essential-oil-humidifier?sca_ref=1578836.V3jOBkjkyk&utm_source=affiliate&utm_medium=1578836&utm_campaign=panayiotis-georgiou" target="_blank">
                <span class="image" :style="mdsoilsFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>ESSENTIAL OIL HUMIDIFIER by MDS</b></span>
                  <span class="featured-button btn btn-primary btn-sm">SHOP NOW</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->
          
          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://shop.minimaldesksetups.com/products/pomodoro-timer?sca_ref=1578836.V3jOBkjkyk&utm_source=affiliate&utm_medium=1578836&utm_campaign=panayiotis-georgiou" target="_blank">
                <span class="image" :style="mdspomodoroFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>POMODORO TIMER by MDS</b></span>
                  <span class="featured-button btn btn-primary btn-sm">SHOP NOW</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->
          
          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://gridstudio.cc/products/grid-macbook-air-1st-generation?source_type=sales_plugin_af&slt=sales_plugin_af&referral_code=JW7VNR69SBB7" target="_blank">
                <span class="image" :style="gridFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>Macbook Air (1st Gen)</b> <br>by Grid&reg; <br> <small>10% off with code PETERPANDEV</small></span>
                  <span class="featured-button btn btn-primary btn-sm">SHOP NOW</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->
          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://ascrono.com/products/ascrono-cablecare-tray?ref=PETERPANDEV" target="_blank">
                <span class="image" :style="ascronoCableFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>Ascrono® CableCare Tray</b></span>
                  <span class="featured-button btn btn-primary btn-sm">SHOP NOW</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->
          
          <!-- <div class="col-12">
            <div class="featured-item-static widen">
              <a href="https://www.balolo.de/?ref=peterpandev" target="_blank">
                <span class="image" :style="baloloFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>SETUP COCKPIT</b> <br><small><b>10% OFF</b> <br> with code PETERPANDEV</small></span>
                  <span class="featured-button btn btn-primary btn-sm">SHOP NOW</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div> -->

          <!-- <div class="featured-item-static">
              <a href="http://go.deltahub.io/443wpdS" target="_blank">
                <span class="image" :style="deltahubFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>Deltahub</b> <br> REO COLLECTION</span>
                  <span class="featured-button btn btn-primary btn-sm">Shop Now</span>
                </span>
                <span class="star"></span>
              </a>
            </div> -->


          <!-- <div class="col-12 text-center mt-2 mb-4">
            <div class="embed-responsive embed-responsive-16by9">
              <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/76lHoB7H9ww"
                allowfullscreen></iframe>
            </div>
          </div> -->
          <!-- <div class="col-12 text-center mt-2 mb-4">
            <div class="embed-responsive embed-responsive-16by9">
              <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/yPUX2z16uDM"
                allowfullscreen></iframe>
            </div>
          </div> -->
         

        </div>

        <!-- <hr class="w-50 border border-grey mt-2 mb-2" style="opacity:0.75"> -->



        <!-- <div class="row">
          <div class="col-12">
            <div class="featured-item-static">
              <a href="https://pieces.app/"
                target="_blank">
                <span class="image" :style="piecesFeature"></span>
                <span class="content">
                  <span class="featured-title"><b>Pieces</b> <br> for Developers</span>
                  <span class="featured-button btn btn-primary btn-sm">SIGN UP FOR FREE</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div>
        </div> -->

        <!-- <div class="row">
          <div class="col-12">
            <div class="featured-item-static">
              <a href="https://www.autonomous.ai/standing-desks/smartdesk-2-business?utm_source=pr&utm_medium=influencer&utm_campaign=growth&utm_content=Instagram&utm_term=22PETER"
                target="_blank">
                <span class="image" :style="smartdeskproFeature"></span>
                <span class="content">
                  <span class="featured-title">SmartDesk Pro</span>
                  <span class="featured-button btn btn-primary btn-sm">Shop now</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div>
        </div> -->

        <!-- <div class="row">
          <div class="col-12">
            <div class="featured-item-static">
              <a href="https://www.insta360.com/sal/flow?insrc=INRWVK2"
                target="_blank">
                <span class="image" :style="flowFeature"></span>
                <span class="content">
                  <span class="featured-title">Insta360 Flow</span>
                  <span class="featured-button btn btn-primary btn-sm">Shop now</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div>
        </div> -->

        <!-- <div class="row">
          <div class="col-12">
            <div class="featured-item-static">
              <a href="https://www.omnicharge.co/pages/shop?sca_ref=3407976.dM2IxUAsxW"
                target="_blank">
                <span class="image" :style="omniFeature"></span>
                <span class="content">
                  <span class="featured-title">Omni 20C+</span>
                  <span class="featured-button btn btn-primary btn-sm">Shop now</span>
                </span>
                <span class="star"></span>
              </a>
            </div>
          </div>
        </div> -->

        <div class="row mb-3 featured-items">
          <a href="https://peterpandev.gumroad.com/l/start-learning-how-to-code"
            target="_blank" class="featured-item" :style="ebookImage">
            <span class="featured-title">Get my E-book ✨</span>
          </a>
          <nuxt-link to="/setup" class="featured-item" :style="setupImage">
            <span class="featured-title">My Setup Gear</span>
          </nuxt-link>
          <nuxt-link to="/get-in-touch" class="featured-item" :style="profileImage">
            <span class="featured-title">Get In Touch</span>
          </nuxt-link>
          <a href="https://vscodethemes.com/e/morgan-codes.morgan-codes-vscode-theme" target="_blank"
            class="featured-item" :style="vsCodeImage">
            <span class="featured-title">VS Code Theme</span>
          </a>
        </div>


        <div class="row content-wrapper">
          <div class="col-10 offset-1 links">
            <nuxt-link to="/promotions" class="link">
              <span class="link-image" :style="couponImage"
                style="background-size:70%;background-position:center center;"></span>
              <span class="link-text">Discount Codes</span>
              <span class="arrow"></span>
            </nuxt-link>
          </div>
          <div class="col-10 offset-1 links">
            <nuxt-link to="/partners" class="link">
              <span class="link-image" :style="partnersImage"
                style="background-size:contain;background-position:center center;"></span>
              <span class="link-text">Brand Partners</span>
              <span class="arrow"></span>
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
    <div>
      <b-modal id="modal-1" title="Coming Soon ✨" hide-footer>
        <div class="row">
          <div class="col-12">
            <img class="book-cover img-fluid" src="~/assets/img/ebooksnapshot.png" />
            <h3 class="title text-center mb-3 h4 mt-3">Sign up below to be the first to know when the E-Book is released!
            </h3>
          </div>
          <div class="col-12">
            <link href="//cdn-images.mailchimp.com/embedcode/classic-071822.css" rel="stylesheet" type="text/css">
            <div id="mc_embed_signup">
              <form
                action="https://tech.us21.list-manage.com/subscribe/post?u=cef0d5f27e1a3959c4d32cea8&amp;id=caa488f38c&amp;f_id=0070c1e1f0"
                method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate"
                target="_blank" novalidate>
                <div id="mc_embed_signup_scroll">
                  <div class="mc-field-group">
                    <label for="mce-EMAIL">Email Address <span class="asterisk">*</span>
                    </label>
                    <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL" required>
                    <span id="mce-EMAIL-HELPERTEXT" class="helper_text"></span>
                  </div>
                  <div class="mc-field-group">
                    <label for="mce-FNAME">First Name </label>
                    <input type="text" value="" name="FNAME" class="" id="mce-FNAME">
                    <span id="mce-FNAME-HELPERTEXT" class="helper_text"></span>
                  </div>
                  <div id="mce-responses" class="clear foot">
                    <div class="response" id="mce-error-response" style="display:none"></div>
                    <div class="response" id="mce-success-response" style="display:none"></div>
                  </div>
                  <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
                  <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text"
                      name="b_cef0d5f27e1a3959c4d32cea8_caa488f38c" tabindex="-1" value=""></div>
                  <div class="optionalParent">
                    <div class="clear foot">
                      <input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button">
                      <p class="brandingLogo"><a href="http://eepurl.com/icGc9z"
                          title="Mailchimp - email marketing made easy and fun"><img
                            src="https://eep.io/mc-cdn-images/template_images/branding_logo_text_dark_dtp.svg"></a></p>
                    </div>
                  </div>
                </div>
              </form>
            </div>
            <script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script>
            <script type='text/javascript'>
              (function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';fnames[3]='ADDRESS';ftypes[3]='address';fnames[4]='PHONE';ftypes[4]='phone';fnames[5]='BIRTHDAY';ftypes[5]='birthday';}(jQuery));var $mcj = jQuery.noConflict(true);
            </script>
            <!--End mc_embed_signup-->
          </div>
        </div>

      </b-modal>

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
import instagram from "assets/img/instagram.png";
import youtube from "assets/img/youtube.png";
import tiktok from "assets/img/tiktok.png";
import amazon from "assets/img/icons/amazon.png";
import email from "assets/img/email.png";
import quadlock from "assets/img/brands/quadlock.jpg";
import neon from "assets/img/brands/neonbeach.jpg";
import ebook from "assets/img/ebooksnapshot.png";
import cloudways from "assets/img/brands/cloudways.jpg";
import nanlite from "assets/img/brands/nanlite.png";
import link from "assets/img/brands/link.jpg";
import standingdesk from "assets/img/setup23/standingdesk.jpg";
import pitakafeature from "assets/img/features/pitaka.jpg";
// import deltahubfeature from "assets/img/setup23/deltahub.jpg";
import omnifeature from "assets/img/features/omnicharge.jpg";
import dorofeature from "assets/img/setup23/doro.jpg";
import flowfeature from "assets/img/features/flow.jpg";
import smartdeskprofeature from "assets/img/smartdeskpro.jpg";
import piecesfeature from "assets/img/features/pieces.jpg";
import ascronofeature from "assets/img/features/ascrono.jpg";
import deltahubfeature from "assets/img/deltahubreo.png";
import go3feature from "assets/img/features/go3.png";
import rodefeature from "assets/img/features/rode.jpg";
import balolofeature from "assets/img/features/balolo.jpeg";
import mdsfeature from "assets/img/features/taskandtime.jpg";
import mdspadfeature from "assets/img/features/mds.jpg";
import mdsoilsfeature from "assets/img/features/oils.jpg";
import mdspomodorofeature from "assets/img/features/pomodoro.jpg";
import gridfeature from "assets/img/features/grid.png";
import ascronocableFeature from "assets/img/features/ascronocable.png";

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
      instagramImage: { backgroundImage: `url(${instagram})` },
      tiktokImage: { backgroundImage: `url(${tiktok})` },
      youtubeImage: { backgroundImage: `url(${youtube})` },
      amazonImage: { backgroundImage: `url(${amazon})` },
      emailImage: { backgroundImage: `url(${email})` },
      quadlockImage: { backgroundImage: `url(${quadlock})` },
      neonImage: { backgroundImage: `url(${neon})` },
      ebookImage: { backgroundImage: `url(${ebook})` },
      cloudwaysImage: { backgroundImage: `url(${cloudways})` },
      nanliteImage: { backgroundImage: `url(${nanlite})` },
      linkImage: { backgroundImage: `url(${link})` },
      standingdeskImage: { backgroundImage: `url(${standingdesk})` },
      pitakaFeature: { backgroundImage: `url(${pitakafeature})` },
      deltahubFeature: { backgroundImage: `url(${deltahubfeature})` },
      omniFeature: { backgroundImage: `url(${omnifeature})` },
      doroFeature: { backgroundImage: `url(${dorofeature})` },
      flowFeature: { backgroundImage: `url(${flowfeature})` },
      smartdeskproFeature: { backgroundImage: `url(${smartdeskprofeature})` },
      piecesFeature: { backgroundImage: `url(${piecesfeature})` },
      ascronoFeature: { backgroundImage: `url(${ascronofeature})` },
      deltahubFeature: { backgroundImage: `url(${deltahubfeature})` },
      go3Feature: { backgroundImage: `url(${go3feature})` },
      rodeFeature: { backgroundImage: `url(${rodefeature})` },
      baloloFeature: { backgroundImage: `url(${balolofeature})` },
      mdsFeature: { backgroundImage: `url(${mdsfeature})` },
      mdspadFeature: { backgroundImage: `url(${mdspadfeature})` },
      mdsoilsFeature: { backgroundImage: `url(${mdsoilsfeature})` },
      mdspomodoroFeature: { backgroundImage: `url(${mdspomodorofeature})` },
      gridFeature: { backgroundImage: `url(${gridfeature})` },
      ascronoCableFeature: { backgroundImage: `url(${ascronocableFeature})` },
    };
  }
};
</script>

<style>
.featured-item-static.widen a .image {
  width: 290px;
  height: 200px;
  border-radius: 1rem;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
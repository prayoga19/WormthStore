<template>
  <div class="home">
    <HeaderWormth />
    <HeroWormth />
    <BannerWormth />
    <InstaWormth />
    <PartnerWormth />
    <FooterWormth />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderWormth from "../components/HeaderWormth.vue";
import HeroWormth from "../components/HeroWormth.vue";
import BannerWormth from "../components/BannerWormth.vue";
import InstaWormth from "../components/InstaWormth.vue";
import PartnerWormth from "../components/PartnerWormth.vue";

import FooterWormth from "../components/FooterWormth.vue";

export default {
  name: "Home",
  components: {
    HeaderWormth,
    HeroWormth,
    BannerWormth,
    InstaWormth,
    PartnerWormth,
    FooterWormth,
  },
};
</script>

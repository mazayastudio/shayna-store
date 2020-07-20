<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBanner />
    <InstagramShayna />
    <PartnerShayna />
  </div>
</template>

<script>
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomenBanner from "@/components/WomenBanner.vue";
import InstagramShayna from "@/components/InstagramShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBanner,
    InstagramShayna,
    PartnerShayna,
  },
};
</script>

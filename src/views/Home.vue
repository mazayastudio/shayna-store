<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBanner />
    <InstagramShayna />
  </div>
</template>

<script>
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomenBanner from "@/components/WomenBanner.vue";
import InstagramShayna from "@/components/InstagramShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBanner,
    InstagramShayna,
  },
};
</script>

<template>
  <div class="product">
    <HeaderShayna />
    <FooterShayna />
  </div>
</template>

<script>
import HeaderShayna from "@/components/HeaderShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "product",
  components: {
    HeaderShayna,
    FooterShayna,
  },
};
</script>

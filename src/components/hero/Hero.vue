<template>
  <div class="block-wrapp hero__container">
    <HeroHeader />
    <HeroInformation />
    <HeroButton />
    <div class="hero__scroll-down" />
  </div>
</template>

<script>
import HeroHeader from "@/components/hero/HeroHeader/HeroHeader";
import HeroInformation from "@/components/hero/HeroInformation/HeroInformation";
import HeroButton from "@/components/hero/HeroButton/HeroButton";
export default {
  name: "HeroBlock",
  components: {
    HeroHeader,
    HeroInformation,
    HeroButton,
  }
}
</script>

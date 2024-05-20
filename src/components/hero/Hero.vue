<template>
  <div class="block-wrapp hero__container">
    <HeroPicture />
    <HeroHeader />
    <HeroInformation />
    <HeroButton />
    <div class="hero__scroll-down" />
  </div>
</template>

<script>
import "./__hero.css";

import HeroHeader from "@/components/hero/HeroHeader/HeroHeader";
import HeroInformation from "@/components/hero/HeroInformation/HeroInformation";
import HeroButton from "@/components/hero/HeroButton/HeroButton";
import HeroPicture from "@/components/hero/HeroPicture/HeroPicture";

export default {
  name: "HeroBlock",
  components: {
    HeroHeader,
    HeroInformation,
    HeroButton,
    HeroPicture
  }
}
</script>

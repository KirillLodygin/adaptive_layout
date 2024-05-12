<template>
  <div class="block-wrapp">
    <SectionHeader />
    <div class="promises__container">
      <FirstPromiseBlock />
      <ThreeDots />
      <SecondPromiseBlock />
      <ThreeDots />
      <ThirdPromiseBlock />
    </div>
  </div>
</template>

<script>
import SectionHeader from "@/components/ui/SectionHeader";
import FirstPromiseBlock from "@/components/promises/PromiseBlock/FirstPromiseBlock";
import ThreeDots from "@/components/promises/ThreeDots/ThreeDots";
import SecondPromiseBlock from "@/components/promises/PromiseBlock/SecondPromiseBlock";
import ThirdPromiseBlock from "@/components/promises/PromiseBlock/ThirdPromiseBlock";

export default {
  name: "PromisesBlock",
  components: {
    SectionHeader,
    FirstPromiseBlock,
    SecondPromiseBlock,
    ThirdPromiseBlock,
    ThreeDots
  }
}
</script>

<style scoped>

</style>
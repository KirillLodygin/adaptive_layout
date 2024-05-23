<template>
  <div class="block-wrapp honest-block">
    <div class="services-picture-wrapp">
      <img src="@/assets/img/leaves_2.png" loading="lazy" alt="">
    </div>
    <SectionHeader />
    <CostInformation />
  </div>
</template>

<script>
import "./__services.css";

import SectionHeader from "@/components/ui/SectionHeader";
import CostInformation from "@/components/ui/CostInformation/CostInformation";

export default {
  name: "ServicesBlock",
  components: {
    SectionHeader,
    CostInformation,
  }
}
</script>

<style scoped>

</style>
<template>
  <div class="block-wrapp honest-block">
    <SectionHeader />
    <CostInformation />
  </div>
</template>

<script>
import SectionHeader from "@/components/ui/SectionHeader";
import CostInformation from "@/components/ui/CostInformation/CostInformation";

export default {
  name: "ServicesBlock",
  components: {
    SectionHeader,
    CostInformation
  }
}
</script>

<style scoped>

</style>
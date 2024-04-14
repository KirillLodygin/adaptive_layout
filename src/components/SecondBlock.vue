<template>
  <div class="block-wrapp leaves-1">
    <SectionHeader />
    <div class="information-blocks-wrapp">
      <InformationBlock />
      <InformationBlock />
      <InformationBlock />
    </div>
  </div>
</template>

<script>
import SectionHeader from "@/components/SectionHeader";
import InformationBlock from "@/components/InformationBlock";
export default {
  name: "FirstBlock",
  components: {
    SectionHeader,
    InformationBlock,
  }
}
</script>
<template>
  <div class="cost-information__container">
    <InformationBlock />
    <InformationBlock />
    <InformationBlock />
  </div>
</template>

<script>
import InformationBlock from "@/components/ui/InformationBlock";
export default {
  name: "CostInformation",
  components: {
    InformationBlock
  }
}
</script>

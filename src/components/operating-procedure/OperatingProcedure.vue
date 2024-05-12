<template>
  <div class="block-wrapp">
    <SectionHeader />
    <OperatingProcedureInformation />
  </div>
</template>

<script>
import SectionHeader from "@/components/ui/SectionHeader";
import OperatingProcedureInformation
  from "@/components/operating-procedure/OperatingProcedureInformation/OperatingProcedureInformation";

export default {
  name: "OperatingProcedure",
  components: {
    SectionHeader,
    OperatingProcedureInformation
  }
}
</script>

<style scoped>

</style>
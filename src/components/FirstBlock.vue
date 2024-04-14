<template>
  <div class="block-wrapp first-block">
    <MainHeaderBlock />
    <FirstBlockInformation />
    <OrderButtonBlock />
  </div>
</template>

<script>
import MainHeaderBlock from "@/components/MainHeaderBlock";
import FirstBlockInformation from "@/components/FirstBlockInformation";
import OrderButtonBlock from "@/components/OrderButtonBlock";
export default {
  name: "FirstBlock",
  components: {
    MainHeaderBlock,
    FirstBlockInformation,
    OrderButtonBlock,
  }
}
</script>

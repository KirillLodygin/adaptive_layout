<template>
  <div class="order-button-wrapp">
    <div class="btn-wrapp">
      <BlackButton />
    </div>
    <div class="line-wrapp">
      <div class="line"/>
    </div>
  </div>
</template>

<script>
import BlackButton from "@/components/BlackButton";
export default {
  name: "OrderButtonBlock",
  components: {
    BlackButton
  }
}
</script>

<template>
  <div>
    <div class="order-button-wrapp">
      <div class="info-action">
        Акция: <span class="bold-text">при стоимости работ по расчету сметы от 10 000,00 руб. КС-2, КС-3 в подарок.</span>
      </div>
      <div class="btn-wrapp">
        <BlackButton />
      </div>
      <div class="line-wrapp">
        <div class="line"/>
      </div>
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

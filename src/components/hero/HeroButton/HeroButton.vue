<template>
  <div>
    <div class="hero-button__container">
      <div class="hero-button__info">
        Акция: <span class="bold-text">при стоимости работ по расчету сметы от 10 000,00 руб. КС-2, КС-3 в подарок.</span>
      </div>
      <div class="hero-button__btn-wrapp">
        <BlackButton />
      </div>
      <div class="hero-button__line-wrapp">
        <div class="hero-button__line"/>
      </div>
    </div>
  </div>
</template>

<script>
import "./__hero-button.css";

import BlackButton from "@/components/ui/BlackButton";
export default {
  name: "HeroButton",
  components: {
    BlackButton
  }
}
</script>

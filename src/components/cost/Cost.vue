<template>
  <div class="block-wrapp cost__container">
    <CostPicture />
    <SectionHeader />
    <CostInformation />
    <p class="cost__normal-text">Проектно-изыскательские работы – 4 000,00 рублей (за раздел сметы);</p>
    <p class="cost__big-text">Расчеты производятся с применением сметных<br/> программных комплексов
      «<span class="bold-text">Смета ру</span>» и «<span class="bold-text">Турбо сметчик</span>».</p>
    <p class="cost__normal-text">Для получения стоимости по вашему проекту – напишите нам</p>
    <div class="cost__black-button-wrapp">
      <BlackButton />
    </div>
  </div>
</template>

<script>
import "./__cost.css";

import SectionHeader from "@/components/ui/SectionHeader";
import CostInformation from "@/components/ui/CostInformation/CostInformation";
import BlackButton from "@/components/ui/BlackButton";
import CostPicture from "@/components/cost/CostPicture/CostPicture";

export default {
  name: "CostBlock",
  components: {
    SectionHeader,
    CostInformation,
    BlackButton,
    CostPicture
  }
}
</script>
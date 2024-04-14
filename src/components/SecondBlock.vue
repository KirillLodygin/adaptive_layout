<template>
  <div class="block-wrapp leaves-1">
    <SectionHeader />
    <div class="information-blocks-wrapp">
      <InformationBlock offset="" />
      <InformationBlock offset="offset-1" />
      <InformationBlock offset="offset-2" />
    </div>
    <p class="normal-text">Проектно-изыскательские работы – 4 000,00 рублей (за раздел сметы);</p>
    <p class="big-text">Расчеты производятся с применением сметных программных комплексов
      «<span class="bold-text">Смета ру</span>» и «<span class="bold-text">Турбо сметчик</span>».</p>
    <p class="normal-text">Для получения стоимости по вашему проекту – напишите нам</p>
    <div class="black-button-wrapp">
      <BlackButton />
    </div>
  </div>
</template>

<script>
import SectionHeader from "@/components/SectionHeader";
import InformationBlock from "@/components/InformationBlock";
import BlackButton from "@/components/BlackButton";
export default {
  name: "FirstBlock",
  components: {
    SectionHeader,
    InformationBlock,
    BlackButton
  }
}
</script>
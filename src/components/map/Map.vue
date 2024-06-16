<template>
  <div class="map__container">
    <div class="map-picture">
      <div id="map"></div>
    </div>
    <div class="map__info-wrapp">
      <div class="map__info">
        <p class="map__info-header">Свяжитесь с нами</p>
        <p class="map__info-text">
          <span class="bold-text">+7 900 000 00 00</span>
        </p>
        <p class="map__info-text">
          info@companymail.ru
        </p>
        <p class="map__info-text">
          134000, Москва, Большая Академическая 12 корп 2
        </p>
        <p class="map__info-text">
          Общество с ограниченной ответственностью «Сметчик Рус»
        </p>
        <p class="map__info-text">
          ОГРН/ИНН 11920284320283820 / 502440802827
        </p>
      </div>
    </div>
    <div class="map__copy">
      <div>
        <p class="map__slitename">
          © 2019 «Slitename»
        </p>
        <p class="map__agreement">
          Соглашение на обработку персональных данных
        </p>
      </div>
      <div class="map__developed">
        <div class="developed-logo">
          <img src="@/assets/img/3owls.png" loading="lazy" alt="">
        </div>
        <p class="map__agreement">
          Сайт разработали в агентстве 3owls
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import "./__map.css";

export default {
  name: "MapBlock"
}
</script>

<style scoped>

</style>
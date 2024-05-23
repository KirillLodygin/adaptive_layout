<template>
  <div class="block-wrapp honest-block">
    <SectionHeader />
    <div class="company__about">
      <span class="bold-text">Супе- смета</span> - Сайт рыбатекст поможет дизайнеру, верстальщику, вебмастеру
      сгенерировать несколько абзацев более менее осмысленного текста рыбы на русском языке, а начинающему оратору
      отточить навык публичных выступлений в домашних условиях. При создании генератора мы использовали небезизвестный
      универсальный код речей. Текст генерируется абзацами случайным образом
    </div>
    <div class="company__reasons">
      <FirstCompanyReason />
      <SecondCompanyReason />
      <ThirdCompanyReason />
      <FourthCompanyReason />
    </div>
    <div class="company__logo-lyne">
      <FirstCompanyLogo />
      <SecondCompanyLogo />
      <ThirdCompanyLogo />
      <FourthCompanyLogo />
      <FifthCompanyLogo />
      <SixthCompanyLogo />
    </div>
  </div>
</template>

<script>
import "./__company.css";

import SectionHeader from "@/components/ui/SectionHeader";
import FirstCompanyReason from "@/components/company/CompanyReason/FirstCompanyReason";
import SecondCompanyReason from "@/components/company/CompanyReason/SecondCompanyReason";
import ThirdCompanyReason from "@/components/company/CompanyReason/ThirdCompanyReason";
import FourthCompanyReason from "@/components/company/CompanyReason/FourthCompanyReason";
import FirstCompanyLogo from "@/components/company/CompanyLogo/FirstCompanyLogo";
import SecondCompanyLogo from "@/components/company/CompanyLogo/SecondCompanyLogo";
import ThirdCompanyLogo from "@/components/company/CompanyLogo/ThirdCompanyLogo";
import FourthCompanyLogo from "@/components/company/CompanyLogo/FourthCompanyLogo";
import FifthCompanyLogo from "@/components/company/CompanyLogo/FifthCompanyLogo";
import SixthCompanyLogo from "@/components/company/CompanyLogo/SixthCompanyLogo";

export default {
  name: "CompanyBlock",
  components: {
    SectionHeader,
    FirstCompanyReason,
    SecondCompanyReason,
    ThirdCompanyReason,
    FourthCompanyReason,
    FirstCompanyLogo,
    SecondCompanyLogo,
    ThirdCompanyLogo,
    FourthCompanyLogo,
    FifthCompanyLogo,
    SixthCompanyLogo
  }
}
</script>

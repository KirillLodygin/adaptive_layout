<template>
  <HeroBlock />
  <CostBlock />
  <OperatingProcedure />
  <ServicesBlock />
  <PromisesBlock />
  <CompanyBlock />
  <MapBlock />
</template>

<script>
import HeroBlock from "@/components/hero/Hero";
import CostBlock from "@/components/cost/Cost";
import OperatingProcedure from "@/components/operating-procedure/OperatingProcedure";
import ServicesBlock from "@/components/services/Services";
import PromisesBlock from "@/components/promises/Promises";
import CompanyBlock from "@/components/company/Company";
import MapBlock from "@/components/map/Map";

export default {
  name: 'App',
  components: {
    HeroBlock,
    CostBlock,
    OperatingProcedure,
    ServicesBlock,
    PromisesBlock,
    CompanyBlock,
    MapBlock
  }
}
</script>


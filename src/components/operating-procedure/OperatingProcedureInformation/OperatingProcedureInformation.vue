<template>
  <div class="operating-procedure-information__container">
    <div class="operating-procedure-information__steps-container">
      <div class="operating-procedure-information__steps">
        <OperatingProcedureStep />
        <OperatingProcedureStep />
        <OperatingProcedureStep />
      </div>
      <div class="operation-procedure-step__instruction">
        Подготовьте исходные данные для составления сметы
        (проектные решения, осмечиваемые тома с ведомостями материалов, спецификацией оборудования и другими необходимыми данными).
      </div>
    </div>
    <OperatingProcedureAttention />
  </div>
</template>

<script>
import "./__operating-procedure-information.css";

import OperatingProcedureStep
  from "@/components/operating-procedure/OperatingProcedureInformation/OperatingProcedureStep/OperatingProcedureStep";
import OperatingProcedureAttention
  from "@/components/operating-procedure/OperatingProcedureAttention/OperatingProcedureAttention";
export default {
  name: "OperatingProcedureInformation",
  components: {
    OperatingProcedureStep,
    OperatingProcedureAttention
  }
}
</script>

<style scoped>

</style>
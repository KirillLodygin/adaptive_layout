<template>
  <div class="information-block-wrapp">
    <div class="blocks-wrapp">
      <div class="frame information-block">
        <BlockHeader />
        <BlockTextList />
        <YellowButton />
      </div>
      <YellowFrame />
    </div>
  </div>
</template>

<script>
import YellowFrame from "@/components/YellowFrame";
import YellowButton from "@/components/YellowButton";
import BlockHeader from "@/components/BlockHeader";
import BlockTextList from "@/components/BlockTextList";

export default {
  name: "InformationBlock",
  components: {
    YellowFrame,
    YellowButton,
    BlockHeader,
    BlockTextList,
  },
}
</script>

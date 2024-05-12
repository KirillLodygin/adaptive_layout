<template>
  <div class="information-block-wrapp">
    <div class="frame information-block">
      <BlockHeader />
      <BlockTextList />
      <YellowButton />
    </div>
  </div>
</template>

<script>
import YellowButton from "@/components/ui/YellowButton";
import BlockHeader from "@/components/ui/BlockHeader";
import BlockTextList from "@/components/ui/BlockTextList";

export default {
  name: "InformationBlock",
  components: {
    YellowButton,
    BlockHeader,
    BlockTextList,
  },
}
</script>

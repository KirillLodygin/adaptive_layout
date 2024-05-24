<template>
  <div class="information-block-wrapp">
    <div class="frame information-block">
      <BlockHeader />
      <BlockTextList />
      <div class="yellow-button-wrapp">
        <YellowButton />
      </div>
    </div>
  </div>
</template>

<script>
import "./__ui.css";

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

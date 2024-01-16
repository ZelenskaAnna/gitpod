<template>
  <HeaderBlock />
  <div class="container">
    <WelcomeBlock />
    <SelectBlock />
    <ThinkBlock />
    <SecureBlock />
    <StatisticsBlock />
    <StartBlock />
  </div>
  <FooterBlock />
</template>

<script>
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import WelcomeBlock from "@/components/WelcomeBlock/WelcomeBlock.vue";
import SelectBlock from "@/components/SelectBlock.vue";
import ThinkBlock from "@/components/ThinkBlock/ThinkBlock.vue";
import SecureBlock from "@/components/SecureBlock/SecureBlock.vue";
import StatisticsBlock from "@/components/StatisticsBlock/StatisticsBlock.vue";
import StartBlock from "@/components/StartBlock/StartBlock.vue";
import FooterBlock from "@/components/FooterBlock/FooterBlock.vue";

export default {
  name: "HomePage",
  data() {
    return {
      isChecked: false,
    };
  },
  methods: {},
  components: {
    HeaderBlock,
    WelcomeBlock,
    SelectBlock,
    ThinkBlock,
    SecureBlock,
    StatisticsBlock,
    StartBlock,
    FooterBlock,
  },
};
</script>

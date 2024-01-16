<template>
  <section class="statistics">
    <h2 class="statistics__title">Used by 400,000+ developers.</h2>
    <div class="statistics__list">
      <div class="statistics__card">
        <SwiperBlock />
      </div>

    </div>
    <div class="statistics__logo">
      <img src="@/assets/gitLab2.svg" alt="GitLab" />
      <img src="@/assets/freeCode.svg" alt="FreeCode" />
      <img src="@/assets/dWave.svg" alt="dWave" />
      <img src="@/assets/google2.svg" alt="Google" />
      <img src="@/assets/amazon.svg" alt="Amazon" />
      <img src="@/assets/facebook.svg" alt="Facebook" />
      <img src="@/assets/uber.svg" alt="Uber" />
    </div>
    <div class="statistics__logo">
      <img src="@/assets/openAi.svg" alt="OpenAI" />
      <img src="@/assets/intel.svg" alt="Intel" />
      <img src="@/assets/theia.svg" alt="Theia" />
      <img src="@/assets/code.svg" alt="Code" />
      <img src="@/assets/4geeks.svg" alt="4Geeks" />
    </div>
  </section>
</template>

<script>
import SwiperBlock from "@/components/SwiperBlock.vue";

export default {
  name: "StatisticsBlock",
  components: {
    SwiperBlock,
  },
};
</script>

<style lang="scss" scoped>
@import "@/components/StatisticsBlock/StatisticsBlock.scss";
</style>

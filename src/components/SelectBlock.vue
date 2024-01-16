<template>
  <section class="select">
    <span class="select__text">Select project,</span>
    <span class="select__text">check dependencies, checkout branch, view</span>
    <span class="select__text"
      >readme.txt, install tools, run build, run test,</span
    >
    <span class="select__text">start coding.</span>
  </section>
</template>

<script>
export default {
  name: "SelectBlock",
};
</script>

<style lang="scss" scoped>
.select {
  display: flex;
  flex-direction: column;
  text-align: center;
  margin-top: 158rem;

  &__text {
    &:nth-child(1),
    &:nth-child(4) {
      font: var(--selectBlock-text);
      color: var(--c-btn-background);
      @include tablet-small {
        font: var(--selectBlock-text-tablet);
      }
      @include mobile {
        font: var(--selectBlock-text-mobile);
      }
    }
    &:nth-child(2),
    &:nth-child(3) {
      font: var(--selectBlock-text2);
      color: var(--c-selectBlock-text);
      text-decoration-line: line-through;
      @include tablet-small {
        font: var(--selectBlock-text2-tablet);
      }
      @include mobile {
        font: var(--selectBlock-text2-mobile);
      }
    }
  }

  @include desktop-small {
    margin-top: 90rem;
  }
  @include tablet-small {
    margin-top: 70rem;
  }
}
</style>

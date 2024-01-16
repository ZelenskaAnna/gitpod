<template>
  <section class="think">
    <div class="think__info">
      <h3 class="think__title">Think CI/CD for dev environments</h3>
      <p class="think__desc">
        We invented prebuilds so application code, configuration and
        infrastructure can all be stored as machine-executable code in your git
        repositories and applied to dev environments automatically and
        continuously.
      </p>
      <div class="think__buttons">
        <a href="/">More on prebuilds</a>
        <a href="/">Documentation</a>
      </div>
    </div>
    <img class="think__img" src="@/assets/workspace.png" alt="Workspace" />
  </section>
</template>

<script>
export default {
  name: "ThinkBlock",
};
</script>

<style lang="scss" scoped>
@import "@/components/ThinkBlock/ThinkBlock.scss";
</style>

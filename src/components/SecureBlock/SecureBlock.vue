<template>
  <section class="secure">
    <h2 class="secure__title">Remote-first. Secure by design.</h2>
    <img src="@/assets/screen.png" alt="Screen" class="secure__img" />
    <p class="secure__desc">
      You no longer need an over-powered laptop to code, Gitpod works just as
      smoothly on a Chromebook or iPad. All you need is a browser. Gitpod
      centralizes all source code and never stores it on insecure machines and
      networks.
    </p>
    <div class="secure__buttons">
      <a href="/"
        ><img
          src="@/assets/google.svg"
          alt="Google"
          class="secure__icon"
        />Chrome Extension</a
      >
      <a href="/"
        ><img
          src="@/assets/firefox.svg"
          alt="Firefox"
          class="secure__icon"
        />Firefox Extension</a
      >
    </div>
  </section>
</template>

<script>
export default {
  name: "SecureBlock",
};
</script>

<style lang="scss" scoped>
@import "@/components/SecureBlock/SecureBlock.scss";
</style>

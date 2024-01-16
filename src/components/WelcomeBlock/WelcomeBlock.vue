<template>
  <section class="welcome">
    <div class="welcome__info">
      <h1 class="welcome__title">Always</h1>
      <h1 class="welcome__title">Ready to Code.</h1>
      <p class="welcome__desc">Spin up fresh, automated dev environments</p>
      <p class="welcome__desc">for each task, in the cloud, in seconds.</p>
      <div class="workspace">
        <div class="workspace__item">
          <a href="/" class="btn workspace__btn">Try Now</a>
          <div class="workspace__icons">
            <a href=""
              ><img src="@/assets/gitLab.svg" alt="Fox" class="workspace__img"
            /></a>
            <a href=""
              ><img
                src="@/assets/gitHub.svg"
                alt="GitHub"
                class="workspace__img"
            /></a>
            <a href=""
              ><img
                src="@/assets/bitbucket.svg"
                alt="Frame"
                class="workspace__img"
            /></a>
          </div>
        </div>
        <div class="workspace__text">
          <span>Open a workspace.</span>
          <span>Start from any Git context.</span>
        </div>
      </div>
    </div>
    <img class="welcome__img" src="@/assets/rectangle.png" alt="Image" />
  </section>
</template>

<script>
export default {
  name: "WelcomeBlock",
  components: {},
};
</script>

<style lang="scss" scoped>
@import "@/components/WelcomeBlock/WelcomeBlock.scss";
</style>

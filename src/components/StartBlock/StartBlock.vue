<template>
  <section class="start">
    <h2 class="start__title">Get started now</h2>
    <div class="start__info">
      <div class="start-git">
        <h3 class="start-git__title">Connect Git repository</h3>
        <p class="start-git__desc">
          Select a Git provider to start with an existing project from any Git
          context.
        </p>
        <div class="start-git__buttons">
          <a href="/" class="start-git__btn"
            ><img src="@/assets/gitLabWhite.svg" alt="GitLab" />Continue with
            GitLab</a
          >
          <a href="/" class="start-git__btn"
            ><img src="@/assets/gitHub2.svg" alt="GitHub" />Continue with
            GitHub</a
          >
          <a href="/" class="start-git__btn"
            ><img src="@/assets/bitbucket2.svg" alt="Bitbucket" />Continue with
            Bitbucket</a
          >
        </div>
        <p class="start-git__desc">
          Or prefix any GitLab, GitHub or Bitbucket URL with
        </p>
        <span class="start-git__hashteg">gitpod.io/#</span>
      </div>
      <div class="start-workspace">
        <h3 class="start-workspace__title">Launch an example workspace</h3>
        <p class="start-workspace__desc">
          Dive into one of our example workspaces
        </p>
        <div class="start-workspace__list">
          <div class="start-workspace__item">
            <div class="start-workspace__element">
              <img src="@/assets/typeScript.svg" alt="TypeScript" />
              <span>Node or TypeScript</span>
            </div>
            <a href="/">Launch workspace</a>
          </div>

          <div class="start-workspace__item">
            <div class="start-workspace__element">
              <img src="@/assets/python.svg" alt="Python" />
              <span>Python</span>
            </div>
            <a href="/">Launch workspace</a>
          </div>

          <div class="start-workspace__item">
            <div class="start-workspace__element">
              <img src="@/assets/go.svg" alt="Go" />
              <span>Go</span>
            </div>
            <a href="/">Launch workspace</a>
          </div>

          <div class="start-workspace__item">
            <div class="start-workspace__element">
              <img src="@/assets/rust.svg" alt="Rust" />
              <span>Rust</span>
            </div>
            <a href="/">Launch workspace</a>
          </div>

          <div class="start-workspace__item">
            <div class="start-workspace__element">
              <img src="@/assets/java.svg" alt="Java" />
              <span>Java</span>
            </div>
            <a href="/">Launch workspace</a>
          </div>

          <div class="start-workspace__item">
            <div class="start-workspace__element">
              <img src="@/assets/svelte.svg" alt="Svelte" />
              <span>Svelte</span>
            </div>
            <a href="/">Launch workspace</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "StartBlock",
};
</script>

<style lang="scss" scoped>
@import "@/components/StartBlock/StartBlock.scss";
</style>

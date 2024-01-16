<template>
  <footer class="footer">
    <div class="footer__list">
      <div class="footer__item">
        <h4 class="footer__title">Gitpod</h4>
        <a href="/" class="footer__element">Home</a>
        <a href="/" class="footer__element">Features</a>
        <a href="/" class="footer__element">Pricing</a>
        <a href="/" class="footer__element">Changelog</a>
        <a href="/" class="footer__element">Self-Hosted</a>
        <a href="/" class="footer__element">Gitpod vs GitHub</a>
        <a href="/" class="footer__element">Codespaces</a>
        <a href="/" class="footer__element">Status</a>
      </div>
      <div class="footer__item">
        <h4 class="footer__title">Developer</h4>
        <a href="/" class="footer__element">Getting started</a>
        <a href="/" class="footer__element">Screencasts</a>
        <a href="/" class="footer__element">Blog</a>
        <a href="/" class="footer__element">Documentation</a>
        <a href="/" class="footer__element">Report a bug</a>
        <a href="/" class="footer__element">Community</a>
      </div>
      <div class="footer__item">
        <h4 class="footer__title">Company</h4>
        <a href="/" class="footer__element">About</a>
        <a href="/" class="footer__element">Careers</a>
        <a href="/" class="footer__element">Contact</a>
        <a href="/" class="footer__element">Media Kit</a>
      </div>
      <div class="footer__item">
        <h4 class="footer__title">Legal</h4>
        <a href="/" class="footer__element">Imprint</a>
        <a href="/" class="footer__element">Terms of Service</a>
        <a href="/" class="footer__element">Privacy Policy</a>
      </div>
    </div>
    <div class="footer__copyright">
      <div class="footer__logo">
        <img src="@/assets/logo2.svg" alt="Gitpod" />Copyright &copy;
        {{ currentYear }} Gitpod
      </div>
      <div class="footer__link">
        <a href="/"><img src="@/assets/twitter.svg" alt="Twitter" /></a>
        <a href="/"><img src="@/assets/gitHubOrange.svg" alt="Twitter" /></a>
        <a href="/"><img src="@/assets/message.svg" alt="Message" /></a>
      </div>
    </div>
    <div class="footer__cookies">
      <p class="footer__desc">
        This website uses cookies to enhance the user experience. Read our
        <a href="/">privacy policy</a> for more info.
      </p>
      <button class="footer__btn">Accept Cookies</button>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterBlock",
  components: {},
  data() {
    return {
      currentYear: new Date().getFullYear(),
    };
  },
};
</script>

<style lang="scss" scoped>
@import "@/components/FooterBlock/FooterBlock.scss";
</style>

<template>
  <div class="swiper-container">
    <swiper
      :slides-per-view="'auto'"
      :space-between="30"
      :grid="{}"
      :pagination="{
        clickable: true,
      }"
      class="swiper"
    >
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">GitPod is incredibly cool.</p>
          <p class="statistics__desc">
            In my opinion, this is a big step in open source software
            contribution. I'm excited to see where we go from here.
          </p>
          <div class="statistics__author">
            <img
              src="@/assets/author1.png"
              alt="Ben Halpern"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">Ben Halpern</span>
              <span class="statistics__role"
                >Creator and Co-founder <span>@forem</span> and
                <span>@ThePracticalDev</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">
            Let's say we were overwhelmed how smooth @gitpod workspaces creation
            & own Docker image for workspaces worked.
          </p>
          <p class="statistics__desc">
            Plus, installing @code extensions from the store and integrating
            @gitlab CI. That blew my mind entirely, and that is hard ;)
          </p>
          <div class="statistics__author">
            <img
              src="@/assets/author2.png"
              alt="Michael Friedrich"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">Michael Friedrich</span>
              <span class="statistics__role"
                >Developer Evangelist <span>@GitLab</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">
            Look at any PR (pull request) in a full coding environment where you
            can edit, build, and test the PR code, by just prepending
            "gitpod.io#" to the PR URL. Super useful for reviewing/testing stuff
            without having to check it out locally!
          </p>
          <div class="statistics__author">
            <img
              src="@/assets/author3.png"
              alt="Julius Volz"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">Julius Volz</span>
              <span class="statistics__role"
                >Creator <span>@PrometheusIO</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">
            I think I’m in love with @gitpod. It’s such a powerful tool. I’ve
            learned so much in the past week just from stumbling across Github
            repos that interest me and appending “http://gitpod.io/#” to the
            URL. A+ tool all around.
          </p>
          <p class="statistics__desc"></p>
          <div class="statistics__author">
            <img
              src="@/assets/author4.png"
              alt="David Ressler"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">David Ressler</span>
              <span class="statistics__role"
                >Engineering Manager <span>@instagram</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
    </swiper>

    <swiper
      :direction="'vertical'"
      :space-between="24"
      :pagination="{
        clickable: true,
      }"
      class="swiperMobile"
    >
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">GitPod is incredibly cool.</p>
          <p class="statistics__desc">
            In my opinion, this is a big step in open source software
            contribution. I'm excited to see where we go from here.
          </p>
          <div class="statistics__author">
            <img
              src="@/assets/author1.png"
              alt="Ben Halpern"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">Ben Halpern</span>
              <span class="statistics__role"
                >Creator and Co-founder <span>@forem</span> and
                <span>@ThePracticalDev</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">
            Let's say we were overwhelmed how smooth @gitpod workspaces creation
            & own Docker image for workspaces worked.
          </p>
          <p class="statistics__desc">
            Plus, installing @code extensions from the store and integrating
            @gitlab CI. That blew my mind entirely, and that is hard ;)
          </p>
          <div class="statistics__author">
            <img
              src="@/assets/author2.png"
              alt="Michael Friedrich"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">Michael Friedrich</span>
              <span class="statistics__role"
                >Developer Evangelist <span>@GitLab</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">
            Look at any PR (pull request) in a full coding environment where you
            can edit, build, and test the PR code, by just prepending
            "gitpod.io#" to the PR URL. Super useful for reviewing/testing stuff
            without having to check it out locally!
          </p>
          <div class="statistics__author">
            <img
              src="@/assets/author3.png"
              alt="Julius Volz"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">Julius Volz</span>
              <span class="statistics__role"
                >Creator <span>@PrometheusIO</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="statistics__item">
          <p class="statistics__desc">
            I think I’m in love with @gitpod. It’s such a powerful tool. I’ve
            learned so much in the past week just from stumbling across Github
            repos that interest me and appending “http://gitpod.io/#” to the
            URL. A+ tool all around.
          </p>
          <p class="statistics__desc"></p>
          <div class="statistics__author">
            <img
              src="@/assets/author4.png"
              alt="David Ressler"
              class="statistics__img"
            />
            <div class="statistics__info">
              <span class="statistics__name">David Ressler</span>
              <span class="statistics__role"
                >Engineering Manager <span>@instagram</span></span
              >
            </div>
          </div>
        </div>
      </swiper-slide>
      ></swiper
    >
  </div>
</template>

<script>
import SwiperCore, { Navigation } from "swiper/core";
import { Swiper, SwiperSlide } from "swiper/vue";

import "swiper/swiper-bundle.css";

SwiperCore.use([Navigation]);

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
};
</script>

<style lang="scss">
@import "@/components/StatisticsBlock/StatisticsBlock.scss";

.swiper {
  @include mobile {
    display: none;
  }
  @include tablet-small {
    max-height: 350rem;
    height: 100%;
  }
}

.swiperMobile {
  display: none;

  @include mobile {
    display: block;
    max-height: 300rem;
  }
}
</style>

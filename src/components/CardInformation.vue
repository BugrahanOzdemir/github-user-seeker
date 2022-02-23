<template>
  <div class="information">
    <img src="" alt="" class="information__img" />
    <div class="information-container">
      <h2 class="information__name"></h2>
      <h3 class="information__user"></h3>
      <p class="information__joined"></p>
    </div>

    <p class="information__description"></p>
  </div>

  <div class="information__statistic">
    <div class="information__item">
      <h4 class="information__item--title">Repos</h4>
      <p class="information__item--content"></p>
    </div>

    <div class="information__item">
      <h4 class="information__item--title">Followers</h4>
      <p class="information__item--content"></p>
    </div>

    <div class="information__item">
      <h4 class="information__item--title">Following</h4>
      <p class="information__item--content"></p>
    </div>

    <div class="information__links">
      <p class="information__link location">
        <span class="information__icon">
          <IconLocation />
        </span>
      </p>

      <a href="" class="informatiom__link">
        <span class="information__icon">
          <IconWebsite />
        </span>
      </a>

      <a href="" class="information__link">
        <span class="information__icon"><IconTwitter /></span>
      </a>

      <a href="" class="information__link">
        <span class="information__icon">
          <IconCompany />
        </span>
      </a>
    </div>
  </div>
</template>

<script>
import IconLocation from "@/icon/IconLocation.vue";
import IconWebsite from "@/icon/IconWebsite.vue";
import IconTwitter from "@/icon/IconTwitter.vue";
import IconCompany from "@/icon/IconCompany.vue";

export default {};
</script>
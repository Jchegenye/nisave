<template>
  <b-row align-v="center" class="hero__content">
    <b-col md="6">
      <div>
        <h1>Getting loans is easier than you think with Nisave.</h1>
        <p>
          Your friends and family are your first real help when you need a quick
          loan. They trust you and may offer better terms and conditions.
        </p>
      </div>

      <div class="hero__content__inner my-5">
        <b-link href="#">
          <b-img
            src="~/assets/imgs/google-play.svg"
            fluid
            alt="google-play"
          ></b-img>
        </b-link>
        <div class="mt-sm-2">
          <small>Want to sign up as a beta tester?</small>
          <small>
            <b-link href="#">Sign up here</b-link>
          </small>
        </div>
      </div>

      <div class="hero__content__outerinner">
        <small
          >Nisave is a secure peer to peer lending platform regulated by the
          Central Bank of Kenya etc.</small
        >
      </div>
    </b-col>
    <b-col md="4" offset-md="2">
      <b-img
        src="~/assets/imgs/mobile.png"
        fluid
        alt="mobile-dummy"
        class="hero__content__google-play"
      ></b-img>
    </b-col>
  </b-row>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style lang="scss">
.hero {
  position: relative;
  min-height: 100%;
  background: url(../assets/imgs/Hero-Image.png) rgba(0, 0, 0, 0.29);
  background-size: cover;
  background-blend-mode: overlay;
  background-repeat: no-repeat;

  &__content {
    color: var(--white-color);
    &__inner {
      font-size: var(--font-medium);
    }
    &__outerinner {
      font-size: var(--font-small);
    }
    &__google-play {
      position: relative;
      top: 85px;
    }
  }
}
</style>
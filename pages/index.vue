<template>
  <div>
    <b-container fluid class="hero">
      <b-container fluid="lg" class="py-lg-4">
        <navbar></navbar>
        <hero></hero>
      </b-container>
    </b-container>

    <b-container fluid="lg">
      <services></services>
    </b-container>

    <b-container fluid class="video mt-120">
      <video-banner></video-banner>
    </b-container>

    <b-container fluid="lg" class="faq">
      <faq></faq>
    </b-container>

    <b-container fluid="lg">
      <b-row>
        <b-col md="6" offset-md="3" class="text-center mt-120">
          <h1>Join us, Let’s start a revolution!</h1>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid class="footer mt-120">
      <bottom-footer></bottom-footer>

      <b-img
        src="~/assets/imgs/red-dice.png"
        fluid
        alt="red-dice"
        class="footer__dice small medium"
      ></b-img>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

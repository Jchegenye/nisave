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
          <h1>Are you ready to start borrowing from people you trust?</h1>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid class="footer mt-120">
      <bottom-footer></bottom-footer>

      <b-img
        src="~/assets/imgs/red-dice.png"
        fluid
        alt="red-dice"
        class="footer__dice"
      ></b-img>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

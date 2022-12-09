<template>
  <b-row class="justify-content-md-center text-center video__inner">
    <b-img src="~/assets/imgs/call.png" fluid alt="video banner"></b-img>
    <div>
      <svg
        width="96"
        height="96"
        viewBox="0 0 96 96"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        @click="$bvModal.show('bv-modal-video')"
      >
        <path
          d="M48 88C70.0914 88 88 70.0914 88 48C88 25.9086 70.0914 8 48 8C25.9086 8 8 25.9086 8 48C8 70.0914 25.9086 88 48 88Z"
          stroke="white"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
        <path
          d="M38 35.8613C38 33.9522 38 32.9976 38.399 32.4647C38.7466 32.0003 39.2789 31.7097 39.8575 31.6684C40.5215 31.621 41.3245 32.1372 42.9304 33.1696L61.8128 45.3082C63.2063 46.2041 63.9031 46.652 64.1438 47.2216C64.3541 47.7192 64.3541 48.2808 64.1438 48.7784C63.9031 49.348 63.2063 49.7959 61.8128 50.6918L42.9304 62.8304C41.3245 63.8628 40.5215 64.379 39.8575 64.3316C39.2789 64.2903 38.7466 63.9997 38.399 63.5353C38 63.0024 38 62.0478 38 60.1387V35.8613Z"
          stroke="white"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
      <div class="video__overlay"></div>
    </div>

    <b-modal id="bv-modal-video" size="lg" centered hide-header hide-footer>
      <div
        @click="$bvModal.hide('bv-modal-video')"
        class="text-right video__close"
      >
        X
      </div>
      <div class="d-block text-center">
        <iframe
          width="100%"
          height="315"
          src="https://www.youtube-nocookie.com/embed/z1MnqhJKaU4?controls=0"
          title="Nisave Video"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </b-modal>
  </b-row>
</template>
<style lang="scss" scoped>
.video {
  &__inner {
    position: relative;
  }
  &__close {
    position: absolute;
    right: 0;
    top: 0;
    line-height: 0.7;
    background-color: white;
    color: var(--primary-color);
    font-size: var(--font-small);
    padding: 18px;
    border-bottom-left-radius: 50%;
    cursor: pointer;
  }
  svg {
    position: absolute;
    top: 50%;
    right: 50%;
    transform: translate(50%, -50%);
    z-index: 1;
    cursor: pointer;
    &:focus {
      outline: 0;
    }
    &:hover {
      path {
        stroke: var(--primary-color);
        stroke-width: 3;
      }
    }
  }
  &__overlay {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    top: 0;
    background-color: rgb(0 0 0 / 64%);
  }
}
</style>
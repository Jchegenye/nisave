<template>
  <b-row
    align-v="center"
    class="justify-content-md-center text-left mt-120 faq__inner py-5"
  >
    <b-col md="10">
      <no-ssr>
        <carousel
          :autoplay="true"
          :dots="false"
          :rewind="true"
          :items="1"
          :boolean="true"
        >
          <div>
            <h1 class="mb-4">What is social network financing?</h1>
            <p>
              Social network financing refers to financing between family,
              friends and colleagues, ranging from peer-to-peer lending,
              fundraising and group savings. This type of financing is mostly
              informal and difficult to track. We are here to solve this
              problem.
            </p>
          </div>
          <div>
            <h1 class="mb-4">How do I get Nisave?</h1>
            <p>
              Nisave is available on Google play store for users with a smart
              phone and internet access. Sign up with a few simple steps and
              open a new world of possibilities.
            </p>
          </div>
          <div>
            <h1 class="mb-4">Does it Cost to use Nisave?</h1>
            <p>
              Downloading nisave is free. We only charge a small platform fee
              for successful transactions on the platform to help us bring a
              world class product to you.
            </p>
          </div>
        </carousel>
      </no-ssr>
    </b-col>
    <b-col md="2" offset-md="1"></b-col>
  </b-row>
</template>
<style lang="scss" scoped>
.faq {
  &__inner {
    background-color: var(--secondary-color);
    color: var(--white-color);
  }
}
</style>
<template>
  <b-row align-v="center" class="hero__content">
    <b-col md="6">
      <div>
        <h1 class="d-flex mb-4">
          Trust Is King
          <svg
            x="0px"
            y="0px"
            viewBox="0 0 1000 1000"
            width="35px"
            class="ml-3"
          >
            <g>
              <g
                transform="translate(0.000000,511.000000) scale(0.100000,-0.100000)"
              >
                <path
                  fill="white"
                  d="M4808.2,4300.3c-441.1-161.1-561.9-700-230.1-1022.2c42.2-40.3,103.6-84.4,134.2-97.8c38.4-15.3,55.6-34.5,49.9-51.8C4720,3019.2,3203,284.4,3166.6,251.8c-26.8-24.9-67.1-44.1-88.2-44.1c-23,0-475.6,264.7-1004.9,588.8l-962.7,588.8l57.5,67.1c101.6,115.1,140,222.5,140,395.1c-1.9,195.6-51.8,318.4-184.1,441.1c-136.2,126.6-243.6,170.7-420,170.7c-176.4,0-283.8-44.1-420-170.7C151.8,2165.8,101.9,2043,100,1847.4c0-130.4,7.7-170.7,53.7-262.7c94-191.8,318.4-341.4,512.1-341.4h74.8l36.4-118.9c21.1-67.1,264.7-901.4,542.7-1856.4c435.3-1494,512.1-1743.3,556.2-1787.4l51.8-53.7h3070.4h3068.5l51.8,44.1c44.1,38.4,111.3,255.1,592.6,1902.5l542.7,1860.3l105.5,11.5c214.8,23,410.4,164.9,498.6,360.5c32.6,67.1,42.2,124.7,42.2,241.6c-1.9,195.6-51.8,318.4-184.1,441.1c-136.2,126.6-243.6,170.7-420,170.7c-180.3,0-304.9-51.8-427.7-176.4c-128.5-132.3-176.4-247.4-176.4-435.3c0-172.6,38.4-280,140-395.1l57.5-67.1l-962.7-588.8c-529.3-324.1-981.9-588.8-1004.9-588.8c-21.1,0-61.4,19.2-88.2,44.1c-38.4,32.6-1551.5,2763.6-1593.7,2874.8c-7.7,19.2,7.7,36.4,47.9,53.7c84.4,34.5,201.4,157.3,262.7,272.3c46,88.2,53.7,122.7,53.7,264.7c-1.9,191.8-46,306.9-172.6,431.5C5274.2,4306,5005.8,4371.2,4808.2,4300.3z"
                />
                <path
                  fill="white"
                  d="M2084.9-3211.8c-36.4-11.5-111.2-65.2-163-118.9c-136.2-134.2-174.5-278.1-120.8-458.4c30.7-105.5,189.9-264.7,295.3-295.3c115.1-32.6,5692.1-32.6,5807.1,0c164.9,49.9,318.3,260.8,318.3,437.3s-153.4,387.4-318.3,437.3C7796.2-3179.2,2186.6-3179.2,2084.9-3211.8z"
                />
              </g>
            </g>
          </svg>
        </h1>
        <p>
          Take control of your social network financing, make it binding,
          convenient and trackable. With nisave you gain access to affordable
          and flexible credit from your trusted social networks.
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
        <!-- <div class="mt-sm-2">
          <small>
            <b-link href="#">Sign up here</b-link>
          </small>
        </div> -->
      </div>

      <div class="hero__content__outerinner">
        <small
          >Nisave is a regulated and secure social network financing Platform.
        </small>
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
  background: url(../assets/imgs/Hero-Image.webp) rgba(0, 0, 0, 0.29);
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
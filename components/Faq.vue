<template>
  <b-row
    align-v="center"
    class="justify-content-md-center text-left mt-120 faq__inner py-5"
  >
    <b-col md="10">
      <h4>Answers to a few good questions.</h4>
      <h1 class="py-4">How do I get Nisave application?</h1>
      <p>
        You can download Nisave Application from Google Playstore. Once
        downloaded, you can first sign up and you will receive a One Time
        Password (OTP) code that will be used to verify your account. You can
        then log in and setup your account to start enjoying the freedom of
        borrowing from your friends and family.
      </p>

      <div class="faq__pagination">
        <div class="faq__pagination__btn prev">
          <svg
            width="8"
            height="14"
            viewBox="0 0 8 14"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M7 13L1 7L7 1"
              stroke="white"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>
        </div>
        <div class="faq__pagination__btn next">
          <svg
            width="8"
            height="14"
            viewBox="0 0 8 14"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M1 13L7 7L1 1"
              stroke="white"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>
        </div>
      </div>
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
  &__pagination {
    display: flex;
    &__btn {
      background-color: var(--primary-color);
      flex-direction: row;
      justify-content: center;
      align-items: center;
      width: 44px;
      height: 44px;
      text-align: center;
      line-height: 40px;
      border-radius: 50%;
      margin-top: 22px;
      cursor: pointer;
      &.prev {
        margin-right: 15px;
      }
    }
  }
}
</style>
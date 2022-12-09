<template>
  <b-navbar toggleable="sm" type="light" class="navbar">
    <b-navbar-brand href="/">
      <logo></logo>
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse" class="navbar__toggle">
      <template #default="{ expanded }">
        <div v-if="!expanded" class="navbar__toggle--open">
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div v-else class="navbar__toggle--close">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </template>
    </b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-button variant="nisave">Become a Beta Tester</b-button>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
<style lang="scss" scopped>
.navbar {
  &__toggle {
    border-color: transparent !important;
    padding: 0;

    &--close > span,
    &--open > span {
      display: block;
      width: 33px;
      height: 4px;
      margin-bottom: 5px;
      position: relative;
      background: var(--primary-color);
      border-radius: 3px;
      z-index: 1;
      transform-origin: 4px 0px;
      transition: transform 0.5s cubic-bezier(0.77, 0.2, 0.05, 1),
        background 0.5s cubic-bezier(0.77, 0.2, 0.05, 1), opacity 0.55s ease;
    }
    &--close {
      span {
        -webkit-transform: rotate(-45deg) translate(0, -1px);
        -moz-transform: rotate(-45deg) translate(0, -1px);
        -ms-transform: rotate(-45deg) translate(0, -1px);
        -o-transform: rotate(-45deg) translate(0, -1px);
        transform: rotate(-45deg) translate(0, -1px);
      }
      span:nth-last-child(2) {
        -webkit-transform: rotate(45deg) translate(-5px, -7px);
        -moz-transform: rotate(45deg) translate(-5px, -7px);
        -ms-transform: rotate(45deg) translate(-5px, -7px);
        -o-transform: rotate(45deg) translate(-5px, -7px);
        transform: rotate(45deg) translate(-5px, -7px);
      }
      span:nth-last-child(3) {
        opacity: 0;
        transform: rotate(0deg) scale(0.2, 0.2);
      }
    }
  }
}
</style>
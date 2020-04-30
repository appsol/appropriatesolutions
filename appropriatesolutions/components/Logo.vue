<template>
  <img class="logo" :style="logoStyle" src="~assets/images/logo.svg" />
</template>
<script>
  export default {
    props: {
      width: {
        type: Number,
        default: 200
      }
    },
    computed: {
      logoStyle() {
        return { width: this.width + 'px' }
      }
    }
  }
</script>
<style>
  .logo {
    animation: 1s appear;
    margin: auto;
  }

  @keyframes appear {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
</style>

<template>
  <section class="hero is-info is-large">
    <div class="hero-body">
      <div class="container">
        <div class="level">
          <div class="level-left">
            <div class="level-item">
              <logo />
            </div>
          </div>
          <div class="level-right">
            <div class="level-item">
              <div>
                <h1 class="title">appropriate solutions</h1>
                <h2 class="subtitle">Web application development</h2>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  import Logo from '~/components/Logo.vue'

  export default {
    components: {
      Logo
    }
  }
</script>

<style>
</style>

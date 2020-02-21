<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        caudex
      </h1>
      <h2 class="subtitle">
        Note &amp; document management
      </h2>


    </div>
  </div>
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
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

</style>

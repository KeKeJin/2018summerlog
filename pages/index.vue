<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        2018summerlog
      </h1>
      <n/>
      <h2 class="subtitle">
        hmc 2018 summer cs startup log
        <n/>
      </h2>
      <div class="links">
        <n/>
        <a
          href="https://docs.google.com/document/d/141XpVpWjHGN_F1DALZi77EVCl3PpdPMhIjaCkNnTf98/edit"
          target="_blank"
          class="button--green">daily log</a>

      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

<template>
  <section class="container">
    <div>
      
      <app-logo/>
      <h1 class="title">
        wwww.slovakiaholiday.org
      </h1>
      <h2 class="subtitle">
        Spoznajte krásy Slovenska s nami!
      </h2>
      <div class="lang">
        <img src="@/assets/img/slovensko.jpg" width="35px" height="35px" /> 
        <img src="@/assets/img/nemecko.jpg" width="35px" height="35px" /> 
        <img src="@/assets/img/anglicko.jpg" width="35px" height="35px"/> 
      </div>
      <div class="links">
        <a
          href="/Home"
          target="_blank"
          class="button--green">Vstúpte</a>

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
  background-image: url("/assets/img/background-index.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: white;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}



</style>

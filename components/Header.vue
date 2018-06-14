<template>
    <header class="header">
      <router-link :to="{ name: 'Home' }">
        <img src="@/assets/img/logo.png" />
      </router-link>
      <nav>
        <router-link :to="{ name: 'Home' }">Home</router-link> 
        <router-link :to="{ name: 'About' }">About us</router-link> 
        <router-link :to="{ name: 'Services' }">Services</router-link> 
        <router-link :to="{ name: 'Slovakia' }">Slovakia</router-link>
        <router-link :to="{ name: 'Wellnes' }">Wellnes</router-link> 
        <router-link :to="{ name: 'Contactform' }">Contact</router-link>
      </nav>
    </header>
</template>

<style lang="scss">
@import "~@/assets/scss/reset";
@import "~@/assets/scss/variables";
@import "~@/assets/scss/mixins";

.header {
  width:           100%;
  height:          80px;
  background:      #2C3E50;
  padding:         0 40px;
  display:         flex;
  align-items:     center;
  justify-content: space-between;
  position:        fixed;
  top:             0;
  left:            0;

  img {
    max-width: 100px;
  }

  nav {
    display: none;
    @include media(md) {
      display: flex;
    }

    a {
      padding:   12px;
      color:     $accent;
      font-size: 18px;
      display:   block;

      &:not(:last-of-type) {
        margin-right: 60px;
      }
      
      &:hover {
        color: $primary;
      }
    }
  }
}

</style>

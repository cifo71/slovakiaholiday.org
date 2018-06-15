<template>
    <footer class="footer">
      <p>Copyright &copy; 2018 www.slovakiaholiday.org</p>
    </footer>
</template>

<style lang="scss">
@import "~@/assets/scss/reset";
@import "~@/assets/scss/variables";
@import "~@/assets/scss/mixins";

.footer {
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 50px;
    background-color: #2C3E50;
    color: white;
    text-align: center;

  p {
  padding: 20px;
  }
}

</style>
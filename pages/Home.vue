<template>
        <ui-layout container>
            <ui-layout class="col-xs-6 col-md-3"></ui-layout><h1>Vitajte na stránke</h1>
            <ui-layout class="col-xs-6 col-md-3"></ui-layout>
        </ui-layout>
</template>


<script>
import UiLayout from '@/components/UiLayout.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'


export default {
  components: {
  UiLayout,
  Header,
  Footer
}
};
</script>

<style lang="scss">
@import '~@/assets/scss/_variables';
@import '~@/assets/scss/_mixins';

</style>
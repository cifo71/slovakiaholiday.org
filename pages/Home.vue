<template>
  <div>
    <ui-header/>
        <ui-layout container>
            <ui-layout class="col-xs-6 col-md-3"></ui-layout>
            <ui-layout class="col-xs-6 col-md-3"></ui-layout>
        </ui-layout>
    <ui-footer/>
  </div>
</template>


<script>
import UiLayout from '@/components/UiLayout.vue'
import UiHeader from '@/components/UiHeader.vue'
import UiFooter from '@/components/UiFooter.vue'


export default {
  components: {
  UiLayout,
  UiHeader,
  UiFooter
}
};
</script>

<style lang="scss">
@import '~@/assets/scss/_variables';
@import '~@/assets/scss/_mixins';


</style>
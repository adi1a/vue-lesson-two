<template>
  <div id="app">
    <NumbersComponent />
    
    <br>

    <ShowText />
    

    
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import NumbersComponent from '../src/components/Numbers.vue';
import ShowText from '../src/components/ShowText.vue';

interface Data {
  // products:  IProduct[];
}

export default Vue.extend({
  name: 'App',
  data: (): Data => ({
   isVisible: true,

   activeBtn: true,
  }),

  components: {
    NumbersComponent, 
    ShowText
  }
});
</script>

<style lang="scss">

</style>

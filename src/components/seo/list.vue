<template>
  <div class='seo'>
    <ul>
      <li>{{ one }}</li>
      <li>{{ two }}</li>
      <li>{{ three }}</li>
    </ul>
    <Button @click='requestSeo'>ALERT</Button>    
  </div>
</template>

<script lang='ts'>
import Vue from 'vue';

export default Vue.extend({
  name: 'List',
  data() {
    return {
      one: 'ONE',
      two: 'TWO',
      three: 'THREE'
    }
  },
  methods: {
    requestSeo(): void {
      this.one = "request"
    }
  }
})


</script>

<style>
.seo {
  width: 100px;
  height: 100px;
  border: 1px solid #ccc;
}
</style>

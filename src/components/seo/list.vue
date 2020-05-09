<template>
  <div class="seo">
    <Button @click="listAlert">ALERT</Button>    
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component ({
  methods: {
    listAlert: function(e): void {
      alert('GetSeo')
    },
  }
})
export default class List extends Vue {}

</script>

<style>
.seo {
  width: 100px;
  height: 100px;
  border: 1px solid #ccc;
}
</style>

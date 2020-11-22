<template>
  <div class="trashdetail">
    <h1>TrashDetail</h1>
    <div>被回收的文章id：{{ $route.params.id }}</div>
  </div>
</template>

<script lang='ts'>
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component( {
  name: 'TashDetail'
} )
export default class extends Vue {

}
</script>

<style lang='less' scoped>

</style>
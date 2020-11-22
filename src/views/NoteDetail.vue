<template>
  <div class="notedetail">
    <h1>NoteDetail</h1>
    <div>笔记的id：{{ $route.params.id }}</div>
  </div>
</template>

<script lang='ts'>
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component( {
  name: 'NoteDetail'
} )
export default class extends Vue {

}
</script>

<style lang='less' scoped>

</style>
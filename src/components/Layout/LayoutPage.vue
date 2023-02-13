<script setup>
  import SideBarNav from './SideBarNav.vue';
</script>

<style scoped>
  .page-container{
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: flex-start;
    justify-content: flex-start;
  }

  .content-page-container{
    height: 100vh;
    flex: 1;
    background-color: var(--purple-800);
  }
</style>

<template>
  <div class="page-container">
    <SideBarNav/>
    <div class="content-page-container">
      <slot></slot>
    </div>
  </div>
</template>

<script setup lang="ts">
import navMenu from "@/components/navMenu/navMenu.vue"
import TeamMainCreate from "@/views/TeamMain/TeamMainCreate.vue"
</script>

<template>
  <div class="default-layout">
    <div class="header">
      <div class="contest-menu">
        <navMenu></navMenu>
      </div>
    </div>
    <div class="mainlayout">
      <div class="main">
        <TeamMainCreate></TeamMainCreate>
      </div>

    </div>
  </div>
</template>
<style lang="less" scoped>
.header {
  height: 50px;
  border-bottom: #EBEBEB 1px solid;
  overflow: hidden;

  .contest-menu {
    max-width: 1700px;
    width: 100%;
    height: 100%;
    margin: 0 auto;
  }
}

.mainlayout {
  width: 100%;
  height: 100%;
  text-align: center;
  background-color: #ffffff;

  .main {
    margin: 0 auto;
    width: 1000px;
    height: 100%;
    background-color: #ffffff;
    text-align: left;
  }
}
</style>

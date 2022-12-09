<template>
  <div class="common-layout">
    <el-container>
      <el-aside width="200px" float-left>
        <Menu/>
      </el-aside>
      <el-main>
        <div class="float-right">a</div>
        Main
      </el-main>
    </el-container>
  </div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue'
import Menu from '../../components/Menu.vue'



onMounted(()=>{
  console.log("aaaa");
})
</script>

<style scoped>

</style>

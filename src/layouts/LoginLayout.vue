<!--
  * @Description: 登陆页面布局
  * @Author: NekoLing
  * @Date: 2022/10/22 14:00
  -->
<template>
  <div class="column flex-center" style="height: 100vh">
    <MptfLogo class="q-mb-lg" style="max-width: 600px"/>
    <LoginForm style="max-width: 400px; width: 100%"/>
  </div>
</template>

<script setup>
import LoginForm from "components/LoginForm.vue"
import MptfLogo from "components/MptfLogo.vue"

</script>

<style scoped>

</style>

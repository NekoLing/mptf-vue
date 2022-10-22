<!--
  * @Description: 登陆表单
  * @Author: NekoLing
  * @Date: 2022/10/22 13:12
  -->
<template>
  <div class="q-pa-md">
    <q-form>
      <q-input label="用户名" hint="无需密码 新用户会自动创建账号" outlined  v-model="userName"/>
      <q-btn label="进入" class="full-width q-mt-sm" color="primary" icon="login"/>
    </q-form>
  </div>
</template>

<script setup>
import { ref } from "vue";
const userName = ref("");


</script>

<style scoped>

</style>

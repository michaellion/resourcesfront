<template>
    <div class="login-container">
      <div id="canvascontainer" ref="can"></div>

    <el-form ref="loginForm" autocomplete="on" :modal="loginForm" class="card-box login-form">
      <el-form-item>
        <el-input type="text" v-model="loginForm.username" placeholder="username" auto-complete="on"></el-input>
      </el-form-item>

      <el-form-item>
        <el-input type="password" v-model="loginForm.password" aria-placeholder="password" auto-complete="on"></el-input>
      </el-form-item>
    </el-form>

    </div>
</template>

<script>
    export default {
        name: "login"
    }
</script>

<style scoped>

</style>

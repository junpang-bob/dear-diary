<template>
  <div id="login" class="flex justify-center items-center bg-yellow-300">
    <div class="space-y-3">
      <h1 class="text-center text-2xl pb-1 text-white font-black">日记ing</h1>
      <div class="space-y-3">
        <div class="flex justify-center items-center space-x-3">
          <span class="w-20">账户:</span><el-input class="w-80"></el-input>
        </div>
        <div class="flex justify-center items-center space-x-3">
          <span class="w-20">密码:</span><el-input></el-input>
        </div>
      </div>
      <div class="flex justify-around">
        <el-button>登录</el-button>
        <el-button>注册</el-button>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  setup() {
    return {};
  },
};
</script>

<style>
#login {
  width: 100vw;
  height: 100vh;
}
</style>

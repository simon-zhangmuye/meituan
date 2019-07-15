<template>
  <div class="header-user">
    <template v-if="user">
      欢迎您，<span class="username">{{ user }}</span>
      [<nuxt-link to="/exit">退出</nuxt-link>]
    </template>
    <template v-else>
      <nuxt-link to="/login">立即登录</nuxt-link>
      <nuxt-link to="/register">注册</nuxt-link>
    </template>
  </div>
</template>

<script>
export default {
  name: 'user',
  data () {
    return {
      user: ''
    }
  }
}
</script>

<style scoped lang="scss">

</style>

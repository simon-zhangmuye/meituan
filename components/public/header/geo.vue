<template>
  <div class="header-geo">
    <i class="el-icon-location"/>北京市
    <nuxt-link to="/changeCity">切换城市</nuxt-link>
    [香河 廊坊 天津]
  </div>
</template>

<script>
export default {
  name: 'geo',
  data () {
    return {
    }
  }
}
</script>

<style scoped lang="scss">

</style>

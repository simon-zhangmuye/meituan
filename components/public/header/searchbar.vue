<template>
  <div class="header-searchbar">
    <el-autocomplete
      v-model="search1"
      :fetch-suggestions="querySearch"
      placeholder="请输入内容"
      @select="handleSelect"
    >
      <el-button slot="append" icon="el-icon-search"></el-button>
    </el-autocomplete>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        search1:""
      }
    }
  }
</script>
<style scoped lang="scss">

</style>

<template>
  <el-steps :active="active" align-center style="width: 800px;margin: 100px auto">
    <el-step title="上传资料" ></el-step>
    <el-step title="购买服务" ></el-step>
    <el-step title="填报说明" ></el-step>
    <el-step title="内容填报" ></el-step>
    <el-step title="上传附件" ></el-step>
    <el-step title="专家评审" ></el-step>
    <el-step title="申报完成" ></el-step>
    <el-step title="导出资料" ></el-step>
  </el-steps>
</template>

<script>
  export default {
    name: 'formStep',
    data() {
      return {
        active: 0
      }
    },
    props: ['active'],
    methods: {
    }
  }
</script>

<style scoped>
</style>

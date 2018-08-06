<template>
    <el-row style="text-align: center">
      <label style="border-bottom: rgb(64, 158, 255) 3px solid;height: 40px;line-height: 40px;padding-bottom: 10px;font-size: 20px;font-weight: normal">{{title}}</label>
      <h4 style="font-weight: normal;color: #d3dce6;font-size: 14px;text-align: center">{{detail}}</h4>
    </el-row>
</template>

<script>
  export default {
    name: 'head-assembly',
    data() {
      return {
        title: '',
        detail: '科技部、财政部、国家税务总局编制二〇一六年六月'
      }
    },
    props: ['title', 'detail'],
    components: {
    },
    methods: {
    }
  }

</script>

<style scoped>
  p {
    text-align: left;
    text-indent: 2em;
  }
</style>

<template>
  <svg width="100%" height="100%" id="svg" viewBox="0 0 1440 700" xmlns="http://www.w3.org/2000/svg" class="transition duration-300 ease-in-out delay-150">
  </svg>
</template>

<script>
  /**
   * 直接使用<my-icon></my-icon>，参数icon不需要带#
   * my-icon的style或class可以直接改属性
   * 也可以直接在父类下使用.icon{}进行修改属性
   */
  export default {
    name: "MyBackGronud",
    components: {},
    props: {
      icon: {
        type: String,
        required: true,
        default: ''
      }
    },
    data() {
      return {}
    },
    methods: {}
  }
</script>

<style scoped>

</style>

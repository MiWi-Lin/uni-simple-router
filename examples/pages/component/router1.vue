<template>
  <div>
        <h1>配置项useUniConfig:false</h1>
        <h3>我是router1</h3>
        <button @click="$Router.push({name:'tabbar-2'})">去router2页面</button>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
  created(){
      console.log(666666)
  },
  onLoad(){
	console.log('onLoad')  
  },
  methods: {

  },
  components: {

  }
}
</script>

<style>

</style>

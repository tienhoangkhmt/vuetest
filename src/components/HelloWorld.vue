<template>
  <div class="hello">
    <input type="text" v-model="age"/>
    <div>
      {{ age }}
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  age:'23',
  data(){
    return {
      age:this.age,
    }
  },
  // props: {
  //   data: String
  // },

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">

</style>

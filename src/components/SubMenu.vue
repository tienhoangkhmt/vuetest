<template>
  <ul>
    <li v-for="(value, index) in menu" :key="index" >
      {{value}} {{index}}
    </li>
  </ul>
</template>

<script>
export default {
  name: "SubMenu",
  data(){
    return{
      menu:[
      "Home",
      "Groceries",
      "Household",
      "Personal Care",
      "Packaged Foods",
      "Beverages"
    ]
    }
  }
}

</script>

<style lang="scss">
      
</style>
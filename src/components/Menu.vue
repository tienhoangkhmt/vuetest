<template>
  <div class="Menu nav-bar">
    <nav>
       <SubMenu/>
    </nav>
  </div>
</template>

<script>
import SubMenu from "@/components/SubMenu";
export default {
  name: "Menu",
  components:{
    SubMenu
  }
}
</script>

<style lang="scss">

</style>
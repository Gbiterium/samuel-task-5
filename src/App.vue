<template>
  
  <div id="app">
    <desk-nav id='desktop-nav'/>
    <div class="view-container">
      <router-view/>
    </div>
  </div>
</template>

<script>
import DeskNav from '@/components/DeskNav'
export default {
  components: {
    DeskNav
  }
}
</script>


<style scoped>
.view-container{
    width: 100vw;
    padding: 1.5em;
    box-sizing: border-box;
    min-height: 100vh;
}

</style>

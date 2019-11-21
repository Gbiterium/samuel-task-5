<template>
  <div class="home">
    <main-component />
  </div>
</template>

<script>
// @ is an alias to /src
import MainComponent from '@/components/MainComponent'

export default {
  name: 'home',
  components: {
    MainComponent
  }
}
</script>

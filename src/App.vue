<template>
  <div id="container">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      filterDone: false
    }
  }
}
</script>
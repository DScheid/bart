// Simply the home page..

<template>
  <div class="center">
    <div class="text-center">
      <h1>Hi, Welcome to my Bitcoin and Drink Recipe Site</h1>
      <p>Please find API Usage on the DOTD, SEARCH, and BITCOIN Pages</p>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
      }
    },
    head () {
      return {
        title: this.title,
        meta: [
          // hid is used as unique identifier. Do not use `vmid` for it as it will not work
          { hid: 'description', name: 'description', content: 'Introduction to the Bitcoin/Cocktail App' }
        ]
      }
    }
  }
</script>

<style> 
</style>
<template>
  <div>
<SideMenu />
    <MainSlider />
  </div>
</template>

<script>
  import Header from '~/components/SideMenu'
  import Menu from '~/components/MainSlider'
  export default {
    components: { Menu, Header  }
  }
</script>

<style>

</style>

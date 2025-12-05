<script setup lang="ts">
const ui = reactive({
})

</script>

<template lang="pug">
UDashboardPanel
  template(#header)
    UDashboardNavbar(title="Home")
      template(#leading)
        UDashboardSidebarCollapse
  template(#body)
    main.container
      h1 Welcome to Nuxt
</template>

<style scoped lang="sass">
</style>

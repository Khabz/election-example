<template>
  <div id="app">
    <top-navigation />
    <div class="container-fluid">
      <div class="row">
        <side-navigation />
        <router-view />
      </div>
    </div>
  </div>
</template>

<script>
import SideNavigation from './components/SideNavigation.vue'
import TopNavigation from './components/TopNavigation.vue'
export default {
  components: {
    TopNavigation,
    SideNavigation
  }
}
</script>


    SideNavigation
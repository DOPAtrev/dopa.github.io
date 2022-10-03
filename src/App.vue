<template>
  <div id="app">
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav> -->
    <router-view/>
    <FooterView/>
  </div>
</template>

<script>
import FooterView from '@/components/FooterView'

export default {
  components: {
    FooterView,
  },
}

</script>

<style src="@/css/main.scss" lang="scss" />

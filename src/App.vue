<template>
  <div id="app">
  <Navbar />
    <div class="container">
        <router-view />
    </div>
  </div>
</template>

<script>

import Navbar from './components/NavBar'

export default {
  name: 'app',
  components: {
    Navbar,
  },
}
</script>


<template>
  <div id="app">
    <header>
      <RdiNavbar />
    </header>

    <main>
      <!-- Main content (like book listings) will be added here -->
    </main>

    <footer>
      <!-- Footer content goes here -->
    </footer>
  </div>
</template>

<script>
import RdiNavbar from './components/RdiNavbar.vue';

export default {
  name: 'App',
  components: {
    RdiNavbar
  }
}
</script>

<style>
/* Global styles */
#app {
  text-align: center;
}

header, footer {
  padding: 1rem;
  background-color: #f5f5f5;
}

main {
  margin: 1rem;
}
</style>

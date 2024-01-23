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
body, html {
  font-family: 'Comfortaa', cursive;
  text-transform: lowercase;
  margin: 0;
  height: 100%;
  padding: 0;
  box-sizing: border-box; /* Include padding and border in the element's total width and height */
  overflow-x: hidden; /* Hide horizontal scrollbar */
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: stretch; /* Stretch children to fill width */
  min-height: 100vh;
  text-align: center;
  width: 100%;
  margin: 0;
  padding: 0;
}

header {
  background-color: #f5f5f5;
  font-size: 1.5em;
  font-weight: 700;
}

/* Styles for Navbar */
nav {
  background-color: #333;
  color: white;
  padding: 1rem;
  display: flex;
  justify-content: center; /* Center content horizontally */
  align-items: center; /* Center content vertically */
  width: 100%;
}

.navbar-logo {
  height: 50px;
  margin-right: 1rem;
}

main {
  flex: 1;
  margin: 1rem 0;
}

footer {
  padding: 1rem;
  background-color: #f5f5f5;
  width: 100%;
}
</style>

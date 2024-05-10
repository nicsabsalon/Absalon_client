<!--
  This example requires some changes to your config:
  
  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/forms'),
      require('@tailwindcss/aspect-ratio'),
    ],
  }
  ```
-->
<template>
    <div>
      <Navigation />
      <NuxtLayout name="default">
        <!-- Your page content goes here -->
      </NuxtLayout>
    </div>
  </template>
  
  <script>
  import Navigation from '~/components/navigation.vue'
  
  export default {
    components: {
      Navigation
    }
  }
  </script>
<template>
    <div>
      <!-- <Navbar /> -->
      <h1>Add Student</h1>
      <form @submit.prevent="submit">
        <!-- Form fields for adding a new student -->
        <button type="submit">Add Student</button>
      </form>
    </div>
  </template>

  <script>
//   import Navbar from './Navbar.vue';

  export default {
    // components: {
    //   Navbar
    // },
    methods: {
      submit() {
        // Handle adding a new student
      }
    }
  }
  </script>

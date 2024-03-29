<template>
    <div>
      <Navbar />
      <h1>Dashboard</h1>
      <button @click="logout">Logout</button>
      <table>
        <!-- Table to show student details -->
      </table>
      <router-link to="/add-student">Add Student</router-link>
    </div>
  </template>

  <script>
  import Navbar from './Navbar.vue';

  export default {
    components: {
      Navbar
    },
    methods: {
      logout() {
        // Handle logout
      }
    }
  }
  </script>

<template>
    <div>

      <h1>Dashboard</h1>
      <button @click="logout">Logout</button>
      <table>
        <!-- Table to show student details -->
      </table>
      <router-link to="/addstudent">Add Student</router-link>
    </div>
  </template>

  <script>


  export default {

    methods: {
      logout() {
        // Handle logout
      }
    }
  }
  </script>

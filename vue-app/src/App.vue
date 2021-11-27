<template>
  <div id="app" class="small-container">
    <h1>Employees</h1>
    <employee-table/>
  </div>
</template>

<script>
import EmployeeTable from './components/EmployeeTable.vue'

export default {
  name: 'app',
  components: {
    EmployeeTable
  }
}
</script>

<style>
  button {
    background: purple;
    border: 1px solid purple;
  }

  .small-container {
    max-width: 680px;
  }
</style>

<template>
  <div>
    Filter:
    <select>
      <option value="200">200</option>
      <option value="200">100</option>
      <option value="200">50</option>
      <option value="200">20</option>
      <option value="200">10</option>
    </select>
  </div>
</template>

<script>
export default {
  name: "FilterTodos"
};
</script>
 
<style>
select {
  margin-top: 20px;
  padding: 6px;
  border: #41b883 1px solid;
}
</style>
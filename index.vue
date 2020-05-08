<template>
  <div class="exmaple-1">
    <h1>User 2</h1>
    <ul>
      <li v-for="item in items" :key="item.id">{{ item }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: ["Test1", "Test2", "Test3", "Test4"]
    };
  }
};
</script>

<style>
</style>
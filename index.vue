<template>
  <div class="text-">
    <h1>User 2 is now in the house, get rekt</h1>
    <ul>
      <li v-for="item in items" :key="item.id">{{ item }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: ["Item 1", "Item 1", "Item 1", "Item 1"]
    };
  }
};
</script>

<style>
</style>
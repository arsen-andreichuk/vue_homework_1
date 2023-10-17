<script>
export default {
  name: "TaskCounter",
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<template>
  <h1>Counter</h1>
  <h2>Count: {{ count }}</h2>
  <button @click="count++">+</button>
</template>

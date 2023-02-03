<template>
  <div class="home">
    <button @click="sayHello()">Click Me</button>
    <h1>Your pressed button {{ counter }} times</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 0,
    };
  },
  methods: {
    sayHello() {
      console.log("Hello from methods");
      this.counter++;
    },
  },
};
</script>

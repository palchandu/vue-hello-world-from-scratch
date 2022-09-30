<template>
    <div id="app">
      <input type="text" v-model="message" />
      <h3 class="message">{{ message }}</h3>
      <h3>Some Other Message</h3>
    </div>
</template>

<script>
    export default {
      data() {
        return {
          message: 'Hello Universe',
        };
      },
    };
</script>

<style>
    #app {
      font-size: 18px;
      font-family: 'Roboto', sans-serif;
      color: blue;
    }
</style>
<template>
  <div id="app">
    <h1>Chat</h1>
    <ul>
      <li v-for="message in messages">
        {{messages}}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
  body{
    margin: 50px;
    font-family: sans-serif;
  }
</style>

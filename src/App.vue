<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <p>{{ introduction }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: '自己紹介',
      introduction: 'こんにちは、私の名前はMasatomo Yanagiharaです。'
    }
  }
}
</script>

<style scoped>
#app {
  text-align: center;
  color: #2c3e50;
}
h1 {
  font-size: 2em;
}
</style>

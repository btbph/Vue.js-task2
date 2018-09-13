<template>
  <div id="app">
    <ShowName v-for="(name, index) in nameArr" :key="index" :name="name"/>
  </div>
</template>

<script>

export default {
  data() {
    return {
      nameArr: ['Kate', 'Max', 'John', 'Lisa', 'Anna', 'Bob', 'Nick', 'Conor', 'Bill']
    }
  }
}
</script>

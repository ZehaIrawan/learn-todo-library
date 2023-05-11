<script lang="ts">
  export default {
    props:{
      title: String
    },
    name:'TodoItem',
  }
</script>


<template>
  <main>
    <span>{{ title }}</span>
  </main>
</template>
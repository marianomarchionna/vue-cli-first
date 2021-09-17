<template>
    <h1>{{ msg }}</h1>
</template>

<script>
export default {
  name: 'Title',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
    h1 {
        color: red;
    }
</style>
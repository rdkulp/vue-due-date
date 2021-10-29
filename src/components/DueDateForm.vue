<template>
  <section class="due-date-form-wrapper">
    <h1>Due Date Conversion</h1>
    <input placeholder="3/20/2022" v-model="date">
    <p>{{ date }}</p>
  </section>
</template>

<script>
  export default {
    data () {
      return {
        date: '3/20/2022'
      };
    },
  }
</script>

<style lang="scss">

</style>

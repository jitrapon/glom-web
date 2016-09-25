<template>
  <ol>
    <li v-for="event in events">
      <pre>
        {{event.name}}
      </pre>
    </li>
  </ol>
</template>

<script>
  export default {
    data () {
      return {
        events: [{'name': 'Test Event 1'}, {'name': 'Party'}]
      }
    },

    ready () {
    }
  }
</script>

<style>
/* add css here */
</style>
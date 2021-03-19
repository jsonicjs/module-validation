<template>
  <div>
    <h1>Jsonic</h1>
    <pre>{{ json }}</pre>
  </div>
</template>

<script>
import { Jsonic } from 'jsonic'

export default {
  data () {
    return {
      json: Jsonic('a:1')
    }
  }
}
</script>

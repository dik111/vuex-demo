<template>
  <div>
    <my-Addition></my-Addition>

    <p>----------------------</p>
    <my-Subtraction></my-Subtraction>
  </div>
</template>

<script>
import Addition from './components/Addition'
import Subtraction from './components/Subtraction'

export default {
  data () {
    return {

    }
  },
  components: {
    'my-Addition': Addition,
    'my-Subtraction': Subtraction
  }
}
</script>

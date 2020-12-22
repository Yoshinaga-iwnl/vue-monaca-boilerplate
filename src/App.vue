<template>
  <test />
</template>

<script>
import Test from '@/components/atoms/Test/Index'
export default {
  name: 'app',
  computed: {
  },
  components: {
    Test
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ons-splitter-side[side=left][animation=overlay] {
  border-right: 1px solid #BBB;
}
</style>

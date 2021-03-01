<template>
  <div class="home">
    <intro/>
    <situation/>
    <solution/>
    <comparison/>
    <tryYs/>
  </div>
</template>

<script>
// @ is an alias to /src
import intro from '@/components/intro.vue'
import situation from '@/components/situation.vue'
import solution from '@/components/solution.vue'
import comparison from '@/components/comparison.vue'
import tryYs from '@/components/try.vue'

export default {
  name: 'Home',
  components: {
    intro,
    situation,
    solution,
    comparison,
    tryYs
  }
}
</script>

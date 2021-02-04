<template>
  <div>
    Hello World!
  </div>
</template>

<script lang="ts">
import { defineComponent, useAsync, useFetch } from '@nuxtjs/composition-api'

export default defineComponent({
  setup () {

    // first uncomment the line with useFetch() and notice the response time in the devtools network tab, then compare with the useAsync() line

    // useFetch(() => console.log('response time >200ms'))

    // useAsync(() => console.log('response time ~15ms'))
  }
})
</script>

<template>
  <div>
    Hello World!
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  setup () {
    const api = 'https://randomuser.me/api/?results=10&inc=name,dob,picture'
  }
})
</script>

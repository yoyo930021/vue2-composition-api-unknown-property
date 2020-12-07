<template>
  <div>
    {{ b }}
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  data () {
    return {
      a: 1
    }
  }
})
</script>

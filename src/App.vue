<template>
  <BarChart :chart-data="{}" />
</template>

<script>
import { defineComponent } from '@vue/composition-api'
import { BarChart } from 'vue-chart-3'

export default defineComponent({
  components: { BarChart },
})
</script>

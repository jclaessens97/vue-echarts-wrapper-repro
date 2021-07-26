<template>
  <div id="app">
    <chart></chart>
  </div>
</template>

<script>
import ECharts from 'chart-wrapper'

export default {
  name: 'App',
  components: {
    chart: ECharts,
  },
}
</script>


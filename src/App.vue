<template>

  <div id="chart1">
      <AreaChart/>
  </div>

</template>

<script>
import AreaChart from './components/AreaChart.vue'


export default {
  name: 'app',
  components: {
    AreaChart,
  },
}

</script>


<style lang="css">
  #chart1 {
      width: 100%;
  }

</style>

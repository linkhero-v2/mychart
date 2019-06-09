<template>
  <div class="chart-container">
    <el-button>add click </el-button>
    <chart height="100%" width="100%" />
  </div>
</template>

<script>
import Chart from '@/components/Charts/LineMarker'

export default {
  name: 'LineChart',
  components: { Chart }
}
</script>

<style scoped>
.chart-container{
  position: relative;
  width: 100%;
  height: calc(100vh - 84px);
}
</style>


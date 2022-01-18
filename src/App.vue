<template>
  <div id="app">
    <!-- 折线 -->
    <LineChart />
    <!-- 柱状图 -->
    <LineChart2 />
     <!-- 有错误 -->
    <RaceChart />
    <!-- 柱状图 -->
    <RaceChart_1 />
    <!-- 待研究 -->
    <RaceChart_2 />
  </div>
</template>

<script>
import LineChart from './components/LineChart.vue'
import LineChart2 from './components/LineChart2.vue'
import RaceChart from './components/RaceChart.vue'
import RaceChart_1 from './components/RaceChart_1.vue'
import RaceChart_2 from './components/RaceChart_2.vue'

export default {
  name: 'app',
  components: {
    LineChart,
    LineChart2,
    RaceChart,
    RaceChart_1,
    RaceChart_2
  }
}
</script>

<style>

</style>

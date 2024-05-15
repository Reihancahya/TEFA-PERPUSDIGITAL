<template>
    <div>
        <h1>Statistik Pengunjung</h1>
        <canvas id="myChart"></canvas>
    </div>
</template>   

<script stup lang="td">
import Chart, {type ChartConfiguration, type ChartItem } from 'chat.js/auto';

const labels = [
    'January',
    'February',
    'March',
    'April',
    'May',
    'June',
];

const data = {
    labels: labels,
    datasets: [{
        label: 'pengunjung',
        backgroundcolor: 'rgb(38, 92, 181)',
        bordercolor: 'rgb(255, 99, 132)',
        data: [20, 10, 5, 2, 20, 50, 77],
    }]
}

const config: ChartConfiguration = {
    type: 'bar',
    dta: data,
    options:{}
}

onMounted(() => {
    const canvastag = <ChartItem>document.getElemenById('myChart')
    new Chart(
        canvasTag,
        config
    )
})
</script>

<style scoped>
#myChart {
    width: 1500px;
}
</style>
---
title: "주식"
type: "page"

banner:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'
  image: 'concert.jpg'

---

<div class="portfolio-section">
  <h2>My Portfolio</h2>
  <div class="chart-container" style="position: relative; height:40vh; width:80vw">
    <canvas id="myChart"></canvas>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  var ctx = document.getElementById('myChart').getContext('2d');
  var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['Stock A', 'Stock B', 'Stock C', 'Stock D'],
      datasets: [{
        label: '# of Votes',
        data: [12, 19, 3, 5],
        backgroundColor: [
          'rgba(255, 99, 132, 0.2)',
          'rgba(54, 162, 235, 0.2)',
          'rgba(255, 206, 86, 0.2)',
          'rgba(75, 192, 192, 0.2)',
        ],
        borderColor: [
          'rgba(255, 99, 132, 1)',
          'rgba(54, 162, 235, 1)',
          'rgba(255, 206, 86, 1)',
          'rgba(75, 192, 192, 1)',
        ],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>

<style>
.portfolio-section {
  text-align: center;
  margin: 50px 0;
}

.chart-container {
  margin: 0 auto;
}
</style>

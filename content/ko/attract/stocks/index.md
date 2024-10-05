---
title: "주식"
type: "page"

banner:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'
  image: 'stock.jpg'

---

<div class="portfolio-section">
  <h2>주식 보유현황</h2>
  <div class="chart-container" style="position: relative; height:40vh; width:80vw">
    <canvas id="myPieChart"></canvas>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  var ctx = document.getElementById('myPieChart').getContext('2d');
  var myPieChart = new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: ['엔비디아', 'FTAI', 'SK텔레콤', '테슬라'],
      datasets: [{
        label: '포트폴리오',
        data: [60, 20, 10, 10],
        backgroundColor: [
          'rgba(255, 99, 132, 0.6)',
          'rgba(54, 162, 235, 0.6)',
          'rgba(255, 206, 86, 0.6)',
          'rgba(75, 192, 192, 0.6)',
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
      responsive: true,
      plugins: {
        legend: {
          position: 'top',
        },
        tooltip: {
          callbacks: {
            label: function(tooltipItem) {
              return tooltipItem.label + ': ' + tooltipItem.raw + '%';
            }
          }
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

많은 돈을 잃었습니다..

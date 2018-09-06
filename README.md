<!DOCTYPE html>
<html lang="en">

  <head>
  <meta charset="UTF-8">
  <title>311 NYC</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#157878">
  <link rel="stylesheet" href="/css/normalize.css">
  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,700' rel='stylesheet' type='text/css'>
  <link rel="stylesheet" href="/css/cayman.css">
</head>

  <body>
    <section class="page-header">
  <h1 class="project-name">311 NYC</h1>
  <h2 class="project-tagline">Regression Predictions on NYC311 Data</h2>
  <a href="#" class="btn">View on GitHub</a>
</section>
<!-Data intro>
    <section class="main-content">

      <div id="home">
  <h1>The Data:</h1>
  <ul class="posts">

Welcome to Jekyll!

  </ul>
</div>
</section>

<! Data Cleaning:>
    <section class="main-content">

      <div id="home">
  <h1> Data Mungeing:</h1>
  <ul class="posts">

Welcome to Jekyll!

  </ul>
</div>
</section>

<!-Initial Findings>
    <section class="main-content">

      <div id="home">
  <h1>Basic Info:</h1>
  <ul class="posts">

We can see a breakdown of calls by Borough
<div>
    <a href="https://plot.ly/~nickeloustex/4/?share_key=XbL5jS1S81uSSodFKMFurf" target="_blank" title="basic_pie_chart" style="display: block; text-align: center;"><img src="https://plot.ly/~nickeloustex/4.png?share_key=XbL5jS1S81uSSodFKMFurf" alt="basic_pie_chart" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="nickeloustex:4" sharekey-plotly="XbL5jS1S81uSSodFKMFurf" src="https://plot.ly/embed.js" async></script>
</div>
<div>
    <a href="https://plot.ly/~nickeloustex/2/?share_key=ccbE9YFljywjZR8q8OOCa6" target="_blank" title="Top Complaints" style="display: block; text-align: center;"><img src="https://plot.ly/~nickeloustex/2.png?share_key=ccbE9YFljywjZR8q8OOCa6" alt="Top Complaints" style="max-width: 50%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="nickeloustex:2" sharekey-plotly="ccbE9YFljywjZR8q8OOCa6" src="https://plot.ly/embed.js" async></script>
</div>


  </ul>
</div>
</section>

<!-Running Regression:>
    <section class="main-content">

      <div id="home">
  <h1>Regression Predicting</h1>
  <ul class="posts">

<pre><code>random_forest = RandomForestRegressor()
random_forest.fit(X_train, y_train)
print('R2 score {}'.format(random_forest.score(X_test,y_test)))
R2 score 0.7741774171081134
</code></pre>

  </ul>
</div>
</section>

<!-Tables of current info:>
    <section class="main-content">

      <div id="home">
  <h1>Current Predictions:</h1>
  <ul class="posts">

Welcome to Jekyll!
 <button type="button">Click Me!</button>

<div class="dropdown">
 <div id="myDropdown" class="dropdown-content">
   <a href="../docs/Homeless_complaints_flagged.html">Homeless Complaints</a>
   <a href="#">Noise Complaints</a>
   <a href="#">Rodent Complaints</a>
   <a href="#">Bulk Pickup</a>
 </div>
</div>
</section>

<!-Building Dashboards>
    <section class="main-content">

      <div id="home">
  <h1>Data Dashboarding:</h1>
  <ul class="posts">

Rather than vizualize and call all data, we can create dashboards based upon specifically interesting events that occur:

<embed src="../docs/Homeless_complaints_flagged.html" style="width:800px; height: 300px;" align="right">an>

</section>

<!-Findings>
    <section class="main-content">

      <div id="home">
  <h1>Findings & Conclusion:</h1>
  <ul class="posts">

Welcome to Jekyll!

  </ul>
</div>
</section>

<!-Next Steps>
    <section class="main-content">

      <div id="home">
  <h1>The Future:</h1>
  <ul class="posts">

Welcome to Jekyll!

  </ul>
</div>
</section>
    <footer class="site-footer">
<span class="site-footer-owner"><a href="">311 NYC</a> is maintained by <a href="https://www.linkedin.com/in/nickeloustex/">Nick Teixeira</a>.</span>
<span class="site-footer-credits">This page was generated by <a href="https://pages.github.com">GitHub Pages</a>.</span>
</footer>

  </body>
</html>

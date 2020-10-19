---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: none
permalink: /
---
<html>
<head>
  <title>Daren Palmer's Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
  <link rel="stylesheet" href="/style.css">
</head>
<body>
  
  {% include h.html %}

  <h2>Current Projects 🔴</h2>
  <div id="current">
    <div class="row">
      <div class="col-sm-12">
        <div class="card bg-dark text-white">
          <div class="card-body">
            <h5 class="card-title">Introduction to Python and Data Visualization course @ My high school (EJM Lille)</h5>
            <p class="card-text">I'm going to be giving an introduction to Python and Data Visualization using pandas and matplotlib with my good friend Adrien Dumont.<br>The course will be from September to February and the subjects will change to web app development with Flutter after that.</p>
            <a href="https://colab.research.google.com/drive/1ad9tzhB9e20ZM2iDjWfMxIibJ5EwJ_Ny?usp=sharing" class="btn btn-primary" target="_blank">View Google Colab</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-12">
        <div class="card bg-dark text-white">
          <div class="card-body">
            <h5 class="card-title">Responding to COVID</h5>
            <p class="card-text">Our innovation club has found a way to help people social distance, you can learn more with the diagram below</p>
            <a href="Rush hour detection system.xmind" class="btn btn-outline-light" target="_blank" download>Download project diagram</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-12">
        <div class="card bg-dark text-white">
          <div class="card-body">
            <h5 class="card-title">my-privacy.online</h5>
            <p class="card-text">I've published a website that grades user's privacy based on the websites/services they use.</p>
            <a href="https://github.com/ColleSerre/PrivacyApp" class="btn btn-primary" target="_blank">View Github repository</a>
            <a href="https://www.my-privacy.online" class="btn btn-warning" style="margin-left: 5px;">Visit site</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-12">
        <div class="card bg-dark text-white">
          <div class="card-body">
            <h5 class="card-title">Message in a bottle</h5>
            <p class="card-text">A Twitter bot that allows unacquainted users to come in contact with each other</p>
            <a href="https://github.com/ColleSerre/Twitter-Bot" class="btn btn-primary" target="_blank">View Github repository</a>
            <a href="diagram.xmind" download class="btn btn-outline-light" id="diagram">Download project diagram</a>
          </div>
        </div>
      </div>
    </div>
  </div>




  <h3>Featured projects:</h3>
  <div class="row">
    <div class="col-sm-6">
      <div class="card bg-dark text-white">
        <div class="card-body">
          <h5 class="card-title">Red and Gold app</h5>
          <p class="card-text">A WIP project to allow users to educate themselves about the marxist ideas.</p>
          <a href="https://github.com/ColleSerre/RedAndGold" class="btn btn-primary" target="_blank">View Github repository</a>
        </div>
      </div>
    </div>
    <div class="col-sm-6">
      <div class="card bg-dark text-white">
        <div class="card-body">
          <h5 class="card-title">Scraping Tool</h5>
          <p class="card-text">A tool to scrape Amazon and Ebay easily (more feature to come)</p>
          <a href="https://github.com/ColleSerre/ScrapingTool" class="btn btn-primary" target="_blank">View Github repository</a>
        </div>
      </div>
    </div>
    <div class="col-sm-12">
      <div class="card bg-dark text-white">
        <div class="card-body">
          <h5 class="card-title">Google CLI</h5>
          <p class="card-text">As useful as it is simple. A command line program to search Google or Youtube for queries</p>
          <a href="https://github.com/ColleSerre/GoogleCLI" class="btn btn-primary" target="_blank">View Github repository</a>
        </div>
      </div>
    </div>
  </div>

</body>
</html>

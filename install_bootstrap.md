## What you will learn in this section

This section will help you understand and install Bootstrap on your system.

The first thing you need to do is access the getting started page on getBootstrap. Here you will notice three different download options depending on your level and skill set.

If you’re completely new to Bootstrap, you’ll want to stick with the basic Bootstrap download. This contains compiled and minified CSS, JavaScript, and fonts. No docs or original source files are included.

If you’re experienced using CSS pre-processors to extend the CSS language, there are two additional options available. The Source Code installation contains Source Less, JavaScript and font files. The SASS installation is Bootstrap ported from Less to Sass for easy inclusion in Rails, Compass, or Sass-only projects.

In this tutorial we will cover Bootstrap for the beginner level for those who are new to Bootstrap. Hope you all have downloaded the Bootstrap from getBootstrap.

### What is Next

Once you have downloaded the Bootstrap you will get the following folder structure when you unpacke the compliled version of Bootstrap. Lets have a look,

```
bootstrap/
├──css/
|    ├── bootstrap.css
|    ├── bootstrap.min.css
|    ├── bootstrap-theme.css
|    └── bootstrap-theme.min.css
├──jss/
|    ├── bootstrap.js
|    └── bootstrap.min.js
└── fonts/
     ├── glyphicons-halflings-regular.eot
     ├── glyphicons-halflings-regular.svg
     ├── glyphicons-halflings-regular.ttf
     └── glyphicons-halflings-regular.woff    
```      
This is the basic structure of the file you can also add the file in order to modify the standard css. We will cover it in the later part of this tutorial. How about having some magic and fun? We at Hello Django belief in the proverb 'All work and no play make Jack a dull boy'.
So try the following steps:
```
Create a file 'index.html' in bootstrp folder
Open 'index.html' in your editor.
```

Now lets copy the given bellow code and paste it in our file.

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="icon" href="../../favicon.ico">

    <title>Learn Bootstrap</title>

    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <link href="css/ie10-viewport-bug-workaround.css" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="css/custom.css" rel="stylesheet">

    <!-- Just for debugging purposes. Don't actually copy these 2 lines! -->
    <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->
    <script src="js/ie-emulation-modes-warning.js"></script>

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>

  <body>

    <div class="container">
      <div class="header clearfix">
        <nav>
          <ul class="nav nav-pills pull-right">
            <li role="presentation"><a href="#">About Bootstrap</a></li>
            <li role="presentation"><a href="#">Installation</a></li>
            <li role="presentation"><a href="#">Components</a></li>
            <li role="presentation"><a href="#">Customization</a></li>
          </ul>
        </nav>
        <h3 class="text-muted">Learn Bootstrap</h3>
      </div>

      <div class="jumbotron">
        <h2>Software Development</h2>
        <p class="lead">We at Hello Django belief in the proverb 'All work and no play make Jack a dull boy'.</p>
        <p><a class="btn btn-lg btn-primary" href="#" role="button">Sign up today</a></p>
      </div>

      <div class="row marketing">
        <div class="col-lg-6">
          <h4><span class="glyphicon glyphicon-send" aria-hidden="true"></span>Exam Stress</h4>
          <p>Exam stress is tough but if you want to get somewhere, you have to put the work in. Just like when you’re in the gym and your instructor shouts motivational comments to keep the pressure on.</p>

          <h4><span class="glyphicon glyphicon-stats" aria-hidden="true"></span> Run for your Goal</h4>
          <p>Push yourself because, no one else is going to do it for you.</p>

          <h4><span class="glyphicon glyphicon-earphone" aria-hidden="true"></span> Start now</h4>
          <p>The secret to getting ahead is to get started.</p>
        </div>

        <div class="col-lg-6">
          <h4><span class="glyphicon glyphicon-cloud-upload" aria-hidden="true"></span>Achieve your Goal</h4>
          <p>The expert in anything was once a beginner.</p>

          <h4><span class="glyphicon glyphicon-cd" aria-hidden="true"></span> Don't Regreat</h4>
          <p>A year from you will wish you had started it today.</p>

          <h4><span class="glyphicon glyphicon-king" aria-hidden="true"></span>Solve it</h4>
          <p>Every problem might not have a solution right now, but don’t forget that but every solution was once a problem.</p>
        </div>

        <nav>
  <ul class="pagination">
    <li>
      <a href="#" aria-label="Previous">
        <span aria-hidden="true">&laquo;</span>
      </a>
    </li>
    <li><a href="#">1</a></li>
    <li><a href="#">2</a></li>
    <li><a href="#">3</a></li>
    <li><a href="#">4</a></li>
    <li><a href="#">5</a></li>
    <li>
      <a href="#" aria-label="Next">
        <span aria-hidden="true">&raquo;</span>
      </a>
    </li>
  </ul>
</nav>

<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
    <span class="sr-only">60% Complete</span>
  </div>
</div>
      </div>

      <footer class="footer">
        <p>&copy; 2016 Copyright</p>
      </footer>

    </div> <!-- /container -->


    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <script src="../../assets/js/ie10-viewport-bug-workaround.js"></script>
  </body>
</html>
```
Now open your 'index.html' and have a look in your browser isn't it great. Hey!you learned Bootstrap just right now, isn't it? Don't get afraid looking on the above code, we will explain you each and every line of the code.    

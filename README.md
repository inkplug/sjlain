# sjlain
Portfolio used at FreeCodeCamp

<!DOCTYPE html>
<html >
  <head>
    <meta charset="UTF-8">
    <title>FreeCodeCamp Portfolio Site</title>
    
    
<!-- Bootstrap Core CSS --> 

<link rel='stylesheet prefetch' href='https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css'>

<!-- Custom CSS -->
<link rel="stylesheet" href="css/style.css">

<!-- Custom Fonts -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.css" rel="stylesheet" type="text/css">
<link href="http://fonts.googleapis.com/css?family=Lora:400,700,400italic,700italic" rel="stylesheet" type="text/css">
<link href="http://fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet" type="text/css">
    
    
    
  </head>

<body>

<body id="page-top" data-spy="scroll" data-target=".navbar-fixed-top">

  <!-- Navigation -->
  <nav class="navbar navbar-custom navbar-fixed-top" role="navigation">
    <div class="container">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-main-collapse">
                    <i class="fa fa-bars"></i>
                </button>
        <a class="navbar-brand page-scroll" href="#page-top">
          <i class="fa fa-play-circle"></i> <span class="light">Steven Lain</span>
        </a>
      </div>

      <!-- Collect the nav links, forms, and other content for toggling -->
      <div class="collapse navbar-collapse navbar-right navbar-main-collapse">
        <ul class="nav navbar-nav">
          <!-- Hidden li included to remove active class from about link when scrolled up past about section -->
          <li class="hidden">
            <a href="#page-top"></a>
          </li>
          <li>
            <a class="page-scroll" href="#about">about</a>
          </li>
          <li>
            <a class="page-scroll" href="#project">work</a>
          </li>
          <li>
            <a class="page-scroll" href="#contact">contact</a>
          </li>
        </ul>
      </div>
      <!-- /.navbar-collapse -->
    </div>
    <!-- /.container -->
  </nav>

  <!-- Intro Header -->
  <header class="intro">
    <div class="intro-body">
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h1 class="brand-heading"></h1>
            <p class="intro-text">Greetings, this is my portfolio site created for my certificate @ <a href="https://www.freecodecamp.com/about">freeCodeCamp</a><br></p>
            <a href="#about" class="btn btn-circle page-scroll">
              <i class="fa fa-angle-double-down animated"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </header>

  <!-- About Section -->
  <section id="about" class="container container-main content-section text-center">
    <div class="row">
      <div class="col-lg-8 col-lg-offset-2">
        <h2>About Me</h2>
        <p>Hi, I'm Steven Lain and I sling web, but not like Peter Parker! I am mostly a self taught web enthusiast who aspires to learn as much as I can about all things web. I want to be able to create / maintain the full stack and I'm not talking pancakes...
        </p>
        <a href="#project" class="btn btn-circle page-scroll">
          <i class="fa fa-angle-double-down animated"></i>
        </a>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="project" class="content-section text-center">
    <div class="project-section">
      <div class="container container-main">
        <div class="col-lg-8 col-lg-offset-2">
          <h2>Here Are Some of My Projects</h2>
          <p>These are some of my past projects that I have worked on collaboratively with my partner in crime, the very beautiful & talented -<a href="http://www.mistieallen.com/"> Mistie Allen</a>.</p>
          <p>We started - INKPLUG, where we make things together for the web.</p>

          <a href="#" class="btn btn-default btn-lg">Visit Inkplug</a>


          <!-- START THE FEATURETTES -->

          <hr class="featurette-divider">

          <div class="row featurette">
            <div class="col-md-7">
              <h2 class="featurette-heading">First featurette heading. <span class="text-muted">It'll blow your mind.</span></h2>
              <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
              <a href="http://www.ediblealternative.com/" class="btn btn-default btn-lg">Visit</a>
            </div>
            <div class="col-md-5">
            <img src="data:image/png;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" data-src="http://inkplug.github.io/sjlain/img/EA.png" width="300">
              <!--<img src="http://inkplug.github.io/sjlain/img/EA.png" width="300">-->
              <!--<img src="https://unsplash.it/g/200/300" alt="Generic placeholder image">-->
            </div>
          </div>

          <hr class="featurette-divider">

          <div class="row featurette">
            <div class="col-md-7 col-md-push-5">
              <h2 class="featurette-heading">Oh yeah, it's that good. <span class="text-muted">See for yourself.</span></h2>
              <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
              <a href="http://highpointhealthproducts.com/" class="btn btn-default btn-lg">Visit</a>
            </div>
            <div class="col-md-5 col-md-pull-7">
            <img src="data:image/png;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" data-src="http://inkplug.github.io/sjlain/img/HP.png" width="300">
              <!--<img src="http://inkplug.github.io/sjlain/img/HP.png" width="300">-->
              <!--<img src="https://unsplash.it/g/200/300" alt="Generic placeholder image">-->
            </div>
          </div>

          <hr class="featurette-divider">

          <div class="row featurette">
            <div class="col-md-7">
              <h2 class="featurette-heading">And lastly, this one. <span class="text-muted">Checkmate.</span></h2>
              <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
              <a href="http://thelawnranger479.com/" class="btn btn-default btn-lg">Visit</a>
            </div>
            <div class="col-md-5">
            <img src="data:image/png;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" data-src="http://inkplug.github.io/sjlain/img/LR.png" width="300">
              <!--<img src="http://inkplug.github.io/sjlain/img/LR.png" width="300">-->
              <!--<img src="https://unsplash.it/g/200/300" alt="Generic placeholder image">-->
            </div>
          </div>

          <hr class="featurette-divider">

          <a href="#contact" class="btn btn-circle page-scroll">
            <i class="fa fa-angle-double-down animated"></i>
          </a>

          <!-- /END THE FEATURETTES -->

        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="container container-main content-section text-center">
    <div class="row">
      <div class="col-lg-8 col-lg-offset-2">
        <h2>Let's Talk!</h2>
        <p>I am available for hire and looking forward to taking other interesting projects or to just say hello!</p>
        <p><a href="mailto:sjlain@inkplug.com">sjlain@inkplug.com</a>
        </p>
        <ul class="list-inline banner-social-buttons">
          <li>
            <a href="#" class="btn btn-default btn-lg"><i class="fa fa-twitter fa-fw"></i> <span class="network-name">Twitter</span></a>
          </li>
          <li>
            <a href="https://github.com/inkplug" class="btn btn-default btn-lg"><i class="fa fa-github fa-fw"></i> <span class="network-name">Github</span></a>
          </li>
          <li>
            <a href="#" class="btn btn-default btn-lg"><i class="fa fa-google-plus fa-fw"></i> <span class="network-name">Google+</span></a>
          </li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container text-center">

      <p>Copyright &copy; Steven Lain 2016</p>
      <br>
      <a href="#page-top" class="btn btn-circle page-scroll">
        <i class="fa fa-angle-double-up animated"></i>
      </a>
    </div>
  </footer>

  <!-- jQuery -->
  <script src="js/jquery.js"></script>

  <!-- Bootstrap Core JavaScript -->
  <script src="js/bootstrap.min.js"></script>

  <!-- Plugin JavaScript -->
  <script src="js/jquery.easing.min.js"></script>

  <!-- Google Maps API Key - Use your own API key to enable the map feature. More information on the Google Maps API can be found at https://developers.google.com/maps/ -->
  </script>


</body>

</html>
<script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.2/jquery.min.js'></script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.min.js'></script>
<script src="js/index.js"></script>

<script>
function init() {
var imgDefer = document.getElementsByTagName('img');
for (var i=0; i<imgDefer.length; i++) {
if(imgDefer[i].getAttribute('data-src')) {
imgDefer[i].setAttribute('src',imgDefer[i].getAttribute('data-src'));
} } }
window.onload = init;
</script>

    
    
    
  </body>
</html>

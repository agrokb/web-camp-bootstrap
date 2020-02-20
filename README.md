<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <!--Font  Awesome-->
  <script src="https://kit.fontawesome.com/57a250885d.js" crossorigin="anonymous"></script>
  <!--Bootstrap-->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
  <!--CSS-->
  <link rel="stylesheet" href="css/styles.css">
   <!--Google fonts -->
   <link href="https://fonts.googleapis.com/css?family=Montserrat|Ubuntu&display=swap" rel="stylesheet">
</head>

<body>

  <section id="title" class="colored-background">
    <div class="container-fluid">
      <!-- Nav Bar -->
      <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="#">TinDog</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Download</a>
            </li>
          </ul>
        </div>
      </nav>



      <!-- Title -->
      <div class="row">
        <div class="col-lg-6">
          <h1 class="big-heading">Meet new and interesting dogs nearby.</h1>
          <button type="button" class="btn btn-dark btn-lg download-button"><i class="fab fa-apple"></i>Download</button>
          <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="fab fa-google-play"></i>Download</button>
        </div>
        <div class="col-lg-6">
          <img class="title-image" src="images/iphone6.png" alt="iphone-mockup">
        </div>
      </div>
    </div>
  </section>
  


  <!-- Features -->

  <section id="features" class="white-background">
    <div class="container-fluid">
  <div class="row">
    <div class="col-lg-4 features-item">
    <i class="fas fa-check-circle features-icon"></i>
    <h3 class="feature-title">Easy to use.</h3>
    <p>So easy to use, even your dog could do it.</p>
  </div>
  <div class="col-lg-4 features-item">
    <i class="fas fa-bullseye features-icon"></i>
    <h3 class="feature-title">Elite Clientele</h3>
    <p>We have all the dogs, the greatest dogs.</p>
  </div>
  <div class="col-lg-4 features-item">
    <i class="fas fa-heart features-icon"></i>    
    <h3 class="feature-title">Guaranteed to work.</h3>
    <p>Find the love of your dog's life or your money back.</p>
  </div>
  </div>
</div>
  </section>


  <!-- Testimonials -->

  <section id="testimonials" class="testimonials-color">
    <div class="container-fluid">
    <div id="carouselExampleInterval" class="carousel slide">
      <div class="carousel-inner">
        <div class="carousel-item active container-fluid" data-pause="hover">
          <h2 class="estimonials-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item container-fluid" data-pause="hover">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em> 
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleInterval" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleInterval" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    </div>

    

  </section>


  <!-- Press -->

  <section id="press" class="testimonials-color">
    <div>
    <img class="press-logo" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="images/mashable.png" alt="mashable-logo">
    </div>
  </section>


  <!-- Pricing -->

  <section id="pricing" class="white-background">
   <div class="container-fluid">
    <h2 class="section-heading">A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>
<div class="row">
  <div class="pricing-column col-lg-4 col-md-6">
    <div class="card">
      <div class="card-header">
        <h3>Chihuahua</h3>
      </div>
      <div class="card-body">
        <h2 class="price-text">Free</h2>
        <p>5 Matches Per Day</p>
        <p>10 Messages Per Day</p>
        <p>Unlimited App Usage</p>
        <button type="button" class="btn btn-lg btn-block btn-outline-dark">Sign up</button>   
      </div>
    </div>
  </div>
    <div class="pricing-column col-lg-4 col-md-6">
      <div class="card">
        <div class="card-header">
          <h3>Labrador</h3>
        </div>
        <div class="card-body">
          <h2 class="price-text">$49 / mo</h2>
          <p>Unlimited Matches</p>
          <p>Unlimited Messages</p>
          <p>Unlimited App Usage</p>
          <button type="button" class="btn btn-lg btn-block btn-dark">Sign Up</button>    
        </div>
      </div>
    </div>
    <div class="pricing-column col-lg-4">
      <div class="card">
        <div class="card-header">
          <h3>Mastiff</h3>
        </div>
        <div class="card-body">
          <h2 class="price-text">$99 / mo</h2>
      <p>Pirority Listing</p>
      <p>Unlimited Matches</p>
      <p>Unlimited Messages</p>
      <p>Unlimited App Usage</p>
      <button type="button" class="btn btn-lg btn-block btn-dark">Sign Up</button>
        </div>
      </div>
    </div>
  </div>
  </div> 
  </section>


  <!-- Call to Action -->
  <section id="cta" class="colored-background">
    <div class="container-fluid">

    <h3 class="big-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button type="button" class="btn btn-dark btn-lg download-button"><i class="fab fa-apple"></i>Download   </button>
    <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="fab fa-google-play"></i>Download</button>
</div>
  </section>


  <!-- Footer -->

  <footer id="footer" class="container-fluid white-background">
    <i class="fab fa-twitter footer-icon"></i>
    <i class="fab fa-facebook-f footer-icon"></i>
    <i class="fab fa-instagram footer-icon"></i>
    <i class="fas fa-envelope footer-icon"></i>

    <p>© Copyright 2018 TinDog</p>

  </footer>

  <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
    integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous">
  </script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
    integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous">
  </script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
    integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous">
  </script>

</body>

</html>

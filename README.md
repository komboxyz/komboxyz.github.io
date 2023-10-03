<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Start training now!</title>
  <link rel="icon" type="image/x-icon" href="Logo.ico">
  <link href='https://fonts.googleapis.com/css?family=Kanit' rel='stylesheet'>
  <!--BOOTSTRAP IMPORT --> 
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
  
  
  <style>


    /*headerbar*/
.nav-link{
  color: red;
}
h1{
  color:crimson;
  text-align: center;
}

li{
  font-size: large;
}

  </style>

</head>
<div class="container">

<body style="font-family:'Kanit'">

  <!--HEADBAR-->
    <div class="container">
      <header class="d-flex justify-content-center py-3">
        <ul class="nav nav-pills">
          <li class="nav-item"><a href="#Features" class="nav-link">Features</a></li>
          <li class="nav-item"><a href="#Schedule" class="nav-link">Schedule</a></li>
          <img src="Logo.jpg" width="75px" length="75px">
          <li class="nav-item"><a href="#Pricing" class="nav-link">Pricing</a></li>
          <li class="nav-item"><a href="#Contact" class="nav-link">Contact</a></li>
        </ul>
      </header>
    </div>
     <!--HEADBAR END-->



     <hr/><br>



        <!--CAROUSEL   width="600px" height="200px">  -->
        <h1 id="Features">Get started with your workout journey!</h1> <br>
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="true">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active" data-bs-interval="5000">
              <img src="page.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h5>First slide label</h5>
                <p>Some representative placeholder content for the first slide.</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="page.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h5>Second slide label</h5>
                <p>Some representative placeholder content for the second slide.</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="page.jpg" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h5>Third slide label</h5>
                <p>Some representative placeholder content for the third slide.</p>
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div><br>
<!--CAROUSEL END--> 

<hr/><br>

<!--SCHEDULE-->
<h1 id="Schedule">Check this table to see my availabilities!</h1> <br>
<div class="bd-example">
  <table class="table">
    <thead>
      <tr>
        <th scope="col">Time/Day</th>
        <th scope="col">Monday</th>
        <th scope="col">Tuesday</th>
        <th scope="col">Wednesday</th>
        <th scope="col">Thursday</th>
        <th scope="col">Friday</th>
        <th scope="col">Saturday</th>
        <th scope="col">Sunday</th>
      </tr>
    </thead>
    <tbody>
      <tr class="table-active">
        <th scope="row">6:00am - 7:00am</th>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
      </tr>
      <tr>
        <th scope="row">7:00am - 8:00am</th>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
      </tr>
      <tr class="table-active">
        <th scope="row">8:00am - 9:00am</th>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
      </tr>
      <tr>
        <th scope="row">9:00am - 10:00am</th>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
        <td>Available</td>
      </tr>
      <tr class="table-active">
      <th scope="row">10:00am - 11:00am</th>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
    </tr>
    <tr>
      <th scope="row">11:00am - 12:00pm</th>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
    </tr>
    <tr class="table-active">
      <th scope="row">12:00pm - 1:00pm</th>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
    </tr>
    <tr>
      <th scope="row">1:00pm - 2:00pm</th>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
    </tr>
    <tr class="table-active">
      <th scope="row">2:00pm - 3:00pm</th>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
    </tr>
    <tr>
      <th scope="row">3:00pm - 4:00pm</th>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
      <td>Available</td>
    </tr>
    <tr class="table-active">
    <th scope="row">4:00pm - 5:00pm</th>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
  </tr>
  <tr>
    <th scope="row">5:00pm - 6:00pm</th>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td class="table-danger">Unavailable</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
  </tr>
  <tr class="table-active">
    <th scope="row">6:00pm - 7:00pm</th>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td class="table-danger">Unavailable</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
  </tr>
  <tr>
    <th scope="row">7:00pm - 8:00pm</th>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td class="table-danger">Unavailable</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
  </tr>
  <tr class="table-active">
    <th scope="row">8:00pm - 9:00pm</th>
    <td>Available</td>
    <td>Available</td>
    <td class="table-danger">Unavailable</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
    <td>Available</td>
  </tr>
  <tr>




    </tbody>
  </table>
</div>
<!--SCHEDULE END-->





<br>
<hr/><br>
<h1  id="Pricing">Our bundles</h1><br>
<!--PRICING-->
<div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
  <div class="col">
    <div class="card mb-4 rounded-3 shadow-sm">
      <div class="card-header py-3">
        <h4 class="my-0 fw-normal">Free</h4>
      </div>
      <div class="card-body">
        <h1 class="card-title pricing-card-title">$0<small class="text-body-secondary fw-light">/mo</small></h1>
        <ul class="list-unstyled mt-3 mb-4">
          <li>10 users included</li>
          <li>2 GB of storage</li>
          <li>Email support</li>
          <li>Help center access</li>
        </ul>
        <button type="button" class="w-100 btn btn-lg btn-outline-primary">Sign up for free</button>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card mb-4 rounded-3 shadow-sm">
      <div class="card-header py-3">
        <h4 class="my-0 fw-normal">Pro</h4>
      </div>
      <div class="card-body">
        <h1 class="card-title pricing-card-title">$15<small class="text-body-secondary fw-light">/mo</small></h1>
        <ul class="list-unstyled mt-3 mb-4">
          <li>20 users included</li>
          <li>10 GB of storage</li>
          <li>Priority email support</li>
          <li>Help center access</li>
        </ul>
        <button type="button" class="w-100 btn btn-lg btn-primary">Get started</button>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card mb-4 rounded-3 shadow-sm border-primary">
      <div class="card-header py-3 text-bg-primary border-primary">
        <h4 class="my-0 fw-normal" >Enterprise</h4>
      </div>
      <div class="card-body">
        <h1 class="card-title pricing-card-title">$29<small class="text-body-secondary fw-light">/mo</small></h1>
        <ul class="list-unstyled mt-3 mb-4">
          <li>30 users included</li>
          <li>15 GB of storage</li>
          <li>Phone and email support</li>
          <li>Help center access</li>
        </ul>
        <button type="button" class="w-100 btn btn-lg btn-primary">Contact us</button>
      </div>
    </div>
  </div>
</div>

<!--PRICING END-->


<!--CONTACT-->
<br>
<hr/><br>
<h1  id="Contact">Contact me</h1><br>
<p style="font-size: large; text-align: center" ><img src="wtsp.png" height="100px" width="100px"> Text me on Whatsapp: <a href="tel:9613764567"></a>(+961) 03 764 567
<p style="font-size: large; text-align: center"><a href="instagram.com/fitwithgalia"><img src="insta.png"  height="100px" width="100px"></a> DM me on Instagram: <a href="instagram.com/fitwithgalia">FitWithGalia</a>
<p style="font-size: large; text-align: center"><a href = "Jrab.galia@gmail.com?subject = Training Session = Hello! I would like to schedule a training session with you on XX/XX/XXXX at XX:XX"><img src="gmail.png"  height="60px" width="90px"></a> Or send me a mail me on: <a href = "Jrab.galia@gmail.com?subject = Training Session = Hello! I would like to schedule a training session with you on XX/XX/XXXX at XX:XX">Jrab.galia@gmail.com</a>



  <!--BOOTSTRAP js IMPORT --> 
  
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous"></script>
        
</body>

</html>

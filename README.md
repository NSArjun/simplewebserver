# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:

    
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ISRO</title>
    </head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
    a{
    color: red;
    padding: 10px;
    text-decoration: none;
    font-size: 20px;
    font-weight: 200;

    }
    a:hover
    {
    color: burlywood;
    text-decoration: dotted red;
    }

    </style>
    <body style="background-image: url('psuje1ek.png');background-size: cover;">
    <div style="display: flex;">
    <div style="width: 40%;">
     <img src="ISRO LOGO.png" style="width: 100%;">
    </div>
    <div style="width: 50%;">
        <a href="">HOME</a>
        <a href="">OUR MISSIONS</a>
        <a href="">ARCHIVES</a>
        <a href="">GOALS</a>
        <a href="">IND2020</a>
        <a href="">CONTACT</a>
    </div>
    <div style="width: 10%;">
        <img src="ISRO.png" style="width: 100%;">
    </div>
     </div>
     <h1 style="color: red; font-size: 50px ;">ISRO,Indian Space Research Organisation</h1>
     <h1 style="color: orange; font-size: 20px ;">ISRO, the Indian Space Research Organisation, <br>   pioneers space exploration and satellite technology, 
    propelling India's advancements in space science and satellite communication,  <br> making strides towards 
    unlocking the mysteries of the cosmos and enhancing global connectivity.</h1>
    <div style="display: flex; text-align: center;align-items: stretch; ">
      <div class="card" style="width: 18rem; margin: 10px;">
    <img src="C1.webp" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">CHANDRAYAN 3</h5>
      <p class="card-text">ISRO successfully returns the Chandrayaan-3 Propulsion Module (PM) 
        to Earth's orbit after surpassing lunar mission objectives.
         The mission aimed to showcase a soft landing near the lunar 
         south polar region using the Vikram Lander and Pragyaan

       </p>
      <a href="http://timesofindia.indiatimes.com/articleshow/105735162.cms?utm_source=contentofinterest&utm_medium=text&utm_campaign=cppst" class="btn btn-primary">READ MORE</a>
    </div>
      </div>
     <div class="card" style="width: 18rem; margin: 10px;">
    <img src="C2.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">PM Modi reveals names of 4 astronauts for Gaganyaan mission      </h5>
      <p class="card-text">Prime Minister Narendra Modi on Tuesday announced the names of the four astronauts
         that will fly to low-Earth orbit as part of the Indian Space Research Organisation’s
         (ISRO) Gaganyaan, which will be the first crewed Indian space mission.</p>
      <a href="https://indianexpress.com/article/technology/science/four-gaganyaan-astronauts-announced-9183379/" class="btn btn-primary">READ MORE</a>
    </div>
      </div>  
    <div class="card" style="width: 18rem; margin: 10px;">
    <img src="C3.webp" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Aditya L1 </h5>
      <p class="card-text">Aditya L1 Mission Highlights: The Indian Space Research Organisation (ISRO)'s 
        ambitious debut mission to study the Sun, Aditya L1, will reach its final destination on Saturday at 4pm. 
        ISRO will perform the final manoeuvre on Saturday to inject Aditya-L1 spacecraft 
        -- the first space-based Indian observatory to study the Sun.</p>
      <a href="https://www.livemint.com/science/news/aditya-l1-isros-first-sun-mission-live-space-based-indian-observatory-to-enter-final-halo-orbit-11704532260232.html" class="btn btn-primary">READ MORE</a>
    </div>
      </div>

    
    </div>
     
     <center><div style="width: 40%;" id="carouselExampleIndicators" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="5.webp" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="C2.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="4.jpeg" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div></center>
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    </body>
    </html>


## OUTPUT:
![alt text](<Screenshot 2024-03-26 103155.png>)
![alt text](<Screenshot 2024-03-26 103233.png>)

## RESULT:
The program for implementing simple webserver is executed successfully.

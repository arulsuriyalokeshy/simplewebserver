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
`````
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
  <div class="container">
    

    <nav class=" navbar navbar-expand-lg bg-body-tertiary ">
        <div class="container">
          <a class="navbar-brand" href="#"><span class="text-warning"><h2 style="background-color:white;color:black;">Hackers.in</h2></span></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              
              <li class="nav-item bg bi bi-house">
                <a class="nav-link color" href="home#">Home</a>
              </li>
              <li class="nav-item bg bi bi-sign-turn-slight-right">
                <a class="nav-link color" href="#about">About</a>
              </li>
               <li class="nav-item bg bi bi-person-workspace">
                <a class="nav-link color" href="#services">Services</a>
              </li>  
              <li class="nav-item bg bi bi-microsoft-teams">
                <a class="nav-link color" href="#team">Team</a>
              </li>
              <li  class="nav-item bg bi bi-whatsapp">
                <a class="nav-link color" href="#contact">Contact</a>
              </li>
              
              
            </ul>
            
          </div>
        </div>
      </nav>
<div>
<h1 class=" body p highlight italic  shadow  bi bi-exclamation-triangle text-success" style="background-color: black;color:crimson; textcolor:crimson">Welcome To Hacker page...</h1>


</div>


      <div id="carouselExampleCaptions" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="2.webp" class="d-block  img" alt="...">
            <div class="carousel-caption d-none d-md-block ">
              
            </div>
          </div>
          <div class="carousel-item">
            <img src="3.webp" class="d-block  img"  alt="...">
            <div class="carousel-caption d-none d-md-block">
              
            </div>
          </div>
          <div class="carousel-item">
            <img src="1.webp" class="d-block  img" alt="...">
            <div class="carousel-caption d-none d-md-block  ">
              
            
            </div>
          </div>
        </div>
        <h1 style="color:red;backgroungcolor:yellow" class="bg shadow">Defeating security one line of code at a time.</h1>
        
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
      
  
    

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
`````
## OUTPUT:

![image](https://github.com/arulsuriyalokeshy/simplewebserver/assets/149130151/e48a16bd-9673-4eb3-89d8-5fe86986e152)

## RESULT:
The program for implementing simple webserver is executed successfully.

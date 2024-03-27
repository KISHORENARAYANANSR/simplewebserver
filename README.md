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
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
         a{
            color: crimson; 
            padding: 30px;
            text-decoration: none;
        }
        a:hover{
            color: gray;
        
        }

    </style>

</head>


<body style="background-image: url('black.avif');background-size: 100%;background-attachment: fixed;"> <br><br> >
    <div style="display: flex;">
        <div>
            <img src="mec logo.png">
        </div>
        <div style="padding: 5px;">
            
            <a href="">Our Models</a>
            <a href="">Buy Online</a>
            <a href="">Fine</a>
            <a href="">Service</a>
            <a href="">Our Brand</a><hr/></div><br>
        </div>
        
        <div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="mec pic2.png" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="2.png" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="3.3.jpg" class="d-block w-100" alt="...">
            </div>
            
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
<div style="display: flex;padding: 10px;margin-right: 10px;">
  <div class="card" style="width: 18rem;margin-right: 10px;">
    <img src="a class.png" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">A Class</h5>
      <p class="card-text">Starting from  £30,705</p>
      <a href="https://www.mercedes-benz.co.in/passengercars/models/saloon/eqs/overview.html" class="btn btn-primary">More</a>
    </div>
</div>

          <div class="card" style="width: 18rem;margin-right: 10px;">
              <img src="a class.png" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">A Class</h5>
                <p class="card-text">Starting from  £30,705</p>
                <a href="https://www.mercedes-benz.co.in/passengercars/models/saloon/eqs/overview.html" class="btn btn-primary">More</a>
              </div>
          </div>

          <div class="card" style="width: 18rem;margin-right: 10px;">
                <img src="c class 2.webp" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">C Class</h5>
                  <p class="card-text">Starting from ₹58,60,000.0</p>
                  <a href="https://www.mercedes-benz.co.in/passengercars/models/saloon/eqs/overview.html" class="btn btn-primary">More</a>
                </div>
          </div>

          <div class="card" style="width: 18rem;margin-right: 10px;">
                  <img src="e class.png" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">E Class</h5>
                    <p class="card-text">Starting from $63,350</p>
                    <a href="https://www.mercedes-benz.co.in/passengercars/models/saloon/eqs/overview.html" class="btn btn-primary">More</a>
                  </div>
                </div>

                <div class="card" style="width: 18rem;margin-right: 10px;">
                  <img src="s class.jpg" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">S Class</h5>
                    <p class="card-text">Starting from $118,450</p>
                    <a href="https://www.mercedes-benz.co.in/passengercars/models/saloon/eqs/overview.html" class="btn btn-primary">More</a>
                  </div>
                </div>
         
        </div>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
        </div>
</div>
</body>
</html>


## OUTPUT:
![alt text](<Screenshot 2024-03-26 160245.png>)
![alt text](<Screenshot 2024-03-26 160331.png>)

## RESULT:
The program for implementing simple webserver is executed successfully.

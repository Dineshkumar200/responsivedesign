# Design of Responsive Website
## AIM:
To design a responsive website with two break points.

## DESIGN STEPS:
### Step 1: 
Requirement collection.
### Step 2:
Creating the layout using HTML and CSS.
### Step 3:
Updating the sample content.
### Step 4:
Choose the appropriate style and color scheme.
### Step 5:
Validate the layout in various browsers.
### Step 6:
Validate the HTML code.
### Step 7:
Create a database model and migrate the database.
### Step 8:
Retrieve data from database and display it in a dynamic webpage.
### Step 9:
Publish the website in the given URL.

## PROGRAM:
### responsive.html
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Responsive Design</title>
</head>

<body>
    <div class="jumbotron">
        <div class="container text-center">
            <h1 class="display-1">Dinesh Electronic Private Limited</h1>
            <p class="lead">We Manufacture high quality Electronic products</p>
        </div>

    </div>
    <div class="container">
        <div class="row text-center">
            <div class="col-12 col-md-3"><a href="#">Home</a></div>
            <div class="col-12 col-md-3"><a href="#">People</a></div>
            <div class="col-12 col-md-3"><a href="#">products</a></div>
            <div class="col-12 col-md-3"><a href="#">Contact us</a></div>
        </div>
        <div class="row text-center">
            <div class="col-12">
                <p class="lead">Our Premium Products</p>
            </div>
        </div>
    
 
        <div class="row text-center">
            <div class="card col-12 col-md-6 col-lg-3 ">
               <img class="card-img-top" src="/static/img/c6.jpg" alt="Card image cap">
                <div class="card-body">

                <h5 class="card-title">Mivi USB Type C, USB OTG Adapter</h5>
                <p class="card-text">Price: 399.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
                </div>
        </div>
    
        <div class="card col-12 col-md-6 col-lg-3 ">
               <img class="card-img-top" src="/static/img/c2.jpg" alt="Card image cap">
                <div class="card-body">

                <h5 class="card-title">1TB Laptop HDD</h5>
                <p class="card-text">Price: Rs.5000.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
                </div>
        </div>
    
    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/c3.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">boAt Airdopes 131 Bluetooth Headset (Active Black, True Wireless)</h5>
                <p class="card-text">price: Rs.1299</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>


    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m1.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">Boult Audio Thunder Bluetooth Headset</h5>
                <p class="card-text">Price: Rs.1299.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>


    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m2.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">Gigabyte NVIDIA GeForce GT 710 2 GB DDR3 Graphics Card</h5>
                <p class="card-text">Price: Rs.3299.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>

    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m4.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">Casio FX-991ES Plus-2nd Edition Scientific Scientific</h5>
                <p class="card-text">Price: Rs.1087.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>


    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m3.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">CSD-255-21 Combo Box Analog Watch</h5>
                <p class="card-text">Price: Rs.330.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>


    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m5.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">Regatech PA5108U-1BRS, PA5109U-1BRS, PA5110U 6 Cell Lap</h5>
                <p class="card-text">Price: Rs.2750.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>


    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m8.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">Canon EOS 3000D DSLR Camera Single Kit with 18-55 lens (16 GB Memory Card & Carry
                    Case) (Black)</h5>
                <p class="card-text">Price: Rs.27835.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>


    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m6.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">15 inch Expandable Laptop Backpack</h5>
                <p class="card-text">Price: Rs.459.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>


    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/m7.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">Pitambara USB Type C to 3 Port USB 3.0 and Lan RJ45</h5>
                <p class="card-text">Price: Rs.1249.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>
    

    
        <div class="card col-12 col-md-6 col-lg-3">
            <img class="card-img-top" src="/static/img/c8.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">Paybox 10g-50Kg Digital Hanging Luggage Fishing Weight Scale Weighing Scale</h5>
                <p class="card-text">price: Rs.250.00</p>
                <a href="#" class="btn btn-primary">More Details</a>
            </div>
        </div>
        </div>
    
    </div>
 


        <div class="row text-center">
            <div class="card col-12">
                <p>Copyright © 2020 Dinesh Electronic Private Limited, Developed by Dineshkumar V.</p>
            </div>
        </div>


        <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
            integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
            crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
            integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
            crossorigin="anonymous"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
            integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
            crossorigin="anonymous"></script>
</body>

</html>
```


## OUTPUT:
![output](./static/img/s1.jpg)

![output](./static/img/s2.jpg)

![output](./static/img/s3.jpg)
![output](./static/img/s5.jpg)


## CODE VALIDATION REPORT
![output](./static/img/s4.jpg)


## RESULT:
Thus a responsive website designed with two break points  and is hosted in the URL http://dineshkumar.student.saveetha.in:8000/responsiveproducts/ HTML code is validated.
# Project Responsive Web Design using Bootstrap
## Date:17.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bata</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .navbar {
      background-color: blue;
    }
    .navbar a, .navbar-brand {
      color: white !important;
    }
    .banner {
      background-color: #d9534f;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    .card img {
      height: 150px;
      object-fit: cover;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #555;
    }
  </style>
</head>
<body>

 
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">bata</a>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link" href="#">Orders</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Cart</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Account</a></li>
        </ul>
        <div class="d-flex">
          <a href="#" class="nav-link text-white">Sign up</a>
          <a href="#" class="nav-link text-white">Sign in</a>
        </div>
      </div>
    </div>
  </nav>

  
  <div class="banner">
    <p>What are you looking for? bata is awesome platform to buy anything</p>
    <button class="btn btn-primary">Learn More</button>
    <button class="btn btn-light">Sign up</button>
  </div>

  
  <div class="container text-center mt-4 mb-3">
    <button class="btn btn-light dropdown-toggle me-2">Recent</button>
    <button class="btn btn-light dropdown-toggle me-2">Popular</button>
    <button class="btn btn-light dropdown-toggle">Filters</button>
  </div>

  
  <div class="container">
    <div class="row justify-content-center g-4">
      <div class="col-md-2 col-sm-4">
        <div class="card">
          <img src="Screenshot (93).png" class="card-img-top" alt="Shoe for men">
          <div class="card-body text-center">
            <p class="card-text">shoe for men</p>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-4">
        <div class="card">
          <img src="Screenshot (94).png" class="card-img-top" alt="Boots">
          <div class="card-body text-center">
            <p class="card-text">boots</p>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-4">
        <div class="card">
          <img src="Screenshot (95) - Copy.png" class="card-img-top" alt="Crocs">
          <div class="card-body text-center">
            <p class="card-text">crocs</p>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-4">
        <div class="card">
          <img src="Screenshot (96).png" class="card-img-top" alt="Slippers for girls">
          <div class="card-body text-center">
            <p class="card-text">Slippers for girls</p>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-4">
        <div class="card">
          <img src="Screenshot (97).png" class="card-img-top" alt="Girls shoe">
          <div class="card-body text-center">
            <p class="card-text">girls shoe</p>
          </div>
        </div>
      </div>

      <div class="col-md-2 col-sm-4">
        <div class="card">
          <img src="Screenshot (98).png" class="card-img-top" alt="School shoe">
          <div class="card-body text-center">
            <p class="card-text">school shoe</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  
  <footer>
     Designed by Lavanya.D(25016895)
  </footer>

  
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<bata image.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

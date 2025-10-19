# Project Responsive Web Design using Bootstrap
## Date:19.10.2025

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
  <title>DRIBBLE</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-info">

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">DRIBBLE</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
          <li class="nav-item"><a class="btn btn-primary ms-3" href="#">explore</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="text-center bg-secondary py-4">
    <div class="container">
      <h1 class="display-6">Slippers makes a perfect outfit</h1>
      <p class="lead display-7">SLIPPERS GIVES A CONFIDENT </p>
      <a href="#" class="btn btn-danger btn-md ">login</a>
      <a href="#" class="btn btn-success btn-lg ">sign up</a>
    </div>
  </section>

  <section class="py-4">
    <div class="container">
      <h2 class="mb-4 text-center text-primary">SLIPPERS</h2>
      <div class="row g-3 justify-content-center">
        
        <div class="col-md-3 ">
          <div class="card">
            <img src="Screenshot (93).png"class="card-img-top" alt="image 1" style="height:190px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 ">
          <div class="card">
            <img src="Screenshot (94).png" class="card-img-top" alt="image 2" style="height:190px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3">
          <div class="card">
            <img src="Screenshot (95).png" class="card-img-top" alt="image 3" style="height:190px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 ">
          <div class="card">
            <img src="Screenshot (97).png" class="card-img-top" alt="image 4" style="height:190px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 ">
          <div class="card">
            <img src="Screenshot (98).png" class="card-img-top" alt="image 5" style="height:190px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 ">
          <div class="card">
            <img src="Screenshot (96).png" class="card-img-top" alt="image 6" style="height:190px; object-fit:cover;">
          </div>
        </div>


      </div>
    </div>
  </section>


  <footer class="text-warning text-center bg-primary py-3">
    <p> &COPY; LAVANYA D(25016895)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-10-19 231310.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

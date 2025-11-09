# Project Responsive Web Design using Bootstrap
## Date:09.11.2025

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
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dribbble Clone</title>

  <!-- Bootstrap CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    body {
      margin: 0;
      padding: 0;
    }

    /* Hero Section */
    .hero {
      height: 90vh;
      background-size: cover;
      background-position: center;
      position: relative;
    }

    .hero::before {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.45);
    }

    .hero .container {
      position: relative;
      z-index: 2;
    }

    /* Join Section */
    .join {
      background-color: #e63946;
    }

    /* Footer */
    footer {
      background-size: cover;
      background-position: center;
      position: relative;
    }

    footer .overlay {
      background: rgba(0, 0, 0, 0.6);
    }

    /* Hover effect on cards */
    .card:hover {
      transform: scale(1.03);
      transition: 0.3s ease;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-white shadow-sm fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navmenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link text-danger fw-semibold" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero text-center text-white d-flex align-items-center" style="background-image: url('hero.jpg');">
    <div class="container">
      <h1 class="fw-bold display-5">Discover the World’s Top Designers</h1>
      <p class="lead mt-3">Join the largest creative community to share, grow, and get inspired.</p>
      <a href="#" class="btn btn-light mt-3 px-4 fw-semibold">Explore Now</a>
    </div>
  </section>

  <!-- Trending Shots Section -->
  <section class="container py-5">
    <h2 class="text-center fw-bold mb-4">Trending Shots</h2>
    <div class="row g-4">
      <div class="col-md-4 col-sm-6">
        <div class="card border-0 shadow-sm">
          <img src="image1.jpg" class="card-img-top" alt="Design 1">
          <div class="card-body text-center">
            <h5 class="card-title">Modern UI Design</h5>
            <p class="text-muted mb-0">By Designer A</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card border-0 shadow-sm">
          <img src="image2.jpg" class="card-img-top" alt="Design 2">
          <div class="card-body text-center">
            <h5 class="card-title">Creative Dashboard</h5>
            <p class="text-muted mb-0">By Designer B</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card border-0 shadow-sm">
          <img src="image3.jpg" class="card-img-top" alt="Design 3">
          <div class="card-body text-center">
            <h5 class="card-title">App Concept</h5>
            <p class="text-muted mb-0">By Designer C</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Join Section -->
  <section class="join text-center text-white py-5 bg-danger">
    <div class="container">
      <h2 class="fw-bold">Join Our Community Today!</h2>
      <p class="mt-3">Showcase your creativity and get noticed by top brands.</p>
      <a href="#" class="btn btn-light px-4 mt-2 fw-semibold">Sign Up Free</a>
    </div>
  </section>

  <!-- Footer -->
  <footer style="background-image: url('footer-bg.jpg');">
    <div class="overlay text-center text-white py-4">
      <p class="mb-0">&copy; 2025 Dribbble Clone. All rights reserved.</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2025-11-09 110231.png>)
![alt text](<Screenshot 2025-11-09 110247.png>)
![alt text](<Screenshot 2025-11-09 110258.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

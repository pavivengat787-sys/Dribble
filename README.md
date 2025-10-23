# Project Responsive Web Design using Bootstrap
## Date: 15.10.2025

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
# HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dribbble Clone (Bootstrap)</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-white shadow-sm sticky-top">
    <div class="container">
      <a class="navbar-brand text-pink fw-bold fs-3" href="#">dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
        </ul>
        <div class="d-flex">
          <button class="btn btn-outline-secondary me-2">Sign in</button>
          <button class="btn btn-pink">Sign up</button>
        </div>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="text-center py-5 hero-bg">
    <div class="container">
      <h1 class="fw-bold mb-4">Discover the world’s top designers & creatives</h1>
      <div class="input-group w-75 mx-auto">
        <input type="text" class="form-control" placeholder="Search for design inspiration...">
        <button class="btn btn-pink px-4">Search</button>
      </div>
    </div>
  </section>

  <!-- Shots Grid -->
  <section class="py-5">
    <div class="container">
      <div class="row g-4">
        <!-- Repeat for random images -->
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=1" class="card-img-top" alt="shot">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=2" class="card-img-top" alt="shot">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=3" class="card-img-top" alt="shot">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=4" class="card-img-top" alt="shot">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=5" class="card-img-top" alt="shot">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=6" class="card-img-top" alt="shot">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=7" class="card-img-top" alt="shot">
          </div>
        </div>
        <div class="col-6 col-md-4 col-lg-3">
          <div class="card shot-card">
            <img src="https://picsum.photos/400/300?random=8" class="card-img-top" alt="shot">
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-4 bg-white text-center shadow-sm">
    <p class="mb-0 text-muted">© 2025 Dribbble Clone — For educational use only.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

# CSS:
```css
body {
  background-color: #f8f7f4;
  font-family: "Poppins", sans-serif;
}

.text-pink {
  color: #ea4c89 !important;
}

.btn-pink {
  background-color: #ea4c89;
  color: white;
  border: none;
}

.btn-pink:hover {
  background-color: #d63c7b;
  color: white;
}

.hero-bg {
  background: linear-gradient(180deg, #fff, #f8f7f4);
}

.shot-card {
  border: none;
  border-radius: 12px;
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.shot-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);
}

```

## OUTPUT:
<img width="1919" height="1038" alt="image" src="https://github.com/user-attachments/assets/8d97705d-9f5d-4d5b-890e-ae570ce3a7fd" />



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

# Project Responsive Web Design using Bootstrap
## Date:30/05/2025

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
    <title>Dribbble Clone</title>

  
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
   
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign in</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="hero-section text-white text-center py-5" style="background-color: #ff5e5b;">
        <h1>Welcome to Dribbble</h1>
        <p>Explore design inspiration and showcase your work</p>
        <a href="#" class="btn btn-light btn-lg">Get Started</a>
    </div>

    <div class="content-section bg-light py-5">
        <div class="container text-center">
            <h2>Featured Designs</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="Health app.jpg" class="card-img-top" alt="Design 1" style="max-height: 250px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title">Health app</h5>
                            <p class="card-text">A beautiful minimalist design concept.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="Sky adventures.jpg" class="card-img-top" alt="Design 2" style="max-height: 250px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title">Sky adventures</h5>
                            <p class="card-text">Explore a vibrant and modern look for mobile apps.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="Club edge.jpg" class="card-img-top" alt="Design 3" style="max-height: 250px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title">Club edge</h5>
                            <p class="card-text">Creative concepts for website layouts.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="content-section py-5">
        <div class="container text-center">
            <h2>Popular Designers</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="Designer-1.jpg" class="card-img-top" alt="Designer 1" style="max-height: 250px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title">Prabhas</h5>
                            <p class="card-text">A renowned designer with expertise in web design.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="Designer-2.jpg" class="card-img-top" alt="Designer 2" style="max-height: 250px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title">keerthy Suresh</h5>
                            <p class="card-text">Known for creating stunning branding designs.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="Designer-3.jpg" class="card-img-top" alt="Designer 3" style="max-height: 250px; object-fit: cover;">
                        <div class="card-body">
                            <h5 class="card-title">Ram Charan</h5>
                            <p class="card-text">Specializes in mobile and app design.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

  
    <footer class="footer bg-dark text-white text-center py-3">
        <p>&copy; 2025 RAJU D</p>
    </footer>

   
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
</body>

</html>


```

## OUTPUT:
![Screenshot (122)](https://github.com/user-attachments/assets/9a04f1df-a49f-46d7-9028-c3584388ee68)
![Screenshot (123)](https://github.com/user-attachments/assets/6871e45e-07f9-4230-a57e-009eaa987adf)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

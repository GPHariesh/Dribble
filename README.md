# Project Responsive Web Design using Bootstrap
## Date:30-12-24

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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .header-bar {
            background-color: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        .header-bar a {
            color: #ff4785;
            font-weight: bold;
        }

        .design-card img {
            border-radius: 8px;
            width: 70%;
            margin-left:50px;
        }

        .design-card .card-footer {
            font-size: 0.9rem;
            background-color: #f7f7f7;
            text-align: center;
        }
    </style>
</head>

<body>
   
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Designers</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Teams</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Jobs</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-primary btn-sm" href="#">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

  
    <div class="header-bar">
        <h2>What are you working on? Dribbble is show and tell for designers.</h2>
        <a href="#" class="btn btn-light btn-sm">Learn more</a>
        <a href="#" class="btn btn-pink btn-sm">Sign up</a>
    </div>

   
    <div class="container py-4">
        <h3 class="mb-4">Popular Shots</h3>
        <div class="row g-4">
            
            <div class="col-md-3">
                <div class="card design-card">
                    <img src="images.jpeg" alt="Design 1" class="card-img-top">
                    <div class="card-footer">
                        <p>Four plus studio</p>
                        <small><i class="bi bi-eye"></i> 4,044 | <i class="bi bi-heart"></i> 290</small>
                    </div>
                </div>
            </div>
          
            <div class="col-md-3">
                <div class="card design-card">
                    <img src="2p.png" alt="Design 2" class="card-img-top">
                    <div class="card-footer">
                        <p>Balgan brothers</p>
                        <small><i class="bi bi-eye"></i> 2,404 | <i class="bi bi-heart"></i> 236</small>
                    </div>
                </div>
            </div>
           
            <div class="col-md-3">
                <div class="card design-card">
                    <img src="3p.png" alt="Design 3" class="card-img-top">
                    <div class="card-footer">
                        <p>King of wisdom</p>
                        <small><i class="bi bi-eye"></i> 3,885 | <i class="bi bi-heart"></i> 264</small>
                    </div>
                </div>
            </div>
          
            <div class="col-md-3">
                <div class="card design-card">
                    <img src="4p.png" alt="Design 4" class="card-img-top">
                    <div class="card-footer">
                        <p>Roman reigns</p>
                        <small><i class="bi bi-eye"></i> 2,602 | <i class="bi bi-heart"></i> 186</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card design-card">
                    <img src="5p.png" alt="Design 4" class="card-img-top">
                    <div class="card-footer">
                        <p>Studio-JQ</p>
                        <small><i class="bi bi-eye"></i> 2,602 | <i class="bi bi-heart"></i> 186</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card design-card">
                    <img src="6p.png" alt="Design 4" class="card-img-top">
                    <div class="card-footer">
                        <p>Muti</p>
                        <small><i class="bi bi-eye"></i> 2,602 | <i class="bi bi-heart"></i> 186</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```


## OUTPUT:
![alt text](<Screenshot (11).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

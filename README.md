<!DOCTYPE html>
<html lang=“en”>
<head>
    <meta charset=“UTF-8”>
    <meta name=“viewport” content=“width=device-width, initial-scale=1.0”>
    <link rel=“stylesheet” type=“text/css” href=“style.css”> 
    <link href=“https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css” rel=“stylesheet” integrity=“sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC” crossorigin=“anonymous”>   
    <title>CoolGadgets | Ecommerce Website</title>
</head>
<body>
 <!--- CSS -->
<link rel="stylesheet" type="text/css" href="style.css">

  <!--- Bootstrap -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">  
<body>
    <header class="bg-light">
        <div class="container">
            <nav class="navbar navbar-expand-lg navbar-light">
                <a class="navbar-brand" href="/">
                    <img src="img/logo.png" alt="CoolGadgets Logo" width="120">
                </a>
                <div class="collapse navbar-collapse">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li class="nav-item"><a class="nav-link" href="/">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="products.html">Products</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                        <li class="nav-item"><a class="nav-link" href="cart.html"><i class="fas fa-shopping-cart"></i></a></li>
                    </ul>
                </div>
            </nav>
        </div>
    </header>
</body>
/* Navigation */
.navbar-collapse .navbar-nav .nav-item a:hover {
    color: #ff523b; /* Changes the color of navigation links to orange when hovered over */
}

.cart-item {
    margin-bottom: 1rem; /* Provides a margin below the cart item for separation */
}

/* Media queries for responsive adjustments */
@media (max-width: 768px) {
    .banner-image {
        min-height: 300px; /* Adjusts the banner image's minimum height for smaller devices */
    }
} 
<link href=“https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css” rel=“stylesheet”>
<a href=“#”><i class=“fas fa-shopping-cart”></i></a>
 <!--- Banner -->
 <section class="container-fluid">
    <div class="row">
        <div class="col-md-6 d-flex align-items-center justify-content-center bg-warning text-white p-5">
            <div>
                <h1>Discover the Future With CoolGadgets!</h1>
                <p class="mb-4"><em>Innovation is not solely about major discoveries.<br>It's about constantly challenging the status quo.</em></p>
                <a href="products.html" class="btn btn-light btn-lg">Shop Now &#10142;</a>
            </div>
        </div>
        <div class="col-md-6 banner-image"></div>
    </div>
</section>
/* Banner */
.banner-image {
    background: url('img/banner.jpg') no-repeat center center / cover;
    min-height: 600px;<!--- Featured Products -->
    <div class="container my-5">
        <h2 class="text-center mb-4">Featured Products</h2>
        <div class="row row-cols-1 row-cols-md-2 row-cols-lg-4 g-4">
            <div class="col">
                <div class="card h-100">
                    <img src="img/product-1.jpg" class="card-img-top" alt="Product">
                    <div class="card-body">
                        <h5 class="card-title">Virtual Reality Glasses</h5>
                        <p class="card-text">$299.00</p>
                        <form action="cart.html" method="GET">
                            <input type="hidden" name="product" value="Virtual Reality Glasses">
                            <input type="hidden" name="price" value="299.00">
                            <input type="hidden" name="quantity" value="1">
                            <input type="submit" class="btn btn-warning" value="Add to Cart">
                        </form>
                    </div>
                </div>
            </div>
           <!--- Add More Products Here -->
        </div>
  </div>
 <hr>
 /* Feature Products Card */
.card-title a {
    color: #333; 
    text-decoration: none; 
}

.card-title a:hover {
    color: #ff523b;
}
<!--- New Product -->
<div class="container">
    <div class="row g-4">
        <div class="col-md-6">
            <img src="img/new-product.jpg" class="img-fluid" alt="New Product">
        </div>
        <div class="col-md-6 d-flex align-items-center">
            <div>
                <p>Our Newest Product Offer</p>
                <h1>Smart Ring</h1>
                <small>Track your fitness journey effortlessly with the Smart Ring, a sleek wearable that combines style and health monitoring right on your fingertip.</small>
                <br>
                <form action="cart.html" method="GET">
                    <input type="hidden" name="product" value="Smart Ring">
                    <input type="hidden" name="price" value="199.00">
                    <input type="hidden" name="quantity" value="1">
                    <input type="submit" class="btn btn-warning" value="Add to Cart">
                </form>
            </div>
        </div>
    </div>
</div>
<hr>
<!-- Contact Section -->
<section id="contact" class="container my-5">
    <div class="row">
        <div class="col-12 mb-4">
            <h2 class="text-center">Contact Us</h2>
        </div>
        <div class="col-md-8 mx-auto border rounded p-4 shadow-sm">
            <!-- Assuming you might want a form for the users to fill out -->
            <form>
                <div class="mb-3">
                    <label for="contactName" class="form-label">Name</label>
                    <input type="text" class="form-control" id="contactName" placeholder="Enter your name">
                </div>
                <div class="mb-3">
                    <label for="contactEmail" class="form-label">Email</label>
                    <input type="email" class="form-control" id="contactEmail" placeholder="Enter your email">
                </div>
                <div class="mb-3">
                    <label for="contactMessage" class="form-label">Message</label>
                    <textarea class="form-control" id="contactMessage" rows="3" placeholder="Your message"></textarea>
                </div>
                <button type="submit" class="btn btn-warning">Submit</button>
            </form>
        </div>
    </div>
</section>
<!--- Footer -->
<footer class="bg-dark text-light py-4">
    <div class="container">
        <div class="row">
            <div class="col-md-3">
                <img src="img/logo.png" alt="CoolGadgets Logo" class="mb-2" width="100">
                <p>Discover the Future <br> With CoolGadgets!</p>
            </div>
            <div class="col-md-3">
                <h3>Navigation</h3>
                <ul class="list-unstyled">
                    <li><a href="/" class="text-decoration-none text-light">Home</a></li>
                    <li><a href="products.html" class="text-decoration-none text-light">Products</a></li>
                    <li><a href="#contact" class="text-decoration-none text-light">Contact</a></li>
                </ul>
            </div>
            <div class="col-md-3">
                <h3>Useful Links</h3>
                <ul class="list-unstyled">
                    <li><a href="#" class="text-decoration-none text-light">Coupons</a></li>
                    <li><a href="#" class="text-decoration-none text-light">Blog Post</a></li>
                    <li><a href="#" class="text-decoration-none text-light">Return Policy</a></li>
                    <li><a href="#" class="text-decoration-none text-light">Join Affiliate</a></li>
                </ul>
            </div>
            <div class="col-md-3">
                <h3>Follow Us</h3>
                <ul class="list-unstyled">
                    <li><a href="#" class="text-decoration-none text-light">Facebook</a></li>
                    <li><a href="#" class="text-decoration-none text-light">Twitter</a></li>
                    <li><a href="#" class="text-decoration-none text-light">Instagram</a></li>
                    <li><a href="#" class="text-decoration-none text-light">YouTube</a></li>
                </ul>
            </div>
        </div>
        <hr class="my-4">
        <div class="text-center">&copy; Copyright 2023 - CoolGadgets Store</div>
    </div>
</footer>
<body>
    <header class="bg-light">
        <div class="container">
             <!--- Add Remaining Header  -->
        </div>
    </header>

    <!--- Products Section -->
    <div class="container my-5">
        <h2 class="text-center mb-4">Our Products</h2>
        <div class="row row-cols-1 row-cols-md-2 row-cols-lg-4 g-4">
            <!-- Product 1 -->
            <div class="col">
                <div class="card h-100">
                    <img src="img/product-1.jpg" class="card-img-top" alt="Virtual Reality Glasses">
                    <div class="card-body">
                        <h5 class="card-title">Virtual Reality Glasses</h5>
                        <p class="card-text">$299.00</p>
                        <form action="cart.html" method="GET">
                            <input type="hidden" name="product" value="Virtual Reality Glasses">
                            <input type="hidden" name="price" value="299.00">
                            <input type="hidden" name="quantity" value="1">
                            <input type="submit" class="btn btn-warning" value="Add to Cart">
                        </form>
                    </div>
                </div>
            </div>
            <!-- Add any additional products here -->
            <div class="col">
                <div class="card h-100">
                    <img src="img/new-product.jpg" class="card-img-top" alt="Smart Ring">
                    <div class="card-body">
                        <h5 class="card-title">Smart Ring</h5>
                        <p class="card-text">$299.00</p>
                        <form action="cart.html" method="GET">
                            <input type="hidden" name="product" value="Smart Ring">
                            <input type="hidden" name="price" value="199.00">
                            <input type="hidden" name="quantity" value="1">
                            <input type="submit" class="btn btn-warning" value="Add to Cart">
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

   <!--- Footer -->
   <footer class="bg-dark text-light py-4">
            <!--- Add Remaining Footer -->
    </footer>
</body>
<body>
    <header class="bg-light">
        <div class="container">
          <!-- Add Remaining Header -->
        </div>
    </header>
    <header class="py-3">
        <div class="container">
            <h1>Your Shopping Cart</h1>
        </div>
    </header>

    <section class="container my-5">
        <div class="row">
            <div class="col-md-8">
                <!-- Cart Items List -->
                <div class="cart-item">
                    <div class="row">
                        <div class="col-md-3">
                            <img src="img/product-1.jpg" class="img-fluid" alt="Product">
                        </div>
                        <div class="col-md-5">
                            <h4>Virtual Reality Glasses</h4>
                            <p>$299.00</p>
                        </div>
                        <div class="col-md-2">
                            <input type="number" class="form-control" value="1">
                        </div>
                        <div class="col-md-2">
                            <button class="btn btn-danger">Remove</button>
                        </div>
                    </div>
                </div>
                <!-- Add more cart items here -->
            </div>

            <div class="col-md-4">
                <!-- Cart Summary -->
                <div class="border p-3 mb-3">
                    <h3 class="mb-3">Cart Summary</h3>
                    <div class="d-flex justify-content-between">
                        <span>Subtotal</span>
                        <span>$299.00</span>
                    </div>
                    <div class="d-flex justify-content-between">
                        <span>Tax</span>
                        <span>$23.92</span>
                    </div>
                    <div class="d-flex justify-content-between">
                        <span>Total</span>
                        <span>$322.92</span>
                    </div>
                    <button class="btn btn-warning w-100 mt-3">Proceed to Checkout</button>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-dark text-light py-4 mt-5">
        <div class="container text-center">
            &copy; Copyright 2023 - CoolGadgets Store
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-PPmltI4DzdaNfQz9JdGpI3TZfvlw7irzjBn3wKgNmCUp0auj/uTPmSy7Ou1EP9J4" crossorigin="anonymous"></script>
</body>
 
 
}

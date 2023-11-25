# igorcislali.github.io
world of soccer
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Soccer Website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="styles.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Soccer Website</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#home">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#teams">Teams</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- Home Section -->
<section id="home" class="py-5 text-center">
  <div class="container">
    <h1>Welcome to the World of Soccer</h1>
    <p>Explore the passion, excitement, and history of the beautiful game!</p>
    <img src="soccer-ball.gif" alt="Soccer Ball" class="https://stock.adobe.com/md/search?k=soccer+balls+clip+art&asset_id=213338964" style="max-width: 300px;">
  </div>
</section>

<!-- About Section -->
<section id="about" class="bg-light py-5">
  <div class="container">
    <h2 class="text-center mb-4">About Soccer</h2>
    <p>Soccer, also known as football in most countries, is a popular sport played by millions worldwide. It involves two teams of eleven players each, trying to score goals by kicking a ball into the opponent's net.</p>
    
  </div>
</section>

<!-- Teams Section -->
<section id="teams" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Top Soccer Teams</h2>
   
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="bg-dark text-white py-5">
  <div class="container">
    <h2 class="text-center mb-4">Contact Us</h2>
   
  </div>
</section>

<!-- Footer -->
<footer class="bg-light text-center py-3">
  <div class="container">
    <p>&copy; 2023 Soccer Website. All rights reserved.</p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
CSS (styles.css):

css
Copy code
/* Custom styles */

/* Change background color for sections */
section {
  padding: 60px 0;
}

/* Style the home section */
#home {
  background-color: #f8f9fa;
}

/* Style the about section */
#about {
  background-color: #e9ecef;
}

/* Style the contact section */
#contact {
  background-color: #343a40;
}

/* Change text color in the footer */
footer {
  color: #6c757d;
}

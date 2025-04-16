# Nutrihealth
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Nutrihealth - Healthy Recipes</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Nutrihealth</h1>
      <p>Your daily dose of healthy, tasty recipes</p>
    </div>
  </header>
  <nav class="navbar">
    <div class="container">
      <a href="#">Home</a>
      <a href="#">Recipes</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </div>
  </nav>
  <main class="container">

    <!-- Example recipe card (copy/paste this for each recipe) -->
    <section class="blog-post">
      <h2>Avocado Toast with a Twist</h2>
      <p><em>Posted on April 13, 2025</em></p>
      <img src="images/avocado-toast.jpg" alt="Avocado Toast with a Twist" />
      <p>A tasty, protein-rich take on classic avocado toast, perfect for a nutritious start.</p>
      <a href="posts/avocado-toast.html">Read more</a>
    </section>

    <!-- Add more recipes below... -->

  </main>
  <footer>
    <div class="container">
      <p>&copy; 2025 Nutrihealth. Eat well, live well.</p>
    </div>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f8f8f8;
  color: #333;
}

header {
  background-color: #4CAF50;
  color: white;
  padding: 2rem 0;
  text-align: center;
}

.navbar {
  background-color: #eee;
  padding: 1rem 0;
  text-align: center;
}

.navbar a {
  margin: 0 1rem;
  text-decoration: none;
  color: #4CAF50;
  font-weight: bold;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 2rem 0;
}

.blog-post {
  background: white;
  padding: 1rem;
  margin-bottom: 2rem;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.blog-post img {
  max-width: 100%;
  height: auto;
  border-radius: 5px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem 0;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Avocado Toast with a Twist - Nutrihealth</title>
    <link rel="stylesheet" href="../style.css">
</head>
<body>
    <div class="container">
        <h1>Avocado Toast with a Twist</h1>
        <p><em>Posted on April 13, 2025</em></p>
        <img src="../images/avocado-toast.jpg" alt="Avocado Toast with a Twist" />
        <p>This delicious twist on the classic avocado toast includes chickpeas and lemon zest to boost protein and flavor. Quick, easy, and satisfying!</p>
        <p><a href="../index.html">Back to Home</a></p>
    </div>
</body>
</html>

<!-- Advanced Website Template with Animated Logo -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Buracod</title>
  <style>
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background: #add8e6; color: #000; }
    header { background: rgba(0, 0, 0, 0.7); backdrop-filter: blur(5px); color: white; padding: 2rem; text-align: center; position: relative; overflow: hidden; }
    .logo { position: absolute; top: 10px; left: 20px; font-size: 1.5rem; font-weight: bold; background: white; color: #4CAF50; padding: 0.5rem 1rem; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.2); animation: slideIn 1.5s ease-out forwards; opacity: 0; }
    @keyframes slideIn {
      0% { transform: translateX(-100px); opacity: 0; }
      100% { transform: translateX(0); opacity: 1; }
    }
    nav { background: rgba(0, 0, 0, 0.7); backdrop-filter: blur(5px); padding: 0.5rem; text-align: center; }
    nav a { color: white; margin: 0 1rem; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    main { padding: 2rem; display: flex; flex-wrap: wrap; justify-content: center; gap: 2rem; }
    .card { background: white; padding: 1.5rem; width: 300px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); border-radius: 10px; transition: transform 0.3s ease; }
    .card:hover { transform: translateY(-5px); }
    button { background: #4CAF50; border: none; color: white; padding: 0.75rem 1.5rem; border-radius: 5px; font-size: 1rem; cursor: pointer; }
    button:hover { background: #45a049; }
    footer { background: rgba(0, 0, 0, 0.7); backdrop-filter: blur(5px); color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
  </style>
</head>
<body>

  <header>
    <div class="logo">Buracod</div>
    <h1>Welcome to Buracod</h1>
    <p>Explore the features and have fun!</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <div class="card">
      <h2>About Us</h2>
      <p>We are passionate about building beautiful websites. Let us help you create your online presence.</p>
      <button onclick="alert('Thanks for clicking!')">Learn More</button>
    </div>
    <div class="card">
      <h2>Our Services</h2>
      <p>We offer web design, development, and SEO optimization to make your brand stand out online.</p>
      <button onclick="alert('We will contact you soon!')">Get Started</button>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 Buracod | Designed with ❤️</p>
  </footer>

</body>
</html>

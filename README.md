<!-- Advanced Website Template with Lessons Section -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Buracod</title>
  <style>
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background: #add8e6; color: #333; scroll-behavior: smooth; }

    header { 
      background: linear-gradient(to right, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.3)), url('header-background.jpg'); 
      background-size: cover;
      color: white; 
      padding: 4rem 2rem; 
      text-align: center; 
      position: relative; 
      overflow: hidden; 
      border-bottom: 5px solid #fff;
    }

    .logo { 
      position: absolute; 
      top: 20px; 
      left: 30px; 
      font-size: 2rem; 
      font-weight: bold; 
      background: rgba(0, 0, 0, 0.5); 
      color: #fff; 
      padding: 1rem 2rem; 
      border-radius: 10px; 
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5); 
      animation: fadeIn 1s ease-out forwards; 
      opacity: 0; 
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(-50px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    h1, p { 
      margin: 0.5rem 0; 
      font-size: 2.5rem; 
      text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5); 
    }

    p { font-size: 1.2rem; max-width: 800px; margin: 1rem auto; line-height: 1.6; }

    .btn { 
      background: #4CAF50; 
      border: none; 
      color: white; 
      padding: 1rem 2rem; 
      border-radius: 5px; 
      font-size: 1.2rem; 
      cursor: pointer; 
      margin-top: 1.5rem;
      transition: background 0.3s ease; 
    }

    .btn:hover { background: #45a049; }

    .about-section { 
      background: #fff; 
      padding: 3rem 2rem; 
      text-align: center; 
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
      margin: 3rem auto; 
      border-radius: 12px; 
      width: 80%; 
      max-width: 1000px;
    }

    .about-section h2 { 
      font-size: 2.5rem; 
      color: #333; 
      margin-bottom: 1rem; 
    }

    .about-section p { 
      font-size: 1.1rem; 
      color: #555; 
      max-width: 800px; 
      margin: 1.5rem auto; 
      line-height: 1.7; 
    }

    .about-section img { 
      width: 80%; 
      max-width: 400px; 
      border-radius: 10px; 
      margin-top: 2rem; 
    }

    .lesson-section { 
      background: #fff; 
      padding: 4rem 2rem; 
      text-align: center; 
      margin-top: 3rem; 
    }

    .lesson-section h2 { 
      font-size: 2.5rem; 
      color: #333; 
      margin-bottom: 1.5rem; 
    }

    .lesson-cards { 
      display: grid; 
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); 
      gap: 2rem;
    }

    .lesson-card { 
      background: #f9f9f9; 
      padding: 2rem; 
      border-radius: 10px; 
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
      transition: transform 0.3s ease; 
    }

    .lesson-card:hover { 
      transform: translateY(-10px); 
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); 
    }

    .lesson-card h3 { 
      font-size: 1.8rem; 
      color: #4CAF50; 
      margin-bottom: 1rem; 
    }

    .lesson-card p { 
      font-size: 1rem; 
      color: #555; 
      margin-bottom: 1.5rem; 
    }

    .lesson-card a { 
      background: #4CAF50; 
      color: white; 
      padding: 0.8rem 1.5rem; 
      text-decoration: none; 
      border-radius: 5px; 
      font-size: 1rem; 
      transition: background 0.3s ease; 
    }

    .lesson-card a:hover { background: #45a049; }

    footer { 
      background: rgba(0, 0, 0, 0.7); 
      color: white; 
      text-align: center; 
      padding: 1rem; 
      margin-top: 2rem; 
    }

  </style>
</head>
<body>

  <header>
    <div class="logo">Buracod</div>
    <h1>Welcome to Buracod</h1>
    <p>Your go-to place for exceptional coding tutorials and resources.</p>
    <button class="btn" onclick="window.location.href='#about'">Learn More</button>
  </header>

  <section class="about-section" id="about">
    <h2>About Us</h2>
    <p>We are passionate about coding and building exceptional digital experiences. Our mission is to empower learners by providing high-quality tutorials, coding tools, and a supportive community. Whether you're just starting or looking to sharpen your skills, Buracod is here to help you achieve your goals.</p>
    <img src="about-image.jpg" alt="Coding image">
    <button class="btn" onclick="alert('Stay tuned for more updates!')">Join Us</button>
  </section>

  <!-- Lessons Section -->
  <section class="lesson-section" id="lessons">
    <h2>Our Coding Lessons</h2>
    <div class="lesson-cards">
      <div class="lesson-card">
        <h3>HTML Basics</h3>
        <p>Learn the foundational building blocks of web development with HTML, from basic tags to creating structured web pages.</p>
        <a href="https://www.w3schools.com/html/" target="_blank">Start Learning</a>
      </div>
      <div class="lesson-card">
        <h3>CSS Styling</h3>
        <p>Enhance the look and feel of your website with CSS. Learn how to apply styles, manage layouts, and design responsive web pages.</p>
        <a href="https://www.w3schools.com/css/" target="_blank">Start Learning</a>
      </div>
      <div class="lesson-card">
        <h3>JavaScript Basics</h3>
        <p>Unlock the power of interactive web pages by learning JavaScript. Cover variables, functions, and events for dynamic behavior.</p>
        <a href="https://www.w3schools.com/js/" target="_blank">Start Learning</a>
      </div>
      <div class="lesson-card">
        <h3>Responsive Design</h3>
        <p>Learn how to build websites that look great on all devices using responsive design techniques with CSS media queries.</p>
        <a href="https://www.w3schools.com/css/css_rwd_intro.asp" target="_blank">Start Learning</a>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Buracod | Designed with ❤️</p>
  </footer>

</body>
</html>
<!-- Advanced Website Template with Enhanced Intro and About Us -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Buracod</title>
  <style>
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background: #add8e6; color: #333; scroll-behavior: smooth; }
    
    header { 
      background: linear-gradient(to right, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.3)), url('header-background.jpg'); 
      background-size: cover;
      color: white; 
      padding: 4rem 2rem; 
      text-align: center; 
      position: relative; 
      overflow: hidden; 
      border-bottom: 5px solid #fff;
    }

    .logo { 
      position: absolute; 
      top: 20px; 
      left: 30px; 
      font-size: 2rem; 
      font-weight: bold; 
      background: rgba(0, 0, 0, 0.5); 
      color: #fff; 
      padding: 1rem 2rem; 
      border-radius: 10px; 
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5); 
      animation: fadeIn 1s ease-out forwards; 
      opacity: 0; 
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(-50px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    h1, p { 
      margin: 0.5rem 0; 
      font-size: 2.5rem; 
      text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5); 
    }

    p { font-size: 1.2rem; max-width: 800px; margin: 1rem auto; line-height: 1.6; }

    .btn { 
      background: #4CAF50; 
      border: none; 
      color: white; 
      padding: 1rem 2rem; 
      border-radius: 5px; 
      font-size: 1.2rem; 
      cursor: pointer; 
      margin-top: 1.5rem;
      transition: background 0.3s ease; 
    }

    .btn:hover { background: #45a049; }

    .about-section { 
      background: #fff; 
      padding: 3rem 2rem; 
      text-align: center; 
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
      margin: 3rem auto; 
      border-radius: 12px; 
      width: 80%; 
      max-width: 1000px;
    }

    .about-section h2 { 
      font-size: 2.5rem; 
      color: #333; 
      margin-bottom: 1rem; 
    }

    .about-section p { 
      font-size: 1.1rem; 
      color: #555; 
      max-width: 800px; 
      margin: 1.5rem auto; 
      line-height: 1.7; 
    }

    .about-section img { 
      width: 80%; 
      max-width: 400px; 
      border-radius: 10px; 
      margin-top: 2rem; 
    }

    footer { 
      background: rgba(0, 0, 0, 0.7); 
      color: white; 
      text-align: center; 
      padding: 1rem; 
      margin-top: 2rem; 
    }

  </style>
</head>
<body>

  <header>
    <div class="logo">Buracod</div>
    <h1>Welcome to Buracod</h1>
    <p>Your go-to place for exceptional coding tutorials and resources.</p>
    <button class="btn" onclick="window.location.href='#about'">Learn More</button>
  </header>

  <section class="about-section" id="about">
    <h2>About Us</h2>
    <p>We are passionate about coding and building exceptional digital experiences. Our mission is to empower learners by providing high-quality tutorials, coding tools, and a supportive community. Whether you're just starting or looking to sharpen your skills, Buracod is here to help you achieve your goals.</p>
    <img src="about-image.jpg" alt="Coding image">
    <button class="btn" onclick="alert('Stay tuned for more updates!')">Join Us</button>
  </section>

  <footer>
    <p>&copy; 2025 Buracod | Designed with ❤️</p>
  </footer>

</body>
</html>
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

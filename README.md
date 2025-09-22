# Task-1
This is my first task of Web Development.
# Task 1:   Create a Simple Responsive Landing Page Using HTML & CSS.
## Here's the html code :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Landing Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="logo">TechnoWorld</div>
    <nav>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">Features</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Welcome to TechnoWorld</h1>
      <p>Your gateway to modern web experiences.</p>
      <a href="#" class="cta-button">Get Started</a>
    </div>
  </section>

  <footer>
    <p>Follow us:</p>
    <div class="social-links">
      <a href="#">Twitter</a>
      <a href="#">Facebook</a>
      <a href="https://www.instagram.com/elevatelabs.official?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==">Instagram</a>
      <a href="https://www.linkedin.com/company/elevate-labs-llc/posts/?feedView=all">LinkedIn</a>
    </div>
  </footer>
</body>
</html>
```
## Here's the css code :
```
/* Reset and base styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.logo {
  padding-left: 70px;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

/* Hero Section */
.hero {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 80vh;
  background: linear-gradient(to right, #0077cc, #00c6ff);
  color: white;
  text-align: center;
  padding: 0 20px;
}

.hero-content h1 {
  font-size: 3rem;
  margin-bottom: 20px;
}

.hero-content p {
  font-size: 1.2rem;
  margin-bottom: 30px;
}

.cta-button {
  padding: 12px 24px;
  background-color: #fff;
  color: #0077cc;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
  transition: background 0.3s ease;
}

.cta-button:hover {
  background-color: #e0e0e0;
}

/* Footer */
footer {
  background-color: #fff;
  padding: 20px;
  text-align: center;
  box-shadow: 0 -2px 4px rgba(0,0,0,0.1);
}

.social-links {
  margin-top: 10px;
}

.social-links a {
  margin: 0 10px;
  text-decoration: none;
  color: #0077cc;
}

/* Responsive */
@media (max-width: 768px) {
  .nav-links {
    flex-direction: column;
    gap: 10px;
  }

  .hero-content h1 {
    font-size: 2rem;
  }

  .hero-content p {
    font-size: 1rem;
  }
}
```

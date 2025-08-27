<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>GuruShala - Empowering Education</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
  <style>
    body {
      padding: 0;
      margin: 0;
    }
    main.container {
      padding: 3rem 1rem;
    }
    figure img {
      border-radius: 8px;
      max-height: 350px;
      object-fit: cover;
      width: 100%;
    }
    footer {
      margin-top: 2rem;
      text-align: center;
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav class="container-fluid">
    <ul>
      <li><strong>GuruShala</strong></li>
    </ul>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Programs</a></li>
      <li><a href="#" role="button">Get Started</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <main class="container">
    <div class="grid">
      <section>
        <hgroup>
          <h2>Welcome to GuruShala</h2>
          <h3>Empowering Education, Inspiring Growth</h3>
        </hgroup>
        <p>
          GuruShala is an innovative educational initiative designed to bridge the gap between knowledge and accessibility. Our mission is to provide high-quality, affordable, and scalable learning solutions for students and educators worldwide.
        </p>
        <figure>
          <img src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=1200&q=80" alt="Students studying together" />
          <figcaption>
            <a href="https://unsplash.com/photos/three-persons-sitting-on-bench-using-laptop-computers-2jiEE9YkYbg" target="_blank">Photo from Unsplash</a>
          </figcaption>
        </figure>

        <h3>Our Vision</h3>
        <p>
          To make education accessible, inclusive, and impactful by blending technology with traditional learning methods.
        </p>

        <h3>Our Programs</h3>
        <p>
          We provide a wide range of educational resources, mentorship programs, digital courses, and workshops to support learners and educators in achieving their goals.
        </p>
      </section>
    </div>
  </main>

  <!-- Subscribe Section -->
  <section aria-label="Subscribe example">
    <div class="container">
      <article>
        <hgroup>
          <h2>Join the GuruShala Community</h2>
          <h3>Stay updated with our latest initiatives</h3>
        </hgroup>
        <form class="grid">
          <input type="text" id="firstname" name="firstname" placeholder="Your name" aria-label="Your name" required />
          <input type="email" id="email" name="email" placeholder="Your email" aria-label="Your email" required />
          <button type="submit" onclick="event.preventDefault()">Subscribe</button>
        </form>
      </article>
    </div>
  </section>

  <!-- Footer -->
  <footer class="container">
    <small>
      <a href="#">Privacy Policy</a> • <a href="#">Terms of Service</a>
    </small>
  </footer>
</body>
</html>

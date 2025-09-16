# Newsletter-
huma project
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Newsletter App</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Bootstrap Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">

  <style>
    .quote-icon {
      font-size: 4rem;
      color: #ccc;
      line-height: 0.5;
      position: absolute;
      top: 1rem;
      left: 1rem;
    }
    .testimonial-card {
      background-color: #fff;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      position: relative;
    }
    .testimonial-card p {
      font-style: italic;
      margin-bottom: 1.5rem;
    }
    .testimonial-info {
      display: flex;
      align-items: center;
    }
    .testimonial-info img {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      margin-right: 1rem;
    }
    .quote-section {
      background-color: #f8f9fa;
    }
    .footer-cta {
      background-color: #1a1a1a;
    }
    .footer-cta .text-content {
      padding: 3rem;
      color: #fff;
    }
    .footer-cta .image-content img {
      max-width: 100%;
      height: auto;
    }
    .newsletter-app {
      color: #0d6efd;
    }
    .newsletter-app-plus {
      color: #dc3545;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light py-3">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">
        <span class="newsletter-app">NEWSLETTER</span><span class="newsletter-app-plus">+++</span>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">How it works</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Why Newsletter-App?</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Pricing</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Blog</a></li>
          <li class="nav-item"><a class="nav-link btn btn-success text-white" href="#">Login</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="py-5 bg-light">
    <div class="container">
      <div class="row align-items-center flex-column-reverse flex-md-row">
        <div class="col-md-6 text-center text-md-start mb-4 mb-md-0">
          <h1 class="display-5 fw-bold mb-3">Bring back the joy of reading newsletters</h1>
          <p class="lead mb-4">Discover, subscribe and manage all your favorite newsletters in one place, with an amazing experience</p>
          <a href="#" class="btn btn-primary btn-lg">TRY FOR FREE</a>
        </div>
        <div class="col-md-6 text-center">
          <img src="./1.png" alt="Newsletter Hero" class="img-fluid rounded">
        </div>
      </div>
    </div>
  </section>

  <!-- Features -->
  <section class="py-5">
    <div class="container">
      <div class="row text-center mb-5">
        <div class="col-12">
          <h2 class="fw-bold">Why Newsletter-App? How to enjoy your feed?</h2>
          <p class="lead">Be ready for an amazing experience.</p>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-md-4 mb-4">
          <div class="card p-3 text-center border-0">
            <h5 class="fw-bold">Kill The Spam</h5>
            <p>No more subscribing with your personal email. Enjoy a clean inbox and stress-free reading.</p>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card p-3 text-center border-0">
            <h5 class="fw-bold">One-Click Unsubscription</h5>
            <p>Unsubscribe from unwanted newsletters with a single click and focus on what matters.</p>
          </div>
        </div>
      </div>
      <div class="row justify-content-center align-items-center mt-5">
        <div class="col-md-4 mb-4 text-center">
          <h5 class="fw-bold">Re-Sort Newsletter Feeds</h5>
          <p>Sort newsletters for a clean and simple feed with just one click.</p>
        </div>
        <div class="col-md-4 mb-4 text-center">
          <img src="./n.jpg" alt="Phone App" class="img-fluid rounded">
        </div>
        <div class="col-md-4 mb-4 text-center">
          <h5 class="fw-bold">Control Your Feed</h5>
          <p>Group newsletters into folders, so you only see what you want, when you want.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="py-5 quote-section">
    <div class="container text-center">
      <h2 class="fw-bold">Enjoy reading newsletters</h2>
      <p class="lead mb-5">Read valuable, high-quality content based on your interest and expertise</p>
      <div class="row">
        <div class="col-md-4">
          <div class="testimonial-card mb-4">
            <span class="quote-icon">“</span>
            <p>"This app completely changed how I read my newsletters. So clean and easy!"</p>
            <div class="testimonial-info">
              <img src="./44.jpg" alt="User 1">
              <div>
                <p class="mb-0 fw-bold">Aisha Khan</p>
                <small class="text-muted">Marketing Manager</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="testimonial-card mb-4">
            <span class="quote-icon">“</span>
            <p>"Finally a place to organize everything. I save so much time now."</p>
            <div class="testimonial-info">
              <img src="./ii.jpg" alt="User 2">
              <div>
                <p class="mb-0 fw-bold">David Lee</p>
                <small class="text-muted">CEO</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="testimonial-card mb-4">
            <span class="quote-icon">“</span>
            <p>"A must-have if you’re subscribed to a lot of newsletters like me!"</p>
            <div class="testimonial-info">
              <img src="./68.jpg" alt="User 3">
              <div>
                <p class="mb-0 fw-bold">Maria Gomez</p>
                <small class="text-muted">CTO</small>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer CTA -->
  <section class="footer-cta py-5">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6 text-content">
          <h2 class="fw-bold">Bring back the joy of reading newsletters</h2>
          <p>Organize your newsletter feeds and be ready for an amazing experience</p>
          <ul class="list-unstyled">
            <li><i class="bi bi-check-circle-fill text-success me-2"></i> Save time with an amazing experience</li>
            <li><i class="bi bi-check-circle-fill text-success me-2"></i> Organize your newsletters</li>
            <li><i class="bi bi-check-circle-fill text-success me-2"></i> Forget about newsletter emails</li>
          </ul>
          <a href="#" class="btn btn-success btn-lg mt-3">TRY NOW</a>
        </div>
        <div class="col-md-6 image-content text-center">
          <img src="./back.jpg" alt="App Preview" class="img-fluid rounded">
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-5 bg-dark text-white">
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <h5>Get Started</h5>
          <ul class="list-unstyled">
            <li><a href="#" class="text-white text-decoration-none">Blog</a></li>
            <li><a href="#" class="text-white text-decoration-none">Pricing</a></li>
          </ul>
        </div>
        <div class="col-md-3">
          <h5>Pricing</h5>
          <ul class="list-unstyled">
            <li><a href="#" class="text-white text-decoration-none">Standard</a></li>
            <li><a href="#" class="text-white text-decoration-none">Premium</a></li>
          </ul>
        </div>
        <div class="col-md-3">
          <h5>Platform</h5>
          <ul class="list-unstyled">
            <li><a href="#" class="text-white text-decoration-none">LinkedIn</a></li>
            <li><a href="#" class="text-white text-decoration-none">Facebook</a></li>
          </ul>
        </div>
      </div>
      <hr class="mt-4 border-white">
      <div class="d-flex flex-column flex-md-row justify-content-between align-items-center pt-3">
        <p class="mb-0">© 2025 All Rights Reserved.</p>
        <div class="d-flex mt-2 mt-md-0">
          <a href="#" class="me-3 text-white text-decoration-none">Privacy Policy</a>
          <a href="#" class="me-3 text-white text-decoration-none">Terms of Service</a>
        </div>
        <a href="#" class="btn btn-success mt-2 mt-md-0">NEWSLETTER+++</a>
      </div>
    </div>
  </footer>

  <!-- Bootstrap Bundle (for navbar toggler only, no custom JS needed) -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
![44](https://github.com/user-attachments/assets/967ce383-ad19-46f1-b5cd-87d08f01b99c)
![ii](https://github.com/user-attachments/assets/0875130a-5ce9-40b6-9622-953c1f0a1a39)
<img width="1056" height="992" alt="1" src="https://github.com/user-attachments/assets/6d9252f5-b452-4e1c-b82c-9113756bb08d" />

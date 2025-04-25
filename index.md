---
layout: front
title: Home
---

<!-- Hero Section -->
<section class="hero">
  <div class="container">
    <h1 class="display-4">The Prudence Missing in Your R&D</h1>
    <p class="lead">Empowering Gen AI & Spatial Analytics with precision and insight.</p>
    <a href="#projects" class="btn btn-primary btn-lg me-2">Explore Projects</a>
    <a href="#contact" class="btn btn-outline-light btn-lg">Get in Touch</a>
  </div>
</section>

<!-- About Section -->
<section id="about" class="container py-5">
  <h2 class="section-title text-center">About Prudencier</h2>
  <p class="text-center">We are an R&D-driven company focused on delivering intelligent solutions using Generative AI, Spatial Data Science, and Data Engineering. Our goal is to bridge the gap between cutting-edge research and real-world applications.</p>
</section>

<!-- Projects Section -->
<section id="projects" class="container py-5">
  <h2 class="section-title text-center">R&D Projects</h2>
  <div class="row">
    <div class="col-md-4">
      <div class="card project-card">
        <img src="{{ site.baseurl }}/img/project1.jpg" class="card-img-top" alt="Crop Yield Optimizer">
        <div class="card-body">
          <h5 class="card-title">Crop Yield Optimizer</h5>
          <p class="card-text">ML-driven platform suggesting optimal crops based on soil and climate data.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card project-card">
        <img src="{{ site.baseurl }}/img/project2.jpg" class="card-img-top" alt="Geo Risk Assessment">
        <div class="card-body">
          <h5 class="card-title">Geo Risk Assessment</h5>
          <p class="card-text">Spatial models to calculate risk for property insurance underwriting.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card project-card">
        <img src="{{ site.baseurl }}/img/project3.jpg" class="card-img-top" alt="AI Document Assistant">
        <div class="card-body">
          <h5 class="card-title">AI Document Assistant</h5>
          <p class="card-text">Chatbot that extracts insights from unstructured PDF documents using LLMs.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Local App Section -->
<section id="service" class="container py-5">
  <h2 class="section-title text-center">Local Service App</h2>
  <div class="text-center">
    <p>We're building a smart app to connect residents with trusted local service providers — from plumbers to electricians. Launching soon!</p>
    <a href="#" class="btn btn-warning">Join the Waitlist</a>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="container py-5">
  <h2 class="section-title text-center">Contact Us</h2>
  <div class="row justify-content-center">
    <div class="col-md-6">
      <form>
        <div class="mb-3">
          <label for="name" class="form-label">Name</label>
          <input type="text" class="form-control" id="name">
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email">
        </div>
        <div class="mb-3">
          <label for="message" class="form-label">Message</label>
          <textarea class="form-control" id="message" rows="4"></textarea>
        </div>
        <button type="submit" class="btn btn-dark">Send Message</button>
      </form>
    </div>
  </div>
</section>

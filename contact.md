---
layout: front
title: Contact
---

<section id="contact" class="container py-5">
  <h2 class="section-title text-center">Contact Us</h2>
  <div class="row justify-content-center">
    <div class="col-md-6">
      <form action="https://formspree.io/f/your-form-id" method="POST">
        <div class="mb-3">
          <label for="name" class="form-label">Name</label>
          <input type="text" class="form-control" id="name" name="name" required>
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" name="email" required>
        </div>
        <div class="mb-3">
          <label for="message" class="form-label">Message</label>
          <textarea class="form-control" id="message" name="message" rows="4" required></textarea>
        </div>
        <button type="submit" class="btn btn-dark">Send Message</button>
      </form>
    </div>
  </div>
</section>

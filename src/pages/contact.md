---
layout: ../layouts/MarkdownLayout.astro
title: Contact Us
---

# Contact Us

Fill out the form below to get in touch with us.

<form action="/submit" method="POST" class="contact-form">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="4" required></textarea>

  <button type="submit">Submit</button>
</form>

<style>
  .contact-form-container {
    max-width: 600px;
    margin: 0 auto;
    padding: 2rem;
    background-color: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .contact-form label {
    display: block;
    margin: 1rem 0 0.5rem;
  }

  .contact-form input,
  .contact-form textarea {
    width: 100%;
    padding: 0.5rem;
    margin-bottom: 1rem;
    border: 1px solid #ddd;
    border-radius: 4px;
  }

  .contact-form button {
    display: block;
    width: 100%;
    padding: 0.75rem;
    background-color: #007BFF;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }

  .contact-form button:hover {
    background-color: #0056b3;
  }
</style>

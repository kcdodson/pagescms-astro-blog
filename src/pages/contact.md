---
layout: ../layouts/ContactLayout.astro
title: "MeMy"
---

I'd love to hear from you! Whether you have a question, want to collaborate, or just want to say hi, feel free to reach out using any of the methods below.

<div class="my-6">
  <img src="/assets/contact.svg" class="sm:w-1/2 mx-auto" alt="contact illustration">
</div>

## Get in Touch

- 📧 Email: [yourname@example.com](mailto:yourname@example.com)
- 🐦 Twitter: [@yourhandle](https://twitter.com/yourhandle)
- 💼 LinkedIn: [Your Name](https://linkedin.com/in/yourname)
- 🌐 Website: [yourwebsite.com](https://yourwebsite.com)

## Contact Form

<form 
  action="https://api.web3forms.com/submit" 
  method="POST" 
  class="flex flex-col gap-4 max-w-full mx-auto text-white"
>
  <!-- Replace with your actual Web3Forms access key -->
  <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">

  <label class="flex flex-col">
    Your Name:
    <input type="text" name="name" class="border p-2 rounded w-full" required>
  </label>

  <label class="flex flex-col">
    Your Email:
    <input type="email" name="email" class="border p-2 rounded w-full" required>
  </label>

  <label class="flex flex-col">
    Message:
    <textarea name="message" rows="5" class="border p-2 rounded w-full" required></textarea>
  </label>

  <!-- Optional: redirect after submit -->
  <input type="hidden" name="redirect" value="https://yourwebsite.com/thank-you">

  <button type="submit" class="px-4 py-2 rounded bg-blue-600 text-white hover:bg-blue-700">
    Send Message
  </button>
</form>

---

Looking forward to connecting with you!

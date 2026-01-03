---
layout: default
---

<section id="hero" class="py-32 px-6 text-center bg-gray-50">
  <h1 class="text-6xl font-semibold mb-4 tracking-tight">Amanda Lynn</h1>
  <p class="text-2xl text-gray-500 italic">Author & Storyteller</p>
</section>

<section id="books" class="max-w-6xl mx-auto py-24 px-6">
  <h2 class="text-4xl font-bold mb-20 text-center">The Collection</h2>
  
  <div class="grid md:grid-cols-2 gap-16 mb-40">
    <div class="sticky-container">
      <img src="{{ '/images/knowing-cover.jpg' | relative_url }}" class="rounded-3xl shadow-2xl w-full">
    </div>
    <div>
      <h3 class="text-4xl font-semibold mb-4">The Knowing</h3>
      <p class="text-red-600 font-bold mb-6">Published 2024</p>
      <p class="text-lg text-gray-600 leading-relaxed mb-8">Detailed blurb goes here. As the user scrolls, the image on the left stays in place while this text moves.</p>
      <div class="world-node">
        <h4 class="font-bold mb-2">Lore Note</h4>
        <p class="text-sm text-gray-500">Details about the world of The Knowing.</p>
      </div>
    </div>
  </div>
</section>

<section id="about" class="bg-gray-50 py-24 px-6">
  <div class="max-w-4xl mx-auto flex flex-col md:flex-row items-center gap-12">
    <img src="{{ '/images/bio-photo.jpg' | relative_url }}" class="w-64 h-64 rounded-full shadow-lg">
    <div>
      <h2 class="text-4xl font-bold mb-6">Meet the Author</h2>
      <p class="text-gray-600 text-lg">Your bio goes here. Keep it clean and sophisticated.</p>
    </div>
  </div>
</section>

<section id="contact" class="py-24 px-6 max-w-2xl mx-auto text-center">
  <h2 class="text-4xl font-bold mb-6">Get in Touch</h2>
  <p class="text-gray-500 mb-8">For inquiries or just to say hello, use the form below.</p>
  <form action="https://formspree.io/f/your-id" method="POST" class="space-y-4">
    <input type="email" name="email" placeholder="Your Email" class="w-full p-4 rounded-xl border border-gray-200 outline-none focus:ring-2 focus:ring-red-600">
    <textarea name="message" placeholder="Your Message" class="w-full p-4 rounded-xl border border-gray-200 h-32"></textarea>
    <button type="submit" class="bg-black text-white px-10 py-4 rounded-full font-bold hover:bg-gray-800">Send Message</button>
  </form>
</section>
